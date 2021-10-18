---
title: Informações do aplicativo para o telus Business Conexão por RingCentral, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Conexão TELUS Business, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d39d9d969d09d711de1d879dd869543e06d3a596
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60445193"
---
# <a name="telus-business-connect"></a>Conexão TELUS Business

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 4 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5001eed-f63e-4a7d-9b49-bf8272c934cd" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002300" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela RingCentral, Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Conexão TELUS Business |
| ID | WA200002300 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | RingCentral, Inc. |
| URL do site do parceiro | [https://www.ringcentral.com](https://www.ringcentral.com) |
| URL da página Teams de informações do aplicativo | [https://appsource.microsoft.com/en-us/product/office/WA2000...](https://appsource.microsoft.com/en-us/product/office/WA200002300) |
| URL da Política de Privacidade | [https://www.telus.com/en/about/privacy/](https://www.telus.com/en/about/privacy/) |
| URL dos Termos de Uso | [https://telus.com/BusinessConnect/ServiceTerms](https://telus.com/BusinessConnect/ServiceTerms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela RingCentral, Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado |  Permite que o aplicativo envie convites de reunião por meio de seu calendário | Nenhum | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read | delegado |  Permite que o aplicativo leia um usuário&#8217;perfil básico (email, nome) para fazer as combinações de contato em nosso final. E permite que o usuário entre e vincule sua conta do O365 com a conta RingCentral |  Email, nome, sobrenome | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| User.Read.All | delegado | Permite que o aplicativo leia o perfil completo de um usuário com números de telefone para fazer chamadas telefônicas com nossos serviços. | Nenhum | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |
>| offline_access | delegado |  Permite que o aplicativo receba e atualize o token oauth |  Token de acesso, token de atualização para acessar a API de Graph MS | [e601bd6e-0476-4d66-bd57-a9d13c207f0b](https://docs.microsoft.com/microsoft-365-app-certification/azure/e601bd6e-0476-4d66-bd57-a9d13c207f0b) |


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

>Onde usamos outra organização, ainda controlamos suas informações pessoais. E temos controles estritos para garantir que&#8217;protegido corretamente. Por fim, a seção acima descreve as situações em que suas informações pessoais são compartilhadas com outras organizações, órgãos governamentais e agências de aplicação da lei.  Quando compartilharmos suas informações com outras organizações que&#8217;garantiremos que ela&#8217;protegida, na medida do possível.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela RingCentral, Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
