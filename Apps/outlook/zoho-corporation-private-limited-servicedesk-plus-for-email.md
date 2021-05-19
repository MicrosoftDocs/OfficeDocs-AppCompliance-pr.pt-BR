---
title: Informações do aplicativo para ServiceDesk Plus para e-mail da Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o ServiceDesk Plus for Email, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dc342375eba7084f5afb31b0f879e46e959fa970
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553652"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus para e-mail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Zoho Corporation Private Limited à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ServiceDesk Plus para e-mail |
| ID | WA104381518 |
| Office 365 clientes suportados | Outlook 2013 ou mais tarde em Windows, Outlook 2016 ou mais tarde no Mac, Outlook na web |
| Nome da empresa parceira | Zoho Corporation Private Limited |
| URL do site de parceiros | [https://www.zoho.com/](https://www.zoho.com/) |
| URL da Política de Privacidade | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
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
>| Calendars.ReadWrite | aplicação |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Delegada |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Delegada |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Delegada | ID por e-mail do usuário. | Permite que o usuário faça login e dá acesso ao aplicativo à sua UPN para ativar o login silencioso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | aplicação |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Delegada | ID de e-mail, Nome, ID do funcionário, título de trabalho, Telefone, Mobile, Site, Departamento, Locale, Foto do perfil do usuário. | Permite importar informações básicas dos usuários de Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Delegada | ID por e-mail do usuário. | Veja o endereço de e-mail do usuário. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Delegada |  | Mantenha o acesso aos dados aos que você deu acesso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | Delegada |  | Veja o perfil básico do usuário. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não coletamos EUII / PII em telemetria / logs. Temos scripts no lugar que procuram padrões e alertam para corrigi-lo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados estão criptografados no REST. Somente pessoas autorizadas têm acesso ao sistema que é de qualquer forma protegido de acesso, completamente auditado para todo tipo de acesso. MFA em vigor para acesso, contas autorizadas são mantidas em diretório corporativo e host


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

