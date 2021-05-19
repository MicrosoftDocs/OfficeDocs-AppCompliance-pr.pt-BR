---
title: Informações sobre o aplicativo para o Adobe Sign Add-In for Outlook pela Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/22/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para o Adobe Sign Add-In para Outlook, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 98180d11de4dcde3cc8820bddd46a9580a908cd6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552562"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Adobe Sign Add-In para Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 22 de fevereiro de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Adobe Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Adobe Sign Add-In para Outlook |
| ID | WA104381158 |
| Office 365 clientes suportados | Outlook 2013 ou mais tarde em Windows, Outlook 2016 ou mais tarde no Mac, Outlook na web |
| Nome da empresa parceira | Adobe Inc. |
| URL do site de parceiros | [https://www.adobe.com/](https://www.adobe.com/) |
| URL da Política de Privacidade | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL de Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Adobe Inc. sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | Delegada | Para preencher o documento anexado, e-mails de remetente e receptor e conteúdo de mensagens de e-mails para o sinal da Adobe para enviar a assinatura. Isso é para economizar tempo para o usuário redigitar esses campos no Adobe Sign. Depois que um acordo é assinado, nós compomos automaticamente um novo e-mail para o usuário enviar um e-mail para informar aos seus destinatários que a transação é feita. | O Adobe Sign salvará os anexos como arquivos temporários, que tem um prazo de validade de 24 horas. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| People.Read | Delegada | Para filtrar automaticamente o endereço de e-mail no &quot; Enviar para a experiência de &quot; assinatura, digitando algumas letras iniciais, não exija que os usuários digitem todos os e-mails. | O Adobe Sign só armazenará e-mails e exibirão o Nome dos destinatários nos contratos. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| User.Read | Delegada | Para ler o perfil do usuário e combinar seu perfil (basicamente, seu e-mail e userId) com o nosso banco de dados para que eles possam usar o Adobe Sign. | Para ler o perfil do usuário e combinar seu perfil (basicamente, seu e-mail e userId) com o nosso banco de dados para que eles possam usar o Adobe Sign. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| offline_access | Delegada | Para atualizar o token de acesso, quando o atual estiver expirado. Por exemplo, quando o usuário está em uma &quot; janela de envio para assinatura e &quot; deixá-lo inativo por muito tempo, precisamos atualizar um novo token quando o usuário está ativo. | Para atualizar o token de acesso, quando o atual estiver expirado. Por exemplo, quando o usuário está em uma &quot; janela de envio para assinatura e &quot; deixá-lo inativo por muito tempo, precisamos atualizar um novo token quando o usuário está ativo. | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| openid | Delegada | E-mail e UserId. Para fazer login com o usuário para garantir seu consentimento para a permissão do aplicativo Adobe Sign.  | O e-mail é o identificador exclusivo para usuários no Adobe Sign. Armazenamos iD de e-mail para mapear todas as atividades desse usuário para seu registro do Adobe Sign.  | 72d5ac5d-a427-408b-907d-72da3f33dd1 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nossos registros contêm informações suficientes para serem capazes de identificar e corrigir problemas do cliente. Os registros são retidos por 90 dias e o acesso é restrito. Nosso banco de dados armazena informações de identificação hashed para autenticação enquanto o usuário está off-line. A política de retenção do banco de dados está a 30 dias do último uso

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não temos nenhuma interação administrativa do cliente em nosso sistema para o aplicativo Microsoft Outlook.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Adobe Inc. sobre como este aplicativo lida com a autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Não |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
