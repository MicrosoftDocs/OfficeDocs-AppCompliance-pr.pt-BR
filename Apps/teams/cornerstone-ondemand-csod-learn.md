---
title: Informações do aplicativo para CSOD Learn by Cornerstone OnDemand
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o CSOD Learn, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c1ffba5aaa75b590f85a1012a3ccfafe28e20bc7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434370"
---
# <a name="csod-learn"></a>CSOD Aprender

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 1º de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/81726ee9-4d27-47ad-8b22-08147c6f8613" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003020" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Cornerstone OnDemand para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CSOD Aprender |
| ID | WA200003020 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Cornerstone OnDemand |
| URL do site do parceiro | [https://www.cornerstoneondemand.com](https://www.cornerstoneondemand.com) |
| URL da Política de Privacidade | [https://www.cornerstoneondemand.com/client-privacy-policy/](https://www.cornerstoneondemand.com/client-privacy-policy/) |
| URL dos Termos de Uso | [https://www.microsoft.com/en-us/microsoft-teams/group-chat-...](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Cornerstone OnDemand sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Os dados organizacionais são compartilhados entre os Serviços CSOD e a Microsoft. Para obter mais informações, consulte os termos de acordo com o CSOD | Os dados organizacionais são compartilhados entre os Serviços CSOD e a Microsoft. Para obter mais informações, consulte os termos de acordo com o CSOD | O serviço CSOD não usa GRAPH APIs. Usamos as estruturas da Microsoft botbuilder^4.9.2 para o desempenho do serviço. Os dados OII são usados pelo serviço para identificar o consumidor do serviço CSOD. Para obter mais informações, consulte os termos de acordo com o CSOD |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| consulte os termos de acordo com o CSOD para obter informações a este respeito | mapeamento aadObjectId do usuário final para ID interna do usuário CSOD | consulte os termos de acordo com o CSOD para obter informações a este respeito |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O serviço CSOD armazena logs de aplicativos que contêm interação do usuário com o aplicativo por um período limitado de tempo para solucionar bugs e problemas relatados pelo usuário. As instruções de log individuais são compostas por ID do usuário lms interno do usuário final, nome da organização configurado no serviço CSOD e a ação apropriada que está sendo executada. v

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O acesso ao serviço CSOD é controlado pelos administradores da organização do usuário final. Para obter mais informações, consulte os termos de acordo com o CSOD

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Cornerstone OnDemand sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
