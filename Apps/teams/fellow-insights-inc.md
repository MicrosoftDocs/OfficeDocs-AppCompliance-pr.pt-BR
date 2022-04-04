---
title: Informações do aplicativo para colegas por colegas Insights Inc
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/31/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Fellow, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 0beb3f9d0e428650da4c7c9abbeeca87b75704c4
ms.sourcegitcommit: 021c258a4aad74b2525c08b60926fbbcd421f0c0
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/01/2022
ms.locfileid: "64598030"
---
# <a name="fellow"></a>Colega

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 30 de março de 2022</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Fellow Insights Inc à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Colega |
| ID | WA200002576 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Fellow Insights Inc |
| Site da empresa | [https://fellow.app](https://fellow.app) |
| Termos de uso do aplicativo | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |
| Funcionalidade principal do aplicativo | Fellow é onde as equipes se reúnem para ter reuniões de equipe produtivas e 1:1s significativas, criar agendas de reuniões colaborativas, decisões de registro e manter umas as outras responsáveis. |
| Localização da sede da empresa | Canadá |
| Página de informações do aplicativo | [https://fellow.app/integrations/microsoft-teams/](https://fellow.app/integrations/microsoft-teams/) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Iaas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Fellow Insights Inc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou ao dispositivo? | Sim |
| Quais dados são processados pelo aplicativo? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | Dados de Perfil de Usuário (nome, email, avatar etc...), Dados do Calendário (lista de calendários, eventos, participantes, etc...), Teams Dados (nomes de equipe, associações de equipe). |
| Se a estrutura subjacente processa ou armazena dados de clientes da Microsoft, onde esses dados são armazenados geograficamente? | Canadá |
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
| O aplicativo está em conformidade com a Lei de Portabilidade e Contabilidade do Seguro de Saúde (HIPAA)? | N/D |
| O aplicativo está em conformidade com a Health Information Trust Alliance, Common Security Framework (HITRUST CSF)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | N/D |
| Data de certificação SOC1 mais recente |   |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você atingiu? |  type1 |
| Data de certificação SOC2 mais recente |  2022-02-28 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Data de certificação SOC3 mais recente | |
| Você realiza avaliações anuais do PCI DSS em relação ao aplicativo e seu ambiente de suporte? | N/D |
| O aplicativo International Organization for Standardization (ISO 27001) é certificado? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27018)? | N/D |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27017)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27002)? | Não |
| O aplicativo Federal Risk and Authorization Management Program (FedRAMP) está em conformidade? | Não |
| O aplicativo está em conformidade com a FerPA (Lei de Privacidade e Direitos Educacionais da Família)? | N/D |
| O aplicativo está em conformidade com a Lei de Proteção de Privacidade Online para Crianças (COPPA)? | N/D |
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
| URL da Política de Privacidade | https://fellow.app/privacy-policy/ |
| O aplicativo executa a tomada de decisão automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para fins secundários não descritos no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficas, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Sim |
| O aplicativo tem recursos para restringir ou limitar o processamento de dados pessoais de uma pessoa mediante solicitação? | Sim |
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
>| Calendars.ReadWrite | ambos | Fellow é um aplicativo de gerenciamento de reuniões, portanto, para funcionar efetivamente, ele precisa de acesso para ler e gravar nos calendários do usuário. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| Channel.ReadBasic.All | delegado | Permite que os usuários postem anotações de reunião em um determinado canal, que está listado em Fellow. Observe que isso só nos permite ver quais canais existem. Ele não fornece a capacidade de ler mensagens. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| Directory.Read.All | aplicação | (Somente para concessões de aplicativo) Permite que Fellow sincronizar informações do diretório do usuário, incluindo todos os usuários. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| Group.Read.All | aplicação | (Somente para concessões de aplicativo) Permite que Fellow sincronizar usuários e grupos. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| People.Read | delegado | Permitir que os usuários encontrem Microsoft Teams para onde enviar anotações. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| People.Read.All | aplicação | (Somente para concessões de aplicativo) Permite o acesso a informações de perfil para todos os usuários. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| Team.ReadBasic.All | delegado | Permitir que os colegas recebam informações básicas sobre uma equipe, para poder enviar anotações e adicionar a guia Colegas. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| User.Read | delegado | Permitir que os usuários entre em Fellow e recebam informações básicas de perfil. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| User.Read.All | aplicação | (Somente para concessões de aplicativo) Permite o acesso a informações de perfil para todos os usuários. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |
>| offline_access | delegado | Fellow requer &quot;acesso offline&quot; aos dados do calendário para sincronização em segundo plano. | [f6671df0-1909-428c-91f7-1c42df04d3e4](../azure/f6671df0-1909-428c-91f7-1c42df04d3e4.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

