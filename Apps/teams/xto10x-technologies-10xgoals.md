---
title: Informações do aplicativo para 10xGoals pela tecnologia xto10x
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para 10xGoals, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f4f0e5c4bdd6a7e41ac7480348fad7eb3882e3d1
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430300"
---
# <a name="10xgoals"></a>10xGoals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 8 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/950aa4fb-0583-4b13-9b5f-bbc92b9cc376" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003122" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelas tecnologias xto10x para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | 10xGoals |
| ID | WA200003122 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Tecnologias xto10x |
| URL do site do parceiro | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| URL da página Teams de informações do aplicativo | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| URL da Política de Privacidade | [https://www.xto10x.com/security/privacy-policy/](https://www.xto10x.com/security/privacy-policy/) |
| URL dos Termos de Uso | [https://www.xto10x.com/security/terms-of-use/](https://www.xto10x.com/security/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelas Tecnologias xto10x sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | aplicação | Os usuários enviam emails e a id do azure é buscada para que o aplicativo possa instalar o aplicativo proativamente para todos os usuários da organização.  | Como este aplicativo primeiro requer assinatura de serviço 10xGoals para que o email do usuário e a id do usuário do azure sejam enviados para o serviço 10xGoals para que, quando alguma atividade acontece relacionada a esse usuário, ele possa enviar uma notificação proativa para o aplicativo de equipes do usuário. | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | aplicação | É necessário para que o aplicativo possa buscar o teamsAppDefinition instalado para administrador e instalar-se proativamente para todos os usuários da organização.  | Nada é armazenado no banco de dados que é buscado a partir dessa api. | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 10xGoals, AWS | email do usuário e AzureId do usuário.  | Como este aplicativo primeiro requer assinatura de serviço 10xGoals para que o email do usuário e a id do azure do usuário sejam enviados para o serviço 10xGoals para que, quando alguma atividade acontece relacionada a esse usuário, o sistema possa enviar uma notificação proativa para o usuário. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Como este aplicativo primeiro requer assinatura de serviço 10xGoals para que o email do usuário e a id do usuário do azure sejam enviados para o serviço 10xGoals para que, quando alguma atividade acontece relacionada a esse usuário, ele possa enviar uma notificação proativa para o aplicativo de equipes do usuário. | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>tenantId da organização é armazenado para ter uma mensagem de boas-vindas de diferença, dependendo se um locatário concedeu permissões necessárias ou não. Se um locatário já concedeu permissões a outros usuários dessa organização não precisar olhar para esse fluxo de concessão de permissões novamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>NA

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelas tecnologias xto10x sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Não |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
