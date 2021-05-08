---
title: Informações do aplicativo para CloudExtend Analytics para NetSuite por Celigo CloudExtend
ms.author: elmalova
author: elenamalova
ms.date: 04/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o CloudExtend Analytics para NetSuite, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 073e27fbf0e2ad9f0fcde35051b2109e5c068952
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52259004"
---
# <a name="cloudextend-analytics-for-netsuite"></a>CloudExtend Analytics para NetSuite

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 9 de abril de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002784" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Celigo CloudExtend para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CloudExtend Analytics para NetSuite |
| ID | WA200002784 |
| Clientes do Office 365 com suporte | Excel 2016 ou posterior no Mac, Excel 2016 ou posterior no Windows, Excel na Web |
| Nome da empresa de parceiro | Celigo CloudExtend |
| URL do site do parceiro | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL da Política de Privacidade | [https://www.celigo.com/privacy](https://www.celigo.com/privacy) |
| URL dos Termos de Uso | [https://www.cloudextend.io/agreements/ssa/2019-12](https://www.cloudextend.io/agreements/ssa/2019-12) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Celigo CloudExtend sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar todas [as permissões do Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | ambos | Leia o conjunto de sites para os quais o usuário tem acesso para obter informações da workbook compartilhada por meio de sites | siteid do store para acessar a workbook offline. | 7040f194-bf08-400e-acb1-69df7939416a |
>| Files.ReadWrite.All | ambos | Leia o conteúdo da pasta de trabalho como tabelas e planilha e seja capaz de gravar conteúdo nessas tabelas | detalhes da workbook, como url da Web, id da workbook e o local da workbook para acessá-la offline | 7040f194-bf08-400e-acb1-69df7939416a |


#### <a name="non-microsoft-services-used"></a>Serviços que não são da Microsoft usados

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os serviços que não são da Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Chargebee, NetSuite, Salesforce, Intercom, LogRocket, Amazon AWS | Nome da organização, número da conta NetSuite, endereços de email domínio da organização, informações de contato de cobrança | Provisionamento de licença, validação e cobrança Suporte ao cliente, solução de problemas e gerenciamento de contas |



#### <a name="add-in-data-access"></a>Acesso a dados do complemento

Listar as permissões necessárias para acessar os dados da sua organização, a justificativa e a finalidade dessa permissão (para que o aplicativo usa essas informações?) e se o aplicativo armazena qualquer uma dessas informações em seus bancos de dados.

>| **Permissão**  | **Descrição** |
>|:----------------|:----------------|
>| Documento ReadWrite | Pode ler e fazer alterações no documento |
>| Enviar Dados | Pode enviar dados pela Internet |

#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>endereço de email, 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do catálogo de Segurança do Aplicativo na [Nuvem](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) da Microsoft aparecem abaixo.

<iframe height='1020' title='Informações de Segurança do Aplicativo na Nuvem da Microsoft' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/14008' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/14008" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Celigo CloudExtend sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração da plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- Fluxo Implícito OAuth2, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
