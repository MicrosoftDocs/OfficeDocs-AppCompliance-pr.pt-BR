---
title: Informações do aplicativo para SEFOS por Meaplus AB
ms.author: elmalova
author: elenamalova
ms.date: 06/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para SEFOS, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d82485bff9e5e250ef0e77377000ace03df328ce
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276188"
---
# <a name="sefos"></a>SEFOS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 15 de junho de 2021</p>

* <a href="https://teams.microsoft.com/l/app/a9b13f17-540f-4b08-a48c-75051b68677e" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003219" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Meaplus AB à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SEFOS |
| ID | WA200003219 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Meaplus AB |
| URL do site do parceiro | [https://www.meaplus.com](https://www.meaplus.com) |
| URL da página Teams de informações do aplicativo | [https://sefos.se/en/sefos-i-teams/](https://sefos.se/en/sefos-i-teams/) |
| URL da Política de Privacidade | [https://www.meaplus.com/privacy-policy/](https://www.meaplus.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-...](https://www.meaplus.com/wp-content/uploads/2020/02/Meaplus-end_user_agreement.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Meaplus AB sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Criar reunião em nome do usuário | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| Mail.Send | delegado | Enviando convites de reunião | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| MailboxSettings.Read | delegado | Coletando o timezone para o usuário autenticado | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| People.Read | delegado | Pesquisar no adressbook de usuário autenticado | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| User.Read | delegado | Entrar e ler o perfil do usuário | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| email | delegado | Endereço de email para identificar o usuário no SEFOS. | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| openid | delegado | Entrar usuário | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |
>| perfil | delegado | Lendo o perfil do usuário | none | [23b236c3-685d-49f0-a7bf-012ef3dc9ec3](https://docs.microsoft.com/microsoft-365-app-certification/azure/23b236c3-685d-49f0-a7bf-012ef3dc9ec3) |


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

>Não aplicável, este é um sistema distribuído onde cada organização controla suas próprias informações em uma instalação local. . 

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Meaplus AB sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
