---
title: Informações do aplicativo para transmissão pelo Cerkl
ms.author: elmalova
author: elenamalova
ms.date: 06/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Broadcast, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a05c24f2534b2635a5faf103b4b1803aa86fe3ee
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435555"
---
# <a name="broadcast"></a>Transmitir

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 11 de maio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/cfdaef91-3bae-4545-a571-b86b1685857f" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002697" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Cerkl à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Transmitir |
| ID | WA200002697 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Cerkl |
| URL do site do parceiro | [https://cerkl.com](https://cerkl.com) |
| URL da página Teams de informações do aplicativo | [https://cerkl.com/broadcast/microsoft-teams/](https://cerkl.com/broadcast/microsoft-teams/) |
| URL da Política de Privacidade | [https://cerkl.com/privacy](https://cerkl.com/privacy) |
| URL dos Termos de Uso | [https://cerkl.com/terms](https://cerkl.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Cerkl sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | O email do usuário é coletado e usado para ver se o usuário está atualmente em nosso sistema e foi adicionado por uma organização. | O aplicativo não armazena dados recuperados da API Graph Microsoft. | [74ef25ab-3685-446c-aa43-4e9cc251ed62](https://docs.microsoft.com/microsoft-365-app-certification/azure/74ef25ab-3685-446c-aa43-4e9cc251ed62) |


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

>Os administradores têm controle total sobre suas informações de usuário e podem solicitar sua remoção a qualquer momento.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39115' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39115" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Cerkl sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
