---
title: Informações do aplicativo para avaliado pela Appraisd ltd.
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Avaliações, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: baebeaa3079fbe38cc9c1fb76f1841059346be9c
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407348"
---
# <a name="appraisd"></a>Avaliado

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/4f037969-20ef-4a41-8330-422b7b115eb6" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003123" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Appraisd ltd. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Avaliado |
| ID | WA200003123 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Avaliado ltd. |
| URL do site do parceiro | [https://www.appraisd.com](https://www.appraisd.com) |
| URL da página Teams de informações do aplicativo | [https://www.appraisd.com](https://www.appraisd.com) |
| URL da Política de Privacidade | [https://help.appraisd.com/hc/en-us/articles/360007779298-Pr...](https://help.appraisd.com/hc/en-us/articles/360007779298-Privacy-Policy) |
| URL dos Termos de Uso | [https://app.appraisd.com/account/terms](https://app.appraisd.com/account/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Appraisd ltd. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | delegado | O selador de pessoas apresenta ao usuário uma lista de seus membros da equipe. Isso é para dar suporte à funcionalidade principal dentro da Avaliação. | Esses dados não são armazenados. | [4f037969-20ef-4a41-8330-422b7b115eb6](https://docs.microsoft.com/microsoft-365-app-certification/azure/4f037969-20ef-4a41-8330-422b7b115eb6) |
>| User.Read | delegado | O endereço de email do usuário (upn) e a ID do usuário são usados para encontrar o usuário dentro do Appraisd e vinculá-lo à sua conta Teams usuário. | O endereço de email do usuário (upn) e a ID do usuário são armazenados para lembrar o link entre a conta Avaliação e Teams usuário. | [4f037969-20ef-4a41-8330-422b7b115eb6](https://docs.microsoft.com/microsoft-365-app-certification/azure/4f037969-20ef-4a41-8330-422b7b115eb6) |
>| User.ReadBasic.All | delegado | O selador de pessoas apresenta ao usuário informações básicas sobre o membro da equipe. Isso é para dar suporte à funcionalidade principal dentro da Avaliação. | Esses dados não são armazenados. | [4f037969-20ef-4a41-8330-422b7b115eb6](https://docs.microsoft.com/microsoft-365-app-certification/azure/4f037969-20ef-4a41-8330-422b7b115eb6) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para dar suporte à funcionalidade principal em Avaliado. | Endereço de email, IDs de usuário | Para criar um link entre contas avaliadas e Teams do usuário e dar suporte à funcionalidade principal no Avaliado. |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>N/A

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

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

Essas informações foram fornecidas pela Appraisd ltd. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
