---
title: Informações do aplicativo para o Cloud Hub pelo GmbH atwork
ms.author: elmalova
author: elenamalova
ms.date: 07/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Cloud Hub, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 386875fbf14ddd7409590a93462c333510b6a229
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277626"
---
# <a name="cloud-hub"></a>hub de Nuvem

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 7 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/0c46172d-7923-422d-902e-f27aaad6994d" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003034" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo GmbH do atwork para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | hub de Nuvem |
| ID | WA200003034 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | atwork GmbH |
| URL do site do parceiro | [https://www.atwork-it.com](https://www.atwork-it.com) |
| URL da página Teams de informações do aplicativo | [https://www.atwork-it.com/solutions/cloudhub/](https://www.atwork-it.com/solutions/cloudhub/) |
| URL da Política de Privacidade | [https://www.atwork-it.com/privacystatement](https://www.atwork-it.com/privacystatement) |
| URL dos Termos de Uso | [https://www.atwork-it.com/eula](https://www.atwork-it.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo GmbH atwork sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | aplicação | Ler os nomes e a descrição de todos os canais | Nada | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| Mail.Send | aplicação | Compartilhe uma mensagem para uma equipe Microsoft Teams por email. | Nada | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| TeamSettings.Read.All | aplicação | Usado para compartilhamento em uma Microsoft Teams equipe. | Nada | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| User.Read | delegado | Entrar e ler o perfil do usuário | Nada | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |
>| User.Read.All | aplicação | Usado para o se picker de pessoas para compartilhar mensagens. | Nada | [b5d4e933-e001-4168-83f8-abdd974877bd](https://docs.microsoft.com/microsoft-365-app-certification/azure/b5d4e933-e001-4168-83f8-abdd974877bd) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| APIs de Gerenciamento do Office 365 | Sim | ActivityFeed.Read e ServiceHealth.Read | Disponibilizar o feed de atividade e a saúde do serviço para usuários que não são administradores | Dados ActivityFeed e ServiceHealth | Para otimizar o desempenho  |

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

>O aplicativo lê dados e os armazena em um armazenamento de dados do cliente, que é fornecido como SaaS. Além disso, os usuários têm a possibilidade de enviar mensagens como emails ou enviá-las para grupos. 

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

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

Essas informações foram fornecidas pelo GmbH do atwork sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Aplicativo Multi Tenant, depende das configurações&#180;cliente |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
