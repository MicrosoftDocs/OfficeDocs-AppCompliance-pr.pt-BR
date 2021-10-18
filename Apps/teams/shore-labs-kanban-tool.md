---
title: Informações do aplicativo para a Ferramenta Kanban por Laboratórios de Costa
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Ferramenta Kanban, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f8ab41264bce6b78ce099a0b295e381e7102a4ca
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430159"
---
# <a name="kanban-tool"></a>Ferramenta Kanban

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 15 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b3c15d4f-1972-4836-a1eb-7575dd56a17e" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002121" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Shore Labs para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Ferramenta Kanban |
| ID | WA200002121 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Laboratórios de Costa |
| URL do site do parceiro | [https://www.shorelabs.com](https://www.shorelabs.com) |
| URL da página Teams de informações do aplicativo | [https://kanbantool.com](https://kanbantool.com) |
| URL da Política de Privacidade | [https://kanbantool.com/policy/privacy](https://kanbantool.com/policy/privacy) |
| URL dos Termos de Uso | [https://kanbantool.com/policy/terms-of-service](https://kanbantool.com/policy/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Laboratórios da Costa sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | Endereço de email do usuário para comunicação, correspondência de identidade e entrega de notificações. | Endereço de email. | [4e820d60-9e62-403c-accd-857b987cc13c](https://docs.microsoft.com/microsoft-365-app-certification/azure/4e820d60-9e62-403c-accd-857b987cc13c) |
>| Team.ReadBasic.All | delegado | Identificadores e nomes das equipes das que o usuário é membro direto. Eles são usados para atribuir automaticamente usuários a grupos corretos na Ferramenta Kanban. | Os identificadores de equipe e os nomes de que o usuário de entrada é um membro direto são mapeados para grupos na Ferramenta Kanban. Isso permite o gerenciamento de acesso baseado em grupo e o compartilhamento de Boards kanban entre equipes diferentes na mesma organização. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| User.Read | delegado | Informações básicas da empresa de usuários assinados. Ele é usado para preencher os detalhes da conta para novas contas e para reconhecer os usuários que pertencem à sua organização para fornecer a funcionalidade De Sign-On Único. | Nome e um identificador exclusivo da Microsoft da sua organização. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| offline_access | delegado | Permite a funcionalidade "Entrar com a Microsoft" e a sincronização de dados aos os que você deu acesso ao aplicativo, após o logon do usuário. | Mantenha acesso aos dados aos que você lhe deu acesso. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| openid | delegado | Abra tokens de ID que permitem que os usuários entre no aplicativo com suas contas de trabalho ou de estudante por meio do botão "Entrar com a Microsoft". | Um identificador imutável para conta de usuário no sistema de identidade da Microsoft. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |
>| perfil | delegado | Nome de usuário para autopopular na Ferramenta Kanban e manter em sincronia com as alterações no Microsoft Teams. | Nome completo do usuário. | [a8ead1a3-85e1-42a3-9ed0-9afb97482b31](https://docs.microsoft.com/microsoft-365-app-certification/azure/a8ead1a3-85e1-42a3-9ed0-9afb97482b31) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| A Ferramenta Kanban usa os seguintes sub-processadores para o desempenho de seu serviço: https://kanbantool.com/policy/privacy#appointed-subprocessors |   | Usamos esses terceiros para fornecer e manter a infraestrutura técnica e ajudar no processamento de cobrança e pagamento. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Coletamos automaticamente informações técnicas sobre sua conta e atividade no Serviço. Essas informações são armazenadas em arquivos de log internos e podem incluir dados OII e EUII, se fizerem parte da atividade que você fez. Não compartilhamos arquivos de log com terceiros. A finalidade da coleta de dados de log é por motivos legais e regulatórios, com o objetivo de identificar a origem de possíveis violações de segurança ou uso indevido do serviço, para limitar a taxa de solicitação e a criação de perfil de desempenho

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os administradores de contas têm acesso total, incluindo a capacidade de modificar e remover dados pessoais relacionados a sua conta e são os controladores de dados reais.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Laboratórios da Costa sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | ,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
