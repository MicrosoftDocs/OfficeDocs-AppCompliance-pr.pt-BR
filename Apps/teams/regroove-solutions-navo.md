---
title: Informações de aplicação para Navo pela Regroove Solutions
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Navo, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ef2c71df0559a5a3db4612df5acf86835efe1a71
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553932"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Regroove Solutions à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Navo |
| ID | WA200001047 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Regroove Solutions |
| URL do site de parceiros | [https://getnavo.com](https://getnavo.com) |
| URL da Política de Privacidade | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| URL de Termos de Uso | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Regroove Solutions sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicação | Armazenamos a contagem de usuários e consultamos uma vez por ciclo de faturamento. Também usamos o ID de locação como iD para a organização. | Permite-nos contar quantos usuários estão no aluguel, que usamos para fins de faturamento. Ele também nos permite consultar em que grupos um usuário está, para que possamos usar o corte de segurança para proteger certos dados. Também consultamos o Id de locação da organização. | 75ce4e02-e37b-479c-81c7-438348a2a251 |
>| User.Read | Delegada | Sem dados armazenados | Entrar e ler o perfil do usuário | 75ce4e02-e37b-479c-81c7-438348a2a251 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Armazenamos o id de aluguel e a contagem de usuários no Stripe. |  | User.Read | Delegated | Faça login e leia o perfil do usuário - Sem dados armazenados |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, no Application Insights armazenamos o ID Autenticado do Usuário e o ID da Conta de Usuário (Tenancy Id).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados que armazenamos (não através de um serviço como Stripe ou Application Insights) são armazenados em um banco de dados Cosmos do Azure. Todos os administradores usam 2FA, e o acesso é restrito a um subconjunto de nossos funcionários.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

