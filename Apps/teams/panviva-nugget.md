---
title: Informações do aplicativo para a Pepita pelo Panviva
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Pepita, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7c32714b99ec38c2328c1443fb8747ac8b516a3e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429689"
---
# <a name="nugget"></a>Nugget

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 12 de outubro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/4e85cc82-5187-4059-af36-a49e7db32bee" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001737" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Panviva à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Nugget |
| ID | WA200001737 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Panviva |
| URL do site do parceiro | [https://www.panviva.com](https://www.panviva.com) |
| URL da Política de Privacidade | [https://www.panviva.com/privacy-policy/](https://www.panviva.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.panviva.com/terms-and-conditions](https://www.panviva.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Panviva sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim.
Teams id do usuário é armazenada : isso é necessário para que possamos recuperar informações sobre qual locatário ele está e se o usuário é administrador ou não.
Teams id da organização : isso é armazenado para que possamos recuperar os usuários em um locatário e recuperar os detalhes da assinatura para esse locatário específico.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Usamos o Azure CosmosDB para armazenar todos os dados do aplicativo. Para acessar os dados, você precisa de um ponto de extremidade e uma chave, ambos injetados no serviço de configuração usado para acessar os dados. O serviço de configuração só lida com solicitações com um token de portador que ele recebe na solicitação do nosso serviço de aplicativo bot. Esse token é originalmente criado pela Okta quando um usuário faz login no bot na interface da equipe. Esses dados podem ser acessados por administradores do Panviva que precisam fazer logon na plataforma Microsoft Azure com o uso da autenticação de dois fatores. Email e nome de usuário são armazenados na OKTA e só podem ser acessados com uma chave privada que é armazenada em um cofre de chaves que é acessado pelo serviço de configuração. Somente o serviço de configuração tem acesso ao cofre de chaves por meio do uso de identidades gerenciadas para que nenhuma credencial seja armazenada no aplicativo.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

