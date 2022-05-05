---
title: Informações do aplicativo para Office2SharePoint
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Office2SharePoint, suas políticas de tratamento de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9d063ac1a7cee57ef2bee185ed43a2c3385c06c2
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65224996"
---
# <a name="application-information-for-office2sharepoint"></a>Informações do aplicativo para Office2SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 22 de junho de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.o2s" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Office2SharePoint |
| ID | 17859280.o2s |
| Nome da empresa parceira | iGlobe |
| URL do site do parceiro | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL da Política de Privacidade | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL dos Termos de Uso | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para coletar?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **Azure AD ID do aplicativo** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Verifique se há permissão e para obter os Sites e listas. Criar pastas, obter arquivos e salvar arquivos. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Verifique se há permissão e para obter os Sites e listas. Criar pastas, obter arquivos e salvar arquivos. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Para obter os sites do grupo de usuários. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Para acessar os emails selecionados e obter os anexos. Do email ou adicione do SharePoint ou grupos ao email. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Permite que o aplicativo crie ou exclua bibliotecas de documentos e listas em todos os conjuntos de sites em nome do usuário conectado. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Para obter os usuários SharePoint site. Obtenha arquivos e salve anexos do email selecionado. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Para obter SharePoint, bibliotecas e arquivos. Para salvar arquivos em SharePoint listas. | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | Delegada | Nenhum dado é armazenado em bancos de dados de aplicativo. | Para obter os usuários SharePoint site, OneDrive e sites de grupo. | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e suplementos criados Microsoft 365 podem usar APIs adicionais da Microsoft diferentes do Microsoft Graph para coletar ou processar informações de identificação organizacional (OII). Liste todas as APIs da Microsoft diferentes Graph este aplicativo usa.

>| **API** |  **O OII foi coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS. AccessAsUser.All | Não |  |  |  |  |
>| Exchange - Mail.ReadWrite | Não |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Não |  |  |  |  |
>| SharePoint- AllSites.Manage | Não |  |  |  |  |
>| SharePoint - AllSites.Write | Não |  |  |  |  |
>| SharePoint - MyFiles.Write | Não |  |  |  |  |
>| SharePoint - User.Read.All | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não são serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O iGlobe coleta dados para operar com eficiência e fornecer as melhores experiências com nossos produtos e serviços. Para licenciamento: dados coletados para administrar sua&#8217;conta de licenciamento, como quando você implanta suplementos gratuitos, cria uma assinatura de avaliação ou compra uma assinatura. As informações a seguir são coletadas. Para fins financeiros: Nome da empresa e endereço Usuários inscritos: nome de usuário e email

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>Todos os dados do aplicativo estão no próprio locatário do cliente e são controlados pelo administrador de locatários como todos os outros serviços no Office 365. Nenhum dado de aplicativo é armazenado no Suplemento. Um suplemento moderno é executado em um navegador em área restrita, &#8220;fora do processo&#8221;. O suplemento só pode acessar os dados com os quais o usuário está trabalhando. Ele interage com os dados dos usuários usando serviços Microsoft.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de todos os dados de OII (informações de identificação organizacional) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de identidade.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você integra-se ao Microsoft Identify Platform (Azure AD)?  | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa a MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Padrões de segurança e qualquer outra das políticas comuns, como Bloquear autenticação herdada* Exigir MFA para administradores* Exigir MFA para gerenciamento do Azure* Exigir MFA para todos os usuários* |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multilocação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Seu aplicativo expõe alguma APIs Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
