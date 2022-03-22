---
title: Informações do aplicativo para Kudozza por surviveF5 GmbH
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 02/03/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Kudozza, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: ae20cb817283550e9dd6c75ef2abe6215d616ff1
ms.sourcegitcommit: 58c50d1704196178455927329748485b40dd7880
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/17/2022
ms.locfileid: "63545920"
---
# <a name="kudozza"></a>Kudozza

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de fevereiro de 2022</p>

* <a href="https://teams.microsoft.com/l/app/61a58a9f-3474-4d14-bda6-6547194a7381" target="_blank">Exibir no Armazenamento do Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002599" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela GmbH surviveF5 para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Kudozza |
| ID | WA200002599 |
| Clientes do Office 365 com suporte | Microsoft Teams |
| Nome da empresa de parceiro | surviveF5 GmbH |
| Site da empresa | [https://surviveF5.com](https://surviveF5.com) |
| Termos de uso do aplicativo | [https://kudozza.com/terms](https://kudozza.com/terms) |
| Funcionalidade principal do aplicativo | Kudozza permite dar Kudos a outros membros da equipe para mostrar a eles sua apreço. Ele oferece várias ferramentas, como participação emoji, categorias ou classificações para motivar a oferta de Kudos. |
| Localização da sede da empresa | Alemanha |
| Página de informações do aplicativo | [https://kudozza.com](https://kudozza.com) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Aws, Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo GmbH surviveF5 sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou ao dispositivo? | Sim |
| Quais dados são processados pelo aplicativo? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | userid, teamid, teamname, username, tenantid, messageid, messagetext |
| Se a estrutura subjacente processa ou armazena dados de clientes da Microsoft, onde esses dados são armazenados geograficamente? | Alemanha |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são mantidos após o término da conta? | Menos de 90 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou sub-processadores? | Sim |
| Você tem contratos de compartilhamento de dados com qualquer serviço de terceiros com o que compartilhar dados do cliente da Microsoft? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo de Segurança do Aplicativo na Nuvem da Microsoft](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) aparecem abaixo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você realiza testes de penetração anual no aplicativo? | Não |
| O aplicativo tem um plano de recuperação de desastres documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa proteção anti-malware tradicional ou controles de aplicativos? | ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de classificação de risco? | Não |
| Você tem uma política que rege seu contrato de nível de serviço (SLA) para aplicar patches? | Não |
| Você realiza atividades de gerenciamento de patch de acordo com suas SLAs de política de patch? | Não |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que oferece suporte a ele? | Não |
| Você tem um firewall instalado no limite de rede externo? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para revisar e aprovar solicitações de alteração antes que elas sejam implantadas na produção? | Sim |
| Uma pessoa adicional está revendo e aprovando todas as solicitações de alteração de código enviadas à produção pelo desenvolvedor original? | Não |
| As práticas de codificação segura levam em consideração classes comuns de vulnerabilidade, como o OWASP Top 10? | Sim |
| Autenticação multifator (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem um software IDPS (Detecção e Prevenção de Intrusão) implantado no perímetro do limite de rede que suporta seu aplicativo? | Não |
| Você tem o log de eventos definido em todos os componentes do sistema que suportam seu aplicativo? | Sim |
| Todos os logs são revisados em uma cadência regular por ferramentas humanas ou automatizadas para detectar possíveis eventos de segurança? | Sim|
| Quando um evento de segurança é detectado, os alertas são enviados automaticamente a um funcionário para triagem? | Não |
| Você tem um processo formal de gerenciamento de risco de segurança de informações estabelecido? | Não |
| Você tem um processo formal de resposta a incidentes de segurança documentado e estabelecido? |  |
| Você relata violações de dados de aplicativo ou serviço a autoridades de supervisão e indivíduos afetados pela violação dentro de 72 horas após a detecção?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a Lei de Portabilidade e Contabilidade do Seguro de Saúde (HIPAA)? | N/D |
| O aplicativo está em conformidade com a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | N/D |
| Data de certificação SOC1 mais recente |   |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| Qual certificação do SOC 2 você atingiu? | |
| Data de certificação SOC2 mais recente | |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Data de certificação SOC3 mais recente | |
| Você realiza avaliações anuais do PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo International Organization for Standardization (ISO 27001) é certificado? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27018)? | N/D |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27017)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27002)? | Não |
| O aplicativo Federal Risk and Authorization Management Program (FedRAMP) está em conformidade? | Não |
| O aplicativo está em conformidade com a FerPA (Lei de Privacidade e Direitos Educacionais da Família)? | Não |
| O aplicativo está em conformidade com a Lei de Proteção de Privacidade Online para Crianças (COPPA)? | Não |
| O aplicativo está em conformidade com Sarbanes-Oxley Lei (SOX)? | N/D |
| O aplicativo está em conformidade com o NIST 800-171? | N/D |
| O aplicativo foi certificado pelo Cloud Security Alliance (CSA Star)? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem o RGPD ou outros requisitos ou obrigações de proteção de dados ou privacidade (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://www.kudozza.com/privacy/ |
| O aplicativo executa a tomada de decisão automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para fins secundários não descritos no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficas, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo tem recursos para restringir ou limitar o processamento de dados pessoais de uma pessoa mediante solicitação? | Sim |
| O aplicativo fornece às pessoas a capacidade de corrigir ou atualizar seus dados pessoais? | Não |
| As avaliações regulares de segurança e privacidade de dados são realizadas (por exemplo, Avaliações de Impacto da Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Não |

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
| Seu aplicativo armazena alguma credencial no código? | Sim |
| Aplicativos e complementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou complemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph Permissão**  | **Tipo de permissão** |          **Justificativa**          | **ID do aplicativo do Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Channel.ReadBasic.All | delegado | Lendo os canais de uma equipe para dar ao usuário a possibilidade de selecionar um canal onde ele deseja publicar os kudos | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |
>| Teams.ReadBasic.All | delegado | O usuário pode selecionar uma equipe e um canal onde deseja que os parabéns sejam publicados. As permissões de leitura de equipe são necessárias para a leitura de equipes. | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |
>| User.Read | delegado | Obter as equipes das que um usuário faz parte | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |
>| User.ReadBasic.All | delegado | Ler o nome do usuário | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

