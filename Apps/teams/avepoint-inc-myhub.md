---
title: Informações do aplicativo para MyHub by AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o MyHub, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 391c44f4f1d06742d1002b713f5f24f69db7d01e
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52253182"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 21 de dezembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo AvePoint, inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | MyHub |
| ID | WA200000726 |
| Recursos | Bot, Guia |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | AvePoint, inc. |
| URL do site do parceiro | [https://www.avepoint.com](https://www.avepoint.com) |
| URL da Política de Privacidade | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL dos Termos de Uso | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo AvePoint, inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | ambos | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Ler dados do diretório | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | ambos | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Ler e gravar todos os grupos | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Mail.Send | delegado | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Enviar email como um usuário | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports.Read.All | aplicação | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Ler todos os relatórios de uso | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.FullControl.All | aplicação | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Ter controle total de todos os conjuntos de sites | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | aplicação | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Ler itens em todos os conjuntos de sites  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | delegado | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Editar ou excluir itens em todos os conjunto de sites | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | ambos | os dados de configuração do aplicativo são armazenados de um ponto de vista de manipulação de dados | Ler todos os usuários&#8217; perfis completos | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, o email do usuário e a ID do locatário aparecerão nos logs. Os logs são armazenados em local seguro e somente funcionários autorizados podem acessar durante a solução de problemas. Os logs serão arquivados após 60 dias para fins de auditoria de segurança e serão excluídos após um ano.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do Aplicativo são armazenados no Banco de Dados SQL do Azure e no Azure Armazenamento. O Azure SQL e a Armazenamento do Azure estão habilitados.
Somente administradores autorizados podem acessar os dados. O MFA é necessário para que os administradores faça logon. As operações são auditadas. A lista branca de IP também é usada para restringir o acesso aos dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

