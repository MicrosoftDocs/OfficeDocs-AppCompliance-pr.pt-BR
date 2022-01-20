---
title: Informações do aplicativo para o Jira Cloud by Atlassian
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Jira Cloud, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 6c0f6a2085f3bca86883f3ce5817cec32973e140
ms.sourcegitcommit: d492eaf294e4eb3bb6f5db6d4fcf2ea1de3deabf
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 01/20/2022
ms.locfileid: "62144168"
---
# <a name="jira-cloud"></a>Jira Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 11 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/aa183fd9-7104-46c4-af9f-9ee9b81d717e" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002140" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Atlassian para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Jira Cloud |
| ID | WA200002140 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Atlassian |
| Site da empresa | [https://www.atlassian.com](https://www.atlassian.com) |
| Termos de uso do aplicativo | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |
| Funcionalidade principal do aplicativo | Permite que sua equipe acompanhe, atualize e gerencie projetos Microsoft Teams. |
| Localização da sede da empresa | Austrália |
| Página de informações do aplicativo | |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Atlassian sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou ao dispositivo? | Sim |
| Quais dados são processados pelo aplicativo? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | ID de locatário e ID do usuário |
| Se a estrutura subjacente processa ou armazena dados de clientes da Microsoft, onde esses dados são armazenados geograficamente? | Estados Unidos da América |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são mantidos após o término da conta? | Não mantido |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou sub-processadores? | Não |
| Você tem contratos de compartilhamento de dados com qualquer serviço de terceiros com o que compartilhar dados do cliente da Microsoft? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você realiza testes de penetração anual no aplicativo? | Não |
| O aplicativo tem um plano de recuperação de desastres documentado, incluindo uma estratégia de backup e restauração? | Não |
| Seu ambiente usa proteção anti-malware tradicional ou controles de aplicativos? | TraditionalAntiMalware, ApplicationControls |
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
| Data de certificação SOC2 mais recente |  2020-10-31 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Sim |
| Data de certificação SOC3 mais recente |  2020-10-31 |
| Você realiza avaliações anuais do PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo International Organization for Standardization (ISO 27001) é certificado? | Sim |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27018)? | Sim |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27017)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27002)? | Não |
| O aplicativo Federal Risk and Authorization Management Program (FedRAMP) está em conformidade? | Não |
| O aplicativo está em conformidade com a FerPA (Lei de Privacidade e Direitos Educacionais da Família)? | Não |
| O aplicativo está em conformidade com a Lei de Proteção de Privacidade Online para Crianças (COPPA)? | Não |
| O aplicativo está em conformidade com Sarbanes-Oxley Lei (SOX)? | Sim |
| O aplicativo está em conformidade com o NIST 800-171? | Não |
| O aplicativo foi certificado pelo Cloud Security Alliance (CSA Star)? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem o RGPD ou outros requisitos ou obrigações de proteção de dados ou privacidade (como CCPA)? | Não |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como coleta, usa, compartilha e armazena dados do cliente? | Não |
| O aplicativo executa a tomada de decisão automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para fins secundários não descritos no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficas, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? |  |
| O aplicativo tem recursos para restringir ou limitar o processamento de dados pessoais de uma pessoa mediante solicitação? |  |
| O aplicativo fornece às pessoas a capacidade de corrigir ou atualizar seus dados pessoais? |  |
| As avaliações regulares de segurança e privacidade de dados são realizadas (por exemplo, Avaliações de Impacto da Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? |  |

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

>|   **Graph Permissão**  | **Tipo de permissão** |          **Justificativa**          |
>|:------------------------|:--------------------|:------------------------------------|
>| offline_access | delegado | Forneça acesso aos recursos em nome do usuário por um tempo estendido para garantir a melhor experiência do usuário. |
>| openid | delegado | Obtenha o nome, o sobrenome, o nome de usuário preferencial e a ID do objeto do usuário. |
>| perfil | delegado | Obtenha o nome, o sobrenome, o nome de usuário preferencial e a ID do objeto do usuário. |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

