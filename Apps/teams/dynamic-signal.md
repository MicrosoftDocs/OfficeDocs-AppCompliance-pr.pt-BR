---
title: Informações do aplicativo para sinal dinâmico por sinal dinâmico
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Dynamic Signal, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552222"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Dynamic Signal à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Dynamic Signal |
| ID | WA200000102 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Dynamic Signal |
| URL do site de parceiros | [https://dynamicsignal.com](https://dynamicsignal.com) |
| URL da página de informações do aplicativo Teams | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| URL da Política de Privacidade | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| URL de Termos de Uso | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Dynamic Signal sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada | O Dynamic Signal sincroniza o usuário do Azure AD à sua plataforma para permitir a ativação e desativação simplificadas dos usuários em tempo real. Os dados são armazenados no Dynamic Signal para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Leia permissões de um usuário específico para sincronizar usuários da plataforma Dynamic Signal com o Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | Delegada | O Dynamic Signal sincroniza o usuário do Azure AD à sua plataforma para permitir a ativação e desativação simplificadas dos usuários em tempo real. Os dados são armazenados no Dynamic Signal para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Leia permissões de um usuário específico para sincronizar usuários da plataforma Dynamic Signal com o Azure AD. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | Delegada | O Dynamic Signal sincroniza o usuário do Azure AD à sua plataforma para permitir a ativação e desativação simplificadas dos usuários em tempo real. Os dados são armazenados no Dynamic Signal para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Mantenha o acesso aos grupos e equipes do inquilino. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | Delegada | O Dynamic Signal sincroniza o usuário do Azure AD à sua plataforma para permitir a ativação e desativação simplificadas dos usuários em tempo real. Os dados são armazenados no Dynamic Signal para permitir que os usuários usem esse aplicativo enquanto a sincronização ocorre. | Autenticar os usuários com o Aplicativo de Sinal Dinâmico. | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| abrir sinal usando o openid directory.readwrite.all acesso ao domínio e grupos do inquilino, adicionar um aplicativo a uma equipe offline_access manter acesso aos grupos e equipes do inquilino | openid Permitir autenticação independente. directory.readwrite.all access to the tenant's domain and groups, add a a team to a team offline_access mantenha acesso aos grupos e equipes do inquilino Nota: O aplicativo do Dynamic Signal usa o bot de equipes para aplicar grupos e permissões criadas dentro do Dynamic Signal para Teams para que um usuário ativo no Dynamic Signal tenha acesso aos mesmos grupos e usuários que dentro de Teams. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O Aplicativo e a Plataforma de Sinal Dinâmico utilizam informações do usuário para facilitar a integração com Microsoft Teams. Essas informações estão disponíveis para usuários com permissões apropriadas dentro da plataforma Dynamic Signal. As informações relevantes são Nome, Nome de Exibição e E-mail. Essas informações são armazenadas dentro dos registros da plataforma Dynamic Signal de acordo com a política da respectiva organização com a licença Dynamic Signal.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do PII coletados durante o registro e armazenados dentro da plataforma Dynamic Signal incluem: Nome, Sobrenome, E-mail/Identificador e quaisquer campos personalizados que sejam configurados pela marca e/ou parceiros da agência. Quando os membros usam o Facebook ou Twitter usando o Registro oAuth, alguns dos dados do usuário expostos são apresentados à plataforma Dynamic Signal para pré-preencher dados. Esses dados incluem nome, localização e foto. Os usuários têm controle sobre quais informações e dados são apresentados aos usuários nas páginas biológicas para a comunidade. Os membros podem optar por carregar fotos pessoais ou de marca, conectando contas/canais sociais e uso/pontos no programa a ser apresentado na página biológica.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

