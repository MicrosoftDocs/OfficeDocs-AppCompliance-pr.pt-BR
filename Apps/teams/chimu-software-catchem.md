---
title: Informações do aplicativo para CatchEm by Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o CatchEm, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55b248c8f99e18d08ddf60dec177ce92b543f008
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552312"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 27 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Chimu Software à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CatchEm |
| ID | WA200002639 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Chimu Software |
| URL do site de parceiros | [https://www.chimusoftware.com](https://www.chimusoftware.com) |
| URL da página de informações do aplicativo Teams | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL da Política de Privacidade | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL de Termos de Uso | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Chimu Software sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | Delegada | Esta permissão é necessária para determinar os contatos de um usuário de aplicativo. AadObjectId: Para identificar com exclusividade um usuário. InquilinoS: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários do aplicativo. E-mail, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e permitir &quot; a funcionalidade do clique para &quot; conversar. Última ID de bate-papo: Para ativar &quot; a funcionalidade do clique para conversar &quot; | Esta permissão é necessária para determinar os contatos de um usuário de aplicativo. AadObjectId: Para identificar com exclusividade um usuário. InquilinoS: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários do aplicativo. E-mail, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e permitir &quot; a funcionalidade do clique para &quot; conversar. Última ID de bate-papo: Para ativar &quot; a funcionalidade do clique para conversar &quot; | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | Delegada | Para melhorar a precisão dos dados para contatos externos. DisplayName: para identificar contatos para usuários de aplicativos. | Para melhorar a precisão dos dados para contatos externos. DisplayName: para identificar contatos para usuários de aplicativos. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | Delegada | Contatos status de presença atual | Não disponível | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | ambos | Enviar notificações aos usuários quando um contato muda o status de presença | Não disponível | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | Delegada | Para habilitar atualizações automáticas para o aplicativo | Não disponível | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | Delegada | AadObjectId: Para identificar com exclusividade um usuário. InquilinoS: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários do aplicativo. E-mail, Endereços IM, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e permitir &quot; a funcionalidade do clique para &quot; conversar. CompanyName, País: Análise. AccountEnabled, DeletedDateTime: exclusão automática de dados do usuário para usuários com deficiência | AadObjectId: Para identificar com exclusividade um usuário. InquilinoS: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários do aplicativo. E-mail, Endereços IM, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e permitir &quot; a funcionalidade do clique para &quot; conversar. CompanyName, País: Análise. AccountEnabled, DeletedDateTime: exclusão automática de dados do usuário para usuários com deficiência | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | Delegada | Para melhorar a precisão dos dados para contatos internos. AadObjectId: Para identificar com exclusividade um usuário. InquilinoS: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários do aplicativo. E-mail, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e permitir &quot; a funcionalidade do clique para &quot; conversar. | Para melhorar a precisão dos dados para contatos internos. AadObjectId: Para identificar com exclusividade um usuário. InquilinoS: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários do aplicativo. E-mail, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e permitir &quot; a funcionalidade do clique para &quot; conversar. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | Delegada | Graph tokens de segurança, para permitir que o aplicativo notifique sobre as alterações de presença de contato e atualize as listas de contatos quando o usuário não estiver usando ativamente o aplicativo | tokens de segurança Graph | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| A &quot; funcionalidade da tag da mensagem precisa usar o nome de &quot; exibição do contato para mostrar ao usuário do aplicativo | O nome de exibição do contato | Para poder apresentar o nome do contato de volta ao usuário do aplicativo |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparecem nos aplicativos telemetria ou logs.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não disponível

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Chimu Software sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Sim |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Não |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
