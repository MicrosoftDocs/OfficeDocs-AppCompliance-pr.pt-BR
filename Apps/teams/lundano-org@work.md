---
title: Informações do aplicativo para Org@Work por Lundano
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Org@Work, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2c1cfec539c8db4ddd597b8125079521d40615c4
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521404"
---
# <a name="orgwork"></a>Org@Work

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 22 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b9f5d3b0-424e-473d-bcbe-dd01f17f9a41" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002461" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Lundano à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Org@Work |
| ID | WA200002461 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Lundano |
| URL do site do parceiro | [https://www.lundano.com/en/](https://www.lundano.com/en/) |
| URL da página Teams de informações do aplicativo | [https://www.lundano.com/orgatwork/index.html#](https://www.lundano.com/orgatwork/index.html#) |
| URL da Política de Privacidade | [https://cp.lundano.com/privacy_en.html](https://cp.lundano.com/privacy_en.html) |
| URL dos Termos de Uso | [https://cp.lundano.com/Terms_en.html](https://cp.lundano.com/Terms_en.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Lundano sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Estamos armazenar dados. Usamos os dados para fazer logon do usuário Org@work | Nenhum | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| email | delegado | Estamos armazenar dados. Usamos os dados para fazer logon do usuário Org@work | Nenhum | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| offline_access | delegado | Estamos armazenar dados. Usamos os dados para fazer logon do usuário Org@work | Nenhum | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| openid | delegado | Estamos armazenar dados. Usamos os dados para fazer logon do usuário Org@work | Nenhum | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| perfil | delegado | Estamos armazenar dados. Usamos os dados para fazer logon do usuário Org@work | nenhuma | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O push de bot precisa mencionar o nome do funcionário para seu gerente de planejamento confirmá-lo | Sobrenomes do &amp; funcionário, endereço de email, local de trabalho e organização | Essas informações são necessárias pelo Org@Work de planejamento para concluir o fluxo de trabalho do &amp; processo |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Política de usuário final, contrato contratual e exclusão

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36914' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36914" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Lundano sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Funcionário, Gerente de Planejamento e Administrador |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
