---
title: Informações do aplicativo para Asana por Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para a Asana, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6c18bb20cdf753b1a5d998b3d7b7144f950f00c0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553402"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Asana à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Asana |
| ID | WA200001727 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Asana |
| URL do site de parceiros | [https://asana.com/?noredirect&amp;utm_source=asana_inproduct &amp; ut...](https://asana.com/?noredirect&amp;utm_source=asana_inproduct&amp;utm_medium=organic_inproduct&amp;utm_campaign=msft_teams_launch) |
| URL da Política de Privacidade | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL de Termos de Uso | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Asana sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O complemento transfere informações básicas de e-mail (remetente, receptivo, assunto, corpo) e anexos à Asana quando solicitado pelo usuário. |  | E-mail - Lê atualmente e-mail aberto quando exibido em um painel de tarefas. - Atualmente, os anexos de e-mail abrem para carregar as tarefas da Asana. - Isso fornece aos usuários a capacidade de fazer tarefas rapidamente em Asana com informações de e-mails. |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nosso aplicativo apenas registra informações relacionadas aos dados da Asana. A única vez que registramos algo relacionado a Outlook informações do usuário é quando o usuário anexa explicitamente um e-mail ou carrega um anexo à Asana, e mesmo assim não registramos o conteúdo. Registros de curto prazo existem em servidores que podem incluir alguns dados do usuário, mas são efêmeros e limitados a períodos inferiores a 72 horas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Enterprise clientes têm criptografia garantida em repouso usando o AES-256. Os dados são armazenados no Amazon Web Services e a AWS gerencia as chaves de criptografia usando seu sistema de gerenciamento de chaves. Temos 2FA para todos os administradores. O acesso é dado com o princípio do menor privilégio.
Seus administradores organizacionais asana têm a capacidade de configurar contas SAML, SCIM, Service e ter uma visão abrangente dos dados que são colocados na ferramenta. Os administradores podem solicitar uma exportação organizacional completa de dentro do console administrativo e auditoria conforme necessário.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

