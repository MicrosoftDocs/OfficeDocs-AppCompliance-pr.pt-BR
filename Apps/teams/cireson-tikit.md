---
title: Informações do aplicativo para Tikit por Cireson
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Tikit, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: de10b787d3e4100972e46efe76050ed0c7df31fd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553242"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 11 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Cireson à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Tikit |
| ID | WA200002602 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Cireson |
| URL do site do parceiro | [https://tikit.ai](https://tikit.ai) |
| URL da página Teams de informações do aplicativo | [https://tikit.ai](https://tikit.ai) |
| URL da Política de Privacidade | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| URL dos Termos de Uso | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Cireson sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | aplicação | Informações do gráfico do usuário usadas para o login único, por meio da comunicação do bot do teams  | Armazenamos funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID do usuário. Esse informe é usado para autenticação de aplicativos, segurança, RBAC, integração de equipes, notificações de equipes e mapeamento de relação de usuário   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | delegado | Nomes de grupo e funções para RBAC | Nome da Função de Grupo Nome, precisa fornecer controle de acesso &amp; mapeado seguro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | delegado | Nomes de grupo e funções para RBAC | Nome da Função de Grupo Nome, precisa fornecer controle de acesso &amp; mapeado seguro. | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | ambos | Nomes de grupo e funções para RBAC | Nomes de grupo e funções para RBAC | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | delegado | Funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID de usuário, usada para autenticação  | Funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID de usuário, usada para autenticação  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | aplicação | Funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID de usuário, usada para autenticação  | Funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID de usuário, usada para autenticação  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | delegado | Funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID de usuário, usada para autenticação  | Funções de usuário, nome da família, nome dado, email, ID do AAD, Teams ID de usuário, usada para autenticação  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| email | delegado | Email de usuário usado para logon e identificação associada de entidades relacionadas. &quot;Usuário atribuído&quot; | Email de usuário usado para logon e identificação associada de entidades relacionadas. &quot;Usuário atribuído&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | delegado | usado para autenticação via MSAL por requisitos  | usado para autenticação via MSAL por requisitos  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| perfil | delegado | usado para autenticação via MSAL por requisitos  | usado para autenticação via MSAL por requisitos  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Criador de QnA | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nome e email para relações de entidade do usuário &quot; Solicitador de Tíquete&quot;  | Nome e email  | para as relações de entidade do usuário &quot; Solicitante de Tíquete&quot;  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos Nome da Empresa, ID do Locatário, Email, ID do Cliente bot em insights do aplicativo, com uma política de retenção de 30 dat.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não temos dados em sistemas parceiros.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Cireson sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
