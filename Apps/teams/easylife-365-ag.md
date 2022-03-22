---
title: Informações do aplicativo para EasyLife 365 by EasyLife 365 AG
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/21/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o EasyLife 365, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 1bbd4661f847866ed0d9094f641ba7d34fefd8c0
ms.sourcegitcommit: af065aeee2812a85ead9e0de968fc474204a6e8a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/22/2022
ms.locfileid: "63696503"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 21 de março de 2022</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela EasyLife 365 AG para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | EasyLife 365 |
| ID | WA200003697 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | EasyLife 365 AG |
| Site da empresa | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| Termos de uso do aplicativo | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| Funcionalidade principal do aplicativo | Facilitar a governança! |
| Localização da sede da empresa | Suíça |
| Página de informações do aplicativo | [https://www.easylife365.cloud/governance/features](https://www.easylife365.cloud/governance/features) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela EasyLife 365 AG sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou ao dispositivo? | Sim |
| Quais dados são processados pelo aplicativo? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | Metadados de grupo (id, nome) e Informações do Usuário (id, email) em nosso log por 90 dias |
| Se a estrutura subjacente processa ou armazena dados de clientes da Microsoft, onde esses dados são armazenados geograficamente? | Países Baixos (o) |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são mantidos após o término da conta? | Menos de 90 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou sub-processadores? | Não |
| Você tem contratos de compartilhamento de dados com qualquer serviço de terceiros com o que compartilhar dados do cliente da Microsoft? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você realiza testes de penetração anual no aplicativo? | Sim |
| O aplicativo tem um plano de recuperação de desastres documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa proteção anti-malware tradicional ou controles de aplicativos? | TraditionalAntiMalware, ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de classificação de risco? | Sim |
| Você tem uma política que rege seu contrato de nível de serviço (SLA) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com suas SLAs de política de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que oferece suporte a ele? | Não |
| Você tem um firewall instalado no limite de rede externo? | Não |
| Você tem um processo de gerenciamento de alterações estabelecido usado para revisar e aprovar solicitações de alteração antes que elas sejam implantadas na produção? | Sim |
| Uma pessoa adicional está revendo e aprovando todas as solicitações de alteração de código enviadas à produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em consideração classes comuns de vulnerabilidade, como o OWASP Top 10? | Sim |
| Autenticação multifator (MFA) habilitada para: | DNSManagement, Credential, CodeRepositories |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem um software IDPS (Detecção e Prevenção de Intrusão) implantado no perímetro do limite de rede que suporta seu aplicativo? | N/D |
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
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| Qual certificação do SOC 2 você atingiu? | |
| Data de certificação SOC2 mais recente | |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Data de certificação SOC3 mais recente | |
| Você realiza avaliações anuais do PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo International Organization for Standardization (ISO 27001) é certificado? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27018)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27017)? | Não |
| O aplicativo está em conformidade com a Organização Internacional para Padronização (ISO 27002)? | Não |
| O aplicativo Federal Risk and Authorization Management Program (FedRAMP) está em conformidade? | Não |
| O aplicativo está em conformidade com a FerPA (Lei de Privacidade e Direitos Educacionais da Família)? | Não |
| O aplicativo está em conformidade com a Lei de Proteção de Privacidade Online para Crianças (COPPA)? | Não |
| O aplicativo está em conformidade com Sarbanes-Oxley Lei (SOX)? | Não |
| O aplicativo está em conformidade com o NIST 800-171? | Não |
| O aplicativo foi certificado pelo Cloud Security Alliance (CSA Star)? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem o RGPD ou outros requisitos ou obrigações de proteção de dados ou privacidade (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://www.easylife365.cloud/web/privacy |
| O aplicativo executa a tomada de decisão automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para fins secundários não descritos no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficas, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo tem recursos para restringir ou limitar o processamento de dados pessoais de uma pessoa mediante solicitação? | Não |
| O aplicativo fornece às pessoas a capacidade de corrigir ou atualizar seus dados pessoais? | Não |
| As avaliações regulares de segurança e privacidade de dados são realizadas (por exemplo, Avaliações de Impacto da Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Seu aplicativo se integra com a Plataforma de Identidade da Microsoft (Azure AD) para um único login, acesso à API etc.? | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente do MSAL (Biblioteca de Autenticação da Microsoft) ou da Microsoft Identity Web para autenticação? | Sim |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? |  |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à Avaliação de Acesso Contínuo (CAE) | Não |
| Seu aplicativo armazena alguma credencial no código? | Não |
| Aplicativos e complementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou complemento usa APIs adicionais da Microsoft? | Sim |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph Permissão**  | **Tipo de permissão** |          **Justificativa**          | **ID do aplicativo do Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | delegado | Permite ler Grupos ou Teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Group.ReadWrite.All | delegado | Permite manipualizar metadados de Grupos ou Teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| GroupMember.Read.All | delegado | Lê membros de um grupo | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.Read.All | delegado | Permite recuperar metadados de conta de convidado | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.ReadBasic.All | delegado | Permite pesquisar membros ou contas de convidado em uma organização | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Channel.Create | aplicação | Cria canais para uma equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Channel.ReadBasic.All | aplicação | Lê canais de uma equipe existente | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.Read.All | aplicação | Obter modelos atuais de configuração de conta de grupo e convidado | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.ReadWrite.All | aplicação | Aplicar configurações de conta de convidado para o Grupo ou Equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Create | aplicação | Cria um grupo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | ambos | Lê informações do grupo e recupera aliases de grupo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.ReadWrite.All | aplicação | Manipula metadados de grupo no back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.Read.All | aplicação | Recupera associações de grupo ou equipe no back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.ReadWrite.All | aplicação | Permite adicionar ou remover membros de um grupo ou equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| IdentityRiskyUser.ReadWrite.All | aplicação | Permite manipular contas de convidados e seus metadados | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Mail.Send | aplicação | Envia emails usando uma caixa de correio compartilhada | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| MailboxSettings.Read | aplicação | Recupera as configurações de idioma preferencial de um usuário | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Reports.Read.All | aplicação | Recupera dados de uso de grupos e Teams | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Team.ReadBasic.All | aplicação | Recuperar informações básicas da equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamSettings.ReadWrite.All | aplicação | Permite arquivar e desarquivar uma equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Teams. Criar | aplicação | Cria uma equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.Read.All | aplicação | Recupera guias de uma equipe criada | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.ReadWrite.All | aplicação | Permite criar ou manipualizar guias de uma equipe criada | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Invite.All | aplicação | Convida um usuário para o locatário | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read | delegado | Obtém informações do usuário e informações da organização | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read.All | ambos | Recupera informações de convidados e usuários | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | delegado | Ler todos os grupos de usuários | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| Group.ReadWrite.All | delegado | Modificar os metadados de grupo do usuário e manipular grupos e Teams | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.Read.All | delegado | Permite que um proprietário do Grupo leia a associação de um grupo ou equipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.ReadWrite.All | delegado | Permite que o proprietário do grupo manipule a associação de um grupo ou equipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamSettings.ReadWrite.All | delegado | Permite arquivar ou desarquivar uma equipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsActivity.Send | aplicação | Usado para enviar Teams notificações no back-end | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsAppInstallation.ReadForUser.All | aplicação | Verifique se o usuário tem o aplicativo EasyLife instalado antes de enviar notificações por meio Teams. | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read | delegado | Lê dados da organização e informações do usuário | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read.All | delegado | Permite pesquisar outros membros ou contas de convidado em um diretório | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.ReadBasic.All | delegado | Mostra as fotos do usuário | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| email | delegado | Usado pela autenticação SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| offline_access | delegado | Usado pela autenticação SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| openid | delegado | Usado pela autenticação SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| perfil | delegado | Usado pela autenticação SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

