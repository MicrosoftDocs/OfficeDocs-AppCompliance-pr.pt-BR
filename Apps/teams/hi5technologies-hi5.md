---
title: Informações do aplicativo para Hi5 by Hi5Technologies
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
description: Todas as informações de segurança e conformidade disponíveis para Hi5, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b0d55e54a8c144d9b44061b97d02d5728ec3023e
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092404"
---
# <a name="hi5"></a>Hi5

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/ca334a56-72b5-4613-81d4-77b1148df03c" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001610" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Hi5Technologies à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Hi5 |
| ID | WA200001610 |
| Recursos | Bot, Guia, Extensão de Mensagem |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Hi5Technologies |
| URL do site do parceiro | [https://www.get5.io/](https://www.get5.io/) |
| URL da Política de Privacidade | [https://www.get5.io/privacy](https://www.get5.io/privacy) |
| URL dos Termos de Uso | [https://www.get5.io/terms](https://www.get5.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Hi5Technologies sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegado | Armazenamos apenas as informações de sessão dos usuários Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-los a qualquer momento). Nenhuma outra informação é armazenada. | Obrigatório para logon e autenticação de SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| email | delegado | Armazenamos apenas as informações de sessão dos usuários Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-los a qualquer momento). Nenhuma outra informação é armazenada. | Obrigatório para logon e autenticação de SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| offline_access | delegado | Armazenamos apenas as informações de sessão dos usuários Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-los a qualquer momento). Nenhuma outra informação é armazenada. | Mantém que o usuário está vendo as informações corretas e podemos enviar as informações corretas para outras pessoas que ingressarem na mesma empresa/espaço de trabalho. | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| openid | delegado | Armazenamos apenas as informações de sessão dos usuários Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-los a qualquer momento). Nenhuma outra informação é armazenada. | Obrigatório para logon e autenticação de SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |
>| perfil | delegado | Armazenamos apenas as informações de sessão dos usuários Teams e o usuário precisa aprovar isso adicionando notificações (eles podem removê-los a qualquer momento). Nenhuma outra informação é armazenada. | Obrigatório para logon e autenticação de SSO em nosso servidor | 7cb50e3e-0427-409e-90d2-638eb28217c3 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para notificar o usuário em um canal que recebeu um Hi5 | Nenhuma informação é armazenada, o usuário será apenas @ pelo cartão enviado de volta no canal |  |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não, o Hi5 é apenas iFramed e todos os dados são armazenados com segurança.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Estamos usando o OAuth e fornecemos 3 opções de logon:
- Googles SSO (OAuth).
- Microsoft SSO (OAuth).
- Nossa própria criptografia, que é uma combinação de criptografia SHA e AES.
Depois de autenticado e conectado, seu nível de permissão concede acesso a seções autorizadas dentro da Plataforma Hi5.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36143" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

