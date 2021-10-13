---
title: Informações do aplicativo para Luware Nimbus para Microsoft Teams por Luware AG
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Luware Nimbus para Microsoft Teams, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ee4101bb8116bec2db6a095ef170368eb9dfff6b
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/13/2021
ms.locfileid: "60290332"
---
# <a name="luware-nimbus-for-microsoft-teams"></a>Luware Nimbus para Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 1º de outubro de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/luwareagzurich.advanced_routing_azure_marketplace" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Luware AG à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Luware Nimbus para Microsoft Teams |
| ID | luwareagzurich.advanced_routing_azure_marketplace |
| Nome da empresa de parceiro | Luware AG |
| URL do site do parceiro | [https://luware.com](https://luware.com) |
| URL da Política de Privacidade | [https://luware.com/en/privacy-policy](https://luware.com/en/privacy-policy) |
| URL dos Termos de Uso | [https://luware.com/en/agreements/saas/](https://luware.com/en/agreements/saas/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Luware AG sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | delegado | Console do Atendente: Ler Calendário do usuário conectado mostra Calendário com compromissos | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calendars.Read.Shared | delegado | Console do Atendente: ler calendários compartilhados para mostrar Calendário com compromissos | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read | delegado | Console do Atendente: Pesquise no Exchange contatos do usuário conectado | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read.Shared | delegado | Console do Atendente: Pesquisar no Painel Exchange Contatos Compartilhados | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| GroupMember.Read.All | aplicação | Obter membros da equipe, ler grupos de segurança | Armazenamos essas informações como agentes do call center são gerenciados por meio de associações de grupo | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Presence.Read.All | delegado | Mostrar Presença na Pesquisa de Contato na página Do Console do Atendente | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read | delegado | Obter UserInformation (de usuário conectado) | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read.All | ambos | Aplicativo Nimbus - Obter CallerInformation. Em uma chamada interna para a Central de Contatos, fazemos uma pesquisa inversa sobre quem poderia ser para que possamos mostrar essas informações ao Agente. No Console do Atendente (com permissão delegada), pesquisamos todo o diretório interno em busca de destinos de transferência. | Para Relatórios REasons sobre quem mais chamou, armazenamos esses dados. | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.ReadBasic.All | delegado | Pesquisa limitada de usuário | None | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calls.AccessMedia.All | aplicação | Muitos desses Aplicativos/Bots (Fila de Aplicativos por Central de Contatos): Inscreva-se em tons DTMF onde o cliente pode selecionar sua posição na IVR | Todas as informações de DTMF para maneiras selecionadas por meio do ivr para o motivo de relatórios | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.Initiate.All | aplicação | Muitos desses Aplicativos/Bots (Um por Fila do Centro de Contatos): Fazer uma chamada para o Agente  | Todas as informações de CDR para o motivo do relatório | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.InitiateGroupCall.All | aplicação | Muitos desses Aplicativos/Bots (Um por Fila do Centro de Contatos): Fazer uma chamada para o Agente  | Todas as informações de CDR para o motivo do relatório | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.JoinGroupCall.All | aplicação | Muitos desses Aplicativos/Bots (Um por Fila do Contact Center): Participe de uma chamada escalonada para reproduzir comunicados | Todas as informações de CDR para o motivo do relatório | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Dados de relatórios agregados (Registros de Detalhes de Chamadas, informações do chamador, tratamento de chamadas e detalhes da jornada de chamada etc.): Dados de configuração de 24 meses: Duração do Contrato do Cliente +30 dias Logs de aplicativo: Armazenamento temporário de logs de aplicativos internos (para ajudar nossos engenheiros de suporte a solucionar problemas de desempenho e operação de componentes de aplicativo) 30 dias.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>https://luware.com/en/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Luware AG sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Aplicativos cliente, usuários e grupos |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
