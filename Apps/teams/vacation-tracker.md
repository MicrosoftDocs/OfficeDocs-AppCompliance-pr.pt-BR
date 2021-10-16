---
title: Informações do aplicativo para o Rastreador de Férias pelo Rastreador de Férias
ms.author: elmalova
author: elenamalova
ms.date: 09/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Vacation Tracker, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1acd1c49f70e9571c1ec71dbf110fd898b18d5ca
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413262"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 15 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Rastreador de Férias para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Vacation Tracker |
| ID | WA200002167 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Vacation Tracker |
| URL do site do parceiro | [https://vacationtracker.io](https://vacationtracker.io) |
| URL da página Teams de informações do aplicativo | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL da Política de Privacidade | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL dos Termos de Uso | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Vacation Tracker sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | delegado | Lemos IDs e nomes de canal público quando os usuários configuram suas notificações semanais ou diárias. | Os usuários podem selecionar um canal no qual eles querem receber notificações diárias ou semanais do Vacation Tracker. Quando um usuário escolhe seu canal preferencial, armazenamos a ID do canal. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Team.ReadBasic.All | delegado | Listamos o Microsoft Teams equipes ingressado durante a assinatura para permitir que os usuários selecionem uma equipe que eles querem inscrever-se no Rastreador de Férias. Como alternativa, eles podem se inscrever em toda a organização. | Armazenamos a Microsoft Teams de equipe para uma equipe selecionada somente se o usuário se insissar no Rastreador de Férias como uma única equipe (não como uma organização inteira). Usamos as IDs de equipe para conectar um usuário conectado a uma conta existente no Rastreador de Férias. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read | delegado | Coletamos as informações básicas do usuário, incluindo o nome, a ID e a ID do locatário. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | Armazenamos o nome do usuário, a ID e a ID do locatário. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read.All | delegado | Nossos usuários podem importar todos os usuários de sua organização Microsoft 365 ou Microsoft Teams equipe. Usamos essa permissão para importar somente usuários licenciados para uma equipe Microsoft Teams ou organização selecionada. | Armazenamos informações básicas sobre usuários importados, incluindo seu nome, endereço de email e ID do usuário. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.ReadBasic.All | delegado | Permitimos que os usuários importem os outros usuários de sua organização ou Microsoft Teams equipe. Usamos essa permissão para listar os usuários disponíveis e seus endereços de email no pop-up de importação. | Quando os usuários selecionam seus colegas de trabalho para importar para o Vacation Tracker, armazenamos informações básicas sobre esses usuários importados, incluindo seu nome, endereço de email e ID do usuário. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| email | delegado | Quando o usuário faz login usando o Microsoft AAD, armazenamos seu endereço de email como um identificador exclusivo. | Armazenamos o email do usuário como um identificador exclusivo. Não usamos esse email para comunicação, os usuários insere seu endereço de email comercial que usamos para comunicação durante a inscrição. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| offline_access | delegado | Não coletamos dados com essa permissão. Ele é usado para manter o acesso aos dados que podemos acessar. | Não armazenamos dados com essa permissão. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| openid | delegado | Usamos essa permissão para entrar ou inscrever usuários no Rastreador de Férias. Não coletamos dados específicos com essa permissão. | Usamos essa permissão para entrar ou inscrever usuários no Rastreador de Férias. Não armazenamos dados específicos com essa permissão. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| perfil | delegado | Coletamos as informações básicas do usuário, incluindo o nome, a ID e a ID do locatário. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | Armazenamos o nome do usuário, a ID e a ID do locatário. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | Nome da empresa (conforme inserido pelo usuário) | Quando um usuário se ins inscrever, ele instala o nome da empresa e usamos esse nome como o nome da organização dentro do produto |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O bot pode ver as informações básicas sobre o usuário se comunicando com o bot. No entanto, não armazenamos ou usamos essas informações. Usamos apenas a ID do usuário, a ID da conversa e uma mensagem enviada ao nosso bot. | Armazenamos o endereço de email do usuário, o nome do usuário (conforme definido no Microsoft AAD) e a foto de perfil do usuário (do Microsoft AAD) | Usamos um endereço de email como um identificador exclusivo para nossos usuários e o nome e a foto de perfil do usuário para permitir que administradores e aprovadores da mesma empresa reconheçam seus funcionários em nosso painel.  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nome da empresa e ele é retido e removido de acordo com nossa política de retenção padrão de um ano para esse tipo de dados

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Para começar, coletamos a quantidade mínima de dados necessária dos usuários. Em seguida, compartilharemos o mínimo possível com nossos parceiros e, finalmente, temos políticas de retenção de dados para que todos os dados são removidos dentro de um ano, se aplicável.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Vacation Tracker sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

