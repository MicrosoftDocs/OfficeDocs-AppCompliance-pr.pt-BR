---
title: Informações do aplicativo para colegas por colegas Insights Inc
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Fellow, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 581b41bdf80bcbdd77bb3406b35556308a13b8f9
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276304"
---
# <a name="fellow"></a>Colega

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 21 de maio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Fellow Insights Inc para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Colega |
| ID | WA200002576 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Fellow Insights Inc |
| URL do site do parceiro | [https://fellow.app](https://fellow.app) |
| URL da Política de Privacidade | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| URL dos Termos de Uso | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Fellow Insights Inc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | ambos | O colega se conecta aos calendários do usuário para fornecer a eles a capacidade de fazer anotações nos dados. | Os colegas armazenam todos os dados de evento do calendário principal do usuário. Os anexos não são armazenados. Isso é usado em Fellow para fornecer uma experiência de tomada de anotações baseada em calendário. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | delegado | Coletamos os nomes dos canais dos que um usuário é membro para mostrar a eles uma lista de canais para os que podem enviar anotações. | Armazenamos em cache os nomes e as IDs dos canais dos que um usuário é membro, para permitir que os usuários enviem anotações de Fellow para o canal especificado. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | aplicação | Esses dados só serão coletados se uma instalação do administrador for feita para toda a organização. Usamos os dados de diretório para sincronizar uma lista de usuários e provisionar contas automaticamente. | Se e somente se uma instalação em toda a organização for executada pelo administrador de dentro das configurações do espaço de trabalho em Fellow, os administradores terão a opção de habilitar a sincronização automática de todos os usuários do Azure AD para o Fellow (provisionamento automático). Nesse caso, armazenamos informações do usuário, como associações de ID, Nome, Email e Gerente e Grupo (para recursos de gerenciamento de equipe). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | aplicação | Esses dados só serão coletados se uma instalação do administrador for feita para toda a organização. Usamos os dados de diretório para sincronizar uma lista de usuários e provisionar contas automaticamente. | Se e somente se uma instalação em toda a organização for executada pelo administrador de dentro das configurações do espaço de trabalho em Fellow, os administradores terão a opção de habilitar a sincronização automática de todos os usuários do Azure AD para o Fellow (provisionamento automático). Nesse caso, armazenamos informações do usuário, como associações de ID, Nome, Email e Gerente e Grupo (para recursos de gerenciamento de equipe). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | delegado | Os contatos do usuário são coletados, em displayNames de contato específicos e endereços de email. Isso é usado em Fellow para fornecer uma lista de usuários para convidar para convidar para uma nota/compartilhar uma nota com. | Os contatos do usuário são coletados, em displayNames de contato específicos e endereços de email. Isso é usado em Fellow para fornecer uma lista de usuários para convidar para convidar para uma nota/compartilhar uma nota com. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | aplicação | Esses dados só serão coletados se uma instalação do administrador for feita para toda a organização. Os contatos do usuário são coletados, em displayNames de contato específicos e endereços de email. Isso é usado em Fellow para fornecer uma lista de usuários para convidar para convidar para uma nota/compartilhar uma nota com. | Se e somente se uma instalação em toda a organização for executada pelo administrador de dentro das configurações do espaço de trabalho em Fellow, os administradores terão a opção de habilitar a sincronização automática de todos os usuários do Azure AD para o Fellow (provisionamento automático). Nesse caso, os contatos do usuário são coletados, em displayNames de contato específicos e endereços de email. Isso é usado em Fellow para fornecer uma lista de usuários para convidar para convidar para uma nota/compartilhar uma nota com. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | delegado | Uma lista de equipes das que o usuário faz parte é coletada. Isso é usado em colegas com o objetivo de permitir que o usuário envia anotações de Fellow para uma equipe. | Armazenamos em cache os nomes e as IDs das equipes das que um usuário é membro, para permitir que os usuários enviem anotações de Fellow para o canal de equipes especificado. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | delegado | Informações básicas do usuário são coletadas. Nome de usuário, email, cargo. Essas informações são usadas em Fellow para criar contas de usuário e contas da empresa. | As informações básicas do usuário são armazenadas. Nome de usuário, email, cargo. Essas informações são usadas em Fellow para manter contas de usuário e contas da empresa. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | aplicação | Esses dados só serão coletados se uma instalação do administrador for feita para toda a organização. Usamos os dados de diretório para sincronizar uma lista de usuários e provisionar contas automaticamente. | Se e somente se uma instalação em toda a organização for executada pelo administrador de dentro das configurações do espaço de trabalho em Fellow, os administradores terão a opção de habilitar a sincronização automática de todos os usuários do Azure AD para o Fellow (provisionamento automático). Nesse caso, armazenamos informações do usuário, como associações de ID, Nome, Email e Gerente e Grupo (para recursos de gerenciamento de equipe). | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | delegado | O token de atualização do usuário para manter o acesso aos dados coletados por meio de outros escopos. | O token de atualização do usuário é armazenado no banco de dados. Isso é usado em Fellow para sincronizar eventos em segundo plano para a experiência de tomada de notas baseada em calendário, bem como notificações para anotações sobre eventos agendados. | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Os colegas armazenam informações fornecidas diretamente pelo usuário, incluindo dados pessoais. Fellow também armazena algumas informações de sistemas de terceiros, como dados OAuth, dados de calendário e PII, como email de &amp; nome. Retêmos todos os dados indefinidamente, pelo tempo necessário e legalmente permitido para a finalidade para a qual foram coletados. Excluímos essas informações com segurança em uma data anterior após o recebimento de uma solicitação pelos usuários. Os dados de log são mantidos por 30 dias.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todas as transferências de dados ocorrem por APIs protegidas para nossos sistemas back-end. O colega emprega muitos controles para garantir a Segurança e a Confidencialidade de seus sistemas, de acordo com a estrutura do SOC 2, conforme definido pela AICPA. Os controles dos colegas passam por uma auditoria anual para garantir a conformidade contínua. Um relatório SOC 2 pode ser compartilhado mediante solicitação e NDA.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Fellow Insights Inc sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | ,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
