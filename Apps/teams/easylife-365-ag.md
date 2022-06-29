---
title: Informações do aplicativo para EasyLife 365 da EasyLife 365 AG
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/27/2022
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o EasyLife 365, suas políticas de tratamento de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust-certification
ms.openlocfilehash: a50f566f963504e4c87d5b7a261373446afe6432
ms.sourcegitcommit: c06f3d478e1b4f66c02e2855ffac6de2f350208a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/29/2022
ms.locfileid: "66249324"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 23 de março de 2022</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">Exibir na loja do Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo EasyLife 365 AG à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | EasyLife 365 |
| ID | WA200003697 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | EasyLife 365 AG |
| Site da empresa | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| Termos de Uso do Aplicativo | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| Funcionalidade principal do aplicativo | Facilitar a governança! |
| Localização da sede da empresa | Suíça |
| Página de informações do aplicativo | [https://www.easylife365.cloud/governance/features](https://www.easylife365.cloud/governance/features) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Paas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo EasyLife 365 AG sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Metadados de grupo (id, nome, contagem de proprietários, informações de expiração); Informações do Usuário (id, userprincipalname, mail, preferredlanguage, userType) |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | Metadados de grupo (id, nome) e informações do usuário (id, email) em nosso log por 90 dias |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Países Baixos (o) |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Menos de 90 dias |
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
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | TraditionalAntiMalware, ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Sim |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Não |
| Você tem um firewall instalado no limite de rede externa? | Não |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| Autenticação Multifator (MFA) habilitada para: | DNSManagement, Credential, CodeRepositories |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| Você tem o software de Detecção e Prevenção de Intrusões (IDPS) implantado no perímetro do limite de rede que dá suporte ao seu aplicativo? | N/D |
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
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | Não |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Não |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Não |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | Não |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | Não |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | Não |
| O aplicativo está em conformidade com o NIST 800-171? | Não |
| O aplicativo foi certificado pela Cloud Security Alliance (CSA Star) ? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como ele coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://www.easylife365.cloud/web/privacy |
| O aplicativo executa a tomada de decisões automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para uma finalidade secundária não descrita no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficos, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo tem recursos para restringir ou limitar o processamento dos dados pessoais de um indivíduo mediante solicitação? | Não |
| O aplicativo fornece aos indivíduos a capacidade de corrigir ou atualizar seus dados pessoais? | Não |
| As revisões regulares de privacidade e segurança de dados são executadas (por exemplo, Avaliações de Impacto de Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | Não |

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
| Aplicativos e suplementos do Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Sim |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Permissão do Graph**  | **Tipo de permissão** |          **Justificativa**          | **Azure AD ID do aplicativo** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | Delegada | Permite ler Grupos ou Equipes | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Group.ReadWrite.All | Delegada | Permite manipualizar metadados de Grupos ou Equipes | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| GroupMember.Read.All | Delegada | Lê membros de um grupo | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.Read.All | Delegada | Permite recuperar metadados da conta de convidado | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.ReadBasic.All | Delegada | Permite pesquisar membros ou contas de convidado em uma organização | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Channel.Create | aplicação | Cria canais para uma equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Channel.ReadBasic.All | aplicação | Lê canais de uma equipe existente | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.Read.All | aplicação | Obter modelos atuais de configuração de conta de Grupo e Convidado | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.ReadWrite.All | aplicação | Aplicar configurações de conta de convidado para o Grupo ou a Equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Create | aplicação | Cria um grupo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | Ambas | Lê informações do grupo e recupera aliases de grupo | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.ReadWrite.All | aplicação | Manipula metadados de grupo no back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.Read.All | aplicação | Recupera associações de grupo ou equipe no back-end | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.ReadWrite.All | aplicação | Permite adicionar ou remover membros de um grupo ou equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| IdentityRiskyUser.ReadWrite.All | aplicação | Permite manipular contas de convidado e seus metadados | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Mail.Send | aplicação | Envia emails usando uma caixa de correio compartilhada | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| MailboxSettings.Read | aplicação | Recupera as configurações de idioma preferenciais de um usuário | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Reports.Read.All | aplicação | Recupera dados de uso de Grupos e Equipes | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Team.ReadBasic.All | aplicação | Recuperar informações básicas da equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamSettings.ReadWrite.All | aplicação | Permite arquivar e desarquivar uma equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Teams.Create | aplicação | Cria uma equipe | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.Read.All | aplicação | Recupera guias de uma equipe criada | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.ReadWrite.All | aplicação | Permite criar ou manipualizar guias de uma equipe criada | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Invite.All | aplicação | Convida um usuário para o locatário | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read | Delegada | Obtém informações do usuário e informações da organização | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read.All | Ambas | Recupera informações de convidado e usuário | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | Delegada | Ler todos os grupos de usuários | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| Group.ReadWrite.All | Delegada | Modificar metadados de Grupo do usuário e manipular Grupos e Equipes | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.Read.All | Delegada | Permite que um proprietário do grupo leia a associação de um grupo ou equipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.ReadWrite.All | Delegada | Permite que o proprietário do grupo manipule a associação de um grupo ou equipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamSettings.ReadWrite.All | Delegada | Permite arquivar ou desarquivar uma equipe | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsActivity.Send | aplicação | Usado para enviar notificações do Teams no back-end | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsAppInstallation.ReadForUser.All | aplicação | Verifique se o usuário tem o aplicativo EasyLife instalado antes de enviar notificações por meio do Teams. | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read | Delegada | Lê dados da organização e informações do usuário | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read.All | Delegada | Permite pesquisar outros membros ou contas de convidado em um diretório | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.ReadBasic.All | Delegada | Mostra as fotos do usuário | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| email | Delegada | Usado pela autenticação de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| offline_access | Delegada | Usado pela autenticação de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| openid | Delegada | Usado pela autenticação de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| perfil | Delegada | Usado pela autenticação de SSO | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>Informações de certificação

| **Control** | **Resultado da certificação do Microsoft 365** |
|:------------|:---------------------------------------|
| [**SEGURANÇA DO APLICATIVO**](../docs/certification-submission-guide.md#application-security) | **PASSAR** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Teste de penetração | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Revisão da Avaliação de Vulnerabilidade (TESTE DE PENETRAÇÃO/DAST/SAST) | No Escopo |
| [**SEGURANÇA OPERACIONAL**](../docs/certification-submission-guide.md#operational-security) | **PASSAR** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Proteção contra malware – Antivírus | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Proteção contra malware – Controle de Aplicativos | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Patches – Classificação de Risco | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de patch – aplicação de patch | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Verificação de vulnerabilidade | N/D |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall – Firewalls (ou tecnologias equivalentes) | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall – WAFs (Firewalls de Aplicativo Web) (opcional) | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Alterar Controle | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Desenvolvimento/implantação de software seguro | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento de Contas | No Escopo |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Detecção e prevenção contra intrusões (opcional) | N/D |
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
