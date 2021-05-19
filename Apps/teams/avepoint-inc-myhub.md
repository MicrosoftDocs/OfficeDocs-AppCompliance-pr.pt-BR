---
title: Informações do aplicativo para MyHub pela AvePoint, inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para o MyHub, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ccf5367ea692731bafcdc03d04ab4dad2e76c976
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553382"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 21 de dezembro de 2020</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela AvePoint, inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | MyHub |
| ID | WA200000726 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | AvePoint, inc. |
| URL do site de parceiros | [https://www.avepoint.com](https://www.avepoint.com) |
| URL da Política de Privacidade | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| URL de Termos de Uso | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela AvePoint, inc. sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | ambos | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Ler dados do diretório | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | ambos | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Ler e gravar todos os grupos | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Mail.Send | Delegada | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Enviar email como um usuário | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports.Read.All | aplicação | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Ler todos os relatórios de uso | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.FullControl.All | aplicação | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Ter controle total de todos os conjuntos de sites | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | aplicação | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Ler itens em todos os conjuntos de sites  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | Delegada | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Editar ou excluir itens em todas as coleções do site | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | ambos | os dados de configuração do aplicativo são armazenados do ponto de vista do tratamento de dados | Leia todos os usuários&#8217; perfis completos | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Sim, o e-mail do usuário e o id do inquilino aparecerão nos registros. Os registros são armazenados em local seguro e apenas o pessoal autorizado pode acessar durante a solução de problemas. Os registros serão arquivados após 60 dias para fins de auditoria de segurança e serão excluídos após um ano.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do Aplicativo são armazenados em Banco de Dados SQL do Azure e Armazenamento do Azure. A SQL do Azure e a criptografia Armazenamento do Azure estão habilitadas.
Apenas administradores autorizados podem acessar os dados. É necessário que os administradores façaem login. As operações são auditadas. A lista branca ip também é usada para restringir o acesso aos dados.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

