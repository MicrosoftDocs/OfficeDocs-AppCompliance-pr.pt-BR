---
title: Informações do aplicativo para Sift by Sift
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/26/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Sift, suas políticas de manipulação de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 04cd18d76682248c2270f53791647b19ae948ef9
ms.sourcegitcommit: 6771e51564baf354398b12cdf2f9eede6a8ce994
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/27/2022
ms.locfileid: "67045469"
---
# <a name="sift"></a>Separar

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 25 de abril de 2022</p>

* <a href="https://teams.microsoft.com/l/app/d2a1ed44-6cca-44d2-9b9c-1c9c1d597093" target="_blank">Exibir na loja do Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002545" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Sift à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Separar |
| ID | WA200002545 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | Separar |
| Site da empresa | [https://www.justsift.com](https://www.justsift.com) |
| Termos de Uso do Aplicativo | [https://www.justsift.com/sift-msteams-eula](https://www.justsift.com/sift-msteams-eula) |
| Funcionalidade principal do aplicativo | Localizar, descobrir e conectar-se com as pessoas da sua organização |
| Localização da sede da empresa | Estados Unidos da América |
| Página de informações do aplicativo | [https://www.justsift.com/integrating-sift/with-microsoft-te...](https://www.justsift.com/integrating-sift/with-microsoft-teams) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo Sift sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Nosso aplicativo Teams solicita informações básicas de perfil e consentimento para exibir dados de reunião de usuários de Azure AD. Ele também coleta voluntariamente informações adicionais de perfil dos usuários para aprimorar seus perfis dentro de nossa plataforma. |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | As informações de perfil do usuário do Microsoft Graph serão coletadas se o consentimento for concedido por um usuário administrativo. |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Estados Unidos da América |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Mais de 90 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Sim |
| Você tem contratos de compartilhamento de dados em vigor com qualquer serviço de terceiros com o qual você compartilha dados de clientes da Microsoft? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Response** |
|:----------------|:-------------|
| Você executa testes de penetração anuais no aplicativo? | Sim |
| O aplicativo tem um plano de recuperação de desastre documentado, incluindo uma estratégia de backup e restauração? | Sim |
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | ApplicationControls, TraditionalAntiMalware |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Sim |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Sim |
| Você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Não |
| Autenticação Multifator (MFA) habilitada para: | CodeRepositories, DNSManagement, Credential |
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
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você obteve? | type2 |
| Data de certificação SOC2 mais recente | 2022-04-25 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Não |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Não |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | N/D |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | N/D |
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
| URL da Política de Privacidade | https://www.justsift.com/privacy-policy |
| O aplicativo executa a tomada de decisões automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para uma finalidade secundária não descrita no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficos, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Sim |
| O aplicativo tem recursos para restringir ou limitar o processamento dos dados pessoais de um indivíduo mediante solicitação? | Sim |
| O aplicativo fornece aos indivíduos a capacidade de corrigir ou atualizar seus dados pessoais? | Sim |
| As revisões regulares de privacidade e segurança de dados são executadas (por exemplo, Avaliações de Impacto de Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Não |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos do Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Permissão do Graph**  | **Tipo de permissão** |          **Justificativa**          | **Azure AD ID do aplicativo** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | Delegada | Recuperamos informações de grupo do Graph com a finalidade de filtrar os usuários recuperados por grupo | [270b510a-7cfb-4a9a-8071-5ceab03cf357](../azure/270b510a-7cfb-4a9a-8071-5ceab03cf357.md) |
>| User.Read.All | Delegada | Recuperamos objetos user do Graph para fins de provisionamento e atualização consistente de perfis de funcionários em nosso produto | [270b510a-7cfb-4a9a-8071-5ceab03cf357](../azure/270b510a-7cfb-4a9a-8071-5ceab03cf357.md) |
>| OnlineMeetingArtifact.Read.All | Delegada | Para nossa extensão de reuniões em nosso aplicativo Teams, exigimos a permissão para recuperar informações sobre os participantes da reunião | [d2a1ed44-6cca-44d2-9b9c-1c9c1d597093](../azure/d2a1ed44-6cca-44d2-9b9c-1c9c1d597093.md) |
>| OnlineMeetings.Read | Delegada | Para nossa extensão de reuniões em nosso aplicativo Teams, exigimos a permissão para recuperar informações sobre os participantes da reunião | [d2a1ed44-6cca-44d2-9b9c-1c9c1d597093](../azure/d2a1ed44-6cca-44d2-9b9c-1c9c1d597093.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

