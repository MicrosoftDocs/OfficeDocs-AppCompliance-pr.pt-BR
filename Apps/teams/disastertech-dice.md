---
title: Informações do aplicativo para DisasterTech DICE by DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o DisasterTech DICE, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29d53402a9bbf635e83d6d262227a8363577e261
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552232"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela DisasterTech à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | DisasterTech |
| URL do site de parceiros | [https://dice.disastertech.com](https://dice.disastertech.com) |
| URL da Política de Privacidade | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL de Termos de Uso | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela DisasterTech sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Delegada | Endereço de e-mail do usuário armazenado para estabelecer direitos de acesso, bem como nome de usuário para identificar usuários pelo nome | Permite que o usuário faça login e dá acesso ao aplicativo à sua UPN para habilitar o login silencioso, bem como Teams login, também para estabelecer nomes de usuários e endereços de e-mail. | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| email | Delegada | Nenhum | Necessário para Teams Sign-On Único | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | Delegada | Nenhum | Necessário para Teams Sign-On Único | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | Delegada | Nenhum | Necessário para Teams Sign-On Único | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| perfil | Delegada | Nenhum | Necessário para Teams único sinal. | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos o nome de usuário, nome e sobrenome, em um banco de dados PostgreSQL hospedado pelo Azure para permitir que os usuários colaborem juntos no aplicativo. Os controles são que apenas os funcionários da Disaster Tech têm acesso direto ao banco de dados. Quando um usuário é removido do aplicativo, arquivamos as informações. Os usuários mantêm o direito de remover seus dados pessoais do sistema a qualquer momento. No entanto, a remoção dessas informações também proibiria o uso do aplicativo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados em um banco de dados PostgreSQL no Azure que é criptografado em repouso. Nenhum usuário tem acesso direto ao banco de dados ou à API back-end. Todas as chamadas de API são protegidas com um Token de Acesso ao Diretório Ativo.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

