---
title: Informações do aplicativo para o Organizr pela Arrangr, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Arrangr, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3ccc0e501a899fcb5dc613c254de9aa62911d023
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59275770"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 15 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Arrangr, Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Arrangr |
| ID | WA200002975 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Arrangr, Inc. |
| URL do site do parceiro | [https://arrangr.com](https://arrangr.com) |
| URL da página Teams de informações do aplicativo | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| URL da Política de Privacidade | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| URL dos Termos de Uso | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Arrangr, Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Coletamos nomes de calendários do usuário e detalhes sobre seus eventos de calendário para facilitar o agendamento de reuniões. | Armazenamos os nomes de todos os calendários conectados, para que eles possam ver e alterar quais calendários eles se conectaram | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | delegado | Colete uma lista de canais disponíveis para o usuário, para que possamos mostrar a eles uma lista de seus canais para que eles escolham um para compartilhar um convite do Arrangr. | Não armazenamos informações nos canais do usuário | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | delegado | Essa permissão é usada para enviar convites do Arrangr para canais de equipe em nome do usuário. Não é usado para coletar dados. | Nenhum dado é armazenado coletado com essa permissão. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | delegado | Essa permissão é usada para enviar convites do Arrangr para um Teams chat em nome do usuário. Essa permissão não é usada para coletar dados. | Nenhum dado é armazenado coletado com essa permissão. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | delegado | Essa permissão é usada para enviar convites do Arrangr para 1:1 e chats de grupo em nome do usuário. Não é usado para coletar dados. | Nenhum dado é armazenado coletado com essa permissão. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | delegado | O Organizr coleta Microsoft Teams de reunião no processo de gerando-os com essa permissão. Geramos Teams reuniões em nome do usuário para que ele possa organizar Teams chamadas no Arranger. | Armazenamos os links de reunião para que eles possam ser compartilhados com as partes apropriadas para ingressar na reunião. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | delegado | Coletamos nomes e emails de pessoas relevantes para o usuário. Isso é para que possamos tornar mais fácil para o usuário selecioná-los como destinatários de convites do Arrangr. | Se o usuário terminar selecionando um destinatário oferecido por meio dessa API, salvaremos o nome e o email desse destinatário para conduzir a reunião e facilitar a seleção do usuário como destinatário novamente no futuro. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | delegado | Coletamos os nomes da Teams do usuário, para que ele possa selecionar em qual Teams deseja se conectar ao Arrangr e em qual Equipe deseja compartilhar um convite do Organizr. | O Organizr armazena os nomes de Teams que o usuário optou por vincular ao Arrangr, para que possamos exibir esses Teams em suas configurações e permitir que eles selecionem entre esses Teams ao decidir onde compartilhar um convite do Arrangr. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | delegado | Lemos se nosso aplicativo foi instalado ou não na conta Teams do usuário, para que possamos perguntar se eles querem instalar nosso aplicativo e para que possamos instalá-lo para eles. | Não armazenamos dados coletados por meio dessa permissão. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| perfil | delegado | Nome e endereço de email | Nome e endereço de email, para mostrar ao usuário qual conta ele se conectou ao nosso serviço. | [57de46f8-193a-400c-9a34-c86233aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | Sim | Nome, email, nomes de calendário, informações de eventos de calendário | Coletamos essas informações para permitir que os usuários conectem seu calendário ao Organizr para facilitar o agendamento de reuniões | Nome, email, nomes de calendário | Armazenamos essas informações para que possamos mostrar aos usuários quais contas e calendários eles se conectaram ao nosso serviço |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud, SendGrid, Stripe, Quaderno | O Google Cloud armazena todos os dados do usuário, os nomes de usuário e os emails são compartilhados com SendGrid para enviar emails aos usuários, listar nomes de usuário recebidos, emails e informações de pagamento para processamento de pagamentos. Quaderno recebe nomes de usuário, emails e informações geográficas para ajudar com a conformidade do imposto de vendas. | O Google Cloud é necessário para armazenar dados para lembrar os usuários e fornecer as informações escolhidas para armazenar no Arrangr. Para enviar emails para nossos usos, precisamos fornecer seus endereços de email para SendGrid. Para coletar pagamentos, devemos processar suas informações de pagamento no Stripe, mas não armazenamos suas informações de pagamento em nossos próprios servidores. Quaderno é necessário para calcular o imposto de vendas e garantir que permaneçamos em conformidade com as regulamentações de imposto de vendas. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Os usuários usarão nossa extensão de mensagens para agendar reuniões com outras pessoas. Precisamos mostrar ao usuário a conta em que ele está conectado e precisamos ser capazes de associar o convite que eles enviam ao usuário correto do Organizr. | Nomes de usuário, emails e informações de comunicação. | Essas informações são necessárias para coordenar reuniões entre várias partes e compartilhar com os detalhes para se conectar e com quem estão se encontrando. |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Controlamos os dados armazenados no Google Cloud Datastore por meio de sua API e podemos excluir todos os dados necessários. Nossos usuários podem solicitar a remoção de suas contas e a exclusão de seus dados.

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

Essas informações foram fornecidas pela Arrangr, Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
