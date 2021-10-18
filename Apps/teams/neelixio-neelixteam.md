---
title: Informações do aplicativo para o Grupo Demix.Team por Neelix.IO
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Neelix.Team, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 968a4ffad3d1c5893414ea3e672474330fc37553
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60437135"
---
# <a name="neelixteam"></a>Neelix. Equipe

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 10 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/bed170ee-dbd7-4efa-b48e-b0937ded1689" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003047" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Neelix.IO para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Neelix. Equipe |
| ID | WA200003047 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Neelix.IO |
| URL do site do parceiro | [https://www.neelix.team](https://www.neelix.team) |
| URL da página Teams de informações do aplicativo | [https://www.neelix.team](https://www.neelix.team) |
| URL da Política de Privacidade | [https://www.neelix.team/data-security-policy](https://www.neelix.team/data-security-policy) |
| URL dos Termos de Uso | [https://www.neelix.io/terms-of-use-en](https://www.neelix.io/terms-of-use-en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Neelix.IO sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | o aplicativo usa ids de canal e nomes para oferecer conveniência aos usuários para gerenciar suas preferências padrão ao enviar comentários do MS Treams | IDs de canal e nomes são armazenados para gerenciamento de padrões para conveniência do usuário | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| Team.ReadBasic.All | delegado | o app usa ids de equipe e nomes para oferecer conveniência aos usuários para gerenciar suas preferências padrão ao enviar comentários do MS Treams | IDs de equipe e nomes são armazenados. Esses dados nos permitem configurar padrões de conveniência que permitem a conclusão mais rápida do formulário de feedback. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| email | delegado | o email é usado como parte do registro do usuário em Neelix. Após o registro inicial, o email é usado para notificações.  | o email é armazenado no perfil do usuário. o email também é usado para verificar se o usuário não tenta usar o mesmo email por meio de algum outro canal oauth. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| offline_access | delegado | Isso usado para obter o token de atualização |  o token de atualização é armazenado para obter um novo token de acesso | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| perfil | delegado | O nome de usuário é usado para criar conta de usuário ao se registrar com o Neelix.  | O nome de usuário é armazenado em conta de usuário. Isso é necessário para que o usuário seja reconhecido por outros membros da equipe no diário de equipe. O usuário pode atualizar o nome armazenado em Neelix. | [6996cad6-a969-487a-9182-f4dc4c6c8803](https://docs.microsoft.com/microsoft-365-app-certification/azure/6996cad6-a969-487a-9182-f4dc4c6c8803) |
>| User.Read | delegado | O aplicativo bot usa user.read para poder enviar o usuário de informações para que a plataforma principal de Neelix possa identificar o usuário | As informações não são armazenadas | [bed170ee-dbd7-4efa-b48e-b0937ded1689](https://docs.microsoft.com/microsoft-365-app-certification/azure/bed170ee-dbd7-4efa-b48e-b0937ded1689) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Plataforma de Identidade da Microsoft | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| IDs de locatário são enviadas para nosso serviço back-back em execução na Plataforma de Nuvem do Google | IDs de locatário | IDs de locatário são usadas para fins de identificação do usuário durante o oauth |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O aplicativo usa a ID do usuário para identificar o usuário em relação às informações registradas na plataforma Demix | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>IDs de locatários são registradas em logs do sistema. A política de retenção de logs é de 30 dias.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Política de usuário final, procedimentos de conformidade do RGPD, Cancelamento de Conta e Procedimentos de Acrichival de Dados

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Neelix.IO sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
