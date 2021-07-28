---
title: Informações do aplicativo para calendários de contatos aprovados por contato aprovado
ms.author: elmalova
author: elenamalova
ms.date: 05/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Calendários de Contatos Aprovados, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 49aac5c5b6544d9324243d704cfaad6dc7bd8732
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526487"
---
# <a name="approved-contact-calendars"></a>Calendários de contatos aprovados

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 10 de maio de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Contato Aprovado para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Calendários de contatos aprovados |
| ID | WA104380294 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior em Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | Contato Aprovado |
| URL do site do parceiro | [https://www.approvedcontact.com](https://www.approvedcontact.com) |
| URL da Política de Privacidade | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| URL dos Termos de Uso | [https://approvedcontact.com/Terms%20of%20use.pdf](https://approvedcontact.com/Terms%20of%20use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Contato Aprovado sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Para o BOT de calendário, estamos armazenar o tempo livre/ocupado dos usuários para encontrar horários gratuitos para várias pessoas.  | Lemos e comparamos o tempo livre/ocupado e agendamos reuniões. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| Contacts.Read | delegado | Sim, armazenamos informações de contato. | Importação e sincronização de contatos. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.Read | delegado | Sim | Informações básicas do perfil. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| User.ReadBasic.All | delegado | Não | Usado para exibir perfis de colegas de trabalho e comparar horários gratuitos e agendar salas de conferência. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| offline_access | delegado | Sim, tempos de tempo livre/de ocupado para usuários offline. | Chame Graph quando o usuário não estiver usando ativamente nosso site. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |
>| openid | delegado | Não | Office 365 SSO. | [adef9811-448f-4dd5-88d9-68734050fe58](https://docs.microsoft.com/microsoft-365-app-certification/azure/adef9811-448f-4dd5-88d9-68734050fe58) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, registramos endereços de email para conectar compras de licença ao Commercial Appsource. Fornecemos a capacidade de excluir essas informações de nossos logs.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Somente desenvolvedores têm acesso aos logs. Aplicamos o 2FA para acesso a todas as plataformas de desenvolvimento.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Contato Aprovado sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
