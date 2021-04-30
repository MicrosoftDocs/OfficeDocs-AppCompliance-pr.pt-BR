---
title: Informações do aplicativo para o Adobe Sign Add-In para Outlook por Adobe Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Todas as informações de segurança e conformidade disponíveis para o Adobe Sign Add-In para Outlook, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5ae63ddb614784164870b24508e0782bce49dd48
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092638"
---
# <a name="adobe-sign-add-in-for-outlook"></a>Adobe Sign Add-In para Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381158" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Adobe Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Adobe Sign Add-In para Outlook |
| ID | WA104381158 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | Adobe Inc. |
| URL do site do parceiro | [https://www.adobe.com/](https://www.adobe.com/) |
| URL da Política de Privacidade | [https://www.adobe.com/privacy/policy.html](https://www.adobe.com/privacy/policy.html) |
| URL dos Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Adobe Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | aplicação | Precisamos de dados do email para retirar o histórico de assinaturas do Adobe e o relatório de trilha de auditoria de todas as transações. https://helpx.adobe.com/sign/using/audit-reports-transaction-history.html | Para preencher o documento anexado, remetente e emails de destinatário e conteúdo de mensagens de emails para o Adobe assinar para enviar para assinatura. Isso é para economizar o tempo do usuário para retipo esses campos no Adobe Sign. Depois que um contrato é assinado, redigimos automaticamente um novo email para o usuário enviar um email para informar aos destinatários que a transação foi feita. |  |
>| People.Read | delegado |  | Para preenchimento automático do endereço de email na experiência Enviar para assinatura, digitando algumas letras iniciais, não exige que os usuários &quot; &quot; digitem todos os emails. |  |
>| User.Read | delegado |  | Para ler o perfil do usuário e corresponder seu perfil (basicamente, seu email) ao nosso banco de dados para que eles possam usar o Adobe Sign. |  |
>| offline_access | delegado |  | Para atualizar o token de acesso, quando o atual expirar. Por exemplo, quando o usuário está em uma janela de envio para assinatura e a deixa inativa por muito tempo, precisamos atualizar um novo token quando o usuário &quot; &quot; estiver ativo. |  |
>| openid | delegado | Email é o identificador exclusivo para usuários no Adobe Sign. Armazenamos a ID de email para que possamos mapear todas as atividades desse usuário para seu registro do Adobe Sign.  | Para entrar no usuário para garantir seu consentimento para a permissão de usar o aplicativo Adobe Sign. |  |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.



#### <a name="add-in-data-access"></a>Acesso a dados do complemento

Listar as permissões necessárias para acessar os dados da sua organização, a justificativa e a finalidade dessa permissão (para que o aplicativo usa essas informações?) e se o aplicativo armazena qualquer uma dessas informações em seus bancos de dados.

>| **Permissão**  | **Descrição** |
>|:----------------|:----------------|
>| Caixa de correio ReadWrite | Esse complemento pode ler ou modificar o conteúdo de qualquer item em sua caixa de correio e criar novos itens. Ele pode acessar informações pessoais , como o corpo, assunto, remetente, destinatários ou anexos, em qualquer mensagem ou item de calendário. Ele pode enviar esses dados para um serviço de terceiros. |
>| Enviar Dados | Pode enviar dados pela Internet |

#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum. Não registramos nenhum EUII ou OII em telemetria ou logs. O processo é nossas próprias análises de segurança que validam que não estamos fazendo isso.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Não temos nenhuma interação do administrador do cliente em nosso sistema para Microsoft Teams aplicativo.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

