---
title: Informações de aplicação para AtBot pela H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o AtBot, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552132"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela H3 Solutions, Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | AtBot |
| ID | WA104381219 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | H3 Solutions, Inc. |
| URL do site de parceiros | [https://atbot.io](https://atbot.io) |
| URL da página de informações do aplicativo Teams | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL da Política de Privacidade | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL de Termos de Uso | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela H3 Solutions, Inc. sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | aplicação | Nome do Grupo AAD, AAD Group GUID, UPN | Enumerar grupos AAD para permitir o corte de segurança das habilidades de bot. Enumerar usuários para poder aplicar licenças. Enumerar usuários para adicionar como administradores/colaboradores | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | Delegada | Nome do Grupo AAD, AAD Group GUID, UPN | Enumerar grupos AAD para permitir o corte de segurança das habilidades de bot. Enumerar usuários para poder aplicar licenças. Enumerar usuários para adicionar como administradores/colaboradores | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | Delegada | Não | Enumerar pessoas em uma ação Get Person de Flow.  Permite que o bot recupere pessoas do ponto final /People na Microsoft Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | Delegada | ID do inquilino, UPN | Nos dá acesso ao usuário&#8217;ID de Inquilino e UPN para nos permitir vincular Fluxos/Aplicativos lógicos criados aos usuários que os criaram. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | Delegada | Não | Nos dá acesso ao endereço de e-mail do usuário. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | Delegada | Tokens de acesso/atualização. | Permite-nos usar um token de atualização para manter os usuários conectados. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | Delegada | Não | Permite que os usuários façam login. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| perfil | Delegada | UPN | Acesso à UPN do usuário. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| A criação de menções em mensagens de bate-papo geradas por bots | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>ID do inquilino, UPN Usamos Insights de Aplicativos e nossos registros durarão 90 dias antes de serem arquivados automaticamente. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os administradores têm a capacidade de excluir configurações de bots que podem conter nomes de grupos AAD/GUIDs.
Após o cancelamento do serviço, todas as UPNs serão removidas do banco de dados de licenciamento.
Consulte 'Azure Services' em Data Residency.  Grande parte dos dados específicos do cliente produzidos através do uso do AtBot é armazenado no inquilino do cliente e assim os administradores desse inquilino têm controle total dos dados lá.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

