---
title: Informações do aplicativo para a ferramenta de relatórios iPlanner para Office 365 Planner pelo iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para a ferramenta de relatórios iPlanner para Office 365 Planner, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548761"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>ferramenta de relatórios iPlanner para Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ferramenta de relatórios iPlanner para Office 365 Planner |
| ID | WA104380686 |
| Office 365 clientes suportados | Excel 2016 ou mais tarde em Windows, Excel na Web, Excel 2016 ou mais tarde em Mac |
| Nome da empresa parceira | iGlobe |
| URL do site de parceiros | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL da Política de Privacidade | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL de Termos de Uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela iGlobe sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para criar uma entrada de calendário no calendário do usuário&#8217;calendário na data de vencimento da tarefa. |  |
>| Directory.AccessAsUser.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para verificar se o usuário tem consentimento e ter acesso para usar a API. |  |
>| Directory.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa de planejador Outlook To Do, e-mails sinalizados e atualizá-los. Para criar uma nova Tarefa de Planejador. |  |
>| Files.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para acessar o arquivo como anexo e carregar arquivos para uma tarefa. |  |
>| Group.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a lista de planos e atualizar a tarefa. |  |
>| Group.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa de planejador e adicionar novas tarefas atualize o balde e a linha de natação. |  |
>| Mail.Read | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Usuário.Leia, para obter a tarefa de planejador Outlook To Do, e-mails sinalizados e atualizá-los. Para criar uma nova Tarefa de Planejador |  |
>| Mail.ReadWrite | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para mostrar os e-mails e enviar e-mails. |  |
>| Mail.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Obtenha o assunto do e-mail pelo e-mail selecionado. Permite que o aplicativo obtenha informações do e-mail selecionado, permitindo copiar o campo de descrição na descrição da tarefa e permitindo salvar anexos do e-mail ou do próprio e-mail para a tarefa. Envie notificação. |  |
>| Tasks.ReadWrite | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter o Outlook To Do dos usuários assinados e atualizar o Usuário.Read, para obter a tarefa do planejador Outlook To Do, e-mails sinalizados e atualizá-los. Para criar uma nova Tarefa de Planejador. |  |
>| User.Read | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Entrar e ler o perfil do usuário |  |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>A iGlobe coleta dados para operar de forma eficaz e fornecer as melhores experiências com nossos produtos e serviços. Para licenciamento: Dados coletados para administrar sua organização&#8217;conta de licenciamento, como quando você implanta um Add-ins gratuito, cria uma assinatura de teste ou compra uma assinatura. As informações seguintes são coletadas. 
- Para fins financeiros: Nome e endereço da empresa
- Usuários inscritos: nome de usuário e e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados estão no próprio inquilino do cliente. Nenhum dado do aplicativo é armazenado. Um complemento moderno é executado em um navegador sandboxed, &#8220;fora de processo&#8221;. Ele interage com os dados dos usuários usando serviços Microsoft. O complemento só pode acessar os dados com os quais o usuário está trabalhando.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

