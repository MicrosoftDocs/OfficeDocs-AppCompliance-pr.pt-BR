---
title: Informações do aplicativo para BlackBerry AtHoc por BlackBerry
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para BlackBerry AtHoc, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 60183f04c8f82a7e2c365bb26ee73db7a787147a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428354"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo BlackBerry para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | BlackBerry AtHoc |
| ID | WA200003065 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | BlackBerry |
| URL do site do parceiro | [https://www.blackberry.com](https://www.blackberry.com) |
| URL da página Teams de informações do aplicativo | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| URL da Política de Privacidade | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| URL dos Termos de Uso | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo BlackBerry sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | delegado | Acessamos os&#8217;básicos do usuário, como nome principal e link para o canal geral do teams (para o qual o usuário está autorizado) para enviar o cartão de alerta para as equipes. | Não armazenamos&#8217;os dados do usuário no banco de dados, mas na memória Bot. Armazenamos o nome principal do usuário, AAD Token, Token BlackBerry AtHoc, preferência/configuração do BlackBerry AtHoc Server na memória do bot. Precisa das informações para enviar solicitação de API para a API do Microsoft Graph e nosso BlackBerry AtHoc Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | delegado | Acessamos os&#8217;básicos do usuário, como nome principal e link para o canal geral do teams (para o qual o usuário está autorizado) para enviar o cartão de alerta para as equipes. | Não armazenamos&#8217;os dados do usuário no banco de dados, mas na memória Bot. Armazenamos o nome principal do usuário, AAD Token, Token BlackBerry AtHoc, preferência/configuração do BlackBerry AtHoc Server na memória do bot. Precisa das informações para enviar solicitação de API para a API do Microsoft Graph e nosso BlackBerry AtHoc Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | delegado | Acessamos os&#8217;básicos do usuário, como nome principal e link para o canal geral do teams (para o qual o usuário está autorizado) para enviar o cartão de alerta para as equipes. | Não armazenamos&#8217;os dados do usuário no banco de dados, mas na memória Bot. Armazenamos o nome principal do usuário, AAD Token, Token BlackBerry AtHoc, preferência/configuração do BlackBerry AtHoc Server na memória do bot. Precisa das informações para enviar solicitação de API para a API do Microsoft Graph e nosso BlackBerry AtHoc Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| email | delegado | Acessamos os&#8217;básicos do usuário, como nome principal e link para o canal geral do teams (para o qual o usuário está autorizado) para enviar o cartão de alerta para as equipes. | Não armazenamos&#8217;os dados do usuário no banco de dados, mas na memória Bot. Armazenamos o nome principal do usuário, AAD Token, Token BlackBerry AtHoc, preferência/configuração do BlackBerry AtHoc Server na memória do bot. Precisa das informações para enviar solicitação de API para a API do Microsoft Graph e nosso BlackBerry AtHoc Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| openid | delegado | Acessamos os&#8217;básicos do usuário, como nome principal e link para o canal geral do teams (para o qual o usuário está autorizado) para enviar o cartão de alerta para as equipes. | Não armazenamos&#8217;os dados do usuário no banco de dados, mas na memória Bot. Armazenamos o nome principal do usuário, AAD Token, Token BlackBerry AtHoc, preferência/configuração do BlackBerry AtHoc Server na memória do bot. Precisa das informações para enviar solicitação de API para a API do Microsoft Graph e nosso BlackBerry AtHoc Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| perfil | delegado | Acessamos os&#8217;básicos do usuário, como nome principal e link para o canal geral do teams (para o qual o usuário está autorizado) para enviar o cartão de alerta para as equipes. | Não armazenamos&#8217;os dados do usuário no banco de dados, mas na memória Bot. Armazenamos o nome principal do usuário, AAD Token, Token BlackBerry AtHoc, preferência/configuração do BlackBerry AtHoc Server na memória do bot. Precisa das informações para enviar solicitação de API para a API do Microsoft Graph e nosso BlackBerry AtHoc Server. | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>NA

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo BlackBerry sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
