---
title: Informações do aplicativo para Nuvem de Confluência pela Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Nuvem de Confluência, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83a34d3ae66bd3cb82fcc9d18ad88ba7ee7c4983
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276396"
---
# <a name="confluence-cloud"></a>Nuvem de Confluência

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 18 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Atlassian para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Nuvem de Confluência |
| ID | WA200003113 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Atlassian |
| URL do site do parceiro | [https://www.atlassian.com](https://www.atlassian.com) |
| URL da Política de Privacidade | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| URL dos Termos de Uso | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Atlassian sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Chat.ReadBasic | delegado |  - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | delegado | - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| email | delegado | - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | delegado | - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| openid | delegado |  - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| perfil | delegado |  - Lemos a lista de membros do Chat em uma reunião, portanto, sabemos a lista de convidados para a reunião.   - Lemos os usuários&#8217; nomes e endereços de email que exibimos condicionalmente em nosso aplicativo de reunião. Por exemplo, exibe o nome do usuário atual que está fazendo anotações de reunião.   - Nosso aplicativo lê o evento de calendário do usuário&#8217;em que nosso aplicativo foi adicionado a uma reunião, portanto, temos informações básicas sobre a reunião, como o título da reunião. | Exemplos de conteúdo que coletamos e armazenamos incluem: o resumo e a descrição adicionados a um problema JIRA, as páginas que você cria em Confluência, seus repositórios e solicitações de pull no Bitbucket, comentários que você inserir em conexão com um incidente em Statuspage e qualquer comentário que você fornecer para nós. O conteúdo também inclui os arquivos e links que você carrega para os Serviços. | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Atlassian sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Não |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
