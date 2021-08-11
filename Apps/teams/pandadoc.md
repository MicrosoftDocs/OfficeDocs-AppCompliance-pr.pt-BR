---
title: Informações do aplicativo para o PandaDoc por PandaDoc
ms.author: elmalova
author: elenamalova
ms.date: 07/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o PandaDoc, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0ad06df6fb1b41955c2cb69e45f2ea84660b3e06
ms.sourcegitcommit: ae66ada4d4513555375f046c726093b0947583ee
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/05/2021
ms.locfileid: "53774817"
---
# <a name="pandadoc"></a>PandaDoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 19 de julho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/769d6db6-6890-4f70-8088-5943fdeac3c5" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002927" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo PandaDoc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | PandaDoc |
| ID | WA200002927 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | PandaDoc |
| URL do site do parceiro | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL da página Teams de informações do aplicativo | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL da Política de Privacidade | [https://www.pandadoc.com/privacy-notice/?utm_source=microso...](https://www.pandadoc.com/privacy-notice/?utm_source=microsoft-teams&amp;utm_medium=partner&amp;utm_campaign=2021-2-inbd-marketplace-websitevisit-pandadoc-privacy) |
| URL dos Termos de Uso | [https://www.pandadoc.com/terms-of-use/](https://www.pandadoc.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo PandaDoc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | ambos | para obter uma lista de IDs de canais para cada comando recebido anteriormente e obter as IDs de unidades de arquivo para cada canal. | Os dados não são armazenados | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.Read.All | ambos | para obter uma lista de IDs de canais para cada comando recebido anteriormente e obter as IDs de unidades de arquivo para cada canal.  | Os dados não são armazenados | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.ReadWrite.All | ambos | para obter uma lista de IDs de canais para cada comando recebido anteriormente e obter as IDs de unidades de arquivo para cada canal. | Os dados não são armazenados | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.Read.All | ambos | Para obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.ReadWrite.All | ambos | Para obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.All | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.Selected | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.Read.All | ambos | para obter uma lista de IDs de canais para cada comando recebido anteriormente e obter as IDs de unidades de arquivo para cada canal. Documentação - https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.ReadWrite.All | ambos | para obter uma lista de IDs de canais para cada comando recebido anteriormente e obter as IDs de unidades de arquivo para cada canal. Documentação - https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp ;tabs=http | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Team.ReadBasic.All | ambos | para obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. Para obter as IDs do cofre de arquivos, primeiro precisa obter uma lista das equipes inseridas pelo usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.Read.All | ambos | Para obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. Para obter as IDs do cofre de arquivos, primeiro precisa obter uma lista das equipes inseridas pelo usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.ReadWrite.All | ambos | ou obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. Para obter as IDs do cofre de arquivos, primeiro precisa obter uma lista das equipes inseridas pelo usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | ambos | necessário para instalar o aplicativo em um usuário no Team e instalar o bot no chat. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | ambos | necessário para instalar o aplicativo em um usuário no Team e instalar o bot no chat. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read.All | ambos |  para obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. Para obter as IDs do cofre de arquivos, primeiro precisa obter uma lista das equipes inseridas pelo usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.ReadWrite.All | ambos |  para obter IDs das equipes Microsoft Teams que o usuário é um membro direto. Depois disso, receber canais para cada identificador de comando. Para obter as IDs do cofre de arquivos, primeiro precisa obter uma lista das equipes inseridas pelo usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| email | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| offline_access | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| openid | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| perfil | ambos | para o usuário sso de Tab (exemplo - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Necessário para obter um token de usuário com acesso à Microsoft Graph e obter ainda mais arquivos de usuário. | Os dados não são armazenados. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| PandaDoc API | Não |  |  |  |  |
>| MS Graph | Não |  |  |  |  |
>| Elementor | Não |  |  |  |  |

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

>Nossos contratos de fornecedor abordam as respectivas obrigações de nós mesmos e nossos fornecedores em relação à privacidade e à segurança dos dados, e fazemos análises de segurança/privacidade de nossos principais fornecedores a cada ano.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo PandaDoc sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Não |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Não |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/> |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
