---
title: Informações do aplicativo para o complemento starleaf para Outlook por StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o complemento do StarLeaf para Outlook, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552472"
---
# <a name="starleaf-add-in-for-outlook"></a>Complemento starleaf para Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo StarLeaf à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Complemento starleaf para Outlook |
| ID | WA104381343 |
| Office 365 clientes suportados | Outlook 2013 ou mais tarde em Windows, Outlook 2016 ou mais tarde no Mac, Outlook na web |
| Nome da empresa parceira | StarLeaf |
| URL do site de parceiros | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL da Política de Privacidade | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL de Termos de Uso | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela StarLeaf sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | aplicação | armazenamos o iCalUId de reuniões, hora/data da reunião, endereços de e-mail do participante e uma propriedade estendida de valor único que lemos e escrevemos na reunião usando a interface de propriedades personalizadas Office.js. O iCalUId é usado para correlacionar a reunião em um calendário de perspectiva de&#8217;de usuários com a reunião de vídeo em nosso serviço. A hora/data e os participantes são usados para fornecer uma reunião de vídeo no momento certo para as pessoas certas em nosso serviço. O SVEP está acostumado com nosso addin O365 para fornecer uma interface para os usuários definirem detalhes sobre a reunião de vídeo em nosso serviço, como gravação. | costumava assinar notificações webhook para rastrear as alterações dos usuários em seus calendários e atualizar nosso serviço para mantê-lo consistente. Ele também é usado para criar eventos em seu calendário quando um usuário interage com nosso aplicativo Teams e agenda uma reunião em nosso serviço. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | aplicação | nós armazenamos o token de atualização oauth para ser capaz de fazer login. Armazenamos o perfil dos usuários para poder comparar com futuras tentativas da OAuth desse usuário e garantir que não&#8217;armazenar seus dados duas vezes.  | permitir que os usuários entrem no aplicativo e permite que nosso aplicativo obtenha ao usuário&#8217;endereço de e-mail para correlacionar seu login com uma conta em nosso serviço.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Se surgirem problemas de suporte técnico, os dados organizacionais poderão ser transferidos para o SalesForce para gerenciamento de casos. Se o usuário fizer uso do recurso de discagem PSTN, a chamada fluirá através de Twilio, Plivo ou Voxbone |  | Não disponível |



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim. Os registros incluem nomes de usuário, endereços IP, registros de detalhes de chamadas, informações sobre qualidade de conexão (perda de pacote, bitrate), tipo de dispositivo, progresso de chamada. As informações estão disponíveis para a equipe de suporte técnico e desenvolvedores seniores para o diagnóstico de problemas de serviço. Os dados são anonimizados após 90 dias. Os controles para proteger esses dados são auditados sob nossa certificação ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados são armazenados no StarLeaf&#8217;servidores de log próprios no data center no qual o usuário&#8217;conta está localizado e em backup até um ou mais data centers dentro da mesma jurisdição. O acesso aos dados é por conta de usuário individual usando senhas por usuário que são verificadas com força. As contas de usuário de serviços da StarLeaf&#8217;são auditadas automaticamente contra os sistemas de RH e os grupos corporativos do Active Directory para alertar a equipe de Segurança e Conformidade se anomalias forem encontradas.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

