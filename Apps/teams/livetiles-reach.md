---
title: Informações do aplicativo para alcance por LiveTiles
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para a Reach, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551992"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 22 de março de 2021</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo LiveTiles à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Reach |
| ID | WA200002045 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | LiveTiles |
| URL do site de parceiros | [https://livetilesglobal.com](https://livetilesglobal.com) |
| URL da página de informações do aplicativo Teams | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| URL da Política de Privacidade | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| URL de Termos de Uso | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo LiveTiles sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | aplicação | none | none | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | Delegada | User DisplayName, Endereço de E-mail do usuário, UPN. Necessário permitir que os usuários façaem login no aplicativo e obtenham informações básicas do usuário de login, como o nome do display. O endereço de e-mail é usado para enviar notificações por e-mail.  | User DisplayName, Endereço de E-mail do usuário, UPN. Necessário permitir que os usuários façaem login no aplicativo e obtenham informações básicas do usuário de login, como o nome do display. O endereço de e-mail é usado para enviar notificações por e-mail.  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | Delegada | User DisplayName, Endereço de E-mail do usuário, UPN, Departamento do Usuário, Título do Trabalho do Usuário, Número de Telefone do Usuário Móvel, Número de Telefone de Negócios do Usuário, Localização do usuário Office. Necessário permitir que os usuários procurem por outros usuários dentro do aplicativo (Phonebook) e veja o perfil básico e informações de contato de outros usuários.  | nenhuma | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | aplicação | Membros do grupo, grupos de anúncios em diretório. A associação de usuários do grupo é armazenada em um cache para minimizar chamadas à API Graph Microsoft. Necessário para permitir que os usuários procurem por grupos do Active Directory. Além disso, essa permissão é necessária para que o aplicativo resolva a adesão do grupo AD aos usuários em trabalhos web do backend. | Associação de Grupos de Usuários. A associação de usuários do grupo é armazenada em um cache para minimizar chamadas à API Graph Microsoft. Necessário para permitir que os usuários procurem por grupos do Active Directory. Além disso, essa permissão é necessária para que o aplicativo resolva a adesão do grupo AD aos usuários em trabalhos web do backend.  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | aplicação | Os dados recuperados do perfil do usuário dependem da configuração do recurso De Segmentação de Audiência especificada dentro do aplicativo. Necessário permitir que o aplicativo leia perfis de usuários sem um usuário assinado. A leitura de dados do perfil é necessária para o recurso de segmentação de informações dentro do aplicativo, para que as informações seja exibida para usuários específicos com base em um valor de propriedade de perfil específico.  | nenhuma | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| SendGrid, OneSignal | endereço de e-mail, nome de exibição | Enviar notificação ao usuário por e-mail e notificações push móveis |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>endereço de e-mail, UPN. máxima de 60 dias de retenção, depois disso eles são removidos

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os administradores podem entrar em contato com o suporte para qualquer inquérito

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo LiveTiles sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Não |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Sim |
| Seu aplicativo suporta políticas de acesso condicional? | Sim |
| Liste os tipos de políticas suportadas | Autenticação multifatorial, restringindo locais de usuários e faixas IP |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
