---
title: Informações do aplicativo para HeyTaco! por HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o HeyTaco!, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553122"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de novembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela HeyTaco! para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | HeyTaco! |
| ID | WA200001346 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | HeyTaco! |
| URL do site de parceiros | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL da Política de Privacidade | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL de Termos de Uso | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Esta informação foi fornecida pela HeyTaco! sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados que o aplicativo coleta.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Delegada | usado para combinar usuário para transferências de dados do Slack para MS Teams | usado para combinar usuário para transferências de dados do Slack para o MS Team | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | Delegada | costumava assinar pessoa no HeyTaco! | costumava assinar pessoa no HeyTaco! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| perfil | Delegada | usado para capturar nome de usuário, imagem de perfil, deslocamento do fuso horário, identificação do inquilino e identificação da equipe | usado para capturar nome de usuário, avatar, deslocamento de fuso horário, identificação do inquilino e identificação da equipe | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Para dizer ao usuário que eles receberam um taco e de quem é. | Endereço de e-mail (para tacos de migração de uma plataforma para outra) Nome (para cumprimentar o usuário) Imagem do perfil (para exibição na tabela de classificação) Fuso horário (para mostrar corretamente tacos dados na página de atividade) ID do inquilino (Para agregar dados por inquilino) ID da equipe (Para agregar dados por equipe)  |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Euii e OII não estão conectados a nenhuma exploração madeireira. Apenas tipos de erro e tipos de ação.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>HeyTaco! bancos de dados e backups de dados estão hospedados no Amazon Web Services (AWS). 

As operações de data center da Amazon foram credenciadas sob ISO 27001 , SOC 1 e SOC 2/SSAE 16/ISAE 3402 (Anteriormente SAS 70 Tipo II), PCI Nível 1, FISMA Moderado e Sarbanes-Oxley (SOX).

Quando você envia informações através do nosso serviço, suas informações são protegidas e criptografadas tanto em repouso quanto em trânsito através de conexões seguras. Implementamos uma variedade de medidas de segurança para manter a segurança de suas informações pessoais.

Temos o Gerenciamento de Acesso Privilegiado em vigor para proteger os dados em nossos servidores.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

