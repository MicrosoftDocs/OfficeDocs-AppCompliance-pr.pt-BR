---
title: Informações de aplicativo para Kudozza por surviveF5 GmbH
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 02/03/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Kudozza, suas políticas de tratamento de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: c8a6ecece9d894adf83bad5458db2597317a4586
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/15/2022
ms.locfileid: "64880878"
---
# <a name="kudozza"></a>Kudozza

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de fevereiro de 2022</p>

* <a href="https://teams.microsoft.com/l/app/61a58a9f-3474-4d14-bda6-6547194a7381" target="_blank">Exibir no Teams armazenamento</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002599" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SurviveF5 GmbH para a Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Kudozza |
| ID | WA200002599 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | surviveF5 GmbH |
| Site da empresa | [https://surviveF5.com](https://surviveF5.com) |
| Termos de Uso do Aplicativo | [https://kudozza.com/terms](https://kudozza.com/terms) |
| Funcionalidade principal do aplicativo | O Kudozza permite dar Kudos a outros membros da equipe para mostrar sua apreciação. Ele oferece várias ferramentas, como participação emoji, categorias ou classificações para motivar a doação de Kudos. |
| Localização da sede da empresa | Alemanha |
| Página de informações do aplicativo | [https://kudozza.com](https://kudozza.com) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Aws, Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela SurviveF5 GmbH sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Dados de perfil do usuário, dados de mensagem (endendidos para o bot) |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | userid, teamid, teamname, username, tenantid, messageid, messagetext |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Alemanha |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Menos de 90 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Sim |
| Você tem contratos de compartilhamento de dados em vigor com qualquer serviço de terceiros com o qual você compartilha dados de clientes da Microsoft? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você executa testes de penetração anuais no aplicativo? | Não |
| O aplicativo tem um plano de recuperação de desastre documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Não |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Não |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Não |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Não |
| Você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Não |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| Autenticação Multifator (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem o software de Detecção e Prevenção de Intrusões (IDPS) implantado no perímetro do limite de rede que dá suporte ao seu aplicativo? | Não |
| Você tem o log de eventos configurado em todos os componentes do sistema que dão suporte ao seu aplicativo? | Sim |
| Todos os logs são revisados regularmente por ferramentas humanas ou automatizadas para detectar possíveis eventos de segurança? | Sim |
| Quando um evento de segurança é detectado, os alertas são enviados automaticamente a um funcionário para triagem? | Não |
| Você tem um processo formal de gerenciamento de risco de segurança da informação estabelecido? | Não |
| Você tem um processo formal de resposta a incidentes de segurança documentado e estabelecido? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | N/D |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
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

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como ele coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://www.kudozza.com/privacy/ |
| O aplicativo executa a tomada de decisões automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para uma finalidade secundária não descrita no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficos, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo tem recursos para restringir ou limitar o processamento dos dados pessoais de um indivíduo mediante solicitação? | Sim |
| O aplicativo fornece aos indivíduos a capacidade de corrigir ou atualizar seus dados pessoais? | Não |
| As revisões regulares de privacidade e segurança de dados são executadas (por exemplo, Avaliações de Impacto de Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Não |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? | MSAL, mas ainda precisamos atualizar para a versão mais recente para Teams |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Sim |
| Aplicativos e suplementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph permissão**  | **Tipo de permissão** |          **Justificativa**          | **ID do aplicativo do Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Delegada | Ler os canais de uma equipe para dar ao usuário a possibilidade de selecionar um canal onde ele deseja publicar os kudos | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |
>| Teams.ReadBasic.All | Delegada | O usuário pode selecionar uma equipe e um canal em que deseja que os kudos sejam publicados. As permissões de leitura da equipe são necessárias para ler as equipes. | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |
>| User.Read | Delegada | Obter as equipes das que um usuário faz parte | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |
>| User.ReadBasic.All | Delegada | Ler o nome de usuário | [69e59100-2fb7-4f6e-a311-987f52b3007b](../azure/69e59100-2fb7-4f6e-a311-987f52b3007b.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

