---
title: Informações de aplicativo para InStation por desenvolvedores Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o InStation, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
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

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelos Desenvolvedores Invillia para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | InStation |
| ID | WA200001701 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Developers Invillia |
| URL do site do parceiro | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL da Política de Privacidade | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL dos Termos de Uso | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelos Desenvolvedores Invillia sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | delegado | stores: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | stores: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | delegado | stores: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | stores: id, join_url, join_web_url e chat_id. Permite que o aplicativo crie reuniões | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | delegado | Permite que o aplicativo faça logon na organização em sua primeira etapa | atividade e avaliabilidade. Permite que o aplicativo capture o status dos usuários; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | delegado | Permite que o aplicativo faça logon na organização em sua primeira etapa, | atividade e avaliabilidade. Permite que o aplicativo capture o status dos usuários; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | delegado | stores: id, email, nome de exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | stores: id, email, nome de exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | delegado | stores: id, email, nome de exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | stores: id, email, nome de exibição, sobrenome e imagem. Permite que o aplicativo pesquise dados do usuário; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | delegado | Permite que o aplicativo capture as informações básicas&#180;administrador no primeiro logon | Permite que o aplicativo capture as informações básicas&#180;administrador no primeiro logon | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | delegado | stores: token e token de atualização. Permite que o aplicativo execute uma atualização no token MS | stores: token e token de atualização. Permite que o aplicativo execute uma atualização no token MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | delegado | Permite que o aplicativo faça logon na organização em sua primeira etapa | Permite que o aplicativo faça logon na organização em sua primeira etapa | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| perfil | delegado | Permite que o aplicativo capture as informações básicas&#180;Administrador no primeiro logon; | Permite que o aplicativo capture as informações básicas&#180;Administrador no primeiro logon; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Apenas salvamos logs de uso do usuário em nosso aplicativo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Apenas salvamos logs de uso do usuário em nosso aplicativo. Nada confidencial, exigindo nenhuma criptografia e apenas nossos administradores específicos têm acesso a esses dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

