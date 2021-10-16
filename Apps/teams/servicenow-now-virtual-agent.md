---
title: Informações do aplicativo para o Agente Virtual Agora pelo ServiceNow
ms.author: elmalova
author: elenamalova
ms.date: 05/30/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Agente Virtual Now, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 20ae315016fa0d5cbc960616f09bfd350ceb5c43
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408340"
---
# <a name="now-virtual-agent"></a>Now Virtual Agent

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de março de 2020</p>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381816" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo ServiceNow à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Now Virtual Agent |
| ID | WA104381816 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | ServiceNow |
| URL do site do parceiro | [https://www.servicenow.com/](https://www.servicenow.com/) |
| URL da página Teams de informações do aplicativo | [https://docs.servicenow.com/bundle/london-servicenow-platfo...](https://docs.servicenow.com/bundle/london-servicenow-platform/page/administer/virtual-agent/task/install-va-integrations.html#install-va-integrations) |
| URL da Política de Privacidade | [https://www.servicenow.com/service-privacy.html](https://www.servicenow.com/service-privacy.html) |
| URL dos Termos de Uso | [https://www.servicenow.com/terms-of-use.html](https://www.servicenow.com/terms-of-use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo ServiceNow sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | O domínio é armazenado em nosso data center para fins futuros de roteamento de mensagens. | Quando o administrador serviceNow instala a integração com o MS Teams, o administrador precisa fazer logoff em sua conta de Teams MS. Lemos o domínio do endereço de email (não endereço de email completo). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não fora da caixa de correio por ServiceNow. Os clientes podem aproveitar a estrutura do Agente Virtual para criar recursos adicionais que podem acessar informações da organização ou do usuário final. Os usuários podem digitar informações de identificação pessoal durante a interação com o bot e ter as informações enviadas para ServiceNow.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Consulte a seção [Cloud Security Alliance para](/microsoft-365-app-certification/teams/servicenow-now-virtual-agent?pivots=csa) obter detalhes.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


