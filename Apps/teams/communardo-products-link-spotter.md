---
title: Informações do aplicativo para o Identificador de Link por Produtos Communardo
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Identificador de Link, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8a6c2ee716c7e07686e2c62e1cd79196acbdc5a3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276222"
---
# <a name="link-spotter"></a>Link Spotter

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 27 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/9e486bb8-9633-48ba-8416-71da1d30cd08" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003092" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelos Produtos Communardo para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Link Spotter |
| ID | WA200003092 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Produtos Communardo |
| URL do site do parceiro | [https://www.communardo.com](https://www.communardo.com) |
| URL da página Teams de informações do aplicativo | [https://communardo.atlassian.net/wiki/spaces/LINK/overview](https://communardo.atlassian.net/wiki/spaces/LINK/overview) |
| URL da Política de Privacidade | [https://www.communardo.com/privacy-statement/](https://www.communardo.com/privacy-statement/) |
| URL dos Termos de Uso | [https://www.communardo.com/customer-agreement/](https://www.communardo.com/customer-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelos Produtos Communardo sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | Verificando a associação de canal do usuário atual | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| ChannelMessage.Read.All | aplicação | Urls dentro de mensagens, messageid, id de resposta para mensagem, id de canal, id de autor... Essas informações são necessárias porque Graph não fornece uma maneira performant de obter de volta todos os links postados em mensagens em um canal. Portanto, as mensagens devem ser analisadas ativamente para fornecer a funcionalidade do link em nossa Teams guia. | Urls dentro de mensagens, messageid, id de resposta para mensagem, id de canal, id de autor | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read | delegado | Entrar e ler o perfil do usuário | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read.All | aplicação | Determine quantos usuários estão tendo uma Teams de usuário. Usado para atualizar o tamanho da sede da assinatura de origem do aplicativo pago para o locatário do cliente. | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.ReadBasic.All | delegado | mostrando a imagem de perfil e o nome do autor da mensagem dentro do aplicativo | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| email | delegado | Conexão OpenID | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| offline_access | delegado | Conexão OpenID | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| openid | delegado | Conexão OpenID | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| perfil | delegado | Conexão OpenID | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API do Marketplace (API de atendimento saas) | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>ID do locatário, ID do canal, Usuários são capazes de remover os dados diretamente, Dados excluídos automaticamente após 90 dias

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>exclusão, política de usuário final

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelos Produtos Communardo sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
