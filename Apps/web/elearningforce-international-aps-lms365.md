---
title: Informações do aplicativo para LMS365
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para LMS365, suas políticas de tratamento de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7136a0f4a71f54772dc250433686996f2d236a19
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224985"
---
# <a name="application-information-for-lms365-by-elearningforce-international-aps"></a>Informações de aplicativo para LMS365 por ELEARNINGFORCE International Aps

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 23 de junho de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/elearningforce.lms365_spfx" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela ELEARNINGFORCE International Aps para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | LMS365 |
| ID | elearningforce.lms365_spfx |
| Nome da empresa parceira | ELEARNINGFORCE International Aps |
| URL do site do parceiro | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL da Política de Privacidade | [https://www.lms365.com/privacy](https://www.lms365.com/privacy) |
| URL dos Termos de Uso | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela ELEARNINGFORCE International Aps sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para coletar?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **Azure AD ID do aplicativo** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | aplicação | Nenhum | Permite que o aplicativo expanda os membros do grupo do AD, o que é necessário para registrar o grupo de usuários nos cursos. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | Delegada | Nenhum | A permissão é solicitada dinamicamente durante a configuração da conta de email para notificação. Permite que o aplicativo envie emails de notificação | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | aplicação | Nenhum | Permite que o aplicativo obtenha SharePoint domínio durante o provisionamento de locatário. O domínio é usado para a construção de URL. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | Delegada | Nenhum | Permite que o aplicativo convide usuários externos em nome do usuário conectado no momento | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | Delegada | Nenhum | Entre e leia o perfil do usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | Delegada | Nenhum | Permite que o aplicativo leia o perfil completo do usuário conectado atual. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | aplicação | Permite que o aplicativo leia o perfil completo do usuário. Ele&#8217;necessário para ler os usuários&#8217; gerentes para criar relatórios de hierarquia. | Os dados pessoais a seguir são armazenados em um Banco de Dados dedicado para o respectivo cliente usado para a funcionalidade do Painel do Learner Management &amp; Manager dentro do aplicativo. Nome da conta, nome de exibição do usuário, endereço de email, departamento, cargo, Office, país, cidade, ID do gerente/email | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| perfil | Delegada | Nenhum | Exibir o perfil básico do usuário. | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e suplementos criados Microsoft 365 podem usar APIs adicionais da Microsoft diferentes do Microsoft Graph para coletar ou processar informações de identificação organizacional (OII). Liste todas as APIs da Microsoft diferentes Graph este aplicativo usa.

>| **API** |  **O OII foi coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Microsoft Office SharePoint Online | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não são serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, usamos Insights telemetria/logs do Log Analytics que são usados apenas para solução de problemas e têm uma política de retenção de 90 dias após a qual todos os dados são excluídos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>O LMS365 é equipado com uma Função de Limpeza que removerá todos os dados pessoais do Banco de Dados LMS365 dos clientes.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de todos os dados de OII (informações de identificação organizacional) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela ELEARNINGFORCE International Aps sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de identidade.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você integra-se ao Microsoft Identify Platform (Azure AD)?  | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa a MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Plataformas de dispositivo, estado do dispositivo, aplicativos cliente |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multilocação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs Web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenha êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
