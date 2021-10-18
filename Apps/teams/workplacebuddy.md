---
title: Informações de aplicativo para WorkplaceBuddy by WorkplaceBuddy
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para WorkplaceBuddy, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 47d67f1f294781a8b1b80462046d3dd0c0ec5e5a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444737"
---
# <a name="workplacebuddy"></a>WorkplaceBuddy

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/6fef6052-d84d-4071-b679-8b542512a621" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001238" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por WorkplaceBuddy para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | WorkplaceBuddy |
| ID | WA200001238 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | WorkplaceBuddy |
| URL do site do parceiro | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL da página Teams de informações do aplicativo | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL da Política de Privacidade | [https://www.workplacebuddy.com/privacy-policy.pdf](https://www.workplacebuddy.com/privacy-policy.pdf) |
| URL dos Termos de Uso | [https://www.workplacebuddy.com/terms-of-use.pdf](https://www.workplacebuddy.com/terms-of-use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo WorkplaceBuddy sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | Sincronizamos esses dados para permitir que as guias WorkplaceBuddy no Teams funcionem e direcionar usuários específicos com o chatbot | Somente nome, ID e membros | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| Group.Read.All | delegado | Sincronizamos esses dados para permitir que as guias WorkplaceBuddy no Teams funcionem e direcionar usuários específicos com o chatbot | Somente nome, ID e membros | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.Read | delegado | Sincronizamos esses dados para permitir que os usuários faça logon | Nome, Email, Imagem de Perfil, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.ReadBasic.All | delegado | Sincronizamos esses dados para permitir que os usuários faça logon | Nome, Email, Imagem de Perfil, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Precisamos dos dados para oferecer uma experiência personalizada | Nome, Email, ID | Precisamos dos dados para oferecer uma experiência personalizada |


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


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por WorkplaceBuddy sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
