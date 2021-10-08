---
title: Informações do aplicativo para comuty por comuty
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Commuty, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8107880619d85a0ea80ba3aa26d9f10edc9cef48
ms.sourcegitcommit: 4817af6bd92bcc7624a43ea79ba6b9362da38035
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/07/2021
ms.locfileid: "60234075"
---
# <a name="commuty"></a>Comuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 7 de outubro de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003325" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Commuty para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Comuty |
| ID | WA200003325 |
| Office 365 clientes com suporte | Outlook 2016 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | Comuty |
| URL do site do parceiro | [https://www.commuty.net](https://www.commuty.net) |
| URL da Política de Privacidade | [https://support.commuty.net/article/33-privacy-policy](https://support.commuty.net/article/33-privacy-policy) |
| URL dos Termos de Uso | [https://support.commuty.net/article/32-terms-conditions](https://support.commuty.net/article/32-terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Commuty sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Eventos de calendário | Nenhuma, ela é usada apenas para sincronizar os dados de Commuty para Calendário do Outlook. Os dados são sempre fornecidos em uma Interface do Usuário Comutável (que pode ser por meio do nosso Outlook Add-In). | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| email | delegado | Endereço de email | Nenhum, isso é usado apenas para corresponder um usuário comutável com a identidade do AD | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| offline_access | delegado | N/D | N/D | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| openid | delegado | Autenticação | Nenhum | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| perfil | delegado | Identidade | Nenhum | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Dados pessoais comuns (Email Principal, Um Email Secundário no qual eles podem receber notificações (opcional), Nome, Sobrenome, número Telefone (opcional), Imagem de perfil (opcional), idioma preferencial, endereço pessoal (opcional, pode ser somente a cidade),Dados de estacionamento (placa de licença), Dados de mobilidade: (Passagem de carpool, várias viagens de trabalho em casa, Departure-Return horas (opcionais), Disponibilidade do carro (opcional), Deslocamentos, Dias de folga). Retenção: na solicitação do usuário OU no final do contrato com nosso cliente

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Cada cliente de Commuty assina nossa DPA ( https://dpa.commuty.net) , que inclui uma exibição curta sobre isso.

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

Essas informações foram fornecidas pela Commuty sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
