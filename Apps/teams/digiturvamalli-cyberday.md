---
title: Informações do aplicativo para Cyberday por Digiturvamalli
ms.author: elmalova
author: elenamalova
ms.date: 08/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Cyberday, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f2adf667a89ff8dcdd1a1f56b1f0ef91951f3eb1
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407353"
---
# <a name="cyberday"></a>Cyberday

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 9 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/a8e43ae4-a97b-4d1a-b364-b27794da19a4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001774" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Digiturvamalli à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Cyberday |
| ID | WA200001774 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Digiturvamalli |
| URL do site do parceiro | [https://cyberday.ai](https://cyberday.ai) |
| URL da página Teams de informações do aplicativo | [https://cyberday.ai](https://cyberday.ai) |
| URL da Política de Privacidade | [https://cyberday.ai/privacy](https://cyberday.ai/privacy) |
| URL dos Termos de Uso | [https://cyberday.ai/terms-of-use](https://cyberday.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Digiturvamalli sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Usar email para identificar o usuário + exibição para administradores de aplicativos quem é esse usuário | Email, Teams ID do Usuário | [1c7d277c-ff8a-4ea4-bc14-7d06314f8941](https://docs.microsoft.com/microsoft-365-app-certification/azure/1c7d277c-ff8a-4ea4-bc14-7d06314f8941) |
>| openid | delegado | Usar a ID do usuário para identificar o usuário | Email, Teams ID do Usuário | [1c7d277c-ff8a-4ea4-bc14-7d06314f8941](https://docs.microsoft.com/microsoft-365-app-certification/azure/1c7d277c-ff8a-4ea4-bc14-7d06314f8941) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Heroku (Salesforce Inc.) | Teams ID do locatário e Teams de locatário | O processamento dessas informações é necessário para o desempenho de um contrato de acordo com os termos de uso. ID de locatário e domínio são usados para conectar usuários do Cyberday a contas de organização corretas (por exemplo, exibir diretrizes de segurança corretas). |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Os logs são mantidos, por exemplo, de logon/autenticação (retenção de 2 dias), envio e entrega de emails (retenção de 90 dias) e tráfego de API/erros (retenção de 90 dias). Além disso, a menos que seja acordado o contrário, todos os dados controlados pelo cliente que eles enviaram ao serviço serão excluídos dentro de seis meses após o término do contrato de usuário.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Direitos completos para administradores (por exemplo, exclusão, retenção, auditoria, arquivamento) e outros requisitos definidos para parceiros em contratos de processamento de dados separadamente com cada processador de dados.

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

Essas informações foram fornecidas por Digiturvamalli sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Todos |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
