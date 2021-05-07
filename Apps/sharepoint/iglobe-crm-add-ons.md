---
title: Informações do aplicativo para complementos do iGlobe CRM pelo iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para complementos do iGlobe CRM, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 21e71a90f0764baba9d251b02eea17c369a6f21a
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252771"
---
# <a name="iglobe-crm-add-ons"></a>Complementos do iGlobe CRM

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 17 de novembro de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002010" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Complementos do iGlobe CRM |
| ID | WA200002010 |
| Office 365 clientes com suporte | SharePoint 2016 ou posterior |
| Nome da empresa de parceiro | iGlobe |
| URL do site do parceiro | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL da Política de Privacidade | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL dos Termos de Uso | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Ter acesso a calendários de usuários ao drear um relatório de reunião do canlendar para iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | delegado |  Directory.AccessAsUser.All | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Verifique se há permissão e para obter os Sites e listas. Criar pastas, obter arquivos e salvar arquivos. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Ler, atualizar, criar tarefas de painel, ler os usuários arquivos recentes e compartilhados, para obter SharePoint lista, bibliotecas e arquivos. Para salvar arquivos e dados em SharePoint listas. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Ler, atualizar, criar tarefas de painel, ler os usuários arquivos recentes e compartilhados, para obter SharePoint lista, bibliotecas e arquivos. Para salvar arquivos em SharePoint listas. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Ler, atualizar, criar tarefas de painel, ler os usuários arquivos recentes e compartilhados, para obter SharePoint lista, bibliotecas e arquivos. Para salvar arquivos em SharePoint listas. Integração ao iGlobe CRM Office 365 | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Svae o eamil para iGlobe CRM e obter informações do iGlobe para um novo e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Criar, editar e excluir itens e listas no iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Ler itens no iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. |  Editar e excluir itens e listas no iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Criar tarefa do planejador a partir do iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter informações do iGlobe CRM para o usuário speficic | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | Não |  |  |  |  |
>| Exchange - Mail.Read.All | Não |  |  |  |  |
>| Exchange - Contacts.Read | Não |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Não |  |  |  |  |
>| Exchange - Tasks.ReadWrite | Não |  |  |  |  |
>| SharePoint - AllSites.Manage | Não |  |  |  |  |
>| SharePoint - AllSites.Read | Não |  |  |  |  |
>|  SharePoint -AllSites.Write | Não |  |  |  |  |
>| SharePoint - MyFiles.Write | Não |  |  |  |  |
>| SharePoint - Sites.Manage.All | Não |  |  |  |  |
>| SharePoint - Sites.Read.All | Não |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | Não |  |  |  |  |
>| SharePoint - Sites.Search.All | Não |  |  |  |  |
>|  SharePoint - TermStore.Read.All | Não |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="add-in-data-access"></a>Acesso a dados do complemento

Listar as permissões necessárias para acessar os dados da sua organização, a justificativa e a finalidade dessa permissão (para que o aplicativo usa essas informações?) e se o aplicativo armazena qualquer uma dessas informações em seus bancos de dados.

>| **Permissão**  | **Descrição** |
>|:----------------|:----------------|
>| Padrão | Não&#8217;ler ou fazer alterações no documento |
>| Enviar Dados | Pode enviar dados pela Internet |

#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O iGlobe coleta dados para operar efetivamente e fornecer as melhores experiências com nossos produtos e serviços. Para licenciamento: dados coletados para administrar sua&#8217;de licenciamento, como quando você implanta um Complementos Gratuitos, cria uma assinatura de avaliação ou compra uma assinatura. As informações a seguir são coletadas. 
- Para fins financeiros: nome da empresa e endereço
- Usuários inscritos: nome de usuário e email

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados estão no próprio locatário do cliente. Nenhum dado de aplicativo é armazenado. Um complemento moderno é executado em um navegador em área &#8220;fora do processo&#8221;. Ele interage com os dados dos usuários usando serviços Microsoft. O complemento só pode acessar os dados com os quais o usuário está trabalhando.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Padrões de segurança e qualquer outra das políticas comuns, como Bloquear autenticação herdada* Exigir MFA para administradores* Exigir MFA para gerenciamento do Azure* Exigir MFA para todos os usuários* |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
