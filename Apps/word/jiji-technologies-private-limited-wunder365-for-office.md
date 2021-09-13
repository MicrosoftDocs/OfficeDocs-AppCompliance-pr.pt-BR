---
title: Informações de aplicativo para wunder365 para Office pela JiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Wunder365 para Office, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ab9ea33824f66afecc8af8df74754fc7f2dd6d43
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276331"
---
# <a name="wunder365-for-office"></a>Wunder365 para Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 15 de dezembro de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001529" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela JiJi Technologies Private Limited à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Wunder365 para Office |
| ID | WA200001529 |
| Office 365 clientes com suporte | Excel 2016 ou posterior no Mac, Excel 2013 ou posterior em Windows, Excel na Web, Word 2016 ou posterior no Mac, Word na Web, Word 2013 ou posterior em Windows, OneNote na Web |
| Nome da empresa de parceiro | Tecnologias JiJi Private Limited |
| URL do site do parceiro | [https://www.jijitechnologies.com](https://www.jijitechnologies.com) |
| URL da Política de Privacidade | [https://www.wunder365.com/office-addin-privacy-policy](https://www.wunder365.com/office-addin-privacy-policy) |
| URL dos Termos de Uso | [https://www.wunder365.com/terms-of-service](https://www.wunder365.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo JiJi Technologies Private Limited sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | Nenhum dado armazenado. | Para obter/atualizar tarefas do Planner, poste atualizações de tarefas no canal de equipe | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| Mail.Send | delegado | Nenhum dado armazenado. | Permitir que o aplicativo envie uma notificação de email para os usuários | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| offline_access | delegado | Nenhum dado armazenado. | Para manter o usuário conectado. | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| openid | delegado | Nenhum dado armazenado. | Permite que os usuários faça logoff com conta organizacional | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |
>| perfil | delegado | UPN, ID do Usuário, ID de Email, ID de locatário para verificação de licenciamento, licença gratuita. | Permite que os usuários faça logoff com conta organizacional | [3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c](https://docs.microsoft.com/microsoft-365-app-certification/azure/3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Estamos entrando no aplicativo Azure Insights. Estamos registrando a ID do locatário e a id de email do usuário para identificar problemas e ajudar os clientes a resolver problemas.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os aplicativos Web e Armazenamento recursos estão localizados em uma assinatura que não está conectada à AAD da nossa empresa com apenas administradores que têm acesso aos recursos. O 2FA é necessário para esses administradores. 


#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo JiJi Technologies Private Limited sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Exigindo autenticação multifato para usuários com funções administrativas, Exigindo autenticação multifato para tarefas de gerenciamento do Azure, Bloqueio de entrada para usuários que tentam usar protocolos de autenticação herdados, Exigindo locais confiáveis para o registro de Autenticação Multifato do Azure AD, Bloqueando ou concedendo acesso de locais específicos, Bloqueando o comportamento de entrada arriscada |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
