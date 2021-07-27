---
title: Informações do aplicativo para mover o trabalho para frente com Jira pelo Move Work Forward
ms.author: elmalova
author: elenamalova
ms.date: 06/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Move Work Forward with Jira, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7120519c2ecb0643465760677b2bef895b1e2f4d
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521253"
---
# <a name="move-work-forward-with-jira"></a>Avançar o trabalho com Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 10 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/79ca2e8f-dd2c-40d5-897e-1b22d41038fe" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002855" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Move Work Forward para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Avançar o trabalho com Jira |
| ID | WA200002855 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Avançar o trabalho |
| URL do site do parceiro | [https://www.moveworkforward.com](https://www.moveworkforward.com) |
| URL da página Teams de informações do aplicativo | [https://www.moveworkforward.com/product/microsoft-teams-jir...](https://www.moveworkforward.com/product/microsoft-teams-jira-connector) |
| URL da Política de Privacidade | [https://www.moveworkforward.com/privacy-policy](https://www.moveworkforward.com/privacy-policy) |
| URL dos Termos de Uso | [https://www.moveworkforward.com/license-agreement/eula](https://www.moveworkforward.com/license-agreement/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Move Work Forward sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | delegado | Usado para criar um canal de discussão de problemas. | A URL da Web do canal recém-criado é armazenada para exibição em Jira para acesso rápido ao canal de Microsoft Teams de discussão. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| Channel.ReadBasic.All | delegado | O nome e a id do canal são usados para enviar notificações de Jira para Microsoft Teams. | A id do canal e o nome são armazenados para configurar notificações de Jira para Microsoft Teams. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| Team.ReadBasic.All | delegado | A permissão é usada para permitir que o usuário selecione uma dessas equipes ingressáveis no Jira. | ID da equipe e nome a ser exibido na tela Configuração em Jira. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| TeamsAppInstallation.ReadForTeam | delegado | Leia os aplicativos Teams instalados nas equipes. Ao configurar a entrega para Microsoft Teams o Aplicativo pode enviar para Teams com o Bot instalado. | Nada | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| User.Read | delegado | Permite que o usuário crie um canal de discussão com colegas de trabalho e @-mention em uma mensagem de canal | Nada | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |
>| email | delegado | O email é usado para corresponder aos usuários Atlassian e Microsoft | O email não é armazenado. Usado somente durante o processo de correspondência. | [39d845a0-3fa2-4fba-acc2-61afe40cfcea](https://docs.microsoft.com/microsoft-365-app-certification/azure/39d845a0-3fa2-4fba-acc2-61afe40cfcea) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Saudar os usuários pelo nome quando o aplicativo for instalado. Corresponder Microsoft Teams usuários atlassianos. | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Registramos a URL do locatário, que é armazenada nos logs por até 5 dias.

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

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39108" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Move Work Forward sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
