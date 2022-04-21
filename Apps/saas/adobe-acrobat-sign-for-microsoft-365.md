---
title: Informações de aplicativo para o Adobe Acrobat Sign para Microsoft 365 da Adobe
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/20/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Adobe Acrobat Sign para Microsoft 365, suas políticas de manipulação de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 9b87349c5829954b6c2f421590406110d32d85fe
ms.sourcegitcommit: 9dbbec778006471c0193a7fd39e2f81e7d441275
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/21/2022
ms.locfileid: "65014311"
---
# <a name="adobe-acrobat-sign-for-microsoft-365"></a>Adobe Acrobat Sign para Microsoft 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 11 de abril de 2022</p>

* <a href="https://appsource.microsoft.com/product/web-apps/adobe.adobe_sign_msft_saas_offer" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Adobe à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Adobe Acrobat Sign para Microsoft 365 |
| ID | adobe.adobe_sign_msft_saas_offer |
| Nome da empresa parceira | Adobe |
| Site da empresa | [https://acrobat.adobe.com/us/en/sign.html](https://acrobat.adobe.com/us/en/sign.html) |
| Termos de Uso do Aplicativo | [https://www.adobe.com/legal/licenses-terms.html](https://www.adobe.com/legal/licenses-terms.html) |
| Funcionalidade principal do aplicativo | Mantenha os fluxos de trabalho de assinatura de documentos se movendo rapidamente ao adicionar o Adobe Sign ao Office-Outlook-Team. A partir desses produtos, você pode enviar e assinar documentos para assinaturas e aprovações legalmente &#8212; com a solução de assinatura automática preferencial da Microsoft. |
| Localização da sede da empresa | Estados Unidos da América |
| Página de informações do aplicativo | [https://helpx.adobe.com/sign/using/microsoft-teams-integrat...](https://helpx.adobe.com/sign/using/microsoft-teams-integration-user-guide.html) |
| Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo? | Híbrido |
| Quais provedores de nuvem de hospedagem o aplicativo usa? | Aws, Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela Adobe sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo ou a infraestrutura subjacente processa dados relacionados a um cliente da Microsoft ou seu dispositivo? | Sim |
| Quais dados são processados pelo seu aplicativo? | Para atualizar o token de acesso, quando o atual estiver expirado. Por exemplo, quando &quot;&quot; o usuário está em uma janela de envio de assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário estiver ativo. |
| O aplicativo dá suporte ao TLS 1.1 ou superior? | Sim |
| O aplicativo ou a infraestrutura subjacente armazena dados do cliente da Microsoft? | Sim |
| Quais dados são armazenados em seus bancos de dados? | Para atualizar o token de acesso, quando o atual estiver expirado. Por exemplo, quando &quot;&quot; o usuário está em uma janela de envio de assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário estiver ativo. |
| Se a infastructure subjacente processa ou armazena dados do cliente da Microsoft, onde esses dados são armazenados geograficamente? | Estados Unidos da América |
| Você tem um processo estabelecido de locação e descarte de dados? | Sim |
| Por quanto tempo os dados são retidos após o encerramento da conta? | Menos de 30 dias |
| Você tem um processo de gerenciamento de acesso a dados estabelecido? | Sim |
| Você transfere dados do cliente ou conteúdo do cliente para terceiros ou subprocessados? | Não |

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

| **Information** | **Resposta** |
|:----------------|:-------------|
| O aplicativo está em conformidade com a HIPAA (Health Insurance Portability and Accounting Act)? | Não |
| O aplicativo está em conformidade com a Aliança de Confiança de Informações de Integridade, a Estrutura de Segurança Comum (HITRUST CSF)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 1)? | Não |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 2)? | Sim |
| Qual certificação do SOC 2 você obteve? | type2 |
| Data de certificação SOC2 mais recente | 2020-11-24 |
| O aplicativo está em conformidade com os Controles da Organização do Serviço (SOC 3)? | Não |
| Você realiza avaliações anuais de PCI DSS em relação ao aplicativo e seu ambiente de suporte? | Sim |
| O aplicativo ISO 27001 (Organização Internacional para Padronização) é certificado? | Sim |
| O aplicativo está em conformidade com a ISO 27018 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27017 (Organização Internacional para Padronização)? | Não |
| O aplicativo está em conformidade com a ISO 27002 (Organização Internacional para Padronização)? | Não |
| O aplicativo FedRAMP (Federal Risk and Authorization Management Program) está em conformidade? | Sim |
| O aplicativo está em conformidade com a LEI de Privacidade e Direitos Educacionais da Família (FERPA)? | Sim |
| O aplicativo está em conformidade com a COPPA (Children's Online Privacy Protection Act)? | Sim |
| O aplicativo está em conformidade com Sarbanes-Oxley Act (SOX)? | N/D |
| O aplicativo está em conformidade com o NIST 800-171? | N/D |
| O aplicativo foi certificado pela Cloud Security Alliance (CSA Star) ? | Sim |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Resposta** |
|:----------------|:-------------|
| Você tem GDPR ou outros requisitos de privacidade ou proteção de dados ou obrigações (como CCPA)? | Sim |
| O aplicativo tem um aviso de privacidade voltado para o externo que descreve como ele coleta, usa, compartilha e armazena dados do cliente? | Sim |
| URL da Política de Privacidade | https://helpx.adobe.com/sign/help/adobesign_gdpr_compliance.html |
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
| Seu aplicativo usa a versão mais recente da MSAL (Biblioteca de Autenticação da Microsoft) ou do Microsoft Identity Web para autenticação? | Não |
| Se seu aplicativo não usar uma das bibliotecas acima, qual biblioteca ou biblioteca de autenticação ele usa? | adal (com plano de migração para a MSAL) |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo dá suporte à CAE (Avaliação Contínua de Acesso) | Não |
| Seu aplicativo armazena credenciais no código? | Não |
| Aplicativos e suplementos para Microsoft 365 podem usar APIs adicionais da Microsoft fora do Microsoft Graph. Seu aplicativo ou suplemento usa APIs adicionais da Microsoft? | Sim |

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

>|   **Graph permissão**  | **Tipo de permissão** |          **Justificativa**          | **ID do aplicativo do Azure AD** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Mail.ReadWrite | Delegada | Para preencher o documento anexado, os emails do remetente e do destinatário e o conteúdo da mensagem de emails para o adobe sign para enviar para assinatura. Isso é para economizar tempo do usuário para digitá-los novamente no Adobe Sign. Depois que um contrato for assinado, redigimos automaticamente um novo email para o usuário enviar um email para informar aos destinatários que a transação foi concluída. O Adobe Sign salvará os anexos como arquivos temporários, que têm uma expiração de 24 horas. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| People.Read | Delegada | Para preencher automaticamente o endereço de &quot;&quot; email na experiência Enviar para assinatura, digitando algumas letras iniciais, não exija que os usuários digitem os emails inteiros. O Adobe Sign armazenará apenas emails e displayName de destinatários nos contratos. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| User.Read | Delegada | Para ler o perfil do usuário e corresponder seu perfil (basicamente, seu email e userId) ao nosso banco de dados para que ele possa usar o Adobe Sign. Para ler o perfil do usuário e corresponder seu perfil (basicamente, seu email e userId) ao nosso banco de dados para que ele possa usar o Adobe Sign. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| offline_access | Delegada | Para atualizar o token de acesso, quando o atual estiver expirado. Por exemplo, quando &quot;&quot; o usuário está em uma janela de envio de assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário estiver ativo. Para atualizar o token de acesso, quando o atual estiver expirado. Por exemplo, quando &quot;&quot; o usuário está em uma janela de envio de assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário estiver ativo. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |
>| openid | Delegada | Email e UserId. Para conectar o usuário para garantir seu consentimento para a permissão de usar o aplicativo Adobe Sign. O email é o identificador exclusivo para usuários no Adobe Sign. Armazenamos a ID de email para que possamos mapear todas as atividades desse usuário para seu registro do Adobe Sign. | [ea36b867-ca67-45fd-a61b-d2be86273167](../azure/ea36b867-ca67-45fd-a61b-d2be86273167.md) |

>Este aplicativo não tem APIs adicionais.

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

