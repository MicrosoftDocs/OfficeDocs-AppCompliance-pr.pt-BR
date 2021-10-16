---
title: Informações do aplicativo para Office2SharePoint pelo iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o Office2SharePoint, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity-certification
ms.openlocfilehash: 4597a2127cab82a6636af23183e4b662d1b8bd77
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413132"
---
# <a name="office2sharepoint"></a>Office2SharePoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 16 de agosto de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.o2s" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Office2SharePoint |
| ID | 17859280.o2s |
| Nome da empresa de parceiro | iGlobe |
| URL do site do parceiro | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL da Política de Privacidade | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL dos Termos de Uso | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.AccessAsUser.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Verifique se há permissão e para obter os Sites e listas. Criar pastas, obter arquivos e salvar arquivos. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Directory.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Verifique se há permissão e para obter os Sites e listas. Criar pastas, obter arquivos e salvar arquivos. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter os sites de grupo dos usuários. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Group.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para acessar os emails/s selecionados e obter os anexos. No email ou adicione do site SharePoint ou Grupos ao email. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Manage.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Permite que o aplicativo crie ou exclua bibliotecas de documentos e listas em todos os conjunto de sites em nome do usuário registrado. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter os usuários SharePoint site. Obter arquivos e salvar anexos do email selecionado. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| Sites.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter SharePoint, bibliotecas e arquivos. Para salvar arquivos em SharePoint listas. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |
>| User.Read | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter os usuários SharePoint site, OneDrive e sites de grupo. | [5971c986-9d39-409c-a6f8-1385b1f690ef](https://docs.microsoft.com/microsoft-365-app-certification/azure/5971c986-9d39-409c-a6f8-1385b1f690ef) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS. AccessAsUser.All | Não |  |  |  |  |
>| Exchange - Mail.ReadWrite | Não |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | Não |  |  |  |  |
>| SharePoint- AllSites.Manage | Não |  |  |  |  |
>| SharePoint - AllSites.Write | Não |  |  |  |  |
>| SharePoint - MyFiles.Write | Não |  |  |  |  |
>| SharePoint - User.Read.All | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O iGlobe coleta dados para operar efetivamente e fornecer as melhores experiências com nossos produtos e serviços. Para licenciamento: dados coletados para administrar sua&#8217;de licenciamento, como quando você implanta um Complementos Gratuitos, cria uma assinatura de avaliação ou compra uma assinatura. As informações a seguir são coletadas. Para fins financeiros: nome da empresa e endereço Usuários inscritos: nome de usuário e email

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados do aplicativo estão no próprio locatário do cliente e são controlados pelo administrador de locatários como todos os outros serviços Office 365. Nenhum dado de aplicativo é armazenado no Add-in. Um complemento moderno é executado em um navegador em área &#8220;fora do processo&#8221;. O complemento só pode acessar os dados com os quais o usuário está trabalhando. Ele interage com os dados dos usuários usando serviços Microsoft.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">Exibir em uma nova guia</a>

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

::: zone pivot="certification"

### <a name="certification-information"></a>Informações de certificação

| **Control** | **Microsoft 365 Resultado da certificação** |
|:------------|:---------------------------------------|
| [**SEGURANÇA DO APLICATIVO**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#application-security) | **N/D** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Testes de penetração | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Análise de Avaliação de Vulnerabilidade (TESTE DE PENETRAÇÃO/SAST/DAST) | N/D |
| [**SEGURANÇA OPERACIONAL**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#operational-security) | **N/D** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Proteção contra Malware - Antivírus | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Proteção contra Malware - Controle de Aplicativos | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Patch - Classificação de Risco | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Patch - Patching | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Verificação de vulnerabilidade | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall - Firewalls (ou tecnologias equivalentes) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall - WaFs (Firewalls de Aplicativo Web) (Opcional) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alterar Controle | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Desenvolvimento/implantação de software seguro | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Contas | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Detecção e prevenção contra intrusões (opcional) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Log de Eventos de Segurança | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisão (Dados de Log) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alerta de eventos de segurança | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Riscos de Segurança da Informação | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resposta a incidentes | N/D |
| [**PRIVACIDADE DE SEGURANÇA DE TRATAMENTO DE &amp; DADOS**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#data-handling-security-and-privacy) | **N/D** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dados em Trânsito | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dados em repouso | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Retenção e descarte de dados | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Acesso a Dados | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RGPD | N/D |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
