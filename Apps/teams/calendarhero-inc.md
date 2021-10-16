---
title: Informações de aplicativo para CalendarHero by CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 01/22/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para CalendarHero, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 380aa287ed8c0a11743b56fbb6a2e3e8fbea5081
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411115"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 17 de março de 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo CalendarHero Inc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CalendarHero |
| ID | WA200000150 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | CalendarHero Inc |
| URL do site do parceiro | [https://zoom.ai](https://zoom.ai) |
| URL da página Teams de informações do aplicativo | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL da Política de Privacidade | [https://zoom.ai/privacy-policy](https://zoom.ai/privacy-policy) |
| URL dos Termos de Uso | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo CalendarHero Inc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | ambos | As reuniões são armazenadas em cache em nosso mongoDB no Azure, mas as descrições são criptografadas. | Acesso aos eventos de calendário do usuário. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite | ambos | Nome e endereço de email de contatos. | Leia os contatos do usuário (para que possamos convidá-los para uma reunião). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | ambos | Nome e membros do grupo. | (Opcional) leia grupos de usuários corporativos (para agendamento com grupos). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | ambos | Contate email/nome, frequência/receência de interações. | (Opcional) é usado para ler os metadados de email para quem são os contatos mais importantes do usuário (por meio Machine Learning). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.ReadWrite | ambos | Timezone do usuário. | Timezone do usuário. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read.All | ambos | Email de nome do &amp; usuário (armazenado como contato). | (Opcional) ler usuários corporativos (para agendamento com colegas de trabalho) | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | aplicação | Não | Precisamos ler e gravar nosso back-end a qualquer momento, sem a presença do usuário. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| importar nomes/emails de colegas de trabalho para que nosso assistente de reunião possa agendar reuniões com eles | email &amp; de nome. ambos são armazenados em nosso banco de dados para pesquisa rápida e para pesquisa parcial de nome (por exemplo. meet with Joe P) |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O endereço de email de um usuário e/ou contato é usado para registrar eventos no LogDNA, nosso provedor de log.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados são armazenados no centro de dados de nuvem do MS Azure localizado na cidade de Quebec, Canadá. Vários campos são criptografados com o AES256. O acesso ao banco de dados está disponível apenas para engenheiros e nossos servidores back-end por meio de credenciais de nível de usuário/serviço.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


