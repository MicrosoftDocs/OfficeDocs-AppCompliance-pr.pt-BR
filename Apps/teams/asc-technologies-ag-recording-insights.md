---
title: Informações do aplicativo para registro do ASC Insights pela ASC Technologies AG
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o registro do asc Insights, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: efeac55591daa01827df42e8b473acdea8ee66f5
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276630"
---
# <a name="asc-recording-insights"></a>ASC Recording Insights

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/8f79287d-5850-42f1-9af2-48ddf6ef89a8" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000708" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela ASC Technologies AG à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ASC Recording Insights |
| ID | WA200000708 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | ASC Technologies AG |
| URL do site do parceiro | [https://asctechnologies.com/english/index.html](https://asctechnologies.com/english/index.html) |
| URL da página Teams de informações do aplicativo | [https://asctechnologies.com/english/ASC_Recording_Insights_...](https://asctechnologies.com/english/ASC_Recording_Insights_Compliance_Recording_for_Microsoft_Teams.html) |
| URL da Política de Privacidade | [https://teams.asc-recording.app/privacy](https://teams.asc-recording.app/privacy) |
| URL dos Termos de Uso | [https://asctechnologies.com/english/asc_impressum.html](https://asctechnologies.com/english/asc_impressum.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela ASC Technologies AG sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | aplicação | Informações das reuniões do usuário | ID do objeto das reuniões | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read | aplicação | Chats gerados dos usuários | ID do objeto dos chats | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read.All | aplicação | Chats gerados dos usuários | ID do objeto dos chats | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Group.Read.All | aplicação | Grupo de usuários do AD de associação | ID do objeto do grupo AD | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| OnlineMeetings.Read.All | aplicação | Informações das reuniões do usuário | ID do objeto das reuniões | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.Read | aplicação | Primeiros e últimos nomes de usuários | ID do objeto do usuário | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.ReadBasic.All | aplicação | Dados básicos do usuário | ID do objeto do usuário | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exportar API | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não temos dados nos sistemas do parceiro

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

Essas informações foram fornecidas pela ASC Technologies AG sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | ,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/> |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
