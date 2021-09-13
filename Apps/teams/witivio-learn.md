---
title: Informações do aplicativo para saber por Witivio
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Learn, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f931e75f0a5736ffa49c7366d9928db774c4bdbf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277728"
---
# <a name="learn"></a>Saiba mais

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 31 de março de 2020</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Witivio à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Saiba mais |
| ID | WA200001308 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Witivio |
| URL do site do parceiro | [https://www.witivio.com](https://www.witivio.com) |
| URL da Política de Privacidade | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| URL dos Termos de Uso | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Witivio sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | N/A | Coletamos o UPN e a ID do AAD para a autorização. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| User.ReadBasic.All | delegado | N/A | Coletamos o UPN e a ID do AAD para a autorização. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| openid | delegado | N/A | Coletamos o UPN e a ID do AAD para a autorização. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |
>| perfil | delegado | N/A | Coletamos o UPN e a ID do AAD para a autorização. | [8c5c0060-2892-4355-b0db-661f206028a9](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c5c0060-2892-4355-b0db-661f206028a9) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Usamos a lista para: 1) autorização (conceder acesso ao bot), 2) detectar o nome para fornecer um UX amigável, 3) Para gerenciar os chatlogs para o administrador comercial do bot | N/A. Ou bots é apenas pessoal |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>A telemetria do bot contém o UPN e o diagnóstico fr da ID do AAD.
Somente administradores PROD/Run têm acesso à telemetria de produção. Os logs são armazenados por 90 dias e podem ser excluídos por solicitação em um portal dedicado support.witivio.com ou por email para dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O Witivio usa apenas componentes do Azure, implantados na região norte da Europa. Usamos o insight do aplicativo e Cosmos DB para análise de dados e armazenamento..
O Witivio usa o MFA para todos os usuários, incluindo administradores. Os administradores têm uma conta de usuário (para estação de trabalho) e uma conta privilegiada para acessar o Azure ressources.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

