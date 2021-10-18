---
title: Informações do aplicativo para gravação de tela de weet pelo FYZ SERVICES
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Registro de Tela de Weet, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ae77181b5b3227627881de9ba805e715a8ca4886
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430199"
---
# <a name="weet-screen-recording"></a>Gravação de tela de weet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/f0c0f156-329e-4083-a1a7-89649407a31b" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003284" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo FYZ SERVICES à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Gravação de tela de weet |
| ID | WA200003284 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | SERVIÇOS FYZ |
| URL do site do parceiro | [https://weet.co](https://weet.co) |
| URL da página Teams de informações do aplicativo | [https://weet.co/weet-teams-integration/](https://weet.co/weet-teams-integration/) |
| URL da Política de Privacidade | [https://weet.co/privacy-policy/](https://weet.co/privacy-policy/) |
| URL dos Termos de Uso | [https://weet.co/terms-of-service/](https://weet.co/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo FYZ SERVICES sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsAppInstallation.ReadWriteSelfForUser.All | delegado | Permitir detectar se o aplicativo de weet já está instalado | nenhum armazenamento de dados | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| User.Read | delegado | Não coletamos dados, mas usamos email apenas para ajudar o usuário com o recurso de autocompleção | Não armazenamos informações sobre o usuário, usamos email somente para autocompleção | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| User.ReadBasic.All | delegado | Não coletamos dados, mas usamos email apenas para ajudar o usuário com o recurso de autocompleção | Não armazenamos informações sobre o usuário, usamos email somente para autocompleção | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| offline_access | delegado | Não coletamos dados, mas usamos email apenas para ajudar o usuário com o recurso de autocompleção | Não armazenamos informações sobre o usuário, usamos email somente para autocompleção | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| openid | delegado | Não coletamos dados, mas usamos email apenas para ajudar o usuário com o recurso de autocompleção | Não armazenamos informações sobre o usuário, usamos email somente para autocompleção | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |
>| perfil | delegado | Não coletamos dados, mas usamos email apenas para ajudar o usuário com o recurso de autocompleção | Não armazenamos informações sobre o usuário, usamos email somente para autocompleção | [32eae2b8-2111-431f-9263-e8e1120d0a97](https://docs.microsoft.com/microsoft-365-app-certification/azure/32eae2b8-2111-431f-9263-e8e1120d0a97) |


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

>Você pode solicitar a exclusão de suas informações pessoais. Se você nos pedir para excluir suas informações pessoais, respeitaremos sua solicitação e excluiremos suas informações pessoais, sujeitas a determinadas exceções fornecidas pela lei, como (mas não limitado a) o exercício por outro consumidor de seu direito à liberdade de expressão, nossos requisitos de conformidade resultantes de uma obrigação legal ou qualquer processamento que possa ser necessário para proteger contra atividades ilegais.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo FYZ SERVICES sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
