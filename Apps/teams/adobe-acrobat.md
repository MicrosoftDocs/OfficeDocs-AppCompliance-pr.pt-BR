---
title: Informações de aplicativo para Adobe Acrobat da Adobe
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/09/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Adobe Acrobat, suas políticas de manipulação de dados, suas Microsoft Cloud App Security do catálogo de aplicativos e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: c87e0fadffed9b801f57668eae3d63285dd6a716
ms.sourcegitcommit: 4ceff6ef6aa0bae1075da646773b852970bb4049
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2022
ms.locfileid: "65874193"
---
# <a name="adobe-acrobat"></a>Adobe Acrobat

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 6 de março de 2022</p>

* <a href="https://teams.microsoft.com/l/app/10aea93d-20cf-44c2-b4a5-284c5ef2e6a5" target="_blank">Exibir no Teams armazenamento</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002564" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Adobe à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Adobe Acrobat |
| ID | WA200002564 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | Adobe |
| Site da empresa | [https://www.adobe.com](https://www.adobe.com) |
| Termos de Uso do Aplicativo | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |
| Funcionalidade principal do aplicativo | Com o Adobe Acrobat para Microsoft Teams, os criadores do formato de arquivo PDF estão fornecendo uma maneira de colaborar com todos em seu canal e coletar comentários em um único pdf &#8211; sem precisar sair do ambiente de Teams. Receba notificações de atividade quando outras pessoas tomarem medidas em seus documentos. Os revisores podem ver e comentar entre si&#8217;comentários, portanto, você&#8217;gastar menos tempo gerenciando conflitos |
| Localização da sede da empresa | Estados Unidos da América |
| Página de informações do aplicativo | [https://helpx.adobe.com/document-cloud/help/microsoft-teams...](https://helpx.adobe.com/document-cloud/help/microsoft-teams.html) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure, Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela Adobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | UserInfo, recurso OAuth, Recurso de Usuário,  |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | tenant_id, upn_hash, profile_and_token_info, oauth_state, ims_login_changed_at, preference_data, updated_at, created_at, expires_at |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Estados Unidos da América |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Menos de 30 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Sim |
| Você tem contratos de compartilhamento de dados em vigor com qualquer serviço de terceiros com o qual você compartilha dados de clientes da Microsoft? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

| **Information** | **Resposta** |
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
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
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

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | Não |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você obteve? | type2 |
| Data de certificação SOC2 mais recente | 2021-11-22 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Sim |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Sim |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | Sim |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | Sim |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | Não |
| O aplicativo está em conformidade com o NIST 800-171? | Sim |
| O aplicativo foi certificado pela Cloud Security Alliance (CSA Star) ? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como ele coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://business.adobe.com/privacy/general-data-protection-regulation.html |
| O aplicativo executa a tomada de decisões automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para uma finalidade secundária não descrita no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficos, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo tem recursos para restringir ou limitar o processamento dos dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo fornece aos indivíduos a capacidade de corrigir ou atualizar seus dados pessoais? | Sim |
| As revisões regulares de privacidade e segurança de dados são executadas (por exemplo, Avaliações de Impacto de Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Não |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? | Não usando nenhuma biblioteca de autenticação, estamos usando diretamente o protocolo OAuth 2.0 |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph permissão**  | **Tipo de permissão** |          **Justificativa**          | **Azure AD ID do aplicativo** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Files.ReadWrite.All | Delegada | Para poder listar e navegar pelos arquivos e pastas dos canais OneDrive e Teams do usuário. Permitimos que os usuários acessem esses arquivos, usem-os para executar operações neles e salvem arquivos de volta no armazenamento. | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| Team.ReadBasic.All | Delegada | Ler os nomes e as descrições das equipes | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| User.Read | Delegada | Entrar e ler o perfil do usuário | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| email | Delegada | Exibir o endereço de email dos usuários | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| offline_access | Delegada | manter o acesso aos dados aos quais você deu acesso | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| openid | Delegada | Conectar os usuários | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |
>| perfil | Delegada | exibir perfil básico de usuários | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

