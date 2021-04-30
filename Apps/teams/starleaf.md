---
title: Informações de aplicativo para StarLeaf por StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
description: Todas as informações de segurança e conformidade disponíveis para StarLeaf, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 99fa034d595c4f45dbea4d706278d1e71d258683
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092204"
---
# <a name="starleaf"></a>StarLeaf

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/220b3db0-e3be-40df-8148-f0e0c33a986a" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000185" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo StarLeaf à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | StarLeaf |
| ID | WA200000185 |
| Recursos | Bot, Extensão de Mensagem |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | StarLeaf |
| URL do site do parceiro | [https://www.starleaf.com](https://www.starleaf.com) |
| URL da Política de Privacidade | [https://support.starleaf.com/legal-information/starleaf-pri...](https://support.starleaf.com/legal-information/starleaf-privacy-notice/) |
| URL dos Termos de Uso | [https://support.starleaf.com/legal-information/starleaf-clo...](https://support.starleaf.com/legal-information/starleaf-cloud-services-customer-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo StarLeaf sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | aplicação | armazenamos o iCalUId de reuniões, hora/data da reunião, endereços de email do participante e uma propriedade De Valor Único-Estendido que lemos e escrevemos na reunião usando a interface de propriedades personalizadas Office.js. O iCalUId é usado para correlacionar a reunião em um calendário&#8217;do outlook do usuário com a reunião de vídeo em nosso serviço. A hora/data e os participantes são usados para fornecer uma reunião de vídeo no momento certo para as pessoas certas em nosso serviço. SVEP são usados com nosso complemento O365 para fornecer uma interface para os usuários definirem detalhes sobre a reunião de vídeo em nosso serviço, como gravação. | usado para assinar notificações de webhook para acompanhar as alterações do usuário em seus calendários e atualizar nosso serviço para mantê-lo consistente. Ele também é usado para criar eventos em seu calendário quando um usuário interage com nosso aplicativo Teams e agenda uma reunião em nosso serviço. | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | aplicação | armazenamos o token de atualização do oauth para poder fazer logon. Armazenamos a ID de perfil de usuários para poder comparar com futuras tentativas OAuth desse usuário e garantir que&#8217;armazenar seus detalhes duas vezes.  | permite que os usuários entre no aplicativo e permite que nosso aplicativo faça com que o usuário&#8217;endereço de email correlacionar seu logon com uma conta em nosso serviço.  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Se surgirem problemas de suporte técnico, os dados organizacionais poderão ser transferidos para SalesForce para gerenciamento de casos. Se o usuário fizer uso do recurso de discagem PSTN, a chamada fluirá através de Twilio, Plivo ou Voxbone |  | N/D |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| O bot acessa a lista da equipe para agendar uma reunião em nome do usuário/host que agenda a reunião por meio do bot. Isso permite que StarLeaf forneça uma experiência de junção perfeita com um botão para ingressar em reuniões. | Nome, sobrenome, endereço de email. Isso permite que o bot StarLeaf reserve uma reunião em nome do usuário/host que interagiu com o bot e convide os outros membros da equipe para a reunião. |  |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim. Os logs incluem nomes de usuário, endereços IP, registros de detalhes de chamada, informações sobre a qualidade da conexão (perda de pacotes, taxa de bits), tipo de dispositivo, andamento da chamada. As informações estão disponíveis para a equipe de suporte técnico e desenvolvedores sênior para diagnóstico de problemas de serviço. Os dados são anonimizados após 90 dias. Os controles para proteger esses dados são auditados em nossa certificação ISO/IEC 27001.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados são armazenados em servidores de log&#8217;StarLeaf no centro de dados no qual a conta do usuário&#8217;está localizada e são armazenados em até um ou mais centros de dados na mesma jurisdição. O acesso aos dados é feito por conta de usuário individual usando senhas por usuário que são verificadas com força. As contas&#8217;de usuário de serviço starLeaf são auditadas automaticamente em relação aos sistemas de RH e aos grupos corporativos do Active Directory para alertar a equipe de Segurança e Conformidade se as anomalias são encontradas.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

