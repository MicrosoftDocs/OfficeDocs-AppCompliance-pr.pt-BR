---
title: Informações do aplicativo para Plumm pela Plumm Health LTD
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Plumm, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 0ecc8063bb993d681ec98a3750ada9afb63bdb81
ms.sourcegitcommit: d67be08c82a50cc263a4bdeb176f41dd60716159
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/15/2021
ms.locfileid: "60378623"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 18 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Plumm Health LTD à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Plumm |
| ID | WA200003326 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Plumm Health LTD |
| URL do site do parceiro | [https://www.plummhealth.com](https://www.plummhealth.com) |
| URL da página Teams de informações do aplicativo | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| URL da Política de Privacidade | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| URL dos Termos de Uso | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Plumm Health LTD sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | aplicação | Usamos o userID nesta permissão. Isso é usado para enviar notificações de requisitos para o usuário com base no uso do nosso serviço. Isso é importante para que o usuário receba notificações apropriadas para sua conta em nosso aplicativo. | Nesta permissão, não estamos armazenar dados em nosso banco de dados. Na verdade, estamos usando o userID para enviar uma notificação apropriada para cada usuário individual com base em seu uso. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | aplicação | Recebemos a ID de Instalação usando essa permissão. Isso é importante para nós para poder enviar a notificação apropriada e correta para cada usuário individual. | Não armazenamos dados em nosso aplicativo usando essa permissão. Não exigimos isso porque só precisamos da ID de Instalação que é obtida em tempo de executar fornecendo o userID. Isso é obtido dinamicamente em tempo de executar, portanto, não há necessidade de armazenar a ID de Instalação. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | delegado | Estamos coletando nome, imagem e email para nossos usuários por meio dessa permissão. Isso é necessário para que nós sejamos capazes de identificar usuários individuais e esses pontos de dados devem ser exibidos sempre que necessário, como a página de perfil individual e a comunicação de email/notificação. | Essas permissões permitem que nosso aplicativo veja o perfil básico de nossos usuários (nome, imagem, email). Esses dados serão usados para exibir o nome e/ou a imagem de perfil do usuário em sua conta de aplicativo conosco e na comunicação por email e/ou notificação. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | aplicação | Essa permissão permite que nosso aplicativo leia perfis de usuário sem um usuário assinado. Neste momento, estamos coletando nome, imagem de perfil e email somente. Isso é necessário para que nós sejamos capazes de identificar usuários individuais e esses pontos de dados devem ser exibidos sempre que necessário, como a página de perfil individual e a comunicação de email/notificação. | Essas permissões permitem que nosso aplicativo veja o perfil básico de nossos usuários (nome, imagem, email). Esses dados serão usados para exibir o nome e/ou a imagem de perfil do usuário em sua conta de aplicativo conosco e na comunicação por email e/ou notificação. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| email | delegado | A ID de email do usuário é coletada. Exigimos esses dados para conceder acesso ao usuário para nossos serviços e entrar em nosso aplicativo e receber notificações sobre suas contas e nossos serviços nesta ID de email.  | A ID de email é armazenada no banco de dados. Precisamos armazenar a ID de email para identificar usuários com exclusividade, fornecer acesso ao nosso aplicativo, ajudá-los a entrar e ajudá-los a receber notificações sobre sua conta conosco. Por exemplo, um usuário com ID de email abc@xyz.com poderá acessar nosso aplicativo e serviços quando entrar no Teams &quot; &quot; com essa ID de email. Com base no uso, podemos enviar notificações a esse usuário em sua ID de email. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | delegado | Para essa permissão, não estamos coletando dados.  | Para essa permissão, não estamos coletando dados. Essa permissão permite que os usuários entre em nosso aplicativo com sua ID de email de trabalho e permite que o aplicativo veja informações básicas de perfil de usuário. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| perfil | delegado | Estamos coletando nome, imagem e email para nossos usuários por meio dessa permissão. Isso é necessário para que nós sejamos capazes de identificar usuários individuais e esses pontos de dados devem ser exibidos sempre que necessário, como a página de perfil individual e a comunicação de email/notificação. | Essas permissões permitem que nosso aplicativo veja o perfil básico de nossos usuários (nome, imagem, email). Esses dados serão usados para exibir o nome e/ou a imagem de perfil do usuário em sua conta de aplicativo conosco e na comunicação por email e/ou notificação. | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | Nome, Sobrenome, Email | O Intercom é nosso CRM que nos ajuda a gerenciar a comunicação com todos os nossos usuários. É por isso que precisamos enviar o primeiro nome, sobrenome e ID de email de nossos usuários para o CRM para que mensagens/emails apropriados possam ser enviados aos usuários. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos dados de uso do serviço, como número de sessões de tratamento usadas, cursos exibidos, meditações exibidas, data de sessões, etc. Retêmos dados para nossos usuários até que o usuário peça especificamente que sua conta seja excluída ou 'esquecida'.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Gerenciamos os dados enviados ao CRM por meio do servidor. Os dados mínimos necessários para o funcionamento são passados para o CRM (Intercom). Plumm mantém o controle total sobre quais dados são passados para o CRM, a retenção dos dados no Intercom e a exclusão deles. Aqui está um link para analisar as políticas de dados do cliente do Intercom: https://www.intercom.com/legal/terms-and-policies#customer-data

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

Essas informações foram fornecidas pela Plumm Health LTD sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Não |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | ,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
