---
title: Informações do aplicativo para Adobe Sign for Word e PowerPoint por Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o Adobe Sign for Word e PowerPoint, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aa9b4a19f83574d7d9428bbf979ac7ee1375227c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552662"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign for Word and PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 12 de fevereiro de 2021</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Adobe Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Adobe Sign for Word and PowerPoint |
| ID | WA104381155 |
| Office 365 clientes com suporte | Word 2016 ou posterior no Mac, PowerPoint 2013 Service Pack 1 ou posterior no Windows, Word 2013 Service Pack 1 ou posterior no Windows, Word na Web, PowerPoint na Web, PowerPoint 2016 ou posterior no Mac |
| Nome da empresa de parceiro | Adobe Inc. |
| URL do site do parceiro | [https://www.adobe.com/](https://www.adobe.com/) |
| URL da Política de Privacidade | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| URL dos Termos de Uso | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Adobe Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | delegado | Para preencher o documento anexado, remetente e emails de destinatário e conteúdo de mensagens de emails para o Adobe assinar para enviar para assinatura. Isso é para economizar o tempo do usuário para retipo esses campos no Adobe Sign. Depois que um contrato é assinado, redigimos automaticamente um novo email para o usuário enviar um email para informar aos destinatários que a transação foi feita. | O Adobe Sign salvará os anexos como arquivos temporários, que têm um vencimento de 24 horas. | 72d5ac5d-a427-408b-907d-72da3f33dddd1 |
>| People.Read | delegado | Para preenchimento automático do endereço de email na experiência Enviar para assinatura, digitando algumas letras iniciais, não exige que os usuários &quot; &quot; digitem todos os emails. | O Adobe Sign armazenará apenas emails de destinatários e displayName nos contratos. | 72d5ac5d-a427-408b-907d-72da3f33dddd1 |
>| User.Read | delegado | Para ler o perfil do usuário e corresponder seu perfil (basicamente, seu email e userId) ao nosso banco de dados para que eles possam usar o Adobe Sign. | Para ler o perfil do usuário e corresponder seu perfil (basicamente, seu email e userId) ao nosso banco de dados para que eles possam usar o Adobe Sign. | 72d5ac5d-a427-408b-907d-72da3f33dddd1 |
>| offline_access | delegado | Para atualizar o token de acesso, quando o atual expirar. Por exemplo, quando o usuário está em uma janela de envio para assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário &quot; &quot; estiver ativo. | Para atualizar o token de acesso, quando o atual expirar. Por exemplo, quando o usuário está em uma janela de envio para assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário &quot; &quot; estiver ativo. | 72d5ac5d-a427-408b-907d-72da3f33dddd1 |
>| openid | delegado | Email e UserId. Para entrar no usuário para garantir seu consentimento para a permissão de usar o aplicativo Adobe Sign.  | Email é o identificador exclusivo para usuários no Adobe Sign. Armazenamos a ID de email para que possamos mapear todas as atividades desse usuário para seu registro do Adobe Sign.  | 72d5ac5d-a427-408b-907d-72da3f33dddd1 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nossos logs contêm informações suficientes para identificar e corrigir problemas do cliente. Os logs são mantidos por 90 dias e o acesso é restrito. Nosso armazenamento de banco de dados tem informações de identificação com hashed para autenticação enquanto o usuário está offline. A política de retenção de banco de dados está a 30 dias do último uso

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não temos nenhuma interação do administrador do cliente em nosso sistema para Microsoft Teams aplicativo.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Adobe Inc. sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
