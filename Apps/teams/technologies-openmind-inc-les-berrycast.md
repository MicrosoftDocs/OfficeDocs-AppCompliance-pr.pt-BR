---
title: Informações do aplicativo para o Berrycast pela Technologies Openmind Inc, Les
ms.author: elmalova
author: elenamalova
ms.date: 07/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Berrycast, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 714db08e839b60403a567b2cab1af888c4cb7b6f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277668"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Technologies Openmind Inc, Les para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Berrycast |
| ID | WA200002798 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Technologies Openmind Inc, Les |
| URL do site do parceiro | [https://www.berrycast.com](https://www.berrycast.com) |
| URL da Política de Privacidade | [https://www.berrycast.com/privacy-policy](https://www.berrycast.com/privacy-policy) |
| URL dos Termos de Uso | [https://www.berrycast.com/terms-of-use](https://www.berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Technologies Openmind Inc, Les sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| People.Read | delegado | Para obter todos os contatos do usuário | Os contatos email, nome do punho, sobrenome e imagem são armazenados para dar acesso de compartilhamento rápido de registros | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| User.Read | delegado | Para identificar o usuário com informações básicas (nome e sobrenome e imagem) | Para exibir o nome. lastname e picture no aplicativo | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| email | delegado | Para identificar o usuário | Para identificar o usuário para registro em log e enviar notificação | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| offline_access | delegado | Manter acesso aos dados aos quais você concedeu acesso | N/A | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |
>| openid | delegado | Para identificar o usuário | Para identificar o usuário para registro em log | [094f3986-3951-4f0c-88fa-514d117c8dd0](https://docs.microsoft.com/microsoft-365-app-certification/azure/094f3986-3951-4f0c-88fa-514d117c8dd0) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, Intercom, MixPanel, Amplitude | email, identificação exclusiva do usuário, nome, sobrenome  | Para processar o pagamento seguro, para executar campanha de marketing, para ter um serviço de cliente eficiente e rastrear o usuário com análise para melhorar o produto |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Email, nome, sobrenome e removeremos todos os dados se o usuário excluir sua conta 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Excluiremos todos os dados relacionados a um usuário se ele excluir sua conta.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Technologies Openmind Inc, Les sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Não |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
