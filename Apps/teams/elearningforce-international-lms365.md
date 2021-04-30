---
title: Informações do aplicativo para LMS365 por ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
description: Todas as informações de segurança e conformidade disponíveis para o LMS365, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 87d3b5b4acb74fcf4d6bab6e49271a8c8d5a33e6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092440"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 25 de fevereiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela ELEARNINGFORCE International para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | LMS365 |
| ID | WA104381467 |
| Recursos | Bot, Guia, Extensão de Mensagem |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | ELEARNINGFORCE International |
| URL do site do parceiro | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL da página Teams de informações do aplicativo | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL da Política de Privacidade | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL dos Termos de Uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela ELEARNINGFORCE International sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | aplicação | Nenhum | Permite que o aplicativo expanda membros do grupo do AD, o que é necessário para registrar um grupo de usuários nos cursos. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | delegado | Nenhum | A permissão é solicitada dinamicamente durante a configuração da conta de email para notificação. Permite que o aplicativo envie emails de notificação | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | aplicação | Nenhum | Permite que o aplicativo SharePoint domínio durante o provisionamento de locatários. O domínio é usado para a construção de URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | delegado | Nenhum | Permite que o aplicativo convide usuários externos em nome do usuário conectado atual | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | delegado | Nenhum | Entre e leia o perfil do usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | delegado | Nenhum | Permite que o aplicativo leia o perfil completo do usuário conectado atual. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | aplicação | Permite que o aplicativo leia o perfil de usuário completo. Ele&#8217;necessário para ler usuários&#8217; para criar relatórios de hierarquia. | Os dados pessoais a seguir são armazenados em um Banco de Dados dedicado para o respectivo cliente usado para a funcionalidade do Painel do Gerenciador de Gerenciamento do Learner &amp; no aplicativo. Nome da conta, Nome de Exibição do Usuário, Endereço de Email, Departamento, Cargo, Office, País, Cidade, ID do Gerente/Email | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| perfil | delegado | Nenhum | Exibir o perfil básico do usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Usamos o Nome apenas para exibir uma mensagem personalizada quando o Bot cumprimenta o usuário. | Os dados pessoais são armazenados em um banco de dados dedicado do Azure para o respectivo cliente usado para a funcionalidade do Painel do Gerenciador de Gerenciamento do Learner no aplicativo &amp; LMS365. | Nome da conta, Nome de Exibição do Usuário, Endereço de Email, Departamento, Cargo, Office, País, Cidade, ID do Gerente/Email |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, usamos telemetria/logs do Insights Log Analytics que são usados apenas para gerar problemas de tiro e têm uma política de retenção de 90 dias após a qual todos os dados são excluídos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O LMS365 é equipado com uma função Purge que removerá todos os dados pessoais do banco de dados lmS365 dos clientes.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela ELEARNINGFORCE International sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Plataformas de dispositivo, estado do dispositivo, aplicativos cliente |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
