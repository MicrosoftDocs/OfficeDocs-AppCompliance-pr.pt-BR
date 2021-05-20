---
title: Informações do aplicativo para o add-in StarLeaf para Outlook por StarLeaf
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o add-in StarLeaf para Outlook, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552472"
---
# <a name="starleaf-add-in-for-outlook"></a>Add-in StarLeaf for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo StarLeaf à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Add-in StarLeaf for Outlook |
| ID | WA104381343 |
| Office 365 clientes com suporte | Outlook 2013 ou posterior no Windows, Outlook 2016 ou posterior no Mac, Outlook na Web |
| Nome da empresa de parceiro | StarLeaf |
| URL do site do parceiro | [https://www.starleaf.com/](https://www.starleaf.com/) |
| URL da Política de Privacidade | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| URL dos Termos de Uso | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

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

