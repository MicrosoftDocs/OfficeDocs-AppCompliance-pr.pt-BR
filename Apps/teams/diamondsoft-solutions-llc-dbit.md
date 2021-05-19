---
title: Informações de aplicação para DBit pela Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o DBit, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23995f613c3c3b6d7b2ab7d161f8710ccddf07d0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553952"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de junho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Diamondsoft Solutions, LLC à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | DBit |
| ID | WA200001536 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Diamondsoft Solutions, LLC |
| URL do site de parceiros | [https://www.dbit.io/index.html](https://www.dbit.io/index.html) |
| URL da Política de Privacidade | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| URL de Termos de Uso | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Diamondsoft Solutions, LLC sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada | Não armazenamos Graph informações em nosso sistema ou bancos de dados. | Entrar e ler o perfil do usuário | 1533d702-7604-463a-9fa3-63077c425e76 |
>| email | Delegada | Não armazenamos Graph informações em nosso sistema ou bancos de dados. | Exibir o endereço de email do usuário | 1533d702-7604-463a-9fa3-63077c425e76 |
>| offline_access | Delegada | Não armazenamos Graph informações em nosso sistema ou bancos de dados. | Manter acesso aos dados aos quais você concedeu acesso | 1533d702-7604-463a-9fa3-63077c425e76 |
>| openid | Delegada | Não armazenamos Graph informações em nosso sistema ou bancos de dados. | Conectar os usuários | 1533d702-7604-463a-9fa3-63077c425e76 |
>| perfil | Delegada | Não armazenamos Graph informações em nosso sistema ou bancos de dados. | Exibir os perfis básicos dos usuários | 1533d702-7604-463a-9fa3-63077c425e76 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para criar uma mensagem de boas-vindas | Não armazenamos informações de listas em nosso sistema ou bancos de dados. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não coletamos essas informações.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Usamos O Azure Cache Redis, a vida útil máxima dos dados em cache é de 300 minutos. Os itens de dados de cache são criptografados com AES256. Apenas o serviço de aplicativos pode se conectar ao Azure Cache Redis via SSL, a sequência de conexão é armazenada em Azure Environmental Variable.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

