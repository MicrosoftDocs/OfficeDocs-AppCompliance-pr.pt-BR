---
title: Informações do aplicativo para Zignals by Alight
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Zignals, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f0c3c319b43d72bf3c825700cfe3bfe1e93e0d5f
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434690"
---
# <a name="zignals"></a>Zignals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 17 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/a0b58ca7-958d-4343-a2dc-a75f2eeb0953" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003201" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Alight à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Zignals |
| ID | WA200003201 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Alight |
| URL do site do parceiro | [https://www.alight.eu](https://www.alight.eu) |
| URL da página Teams de informações do aplicativo | [https://zignals.eu/zignals-support/](https://zignals.eu/zignals-support/) |
| URL da Política de Privacidade | [https://www.zignals.eu/privacy-policy-zignals-for-teams/](https://www.zignals.eu/privacy-policy-zignals-for-teams/) |
| URL dos Termos de Uso | [https://zignals.eu/terms](https://zignals.eu/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Alight sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Para a área &quot; Minhas &quot; Reuniões, temos reuniões do usuário hoje e amanhã. | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Sites.ReadWrite.All | delegado | Nós temos todos os sites SharePoint seguidos do usuário e os exibemos na área Meu Trabalho em Equipe e conseguimos todas as tarefas de SharePoint do usuário e os exibemos na área &quot; &quot; Minhas &quot; &quot; Tarefas. | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Tasks.ReadWrite | delegado | Lemos as tarefas planner e To Do do usuário e as exibemos na área &quot; Minhas &quot; Tarefas. | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| Team.ReadBasic.All | delegado | Podemos obter as equipes ingressáveis do usuário e exibi-las na área Meu Trabalho &quot; em &quot; Equipe. | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadBasic.All | delegado | Na área &quot; Meus &quot; documentos, exibimos o usuário que foi colaboração | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| User.ReadWrite | delegado | Os documentos recentes do usuário são exibidos na área &quot; Meus &quot; Documentos. Os aplicativos favoritos do usuário são armazenados como uma extensão de esquema no MS Graph. Esse nível de permissão é necessário para ler e gravar dados no gráfico. | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| email | delegado | Obter emails de usuários (escopo padrão de Teams MS) | Não armazenado em nosso DB | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| offline_access | delegado | Escopo padrão Teams MS | Não armazenado em nosso DB | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| openid | delegado | Entre usuários. | Nenhuma informação é armazenada no banco de dados de aplicativos. | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |
>| perfil | delegado | Entrar no processo MS Teams | Não armazenado em nosso DB | [a0b58ca7-958d-4343-a2dc-a75f2eeb0953](https://docs.microsoft.com/microsoft-365-app-certification/azure/a0b58ca7-958d-4343-a2dc-a75f2eeb0953) |


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

>Os dados são armazenados somente no Azure. Aqui usamos a interface do administrador para controlar dados (incl. exclusão, auditoria etc.)

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Alight sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
