---
title: Informações do aplicativo para a AtBot by H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o AtBot, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d71404e66489ba3f1e81ca5f1a1a92c17b36f9e6
ms.sourcegitcommit: 7ef4a79aa28ac4dcce067b1f6f8693eeec6335e9
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/13/2021
ms.locfileid: "58239752"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 10 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela H3 Solutions, Inc. para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | AtBot |
| ID | WA104381219 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | H3 Solutions, Inc. |
| URL do site do parceiro | [https://atbot.io](https://atbot.io) |
| URL da página Teams de informações do aplicativo | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL da Política de Privacidade | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL dos Termos de Uso | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela H3 Solutions, Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | aplicação | Nome do grupo AAD, GUID do grupo AAD, UPN | Enumerar grupos AAD para permitir a recortação de segurança de habilidades de bot. Enumerar usuários para poder aplicar licenças. Enumerar usuários a adicionar como Administradores/Colaboradores | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| Directory.Read.All | delegado | Nome do grupo AAD, GUID do grupo AAD, UPN | Enumerar grupos AAD para permitir a recortação de segurança de habilidades de bot. Enumerar usuários para poder aplicar licenças. Enumerar usuários a adicionar como Administradores/Colaboradores | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| People.Read | delegado | Não | Enumerar pessoas em uma ação Obter Pessoa Flow.  Permite que o bot recupere pessoas do ponto de extremidade /People no Microsoft Graph. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| User.Read | delegado | ID de locatário, UPN | Nos dá acesso ao usuário&#8217;ID de Locatário e UPN para nos permitir a adoção de Fluxos/Aplicativos Lógicos criados aos usuários que os criaram. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| email | delegado | Os endereços de email são usados para contatar o suporte por meio do nosso sistema de suporte. | Nos dá acesso ao endereço de email do usuário. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| offline_access | delegado | Tokens de acesso/atualização. | Permite usar um token de atualização para manter os usuários conectados. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| openid | delegado | UPN, identifica o usuário em nosso sistema | Permite que os usuários faça logoff. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |
>| perfil | delegado | UPN | Acesso ao UPN do usuário. | [066a6b3a-f7a0-450a-98c7-34db1da31594](https://docs.microsoft.com/microsoft-365-app-certification/azure/066a6b3a-f7a0-450a-98c7-34db1da31594) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O bot pode acessar o UPN do usuário para @mention usuários ou enviar mensagens para eles. | UPN | Devemos armazenar o UPN para permitir que os usuários acessem o sistema |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>ID do locatário, UPN. Usamos aplicativos Insights e nossos logs durarão 90 dias antes de serem arquivados automaticamente. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os administradores têm a capacidade de excluir configurações de bot que podem conter nomes/GUIDs de grupo do AAD.
Após o cancelamento do serviço, todos os UPNs serão removidos do banco de dados de licenciamento.
Consulte 'Serviços do Azure' em Data Residency.  Grande parte dos dados específicos do cliente produzidos por meio do uso do AtBot é armazenada no locatário do cliente e, portanto, os administradores desse locatário têm controle total dos dados lá.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela H3 Solutions, Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
