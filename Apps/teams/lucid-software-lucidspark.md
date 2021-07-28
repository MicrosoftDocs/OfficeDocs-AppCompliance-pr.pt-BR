---
title: Informações do aplicativo para o Lucidspark pelo Software Lúcido
ms.author: elmalova
author: elenamalova
ms.date: 05/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Lucidspark, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e79bed420b3081ae31a0abda25299610eeb1bc5f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525505"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 13 de maio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Software Lúcido para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Lucidspark |
| ID | WA200002583 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Lucid Software |
| URL do site do parceiro | [https://lucid.co](https://lucid.co) |
| URL da página Teams de informações do aplicativo | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| URL da Política de Privacidade | [https://lucid.co/privacy](https://lucid.co/privacy) |
| URL dos Termos de Uso | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Software Lúcido sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | Nome e endereço de email. | As permissões de email, openid e perfil permitem que o Lucidspark gere um token openid para um usuário e obter informações básicas suficientes sobre o usuário para registrar uma conta do Lucidspark para eles, se necessário. Para verificar os dados que vêm da Microsoft, fazemos uma solicitação para obter a chave pública com a assinatura da resposta. Nenhum outro dado é recebido ou enviado para a Microsoft como parte do nosso fluxo de SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| openid | delegado | Nome e endereço de email. | As permissões de email, openid e perfil permitem que o Lucidspark gere um token openid para um usuário e obter informações básicas suficientes sobre o usuário para registrar uma conta do Lucidspark para eles, se necessário. Para verificar os dados que vêm da Microsoft, fazemos uma solicitação para obter a chave pública com a assinatura da resposta. Nenhum outro dado é recebido ou enviado para a Microsoft como parte do nosso fluxo de SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| perfil | delegado | Nome e endereço de email. | As permissões de email, openid e perfil permitem que o Lucidspark gere um token openid para um usuário e obter informações básicas suficientes sobre o usuário para registrar uma conta do Lucidspark para eles, se necessário. Para verificar os dados que vêm da Microsoft, fazemos uma solicitação para obter a chave pública com a assinatura da resposta. Nenhum outro dado é recebido ou enviado para a Microsoft como parte do nosso fluxo de SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Os dados do Lucidspark e do lucidchart são armazenados no AWS e no Floco de Neve | Nome da organização, informações de contato e nível de licença | Não usamos APIs da Microsoft. Usamos o openID para obter dados básicos do usuário para executar o SSO. Usamos a API do se picker de arquivos, mas isso não nos dá acesso aos arquivos do usuário que não os que nos enviam por meio do se picker. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Registramos emails e endereços IP por motivos de segurança e suporte. Todo o acesso aos logs é &amp; gravado, na verdade, inalterável em um sistema de terceiros. O acesso aos logs requer MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do lucidspark e do lucidchart são armazenados no AWS. Ele é criptografado em repouso e em trânsito. Lúcido usa as regras de privilégio mínimo e MFA.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Software Lúcido sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
