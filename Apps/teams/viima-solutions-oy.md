---
title: Informações de aplicação para Viima pela Viima Solutions Oy
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para a Viima, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 703c1bf3b2980fae538af764bfa1d2024a86a366
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553972"
---
# <a name="viima"></a>Viima

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 17 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/2bffa4e8-aac7-4d2e-976d-5a7db5c4b768" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001589" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Viima Solutions Oy à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Viima |
| ID | WA200001589 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Viima Solutions Oy |
| URL do site de parceiros | [https://www.viima.com/](https://www.viima.com/) |
| URL da página de informações do aplicativo Teams | [https://www.viima.com/product](https://www.viima.com/product) |
| URL da Política de Privacidade | [https://www.viima.com/privacy-policy](https://www.viima.com/privacy-policy) |
| URL de Termos de Uso | [https://www.viima.com/terms](https://www.viima.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Viima Solutions Oy sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada |  Primeiro e sobrenome, endereço UPN/email, localização, localização, departamento, localização do escritório. Estes são usados para registrar o usuário e fornecer informações básicas de perfil para eles dentro do aplicativo. | permite que o usuário faça login e dá acesso ao aplicativo às suas UPN e informações básicas do perfil para habilitar o login silencioso | b8ea7030-ce4d-4ecd-98d7-dc16d8298d1b |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nome da organização, ID da organização Viima, e-mails e IDs do usuário final aparecem em logs. Iso27001 compatíveis controles auditados de terceiros em vigor para acesso restrito e arquivamento/exclusão desses dados.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados são armazenados na AWS (Irlanda). O acesso aos dados limita-se apenas à equipe de manutenção e suporte técnico autorizada que recebeu treinamento adequado e é guardada com uma série de medidas de segurança, como 2FA, faixa IP protegida (acesso somente de rede corporativa) etc. As medidas são compatíveis com ISO27001 e auditadas por um terceiro.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Viima Solutions Oy sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Não |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
