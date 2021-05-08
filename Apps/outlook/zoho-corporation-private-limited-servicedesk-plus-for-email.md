---
title: Informações do aplicativo para ServiceDesk Plus para Email pela Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o ServiceDesk Plus for Email, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dbbafef5141b91c850c916c780cfb2cd89504f52
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252881"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus para Email

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Zoho Corporation Private Limited à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ServiceDesk Plus para Email |
| ID | WA104381518 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | Zoho Corporation Private Limited |
| URL do site do parceiro | [https://www.zoho.com/](https://www.zoho.com/) |
| URL da Política de Privacidade | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL dos Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Zoho Corporation Private Limited sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | aplicação |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | delegado |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | delegado | ID de email do usuário. | Permite que o usuário entre e dê acesso ao aplicativo ao UPN para habilitar o logon silencioso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | aplicação |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | delegado | ID de email, Nome, ID do Funcionário, Cargo, Telefone, Celular, Site, Departamento, Localidade, Foto de perfil do usuário. | Permite importar informações básicas dos usuários Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | delegado | ID de email do usuário. | Exibir o endereço de email do usuário. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | delegado |  | Mantenha acesso aos dados aos que você lhe deu acesso. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| perfil | delegado |  | Exibir o perfil básico do usuário. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="add-in-data-access"></a>Acesso a dados do complemento

Listar as permissões necessárias para acessar os dados da sua organização, a justificativa e a finalidade dessa permissão (para que o aplicativo usa essas informações?) e se o aplicativo armazena qualquer uma dessas informações em seus bancos de dados.

>| **Permissão**  | **Descrição** |
>|:----------------|:----------------|
>| Item de leitura | Esse complemento pode acessar informações pessoais sobre a mensagem ativa, como nomes de remetente, nomes de destinatários, endereços de email, corpo da mensagem e informações de anexo. O complemento pode enviar esses dados para um serviço de terceiros. Outros itens em sua caixa de correio&#8217;podem ser lidos ou modificados. |
>| Enviar Dados | Pode enviar dados pela Internet |

#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não coletamos EUII/PII em telemetria/logs. Temos scripts no local que estão procurando padrões e alertas para corrigi-lo

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Todos os dados são criptografados em REST. Somente pessoas autorizadas têm acesso ao sistema que está protegido de qualquer maneira, completamente auditado para todo tipo de acesso. MFA in-place for access, authorized accounts are maintained in a corporate directory and host


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

