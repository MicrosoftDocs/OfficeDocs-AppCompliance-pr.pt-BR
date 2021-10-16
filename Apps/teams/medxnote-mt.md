---
title: Informações do aplicativo para Medxnote MT pelo Medxnote
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Medxnote MT, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 35f038dcfc9a7ee49153c585741465f444a4e1a4
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411586"
---
# <a name="medxnote-mt"></a>Medxnote MT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 28 de setembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/02ffb7cc-5fcd-4b31-bcbd-b24bbca74cc7" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001823" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Medxnote à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Medxnote MT |
| ID | WA200001823 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Medxnote |
| URL do site do parceiro | [https://medxnote.com/](https://medxnote.com/) |
| URL da Política de Privacidade | [https://medxnote.com/privacy-policy/](https://medxnote.com/privacy-policy/) |
| URL dos Termos de Uso | [https://medxnote.com/terms-conditions/](https://medxnote.com/terms-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Medxnote sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read.All | aplicação | estamos armazenando em cache Nome e email, usados no lado do hospital para verificar privilégios de usuários | ao enviar mensagens algumas vezes Nome e endereço de email são adicionados, estamos armazenando em cache esses dados no lado do servidor, eles também são usados para verificação opcional de privilégio no lado do hospital | [fc70bbbe-91c4-4d8f-a9c9-a022068d5752](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc70bbbe-91c4-4d8f-a9c9-a022068d5752) |
>| openid | delegado | estamos armazenando id de sessão em cache, id do usuário, token de portador e email, usado para entrar usuários no módulo Tarefa | usando-o para entrar em usuários no módulo Tarefa, estamos armazenar id de sessão, userid, email, tokens de portador | [fc70bbbe-91c4-4d8f-a9c9-a022068d5752](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc70bbbe-91c4-4d8f-a9c9-a022068d5752) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>endereço de email, Nome, id de locatário, id de canal pode aparecer em logs Todos os dados de log são excluídos automaticamente após 1 mês no máximo.
O acesso a eles é restrito a vários administradores de organização que têm acesso imposto 2FA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O acesso é restrito a vários administradores de organização que têm acesso imposto 2FA.
sistemas críticos só podem ser acessados a partir de determinados endereços IP

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


