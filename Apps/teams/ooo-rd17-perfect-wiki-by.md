---
title: Informações do aplicativo para Wiki Perfeito pelo RD17 by OOO RD17
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Wiki Perfeito pelo RD17, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 593911e2a4408a0a46fdd13868eb789dd50af933
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414989"
---
# <a name="perfect-wiki-by-rd17"></a>Wiki perfeito por RD17

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/40906836-4323-4bbe-875e-3cbb134c40a2" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001679" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo OOO RD17 para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Wiki perfeito por RD17 |
| ID | WA200001679 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | OOO RD17 |
| URL do site do parceiro | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| URL da página Teams de informações do aplicativo | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| URL da Política de Privacidade | [https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NK...](https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NKFVucpN44PO30SFZHDfxWhu-u5wlZI56UW7v3bT-WCM4zH4ZaWGzQR7lnoUpVyU1S/pub) |
| URL dos Termos de Uso | [https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9...](https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9tNvhDe8Sb2AF8A9v8jfG3gJ503cXzIq1nr_Zbq5aShN0mU49fvADgKZ8a58Oha-C/pub) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo OOO RD17 sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | ChannelId e channelName, obteremos informações para mostrar o usuário no aplicativo | Armazenamos channelId e channelName para exibi-lo mais tarde para o usuário | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| Team.ReadBasic.All | delegado | Obteremos teamId do usuário e obteremos o nome da equipe | teamId e teamName, usamo-lo para entender a qual usuário da equipe pertence | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| User.Read | delegado | userId, usado para entender em que usuário está conectado | userId de hashed, para fazer logon do usuário e obter dados associados do DB | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |


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

>Usamos o controle de acesso baseado em função para qualquer operação com o sistema do parceiro

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo OOO RD17 sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

