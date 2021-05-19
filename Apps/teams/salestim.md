---
title: Informações do aplicativo para SalesTim pelo SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para o SalesTim, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553912"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 27 de outubro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SalesTim à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SalesTim |
| ID | WA200001393 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | SalesTim |
| URL do site de parceiros | [https://www.salestim.com](https://www.salestim.com) |
| URL da Política de Privacidade | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL de Termos de Uso | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo SalesTim sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegada | Não | Permita que o aplicativo instale e atualize seus próprios pacotes no catálogo de aplicativos corporativos. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegada | Nós&#8217;resinduem apenas os IDs de alguns usuários, não os dados do perfil. | Permite que um usuário selecione outros usuários em vários lugares do aplicativo, como selecionar aprovadores em um fluxo de trabalho. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegada | Nós&#8217;apenas resarem os IDs de grupos/equipes,&#8217;não estamos armazenando nenhum conteúdo de grupos/equipes. | Permite que o aplicativo crie grupos, leia todas as propriedades do grupo e associações em nome do usuário de assinatura. Além disso, permite aos proprietários do grupo gerenciar seus grupos, e permite aos membros do grupo atualizar o conteúdo do grupo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegada | &#8217;ressardia os metadados desta ação, como a data da notificação, destinatário (somente 80 de setembro), solicitar 1D. | Permite que o aplicativo envie e-mails de notificação, por exemplo, durante um fluxo de trabalho de aprovação. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegada | Estamos usando alguns serviços do Azure para armazenar dados, especialmente Redis no Azure e Cosmos DB | Permite que o aplicativo gerencie as unidades (arquivos e pastas) associadas a uma equipe, durante um processo de provisionamento da equipe. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegada | Nós&#8217;resinduem apenas os IDs de alguns usuários, não os dados do perfil. | Permite que o aplicativo leia o conjunto completo de propriedades de perfil, relatórios e gerentes de qualquer usuário. Ele é usado especialmente durante o processo de segmentação do público, para filtrar alguns conteúdos com base no perfil atual do usuário. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| acesso offline | Delegada | Não | Permite que o aplicativo realize algumas operações e ações em segundo plano como usuário. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Estamos usando o Intercom como nossa principal aplicação de suporte. O Intercom pode conter algumas informações básicas do perfil do usuário, conforme descrito aqui: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Estamos usando GitHub APIs para gerar problemas automaticamente a partir do nosso ambiente de produção. Também estamos armazenando alguns registros técnicos em GitHub (como descrito aqui: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Esses problemas e logs podem conter algumas informações básicas do perfil do usuário. Esses problemas e logs são automaticamente excluídos a cada 15 dias. |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Todos os dados coletados são descritos aqui: https://developers.salestim.com/platform/datamanagement.html#application-data Como descrito, os logs são temporariamente armazenados por 15 dias e depois excluídos automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>A maioria dos dados são armazenados no Azure Cosmos DB.
O acesso ao ambiente de produção é restrito a duas pessoas, e essas contas administrativas são aplicadas pelo MFA.
Essas contas são dedicadas e diferentes de nossas contas corporativas.
Os dados são criptografados em repouso em todos os serviços Azure que estamos usando.
As implantações em ambientes de produção são automatizadas através de um ramo protegido dedicado em nosso ambiente GitHub, onde apenas duas pessoas podem aprovar mudanças.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

