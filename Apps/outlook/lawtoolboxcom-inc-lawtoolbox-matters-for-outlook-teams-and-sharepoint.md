---
title: Informações do aplicativo para LawToolBox Matters para Outlook, Teams &amp; SharePoint por LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para LawToolBox Matters para Outlook, Teams SharePoint, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do &amp; CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 450fd7c5f0752d523fb94e59308f8f339c95fad8
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428668"
---
# <a name="lawtoolbox-matters-for-outlook-teams-amp-sharepoint"></a>LawToolBox Importa Outlook, Teams &amp; SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de junho de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003103" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo LawToolBox.com Inc. para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | LawToolBox Importa Outlook, Teams &amp; SharePoint |
| ID | WA200003103 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior em Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | LawToolBox.com Inc. |
| URL do site do parceiro | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL da Política de Privacidade | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela LawToolBox.com Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | essa permissão é restrita acessando os contatos do usuário&#8217;que eles já têm acesso &#8211; usamos isso para permitir que os usuários recuperem suas próprias informações de calendário | [Opcional] Leia o calendário do usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | delegado | essa permissão é restrita acessando os contatos do usuário&#8217;que eles já têm acesso &#8211; usamos isso para permitir que os usuários recuperem suas próprias informações de calendário e escrevam em calendários | Para criar um convite de calendário para o calendário do usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | delegado | essa permissão é restrita acessando os contatos do usuário&#8217;que eles já têm acesso &#8211; usamos isso para permitir que os usuários recuperem suas próprias informações de calendário | Para criar o convite de calendário para o calendário compartilhado. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | delegado | essa permissão é restrita acessando os contatos do usuário&#8217;que eles já têm acesso.  Usamos essa permissão para permitir que o usuário pesquise seus contatos do O365 e adicione ao LawToolBox &#8211; não adicionamos automaticamente qualquer contato (isso pode ser revogado se você não quiser que esse recurso e contatos possam ser adicionados manualmente | [Opcional]- ler contatos do usuário e conectar usuários da lista de contatos ao grupo. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | delegado | usamos essa permissão para permitir que o usuário pesquise contatos compartilhados do O365 e adicione ao LawToolBox &#8211; não adicionamos nenhum contato automaticamente | [Opcional]- para ler os usuários contatos compartilhados para atender à lista de contatos relevantes para o caso. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | delegado | que usamos no portal de administração para recuperar a lista de usuários do locatário do O365 para adicionar à sua conta | [Opcional] Leia as informações de Grupos e Usuários como usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | delegado | que usamos no portal de administração para recuperar a lista de usuários do locatário do O365 para adicionar à sua conta | [Opcional] Leia as informações de Grupos e Usuários como usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | delegado | isso permite que o addin leia e liste os arquivos de usuário aos que o usuário já tem acesso | [Opcional] Leia a OneDrive. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | delegado | usamos essa permissão para ler e listar os arquivos de usuário aos que o usuário já tem acesso | [Optional]-Read user's OneDrive. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | delegado | lemos arquivos de Teams, grupos e OneDrive para reuniões (se você revogar isso impedirá que nosso complemento liste arquivos de assunto em nossos aplicativos) | [Opcional]-Ler e modificar arquivos no OneDrive. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | delegado | lemos arquivos de Teams, grupos e OneDrive para reuniões (se você revoá-lo impedirá que a LTB liste arquivos de assunto em nossos aplicativos).  O usuário só pode usar o addin para ler e listar os arquivos de usuário aos que o usuário já tem acesso | [Opcional] Arquivo de OneDrive do usuário de leitura/gravação associado à Matter. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | delegado | GroupID, GroupName, GroupEmail | Criamos um Grupo para cada assunto criado em nosso sistema. Isso ajuda o usuário a armazenar informações relacionadas à questão no Grupo, que, por sua vez, salva seus dados em seu próprio locatário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | delegado | usamos essa permissão para ler emails PACER em nosso complemento do outlook para abrir automaticamente esse assunto e também para ler contatos de seu email para adicionar ao nosso sistema de contatos  | [Opcional] [InProgress] Leia o email do usuário para Assuntos. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | delegado | usamos essa permissão para ler emails PACER em nosso complemento do outlook para abrir automaticamente esse assunto e também para ler contatos de seu email para adicionar ao nosso sistema de contatos  | [Opcional] [InProgress] Ler/gravar emails para usuários. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | delegado | usamos essa permissão para ler emails PACER em nosso complemento do outlook para abrir automaticamente esse assunto e também para ler contatos de seu email para adicionar ao nosso sistema de contatos  | [Opcional] [InProgress] Ler/gravar emails para usuários. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | delegado | Usamos esse envio de emails como o usuário para permitir que um usuário envie a si mesmo relatórios apenas de dados aos que eles já têm acesso em nosso sistema | [Opcional] [InProgress] Enviar Prazos no email como usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | delegado | essa permissão é restrita acessando o usuário&#8217;tarefas que eles já têm acesso &#8211; usamos isso para permitir que os usuários recuperem e atualizem suas próprias informações de TAREFA.  | [Optional]-[InProgress] Ler Prazos de Gravação como Tarefa para usuários. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | delegado | usado para sugerir contatos recentes para adicionar a reuniões ou contatos | Leia Informações do usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | delegado | usado para sugerir contatos recentes para adicionar a reuniões ou contatos | Informações do usuário de leitura/gravação. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | delegado | isso é necessário para ler a API Teams, criar Teams, criar evento Calendar, criar canais, Teams de compartilhamento de arquivos | Informações do usuário de leitura/gravação. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| email | delegado | Email, UserID do Office365, ObjectID, TenantID. | Leia o endereço de email do usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| perfil | delegado | isso é necessário para a autenticação SSO - também usamos essa permissão para recuperar imagens e nomes salvos no locatário do M365 para exibição para que o usuário saiba que está na caixa de ferramentas correta | Leia as informações do perfil do usuário. | [3ee373a-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>User Email,UserID, AccessToken, Groups information in our debug log

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Retêmos registros de caso, a menos que recebamos uma solicitação para excluir os dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela LawToolBox.com Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Para um administrador de controle maior pode implementar permissões de aplicativo |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | ,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/> |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
