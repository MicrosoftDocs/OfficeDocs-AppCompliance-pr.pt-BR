---
title: Informações do aplicativo para LawToolBox pela LawToolBox.com Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o LawToolBox, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2e97d65822a5baeb0cd78101660084e4142e98ea
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553002"
---
# <a name="lawtoolbox"></a>LawToolBox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381656" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela LawToolBox.com Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | LawToolBox |
| ID | WA104381656 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | LawToolBox.com Inc. |
| URL do site de parceiros | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| URL da página de informações do aplicativo Teams | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=718) |
| URL da Política de Privacidade | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| URL de Termos de Uso | [https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661](https://www.lawtoolbox.com/Ads/Adchk.cfm?eaid=661) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela LawToolBox.com Inc. sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | Delegada |  | [Opcional] Leia o calendário do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite | Delegada |  | Para criar o calendário, convide para o calendário do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Calendars.ReadWrite.Shared | Delegada |  | Para criar o calendário, convide para o calendário compartilhado. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite | Delegada |  | [Opcional]- ler contatos do usuário e conectar usuários da lista de contatos para o grupo. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Contacts.ReadWrite.Shared | Delegada |  | [Opcional]- ler usuários compartilhados contatos para servir a lista de contatos relevantes para o caso. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.AccessAsUser.All | Delegada |  | [Opcional] Leia informações sobre grupos e usuários como usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Directory.ReadWrite.All | Delegada |  | [Opcional] Leia informações sobre grupos e usuários como usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read | Delegada |  | [Opcional] Leia a OneDrive do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.Read.All | Delegada |  | [Opcional]-Leia a OneDrive do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite | Delegada |  | [Opcional]-Ler e modificar arquivos no OneDrive de um usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Files.ReadWrite.All | Delegada |  | [Opcional] Arquivo de OneDrive do usuário de leitura/gravação associado ao Assunto. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Group.ReadWrite.All | Delegada | GroupID, GroupName, GroupEmail | Criamos um Grupo para cada matéria criado em nosso sistema. Isso ajuda o usuário a armazena informações relacionadas à matéria no Grupo, que por sua vez salva seus dados em seu próprio inquilino. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Read | Delegada |  | [Opcional] [Em Progress] Leia o e-mail do usuário para Assuntos. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite | Delegada |  | [Opcional] [Em Progress] Ler/Escrever e-mail para usuários. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.ReadWrite.Shared | Delegada |  | [Opcional] [Em Progress] Ler/Escrever e-mail para usuários. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Mail.Send | Delegada |  | [Opcional] [Em Progress] Envie prazos no e-mail como usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| Tasks.ReadWrite.Shared | Delegada |  | [Opcional]-[InProgress] Leia prazos de gravação como tarefa para os usuários. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.Read | Delegada |  | Leia as informações do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite | Delegada |  | Ler/Escrever informações do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| User.ReadWrite.All | Delegada |  | Ler/Escrever informações do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| email | Delegada | E-mail, Office365 UserID, ObjectID, TenantID. | Leia o endereço de e-mail do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |
>| perfil | Delegada |  | Leia as informações do perfil do usuário. | 3ee373aa-62fa-4fc6-b11f-9627d5b4a73d |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para identificar o usuário recém-adicionado na equipe e verificar se há uma possível pista | E-mail, UserId |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>E-mail do usuário,UserID, AccessToken, Agrupa informações em nosso log de depuração

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Nós retemos registros de casos a menos que recebamos uma solicitação para excluir os dados.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35680" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

