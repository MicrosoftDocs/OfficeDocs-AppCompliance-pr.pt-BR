---
title: Informações do aplicativo para Chamada webex pela Cisco
ms.author: elmalova
author: elenamalova
ms.date: 01/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Webex Call, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 8cd5499529eb41a5a840c9a7792e9b47f9a6c877
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552282"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 4 de janeiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Cisco à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Webex Call |
| ID | WA200001495 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Cisco |
| URL do site do parceiro | [https://www.cisco.com/c/en/us/solutions/collaboration/webex...](https://www.cisco.com/c/en/us/solutions/collaboration/webex-teams.html) |
| URL da página Teams de informações do aplicativo | [N/A](N/A) |
| URL da Política de Privacidade | [https://www.cisco.com/c/en/us/about/legal/privacy-full.html](https://www.cisco.com/c/en/us/about/legal/privacy-full.html) |
| URL dos Termos de Uso | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Cisco sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.Read | delegado | Obter membros do chat para poder chamar o outro membro em chat privado com o Cisco WebEx | O aplicativo NÃO armazenaria dados em seus bancos de dados | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| Contacts.Read | delegado | Obter contatos de usuário, para que o usuário possa chamar contatos com o Cisco WebEx | O aplicativo NÃO armazenaria dados em seus bancos de dados | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.Read | delegado | obter email do usuário, telefones para que eles pudessem iniciar o Cisco WebEx para chamar emails ou telefones | O aplicativo NÃO armazenaria dados em seus bancos de dados | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadBasic.All | delegado | obter email do usuário, telefones para que eles pudessem iniciar o Cisco WebEx para chamar emails ou telefones | O aplicativo NÃO armazenaria dados em seus bancos de dados | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |
>| User.ReadWrite | delegado | Essa permissão é para armazenar informações de discagem de velocidade para a extensão do usuário | O aplicativo NÃO armazenaria dados em seus bancos de dados  | 9a7ce614-bdc8-4640-aaea-d8c626c58966 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Essa extensão de mensagem leria os emails/telefones dos membros do chat para que o usuário pudesse chamá-los com o Cisco WebEx | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Este aplicativo não armazena dados de usuário

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Cisco sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
