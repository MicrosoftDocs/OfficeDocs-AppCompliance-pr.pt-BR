---
title: Informações do aplicativo para ecBooking por sistemas especialistas IVR(Ásia) Co.Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o ecBooking, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f36edd400f35d7e4ccbfef5edd0225855f73ab69
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277471"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 28 de dezembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Expert Systems IVR(Asia) Co.Ltd. para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ecBooking |
| ID | WA200002096 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Expert Systems IVR(Asia) Co.Ltd. |
| URL do site do parceiro | [https://www.esi-asia.com](https://www.esi-asia.com) |
| URL da página Teams de informações do aplicativo | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| URL da Política de Privacidade | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| URL dos Termos de Uso | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Expert Systems IVR(Asia) Co.Ltd. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | aplicação | Dados como Email do Usuário, Eventos de Usuário são armazenados. Os Eventos do Usuário são coletados para verificar a disponibilidade de salas e a criação de eventos. | A ID do evento users, o nome do local e os detalhes de outros eventos seriam armazenados. Os dados são coletados para verificar a disponibilidade de salas e a criação de eventos. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| Mail.Send | aplicação | Dados como Email do Usuário. O Email do Usuário é coletado para o envio de email de lembrete de reserva de sala. | Dados como Email do Usuário. O Email do Usuário é coletado para o envio de email de lembrete de reserva de sala. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read | delegado | Dados como ID do usuário, nome e email. Os dados do usuário são coletados para entrar no aplicativo do usuário. | Dados como ID do usuário, nome e email. Os dados do usuário são coletados para entrar no aplicativo do usuário. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read.All | aplicação | Dados como ID do usuário, nome e email. Os dados do usuário são coletados para entrar no aplicativo do usuário. | Dados como ID do usuário, nome e email. Os dados do usuário são coletados para entrar no aplicativo do usuário. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| email | delegado | Dados como Email do Usuário. O Email do Usuário é coletado para verificar a disponibilidade do usuário e a criação de eventos. | Dados como Email do Usuário. O Email do Usuário é coletado para verificar a disponibilidade do usuário e a criação de eventos. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| openid | delegado | A inordenidade openid do usuário para permitir que o usuário faça logon no aplicativo. | A inordenidade openid do usuário para permitir que o usuário faça logon no aplicativo. | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Dados como Email do Usuário, Eventos de Usuário são armazenados. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Dados armazenados no banco de dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Expert Systems IVR(Asia) Co.Ltd. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
