---
title: Informações do aplicativo para o Adobe Acrobat pela Adobe Systems Inc.
ms.author: elmalova
author: elenamalova
ms.manager: tonybal
ms.date: 03/09/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Adobe Acrobat, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 3a2bf567352c8d039d02314f0a7909be84e28f7f
ms.sourcegitcommit: 0bd8c5bf11934d14ea75ec30388534345dcb02a5
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/10/2022
ms.locfileid: "63425258"
---
# <a name="adobe-acrobat"></a>Adobe Acrobat

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 6 de março de 2022</p>

* <a href="https://teams.microsoft.com/l/app/10aea93d-20cf-44c2-b4a5-284c5ef2e6a5" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002564" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Adobe Systems Inc. à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Adobe Acrobat |
| ID | WA200002564 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Adobe Systems Inc. |
| Site da empresa | [https://www.adobe.com](https://www.adobe.com) |
| Termos de uso do aplicativo | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |
| Funcionalidade principal do aplicativo | Com o Adobe Acrobat para Microsoft Teams, os criadores do formato de arquivo PDF estão fornecendo uma maneira de você colaborar com todos em seu canal e coletar comentários em um único pdf &#8211; sem precisar sair do ambiente Teams. Receber notificações de atividade quando outras pessoas tomarem medidas em seus documentos. Os revisadores podem ver e comentar os comentários uns dos outros&#8217;, portanto, você&#8217;gastar menos tempo gerenciando conflitos |
| Localização da sede da empresa | Estados Unidos da América |
| Página de informações do aplicativo | [https://helpx.adobe.com/document-cloud/help/microsoft-teams...](https://helpx.adobe.com/document-cloud/help/microsoft-teams.html) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure, Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Adobe Systems Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou ao dispositivo? | Sim |
| Quais dados são processados pelo aplicativo? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | tenant_id, upn_hash, profile_and_token_info, oauth_state, ims_login_changed_at, preference_data, updated_at, created_at, expires_at |
| Se a estrutura subjacente processa ou armazena dados de clientes da Microsoft, onde esses dados são armazenados geograficamente? |  |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são mantidos após o término da conta? | Menos de 30 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou sub-processadores? | Sim |
| Você tem contratos de compartilhamento de dados com qualquer serviço de terceiros com o que compartilhar dados do cliente da Microsoft? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você realiza testes de penetração anual no aplicativo? | Sim |
| O aplicativo tem um plano de recuperação de desastres documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa proteção anti-malware tradicional ou controles de aplicativos? | ApplicationControls, TraditionalAntiMalware |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de classificação de risco? | Sim |
| Você tem uma política que rege seu contrato de nível de serviço (SLA) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com suas SLAs de política de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que oferece suporte a ele? | Sim |
| Você tem um firewall instalado no limite de rede externo? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para revisar e aprovar solicitações de alteração antes que elas sejam implantadas na produção? | Sim |
| Uma pessoa adicional está revendo e aprovando todas as solicitações de alteração de código enviadas à produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em consideração classes comuns de vulnerabilidade, como o OWASP Top 10? | Sim |
| Autenticação multifator (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem um software IDPS (Detecção e Prevenção de Intrusão) implantado no perímetro do limite de rede que suporta seu aplicativo? | Sim |
| Você tem o log de eventos definido em todos os componentes do sistema que suportam seu aplicativo? | Sim |
| Todos os logs são revisados em uma cadência regular por ferramentas humanas ou automatizadas para detectar possíveis eventos de segurança? | Sim|
| Quando um evento de segurança é detectado, os alertas são enviados automaticamente a um funcionário para triagem? | Sim |
| Você tem um processo formal de gerenciamento de risco de segurança de informações estabelecido? | Sim |
| Você tem um processo formal de resposta a incidentes de segurança documentado e estabelecido? |  |
| Você relata violações de dados de aplicativo ou serviço a autoridades de supervisão e indivíduos afetados pela violação dentro de 72 horas após a detecção?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a Lei de Portabilidade e Contabilidade do Seguro de Saúde (HIPAA)? | Não |
| O aplicativo está em conformidade com a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | Não |
| Data de certificação SOC1 mais recente |   |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você atingiu? |  type2 |
| Data de certificação SOC2 mais recente |  2021-11-22 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Data de certificação SOC3 mais recente | |
| Você realiza avaliações anuais do PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo International Organization for Standardization (ISO 27001) é certificado? | Sim |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27018)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27017)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27002)? | Não |
| O aplicativo Federal Risk and Authorization Management Program (FedRAMP) está em conformidade? | Sim |
| O aplicativo está em conformidade com a FerPA (Lei de Privacidade e Direitos Educacionais da Família)? | Sim |
| O aplicativo está em conformidade com a Lei de Proteção de Privacidade Online para Crianças (COPPA)? | Sim |
| O aplicativo está em conformidade com Sarbanes-Oxley Lei (SOX)? | Não |
| O aplicativo está em conformidade com o NIST 800-171? | Sim |
| O aplicativo foi certificado pelo Cloud Security Alliance (CSA Star)? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem o RGPD ou outros requisitos ou obrigações de proteção de dados ou privacidade (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://business.adobe.com/privacy/general-data-protection-regulation.html |
| O aplicativo executa a tomada de decisão automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para fins secundários não descritos no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficas, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo tem recursos para restringir ou limitar o processamento de dados pessoais de uma pessoa mediante solicitação? | Não |
| O aplicativo fornece às pessoas a capacidade de corrigir ou atualizar seus dados pessoais? | Sim |
| As avaliações regulares de segurança e privacidade de dados são realizadas (por exemplo, Avaliações de Impacto da Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Seu aplicativo se integra com a Plataforma de Identidade da Microsoft (Azure AD) para um único login, acesso à API etc.? | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente do MSAL (Biblioteca de Autenticação da Microsoft) ou da Microsoft Identity Web para autenticação? | Não |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? |  |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à Avaliação de Acesso Contínuo (CAE) | Não |
| Seu aplicativo armazena alguma credencial no código? | Não |
| Aplicativos e complementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou complemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph Permissão**  | **Tipo de permissão** |          **Justificativa**          | **ID do aplicativo do Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Files.ReadWrite.All | delegado | Para poder listar e navegar pelos arquivos e pastas recentes, OneDrive e Teams canais do usuário. Permitimos que os usuários acessem esses arquivos, usem-os para executar operações neles e salvem arquivos de volta ao armazenamento. | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| Team.ReadBasic.All | delegado | Ler os nomes e as descrições das equipes | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| User.Read | delegado | Entrar e ler o perfil do usuário | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| email | delegado | Exibir o endereço de email dos usuários | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| offline_access | delegado | manter o acesso aos dados aos que você deu acesso a ele | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| openid | delegado | Conectar os usuários | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| perfil | delegado | exibir o perfil básico dos usuários | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

