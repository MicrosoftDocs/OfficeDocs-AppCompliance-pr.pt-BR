---
title: Informações do aplicativo para Hoylu por Hoylu
ms.author: elmalova
author: elenamalova
ms.date: 07/20/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Hoylu, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b48adaf3c3816bea363b0fd8e6581f061a5eaed1
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281854"
---
# <a name="hoylu"></a>Hoylu

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 20 de julho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/732e01bc-570a-43ac-9671-8c7fc4152662" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001573" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Hoylu à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Hoylu |
| ID | WA200001573 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Hoylu |
| URL do site do parceiro | [https://hoylu.com](https://hoylu.com) |
| URL da Política de Privacidade | [https://www.hoylu.com/privacy-policy/](https://www.hoylu.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.hoylu.com/terms-of-use/](https://www.hoylu.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Hoylu sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim. O registro em log é feito para segurança de aplicativos, e EUII e OII são coletados na forma de nome e sobrenome, email, endereço IP, ID da organização. O provedor de registro em log de Hoylu é Datadog. O Datadog certificou sua conformidade com a Estrutura de Proteção de Privacidade da UE-EUA e é um Registro STAR da Cloud Security Alliance (CSA). O Datadog também busca as principais validações independentes de terceiros de sua segurança, processos e serviços, incluindo a conclusão da auditoria do SOC 2 Type II. Um usuário pode solicitar a exclusão dessas informações por meio de um processo em conformidade com o RGPD a qualquer momento.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados em Serviços de Nuvem do Microsoft Azure e todos os protocolos de criptografia usados são compatíveis com FIPS 140-2. esses dados de produção só podem ser acessados pelos administradores de infraestrutura (PMA). A administração de contas da organização é feita por meio do Azure AD com 2FA.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

