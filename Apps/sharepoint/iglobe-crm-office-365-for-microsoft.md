---
title: Informações do aplicativo para Office 365 de OFFICE 365 de MICROSOFT OFFICE 365 do iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para o iGlobe CRM Office 365 para Microsoft Office 365, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: b52fcc6ec5d5f5f36c11379c736e098048e58b6b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553502"
---
# <a name="iglobe-crm-office-365-for-microsoft-office-365"></a>Office 365 iGlobe CRM para Microsoft Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 17 de novembro de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379222" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Office 365 iGlobe CRM para Microsoft Office 365 |
| ID | WA104379222 |
| Office 365 clientes suportados | SharePoint 2013 ou mais tarde |
| Nome da empresa parceira | iGlobe |
| URL do site de parceiros | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL da Política de Privacidade | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL de Termos de Uso | [https://www.iglobecrm.com/content/iglobe-crm-office-365-end...](https://www.iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela iGlobe sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Tenha acesso aos calendários dos usuários ao dreating um relatório de reunião do canlendar para iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Contacts.ReadWrite | Delegada |  Directory.AccessAsUser.All | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Verifique se há permissão e para obter os Sites e listas. Crie pastas, obtenha arquivos e salve arquivos. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Directory.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Files.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Leia, atualize, crie tarefas panner, leia os arquivos recentes e compartilhados dos usuários, para obter SharePoint lista, bibliotecas e arquivos. Para salvar arquivos e dados para listas de SharePoint. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Leia, atualize, crie tarefas panner, leia os arquivos recentes e compartilhados dos usuários, para obter SharePoint lista, bibliotecas e arquivos. Para salvar arquivos para listas de SharePoint. | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Group.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Leia, atualize, crie tarefas panner, leia os arquivos recentes e compartilhados dos usuários, para obter SharePoint lista, bibliotecas e arquivos. Para salvar arquivos para listas de SharePoint. Integração ao Office 365 de CRM do iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Mail.ReadWrite | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Svae o eamil para iGlobe CRM e obter informatiopn do iGlobe para um novo e-amil | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Manage.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Criar, editar e excluir itens e listas no CRM iGlobe | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Leia itens no iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Sites.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. |  Editar e excluir itens e listas no iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| Tasks.ReadWrite | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Criar tarefa de planejador a partir do iGlobe CRM | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |
>| User.Read | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter informações do iGlobe CRM para o usuário espelulica | 0bb1641a-3b3b-47f7-a11e-01279d92abfb |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendários.ReadWrite.All | Não |  |  |  |  |
>| Exchange - Mail.Read.All | Não |  |  |  |  |
>| Exchange - Contatos.Read | Não |  |  |  |  |
>| Exchange - EWS. AccessAsUser.All | Não |  |  |  |  |
>| Exchange - Tarefas.ReadWrite | Não |  |  |  |  |
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

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>A iGlobe coleta dados para operar de forma eficaz e fornecer as melhores experiências com nossos produtos e serviços. Para licenciamento: Dados coletados para administrar sua organização&#8217;conta de licenciamento, como quando você implanta um Add-ins gratuito, cria uma assinatura de teste ou compra uma assinatura. As informações seguintes são coletadas. 
- Para fins financeiros: Nome e endereço da empresa
- Usuários inscritos: nome de usuário e e-mail

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados estão no próprio inquilino do cliente. Nenhum dado do aplicativo é armazenado. Um complemento moderno é executado em um navegador sandboxed, &#8220;fora de processo&#8221;. Ele interage com os dados dos usuários usando serviços Microsoft. O complemento só pode acessar os dados com os quais o usuário está trabalhando.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo iGlobe sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Não |
| Seu aplicativo suporta políticas de acesso condicional? | Sim |
| Liste os tipos de políticas suportadas | Padrões de segurança e qualquer outra das políticas comuns como autenticação legado do Bloco* Exigir MFA para administradores* Exigir MFA para gerenciamento do Azure* Exigir MFA para todos os usuários* |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
