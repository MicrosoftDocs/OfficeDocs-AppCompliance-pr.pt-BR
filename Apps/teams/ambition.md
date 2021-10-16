---
title: Informações do aplicativo para ambição por ambição
ms.author: elmalova
author: elenamalova
ms.date: 08/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Ambição, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 41a69c23e64a1059d99c18511837cb166bcf27a0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410465"
---
# <a name="ambition"></a>Ambição

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 17 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/250ef61a-9fa3-434b-ae2a-0ecbe3f8116b" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003159" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Empresa para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Ambição |
| ID | WA200003159 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Ambição |
| URL do site do parceiro | [https://ambition.com](https://ambition.com) |
| URL da página Teams de informações do aplicativo | [https://ambition.com](https://ambition.com) |
| URL da Política de Privacidade | [https://ambition.com/privacy/](https://ambition.com/privacy/) |
| URL dos Termos de Uso | [https://ambition.com/pages/terms/](https://ambition.com/pages/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Ambição sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | Enviar notificações de ambição para o canal | Nome da id &amp; do canal. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| Group.Read.All | delegado | Configurar uma notificação de Fluxo de Trabalho de Ambição para um canal específico dentro de uma equipe. | ID do nome &amp; da equipe. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.Read | delegado | Para identificar o Administrador que autorizou o aplicativo De ambição | Nomes de &amp; usuários de email, para sincronizar com usuários de Ambição | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.ReadBasic.All | delegado | Os emails de nomes de &amp; usuário, para sincronizar os usuários com suas contas de Ambição. | Os emails de nomes de &amp; usuário são armazenados. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| offline_access | delegado | Para sincronizar Microsoft Teams dados enquanto os usuários estão offline. | O Token de Atualização de Token de Acesso OAuth &amp; é armazenado. | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| openid | delegado | Isso é necessário para usar o recurso de login da Microsoft | N/D | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://ambition.com/pages/subprocessors/ | Nome do funcionário, sobrenome, endereço de email | Finalidades de exibição/pesquisa/filtro |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Finalidades de exibição.  | Nomeia &amp; emails. | Para vincular os usuários da Microsoft com suas contas de Ambição. |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>https://ambition.com/privacy/

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Permissões de acesso necessários.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Ambição sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

