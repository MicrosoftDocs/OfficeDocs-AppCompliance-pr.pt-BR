---
title: Informações do aplicativo para Dia de Trabalho por Dia de Trabalho
ms.author: elmalova
author: elenamalova
ms.date: 02/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Workday, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b6839d8bb13fd019639c7b3c98077e2e26c5cb91
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60437329"
---
# <a name="workday"></a>Workday

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 26 de janeiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/aa4981ef-635f-4066-b260-97445a4b2819" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001555" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Workday à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Workday |
| ID | WA200001555 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Workday |
| URL do site do parceiro | [https://www.workday.com/en-us/homepage.html](https://www.workday.com/en-us/homepage.html) |
| URL da página Teams de informações do aplicativo | [https://nw.myworkday.com/microsoftteams/](https://nw.myworkday.com/microsoftteams/) |
| URL da Política de Privacidade | [https://www.workday.com/en-us/privacy.html](https://www.workday.com/en-us/privacy.html) |
| URL dos Termos de Uso | [https://nw.myworkday.com/microsoftteams/post-license/](https://nw.myworkday.com/microsoftteams/post-license/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Workday sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsAppInstallation.ReadWriteForUser.All | aplicação | Retreive a ID do aplicativo, instale App for User, obter Teams detalhes da licença AAD | Não armazenamos dados relacionados a esse recurso.  Ele nos permite instalar o aplicativo para o usuário. | [0209ae9c-8d92-4fb8-9c77-4dc29fd371e0](https://docs.microsoft.com/microsoft-365-app-certification/azure/0209ae9c-8d92-4fb8-9c77-4dc29fd371e0) |
>| User.Read.All | aplicação | Recuperar usuários AAID para enviar mensagens de usuários. | Apenas a AAID e Teams AAID  | [0209ae9c-8d92-4fb8-9c77-4dc29fd371e0](https://docs.microsoft.com/microsoft-365-app-certification/azure/0209ae9c-8d92-4fb8-9c77-4dc29fd371e0) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Os dados organizacionais são compartilhados entre o Workday Services e a Microsoft. Consulte os termos do seu contrato com o Workday para obter detalhes adicionais. | Os dados organizacionais são compartilhados entre o Workday Services e a Microsoft. Consulte os termos do seu contrato com o Workday para obter detalhes adicionais. | N/D |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Os dados de lista são usados para personalizar a interação de um usuário com o Aplicativo Workday. | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Consulte os termos do seu contrato com o Workday.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36384' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36384" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Workday sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
