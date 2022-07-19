---
title: Informações do aplicativo para QuickMinutes por QuickMinutes
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/18/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o QuickMinutes, suas políticas de tratamento de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 462cbb7aa74e6a1f4718554efdfc0e482a832b44
ms.sourcegitcommit: 21d1c42a8e6d9f94b9c8f279bbe37f649ebd4e10
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/19/2022
ms.locfileid: "66852676"
---
# <a name="quickminutes"></a>QuickMinutes

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 9 de junho de 2022</p>

* <a href="https://teams.microsoft.com/l/app/5f60fe53-d441-4320-8c26-13fdaee9b58a" target="_blank">Exibir na loja do Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004414" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo QuickMinutes para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | QuickMinutes |
| ID | WA200004414 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | QuickMinutes |
| Site da empresa | [https://quickminutes.com](https://quickminutes.com) |
| Termos de Uso do Aplicativo | [https://quickminutes.com/privacy#/terms_of_service](https://quickminutes.com/privacy#/terms_of_service) |
| Funcionalidade principal do aplicativo | Simplifique seus fluxos de trabalho online de reunião com nosso assistente digital inteligente. |
| Localização da sede da empresa | Irlanda |
| Página de informações do aplicativo | [https://support.quickminutes.com/portal/en-gb/kb/articles/m...](https://support.quickminutes.com/portal/en-gb/kb/articles/microsoft-teams-integration-22-4-2020-1) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Iaas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo QuickMinutes sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Usamos os dados de perfil do usuário para preencher as informações dos usuários no Banco de Dados QuickMinutes quando o usuário registra uma nova conta no QuickMinutes usando o SSO da Microsoft. O QuickMinutes efetua pull dos dados do calendário dos usuários para exibir os eventos na interface do usuário do QuickMinutes. Não armazenamos essas informações no Banco de Dados QuickMinutes, apenas recuperamos as informações do API do Graph e as exibimos para o usuário.  |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | Informações de perfil do usuário, por exemplo, Nome, Sobrenome, Email e imagem do perfil. Também armazenamos tokens de acesso e atualização do MS dos usuários. |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Irlanda |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Não mantido |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Response** |
|:----------------|:-------------|
| Você executa testes de penetração anuais no aplicativo? | Não |
| O aplicativo tem um plano de recuperação de desastre documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | TraditionalAntiMalware, ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Não |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Não |
| Você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| Autenticação Multifator (MFA) habilitada para: | DNSManagement, Credential, CodeRepositories |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem o software de Detecção e Prevenção de Intrusões (IDPS) implantado no perímetro do limite de rede que dá suporte ao seu aplicativo? | Sim |
| Você tem o log de eventos configurado em todos os componentes do sistema que dão suporte ao seu aplicativo? | Sim |
| Todos os logs são revisados regularmente por ferramentas humanas ou automatizadas para detectar possíveis eventos de segurança? | Não |
| Quando um evento de segurança é detectado, os alertas são enviados automaticamente a um funcionário para triagem? | Não |
| Você tem um processo formal de gerenciamento de risco de segurança da informação estabelecido? | Não |
| Você tem um processo formal de resposta a incidentes de segurança documentado e estabelecido? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | N/D |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | N/D |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Não |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | N/D |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Não |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | Não |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | Não |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | N/D |
| O aplicativo está em conformidade com o NIST 800-171? | N/D |
| O aplicativo foi certificado pela Cloud Security Alliance (CSA Star) ? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como ele coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://quickminutes.com/privacy#/privacy_policy |
| O aplicativo executa a tomada de decisões automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para uma finalidade secundária não descrita no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficos, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Sim |
| O aplicativo tem recursos para restringir ou limitar o processamento dos dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo fornece aos indivíduos a capacidade de corrigir ou atualizar seus dados pessoais? | Sim |
| As revisões regulares de privacidade e segurança de dados são executadas (por exemplo, Avaliações de Impacto de Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | N/D |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos do Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Permissão do Graph**  | **Tipo de permissão** |          **Justificativa**          | **Azure AD ID do aplicativo** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.ReadWrite | Delegada | O escopo do calendário é usado pelo QuickMinutes para ler/gravar reuniões do QuickMinutes no usuário Microsoft Calendar | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| People.Read | Delegada | O escopo de pessoas é usado pelo QuickMinutes para listar os contatos dos usuários da Microsoft quando eles estão adicionando usuários à organização ou grupo QuickMinutes | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| email | Delegada | O escopo de email é usado para dar acesso quickMinutes ao endereço de email principal do usuário na forma da declaração de email. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| openid | Delegada | O escopo de openid é usado por QuickMinutes no ponto de extremidade plataforma de identidade da Microsoft token para adquirir tokens de ID. Isso permite que o QuickMinutes use os tokens para acessar o API do Graph em nome dos usuários | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |
>| perfil | Delegada | O escopo do perfil é usado pelo QuickMinutes para acessar o perfil dos usuários quando os registramos por meio do SSO da Microsoft e criamos sua conta do QuickMinutes. | [e340e520-b8f4-4752-8e1c-60270c863b12](../azure/e340e520-b8f4-4752-8e1c-60270c863b12.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

