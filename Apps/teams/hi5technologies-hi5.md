---
title: Informações do aplicativo para Hi5 por Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Hi5, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 983f86210f224bc492f54a7ab65192dee5b4ad6c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552112"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Hi5Technologies à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Hi5 |
| ID | WA200001610 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Hi5Technologies |
| URL do site de parceiros | [https://www.get5.io/](https://www.get5.io/) |
| URL da Política de Privacidade | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL de Termos de Uso | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Hi5Technologies sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada | Nós apenas armazenamos as informações da sessão dos usuários de Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-lo a qualquer momento). Nenhuma outra informação é armazenada. | Necessário para login e autenticação SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| email | Delegada | Nós apenas armazenamos as informações da sessão dos usuários de Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-lo a qualquer momento). Nenhuma outra informação é armazenada. | Necessário para login e autenticação SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | Delegada | Nós apenas armazenamos as informações da sessão dos usuários de Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-lo a qualquer momento). Nenhuma outra informação é armazenada. | Afirma que o usuário está vendo as informações corretas e podemos enviar as informações corretas para outras pessoas que aderirem à mesma empresa/espaço de trabalho. | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | Delegada | Nós apenas armazenamos as informações da sessão dos usuários de Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-lo a qualquer momento). Nenhuma outra informação é armazenada. | Necessário para login e autenticação SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| perfil | Delegada | Nós apenas armazenamos as informações da sessão dos usuários de Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-lo a qualquer momento). Nenhuma outra informação é armazenada. | Necessário para login e autenticação SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para notificar o usuário em um canal que recebeu um Hi5 | Nenhuma informação é armazenada, o usuário será apenas @ pelo cartão enviado de volta no canal |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não, o Hi5 é meramente iFramed e todos os dados são armazenados com segurança.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Estamos usando o OAuth e fornecemos 3 opções de login:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- Nossa própria criptografia que é uma combinação de criptografia SHA e AES.
Uma vez autenticado e logado, seu nível de permissão concede acesso a seções autorizadas dentro da Plataforma Hi5.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

