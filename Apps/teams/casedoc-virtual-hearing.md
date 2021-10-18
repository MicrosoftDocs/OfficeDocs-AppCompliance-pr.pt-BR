---
title: Informações do aplicativo para a Audiência Virtual do Casedoc por Casedoc
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Audiência Virtual do Casedoc, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c10a429f38ed32c5c11cdab448eb1e523301978a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427143"
---
# <a name="casedoc-virtual-hearing"></a>Audiência virtual do Casedoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 28 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/3e701664-cc46-49e4-b356-1a7ac6500998" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003164" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Casedoc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Audiência virtual do Casedoc |
| ID | WA200003164 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Casedoc |
| URL do site do parceiro | [https://www.casedoc.com](https://www.casedoc.com) |
| URL da página Teams de informações do aplicativo | [https://casedoc.com/virtual-hearing-for-teams/](https://casedoc.com/virtual-hearing-for-teams/) |
| URL da Política de Privacidade | [https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Priv...](https://casedoc.com/wp-content/uploads/2021/07/Casedoc_Privacy_Policy_2021.pdf) |
| URL dos Termos de Uso | [https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Cust...](https://casedoc.com/wp-content/uploads/2020/10/Casedoc_Customer_Agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Casedoc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | delegado | Aplicativo de análise para adicionar à guia reunião | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Calendars.ReadWrite | aplicação | Procure eventos de calendário de usuário de lista, usados para exibir a lista de reuniões e os dados do evento no aplicativo. | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Directory.ReadWrite.All | aplicação | Nenhum dado coletado | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Files.ReadWrite.All | aplicação | Listar arquivos carregados pelo aplicativo | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| Group.ReadWrite.All | aplicação | Nenhum dado coletado | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| MailboxSettings.Read | aplicação | Configurações de email de usuário, zona de tempo. Usado para exibir o tempo de tempo correto para o usuário | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| OnlineMeetings.ReadWrite | delegado | Os dados de reunião são lidos e armazenados, usados para exibir dados de reunião no aplicativo | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadForUser | delegado | Listar aplicativo instalado para usuário, usado para adicionar aplicativo à guia reunião. | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsAppInstallation.ReadWriteForUser | delegado | Usado para adicionar aplicativo à guia reunião. | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.Create | delegado | Usado para adicionar guia à reunião. | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| TeamsTab.ReadWrite.All | delegado | Usado para adicionar guia à reunião. | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |
>| User.Read.All | aplicação | Usado para procurar usuários para reunião. | Nenhum dado é armazenado | [3e701664-cc46-49e4-b356-1a7ac6500998](https://docs.microsoft.com/microsoft-365-app-certification/azure/3e701664-cc46-49e4-b356-1a7ac6500998) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Logs de auditoria, retenção conforme a política ISMS, ISO 27001

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>N/D

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Casedoc sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/> |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Não |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
