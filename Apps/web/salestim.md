---
title: Informações do aplicativo para SalesTim
ms.author: elmalova
manager: tonybal
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Examine todas as informações de segurança e conformidade disponíveis para SalesTim, suas políticas de tratamento de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9bf1f4057ad73ba33a8ae3ba0ff02c74851cdecf
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/26/2022
ms.locfileid: "65688116"
---
# <a name="application-information-for-salestim-by-salestim"></a>Informações de aplicativo para SalesTim by SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de junho de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SalesTim para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | SalesTim |
| ID | salestim.salestim |
| Nome da empresa parceira | SalesTim |
| URL do site do parceiro | [https://nbold.co/](https://nbold.co/) |
| URL da Política de Privacidade | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL dos Termos de Uso | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo SalesTim sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para coletar?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **Azure AD ID do aplicativo** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegada | NÃO | Permitir que o aplicativo instale e atualize seus próprios pacotes no catálogo de aplicativos corporativos. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Delegada | Podemos&#8217;armazenar apenas algumas IDs de usuários, não dados de perfil. | Permite que um usuário selecione outros usuários em vários locais no aplicativo, como selecionar aprovadores em um fluxo de trabalho. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Delegada | Podemos&#8217;armazenar apenas grupos/IDs de equipes,&#8217;não estamos armazenando nenhum conteúdo de grupos/equipes. | Permite que o aplicativo crie grupos, leia todas as propriedades e associações do grupo em nome do usuário conectado. Além disso, permite aos proprietários do grupo gerenciar seus grupos, e permite aos membros do grupo atualizar o conteúdo do grupo. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Delegada | Podemos&#8217;armazenar os metadados dessa ação, como a data da notificação, o destinatário (somente ID), a ID da solicitação. | Permite que o aplicativo envie emails de notificação por exemplo durante um fluxo de trabalho de aprovação. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Delegada | Estamos usando alguns serviços do Azure para armazenar dados, especialmente o Redis no Azure e Cosmos DB | Permite que o aplicativo gerencie as unidades (arquivos e pastas) associadas a uma equipe durante um processo de provisionamento de equipe. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Delegada | Podemos&#8217;armazenar apenas algumas IDs de usuários, não dados de perfil. | Permite que o aplicativo leia o conjunto completo de propriedades, relatórios e gerentes de perfil de qualquer usuário. Ele é usado especialmente durante o processo de direcionamento de público-alvo, para filtrar alguns conteúdos com base no perfil de usuário atual. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | Delegada | Não | Permite que o aplicativo execute algumas operações e ações em segundo plano como um usuário. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII serviços Microsoft não serviços Microsoft são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Estamos usando o Intercom como nosso principal aplicativo de suporte. O intercomando pode conter algumas informações básicas de perfil do usuário, conforme descrito aqui: https://developers.salestim.com/platform/datamanagement.html#support-data | Nome da empresa | Estamos usando apIs GitHub para gerar problemas automaticamente do nosso ambiente de produção. Também estamos armazenando alguns logs técnicos em GitHub (conforme descrito aqui: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data). Esses problemas e logs podem conter algumas informações básicas do perfil do usuário. Esses problemas e logs são excluídos automaticamente a cada 15 dias. |



#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Todos os dados coletados são descritos aqui: https://developers.salestim.com/platform/datamanagement.html#application-data conforme descrito, os logs são armazenados temporariamente por 15 dias e excluídos automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>A maioria dos dados é armazenada no Azure Cosmos DB.
O acesso ao ambiente de produção é restrito a duas pessoas, e essas contas de administrador são impostas pela MFA.
Essas contas são dedicadas e diferentes das nossas contas corporativas.
Os dados são criptografados em repouso em todos os serviços do Azure que estamos usando.
As implantações em ambientes de produção são automatizadas por meio de uma ramificação protegida dedicada em nosso ambiente GitHub, em que apenas duas pessoas podem aprovar as alterações.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de todos os dados de OII (informações de identificação organizacional) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo SalesTim sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de identidade.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você integra-se ao Microsoft Identify Platform (Azure AD)?  | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa a MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | MFA, condições de localização |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multilocação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | ,<br/>- OAuth2 Flow implícito, a menos que seja necessário para um SPA<br/> |
| Seu aplicativo expõe alguma APIs Web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenha êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
