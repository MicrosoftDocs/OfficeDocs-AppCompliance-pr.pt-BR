---
title: Informações do aplicativo para rastreador de férias pelo Rastreador de Férias
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Vacation Tracker, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550991"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 5 de fevereiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Vacation Tracker à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Vacation Tracker |
| ID | WA200002167 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Vacation Tracker |
| URL do site de parceiros | [https://vacationtracker.io](https://vacationtracker.io) |
| URL da página de informações do aplicativo Teams | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| URL da Política de Privacidade | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| URL de Termos de Uso | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Vacation Tracker sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Delegada | Lemos IDs e nomes de canais públicos quando os usuários definem suas notificações semanais ou diárias. | Os usuários podem selecionar um canal onde desejam receber notificações diárias ou semanais do Vacation Tracker. Quando um usuário escolhe seu canal preferido, armazenamos o ID do canal. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | Delegada | Listamos o Microsoft Teams as equipes que o usuário juntou durante a inscrição para permitir que os usuários selecionem uma equipe que eles querem se inscrever no Vacation Tracker. Eles podem, alternativamente, se inscrever em toda a sua organização. | Armazenamos o ID da equipe Microsoft Teams para uma equipe selecionada somente se o usuário se inscreve no Vacation Tracker como uma única equipe (não como uma organização completa). Usamos IDs da equipe para conectar um usuário de login com uma conta existente no Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | Delegada | Coletamos as informações básicas do usuário, incluindo seu nome, ID e ID do inquilino. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | Armazenamos o nome do usuário, identificação e identificação do inquilino. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | Delegada | Nossos usuários podem importar todos os usuários de sua organização Microsoft 365 ou Microsoft Teams equipe. Usamos esta permissão para importar apenas usuários licenciados para uma equipe ou organização Microsoft Teams selecionada. | Armazenamos informações básicas sobre usuários importados, incluindo seu nome, endereço de e-mail e ID do usuário. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | Delegada | Permitimos que os usuários importem os outros usuários de sua organização ou de sua equipe Microsoft Teams. Usamos esta permissão para listar os usuários disponíveis e seus endereços de e-mail no popup de importação. | Quando os usuários selecionam seus colegas de trabalho para importar para o Vacation Tracker, armazenamos informações básicas sobre esses usuários importados, incluindo seu nome, endereço de e-mail e ID do usuário. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| email | Delegada | Quando o usuário faz login usando o Microsoft AAD, armazenamos seu endereço de e-mail como um identificador exclusivo. | Armazenamos o e-mail do usuário como um identificador único. Não usamos este e-mail para comunicação, os usuários digitam seu endereço de e-mail comercial que usamos para comunicação durante a inscrição. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | Delegada | Não coletamos dados com esta permissão. É usado para manter o acesso aos dados que permissão para acessar. | Não armazenamos nenhum dado com esta permissão. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | Delegada | Usamos essa permissão para fazer login ou inscrever usuários no Vacation Tracker. Não coletamos dados específicos com esta permissão. | Usamos essa permissão para fazer login ou inscrever usuários no Vacation Tracker. Não armazenamos dados específicos com esta permissão. | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| perfil | Delegada | Coletamos as informações básicas do usuário, incluindo seu nome, ID e ID do inquilino. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | Armazenamos o nome do usuário, identificação e identificação do inquilino. Usamos esses dados para conectar usuários conectados à sua organização no Vacation Tracker. | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segmento, Amplitude, Gerenciador de Tags do Google | Nome da empresa (como inserido pelo usuário) | Quando um usuário se inscreve, ele digita o nome da empresa e usamos esse nome como nome da organização dentro do produto |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| O bot pode ver as informações básicas sobre o usuário se comunicando com o bot. No entanto, não armazenamos ou usamos essa informação. Nós só usamos o ID do usuário, o ID de conversação e uma mensagem enviada ao nosso bot. | Armazenamos o endereço de e-mail do usuário, o nome do usuário (conforme definido no Microsoft AAD) e a foto do perfil do usuário (da Microsoft AAD) | Usamos um endereço de e-mail como um identificador exclusivo para nossos usuários e o nome do usuário e foto de perfil para permitir que administradores e aprovadores da mesma empresa reconheçam seus funcionários em nosso painel.  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nome da empresa e é retido e removido de acordo com nossa política padrão de retenção de um ano para este tipo de dados

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Para começar, coletamos a quantidade mínima de dados exigida dos usuários. Em seguida, compartilhamos o mínimo possível com nossos parceiros e finalmente temos políticas de retenção de dados para que todos os dados sejam removidos dentro de um ano, se aplicável.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Vacation Tracker sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Não |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
