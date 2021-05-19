---
title: Informações do aplicativo para diagramas de Lucidchart para Excel pela Lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para os Diagramas Lucidchart para Excel, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5481ed9ce5f8e589fe5ea8703fb48b53c5dab488
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548791"
---
# <a name="lucidchart-diagrams-for-excel"></a>Diagramas de Lucidchart para Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Lucid Software Inc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Diagramas de Lucidchart para Excel |
| ID | WA104380194 |
| Office 365 clientes suportados | Excel 2016 ou mais tarde no Mac, Excel 2013 ou mais tarde em Windows, Excel na Web |
| Nome da empresa parceira | Lucid Software Inc |
| URL do site de parceiros | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| URL da Política de Privacidade | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL de Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Lucid Software Inc sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Delegada | Nome e endereço de e-mail. | As permissões de e-mail, openid e perfil permitem que a Lucidchart gere um token openid para um usuário e obtenha informações básicas suficientes sobre o usuário para registrar uma conta lucidchart para eles, se necessário. Para verificar os dados que voltam da Microsoft, fazemos um pedido para obter a chave pública com a quais sua resposta está assinada. Nenhum outro dado é recebido ou enviado para a Microsoft como parte do nosso fluxo SSO. |  |
>| openid | Delegada | Nome e endereço de e-mail. | As permissões de e-mail, openid e perfil permitem que a Lucidchart gere um token openid para um usuário e obtenha informações básicas suficientes sobre o usuário para registrar uma conta lucidchart para eles, se necessário. Para verificar os dados que voltam da Microsoft, fazemos um pedido para obter a chave pública com a quais sua resposta está assinada. Nenhum outro dado é recebido ou enviado para a Microsoft como parte do nosso fluxo SSO. |  |
>| perfil | Delegada | Nome e endereço de e-mail. | As permissões de e-mail, openid e perfil permitem que a Lucidchart gere um token openid para um usuário e obtenha informações básicas suficientes sobre o usuário para registrar uma conta lucidchart para eles, se necessário. Para verificar os dados que voltam da Microsoft, fazemos um pedido para obter a chave pública com a quais sua resposta está assinada. Nenhum outro dado é recebido ou enviado para a Microsoft como parte do nosso fluxo SSO. |  |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript para Office | Sim | Usamos o Office OneDrive javascript SDK para abrir o seletor de arquivos OneDrive usando OneDrive.open(). Nós não geramos nenhum token de acesso e não fazemos nenhuma solicitação para OneDrive APIs nós mesmos; o OneDrive escolha de arquivos SDK faz isso por nós. Só vemos os nomes dos arquivos que o usuário escolhe. |  | Se o usuário selecionar um arquivo usando o OneDrive seletor de arquivos, armazenaremos o nome do arquivo. |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Os dados de Lucidchart são armazenados na AWS. |  | Não usamos nenhuma APIs microsoft. Usamos o openID para obter dados básicos do usuário para executar o SSO. Usamos sua API de catador de arquivos, mas isso não nos dá acesso aos arquivos do usuário além dos que eles nos submetem através do picker. |



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Registramos endereços de e-mail e IP por razões de segurança e suporte. Todo o acesso a logs é registrado &amp; logs são realmente imutáveis em um sistema de terceiros. O acesso aos registros requer MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados de Lucidchart são armazenados na AWS. É criptografado em repouso e em trânsito. Lucidchart usa as regras de menor privilégio e MFA.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

