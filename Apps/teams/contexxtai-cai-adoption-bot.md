---
title: Informações do aplicativo para C.AI bot de adoção por contexxt.ai
ms.author: elmalova
author: elenamalova
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para C.AI Bot de Adoção, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 85c64b89b739d96d48de528d2394f909f404b06e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430511"
---
# <a name="cai-adoption-bot"></a>Bot de Adoção C.AI

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 6 de maio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/f5323aab-3063-46cb-b632-ee01d95de494" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002633" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo contexxt.ai para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Bot de Adoção C.AI |
| ID | WA200002633 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | contexxt.ai |
| URL do site do parceiro | [https://contexxt.ai](https://contexxt.ai) |
| URL da página Teams de informações do aplicativo | [https://contexxt.ai/cai-adoption-bot/](https://contexxt.ai/cai-adoption-bot/) |
| URL da Política de Privacidade | [https://contexxt.ai/privacy-policy](https://contexxt.ai/privacy-policy) |
| URL dos Termos de Uso | [https://contexxt.ai/terms-of-use](https://contexxt.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo contexxt.ai sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | aplicação | Disponibilidade do usuário podendo enviar dicas no momento certo e não durante os horários de foco, por exemplo | Disponibilidade do usuário anônimo podendo enviar dicas no momento certo e não durante os horários de foco, por exemplo | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| ChannelMessage.Read.All | aplicação | Microsoft Teams metadados de canal, como Private ou not or amount of conversations per channel to analyze usage of Teams | Metadados Microsoft Teams canais anônimos, como Private ou not or amount of conversations per channel to analyze usage of Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Chat.Read.All | aplicação | Microsoft Teams metadados de chat, como se uma mensagem foi curtida ou quantos chats de grupo e 1:1 existem para analisar o uso de Teams | Metadados Microsoft Teams chat anônimos, como se uma mensagem foi curtida ou quantos chats de grupo e 1:1 existem para analisar o uso de Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Directory.Read.All | aplicação | ID do objeto do usuário para poder enviar dicas para especificar o usuário posteriormente. | Hashed (anonimizado) ID de objeto do usuário para poder enviar dicas para especificar o usuário posteriormente. | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Group.Read.All | aplicação | Microsoft Teams metadados, como quantidade de Teams e canais para analisar o uso de Teams | Microsoft Teams metadados, como quantidade de Teams e canais para analisar o uso de Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Mail.Read | aplicação | A Microsoft Exchange metadados, como a quantidade de emails e emails de grupo versus 1:1 para analisar o uso de Exchange (em comparação com Teams) | Metadados anônimos da Microsoft Exchange, como a quantidade de emails e emails de grupo versus 1:1 para analisar o uso de Exchange (em comparação com Teams) | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| User.Read.All | aplicação | Microsoft Teams metadados de chat e conversa, como se um usuário fosse mencionado para analisar o uso de Teams | Anonimizado Microsoft Teams metadados de chat e conversa, como se um usuário fosse mencionado para analisar o uso de Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Na Estrutura de Bot, a ID do usuário será transmitida automaticamente, podendo se comunicar com o usuário. Dados de uso adicionais C.AI Análise de Adoção são usados para individualizar a experiência de aprendizado para o usuário, portanto, enviando apenas dicas apropriadas e úteis para os usuários, que podem não conhecer essas dicas | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>As organizações podem gerenciar (atribuir/remover) licenças para seus usuários. As organizações podem atribuir funções diferentes para gerenciar suas licenças. Os administradores sempre podem solicitar a exclusão de seus dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por contexxt.ai sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
