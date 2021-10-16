---
title: Informações do aplicativo para o SecretarioBot pelo MySecretary
ms.author: elmalova
author: elenamalova
ms.date: 04/30/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o SecretarioBot, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ad8e6b2a2f1a7214db66f37de774c01e65ed92e6
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415028"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo MySecretary à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SecretaryBot |
| ID | WA104381085 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | MySecretary |
| URL do site do parceiro | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| URL da página Teams de informações do aplicativo | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| URL da Política de Privacidade | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| URL dos Termos de Uso | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo MySecretary sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | delegado |  | Buscar informações de tempo livre do usuário e de seus colegas. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Calendars.ReadWrite | delegado |  | Enviar solicitação de reunião em vez de usuário. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.Read | delegado | Idioma da loja para mostrar o langage correto. Salvar o timezone para chamar o MS Graph API de calendário corretamente | Buscar a configuração de idioma e de zona de tempo do usuário. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| People.Read | delegado |  | Tente encontrar colegas que tenham relações fortes com o usuário. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegado | Nome de usuário da loja, cidade, país e langauge para análise do usuário. Armazenar emails para entrar em contato com o cliente. Nunca usamos endereço de email, mas podemos usar para suporte. | Tente encontrar o país do usuário e o idioma preferencial. É usado para backup para MailboxSettings.Read. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| email | delegado | Veja acima. | Para armazenar emails. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | delegado |  | Para autenticação OpenID. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| perfil | delegado | Salve o OID para identificar a ID exclusiva do usuário no sistema de identidade MS. | Obter nome de usuário e OID. Tente usar o OID para conectar Outlook Addin no futuro. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Use essa infromation para agendar a reunião de equipe | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Os dados OII ou EUII aparecem na telemetria ou nos logs.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Ainda não fornecemos controle administrativo aos usuários finais, mas se os usuários finais solicitarem que excluam dados, podemos seguir a solicitação deles.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


