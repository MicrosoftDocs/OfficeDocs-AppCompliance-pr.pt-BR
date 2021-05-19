---
title: Informações de aplicação para Salesforce por salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Salesforce, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553702"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por salesforce.com à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Salesforce |
| ID | WA104379334 |
| Office 365 clientes suportados | Outlook 2013 ou mais tarde em Windows, Outlook 2016 ou mais tarde no Mac, Outlook na web |
| Nome da empresa parceira | salesforce.com |
| URL do site de parceiros | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL da Política de Privacidade | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL de Termos de Uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por salesforce.com sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>Este aplicativo não usa o Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript para Office | Sim | O complemento usa funções de Office.js e EWS para copiar conteúdo e anexos sobre um e-mail Outlook usuário decidiu fazer login no Salesforce. Recursos semelhantes são usados no lado do calendário, para registrar compromissos no Salesforce. |  | O complemento usa funções como obter o UsuárioIdentityTokenAsync para obter a identidade de usuário atual Outlook, GetItem (.js e EWS) para obter e definir Propostas Adicionais e o conteúdo da mensagem de e-mail atual ao salvar os registros do Salesforce, GetAttachment (EWS) para recuperar os anexos de Exchange e adicionar ao e-mail do Salesforce emparelhado, UpdateItem (.js), GetFolder (.js) para obter a pasta de rascunhos, CreateItem (.js), que é usada para criar uma mensagem de rascunho. |  |
>| Serviços Web do Exchange (EWS) | Sim | O complemento usa funções de Office.js e EWS para copiar conteúdo e anexos sobre um e-mail Outlook usuário decidiu fazer login no Salesforce. Recursos semelhantes são usados no lado do calendário, para registrar compromissos no Salesforce. |  | O complemento usa funções como obter o UsuárioIdentityTokenAsync para obter a identidade de usuário atual Outlook, GetItem (.js e EWS) para obter e definir Propostas Adicionais e o conteúdo da mensagem de e-mail atual ao salvar os registros do Salesforce, GetAttachment (EWS) para recuperar os anexos de Exchange e adicionar ao e-mail do Salesforce emparelhado, UpdateItem (.js), GetFolder (.js) para obter a pasta de rascunhos, CreateItem (.js), que é usada para criar uma mensagem de rascunho. |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O armazenamento do Salesforce é descrito no Guia de Segurança em https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

