---
title: Informações do aplicativo para Salesforce por salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Salesforce, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d0490ea422179e064443f7fad12abb64bc6efa47
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53527907"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo salesforce.com para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Salesforce |
| ID | WA104379334 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior em Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | salesforce.com |
| URL do site do parceiro | [https://www.salesforce.com](https://www.salesforce.com) |
| URL da Política de Privacidade | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| URL dos Termos de Uso | [https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC...](https://store.office.com/en-us/WebAppLandingPage.aspx?p4=TC&amp;p5=WA104379334&amp;cmu=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo salesforce.com sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API JavaScript para Office | Sim | O complemento usa funções do Office.js e do EWS para copiar conteúdo e anexos sobre um email que um usuário Outlook decidiu fazer logoff no Salesforce. Recursos semelhantes são usados no lado do calendário, para registrar compromissos no Salesforce. |  | O complemento usa funções como getUserIdentityTokenAsync para obter a identidade de usuário atual do Outlook, GetItem (.js e EWS) para obter e definir AdditionalProperties e o conteúdo da mensagem de email atual ao salvar em registros do Salesforce, GetAttachment (EWS) para recuperar os anexos do Exchange e adicionar ao email do Salesforce emparelhado, UpdateItem (.js), GetFolder (.js) para obter a pasta rascunhos, CreateItem (.js), que é usada para criar uma mensagem de rascunho. |  |
>| Serviços Web do Exchange (EWS) | Sim | O complemento usa funções do Office.js e do EWS para copiar conteúdo e anexos sobre um email que um usuário Outlook decidiu fazer logoff no Salesforce. Recursos semelhantes são usados no lado do calendário, para registrar compromissos no Salesforce. |  | O complemento usa funções como getUserIdentityTokenAsync para obter a identidade de usuário atual do Outlook, GetItem (.js e EWS) para obter e definir AdditionalProperties e o conteúdo da mensagem de email atual ao salvar em registros do Salesforce, GetAttachment (EWS) para recuperar os anexos do Exchange e adicionar ao email do Salesforce emparelhado, UpdateItem (.js), GetFolder (.js) para obter a pasta rascunhos, CreateItem (.js), que é usada para criar uma mensagem de rascunho. |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O armazenamento do Salesforce é descrito no Guia de Segurança em https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

