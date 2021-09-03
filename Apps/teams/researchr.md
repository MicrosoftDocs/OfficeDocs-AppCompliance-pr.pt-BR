---
title: Informações do aplicativo para researcHR por KBE&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para researcHR, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b57d492945766c8d65417cf2f1d642ea4ecb8aae
ms.sourcegitcommit: 23a1fdeaf3905ab5f7acfbb378c7c23aaedcdc29
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/03/2021
ms.locfileid: "58873720"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 5 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo KBE&#26666;&#24335;&#20250;&#31038; para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | researcHR |
| ID | WA200002557 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | KBE&#26666;&#24335;&#20250;&#31038; |
| URL do site do parceiro | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| URL da página Teams de informações do aplicativo | [https://app.researchr.work](https://app.researchr.work) |
| URL da Política de Privacidade | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| URL dos Termos de Uso | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo KBE&#26666;&#24335;&#20250;&#31038; sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | aplicação | Usamos esse escopo para permitir que nosso bot crie um novo canal no Teams cliente. Consulte: https://docs.microsoft.com/en-us/graph/api/channel-post | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | aplicação | Usamos esse escopo para obter as IDs de canal e os nomes para exibir esses dados em nosso site. Consulte: https://docs.microsoft.com/en-us/graph/api/channel-list | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | aplicação | Usamos esse escopo para obter as IDs de canal e os nomes para exibir esses dados em nosso site. Consulte: https://docs.microsoft.com/en-us/graph/api/channel-list | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | aplicação | Usamos esse escopo para obter os membros da equipe para que os usuários possam ver seus membros da equipe em nosso site. Consulte: https://docs.microsoft.com/en-us/graph/api/group-list-members | Não armazenamos esses dados no banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | aplicação | Usamos esse escopo para obter os canais ingressáveis do usuário para que os usuários possam ver suas equipes ingressáveis em nosso site. Consulte: https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | Não armazenamos esses dados em nosso banco de dados. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | delegado | Usamos esse escopo para habilitar o logon OAuth e coletar a ID do AAD do usuário, o token de acesso e o token de atualização. Consulte: https://docs.microsoft.com/en-us/graph/auth-v2-user | Armazenamos a ID AAD do usuário, o token de acesso e o token de atualização em nosso banco de dados para que o usuário possa fazer logon no nosso site com o OAuth. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | delegado | Usamos esse escopo para obter o token de atualização para que possamos atualizar o token de acesso dos usuários authed sem nenhuma interação do usuário. Consulte: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | Armazenamos o token de atualização em nosso banco de dados para que possamos atualizar o token de acesso sem nenhuma interação do usuário. | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


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

>Todos os dados no banco de dados são criptografados. Backups de dados de banco de dados serão feitos e armazenados por um determinado período de tempo, de acordo com nossa política operacional interna. Caso um usuário cancele esse serviço, excluiremos as informações do usuário sem atraso, exceto na medida do necessário para cumprir as obrigações de armazenamento estipuladas por lei. Aqui estão os detalhes. https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

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

Essas informações foram fornecidas pelo KBE&#26666;&#24335;&#20250;&#31038; sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
