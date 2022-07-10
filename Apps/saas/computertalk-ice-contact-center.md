---
title: Informações do aplicativo para o Ice Contact Center pelo ComputerTalk
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/07/2022
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o Ice Contact Center, suas políticas de manipulação de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust-certification
ms.openlocfilehash: 3624609e62383a44e9dd6eba04d68a6bcc356685
ms.sourcegitcommit: 7902a8fe5a55d715023f34ea1ab987b4d715a4f7
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/10/2022
ms.locfileid: "66707338"
---
# <a name="ice-contact-center"></a>Ice Contact Center

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 14 de fevereiro de 2022</p>

* <a href="https://appsource.microsoft.com/product/web-apps/computertalk.ice-contact-center" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo ComputerTalk para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Ice Contact Center |
| ID | computertalk.ice-contact-center |
| Nome da empresa parceira | ComputerTalk |
| Site da empresa | [https://www.computer-talk.com](https://www.computer-talk.com) |
| Termos de Uso do Aplicativo | [https://www.computer-talk.com/product/enterprise-contact-ce...](https://www.computer-talk.com/product/enterprise-contact-center/ice-contact-center-for-teams) |
| Funcionalidade principal do aplicativo | O ice fornece o contact center como uma funcionalidade de serviço, incluindo roteamento de chamadas, gravação, monitoramento e relatórios. |
| Localização da sede da empresa | Canadá |
| Página de informações do aplicativo | [https://www.computer-talk.com/product/enterprise-contact-ce...](https://www.computer-talk.com/product/enterprise-contact-center/ice-contact-center-for-teams) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo ComputerTalk sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | AzureADGuid (vinculação de conta).  O endereço de email e o número de telefone podem ser importados do AAD. |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | AzureADGuid (vinculação de conta).  O endereço de email e o número de telefone podem ser importados do AAD. |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Canadá |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Menos de 30 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Response** |
|:----------------|:-------------|
| Você executa testes de penetração anuais no aplicativo? | Sim |
| O aplicativo tem um plano de recuperação de desastre documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | TraditionalAntiMalware |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Sim |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Sim |
| Você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| Autenticação Multifator (MFA) habilitada para: | DNSManagement, Credential, CodeRepositories |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem o software de Detecção e Prevenção de Intrusões (IDPS) implantado no perímetro do limite de rede que dá suporte ao seu aplicativo? | Sim |
| Você tem o log de eventos configurado em todos os componentes do sistema que dão suporte ao seu aplicativo? | Sim |
| Todos os logs são revisados regularmente por ferramentas humanas ou automatizadas para detectar possíveis eventos de segurança? | Sim |
| Quando um evento de segurança é detectado, os alertas são enviados automaticamente a um funcionário para triagem? | Sim |
| Você tem um processo formal de gerenciamento de risco de segurança da informação estabelecido? | Sim |
| Você tem um processo formal de resposta a incidentes de segurança documentado e estabelecido? | Sim |
| Você relata violações de dados de aplicativo ou serviço a autoridades de supervisão e indivíduos afetados pela violação dentro de 72 horas após a detecção? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | Sim |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | Sim |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você obteve? | type2 |
| Data de certificação SOC2 mais recente | 2021-10-15 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Sim |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Não |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Não |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | N/D |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | N/D |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | N/D |
| O aplicativo está em conformidade com o NIST 800-171? | Sim |
| O aplicativo foi certificado pela Cloud Security Alliance (CSA Star) ? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos do Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

>Este aplicativo não usa o Microsoft Graph.

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>Informações de certificação

| **Control** | **Resultado da certificação do Microsoft 365** |
|:------------|:---------------------------------------|
| [**SEGURANÇA DO APLICATIVO**](../docs/certification-submission-guide.md#application-security) | **FAIL** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Teste de penetração | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisão da Avaliação de Vulnerabilidade (TESTE DE PENETRAÇÃO/DAST/SAST) | No Escopo |
| [**SEGURANÇA OPERACIONAL**](../docs/certification-submission-guide.md#operational-security) | **PASSAR** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Proteção contra malware – Antivírus | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Proteção contra malware – Controle de Aplicativos | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Patches – Classificação de Risco | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de patch – aplicação de patch | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Verificação de vulnerabilidade | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall – Firewalls (ou tecnologias equivalentes) | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall – WAFs (Firewalls de Aplicativo Web) (opcional) | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alterar Controle | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Desenvolvimento/implantação de software seguro | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Contas | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Detecção e prevenção contra intrusões (opcional) | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Log de eventos de segurança | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisando (dados de log) | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alertas de eventos de segurança | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Riscos de Segurança da Informação | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Resposta a incidentes | No Escopo |
| [**PRIVACIDADE DE SEGURANÇA DE TRATAMENTO DE &amp; DADOS**](../docs/certification-submission-guide.md#data-handling-security-and-privacy) | **PASSAR** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dados em trânsito | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dados inativos | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Retenção e descarte de dados | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Acesso a Dados | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RGPD | No Escopo |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
