---
title: Informações de aplicativos para IndustryIntel por Equipe de Inteligência do Setor
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para IndustryIntel, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2c1c35d0054df773b83fa2d31a95daceaee585
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553062"
---
# <a name="industryintel"></a>IndustryIntel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/beb2be89-a403-46fe-9a67-c1294c9f9740" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001907" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Equipe de Inteligência do Setor à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | IndustryIntel |
| ID | WA200001907 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Industry Intelligence Team |
| URL do site do parceiro | [https://www.industryintel.com/public:about-us/our-team](https://www.industryintel.com/public:about-us/our-team) |
| URL da Política de Privacidade | [https://www.industryintel.com/public:legal/privacy-policy-m...](https://www.industryintel.com/public:legal/privacy-policy-msteams) |
| URL dos Termos de Uso | [https://www.industryintel.com/public:legal/terms-of-use](https://www.industryintel.com/public:legal/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Equipe de Inteligência do Setor sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para validar o usuário se o usuário tem acesso à rede de Inteligência do Setor. Se o usuário tiver sido validado com êxito, o usuário poderá usar o recurso completo de Bot e Extensão de Mensagens. | Armazenamos apenas a ID do membro da equipe que é para mapear a id w/ Industry Intelligence/id de usuário interno. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não. O mapeamento do usuário do MS Teams so e do usuário so Teams acontece no produto SO Teams. O MS Teams nos envia suas IDs identificáveis e salvamos essas mensagens internamente para mapear o usuário. Além disso, o MS Teams nos envia um JWT para solicitações de bot (impede falsificação de solicitação) e as solicitações de tabulação são validadas usando o cookie so.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O acesso a dados é protegido pelo sistema de intervalo IP e autenticado com segurança. Os dados são logicamente separados em seu próprio esquema SQL e armazenados em um conjunto separado de banco de dados. Seus dados são armazenados em um armazenamento de dados logicamente separado que é acessível somente por solicitações para sua Equipe.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36080' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36080" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

