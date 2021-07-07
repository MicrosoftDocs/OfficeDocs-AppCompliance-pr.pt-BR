---
title: Informações do aplicativo para CatchEm by Chimu Software
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para CatchEm, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8f491e0b26c58392c2e791322603dc014fcf96ef
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281984"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 27 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Software Chimu para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CatchEm |
| ID | WA200002639 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Chimu Software |
| URL do site do parceiro | [https://chimusoftware.com](https://chimusoftware.com) |
| URL da página Teams de informações do aplicativo | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| URL da Política de Privacidade | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| URL dos Termos de Uso | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Software Chimu sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | delegado | Essa permissão é necessária para determinar os contatos de um usuário do aplicativo. AadObjectId: Para identificar exclusivamente um usuário. TenantId: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários de aplicativos. Email, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e para permitir que clique na funcionalidade &quot; de &quot; chat. ID mais recente do Chat: Para &quot; habilitar a funcionalidade de clique para chat &quot; | Essa permissão é necessária para determinar os contatos de um usuário do aplicativo. AadObjectId: Para identificar exclusivamente um usuário. TenantId: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários de aplicativos. Email, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e para permitir que clique na funcionalidade &quot; de &quot; chat. ID mais recente do Chat: Para &quot; habilitar a funcionalidade de clique para chat &quot; | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| People.Read | delegado | Para melhorar a precisão dos dados para contatos externos. DisplayName: para identificar contatos para usuários de aplicativos. | Para melhorar a precisão dos dados para contatos externos. DisplayName: para identificar contatos para usuários de aplicativos. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| Presence.Read.All | delegado | Status de presença atual de contatos | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsActivity.Send | ambos | Para enviar notificações aos usuários quando o status de presença de um contato muda | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegado | Para habilitar atualizações automáticas para o aplicativo | N/D | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.Read | delegado | AadObjectId: Para identificar exclusivamente um usuário. TenantId: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários de aplicativos. Email, Endereços de IM, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e para permitir que clique na funcionalidade &quot; de &quot; chat. CompanyName, País: Análise. AccountEnabled, DeletedDateTime: exclusão automática de dados do usuário para usuários desabilitados | AadObjectId: Para identificar exclusivamente um usuário. TenantId: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários de aplicativos. Email, Endereços de IM, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e para permitir que clique na funcionalidade &quot; de &quot; chat. CompanyName, País: Análise. AccountEnabled, DeletedDateTime: exclusão automática de dados do usuário para usuários desabilitados | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| User.ReadBasic.All | delegado | Para melhorar a precisão dos dados para contatos internos. AadObjectId: Para identificar exclusivamente um usuário. TenantId: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários de aplicativos. Email, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e para permitir que clique na funcionalidade &quot; de &quot; chat. | Para melhorar a precisão dos dados para contatos internos. AadObjectId: Para identificar exclusivamente um usuário. TenantId: para determinar se um contato é interno ou externo ao usuário. DisplayName, GivenName, Sobrenome: para identificar contatos para usuários de aplicativos. Email, UserPrincipalName: para ajudar a distinguir entre contatos com o mesmo nome e para permitir que clique na funcionalidade &quot; de &quot; chat. | fc686a41-3bd0-45b3-a56d-f278888fd694 |
>| offline_access | delegado | Graph tokens de segurança, para permitir que o aplicativo notifique as alterações de presença de contato e atualize listas de contatos quando o usuário não estiver usando ativamente o aplicativo | Graph tokens de segurança | fc686a41-3bd0-45b3-a56d-f278888fd694 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| A marca da funcionalidade da mensagem precisa usar o nome de exibição do contato &quot; para mostrar ao usuário do &quot; aplicativo | O nome de exibição do contato | Para poder apresentar o nome do contato de volta ao usuário do aplicativo |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Software Chimu sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Não |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
