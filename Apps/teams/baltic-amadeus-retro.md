---
title: Informações sobre o aplicativo para retro por Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Retro, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553452"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Baltic Amadeus à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Retro |
| ID | WA200001892 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Baltic Amadeus |
| URL do site de parceiros | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL da Política de Privacidade | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL de Termos de Uso | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Baltic Amadeus sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O aplicativo retrô tem sua própria API web que não é considerada um serviço da Microsoft. Como mencionado anteriormente, ele armazena e-mail e nome completo para identificação e finalidades de exibição de conteúdo apropriadas. Esses dados não são enviados para outro lugar. Além disso, o Retro tem uma funcionalidade opcional para exportar dados de sprint para o espaço de confluência atlassian. Para isso, o usuário precisa inserir seu nome de usuário e senha de confluência. Esses dados são usados apenas para fazer solicitações autenticadas para confluência api em nome do usuário e não são armazenados nem registrados em qualquer lugar. |  | O Retro tem uma API web própria que também está registrada no azure. Para usá-lo, o usuário deve ser autenticado através da Microsoft Identity Platform. O usuário tem que ser autenticado para que o aplicativo Retro possa servidor conteúdo específico do usuário |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot acessa a lista para verificar qual membro entrou ou deixou a equipe. Com base nisso, ele adiciona ou desativa esse usuário do projeto para que o usuário não seja mais exibido na lista de participantes do sprint. | O e-mail e o FullName estão ligados e são armazenados no banco de dados. O e-mail é usado para identificação do usuário, a fim de exibir conteúdo apropriado para o usuário logado. O FullName é usado para exibir puproses, para que outros usuários possam saber para quem estão avaliando ou escrevendo feedback.  |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não. O único processo que gera telemetria/logs no aplicativo Retro é o registro de erros. Os registros de erros não incluem nenhum EUII ou OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados são armazenados no banco de dados do servidor sql azul. É armazenado via aplicativo Retro e retro bot.
Por padrão, o banco de dados sql tem criptografia de dados transparente ativada.
O banco de dados está bloqueado atrás da autenticação básica.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

