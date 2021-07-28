---
title: Informações do aplicativo para SHL por SHL
ms.author: elmalova
author: elenamalova
ms.date: 06/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para SHL, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5c5b98779e7c038d809a8ecaee60fee1cdf0ca71
ms.sourcegitcommit: 0f47d02fff001cd7cba6a7ab9e276e020cfc053e
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/27/2021
ms.locfileid: "53609893"
---
# <a name="shl"></a>SHL

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 25 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/0c52adc0-18a0-45ca-b6ee-154cf1ef87e2" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002887" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SHL à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SHL |
| ID | WA200002887 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | SHL |
| URL do site do parceiro | [https://shl.com](https://shl.com) |
| URL da página Teams de informações do aplicativo | [https://www.shl.com/en/about/](https://www.shl.com/en/about/) |
| URL da Política de Privacidade | [https://www.shl.com/en/privacy/administrator-data-protectio...](https://www.shl.com/en/privacy/administrator-data-protection-notice/) |
| URL dos Termos de Uso | [https://www.shl.com/en/terms-of-service/](https://www.shl.com/en/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo SHL sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | delegado | Slots de calander compartilhados disponíveis | NA | [afd2c390-8b78-40fa-913b-7fc5911e884a](https://docs.microsoft.com/microsoft-365-app-certification/azure/afd2c390-8b78-40fa-913b-7fc5911e884a) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Transferemos dados para os serviços de nosso próprio aplicativo (Talentcentral : https://talentcentral.eu.shl.com/admin) | EUII : Microsoft teams Nome de usuário e id de usuário do teams | O nome de usuário Teams aplicativo é usado em nosso outro aplicativo que dispara emails com nome de usuário nele. e a ID do usuário que estamos mantendo como identificador e mapeando-a com nosso aplicativo&#8217;id de usuário. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O nome de usuário Teams aplicativo é usado em nosso outro aplicativo que dispara emails com nome de usuário nele. e id de usuário que estamos mantendo como identificador e mapeando-o com o nosso aplicativo&#8217;id de usuário | Nome de usuário do Microsoft teams e id de usuário do teams | O nome de usuário Teams aplicativo é usado em nosso outro aplicativo que dispara emails com nome de usuário nele. e id de usuário que estamos mantendo como identificador e mapeando-o com o nosso aplicativo&#8217;id de usuário |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não controlamos os dados, apenas processam os dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36654" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo SHL sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
