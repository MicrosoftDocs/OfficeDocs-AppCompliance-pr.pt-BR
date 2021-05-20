---
title: Informações do aplicativo para a Matriz de Prioridade - Transformar emails em tarefas pela Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para a Matriz de Prioridade - Transforme emails em tarefas, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9843ece5a330f4a8b8adb6f1388a4a26e12dbe21
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553752"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>Matriz de Prioridade - Transformar emails em tarefas

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 16 de abril de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Appfluence Inc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Matriz de Prioridade - Transformar emails em tarefas |
| ID | WA104381735 |
| Office 365 clientes com suporte | Outlook 2016 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook no iOS, Outlook no Android, Outlook na Web |
| Nome da empresa de parceiro | Appfluence Inc |
| URL do site do parceiro | [https://appfluence.com/](https://appfluence.com/) |
| URL da Política de Privacidade | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL dos Termos de Uso | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Appfluence Inc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegado | Somente quando um novo usuário é adicionado à conta, armazenamos seus emails. | Na criação de nova conta, usamos isso para sugerir outros membros da equipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | delegado | Somente quando um novo usuário é adicionado à conta, armazenamos seus emails. | Na criação de nova conta, usamos isso para sugerir outros membros da equipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | delegado | Armazenamos o token de logon para realizar solicitações em nome do usuário | Atualizar token sem incomodar o usuário. (Matriz de prioridade para Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | delegado | Não armazenamos nenhuma informação de arquivo, a menos que o usuário crie explicitamente e conscientemente um item priority Matrix que se vincula ao arquivo original. | Em nosso recurso One-on-One (disponível por meio de nosso aplicativo Web e também nossos complementos do Outlook/Teams), usamos esse recurso para realçar arquivos SharePoint/OneDrive compartilhados entre dois usuários em nosso sistema, como uma maneira de facilitar reuniões e colaboração geral. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | delegado | Informações básicas de perfil de usuário (nome de exibição, nome, sobrenome, email, avatar) são armazenadas por nós. | Obter o nome do usuário, email, avatar, para personalizar sua conta conosco. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | delegado | Armazenamos a conexão SSO para indicar o modo de logon do usuário. | Para entrar nos usuários por meio de um único login. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | delegado | Um pequeno número de eventos de calendário são transformados em tarefas armazenadas em nosso sistema. | Leia eventos de calendário para que eles possam ser exibidos em nosso modo de exibição 1:1. Também para inicializar novas contas.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | delegado | Armazenamos tarefas criadas em nosso sistema, com um link para a mensagem original. | Usado em nosso Outlook para transformar emails em tarefas e exibir o trabalho compartilhado no visor 1:1. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | delegado | Algumas Outlook/Planner são replicadas em nosso sistema para ajudar novos usuários. | Inicializamos novas contas de usuário com suas Graph tarefas. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, usamos o email do usuário como sua ID exclusiva em nosso sistema e isso é usado para rastrear erros de aplicativos e para rastrear eventos-chave no sistema (downloads, logins, versões de aplicativos etc.) para que nossa equipe de atendimento ao cliente possa fornecer uma resposta rápida às consultas do cliente. Como parte de nossa conformidade com o RGPD, excluímos todos os dados do cliente em duas semanas de uma solicitação de exclusão, embora, na prática, façamos isso no mesmo dia, pois temos scripts internos para fazer isso de forma semiautomás.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados com segurança em um banco de dados criptografado com acesso limitado a um pequeno grupo de administradores. Para aumentar o acesso seguro, aplicamos a autenticação de dois fatores, limitamos o acesso a um conjunto controlado de endereços IP e localizamos o banco de dados em sua própria sub-rede privada, diretamente inacessíveis da Internet aberta.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Appfluence Inc sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
