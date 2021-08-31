---
title: Informações do aplicativo para Project Migrator pela FluentPro Software Corporation
ms.author: elmalova
author: elenamalova
ms.date: 08/17/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Project Migrator, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c36f0ed0642705518d18a88068cd67c54f752ede
ms.sourcegitcommit: b1e752ea527ba6049cdc4f5d12cbd5b4dbd7f5b3
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/27/2021
ms.locfileid: "58673054"
---
# <a name="project-migrator"></a>Project Migrator

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 17 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/8cd35615-e306-4b3d-8e93-17520129b60a" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003160" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela FluentPro Software Corporation à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Project Migrator |
| ID | WA200003160 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | FluentPro Software Corporation |
| URL do site do parceiro | [https://projectmigrator.com](https://projectmigrator.com) |
| URL da página Teams de informações do aplicativo | [https://help.fluentpro.com/147404-project-migrator](https://help.fluentpro.com/147404-project-migrator) |
| URL da Política de Privacidade | [https://projectmigrator.com/privacy-policy](https://projectmigrator.com/privacy-policy) |
| URL dos Termos de Uso | [https://projectmigrator.com/terms-of-use](https://projectmigrator.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela FluentPro Software Corporation sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | delegado | Leia grupos e suas associações para migrar para o outro locatário. | Nenhum dado armazenado para essa permissão.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Group.ReadWrite.All | delegado | Nome do grupo, Membros, Planos e Tarefas. Use informações de grupos, planos e tarefas para a migração de dados do Planner. | Nome do grupo, Nome do Plano e Nome da Tarefa. Usado para resumo das informações de migração.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| Sites.ReadWrite.All | delegado | Migre SharePoint documentos para anexos de tarefas do MS Planner. | Nenhum dado armazenado para essa permissão.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegado | UPN para armazenar informações de resumo de migração do MS Planner vinculadas à conta. | UPN. | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.ReadBasic.All | delegado | Use as informações do usuário para migrar as atribuições de tarefas do MS Planner e a associação ao grupo. | Nenhum dado armazenado para essa permissão.  | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| offline_access | delegado | Os tokens de atualização e acesso são usados para acessar dados do MS Planner. | O token de atualização criptografado é armazenado para acessar dados do MS Planner. | [77b31e8c-65d0-484d-a72f-9404ec9dfcfa](https://docs.microsoft.com/microsoft-365-app-certification/azure/77b31e8c-65d0-484d-a72f-9404ec9dfcfa) |
>| User.Read | delegado | Nome, Sobrenome, Nome da Empresa, Telefone, Email Corporativo. Esses dados usados para processos de registro e autenticação. | Nome, Sobrenome, Nome da Empresa, Telefone, Email Corporativo, UPN. | [c36d31a2-8de1-4eb5-9e7d-01da45244c04](https://docs.microsoft.com/microsoft-365-app-certification/azure/c36d31a2-8de1-4eb5-9e7d-01da45244c04) |


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

>https://projectmigrator.com/privacy-policy

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

Essas informações foram fornecidas pela FluentPro Software Corporation sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Não |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
