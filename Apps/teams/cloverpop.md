---
title: Informações do aplicativo para Cloverpop pelo Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Cloverpop, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eaee7a04f4d8e74f97eef1fae358f80a0c3e2249
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553222"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Cloverpop à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Cloverpop |
| ID | WA200001803 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Cloverpop |
| URL do site de parceiros | [https://www.cloverpop.com](https://www.cloverpop.com) |
| URL da Política de Privacidade | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL de Termos de Uso | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Cloverpop sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada | armazenar dados do usuário como. e-mail, oid, givenName, familyName, avatar de usuário, identificação do objeto do usuário. id de organização (inquilinoD), nome de exibição da organização, também armazenamos em nossas equipes laterais/nomes de canais, ids, membros de equipes. Quando os usuários criam e interagem com as decisões, associamos esses dados ao usuário, equipe e organização que os criou. Também precisamos exibir essa propriedade em um UX amigável humano, portanto, estamos armazenando informações de exibição, por exemplo, o usuário&#8217;avatar. | permite que o usuário faça login e dá acesso ao aplicativo à sua UPN para habilitar&#8221; de login silencioso - e-mail, nome, oid, tid, givenName, sobrenome, familyName, avatar de usuário (foto), exibição da organizaçãoName | 1040474b-572d-4575-a423-95d262a8b8a |
>| openid | Delegada | Armazene dados de usuários como. e-mail, oid, givenName, familyName, avatar de usuário, identificação do objeto do usuário. id de organização (inquilinoD), nome de exibição da organização, também armazenamos em nossas equipes laterais/nomes de canais, ids, membros de equipes. Quando os usuários criam e interagem com as decisões, associamos esses dados ao usuário, equipe e organização que os criou. Também precisamos exibir essa propriedade em um UX amigável humano, portanto, estamos armazenando informações de exibição, por exemplo, o usuário&#8217;avatar. | Para implementar &#8220;faça login com Teams&#8221; em nosso aplicativo web. | 1040474b-572d-4575-a423-95d262a8b8a |
>| perfil | Delegada | Armazene dados de usuários como. e-mail, oid, givenName, familyName, avatar de usuário, identificação do objeto do usuário. id de organização (inquilinoD), nome de exibição da organização, também armazenamos em nossas equipes laterais/nomes de canais, ids, membros de equipes. Quando os usuários criam e interagem com as decisões, associamos esses dados ao usuário, equipe e organização que os criou. Também precisamos exibir essa propriedade em um UX amigável humano, portanto, estamos armazenando informações de exibição, por exemplo, o usuário&#8217;avatar. | Para implementar &#8220;faça login com Teams&#8221; em nosso aplicativo web. | 1040474b-572d-4575-a423-95d262a8b8a |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Acessamos os dados do nome do primeiro/último/exibição para exibir com precisão quais ações foram tomadas por usuários específicos relacionados a uma decisão. Usamos o endereço de e-mail como o identificador exclusivo para cada usuário em nosso db, pois permitimos que cada usuário pertença a várias organizações. Nós só acessamos esses dados quando eles interagem com o nosso aplicativo, por exemplo, se eles responderem a uma enquete. | Armazenamos os dados do nome do primeiro/último/exibição para exibir com precisão quais ações foram tomadas por usuários específicos relacionados a uma decisão.  Armazenamos o endereço de e-mail porque o usamos como o identificador exclusivo para cada usuário em nosso db, pois permitimos que cada usuário pertença a várias organizações. Nós só armazenamos esses dados quando eles interagem com o nosso aplicativo, por exemplo, se eles responderem a uma enquete. Nossos dados de decisão devem ser um sistema de registro de decisões, por isso é importante que armazenemos os dados para identificar como cada usuário envolvido com uma decisão contribuiu para essa decisão. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim.
O ID da equipe é mostrado em nossos logs quando nosso aplicativo é interagido em uma equipe.
Temos acesso limitado aos nossos registros de produção aos nossos três fundadores que estão todos baseados nos EUA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O aplicativo Cloverpop é construído usando Ruby on Rails e está hospedado no Heroku PaaS (plataforma como serviço) que utiliza a AWS para sua infraestrutura em nuvem. Heroku e AWS têm relatórios SOC que podem ser acessados. Nosso aplicativo usa PostgreSQL para armazenamento de dados em repouso e é um ambiente de vários inquilinos.
 
Todo o nosso código tem testes automatizados escritos para ele que abrange a segurança de acesso a dados. Cada compilação passa por um rigoroso processo de revisão de código para segurança e um processo manual de teste de QA que também inclui verificações para autenticação do usuário e acesso a dados através de ações de usuário disponíveis. Há uma clara separação entre nosso ambiente de produção e todos os outros ambientes, como desenvolvimento e testes.
 
Apenas pessoal selecionado tem acesso ao ambiente de produção e banco de dados: fundadores da empresa e um pequeno punhado de funcionários avaliados que passaram por verificações de antecedentes e têm uma necessidade quantificada (como o suporte ao cliente).

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

