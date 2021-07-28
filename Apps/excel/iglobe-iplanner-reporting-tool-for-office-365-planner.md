---
title: Informações do aplicativo para a ferramenta de relatório do iPlanner para Office 365 Planner by iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para a ferramenta de relatório do iPlanner para o Office 365 Planner, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3591c67721188d8dc70bf4f2cf0e34bdb9ffc506
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526047"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Ferramenta de relatório do iPlanner para Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Ferramenta de relatório do iPlanner para Office 365 Planner |
| ID | WA104380686 |
| Office 365 clientes com suporte | Excel 2016 ou posterior no Windows, Excel na Web, Excel 2016 ou posterior no Mac |
| Nome da empresa de parceiro | iGlobe |
| URL do site do parceiro | [https://iglobecrm.com/](https://iglobecrm.com/) |
| URL da Política de Privacidade | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| URL dos Termos de Uso | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para criar uma entrada de calendário no calendário do usuário&#8217;na data de vencimento da tarefa. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para verificar se o usuário tem consentimento e tem acesso para usar a API. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa do planejador Outlook To Do, sinalizar emails e atualizá-los. Para criar uma nova tarefa do Planner. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para acessar o arquivo como anexo e carregar arquivos em uma tarefa. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a lista de planos e atualizar a tarefa. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa do planejador e adicionar novas tarefas atualize o bucket e a linha de nada. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | User.Read, para obter a tarefa do planejador Outlook To Do, sinalizar emails e atualizá-los. Para criar uma nova tarefa do Planner | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para mostrar os emails e enviar emails. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Obter o assunto de email do email selecionado. Permite que o aplicativo receba informações do email selecionado, permitindo copiar o campo de descrição para a descrição da tarefa e permitindo salvar anexos do email ou do próprio email para a tarefa. Enviar notificação. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter os usuários Outlook To Do e atualizar User.Read, para obter a tarefa do planejador Outlook To Do, sinalizar emails e atualizá-los. Para criar uma nova tarefa do Planner. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Entrar e ler o perfil do usuário | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O iGlobe coleta dados para operar efetivamente e fornecer as melhores experiências com nossos produtos e serviços. Para licenciamento: dados coletados para administrar sua&#8217;de licenciamento, como quando você implanta um Complementos Gratuitos, cria uma assinatura de avaliação ou compra uma assinatura. As informações a seguir são coletadas. 
- Para fins financeiros: nome da empresa e endereço
- Usuários inscritos: nome de usuário e email

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados estão no próprio locatário do cliente. Nenhum dado de aplicativo é armazenado. Um complemento moderno é executado em um navegador em área &#8220;fora do processo&#8221;. Ele interage com os dados dos usuários usando serviços Microsoft. O complemento só pode acessar os dados com os quais o usuário está trabalhando.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

