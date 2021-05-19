---
title: Informações do aplicativo para OnePlaceMail para Outlook pela OnePlace Solutions
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o OnePlaceMail for Outlook, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5094d1ad5e7b028ac115529de16ddb9cbef2086f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552492"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 31 de janeiro de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela OnePlace Solutions para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | OnePlaceMail para Outlook |
| ID | WA104380723 |
| Office 365 clientes suportados | Outlook 2013 ou mais tarde em Windows, Outlook 2016 ou posterior no Mac, Outlook no iOS, Outlook no Android, Outlook na web |
| Nome da empresa parceira | Soluções OnePlace |
| URL do site de parceiros | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| URL da Política de Privacidade | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL de Termos de Uso | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela OnePlace Solutions sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegada | Necessário determinar Teams o usuário atual é membro de. | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |
>| Mail.ReadWrite.Shared | Delegada | Necessário acessar propriedades de e-mail para definir SharePoint colunas e adicionar a categoria Transferido à SharePoint no item de e-mail | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |
>| MailboxSettings.ReadWrite | Delegada | Sem dados coletados ou usados, este é usado para adicionar uma categoria à lista de categorias mestres em uma caixa de correio de usuários | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | Delegada | Necessário para definir propriedades em itens que o aplicativo carregou para SharePoint. | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | Delegada | Necessário para autenticação para o Microsoft Graph. | Os seguintes dados são armazenados pelo aplicativo em um banco de dados e são usados para rastreamento de assinatura e licença de usuário: Identificação do usuário, E-mail, Primeiro Nome, Sobrenome. | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | Delegada | Necessário mostrar a imagem do perfil do usuário no campo de coleta de pessoas. | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | Delegada | Necessário mostrar a imagem do perfil do usuário no campo de coleta de pessoas. | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | Delegada | Necessário determinar se o serviço Teams está habilitado dentro dos usuários Office 365 locação. | Nenhum | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Microsoft Office SharePoint Online | Sim | SharePoint URLs, nomes de biblioteca/lista/pasta | As informações organizacionais acessadas são usadas para facilitar o processo de salvar e-mails e anexos de Exchange para SharePoint. Esses dados adicionais não são armazenados em repouso e são criptografados em trânsito. Exemplos desses dados incluem valores de coluna SharePoint, como valores da coluna Escolha, valores de Taxonomia, nomes de tipo de conteúdo, nomes de pastas, nomes de sites.  | Embora esses dados não são armazenados ou coletados pelo aplicativo, ele pode aparecer em telemetria/logs onde são retidos por 90 dias. | Os dados não são armazenados |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O serviço Chargify é usado para gerenciamento de assinaturas e faturamento. Para criação de assinatura no aplicativo (gratuito) o Primeiro Nome, Sobrenome, Endereço de E-mail do usuário são compartilhados com o Chargify. Para assinaturas compradas (que suportam vários usuários licenciados) os detalhes individuais do usuário não são compartilhados com o serviço Chargify. | Endereço de Email | Para ser capaz de comunicar eventos do ciclo de vida de assinatura ao usuário |



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Euii e OII aparecem em telemetria. Essas informações são armazenadas em Insights de Aplicativos, criptografadas em repouso, controladas e excluídas após 90 dias

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados armazenados no aplicativo são criptografados em trânsito e em repouso. Contamos com Office 365 credenciais para nossos aplicativos, para que não armazenemos senhas de usuário em nosso sistema. O acesso aos dados/logs/telemetria armazenados é fortemente controlado pela equipe da administração interna com a necessidade de acessar as informações com o propósito de executar e monitorar a saúde do aplicativo. Two-Factor Autenticação aplicada para todos os funcionários da administração interna.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela OnePlace Solutions sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Sim |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
