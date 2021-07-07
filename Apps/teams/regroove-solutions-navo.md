---
title: Informações do aplicativo para Navo por Soluções de Regroove
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Navo, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 11346ff15831615ac6b617d8d14f83f38c7de0a5
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283105"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Regroove Solutions para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Navo |
| ID | WA200001047 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Regroove Solutions |
| URL do site do parceiro | [https://regroove.ca ; https://getnavo.com](https://regroove.ca ; https://getnavo.com) |
| URL da Política de Privacidade | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| URL dos Termos de Uso | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Regroove Solutions sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicação | Armazenamos a contagem de usuários e consultamos-a uma vez por ciclo de cobrança. Também usamos a ID deenancy como a ID da organização. | Permite contar quantos usuários estão na área de trabalho, que usamos para fins de cobrança. Ele também nos permite consultar em quais grupos um usuário está, para que possamos usar a recortação de segurança para proteger determinados dados. Também consultamos a ID deenancy da organização. | 75ce4e02-e37b-479c-81c7-438348a2a251 |
>| User.Read | delegado | Nenhum dado armazenado | Entrar e ler o perfil do usuário | 75ce4e02-e37b-479c-81c7-438348a2a251 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Armazenamos a ID deenancy e a contagem de usuários em Stripe. |  | User.Read | Delegated | Entrar e ler o perfil do usuário - Nenhum dado armazenado |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, no Application Insights armazenamos a ID autenticada do usuário e a ID da Conta de Usuário (ID deenancy).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados que armazenamos (não por meio de um serviço como Stripe ou Aplicativo Insights) são armazenados em um banco de dados do Azure Cosmos. Todos os administradores usam 2FA e o acesso é restrito a um subconjunto de nossos funcionários.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

