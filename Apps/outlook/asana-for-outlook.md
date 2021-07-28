---
title: Informações do aplicativo para Asana para Outlook por Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Asana para Outlook, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 412b9d00d98f955dae3624d7d015970901afcba7
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527407"
---
# <a name="asana-for-outlook"></a>Asana para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de novembro de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Asana à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Asana para Outlook |
| ID | WA104381833 |
| Office 365 clientes com suporte | Outlook 2016 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | Asana |
| URL do site do parceiro | [https://asana.com](https://asana.com) |
| URL da Política de Privacidade | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL dos Termos de Uso | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Asana sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| O complemento transfere informações básicas de email (remetente, recepiente, assunto, corpo) e anexos para Asana quando solicitado pelo usuário. |  | Email - Lê o email aberto no momento quando exibido em um painel de tarefas. - Atualmente, lê anexos de email abertos para carregar em tarefas asanas. - Isso fornece aos usuários a capacidade de realizar tarefas rapidamente no Asana com informações de emails. |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nosso aplicativo registra apenas informações relacionadas aos dados asana. A única vez que registramos qualquer coisa relacionada Outlook informações do usuário é quando o usuário anexa explicitamente um email ou carrega um anexo ao Asana e, mesmo assim, não registramos o conteúdo. Os logs de curto prazo existem em servidores que podem incluir alguns dados do usuário, mas são efêmeros e limitados a períodos menores que 72 horas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Enterprise a criptografia garantida em repouso usando o AES-256. Os dados são armazenados no Amazon Web Services e o AWS gerencia as chaves de criptografia usando seu sistema de Gerenciamento de Chaves. Temos 2FA para todos os administradores. O acesso é dado com base no princípio do privilégio mínimo.
Seus administradores organizacionais asana têm a capacidade de configurar saml, SCIM, contas de serviço e ter uma exibição abrangente dos dados que são colocados na ferramenta. Os administradores podem solicitar uma exportação organizacional completa de dentro do console de Administração e auditoria, conforme necessário.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

