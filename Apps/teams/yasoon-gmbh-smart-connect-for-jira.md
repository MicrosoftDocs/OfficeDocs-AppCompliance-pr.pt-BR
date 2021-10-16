---
title: Informações do aplicativo para Conexão para Jira pelo yasoon GmbH
ms.author: elmalova
author: elenamalova
ms.date: 07/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Smart Conexão para Jira, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4342897ef390842396e62798debc54e146a979e3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413252"
---
# <a name="smart-connect-for-jira"></a>Smart Connect para Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 21 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo yasoon GmbH para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Smart Connect para Jira |
| ID | WA200002055 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | yasoon GmbH |
| URL do site do parceiro | [https://www.yasoon.com](https://www.yasoon.com) |
| URL da página Teams de informações do aplicativo | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| URL da Política de Privacidade | [https://yasoon.com/privacy-policy-services/](https://yasoon.com/privacy-policy-services/) |
| URL dos Termos de Uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474846970/Product_42949680957/Asset_3f25ec80-eacb-454f-8cc2-eeee583b65c6/170825EULAOfficeaddinEN.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo yasoon GmbH sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | A permissão é usada para permitir que o usuário selecione um desses canais ingressado no Jira. | ID do canal, para fins de cache | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Read.Group | aplicação | Permite que o aplicativo mostre mensagens de canal vinculadas em Jira. | IDs de mensagem para vincular mensagens a problemas Jira | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Send | delegado | Nenhum dado é usado, essa API é usada para permitir que o usuário responda às mensagens de canal de Jira. | Nenhum | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelSettings.Read.Group | aplicação | Usado para procurar informações detalhadas sobre um canal. | Nenhum | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Chat.ReadWrite | delegado | Usado para permitir que o usuário adicione novas respostas a chats e exibir mensagens de chat de Jira. | Nenhum | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Member.Read.Group | aplicação | Usado para verificações de permissão, permite que o aplicativo valide a associação de equipe dos usuários. | Nenhum | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Team.ReadBasic.All | delegado | A permissão é usada para permitir que o usuário selecione uma dessas equipes ingressáveis no Jira. | IDs de equipe para fins de cache | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| TeamSettings.Read.Group | aplicação | Permite que o aplicativo leia as configurações de equipe para respeitar determinados padrões. | Nenhum | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| User.ReadBasic.All | delegado | Permite que o usuário selecione colegas de trabalho para @-mention em uma mensagem de canal | Nenhum | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| A Jira atlassiana e possivelmente um dos nossos contratados podem ser vistos aqui: https://go.yasoon.com/contractors | Metadados de mensagem (ids, timestamps), metadados de usuário e organizacionais (IDs de usuário, ids de organização) e endereços de email do usuário | Dando suporte à funcionalidade do aplicativo (por exemplo, correspondência de contas atlassianas com Office contas) e permitindo que nosso suporte solucione problemas mais rapidamente. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Correspondência da conta Teams usuários com a conta Jira do Atlassian dos usuários | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Metadados do usuário (id)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Trabalhamos apenas com serviços que oferecem garantias estritas de privacidade de dados. 

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo yasoon GmbH sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

