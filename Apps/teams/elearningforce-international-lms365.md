---
title: Informações sobre inscrição para LMS365 pela ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o LMS365, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 44ed1631c7d0221b463f518f2494b7a8744eef30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552212"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 25 de fevereiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela ELEARNINGFORCE International à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | LMS365 |
| ID | WA104381467 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | ELEARNINGFORCE International |
| URL do site de parceiros | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL da página de informações do aplicativo Teams | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL da Política de Privacidade | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL de Termos de Uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela ELEARNINGFORCE International sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | aplicação | Nenhum | Permite que o aplicativo expanda os membros do grupo AD, o que é necessário para inscrever grupo de usuários nos cursos. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Delegada | Nenhum | A permissão é solicitada dinamicamente durante a configuração da conta de e-mail para notificação. Permite que o aplicativo envie e-mails de notificação | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | aplicação | Nenhum | Permite que o aplicativo obtenha SharePoint domínio durante o provisionamento do inquilino. O domínio é usado para a construção de URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Delegada | Nenhum | Permite que o aplicativo convide usuários externos no atual conectado em nome do usuário | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Delegada | Nenhum | Faça login e leia o perfil do usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Delegada | Nenhum | Permite que o aplicativo leia o perfil completo do usuário conectado ao usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | aplicação | Permite que o aplicativo leia o perfil completo do usuário. Ele&#8217;necessário ler os usuários&#8217; gestores para construir relatórios de hierarquia. | Os seguintes dados pessoais são armazenados em um banco de dados dedicado para o respectivo cliente usado para a funcionalidade do &amp; Painel de Controle de Gerenciador de Aprendizes dentro do aplicativo. Nome da conta, nome da exibição do usuário, endereço de e-mail, departamento, título de trabalho, Office, país, cidade, ID do gerente/e-mail | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| perfil | Delegada | Nenhum | Veja o perfil básico do usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Microsoft Office SharePoint Online | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Usamos o Primeiro Nome apenas para exibir uma mensagem personalizada quando o Bot cumprimenta o usuário. | Os dados pessoais são armazenados em um banco de dados Azure dedicado para o respectivo cliente usado para a funcionalidade Do Painel de Gerenciador de Gerenciamento de &amp; Aprendizes dentro do aplicativo LMS365. | Nome da conta, nome da exibição do usuário, endereço de e-mail, departamento, título de trabalho, Office, país, cidade, ID do gerente/e-mail |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, usamos telemetria/logs insights Log Analytics que são usados apenas para fotografar problemas e têm uma política de retenção de 90 dias após a qual todos os dados são excluídos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O LMS365 está equipado com uma Função de Expurgo que removerá quaisquer dados pessoais do banco de dados LMS365 dos clientes.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela ELEARNINGFORCE International sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Sim |
| Seu aplicativo suporta políticas de acesso condicional? | Sim |
| Liste os tipos de políticas suportadas | Plataformas de dispositivos, estado do dispositivo, aplicativos cliente |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
