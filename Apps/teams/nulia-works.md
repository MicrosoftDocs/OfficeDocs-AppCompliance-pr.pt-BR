---
title: Informações do aplicativo para Nulia Works by Nulia
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Nulia Works, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4d176b18a8089d9107f30b7581bcca69daf0871e
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521298"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 11 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Nulia à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Nulia Works |
| ID | WA200002051 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Nulia |
| URL do site do parceiro | [https://nulia.com](https://nulia.com) |
| URL da página Teams de informações do aplicativo | [https://nulia.com/product](https://nulia.com/product) |
| URL da Política de Privacidade | [https://nulia.com/privacy](https://nulia.com/privacy) |
| URL dos Termos de Uso | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Nulia sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, contaremos o número de eventos de calendário que um usuário tem. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Contacts.Read | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, contaremos o número de contatos que um usuário criou. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Files.Read.All | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, contaremos o número de arquivos que um usuário está sincronizando com seu computador. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Group.Read.All | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, recuperamos dos grupos a quantos Teams um usuário pertence. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Mail.Read | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, contaremos o número de pastas de email personalizadas que um usuário criou. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| MailboxSettings.Read | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, veremos se um usuário tem um conjunto de respostas fora do escritório. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Notes.Read | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, contaremos o número de Blocos de Anotações que um usuário compartilhou. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Reports.Read.All | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, recuperamos dos relatórios do usuário quantas mensagens Teams enviadas por dia. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Sites.Read.All | aplicação | Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365. | Armazenamos todos os dados coletados no armazenamento de blob. Usamos esses dados para pontuar os usuários sobre a habilidade e o progresso do resultado. Por exemplo, contaremos o número de coleções de sites que o usuário criou. Esse valor afeta o progresso da habilidade. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| User.Read | aplicação | Exibemos o nome de exibição, o departamento e a imagem de perfil do usuário. | Salvamos o nome de exibição e o departamento em nosso banco de dados para que não precisemos atingir o Graph sempre. Não armazenamos a imagem do perfil. | [Criamos uma nova ID de aplicativo para cada cliente. Por exemplo, nosso locatário nulia está usando a ID do aplicativo: 623B1D5D-6D82-493E-9990-1FBFE82ED046](https://docs.microsoft.com/microsoft-365-app-certification/azure/We create a new application ID for each customer. For example, our Nulia tenant is using application ID: 623B1D5D-6D82-493E-9990-1FBFE82ED046) |
>| Organization.Read.All | aplicação | Coletamos o nome do locatário e Yammer URL base. Usamos isso para iniciar Yammer quando o usuário clica em um botão Experimentar em nosso aplicativo relacionado Yammer &quot; &quot; atividades. | Armazenamos todos os dados coletados no armazenamento de blob. Por exemplo, usamos isso para iniciar Yammer quando o usuário clica em um botão Experimentar em nosso aplicativo relacionado às Yammer &quot; &quot; atividades. | [Usamos os dados coletados para pontuar o progresso do usuário em habilidades e resultados. Coletamos contagens de uso em várias cargas de trabalho do O365.](https://docs.microsoft.com/microsoft-365-app-certification/azure/We use the data collected to score user progress on skills and Outcomes. We collect usage counts across multiple O365 workloads.) |


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

>Não controlamos dados em sistemas parceiros

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Nulia sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

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
