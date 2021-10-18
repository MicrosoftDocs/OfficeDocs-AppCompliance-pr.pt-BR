---
title: Informações do aplicativo para decisões por decisões
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Decisões, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a55735ce15a0708c366622beae9e953928d83104
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428618"
---
# <a name="decisions"></a>Decisions

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Decisões para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Decisions |
| ID | WA104381880 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Decisions |
| URL do site do parceiro | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL da página Teams de informações do aplicativo | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| URL da Política de Privacidade | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| URL dos Termos de Uso | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Decisões sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Usado para ler informações do calendário&#8217;usuário para habilitar recursos como a lista de reuniões e a pesquisa. Ele também oferece ao usuário uma opção para excluir reuniões específicas do calendário quando o item é excluído de Decisões. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | delegado | Usado para enviar decisões para votação e criar listas de alto-falantes para itens de agenda individuais diretamente para o Microsoft Teams de reunião. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | delegado | Usado para coletar informações básicas sobre o Office 365 locatário quando registrado, como nome do locatário e domínios verificados. Também é necessário verificar associações de grupo. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | delegado | Usado para ler arquivos compartilhados com o usuário para mesclar esses arquivos no Pdf Meeting Book. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | delegado | Usado para fornecer suporte aos usuários para anotações de arquivo pessoal. Os arquivos anotados são armazenados em particular no&#8217;usuário OneDrive for Business. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | delegado | Usado para criar estruturas de pastas no Office 365 site&#8217;grupo SharePoint agendas de reuniões, arquivos relacionados e conversas de grupo.   Observação: os usuários de Decisões nunca terão acesso a recursos (por exemplo, grupos) aos que eles ainda não têm acesso no locatário de Office 365 da sua organização. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | delegado | Usado para permitir que os usuários de Decisões enviem notificações de participantes da reunião, como atualizações de agenda e links para a reunião para coautor. Os emails vão para os participantes da reunião ou para a lista de distribuição selecionada pelo proprietário da reunião. Todas as notificações e emails enviados são ativamente feitos pelos usuários de Decisões.  Observação: isso não dá ao usuário acesso à sua caixa de entrada por meio de Decisões. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | delegado | Usado para identificar um usuário&#8217;preferências de idioma. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | delegado | Usado para configurar blocos de anotações particulares para reuniões para fazer anotações e preparar comentários e perguntas. Ele também permite que os minutos de reunião de grupo sejam armazenados em seu bloco de anotações OneNote compartilhado, caso o grupo opte por usar OneNote. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | delegado | Use para criar estruturas de pastas em canais privados para informações de reunião. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | delegado | Usado para sincronizar tarefas e decisões com o Microsoft Planner. Ele também permite que os usuários exportem tarefas e decisões para Excel. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | delegado | Necessário para instalar programaticamente o Aplicativo de Decisões no chat. Isso é necessário antes de adicionar a Guia Decisões para a experiência na reunião. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | delegado | Necessário para instalar programaticamente o Aplicativo de Decisões no chat. Isso é necessário antes de adicionar a Guia Decisões para a experiência na reunião. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | delegado | É necessário adicionar a guia In-Meeting/Channel Teams. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | delegado | Necessário para verificar se a guia está instalada ou não. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | delegado | Usado para exibir nome e sobrenome, foto e endereço de email de membros do grupo e participantes externos. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| perfil | delegado | Usado para entrar. | Os dados do cliente são armazenados no locatário&#8217;cliente Office 365 e todos os dados do cliente são processados somente em dispositivos do cliente. O banco de dados de Decisões mantém apenas referências a objetos nos clientes Office 365 locatário, não os dados reais. Consulte para https://www.meetingdecisions.com/security-and-privacy obter mais detalhes. | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados fornecidos pelo Cliente durante o uso do Software só estão disponíveis para o Cliente.  O Serviço é fornecido no Microsoft Office 365 Cloud Services e Microsoft Azure. Todos os dados do cliente são armazenados nos clientes Microsoft Office 365 locatário. Todos os dados armazenados ou processados no serviço são anônimos e não rastreáveis para pessoas individuais. Dessa forma, as Decisões não armazenarão, coletarão ou processarão dados pessoais em nome do Cliente.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Decisões sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Tudo |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
