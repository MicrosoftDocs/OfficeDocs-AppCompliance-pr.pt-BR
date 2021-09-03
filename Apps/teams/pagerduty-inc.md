---
title: Informações do aplicativo para PagerDuty por PagerDuty, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para PagerDuty, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3729a9523ea4af31015f6e8111c6843e90d465f3
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873719"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 27 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por PagerDuty, Inc. para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | PagerDuty |
| ID | WA200001637 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | PagerDuty, Inc. |
| URL do site do parceiro | [https://www.pagerduty.com](https://www.pagerduty.com) |
| URL da página Teams de informações do aplicativo | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| URL da Política de Privacidade | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por PagerDuty, Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | delegado | A partir da criação/resposta de obter reuniões, estamos usando esses campos: join_web_url, audioConferencing. Esses campos são necessários para mostrar ao usuário um link para reuniões ou maneiras alternativas de se conectar na reunião. | Salvamos: join_web_url, audioConferencing. Esses campos são necessários para mostrar ao usuário um link para reuniões ou maneiras alternativas de se conectar na reunião. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | delegado | Usando para adicionar aplicativo pagerduty ao chat. | Usando para adicionar aplicativo pagerduty ao chat. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | delegado | Usando para adicionar aplicativo pagerduty ao chat. | Usando para adicionar aplicativo pagerduty ao chat. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | delegado | Usando para adicionar aplicativo pagerduty como uma guia na reunião | Usando para adicionar aplicativo pagerduty como uma guia na reunião | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | delegado | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | delegado | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são necessários para obter informações sobre reuniões de usuários e online | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são requred para obter informações sobre reuniões de usuários e online | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são requred para obter informações sobre o usuário e criar/obter reuniões online | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| perfil | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são requred para obter informações sobre o usuário e criar/obter reuniões online | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | delegado | A partir da criação/resposta de obter reuniões, estamos usando esses campos: join_web_url, audioConferencing. Esses campos são necessários para mostrar ao usuário um link para reuniões ou maneiras alternativas de se conectar na reunião. | Salvamos: join_web_url, audioConferencing. Esses campos são necessários para mostrar ao usuário um link para reuniões ou maneiras alternativas de se conectar na reunião. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | delegado | Usando para adicionar aplicativo pagerduty ao chat. | Usando para adicionar aplicativo pagerduty ao chat. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | delegado | Usando para adicionar aplicativo pagerduty ao chat. | Usando para adicionar aplicativo pagerduty ao chat. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | delegado | Usando para adicionar aplicativo pagerduty como uma guia na reunião | Usando para adicionar aplicativo pagerduty como uma guia na reunião | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | delegado | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | delegado | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | Os dados são usados: id, userPrincipalName . Ele é usado para fazer com que os usuários do Microsoft Teams os adicionem à reunião como participantes | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são necessários para obter informações sobre reuniões de usuários e online | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são necessários para obter informações sobre reuniões de usuários e online | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são requred para obter informações sobre o usuário e criar/obter reuniões online | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| perfil | delegado | Usando para solicitações de autorização e token. Os dados são usados: access_token, refresh_token, expires_in escopo | access_token, refresh_token, expires_in escopo. Esses dados são requred para obter informações sobre o usuário e criar/obter reuniões online | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Os dados que PagerDuty mantém estão limitados aos dados do computador de produtos de monitoramento e as informações de PII são limitadas a: endereço de email corporativo, nome, sobrenome e número de telefone. Uma lista de sub-processadores com acesso a esses dados pode ser encontrada aqui: https://www.pagerduty.com/subprocessors/ | Os dados que PagerDuty mantém estão limitados aos dados do computador de produtos de monitoramento e as informações de PII são limitadas a: endereço de email corporativo, nome, sobrenome e número de telefone. Uma lista de sub-processadores com acesso a esses dados pode ser encontrada aqui: https://www.pagerduty.com/subprocessors/ | Os dados que PagerDuty mantém estão limitados aos dados do computador de produtos de monitoramento e as informações de PII são limitadas a: endereço de email corporativo, nome, sobrenome e número de telefone. Uma lista de sub-processadores com acesso a esses dados pode ser encontrada aqui: Mais informações sobre privacidade de https://www.pagerduty.com/subprocessors/ dados podem ser encontradas aqui: https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>PagerDuty exige padrões de segurança de dados pelo menos tão rigorosos quanto os mantidos por PagerDuty para serem mantidos por todos os fornecedores com os quais transferimos dados, incluindo uma obrigação contratual na forma de uma DPA assinada. Mais informações sobre nossos padrões de segurança de dados podem ser encontradas aqui: https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela PagerDuty, Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
