---
title: Informações do aplicativo para Zoho CRM para e-mail da Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Zoho CRM para e-mail, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4f06fd2f6a14bbad4d1265df9754884d515f6cb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553672"
---
# <a name="zoho-crm-for-email"></a>Zoho CRM para e-mail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379468" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Zoho Corporation Private Limited à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Zoho CRM para e-mail |
| ID | WA104379468 |
| Office 365 clientes suportados | Outlook 2013 ou mais tarde em Windows, Outlook 2016 ou mais tarde no Mac, Outlook na web |
| Nome da empresa parceira | Zoho Corporation Private Limited |
| URL do site de parceiros | [https://www.zoho.com/](https://www.zoho.com/) |
| URL da Política de Privacidade | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL de Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Zoho Corporation Private Limited sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegada | O ID da pasta do calendário é armazenado para sincronizar os contatos do Zoho CRM com o &amp; vice-versa da Microsoft. As informações do calendário, como event_name, event_location e participant_details são armazenadas. | Permite que o usuário sincronize eventos do Office365 com o Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Delegada | O Id da pasta de contatos é armazenado para sincronizar os contatos do Zoho CRM com o &amp; vice-versa da Microsoft. Informações de contato como first_name, last_name, endereço de e-mail são armazenadas. | Permite que o usuário sincronize contatos do Office365 com o Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Delegada |  | Permite que o usuário importe o arquivo Office365 para o Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | Delegada |  | Permite que o usuário importe o arquivo Office365 para o Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegada | UserPrincipalName é armazenado para identificação do usuário | Permite que o usuário importe o arquivo Office365 para o Zoho CRM. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegada | Propriedades do usuário como first_name, last_name, endereço de e-mail. | Ler os perfis básicos de todos usuários | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegada | UserPrincipaName é armazenado para identificação do usuário | Exibir o endereço de e-mail do usuário | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegada |  | Manter acesso aos dados aos quais você concedeu acesso | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | Delegada |  | Exibir o perfil básico do usuário | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não coletamos EUII / PII em telemetria e troncos. Temos scripts no local para procurar e alertar para corrigir quaisquer dados que sejam visíveis

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O cliente pode selecionar os dados que precisam ser criptografados via EAR (Encryption At Rest) com restrições certaat. As senhas serão hashed por padrão. O acesso lógico aos servidores é fornecido através de uma rede dedicada isolada &amp; e é altamente seguro e


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

