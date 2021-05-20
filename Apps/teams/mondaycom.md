---
title: Informações do aplicativo monday.com por monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para monday.com, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552922"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 28 de setembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo monday.com para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | monday.com |
| ID | WA200001798 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | monday.com |
| URL do site do parceiro | [https://monday.com](https://monday.com) |
| URL da Política de Privacidade | [https://monday.com/privacy](https://monday.com/privacy) |
| URL dos Termos de Uso | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo monday.com sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com usa os seguintes sub-processadores para o desempenho de seu serviço:&#160;https://monday.com/terms/subprocessors |  | monday.com não usa APIs. Usamos as seguintes estruturas da Microsoft para o desempenho do nosso serviço (conforme detalhado em nossa resposta acima): &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>monday.com armazena logs de aplicativos que contêm conteúdo gerado pelos usuários por um período limitado de tempo, a fim de permitir que nossa equipe de RD solucione problemas de bugs e relatados &amp; pelo usuário. Os logs de segurança que contêm endereços IP são mantidos por um período de tempo mais longo, de acordo com nossa política de retenção de dados.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>monday.com serviço é hospedado na infraestrutura AWS no Norte da Virgínia em várias Zonas de Disponibilidade, com um site de DR estabelecido em uma região diferente. Determinados dados de backup são armazenados em GCP (EUA, multi-região). O acesso ao serviço monday.com é controlado pelos administradores da organização do usuário e é obtido utilizando os seguintes recursos:
- Tipos de usuários
- Permissões no nível da conta
- Workplaces
- Tipos de quadro
- Permissões no nível da placa
- As permissões no nível de coluna monday.com suportam os seguintes métodos de autenticação:
- Credenciais
- SSO do Google (para Pro plano)
- Okta, OneLogin e SAML 2.0 personalizado (para o plano Enterprise) 2FA via SMS ou por meio de um aplicativo autenticador podem ser opcionalmente habilitados pelos administradores de conta por meio do painel de administração da plataforma.
Todos os dados em repouso são criptografados usando o AES-256. Todos os dados em trânsito em redes abertas são criptografados usando o TLS 1.3 (TLS 1.2 no mínimo).

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

