---
title: Informações do aplicativo para Timeneye pelo SRL Digital de DM
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Timeneye, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ab8d61b542baaacd406df7596ecdcd4d8c87e327
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873705"
---
# <a name="timeneye"></a>Timeneye

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 31 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/015bf4ec-bc37-4931-9862-ef8686da652b" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001950" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SRL Digital do DM para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Timeneye |
| ID | WA200001950 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | DM Digital SRL |
| URL do site do parceiro | [https://www.dmdigital.it](https://www.dmdigital.it) |
| URL da Política de Privacidade | [https://www.timeneye.com/privacy-policy](https://www.timeneye.com/privacy-policy) |
| URL dos Termos de Uso | [https://www.timeneye.com/terms-and-conditions](https://www.timeneye.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo SRL Digital do DM sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Data de início/término do evento, assunto do evento, ID do evento, URI da Web do evento. Gere sugestões com base em eventos de calendário. | Data de início/término do evento, assunto do evento, ID do evento, URI da Web do evento. Ser capaz de vincular uma sugestão gerada ao evento de calendário relevante. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Calendars.Read.Shared | delegado | Data de início/término do evento, assunto do evento, ID do evento, URI da Web do evento. Usamos essas informações para gerar sugestões com base em eventos de calendário. | Data de início/término do evento, assunto do evento, ID do evento, URI da Web do evento. Usamos essas informações para vincular uma sugestão gerada ao evento de calendário relevante. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Directory.Read.All | delegado | IDs dos grupos de usuários. Usamos essas informações para verificar os grupos dos quais o usuário é membro para que possa sincronizar os planejadores de seus grupos. | IDs dos grupos de usuários. Usamos essas informações para verificar os grupos dos quais o usuário é membro para que possa sincronizar os planejadores de seus grupos. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Group.Read.All | delegado | Nome do grupo, ID do grupo. Usamos essas informações durante a sincronização dos projetos do planejador. | Nome do grupo, ID do grupo.  | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| Tasks.Read | delegado | nome da lista de tarefas, ID da lista de tarefas. Usamos essas informações durante a sincronização dos projetos do planejador. | nome da lista de tarefas, ID da lista de tarefas. Usamos essas informações durante a sincronização dos projetos do planejador. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.Read | delegado | email, nome. Usamos essas informações para fazer logoff no usuário/criar a conta de usuário | email, nome. Usamos essas informações para fazer logoff no usuário/criar a conta de usuário | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| User.ReadBasic.All | delegado | nome do usuário, email. Usamos essas informações para que o usuário possa importar outros usuários do Planner/Microsoft para nosso serviço. | nome do usuário, email. Informações básicas necessárias para criar um novo usuário em nosso serviço. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| email | delegado | Email. Usamos essas informações para fazer logoff no usuário/criar a conta de usuário | Email. Usamos essas informações para fazer logoff no usuário/criar a conta de usuário | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| offline_access | delegado | Permissão necessária para sincronizar o planejador/calendário enquanto o usuário não estiver online. | Permissão necessária para sincronizar o planejador/calendário enquanto o usuário não estiver online. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| openid | delegado | id_token. Fazer logor no usuário por meio do Microsoft SSO | id_token. Fazer logom no usuário por meio do Microsoft SSO. | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |
>| perfil | delegado | email, nome. Usamos essas informações para fazer logoff no usuário/criar a conta de usuário | email, nome. Usamos essas informações para fazer logoff no usuário/criar a conta de usuário | [56412014-bafe-474e-95b4-ebfea106a167](https://docs.microsoft.com/microsoft-365-app-certification/azure/56412014-bafe-474e-95b4-ebfea106a167) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook api de calendário | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nome de usuário e email, Detalhes de Cobrança da Empresa. Quando a conta/usuário é excluída, as informações são removidas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não passamos informações sensatas para nossos sistemas parceiros, exceto para email do usuário para fins de suporte, tíquete e cobrança. As informações são excluídas na exclusão da conta em nosso sistema.

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

Essas informações foram fornecidas pelo SRL Digital do DM sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
