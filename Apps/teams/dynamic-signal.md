---
title: Informações do aplicativo para sinal dinâmico por sinal dinâmico
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Todas as informações de segurança e conformidade disponíveis para o Sinal Dinâmico, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a5839d8c5b8fbd1b27cdd014d82a3a41022738b
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092442"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Sinal Dinâmico para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Dynamic Signal |
| ID | WA200000102 |
| Recursos | Bot, Guia |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Dynamic Signal |
| URL do site do parceiro | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL da página Teams de informações do aplicativo | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL da Política de Privacidade | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL dos Termos de Uso | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Sinal Dinâmico sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | delegado | O Sinal Dinâmico sincroniza o usuário do Azure AD com sua plataforma para permitir a ativação simplificada e desativação de usuários em tempo real. Os dados são armazenados no Sinal Dinâmico para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Leia permissões de um usuário específico para sincronizar usuários da plataforma de Sinal Dinâmico com o Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | delegado | O Sinal Dinâmico sincroniza o usuário do Azure AD com sua plataforma para permitir a ativação simplificada e desativação de usuários em tempo real. Os dados são armazenados no Sinal Dinâmico para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Leia permissões de um usuário específico para sincronizar usuários da plataforma de Sinal Dinâmico com o Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | delegado | O Sinal Dinâmico sincroniza o usuário do Azure AD com sua plataforma para permitir a ativação simplificada e desativação de usuários em tempo real. Os dados são armazenados no Sinal Dinâmico para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Retenha o acesso aos grupos e equipes do locatário. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | delegado | O Sinal Dinâmico sincroniza o usuário do Azure AD com sua plataforma para permitir a ativação simplificada e desativação de usuários em tempo real. Os dados são armazenados no Sinal Dinâmico para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Autenticar usuários com o Aplicativo de Sinal Dinâmico. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| openid entre usando openid directory.readwrite.all acesso ao domínio e aos grupos do locatário, adicione um aplicativo a uma equipe offline_access reter acesso aos grupos e equipes do locatário | openid Permitir autenticação independente. directory.readwrite.all acesso ao domínio e aos grupos do locatário, adicione um aplicativo a uma equipe offline_access mantenha acesso aos grupos e equipes do locatário Observação: o aplicativo do Sinal Dinâmico usa o bot de equipes para aplicar grupos e permissões criados no Sinal Dinâmico ao Teams para que um usuário ativo no Sinal Dinâmico tenha acesso aos mesmos grupos e usuários que no Teams. |  |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O Aplicativo e a Plataforma de Sinal Dinâmico utilizam informações do usuário para facilitar a integração com Microsoft Teams. Essas informações estão disponíveis para usuários com permissões apropriadas na plataforma Sinal Dinâmico. As informações relevantes são Nome, Nome de Exibição e Email. Essas informações são armazenadas nos logs da plataforma De sinal dinâmico de acordo com a política da respectiva organização com a licença de Sinal Dinâmico.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados PII coletados durante o registro e armazenados na plataforma Sinal Dinâmico incluem: Nome, Sobrenome, Email/Identificador e todos os campos personalizados que são definidos pela marca e/ou parceiros de agência. Quando os membros usam o Facebook ou o Twitter usando oAuth O Registro alguns dos dados do usuário expostos são apresentados à plataforma Sinal Dinâmico para pré-preencher dados. Esses dados incluem nome, local e foto. Os usuários têm controle sobre quais informações e dados são apresentados aos usuários nas páginas de bio da comunidade. Os membros podem optar por carregar fotos pessoais ou de marca, conectando contas sociais/canais e pontos de uso no programa a serem apresentados na página de bio.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

