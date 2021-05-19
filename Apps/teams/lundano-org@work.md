---
title: Informações do aplicativo para Org@Work por Lundano
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para Org@Work, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 68f59afdc79ae00f1643f9f2ce5650e06392d2a3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551972"
---
# <a name="orgwork"></a>Org@Work

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 22 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b9f5d3b0-424e-473d-bcbe-dd01f17f9a41" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002461" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Lundano à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Org@Work |
| ID | WA200002461 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Lundano |
| URL do site de parceiros | [https://www.lundano.com/orgatwork/](https://www.lundano.com/orgatwork/) |
| URL da página de informações do aplicativo Teams | [https://www.lundano.com/orgatwork/index.html#](https://www.lundano.com/orgatwork/index.html#) |
| URL da Política de Privacidade | [https://cp.lundano.com/privacy_en.html](https://cp.lundano.com/privacy_en.html) |
| URL de Termos de Uso | [https://cp.lundano.com/terms.html](https://cp.lundano.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Lundano sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada | Estamos armazenando dados. Nós apenas usamos os dados para fazer login com o usuário em Org@work | Nenhum | aa1c54a1-f482-424d-9389-dbd131233483 |
>| email | Delegada | Estamos armazenando dados. Nós apenas usamos os dados para fazer login com o usuário em Org@work | Nenhum | aa1c54a1-f482-424d-9389-dbd131233483 |
>| offline_access | Delegada | Estamos armazenando dados. Nós apenas usamos os dados para fazer login com o usuário em Org@work | Nenhum | aa1c54a1-f482-424d-9389-dbd131233483 |
>| openid | Delegada | Estamos armazenando dados. Nós apenas usamos os dados para fazer login com o usuário em Org@work | Nenhum | aa1c54a1-f482-424d-9389-dbd131233483 |
>| perfil | Delegada | Estamos armazenando dados. Nós apenas usamos os dados para fazer login com o usuário em Org@work | nenhuma | aa1c54a1-f482-424d-9389-dbd131233483 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Bot push precisa mencionar o nome do funcionário para seu gerente de planejamento para confirmá-lo | Primeiros Sobrenomes dos &amp; funcionários, endereço de e-mail, local de trabalho e organização | Essas informações são necessárias pelo Org@Work gerente de planejamento para concluir o fluxo de trabalho do processo &amp; |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparecem nos aplicativos telemetria ou logs.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Política de usuário final, acordo contratual e exclusão

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36914' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36914" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Lundano sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Sim |
| Seu aplicativo suporta políticas de acesso condicional? | Sim |
| Liste os tipos de políticas suportadas | Funcionário, Gerente de Planejamento e Administrador |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
