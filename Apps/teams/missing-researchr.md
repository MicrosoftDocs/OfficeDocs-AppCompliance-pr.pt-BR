---
title: Informações do aplicativo para researcHR por KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o researcHR, suas políticas de tratamento de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229005"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 5 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Exibir no Teams armazenamento</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo KBE&#26666;&#24335;&#20250;&#31038; à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | researcHR |
| ID | WA200002557 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | KBE&#26666;&#24335;&#20250;&#31038; |
| URL do site do parceiro | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL da página Teams informações do aplicativo | [https://app.researchr.work](https://app.researchr.work) |
| URL da Política de Privacidade | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL dos Termos de Uso | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo KBE&#26666;&#24335;&#20250;&#31038; sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para coletar?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **Azure AD ID do aplicativo** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | aplicação | Usamos esse escopo para permitir que nosso bot crie um novo canal no Teams cliente. Consulte: /graph/api/channel-post | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | aplicação | Usamos esse escopo para obter as IDs e os nomes do canal para exibir esses dados em nosso site. Consulte: /graph/api/channel-list | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | aplicação | Usamos esse escopo para obter as IDs e os nomes do canal para exibir esses dados em nosso site. Consulte: /graph/api/channel-list | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | aplicação | Usamos esse escopo para obter os membros da equipe para que os usuários possam ver seus membros da equipe em nosso site. Consulte: /graph/api/group-list-members | Não armazenamos esses dados no banco de dados externo. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | aplicação | Usamos esse escopo para obter os canais ingressados do usuário para que os usuários possam ver suas equipes unidas em nosso site. Consulte: /graph/api/user-list-joinedteams | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | Delegada | Usamos esse escopo para habilitar o logon do OAuth e coletar a ID de AAD do usuário, o token de acesso e o token de atualização. Consulte: /graph/auth-v2-user | Armazenamos a ID de AAD do usuário, o token de acesso e o token de atualização em nosso banco de dados para que o usuário possa fazer logon em nosso site com o OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97].. /azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | Delegada | Usamos esse escopo para obter o token de atualização para que possamos atualizar o token de acesso dos usuários autenticados sem nenhuma interação do usuário. Consulte: /azure/active-directory/develop/v2-permissions-and-consent#offline_access | Armazenamos o token de atualização em nosso banco de dados para que possamos atualizar o token de acesso sem nenhuma interação do usuário. | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não são serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se esse aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao qual ela é adicionada. Esse aplicativo usa essa funcionalidade?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria dos aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>Todos os dados no banco de dados são criptografados. Backups de dados de banco de dados serão feitos e armazenados por um determinado período de tempo de acordo com nossa política operacional interna. No caso de um usuário cancelar esse serviço, excluiremos as informações do usuário sem atraso, exceto na extensão necessária para atender às obrigações de armazenamento estipuladas por lei. Aqui estão os detalhes. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de todos os dados de OII (informações de identificação organizacional) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo KBE&#26666;&#24335;&#20250;&#31038; sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de identidade.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você integra-se ao Microsoft Identify Platform (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
