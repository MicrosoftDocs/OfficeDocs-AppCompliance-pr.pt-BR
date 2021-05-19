---
title: Informações de inscrição para Wrike for Office Documents da Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações disponíveis de segurança e conformidade para a Wrike for Office Documents, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ce29d8d0e8923795e860ffb9013267a39889970e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553552"
---
# <a name="wrike-for-office-documents"></a>Wrike para documentos Office

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 23 de março de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Wrike Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Wrike para documentos Office |
| ID | WA104379841 |
| Office 365 clientes suportados | Excel 2016 ou posterior em Windows, Word 2013 ou posterior em Windows, PowerPoint 2013 ou mais tarde em Windows, Excel 2016 ou mais tarde em Mac, Excel na Web, Word 2016 ou mais tarde em Mac, Word na Web, PowerPoint 2016 ou mais tarde em Mac, PowerPoint na Web |
| Nome da empresa parceira | Wrike Inc. |
| URL do site de parceiros | [https://wrike.com/](https://wrike.com/) |
| URL da Política de Privacidade | [https://www.wrike.com/privacy](https://www.wrike.com/privacy) |
| URL de Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Wrike Inc. sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>Este aplicativo não usa o Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Aplicativos e complementos incorporados em Microsoft 365 podem usar APIs adicionais da Microsoft além da Microsoft Graph para coletar ou processar informações identificáveis organizacionais (OII). Liste quaisquer APIs da Microsoft além da Microsoft Graph que este aplicativo usa.

>| **API** |  **OII é coletado?** |  **O que o OII é coletado?** | **Justificativa para a coleta de OII?** | **OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript para Office | Sim | O complemento usa a API Office.js para se integrar ao aplicativo Office. |  | Nenhum dado organizacional é armazenado nos bancos de dados do Wrike. |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| A Wrike tem as integrações com os seguintes fornecedores que têm acesso a alguns dados: Marketo é serviços de captura de chumbo por e-mail - apenas nomes e e-mails são fornecidos a eles. A divulgação é um engajamento de vendas baseado em nuvem - apenas nomes e e-mails são fornecidos a eles. Salesforce CRM system - tem informações de contato e faturamento (sem dados confidenciais) de informações dos clientes. Zuora - faturamento e faturamento de clientes. Há um DPA no lugar para todos os fornecedores. |  | Usamos JS Office API, no entanto, não coletamos/processamos/armazenamos quaisquer informações organizacionais. |



#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Wrike tem uma arquitetura multi-inquilino que logicamente segrega clientes&#8217; dados através do controle de acesso com base em metadados de clientes. Esses metadados estão associados ao inquilino específico e seus direitos de acesso de acordo com as regras de acesso baseadas em papéis dentro da conta específica de Wrike. Os dados são logicamente isolados e segregados, e o acesso aos dados só está disponível através do aplicativo para garantir segurança e privacidade. A segurança no nível do aplicativo impede os inquilinos de acessar ou modificar dados de aplicativos de propriedade de outro inquilino. O aplicativo de Wrike possui ampla autenticação, controle de acesso baseado em papéis, autorização e mecanismos de compartilhamento e controle de dados (ver https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles e permitir o acesso de dados https://help.wrike.com/hc/en-us/articles/209602969) apenas para usuários autorizados. Além disso, a criptografia em repouso é aplicada para arquivos de usuário carregados para servidores Wrike em armazenamento de arquivos através de aplicativo web e API; os arquivos são criptografados automaticamente usando criptografia AES de 256 bits. Além disso, todos os servidores são criptografados em repouso usando criptografia do sistema de arquivos e, além disso, o Wrike oferece complemento do Wrike Lock para chave de criptografia gerenciada por um cliente, veja https://www.wrike.com/add-on-wrike-lock/ e https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Como camada adicional de segurança de dados, wrike oferece funcionalidade de Auditoria e Relatórios que permite aos administradores realizar revisões completas de segurança, ao mesmo tempo em que é capaz de aumentar a visibilidade sobre o que está acontecendo em sua conta Wrike, mais detalhes podem ser encontrados em https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Finalmente, a Wrike fornece funcionalidade que permite o rastreamento granular de funções de acesso para ajudar os clientes a auditar totalmente o compartilhamento de dados existente ver detalhes em https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
O acesso aos dados do cliente pode ser considerado em dois casos:
- Acesso pela equipe de suporte da Wrike: em caso de solução de problemas ou verificação do problema requer suporte para acesso à sua conta; que o acesso só pode ser concedido por você. Isso é ativado por um token de segurança gerado pelo sistema que você fornece fora da banda para nossa equipe de suporte, permitindo que o Suporte se aprofunde na resolução do seu problema por um período limitado de tempo. Essa abordagem sistêmica garante confidencialidade adicional para seus dados armazenados em Wrike.
- Acesso da equipe operacional wrike: A equipe da Wrike Operacional é responsável pelo ambiente de manutenção e suporte de produção, incluindo monitoramento, patches e atualização, entrega das novas construções à produção, etc. O acesso neste caso é estritamente proibido de aspectos processuais e técnicos, e fortes controles de autorização, incluindo VPN, 2FA e certificado pessoal não limitados, estão em vigor, além disso, é monitorado em detalhes usando o HIDS (Host-based Intrusion Detection System) e revisado pela equipe de Segurança Operacional wrike. No caso da Amazon KMS (funcionalidade Wrike Lock), os dados do cliente são armazenados criptografados no banco de dados wrike, de modo que os dados não estão disponíveis direta ou indiretamente pela equipe da Wrike Operational, pois os dados podem ser descriptografados usando o acesso à Amazon KMS, que é gerenciada e controlada apenas pelo cliente.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

