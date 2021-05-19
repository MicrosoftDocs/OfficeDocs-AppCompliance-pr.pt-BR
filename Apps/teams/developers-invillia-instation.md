---
title: Informações do aplicativo para instation por desenvolvedores Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o InStation, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552242"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 6 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelos desenvolvedores invillia à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | InStation |
| ID | WA200001701 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Developers Invillia |
| URL do site de parceiros | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL da Política de Privacidade | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL de Termos de Uso | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Developers Invillia sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | Delegada | lojas: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | lojas: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | Delegada | lojas: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | lojas: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | Delegada | Permite que o aplicativo faça login na organização em seu primeiro passo | atividade e avaliabilidade. Permite que o aplicativo capture o status dos usuários; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | Delegada | Permite que o aplicativo faça login na organização em seu primeiro passo, | atividade e avaliabilidade. Permite que o aplicativo capture o status dos usuários; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | Delegada | lojas: id, correio, nome da exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | lojas: id, correio, nome da exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | Delegada | lojas: id, correio, nome da exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | lojas: id, correio, nome da exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | Delegada | Permite que o aplicativo capture as informações básicas do Administrador&#180;no primeiro login | Permite que o aplicativo capture as informações básicas do Administrador&#180;no primeiro login | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | Delegada | lojas: token e token de atualização. Permite que o aplicativo realize uma atualização no token MS | lojas: token e token de atualização. Permite que o aplicativo realize uma atualização no token MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | Delegada | Permite que o aplicativo faça login na organização em seu primeiro passo | Permite que o aplicativo faça login na organização em seu primeiro passo | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| perfil | Delegada | Permite que o aplicativo capture as informações básicas do Administrador&#180;no primeiro login; | Permite que o aplicativo capture as informações básicas do Administrador&#180;no primeiro login; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nós só salvamos logs de uso do usuário em nosso aplicativo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Nós só salvamos logs de uso do usuário em nosso aplicativo. Nada confidencial, não precisando de criptografia e apenas nossos administradores específicos têm acesso a esses dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

