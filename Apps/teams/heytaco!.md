---
title: Informações do aplicativo para HeyTaco! por HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para HeyTaco!, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7b4641b33166043dd311bdd89568c9eaea4b87a1
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521634"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por HeyTaco! para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | HeyTaco! |
| ID | WA200001346 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | HeyTaco! |
| URL do site do parceiro | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL da Política de Privacidade | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL dos Termos de Uso | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela HeyTaco! sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | delegado | usado para corresponder ao usuário para transferências de dados do Slack para o MS Teams | usado para corresponder ao usuário para transferências de dados do Slack para a Equipe MS | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| openid | delegado | usado para entrar pessoa em HeyTaco! | usado para entrar pessoa em HeyTaco! | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |
>| perfil | delegado | usado para capturar nome de usuário, imagem de perfil, deslocamento de zona de tempo, id de locatário e id de equipe | usado para capturar nome de usuário, avatar, deslocamento de zona de tempo, id de locatário e id de equipe | [be8d11cf-265a-4974-9912-4ff28c29fc21](https://docs.microsoft.com/microsoft-365-app-certification/azure/be8d11cf-265a-4974-9912-4ff28c29fc21) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para dizer ao usuário que ele recebeu um taco e de quem ele é. | Endereço de email (para tacos de migração de uma plataforma para outra) Nome (para saudação do usuário) Imagem de perfil (para exibição no quadro de líderes) Timezone (para mostrar corretamente os tacos dados na página de atividade) ID do locatário (Para agregar dados por locatário) ID da equipe (Para agregar dados por equipe)  |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>EUII e OII não estão conectados a nenhum registro em log. Somente tipos de erro e tipos de ação.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>HeyTaco! bancos de dados e backups de dados são hospedados no Amazon Web Services (AWS). 

As operações do data center da Amazon foram credenciadas em ISO 27001 , SOC 1 e SOC 2/SSAE 16/ISAE 3402 (anteriormente SAS 70 Type II ), PCI Nível 1 , FISMA Moderado e Sarbanes-Oxley (SOX).

Quando você envia informações por meio de nosso serviço, suas informações são protegidas e criptografadas em repouso e em trânsito por meio de conexões seguras. Implementamos várias medidas de segurança para manter a segurança de suas informações pessoais.

Temos o Gerenciamento de Acesso Privilegiado no local para proteger dados em nossos servidores.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

