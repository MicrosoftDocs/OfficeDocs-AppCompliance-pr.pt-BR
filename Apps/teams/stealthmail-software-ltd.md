---
title: Informações do aplicativo para o FurtivoMail da Furtivo Software Ltd
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o StealthMail, suas políticas de manipulação de dados, suas informações do catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a0a31e0eceafbaa4188587411503514692c4b743
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225555"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 31 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Exibir no Teams armazenamento</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Stealthmail Software Ltd para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | StealthMail |
| ID | WA200001748 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | Stealthmail Software Ltd |
| URL do site do parceiro | [https://stealthmail.com](https://stealthmail.com) |
| URL da página Teams informações do aplicativo | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| URL da Política de Privacidade | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| URL dos Termos de Uso | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela Stealthmail Software Ltd sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para coletar?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **Azure AD ID do aplicativo** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | Delegada | O aplicativo envia a mensagem para o canal com a referência no email seguro criado | nada | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| ChannelMessage.Send | Delegada | O aplicativo envia a mensagem para o canal com a referência no email seguro criado | nada | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| Chat.ReadWrite | Delegada | O aplicativo envia a mensagem para conversar com a referência no email seguro criado | nada | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| GroupMember.Read.All | Delegada | O aplicativo obtém membros do canal para tornar o email seguro para eles | nada | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.Read.All | Delegada | O aplicativo obtém membros do chat para tornar o email seguro para eles | nada | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| User.ReadBasic.All | Delegada | O aplicativo obtém membros do chat para tornar o email seguro para eles | nada | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |
>| email | Delegada | Autenticar usuário | nada armazenar no banco de dados | [1ed0a549-c730-44c7-a984-a8c658fe9807](../azure/1ed0a549-c730-44c7-a984-a8c658fe9807.md) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não são serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se esse aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao qual ela é adicionada. Esse aplicativo usa essa funcionalidade?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria dos aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>Não temos controle sobre os dados do parceiro em seus sistemas.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de todos os dados de OII (informações de identificação organizacional) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Stealthmail Software Ltd sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de identidade.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você integra-se ao Microsoft Identify Platform (Azure AD)?  | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa a MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multilocação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | – URIs de redirecionamento de curinga,<br/>- OAuth2 Flow implícito, a menos que seja necessário para um SPA<br/>- Fluxo ropc (credencial de senha do proprietário do recurso) |
| Seu aplicativo expõe alguma APIs Web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenha êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
