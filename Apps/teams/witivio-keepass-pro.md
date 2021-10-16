---
title: Informações do aplicativo para a Pro por Witivio
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Keepass Pro, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 00c353d404015ae702ea6257bc6d6377a08fc5d5
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410785"
---
# <a name="keepass-pro"></a>Keepass Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 12 de outubro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/dc00c22b-b7ad-4db8-bf35-c2660104d622" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003336" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Witivio à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Keepass Pro |
| ID | WA200003336 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Witivio |
| URL do site do parceiro | [https://www.witivio.com](https://www.witivio.com) |
| URL da página Teams de informações do aplicativo | [https://www.teams-pro.com/en/browse-apps/keypass-pro/](https://www.teams-pro.com/en/browse-apps/keypass-pro/) |
| URL da Política de Privacidade | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| URL dos Termos de Uso | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Witivio sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | delegado | Ler e gravar o arquivo kbdx no sharepoint/onedrive do usuário | Logon e Senhas no arquivo KDBX. O Witivio não armazena dados em servidores | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| User.Read | delegado | Recuperar as propriedades e as relações do objeto user | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| email | delegado | Exibir o endereço de email dos usuários.    | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| openid | delegado | Entre usuários. | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |
>| perfil | delegado | Exibir o perfil básico dos usuários.  | N/D | [597cc93d-8951-4f62-b549-eca97ba5c042](https://docs.microsoft.com/microsoft-365-app-certification/azure/597cc93d-8951-4f62-b549-eca97ba5c042) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>leitura, escrita e exclusão

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Witivio sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

