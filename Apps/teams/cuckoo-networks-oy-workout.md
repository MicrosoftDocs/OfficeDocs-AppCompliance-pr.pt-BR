---
title: Informações do aplicativo para malhar oco por Redes Descaradas Oy
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Treinamento SemEsco, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3544854ed952a23af34da1cc1b0ab82465c0966e
ms.sourcegitcommit: 0f47d02fff001cd7cba6a7ab9e276e020cfc053e
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/27/2021
ms.locfileid: "53609897"
---
# <a name="cuckoo-workout"></a>Malhação de Cuco

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/71138876-8738-4935-95b6-ae7c2fbe4e54" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002750" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Oy de Redes Descaradas para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Malhação de Cuco |
| ID | WA200002750 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Oy de Redes Descarocas |
| URL do site do parceiro | [https://cuckooworkout.com](https://cuckooworkout.com) |
| URL da página Teams de informações do aplicativo | [https://cuckooworkout.com](https://cuckooworkout.com) |
| URL da Política de Privacidade | [https://cuckooworkout.com/service-privacy-policy/](https://cuckooworkout.com/service-privacy-policy/) |
| URL dos Termos de Uso | [https://cuckooworkout.com/terms-of-service/](https://cuckooworkout.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Oy redes de cusco sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Nome de usuário, ID de locatário para comunicações e mapeamento de assinatura | Nome de usuário, ID de locatário para comunicações e mapeamento de assinatura | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| email | delegado | Email, necessário para autenticação e suporte | Email, necessário para autenticação e suporte | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| offline_access | delegado | N/D | N/D | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| openid | delegado | ID do usuário para autenticação | ID do usuário para autenticação | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |
>| perfil | delegado | ID de perfil para autenticação | ID de perfil para autenticação | [71138876-8738-4935-95b6-ae7c2fbe4e54](https://docs.microsoft.com/microsoft-365-app-certification/azure/71138876-8738-4935-95b6-ae7c2fbe4e54) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Amazon AWS | ID do locatário | Para corresponder o usuário ao plano de assinatura da empresa  |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Acompanhamento de autenticação e progresso | Teams ID do usuário, ID de locatário | Acompanhamento de autenticação e progresso |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Chats, exibições de vídeo, configurações do usuário, idioma. Políticas de retenção e remoção de acordo com o RGPD.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O Super Admin pode executar exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41840" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Oy redes de cucos sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
