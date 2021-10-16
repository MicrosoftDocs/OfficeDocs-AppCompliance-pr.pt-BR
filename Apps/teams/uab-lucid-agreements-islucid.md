---
title: Informações do aplicativo para isLucid por Contratos UAB Lúcidos
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para isLucid, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7270fa4f4a08ca820d1fe7452dea13fb107f2294
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414898"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 9 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelos Contratos UAB Lúcidos para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | isLucid |
| ID | WA200002385 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Acordos UAB Lucid |
| URL do site do parceiro | [https://islucid.com](https://islucid.com) |
| URL da página Teams de informações do aplicativo | [https://islucid.com](https://islucid.com) |
| URL da Política de Privacidade | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| URL dos Termos de Uso | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelos Contratos UAB Lúcidos sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | ambos | Com um consentimento específico do usuário para cada chamada separadamente (transcrição iniciada), ele acessa o fluxo de áudio. O fluxo de áudio é encaminhado para um serviço de transcrição para que os usuários recebam mais funcionalidades. | O aplicativo armazena em contêineres separados no Azure (armazenamento de blob e Cosmos DB para cada cliente separadamente) transcrição e informações de meta relacionadas. Isso é necessário para fornecer mais acesso a informações de reunião para o usuário, que usou o aplicativo e estava na reunião específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | ambos | Com um consentimento específico do usuário para cada chamada separadamente (transcrição iniciada), ele acessa o fluxo de áudio. O fluxo de áudio é encaminhado para um serviço de transcrição para que os usuários recebam mais funcionalidades. | O aplicativo armazena em contêineres separados no Azure (armazenamento de blob e Cosmos DB para cada cliente separadamente) transcrição e informações de meta relacionadas. Isso é necessário para fornecer mais acesso a informações de reunião para o usuário, que usou o aplicativo e estava na reunião específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | ambos | Quando o usuário usa a integração com o Microsoft Planner para criar tarefas de chamada e armazenar automaticamente no MS Planner, isLucid coleta para esse usuário grupos, planos, atribuídos. Sem essa permissão, o usuário não seria capaz de criar tarefas a partir da transcrição usando isLucid | O título da tarefa, o criador da tarefa, o data/hora da tarefa, a descrição da tarefa é armazenada para que os usuários tenham acesso ao histórico de tarefas, feito de uma reunião específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | ambos | O aplicativo coleta títulos de reunião para que os usuários posteriormente (quando a reunião seja concluída) encontrem transcrições e tarefas anteriores mais fáceis. | Título da reunião, data/hora da reunião, organizador da reunião | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | ambos | Quando o usuário usa a integração com o Microsoft Planner para criar tarefas de chamada e armazenar automaticamente no MS Planner, isLucid coleta para esse usuário grupos, planos, atribuídos. Sem essa permissão, o usuário não seria capaz de criar tarefas a partir da transcrição usando isLucid | O título da tarefa, o criador da tarefa, o data/hora da tarefa, a descrição da tarefa é armazenada para que os usuários tenham acesso ao histórico de tarefas, feito de uma reunião específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | ambos | Quando o usuário usa a integração com o Microsoft Planner para criar tarefas de chamada e armazenar automaticamente no MS Planner, isLucid coleta para esse usuário grupos, planos, atribuídos. Sem essa permissão, o usuário não seria capaz de criar tarefas a partir da transcrição usando isLucid | O título da tarefa, o criador da tarefa, o data/hora da tarefa, a descrição da tarefa é armazenada para que os usuários tenham acesso ao histórico de tarefas, feito de uma reunião específica. | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | ambos | ID do usuário, ID de locatário coletada para fornecer Azure Active Directory de logon para nossos usuários | ID do usuário, ID de locatário para gerenciamento de direitos posteriores | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | Nome, Sobrenome, Email e Telefone número de usuários recém-registrados | Estamos usando o Hubspot CRM para manter informações relacionadas a vendas |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot está habilitando o envio de fluxo de áudio para o serviço de transcrição. Para fornecer transcrição aceitável, precisamos associar áudio a usuários (alto-falantes). Sem fornecer essas transcrições de informações são inúteis | Nome, sobrenome, status se for uma conta de convidado ou uma Microsoft one | Bot está habilitando o envio de fluxo de áudio para o serviço de transcrição. Para fornecer transcrição aceitável, precisamos associar áudio a usuários (alto-falantes). As informações dos participantes da reunião também são relevantes para permitir que os usuários vejam, que estavam participando da reunião. |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Os usuários ao usar nosso serviço estão gerando transcrições. Nas transcrições que os participantes da reunião (nomes, sobrenomes) apresentam. Potencialmente, qualquer coisa pode ser mencionada durante a chamada. Armazenamos esses dados para os usuários desde que eles usem nossos serviços. Depois que o cliente terminar de nos usar, dentro de 30 dias, destruiremos todos os dados associados.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não controlamos dados em nossos clientes quando o cliente compra isLucid como uma solução hospedada. Para a solução SaaS, permitimos que os usuários cancelem usando nossos serviços e, em seguida, excluímos o Cosmos DB, associado ao parceiro. Também estamos em processo de envio de informações para a API de conformidade

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelos Contratos lúcidos do UAB sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

