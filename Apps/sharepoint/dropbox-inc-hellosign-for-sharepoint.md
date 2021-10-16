---
title: Informações do aplicativo helloSign para SharePoint por Dropbox Inc.
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o HelloSign para SharePoint, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5ff681f19369a1020cd67e6c161fb1a1dcca135e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412090"
---
# <a name="hellosign-for-sharepoint"></a>HelloSign para SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de agosto de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003245" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Dropbox Inc. para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | HelloSign para SharePoint |
| ID | WA200003245 |
| Office 365 clientes com suporte | SharePoint 2013 ou posterior |
| Nome da empresa de parceiro | Dropbox Inc. |
| URL do site do parceiro | [https://hellosign.com](https://hellosign.com) |
| URL da Política de Privacidade | [https://www.hellosign.com/privacy](https://www.hellosign.com/privacy) |
| URL dos Termos de Uso | [https://hellosign.com/terms](https://hellosign.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Dropbox Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | aplicação | Isso é usado com Sites.ReadWrite.All para gravar arquivos assinados helloSign de volta ao site SharePoint site | Não armazenamos dados referentes a esse escopo | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| Sites.ReadWrite.All | aplicação | Isso é usado com Files.ReadWrite.All para gravar arquivos assinados helloSign de volta ao SharePoint site | Não armazenamos dados referentes a esse escopo | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| User.Read | delegado | Email usado para identificar o usuário no aplicativo | Email usado para fazer referência cruzada com nossas contas HelloSign com base no email | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint API | Sim | Email, ID do Locatário e ID do Site | Usado para fins de identificação e autenticação | Email, ID do Locatário, ID do Site | Usado para fins de identificação e autenticação |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.hellosign.com/subprocessors | Email, ID do Locatário, ID do Site | O JN Projects, Inc. dba HelloSign (&#8220;HelloSign&#8221;) usa determinados subprocessadores para ajudar no fornecimento de nossos Serviços. Usamos provedores de serviços que podem armazenar e processar dados pessoais sobre você e seus usuários finais (cada um, um &#8220;Sub-Processor&#8221;). Esta página fornece informações importantes sobre a identidade, o local e a função desses sub-processadores materiais. Os termos usados nesta página, mas não definidos, têm o significado definido em nosso contrato de Termos de Serviço (o &#8220;contrato&#8221;). |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Temos recursos de exclusão, retenção e registro em log para nossos dados que residem em sistemas parceiros

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Dropbox Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

