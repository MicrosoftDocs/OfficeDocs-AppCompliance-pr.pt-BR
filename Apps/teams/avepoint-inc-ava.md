---
title: Informações do aplicativo para AVA pelo AvePoint, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para AVA, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e5b53fbbc4c65c709324611a9ac645b045e4eaa7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429999"
---
# <a name="ava"></a>AVA

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de março de 2020</p>

* <a href="https://teams.microsoft.com/l/app/93106045-6f96-41e3-8a9d-694b6bbcac60" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381883" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo AvePoint, Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | AVA |
| ID | WA104381883 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | AvePoint, Inc. |
| URL do site do parceiro | [https://www.avepoint.com/](https://www.avepoint.com/) |
| URL da página Teams de informações do aplicativo | [https://www.avepoint.com/support/](https://www.avepoint.com/support/) |
| URL da Política de Privacidade | [https://www.avepoint.com/company/privacy-policy/](https://www.avepoint.com/company/privacy-policy/) |
| URL dos Termos de Uso | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo AvePoint, Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Mail.ReadWrite.Shared | delegado | Nenhum | Pesquisar emails do usuário e mover o email para a pasta especificada | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.Read | delegado |  Token de acesso do usuário - usado para pesquisar e restaurar dados do usuário | Permite que o usuário entre e dê o token de acesso ao aplicativo | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |
>| User.ReadWrite | delegado | DisplayName, UserPrincipalName, JobTitle, Organization, Country, MySiteUrl - grave as informações básicas do usuário que usou o aplicativo | Obter informações básicas de perfil do usuário | [6f30434d-3cfa-4cf8-9810-6fcf79ae750a](https://docs.microsoft.com/microsoft-365-app-certification/azure/6f30434d-3cfa-4cf8-9810-6fcf79ae750a) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| APIs REST do SharePoint | Sim | Pesquisar arquivo na reciclagem do site pessoal do usuário e restaurar esses arquivos. Requer permissão AllSites.Manage. |  | Nenhum |  |

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

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35842" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

