---
title: Informações do aplicativo para iPlanner Pro Office 365 iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o iPlanner Pro Office 365, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity-certification
ms.openlocfilehash: 9d433b236c322f730763911764b5ca7be10c243c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414175"
---
# <a name="iplanner-pro-office-365"></a>iPlanner Pro Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 12 de agosto de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380464" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo iGlobe à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | iPlanner Pro Office 365 |
| ID | WA104380464 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook iOS, Outlook na Web |
| Nome da empresa de parceiro | iGlobe |
| URL do site do parceiro | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| URL da Política de Privacidade | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| URL dos Termos de Uso | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo iGlobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa do planejador e adicionar novas tarefas atualize o bucket e a linha de nadador para o usuário específico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Contacts.ReadWrite | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | para criar um Compromisso no calendário de usuários na data de vencimento das tarefas | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Directory.AccessAsUser.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.Read | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para acessar o arquivo como anexo e carregar arquivos em uma tarefa | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.ReadWrite.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Obter o assunto de email do email selecionado. Permite que o aplicativo receba informações do email selecionado, permitindo copiar o campo de descrição para a descrição da tarefa e permitindo salvar anexos do email ou do próprio email para a tarefa. | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Group.Read.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. |  para obter a tarefa do planejador e adicionar novas tarefas atualizem o bucket e a linha de nadador para o usuário específico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.Read | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa do planejador e adicionar novas tarefas atualize o bucket e a linha de nadador para o usuário específico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.ReadBasic.All | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. |  Verifique se há permissão e para obter a tarefa do planejador e adicionar novas tarefas atualizem o bucket e a linha de nadação para o usuário específico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| perfil | delegado | Nenhum dado é armazenado em bancos de dados de aplicativos. | Para obter a tarefa do planejador e adicionar novas tarefas atualize o bucket e a linha de nadador para o usuário específico | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS. AccessAsUser.All | Não |  |  |  |  |
>| Exchange - Mail.Read.All | Não |  |  |  |  |
>| SharePoint - AllSites.Manage | Não |  |  |  |  |
>| SharePoint - AllSites.Read | Não |  |  |  |  |
>| SharePoint - AllSites.Write | Não |  |  |  |  |
>| SharePoint - MyFiles.Read | Não |  |  |  |  |
>| SharePoint - MyFiles.Write | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



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

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35757" target="_blank">Exibir em uma nova guia</a>

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
