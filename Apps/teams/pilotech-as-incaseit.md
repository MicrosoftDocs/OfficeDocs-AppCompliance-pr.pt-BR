---
title: Informações do aplicativo para InCaseIT por Pilotech AS
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para InCaseIT, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: dbc393582f4146c8cf9b44da122b35629df59a83
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785398"
---
# <a name="incaseit"></a>InCaseIT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/4420b597-c1d5-4d40-ba81-2b2a78575c81" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003265" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Pilotech AS à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | InCaseIT |
| ID | WA200003265 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Pilotech AS |
| URL do site do parceiro | [https://incaseit.com](https://incaseit.com) |
| URL da página Teams de informações do aplicativo | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/introduction-to-incaseit-version-2-0) |
| URL da Política de Privacidade | [https://www.incaseit.com/privacy-policy/](https://www.incaseit.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/1-4-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Pilotech AS sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Os únicos dados usados são a confirmação explícita pelos usuários para permitir que o aplicativo use um token de acesso para chamar a API Graph. | Nosso aplicativo armazena apenas um link para a reunião agendada para facilitar a acessibilidade de reunião para os usuários.  Exemplo. 1. Crie uma reunião Teams agendada. 2. Salve o link de reunião no banco de dados 3. Use o link de reunião para um botão no aplicativo para facilitar o acesso à reunião. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| OnlineMeetings.ReadWrite | delegado | Os únicos dados usados são a confirmação explícita pelos usuários para permitir que o aplicativo use um token de acesso para chamar a API Graph. | Nosso aplicativo armazena apenas um link para a reunião online para facilitar a acessibilidade de reunião para os usuários.  Exemplo. 1. Crie uma Teams online. 2. Salve o link de reunião no banco de dados 3. Use o link de reunião para um botão no aplicativo para facilitar o acesso à reunião. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| User.Read | delegado | Os únicos dados usados são a confirmação explícita pelos usuários para permitir que o aplicativo use um token de acesso para chamar a API Graph. | Nenhum dado é armazenado com a permissão User.Read. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O EUII pode aparecer nos logs de aplicativo ao enviar comunicações para as equipes de gerenciamento de crise internas durante uma crise. As políticas de remoção para logs é que salvamos no máximo 3 meses de logs. Eles podem, embora, ser excluídos mediante solicitação, se necessário. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Temos contratos de proteção de dados com todos os nossos parceiros e subvendores garantindo a adesão aos regulamentos do RGPD que regem a posição como processadores de dados e sub-processadores de dados

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

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

Essas informações foram fornecidas pelo Pilotech AS sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/> |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
