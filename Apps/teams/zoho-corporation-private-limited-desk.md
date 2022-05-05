---
title: Informações do aplicativo para Zoho Desk da Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Zoho Desk, suas políticas de manipulação de dados, suas informações do catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 6386c25acea352558965af02c99a49cd79baff6b
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65227976"
---
# <a name="zoho-desk"></a>Zoho Desk

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 20 de outubro de 2021</p>

* [Exibir no Teams armazenamento](https://teams.microsoft.com/l/app/091ec948-c0ee-4d56-aa9e-51c3d8316a9c)
* [Exibir no AppSource](https://appsource.microsoft.com/product/office/WA104382044)

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Zoho Corporation Private Limited à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Zoho Desk |
| ID | WA104382044 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa parceira | Zoho Corporation Private Limited |
| Site da empresa | [https://www.zoho.com](https://www.zoho.com) |
| Termos de Uso do Aplicativo | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |
| Funcionalidade principal do aplicativo | O Zoho Desk é um software de suporte técnico baseado na Web que oferece a capacidade de gerenciar suas atividades de suporte ao cliente com eficiência. O Zoho Desk permite atribuir, acompanhar e configurar alertas em tíquetes de suporte técnico facilmente. Você pode personalizar o Zoho Desk para sua empresa e garantir a satisfação em sua experiência de suporte ao cliente. |
| Localização da sede da empresa | Estados Unidos da América |
| Página de informações do aplicativo | [https://www.zoho.com/desk/help/](https://www.zoho.com/desk/help/) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela Zoho Corporation Private Limited sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para coletar?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **Azure AD ID do aplicativo** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.Read | Delegada |  | Ler arquivos de usuário. |  |
>| Files.Read.All | Delegada |  | Leia todos os arquivos que o usuário pode acessar. |  |
>| User.Read | Delegada |  | Entre e leia o perfil do usuário. |  |
>| User.ReadBasic.All | Delegada |  | Leia os perfis básicos de todos os usuários. |  |
>| email | Delegada |  | Exibir o endereço de email do usuário. |  |
>| offline_access | Delegada |  | Mantenha o acesso aos dados aos qual você deu acesso. |  |
>| perfil | Delegada |  | Exibir o perfil básico do usuário. |  |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não são serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se esse aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao qual ela é adicionada. Esse aplicativo usa essa funcionalidade?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>1)Há uma opção na interface do usuário para excluir as entidades, administradores e agentes dentro do zoho desk com opções de exclusão podem fazer isso. 2) Também temos opções para exportar usando as quais o administrador pode exportar e alcançar para sua finalidade.  3) Manter a auditoria no back-end, mediante solicitação do cliente, essas informações podem ser fornecidas.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Dados de perfil, Webhook de Conversa Pessoal. |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | ID de usuário, Nome de Usuário, Endereço de email |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Estados Unidos da América, Irlanda, Países Baixos (a), China, Japão, Índia, Austrália |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Menos de 90 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28308" target="_blank">Exibir em uma nova resposta</a> 
| **tabInformation** | **** |
|:----------------|:-------------|
| Você executa testes anuais de penetração no aplicativo? | Sim |
| , o aplicativo tem um plano de recuperação de desastre documentado, incluindo uma estratégia de backup e restauração? | Sim |
| , seu ambiente usa a proteção antimalware tradicional ou controles de aplicativo? | TraditionalAntiMalware, ApplicationControls |
| Você tem um processo estabelecido para identificar e classificar vulnerabilidades de segurança de risco? | Sim |
| , você tem uma política que rege o SLA (contrato de nível de serviço) para aplicar patches? | Sim |
| Você realiza atividades de gerenciamento de patch de acordo com os SLAs da política de aplicação de patch? | Sim |
| , seu ambiente tem algum software ou sistemas operacionais sem suporte? | Não |
| Você realiza a verificação de vulnerabilidade trimestral em seu aplicativo e a infastructure que dá suporte a ele? | Sim |
| , você tem um firewall instalado no limite de rede externa? | Sim |
| Você tem um processo de gerenciamento de alterações estabelecido usado para examinar e aprovar solicitações de alteração antes que elas sejam implantadas em produção? | Sim |
| , uma pessoa adicional está examinando e aprovando todas as solicitações de alteração de código enviadas para produção pelo desenvolvedor original? | Sim |
| , as práticas de codificação segura levam em conta classes de vulnerabilidade comuns, como o OWASP Top 10? | Sim |
| MFA (Autenticação Multifator) habilitada para: | CodeRepositories, DNSManagement, Credential |
| Você tem um processo estabelecido para provisionamento, modificação e exclusão de contas de funcionários? | Sim |
| , você tem o software de Detecção e Prevenção contra Intrusões (IDPS) implantado no perímetro do limite de rede que dá suporte ao seu aplicativo? | Sim |
| Você tem o log de eventos configurado em todos os componentes do sistema que dão suporte ao seu aplicativo? | Sim |
| Todos os logs são revisados regularmente por ferramentas humanas ou automatizadas para detectar possíveis eventos de segurança? | Sim |
| Quando um evento de segurança é detectado, os alertas são enviados automaticamente a um funcionário para triagem? | Sim |
| Você tem um processo formal de gerenciamento de risco de segurança da informação estabelecido? | Sim |
| , você tem um processo formal de resposta a incidentes de segurança documentado e estabelecido? | Sim |
| Você relata violações de dados de aplicativo ou serviço a autoridades de supervisão e indivíduos afetados pela violação dentro de 72 horas após a detecção? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | Sim |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você obteve? | type2 |
| Data de certificação SOC2 mais recente | 2021-11-30 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Não |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Sim |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Sim |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Sim |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Não |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | Não |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | Não |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | Não |
| O aplicativo está em conformidade com o NIST 800-171? | Não |
| O aplicativo foi certificado pela Cloud Security Alliance (CSA Star) ? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como ele coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://www.zoho.com/terms.html |
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

| **Information** | **Resposta** |
|:----------------|:-------------|
| Seu aplicativo se integra ao Microsoft Identity Platform (Azure AD) para logon único, acesso à API etc.? | Sim |
| Você examinou e atendeu a todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração? | Sim |
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Sim |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? |  |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Autenticação Multifator, exigindo dispositivos gerenciados pela organização para aplicativos específicos, Bloqueando comportamentos de entrada arriscada, limitando o acesso dado a pessoas que não sejam as funções administrativas  |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Sim |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Não |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph permissão**  | **Tipo de permissão** |          **Justificativa**          | **Azure AD ID do aplicativo** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Contacts.Read | Delegada | Ler contatos do usuário | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read | Delegada | Ler arquivos do usuário | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.All | Delegada | Ler todos os arquivos que o usuário pode acessar | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| Files.Read.Selected | Delegada | Ler arquivos selecionados pelo usuário | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.Read | Delegada | Entrar e ler o perfil do usuário | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| User.ReadBasic.All | Delegada | Ler os perfis básicos de todos usuários | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| email | Delegada | Exibir o endereço de email do usuário | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| offline_access | Delegada | Manter acesso aos dados aos quais você concedeu acesso | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |
>| perfil | Delegada | Exibir os perfis básicos dos usuários | [8a35e217-58cf-4eab-b2b4-384260d3d7f3](../azure/8a35e217-58cf-4eab-b2b4-384260d3d7f3.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

