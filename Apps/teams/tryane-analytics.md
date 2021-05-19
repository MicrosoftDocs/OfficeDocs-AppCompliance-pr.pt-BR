---
title: Informações do aplicativo para Tryane Analytics por Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Tryane Analytics, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551101"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 28 de setembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Tryane à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Tryane Analytics |
| ID | WA200001827 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Tryane |
| URL do site de parceiros | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL da Política de Privacidade | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL de Termos de Uso | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Tryane sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Read | aplicação |  | Leia todas as atividades dos usuários em equipes | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | aplicação |  | Todos liste todos os canais com nomes, descrições | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | aplicação |  | Liste todas as mensagens de canais&#8217; metadados | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | aplicação |  | Identifique usuários com uma licença de Equipe no inquilino | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | aplicação |  | Obtenha uma lista de todas as equipes, membros de&#8217;da equipe e membros ocultos | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | aplicação |  | Leia todas as atividades dos usuários em equipes | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | aplicação |  | Liste todos os canais e propriedades das equipes | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | Delegada | Identificação do usuário, nome, endereço de e-mail, data de criação. Armazenamos esses dados para fornecer análises de uso em Teams | Identifique o usuário atual durante a assinatura | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>A regra organizacional descrita em nossa política de segurança de TI e padrões de codificação nos impedem de ter euii e OII aparecendo nos registros

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Onde/Como: Banco de dados Azure/Azure para servidores PostgreSQL Who pode acessá-lo: nosso aplicativo e os administradores de banco de dados Controle de autorização: 
 - Controle de autorização individual: RBAC
 - Controle de autorização do sistema: pontos finais privados em redes virtuais azure

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

