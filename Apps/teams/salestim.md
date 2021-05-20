---
title: Informações de aplicativo para SalesTim por SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para SalesTim, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
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

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SalesTim à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SalesTim |
| ID | WA200001393 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | SalesTim |
| URL do site do parceiro | [https://www.salestim.com](https://www.salestim.com) |
| URL da Política de Privacidade | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL dos Termos de Uso | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo SalesTim sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | delegado | Não | Permitir que o aplicativo instale e atualize seus próprios pacotes no catálogo de aplicativos corporativos. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | delegado | Não&#8217;armazenar apenas algumas IDs de usuários, não dados de perfil. | Permite que um usuário selecione outros usuários em vários locais no aplicativo, como selecionar aprovadores em um fluxo de trabalho. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | delegado | Não&#8217;apenas grupos/IDs de equipe,&#8217;não estamos armazenar conteúdo de grupos/equipes. | Permite que o aplicativo crie grupos, leia todas as propriedades e associações de grupo em nome do usuário associado. Além disso, permite aos proprietários do grupo gerenciar seus grupos, e permite aos membros do grupo atualizar o conteúdo do grupo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | delegado | Não&#8217;os metadados dessa ação, como a data da notificação, o destinatário (somente ID), a ID da solicitação. | Permite que o aplicativo envie emails de notificação por exemplo durante um fluxo de trabalho de aprovação. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | delegado | Estamos usando alguns serviços do Azure para armazenar dados, especialmente o Redis no Azure e Cosmos DB | Permite que o aplicativo gerencie as unidades (arquivos e pastas) associadas a uma equipe, durante um processo de provisionamento de equipe. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | delegado | Não&#8217;armazenar apenas algumas IDs de usuários, não dados de perfil. | Permite que o aplicativo leia o conjunto completo de propriedades de perfil, relatórios e gerentes de qualquer usuário. Ele é usado especialmente durante o processo de direcionamento de audiência, para filtrar alguns conteúdos com base no perfil de usuário atual. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offlineaccess | delegado | Não | Permite que o aplicativo execute algumas operações e ações em segundo plano como usuário. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Estamos usando o Intercom como nosso principal aplicativo de suporte. O interfone pode conter algumas informações básicas de perfil de usuário, conforme descrito aqui: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Estamos usando apIs GitHub para gerar problemas automaticamente do nosso ambiente de produção. Também armazenamos alguns logs técnicos no GitHub (conforme descrito aqui: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Esses problemas e logs podem conter algumas informações básicas de perfil de usuário. Esses problemas e logs são excluídos automaticamente a cada 15 dias. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Todos os dados coletados são descritos aqui: conforme descrito, os logs são temporariamente armazenados https://developers.salestim.com/platform/datamanagement.html#application-data por 15 dias e excluídos automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>A maioria dos dados é armazenada no Azure Cosmos DB.
O acesso ao ambiente de produção é restrito a duas pessoas, e essas contas de administrador são impostas pelo MFA.
Essas contas são dedicadas e diferentes de nossas contas corporativas.
Os dados são criptografados em repouso em todos os serviços do Azure que estamos usando.
As implantações em ambientes de produção são automatizadas por meio de uma ramificação protegida dedicada em nosso ambiente GitHub, onde apenas duas pessoas podem aprovar alterações.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

