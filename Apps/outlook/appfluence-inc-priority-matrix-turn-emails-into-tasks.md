---
title: Informações do aplicativo para matriz prioritária - Transforme e-mails em tarefas pela Appfluence Inc
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para Priority Matrix - Transforme e-mails em tarefas, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9843ece5a330f4a8b8adb6f1388a4a26e12dbe21
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553752"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>Matriz Prioritária - Transforme e-mails em tarefas

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 16 de abril de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Appfluence Inc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Matriz Prioritária - Transforme e-mails em tarefas |
| ID | WA104381735 |
| Office 365 clientes suportados | Outlook 2016 ou posterior em Windows, Outlook 2016 ou posterior no Mac, Outlook no iOS, Outlook no Android, Outlook na web |
| Nome da empresa parceira | Appfluence Inc |
| URL do site de parceiros | [https://appfluence.com/](https://appfluence.com/) |
| URL da Política de Privacidade | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| URL de Termos de Uso | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Appfluence Inc sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegada | Somente quando um novo usuário é adicionado à conta, armazenamos seu e-mail. | Na criação de novas contas, usamos isso para sugerir outros membros da equipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | Delegada | Somente quando um novo usuário é adicionado à conta, armazenamos seu e-mail. | Na criação de novas contas, usamos isso para sugerir outros membros da equipe. | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | Delegada | Armazenamos o token de login para realizar solicitações em nome do usuário | Atualizar token sem incomodar o usuário. (Matriz Prioritária para Teams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | Delegada | Não armazenamos nenhuma informação de arquivo, a menos que o usuário crie explicitamente e conscientemente um item Priority Matrix que se vincule ao arquivo original. | Em nosso recurso One-on-One (disponível através do nosso aplicativo web e também nossos complementos Outlook/Teams), usamos esse recurso para destacar SharePoint/OneDrive arquivos que são compartilhados entre dois usuários em nosso sistema, como uma maneira de facilitar reuniões e colaboração geral. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | Delegada | As informações básicas do perfil do usuário (nome de exibição, nome do primeiro nome, sobrenome, e-mail, avatar) são armazenadas por nós. | Obtenha o nome do usuário, e-mail, avatar, para personalizar sua conta conosco. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | Delegada | Armazenamos a conexão SSO para indicar o modo de login para o usuário. | A fim de fazer login nos usuários através de login único. | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | Delegada | Um pequeno número de eventos de calendário são transformados em tarefas armazenadas em nosso sistema. | Leia eventos de calendário para que possam ser exibidos em nossa exibição 1:1. Também para inicializar novas contas.  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | Delegada | Armazenamos tarefas criadas em nosso sistema, com um link para a mensagem original. | Usado em nosso Outlook complemento para transformar e-mails em tarefas e exibir trabalho compartilhado na exibição 1:1. | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | Delegada | Algumas tarefas Outlook/Planner são replicadas em nosso sistema para ajudar novos usuários. | Nós bootstrap novas contas de usuário com suas tarefas de Graph. | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, usamos o e-mail do usuário como seu ID exclusivo em nosso sistema, e isso é usado para rastrear erros de aplicativos e rastrear eventos-chave no sistema (downloads, logins, versões de aplicativos, etc) para que nossa equipe de atendimento ao cliente possa fornecer uma resposta rápida às consultas dos clientes. Como parte da nossa conformidade com o GDPR, excluímos todos os dados do cliente dentro de 2 semanas após uma solicitação de exclusão, embora na prática façamos isso no mesmo dia, pois temos scripts internos para fazer isso de forma semiautomática.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados com segurança em um banco de dados criptografado com acesso limitado a um pequeno grupo de administradores. Para garantir ainda mais o acesso, aplicamos a autenticação de dois fatores, limitamos o acesso a um conjunto controlado de endereços IP e localizamos o banco de dados em sua própria sub-rede privada, diretamente inacessível da internet aberta.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Appfluence Inc sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Sim |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/><br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
