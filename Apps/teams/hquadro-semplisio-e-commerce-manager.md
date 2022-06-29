---
title: Informações do aplicativo para o Semplisio e-commerce Manager da HQuadro
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 06/22/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Semplisio e o Gerenciador de comércio eletrônico, suas políticas de tratamento de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro STAR do CSA.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 0aa0282c79baec2c8dfebaeef26efa0f69c55636
ms.sourcegitcommit: c06f3d478e1b4f66c02e2855ffac6de2f350208a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/29/2022
ms.locfileid: "66247890"
---
# <a name="semplisio-e-commerce-manager"></a>Gerente de comércio eletrônico do Semplisio

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 4 de maio de 2022</p>

* <a href="https://teams.microsoft.com/l/app/9aa7a790-c743-4436-a4ba-1d540cbad3fe" target="_blank">Exibir na loja do Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004286" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo HQuadro à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Gerente de comércio eletrônico do Semplisio |
| ID | WA200004286 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | HQuadro |
| Site da empresa | [https://www.hquadro.it](https://www.hquadro.it) |
| Termos de Uso do Aplicativo | [https://www.semplisio.it/tc](https://www.semplisio.it/tc) |
| Funcionalidade principal do aplicativo | Gestisci il tuo ecommerce su Microsoft Teams: automatizza i processi, integrando i tuoi software e Microsoft 365 |
| Localização da sede da empresa | Itália |
| Página de informações do aplicativo | [https://www.semplisio.it/ecommerce-manager](https://www.semplisio.it/ecommerce-manager) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Iaas |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Azure, GCP |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pelo HQuadro sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

| **Information** | **Response** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | perfil de email Channel.ReadBasic.All Files.ReadWrite.AppFolder Files.ReadWrite.All Files.Read.All User.Read Team.ReadBasic.All Sites.Read.All openid offline_access Contacts.ReadWrite |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | id Team, canal de ID |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Países Baixos (a), Finlândia |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? |  |
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
| Seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | TraditionalAntiMalware |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Não |
| Você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| Seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Não |
| Você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| Uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| As práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| Autenticação Multifator (MFA) habilitada para: | CodeRepositories |
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
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | N/D |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | N/D |
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
| URL da Política de Privacidade | https://www.semplisio.it/privacy-policy/ |
| O aplicativo executa a tomada de decisões automatizada, incluindo a criação de perfil que pode ter um efeito legal ou um impacto semelhante? | Não |
| O aplicativo processa dados do cliente para uma finalidade secundária não descrita no aviso de privacidade (ou seja, marketing, análise)? | Não |
| Você processa categorias especiais de dados confidenciais (ou seja, origem racial ou étnica, opinião política, crenças religiosas ou filosóficos, dados genéticos ou biométricos, dados de saúde) ou categorias de dados sujeitos a leis de notificação de violação? | Não |
| O aplicativo coleta ou processa dados de menores (ou seja, indivíduos com menos de 16 anos)? | Não |
| O aplicativo tem recursos para excluir dados pessoais de um indivíduo mediante solicitação? | N/D |
| O aplicativo tem recursos para restringir ou limitar o processamento dos dados pessoais de um indivíduo mediante solicitação? | N/D |
| O aplicativo fornece aos indivíduos a capacidade de corrigir ou atualizar seus dados pessoais? | N/D |
| As revisões regulares de privacidade e segurança de dados são executadas (por exemplo, Avaliações de Impacto de Proteção de Dados ou avaliações de risco de privacidade) para identificar riscos relacionados ao processamento de dados pessoais para o aplicativo? | N/D |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Não |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? | @microsoft/teamsfx |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Sim |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos do Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Permissão do Graph**  | **Tipo de permissão** |          **Justificativa**          | **Azure AD ID do aplicativo** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Channel.ReadBasic.All | Delegada | nós o usamos para mostrar no aplicativo a lista de canais | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| Contacts.ReadWrite | Delegada | nós o usamos para escrever contatos no Outlook | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| Files.Read.All | Delegada | nós o usamos para ler arquivos no One Drive do cliente | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| Files.ReadWrite.All | Delegada | o usamos para gravar/criar um arquivo no One Drive do cliente | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| Files.ReadWrite.AppFolder | Delegada | o usamos para ler e gravar/criar uma pasta no One Drive do cliente | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| Sites.Read.All | Delegada | permitir que o aplicativo leia documentos e uma lista de itens do One Drive do cliente | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| Team.ReadBasic.All | Delegada | nós o usamos para mostrar no aplicativo a lista de equipes | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| User.Read | Delegada | nós o usamos para gerar tokens em nome de | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| email | Delegada | o usamos para logon único | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| offline_access | Delegada | nós o usamos para gerar tokens em nome de | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| openid | Delegada | nós o usamos para gerar tokens em nome de | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |
>| perfil | Delegada | nós o usamos para receber o cliente | [a44c880f-f691-4553-9855-4b256721933c](../azure/a44c880f-f691-4553-9855-4b256721933c.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

