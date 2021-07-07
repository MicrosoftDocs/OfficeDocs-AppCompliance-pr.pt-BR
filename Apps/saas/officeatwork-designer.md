---
title: Informações do aplicativo para Designer por officeatwork
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Designer, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 14c279da91489e679434e489f62945d9a99892d2
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53282464"
---
# <a name="designer"></a>Designer

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de junho de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.designer" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo officeatwork à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Designer |
| ID | officeatwork-ag.designer |
| Nome da empresa de parceiro | officeatwork |
| URL do site do parceiro | [https://www.officeatwork.com](https://www.officeatwork.com) |
| URL da Política de Privacidade | []() |
| URL dos Termos de Uso | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo officeatwork sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.Read | delegado | Nenhum dado é armazenado. | Contatos: para habilitar a leitura de todos os contatos do usuário que entrou. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Files.Read | delegado | Nenhum dado é armazenado. | OneDrive - Arquivos (Conteúdo): para habilitar a leitura dos arquivos do usuário de acesso. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Files.Read.All | delegado | Nenhum dado é armazenado. | Teams - Arquivos (Conteúdo): para habilitar a leitura de todos os arquivos do usuário de acesso. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Group.Read.All | delegado | Nenhum dado é armazenado. | Office 365 Usuários - Limite ao grupo: para habilitar a leitura de todos os grupos do usuário in-locar. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| Sites.Read.All | delegado | Nenhum dado é armazenado. | SharePoint Online: para habilitar a leitura de dados SharePoint Online. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.Read | delegado | Nenhum dado é armazenado. | Sing-In: para habilitar o aplicativo officeatwork para ler as propriedades básicas do usuário. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.Read.All | delegado | Nenhum dado é armazenado. | Office 365 Usuários - Todas as propriedades: para habilitar a leitura de todas as propriedades de todos os usuários. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| User.ReadBasic.All | delegado | Nenhum dado é armazenado. | Office 365 Usuários - Propriedades básicas: para habilitar a leitura das propriedades básicas de todos os usuários | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| offline_access | delegado | Nenhum dado é armazenado. | Sing-In: para habilitar a logona automática por meio de tokens de atualização, como sem, os usuários teriam que entrar manualmente sempre que iniciarem o aplicativo officeatwork. Esse escopo só é necessário para aplicativos host não habilitados para SSO. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| openid | delegado | Nenhum dado é armazenado. | Sing-In: para permitir que os usuários entre no aplicativo officeatwork com sua conta organizacional e/ou da Microsoft | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |
>| perfil | delegado | Nenhum dado é armazenado. | Sing-In: para mostrar o usuário de assinatura no aplicativo officeatwork. Isso ajuda a garantir/confirmar ao usuário qual conta foi usada para entrar no aplicativo officeatwork. | 0c67871c-ffbc-4b37-bd61-afce12b299f9 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| APIs REST do SharePoint | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, os eventos incluem oid e tenantId e são enviados para o Azure AppInsights. Os eventos são excluídos automaticamente após 90 dias. Se um cliente desejar excluir esses dados, ele poderá usar o link fornecido na declaração de privacidade para iniciar a exclusão desses dados.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados de configurações de aplicativos (sinalizadores de recursos, nome de exibição da organização, tenantId, lista de administradores oids) são armazenados em uma instância do Azure Cosmos DB (um arquivo por locatário). Os arquivos DB são criptografados e o acesso é restrito aos engenheiros de trabalho do officeatwork selecionados e à equipe de suporte. O cliente pode acessar e manipular os dados de configurações do aplicativo officeatwork usando o Aplicativo Web do Centro de Administração.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35749" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo officeatwork sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Padrões de segurança |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Não |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
