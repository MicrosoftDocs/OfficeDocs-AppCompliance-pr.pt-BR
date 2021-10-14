---
title: Informações do aplicativo para o Bem-estar do Dia da Escola pelo Dia escolar de Helsínquia Oy
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Bem-estar do Dia da Escola, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9b953bd648ecc795e57e22dd505676d755b1ee32
ms.sourcegitcommit: d49943662d5e28a9c1289ee23318818f1f68ff96
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/14/2021
ms.locfileid: "60337901"
---
# <a name="school-day-wellbeing"></a>Bem-estar do Dia da Escola

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 12 de outubro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/7caaa66b-34b0-4c15-a65d-dba6edf0c8fd" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001430" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Oy do Dia da Escola de Helsínquia para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Bem-estar do Dia da Escola |
| ID | WA200001430 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Oy do Dia da Escola de Helsínquia |
| URL do site do parceiro | [https://www.schoolday.com](https://www.schoolday.com) |
| URL da página Teams de informações do aplicativo | [https://www.schoolday.com/en/resources/faq](https://www.schoolday.com/en/resources/faq) |
| URL da Política de Privacidade | [https://www.schoolday.com/privacy](https://www.schoolday.com/privacy) |
| URL dos Termos de Uso | [https://www.schoolday.com/eula](https://www.schoolday.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Oy de Dia da Escola de Helsínquia sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | delegado | Nome do grupo e associações de grupo. O usuário que é professor pode adicionar alunos ao Dia da Escola a partir de seus grupos. | Nome do grupo, membros do grupo. O grupo no Dia da Escola pode ser nomeado com base no grupo O365. Os membros do grupo são adicionados a essa classe como alunos. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| Team.ReadBasic.All | delegado | O nome da equipe é usado quando o usuário do professor deseja adicionar alunos de suas equipes e grupos. | O nome da equipe não é armazenado no Dia da Escola. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.Read | delegado | Email, nome e token de ID do usuário são usados para gerenciamento e autenticação do usuário. | Email, nome e token do usuário são armazenados para fins de gerenciamento e autenticação do usuário. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| User.ReadBasic.All | delegado | Imagens de perfil de usuário a serem usadas em avatares do usuário. | A imagem do perfil de usuário não é armazenada. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| email | delegado | O email do usuário é coletado para autenticação de conta. | O email do usuário é armazenado para fins de criação de conta e/ou autenticação. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| offline_access | delegado | Autenticação - Atualização de token de acesso. Experiência do usuário mais suave. | Tokens de acesso para fins de autenticação. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| openid | delegado | Identificador exclusivo do usuário para entrar no OpenID.  | O identificador exclusivo do usuário é armazenado para fins de autenticação. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |
>| perfil | delegado | Nome de usuário preferencial e id de objeto para fins de gerenciamento e autenticação do usuário. | ID do objeto para fins de gerenciamento e autenticação do usuário. | [61dc5e28-775a-4dd0-8990-aaabe3be9e2f](https://docs.microsoft.com/microsoft-365-app-certification/azure/61dc5e28-775a-4dd0-8990-aaabe3be9e2f) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Leitura Avançada | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Conta de usuário, grupos que o usuário pertence, dados de resposta de perguntas de bem-estar. Depois que a conta é excluída, os dados são removidos dentro de 90 dias.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O administrador da organização pode controlar os dados (CRUD) por meio das ferramentas de administrador do Dia da Escola. 

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

Essas informações foram fornecidas pelo Oy do Dia da Escola de Helsínquia sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
