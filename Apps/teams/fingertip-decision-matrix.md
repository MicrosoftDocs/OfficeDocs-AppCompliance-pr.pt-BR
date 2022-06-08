---
title: Informações do aplicativo para a matriz de decisão da ponta do dedo por ponta do dedo
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/07/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para a Matriz de Decisão de Ponta do Dedo, suas políticas de manipulação de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 390378f757af6d9fd9afbfd647210827c6f9f3db
ms.sourcegitcommit: dbf716786f7a3c0b84fa4563e47510e4bd3a2fd0
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/08/2022
ms.locfileid: "65943172"
---
# <a name="fingertip-decision-matrix"></a>Matriz de Decisão da Ponta do Dedo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 6 de outubro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/9d9390bb-2d73-4c5e-9609-0ee86fc620ce" target="_blank">Exibir na loja do Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004070" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Ponta do Dedo para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Matriz de Decisão da Ponta do Dedo |
| ID | WA200004070 |
| Clientes do Office 365 com suporte | Microsoft Teams |
| Nome da empresa parceira | Dedo |
| Site da empresa | [https://www.fingertip.org](https://www.fingertip.org) |
| Termos de Uso do Aplicativo | [https://www.fingertip.org/terms-of-use/](https://www.fingertip.org/terms-of-use/) |
| Funcionalidade principal do aplicativo | A Matriz de Decisão da Ponta do Dedo ajuda você a decidir entre várias alternativas quando você precisa levar muitos fatores diferentes em consideração. Ele traz mais clareza e transparência para o processo e ajuda você a priorizar suas alternativas, reduzindo o impacto dos preconceitos. Com a Matriz de Decisão por Ponta do Dedo, você pode colaborar para tomar decisões com mais precisão em conjunto, usando o Microsoft Teams. |
| Localização da sede da empresa | Finlândia |
| Página de informações do aplicativo | [https://www.fingertip.org/solutions/fingertip-decision-matr...](https://www.fingertip.org/solutions/fingertip-decision-matrix/) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Iaas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela Ponta do Dedo sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Informações do perfil do usuário, ID do locatário |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | Informações do perfil do usuário, ID do locatário |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Finlândia |
| Você tem um processo estabelecido de locação e descarte de dados? | Não |
| Por quanto tempo os dados são retidos após o encerramento da conta? |  |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo do Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Response** |
|:----------------|:-------------|
| Você executa testes de penetração anuais no aplicativo? | Sim |
| O aplicativo tem um plano de recuperação de desastre documentado, incluindo uma estratégia de backup e restauração? | Não |
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Sim |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Sim |
| Você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| Autenticação Multifator (MFA) habilitada para: | CodeRepositories, Credential, DNSManagement |
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
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | N/D |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | N/D |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Não |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Não |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | N/D |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | Sim |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | N/D |
| O aplicativo está em conformidade com o NIST 800-171? | N/D |
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
| Você examinou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração da plataforma de identidade da Microsoft? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Autenticação multifator, permitindo que apenas dispositivos registrados no Intune acessem serviços específicos, restringindo locais de usuário e intervalos de IP |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos do Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Sim |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Permissão do Graph**  | **Tipo de permissão** |          **Justificativa**          | **ID do aplicativo do Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| User.Read | Delegada | Informações básicas do perfil para a criação do usuário | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| User.ReadBasic.All | Delegada | Informações básicas do perfil para a criação do usuário | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| email | Delegada | Informações básicas do perfil para a criação do usuário | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| offline_access | Delegada | Para se o usuário se desconectar | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| openid | Delegada | Entrar | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |
>| perfil | Delegada | Informações básicas do perfil para a criação do usuário | [5a6a4d82-42ce-42c4-88f0-df529fe54dcc](../azure/5a6a4d82-42ce-42c4-88f0-df529fe54dcc.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

