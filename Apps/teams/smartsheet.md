---
title: Informações do aplicativo para Smartsheet pelo Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Smartsheet, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551521"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Smartsheet à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Smartsheet |
| ID | WA104380975 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Smartsheet |
| URL do site de parceiros | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL da página de informações do aplicativo Teams | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL da Política de Privacidade | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL de Termos de Uso | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Smartsheet sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Delegada | Nenhum. | Permite que nosso aplicativo instale aplicativos em nome do usuário. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | Delegada | inquilinoId para recuperar informações para mostrar na interface do usuário. | Permite-nos ler quais aplicativos este inquilino está usando para que possamos verificar se precisamos instalar o aplicativo para eles. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | Delegada | teamId/groupId para entrega de mensagens. | Permite que nosso aplicativo leia informações básicas sobre um grupo (ou Teams equipe) bem como conversas. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | Delegada | teamId/groupId para entrega de mensagens. | Permite que nosso aplicativo inicie novas conversas em equipes. Esta permissão também inclui o escopo Read.All acima, mas precisamos deste também por razões técnicas. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | Delegada | userId. | Permite-nos ler informações básicas sobre um usuário durante o processo de auth. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | Delegada | refreshToken. | Permite que nosso aplicativo receba tokens de atualização e atualize o token auth em nome do usuário quando eles usam o aplicativo. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Bot Framework APIs | Sim | Usamos a API do Bot Framework para entregar mensagens como o aplicativo para o aplicativo de equipes. O Smartsheet armazena informações do usuárioId para acompanhar com quem o bot smartsheet está falando. |  | Nenhum |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O Smartsheet armazena informações em um estado de repouso criptografado dentro do nosso ambiente de data center de produção hospedado com a Equinix e no AWS S3, onde armazenamos anexos de clientes em baldes criptografados privados. |  | Usamos a API da estrutura do bot para entregar mensagens como o aplicativo para o aplicativo de equipes. O Smartsheet armazena informações do usuárioId para acompanhar com quem o bot smartsheet está falando. |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| O Smartsheet usa-o para ajudar a manter o controle de quem o bot está falando também. Durante o fluxo de auth inicial, criamos um registro de bot para o usuário no sistema de notificação Smartsheet. | Para o Smartsheet para Teams bot, armazenamos e-mails do usuário e userId de Teams para ajudar a acompanhar com quem o bot está falando.  O Smartsheet armazena inquilinos para ajudar a listar grupos dos que o usuário faz parte do diretório e groupIds para entrega de mensagens. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O Smartsheet criptografa todas as informações do usuário armazenadas e nossos administradores são obrigados a usar o 2FA. O Smartsheet opera como um provedor SaaS sem visualização e, por padrão, não revisamos o conteúdo que os clientes optam por carregar ou entrar na plataforma.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

