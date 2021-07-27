---
title: Informações do aplicativo para assembly pela Empresa DescaradadaHr.
ms.author: elmalova
author: elenamalova
ms.date: 05/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Assembly, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f8d63c77c3fd9b52353ce22954dfa4dadb8dea2f
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522044"
---
# <a name="assembly"></a>Assembly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 21 de maio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/3e674b5f-ba5d-41cc-8b06-e065b4394aeb" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002271" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela CarrotHR Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Assembly |
| ID | WA200002271 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | CarrotHR Inc. |
| URL do site do parceiro | [https://www.joinassembly.com](https://www.joinassembly.com) |
| URL da página Teams de informações do aplicativo | [https://www.joinassembly.com/about](https://www.joinassembly.com/about) |
| URL da Política de Privacidade | [https://joinassembly.com/privacy-policy](https://joinassembly.com/privacy-policy) |
| URL dos Termos de Uso | [https://joinassembly.com/terms-of-service](https://joinassembly.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela CarrotHR Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | delegado | Permitir que o usuário atribua o aplicativo a um canal recém-criado do nosso aplicativo | Armazenamos id de canal para manter nosso aplicativo em sincronia com o canal correto | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Directory.Read.All | aplicação | Mantenha nossos perfis em sincronia para que os membros sejam pesquisáveis corretamente no Assembly | Qualquer informação adicional de perfil que possa estar disponível para manter os membros pesquisáveis no Assembly | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Group.Read.All | delegado | Observamos os dados para garantir que eles possam atribuir nosso aplicativo ao grupo correto | Não armazenamos grupos | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Teams.ReadBasic.All | aplicação | Capacidade de atribuir nosso aplicativo à guia de equipe correta | Não armazenamos equipes que esperam a que estamos anexados  | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| TeamsTab.Create | aplicação | Usamos isso para permitir que nosso aplicativo seja anexado a um canal/equipe corretamente | Não estamos coletando ou armazenar dados da guia | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| email | delegado | Email do usuário para que possamos conceder acesso a sua conta específica | Email do usuário para que possamos conceder acesso a suas contas específicas e identidades de combinação | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| perfil | delegado | Nome de usuário para popular automaticamente o Assembly e manter a sincronização com as alterações no Microsoft Teams | Nome completo do usuário | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |


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

>exclusão, retenção, auditoria, arquivamento

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela CarrotHR Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Não |
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
