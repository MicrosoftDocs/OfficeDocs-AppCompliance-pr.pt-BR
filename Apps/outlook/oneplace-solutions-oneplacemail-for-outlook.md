---
title: Informações sobre aplicativos do OnePlaceMail para Outlook soluções do OnePlace
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o OnePlaceMail para Outlook, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 18dc1ab4ba71102564c1c85f7ed3846d9f4f1700
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276525"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 31 de janeiro de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelas Soluções do OnePlace para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | OnePlaceMail para Outlook |
| ID | WA104380723 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook no iOS, Outlook no Android, Outlook na Web |
| Nome da empresa de parceiro | Soluções OnePlace |
| URL do site do parceiro | [https://www.oneplacesolutions.com](https://www.oneplacesolutions.com) |
| URL da Política de Privacidade | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| URL dos Termos de Uso | [https://www.oneplacesolutions.com/eula.html](https://www.oneplacesolutions.com/eula.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelas Soluções do OnePlace sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | Obrigatório para determinar Teams o usuário atual é membro. | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Mail.ReadWrite.Shared | delegado | Necessário para acessar propriedades de email para definir SharePoint colunas e adicionar a categoria Transferido para SharePoint no item de email | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| MailboxSettings.ReadWrite | delegado | Sem dados coletados ou usados, isso é usado para adicionar uma categoria à lista de categorias mestras em uma caixa de correio de usuários | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| Sites.ReadWrite.All | delegado | Necessário para definir propriedades em itens que o aplicativo carregou para SharePoint. | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.Read | delegado | Obrigatório para autenticação no microsoft Graph. | Os dados a seguir são armazenados pelo aplicativo em um banco de dados e são usados para acompanhamento de licenças de usuário e assinatura: ID do usuário, Email, Nome, Sobrenome. | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | delegado | Necessário para mostrar a imagem do perfil do usuário no campo se picker de pessoas. | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadBasic.All | delegado | Necessário para mostrar a imagem do perfil do usuário no campo se picker de pessoas. | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |
>| User.ReadWrite.All | delegado | Necessário para determinar se o serviço Teams está habilitado dentro do Office 365 de usuário. | Nenhum | [44a72516-136f-4a55-ae26-ef09977230be](https://docs.microsoft.com/microsoft-365-app-certification/azure/44a72516-136f-4a55-ae26-ef09977230be) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Sim | SharePoint URLs, nomes de biblioteca/lista/pasta | As informações organizacionais acessadas por são usadas para facilitar o processo de salvar emails e anexos de Exchange para SharePoint. Esses dados adicionais não são armazenados em repouso e são criptografados em trânsito. Exemplos desses dados incluem SharePoint de coluna, como valores de coluna De escolha, valores de taxonomia, nomes de Tipo de Conteúdo, Nomes de Pasta, Nomes de Site.  | Embora esses dados não são armazenados ou coletados pelo aplicativo, eles podem aparecer em telemetria/logs em que são mantidos por 90 dias. | Os dados não são armazenados |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| O serviço Chargify é usado para gerenciamento e cobrança de assinaturas. Para criação de assinatura no aplicativo (gratuita) o Nome, Sobrenome, Endereço de Email do usuário são compartilhados com Chargify. Para assinaturas compradas (que suportam vários usuários licenciados), os detalhes individuais do usuário não são compartilhados com o serviço Chargify. | Endereço de Email | Para poder comunicar eventos de ciclo de vida de assinatura ao usuário |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>EUII e OII aparecem na telemetria. Essas informações são armazenadas em Aplicativos Insights, criptografados em repouso, acesso controlado e excluído após 90 dias

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados armazenados no aplicativo são criptografados em trânsito e em repouso. Confiamos em Office 365 credenciais para nossos aplicativos, portanto, não armazenamos senhas de usuário em nosso sistema. O acesso a dados/logs/telemetria armazenados é fortemente controlado à equipe de administração interna com a necessidade de acessar as informações com o objetivo de executar e monitorar a saúde do aplicativo. Two-Factor Autenticação imposta para toda a equipe de administração interna.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelas Soluções do OnePlace sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
