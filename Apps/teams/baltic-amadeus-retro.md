---
title: Informações do aplicativo para Retrô pelo Amadeus Báltico
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Retro, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
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

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Amadeus Báltico à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Retro |
| ID | WA200001892 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Baltic Amadeus |
| URL do site do parceiro | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL da Política de Privacidade | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL dos Termos de Uso | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Amadeus Báltico sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O aplicativo retro tem sua própria API Web que não é considerada um serviço da Microsoft. Como mencionado anteriormente, ele armazena Email e Nome Completo para fins de identificação e exibição de conteúdo apropriado. Esses dados não são enviados a nenhum outro lugar. Além disso, Retro tem uma funcionalidade opcional para exportar dados de sprint para o espaço de confluência atlassiano. Para fazer isso, o usuário precisa inserir seu nome de usuário e senha de confluência. Esses dados são usados apenas para fazer solicitações autenticadas para api de confluência em nome do usuário e não são armazenados nem registrados em qualquer lugar. |  | Retro tem sua própria API Web que também está registrada no azure. Para usá-lo, o usuário deve ser autenticado por meio da Plataforma de Identidade da Microsoft. O usuário precisa ser autenticado para que o aplicativo Retro possa servidor de conteúdo específico do usuário |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot acessa a lista para verificar qual membro ingressou ou saiu da equipe. Com base nisso, ele adiciona ou desativa esse usuário do projeto para que o usuário não seja mais exibido na lista de participantes de sprint. | Email e FullName são vinculados e armazenados no banco de dados. O email é usado para identificação do usuário para exibir o conteúdo apropriado para o usuário conectado. FullName é usado para exibir as crias, para que outros usuários possam saber para quem estão avaliando ou escrevendo comentários.  |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não. O único processo que gera telemetria/logs no aplicativo Retro é o registro em log de erros. Os logs de erro não incluem QUALQUER EUII ou OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados são armazenados no banco de dados do sql server do azure. Ele é armazenado por meio do aplicativo Retro e do bot Retro.
Por padrão, o banco de dados sql do azure tem criptografia de dados transparente habilitada.
O banco de dados está bloqueado atrás da autenticação básica.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

