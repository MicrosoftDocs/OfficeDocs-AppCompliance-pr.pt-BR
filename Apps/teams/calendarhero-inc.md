---
title: Informações do aplicativo para CalendarHero pela CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o CalendarHero, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553302"
---
# <a name="calendarhero"></a>CalendárioHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 17 de março de 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela CalendarHero Inc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CalendárioHero |
| ID | WA200000150 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | CalendarHero Inc |
| URL do site de parceiros | [https://calendarhero.com](https://calendarhero.com) |
| URL da página de informações do aplicativo Teams | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL da Política de Privacidade | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL de Termos de Uso | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela CalendarHero Inc sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | ambos | As reuniões são armazenadas em nosso mongoDB no Azure, mas as descrições são criptografadas. | Acesso aos eventos do calendário do usuário. |  |
>| Contacts.ReadWrite | ambos | Contatos nome e endereço de e-mail. | Leia os contatos do usuário (para que possamos convidá-los para uma reunião). |  |
>| Group.Read.All | ambos | Nome do grupo e membros. | (Opcional) leia grupos de usuários corporativos (para agendamento com grupos). |  |
>| Mail.Read | ambos | Entre em contato com e-mail/nome, frequência/recência de interações. | (Opcional) é usado para ler meta dados de e-mail para quem são os contatos mais importantes do usuário (via Machine Learning). |  |
>| MailboxSettings.ReadWrite | ambos | Fuso horário do usuário. | Fuso horário do usuário. |  |
>| User.Read.All | ambos | E-mail de nome do usuário &amp; (armazenado como contato). | (Opcional) leia usuários corporativos (para agendamento com colegas de trabalho) |  |
>| offline_access | aplicação | Não | Precisamos ler e escrever através do nosso back-end a qualquer momento, sem que o usuário está presente. |  |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| importar nomes/e-mails de colegas de trabalho para que nosso bot assistente de reunião possa agendar reuniões com eles | &amp;e-mail nome. ambos são armazenados em nosso banco de dados para pesquisa rápida e para pesquisa parcial de nomes (por exemplo. encontrar-se com Joe P) |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O endereço de e-mail de um usuário e/ou contato é usado para registrar eventos no LogDNA, nosso provedor de registro.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados são armazenados no centro de dados de nuvem MS Azure localizado na cidade de Quebec, Canadá. Vários campos são criptografados com AES256. O acesso ao banco de dados está disponível apenas para engenheiros e nossos servidores back-end através de credenciais de nível de usuário/serviço.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

