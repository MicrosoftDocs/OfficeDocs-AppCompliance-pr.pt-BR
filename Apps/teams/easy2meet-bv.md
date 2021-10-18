---
title: Informações do aplicativo para Easy2Meet por Easy2Meet B.V.
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Easy2Meet, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 164890c1ceebe1cae7567ca5f6d05b38d3c8361b
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60432911"
---
# <a name="easy2meet"></a>Easy2Meet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 21 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/8dbb8c54-678e-4c02-bc35-0f393416e532" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003277" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Easy2Meet B.V. para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Easy2Meet |
| ID | WA200003277 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Easy2Meet B.V. |
| URL do site do parceiro | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| URL da página Teams de informações do aplicativo | [https://www.easy2meet.eu](https://www.easy2meet.eu) |
| URL da Política de Privacidade | [https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf](https://www.easy2meet.eu/hubfs/PrivacyStatement.pdf) |
| URL dos Termos de Uso | [https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet...](https://www.easy2meet.eu/hubfs/PDF%20contractueel/Easy2Meet%20General%20Terms%20and%20Conditions%20Sept%202020%20EN.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Easy2Meet B.V. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | Precisamos de informações do usuário para gerenciar usuários e reuniões no Easy2Meet | Email e nome. Precisamos disso para gerenciar usuários e reuniões. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| email | delegado | Para exibir os adres de email do usuário atual. Precisamos dos adres de email para enviar convites de reunião | Email e nome. Precisamos disso para gerenciar usuários e reuniões. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| openid | delegado | não coletamos dados aqui. Estamos usando isso para entrar no usuário | não coletamos dados aqui. Estamos usando isso para entrar no usuário. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |
>| perfil | delegado | Precisamos de informações do usuário para gerenciar usuários e reuniões no Easy2Meet | Email e nome. Precisamos disso para gerenciar usuários e reuniões. | [286a2e24-18ad-432d-8698-694bcd77ecfc](https://docs.microsoft.com/microsoft-365-app-certification/azure/286a2e24-18ad-432d-8698-694bcd77ecfc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint Online | Não |  |  |  |  |
>| MS Exchange Online | Não |  |  |  |  |

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

>auditoria

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Easy2Meet B.V. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
