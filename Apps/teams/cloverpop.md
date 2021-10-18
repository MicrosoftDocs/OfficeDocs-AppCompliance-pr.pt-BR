---
title: Informações do aplicativo para o Cloverpop pelo Cloverpop
ms.author: elmalova
author: elenamalova
ms.date: 08/04/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Cloverpop, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 93b31587f920416def80740ed2ebf3a399e0879c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429188"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Cloverpop para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Cloverpop |
| ID | WA200001803 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Cloverpop |
| URL do site do parceiro | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| URL da Política de Privacidade | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Cloverpop sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | armazenar dados do usuário como. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Quando os usuários criam e interagem com decisões, associamos esses dados ao usuário, equipe e organização que os criou. Também precisamos exibir essa propriedade em um UX amigável humano, portanto, estamos armazenar informações de exibição, por exemplo, o usuário&#8217;avatar. | permite que o usuário entre e dê acesso ao aplicativo ao UPN para habilitar o logon silencioso&#8221; - email, nome, oid, tid, givenName, sobrenome, familyName, user avatar(photo), organização displayName | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| openid | delegado | Armazenar dados do usuário como. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Quando os usuários criam e interagem com decisões, associamos esses dados ao usuário, equipe e organização que os criou. Também precisamos exibir essa propriedade em um UX amigável humano, portanto, estamos armazenar informações de exibição, por exemplo, o usuário&#8217;avatar. | Para implementar &#8220;entrar com Teams&#8221; em nosso aplicativo Web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| perfil | delegado | Armazenar dados do usuário como. email, oid, givenName, familyName, user avatar, user object id. organization id(tenantId), organization display name, Also we store on our side teams/channels names, ids, teams members. Quando os usuários criam e interagem com decisões, associamos esses dados ao usuário, equipe e organização que os criou. Também precisamos exibir essa propriedade em um UX amigável humano, portanto, estamos armazenar informações de exibição, por exemplo, o usuário&#8217;avatar. | Para implementar &#8220;entrar com Teams&#8221; em nosso aplicativo Web. | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Acessamos os dados de nome de primeira/última/exibição para exibir com precisão quais ações foram tomadas por usuários específicos relacionados a uma decisão. Usamos o endereço de email como o identificador exclusivo para cada usuário em nosso db, pois permitimos que cada usuário pertença a várias organizações. Só acessamos esses dados quando eles interagem com nosso aplicativo, por exemplo, se eles responderem a uma sondagem. | Armazenamos os dados de nome de primeira/última/exibição para exibir com precisão quais ações foram tomadas por usuários específicos relacionados a uma decisão.  Armazenamos o endereço de email porque o usamos como o identificador exclusivo para cada usuário em nosso db, pois permitimos que cada usuário pertença a várias organizações. Armazenamos esses dados somente quando eles interagem com nosso aplicativo, por exemplo, se eles responderem a uma sondagem. Nossos dados de decisão devem ser um sistema de registro para decisões, portanto, é importante armazenar os dados para identificar como cada usuário envolvido com uma decisão contribuiu para essa decisão. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim.
A ID da equipe é mostrada em nossos logs quando nosso aplicativo é interagido em uma equipe.
Temos acesso limitado aos nossos logs de produção para nossos três fundadores que são todos baseados nos EUA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O aplicativo Cloverpop é criado usando Ruby on Rails e é hospedado no Heroku PaaS (plataforma como serviço) que utiliza o AWS para sua infraestrutura de nuvem. Heroku e AWS têm relatórios SOC que podem ser acessados. Nosso aplicativo usa PostgreSQL para criptografado no armazenamento de dados de repouso e é um ambiente de vários locatários.
 
Todo o nosso código tem testes automatizados escritos para ele que abrangem a segurança de acesso a dados. Cada com build passa por um processo rigoroso de revisão de código para segurança e um processo de teste de QA manual que também inclui verificações para autenticação do usuário e acesso a dados por meio de ações de usuário disponíveis. Há uma separação clara entre nosso ambiente de produção e todos os outros ambientes, como desenvolvimento e teste.
 
Somente os funcionários selecionados têm acesso ao ambiente de produção e ao banco de dados: os fundadores da empresa e um pequeno grupo de funcionários controlados que passaram por verificações em segundo plano e têm uma necessidade quantificada (como o suporte ao cliente).

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

