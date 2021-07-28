---
title: Informações do aplicativo para ClipTraining por ClipTraining
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para ClipTraining, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5d59d4cbd2d28f1c906e541e7ffc78311c12ffb6
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525765"
---
# <a name="cliptraining"></a>ClipTraining

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 14 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/6cb4b701-2a4f-4080-8a8a-d99f93905e15" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001687" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela ClipTraining para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ClipTraining |
| ID | WA200001687 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | ClipTraining |
| URL do site do parceiro | [https://www.cliptraining.com](https://www.cliptraining.com) |
| URL da página Teams de informações do aplicativo | [https://www.cliptraining.com](https://www.cliptraining.com) |
| URL da Política de Privacidade | [https://www.cliptraining.com/privacy-policy/](https://www.cliptraining.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.cliptraining.com/eula/](https://www.cliptraining.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela ClipTraining sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| offline_access | delegado | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| openid | delegado | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| perfil | delegado | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | Endereço de email, nome, sobrenome para logon e correspondência do usuário.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| não-Microsoft hosting service, non-Microsoft CRM | Nome, sobrenome, endereço de email | Obrigatório para uso comercial |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nome, sobrenome, endereço de email. Retenção e remoção por política de ClipTraining, disponível mediante solicitação

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os sistemas parceiros aos que a ClipTraining utiliza e tem acesso, seguem as políticas de ClipTraining. 

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40836" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela ClipTraining sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
