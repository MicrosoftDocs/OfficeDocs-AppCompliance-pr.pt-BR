---
title: Informações do aplicativo para codetwo assinaturas de email para Office 365 por CodeTwo
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para CodeTwo Email Signatures para Office 365, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 79db12fe65495df15e21b46e810abd8bbd017359
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59275794"
---
# <a name="codetwo-email-signatures-for-office-365"></a>CodeTwo Email Signatures for Office 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de agosto de 2021</p>

* <a href="https://appsource.microsoft.com/product/web-apps/codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por CodeTwo para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | CodeTwo Email Signatures for Office 365 |
| ID | codetwo.3d2daeb9-a008-4070-a35c-cda39bd30a69 |
| Nome da empresa de parceiro | CodeTwo |
| URL do site do parceiro | [https://www.codetwo.com](https://www.codetwo.com) |
| URL da Política de Privacidade | [https://www.codetwo.com/regulations/privacy](https://www.codetwo.com/regulations/privacy) |
| URL dos Termos de Uso | [https://www.codetwo.com/license-agreement](https://www.codetwo.com/license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo CodeTwo sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Permite que os usuários entre no aplicativo e permita que o aplicativo leia o perfil de usuários assinados. Ele também permite que o aplicativo leia informações básicas da organização de usuários assinados. | Nenhum dado é armazenado. | [2a93620e-4345-4e3b-9bae-0195f08aab69](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a93620e-4345-4e3b-9bae-0195f08aab69) |
>| User.Read | delegado | Permite aos usuários entrar no aplicativo e permite ao aplicativo ler o perfil de usuários conectados. Também permite que o aplicativo leia as informações básicas da empresa sobre os usuários conectados. | Nenhum dado é armazenado. | [7afd058a-f568-4496-96b1-28d06ab3500f](https://docs.microsoft.com/microsoft-365-app-certification/azure/7afd058a-f568-4496-96b1-28d06ab3500f) |
>| Directory.AccessAsUser.All | delegado | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | Nenhum dado é armazenado. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| Directory.Read.All | ambos | Permite que o aplicativo leia dados em sua organização&#8217;diretório, como usuários, grupos e aplicativos. | Nenhum dado é armazenado. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.ReadBasic.All | delegado | Permite ao aplicativo ler um conjunto básico de propriedades de perfil de outros usuários em sua organização em nome do usuário conectado. Isso inclui nome de exibição, nome e sobrenome, endereço de email e foto. As informações são usadas para personalizar automaticamente assinaturas de email para usuários. | Nenhum dado é armazenado. | [cb657bc2-9910-4b9c-82a0-6f4f3a47006b](https://docs.microsoft.com/microsoft-365-app-certification/azure/cb657bc2-9910-4b9c-82a0-6f4f3a47006b) |
>| User.Read | delegado | Permite aos usuários entrar no aplicativo e permite ao aplicativo ler o perfil de usuários conectados. Ele também permite que o aplicativo leia informações básicas da empresa de usuários assinados. Usado para registrar o usuário no serviço CodeTwo. | Nenhum dado é armazenado. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| email | delegado | Permite ao aplicativo ler o endereço de email principal do usuário. Usado para registrar o usuário no serviço CodeTwo. | Nenhum dado é armazenado. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| offline_access | delegado | Permite que o aplicativo veja e atualize os dados aos que você deu acesso a ele, mesmo quando os usuários não estão usando o aplicativo no momento. Isso não dá ao aplicativo permissões adicionais. | Nenhum dado é armazenado. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| openid | delegado | Permite aos usuários entrar no aplicativo com contas corporativas ou de estudante e permite ao aplicativo ver informações básicas do perfil do usuário. Usado para registrar o usuário no serviço CodeTwo. | Nenhum dado é armazenado. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |
>| perfil | delegado | Permite que o aplicativo veja o perfil básico do usuário (nome, foto, nome de usuário). Usado para registrar o usuário no serviço CodeTwo. | Nenhum dado é armazenado. | [ce60db2f-439f-4e45-bfdc-d4c827c1820d](https://docs.microsoft.com/microsoft-365-app-certification/azure/ce60db2f-439f-4e45-bfdc-d4c827c1820d) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os clientes podem acessar e corrigir seus dados da organização de contatos e configurações &amp; de serviço por meio do Painel de Administração codeTwo. Eles também podem entrar em contato com a equipe de segurança de informações CodeTwo por meio de um formulário dedicado ( para exercer qualquer um dos direitos descritos em CodeTwo Terms and Privacy ( , ou seja: acesso a https://www.codetwo.com/form/security-officer/) dados, retificação de dados, apagamento e restrição de processamento, retirada de consentimento e o direito de objeto ao https://www.codetwo.com/regulations/privacy) processamento.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36503" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo CodeTwo sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
