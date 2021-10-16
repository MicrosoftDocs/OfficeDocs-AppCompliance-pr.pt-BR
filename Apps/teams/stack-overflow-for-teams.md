---
title: Informações do aplicativo para estouro de pilha para Teams por Estouro de Pilha
ms.author: elmalova
author: elenamalova
ms.date: 12/17/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Stack Overflow para Teams, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3c6493326d8b58ad4c8e7e4fc5486a7f03cd2b8b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410835"
---
# <a name="stack-overflow-for-teams"></a>Stack Overflow para o Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 6 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/4783e622-5303-4ea7-a211-ef0dd405da73" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000739" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Stack Overflow para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Stack Overflow para o Teams |
| ID | WA200000739 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Stack Overflow |
| URL do site do parceiro | [https://www.stackoverflow.com](https://www.stackoverflow.com) |
| URL da Política de Privacidade | [https://stackoverflow.com/legal/privacy-policy](https://stackoverflow.com/legal/privacy-policy) |
| URL dos Termos de Uso | [https://stackoverflow.com/legal/terms-of-service/teams](https://stackoverflow.com/legal/terms-of-service/teams) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Stack Overflow sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O bot usa a API de conversa para postar mensagens diretamente no chat das equipes. O bot também usa a lista para enviar mensagens diretas aos usuários | Não armazenamos dados da lista |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não. O mapeamento do usuário do MS Teams so e do usuário so Teams acontece no produto SO Teams.
O MS Teams nos envia suas IDs identificáveis e salvamos essas mensagens internamente para mapear o usuário.
Além disso, o MS Teams nos envia um JWT para solicitações de bot (impede falsificação de solicitação) e as solicitações de tabulação são validadas usando o cookie so.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Construímos nosso programa de segurança com base no ISO27001. Os dados são logicamente separados em seu próprio esquema SQL e armazenados em um conjunto separado de banco de dados. Seus dados são armazenados em um armazenamento de dados logicamente separado que é acessível somente por solicitações para sua Equipe.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/23308' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/23308" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


