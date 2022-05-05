---
title: Visão geral do Wrike para Office documentos
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o Wrike para documentos do Office, suas políticas de tratamento de dados, suas informações do catálogo de aplicativos do Microsoft Cloud App Security e informações de segurança/conformidade no registro STAR da CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c4407cdf68b92369e45c798ef76e051980e6c23a
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225615"
---
# <a name="wrike-for-office-documents-overview"></a>Visão geral do Wrike para Office documentos

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 23 de março de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Wrike Inc. à Microsoft:

| **Information** | **Resposta** |
|:----------------|:-------------|
| Nome do aplicativo | Wrike para Office Documentos |
| ID | WA104379841 |
| Office 365 clientes com suporte | Excel 2016 ou posterior no Windows, Word 2013 ou posterior no Windows, PowerPoint 2013 ou posterior no Windows, Excel 2016 ou posterior no Mac, Excel na Web, Word 2016 ou posterior no Mac, Word na Web, PowerPoint 2016 ou posterior no Mac, PowerPoint na Web |
| Nome da empresa parceira | Wrike Inc. |
| URL do site do parceiro | [https://www.wrike.com/](https://www.wrike.com/) |
| URL da Política de Privacidade | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| URL dos Termos de Uso | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com os dados

Essas informações foram fornecidas pela Wrike Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Liste [as permissões Graph Microsoft que](/graph/permissions-reference) este aplicativo requer.

>Este aplicativo não usa o Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e suplementos criados Microsoft 365 podem usar APIs adicionais da Microsoft diferentes do Microsoft Graph para coletar ou processar informações de identificação organizacional (OII). Liste todas as APIs da Microsoft diferentes Graph este aplicativo usa.

>| **API** |  **O OII foi coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript para Office | Sim | O suplemento usa a API de Office.js para integração com o Office aplicativo. |  | Nenhum dado organizacional é armazenado nos bancos de dados do Wrike. |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII serviços Microsoft não serviços Microsoft são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O Wrike tem as integrações com os seguintes fornecedores que têm acesso a alguns dados: Marketo são serviços de captura de clientes potenciais por email– somente nomes e emails são fornecidos a eles. O outreach é o compromisso de vendas baseado em nuvem– somente nomes e emails são fornecidos a eles. Sistema Salesforce CRM – tem informações de contato e informações de cobrança (sem dados confidenciais) dos clientes. Zuora - clientes de cobrança e faturamento. Há um DPA em vigor para todos os fornecedores. |  | Usamos o JS Office API, no entanto, não coletamos/processam/armazenam informações organizacionais. |



#### <a name="telemetry-data"></a>Dados de telemetria

As informações de identificação organizacional (OII) ou EUII (informações de identificação do usuário final) aparecem na telemetria ou nos logs desse aplicativo? Em caso afirmativamente, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política do usuário final etc.

>O Wrike tem uma arquitetura multilocatário que separa logicamente os clientes&#8217; dados por meio do controle de acesso com base nos metadados do cliente. Esses metadados estão associados ao locatário específico e seus direitos de acesso de acordo com as regras de acesso baseadas em função dentro da conta específica do Wrike. Os dados são logicamente isolados e separados, e o acesso aos dados só está disponível por meio do aplicativo para garantir a segurança e a privacidade. A segurança no nível do aplicativo impede que os locatários acessem ou modifiquem dados de aplicativo pertencentes a outro locatário. O aplicativo do Wrike tem autenticação extensiva, controle de acesso baseado em função, autorização e mecanismos de controle e compartilhamento de dados ( https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) consulte e que permitem o acesso a dados somente para usuários autorizados. Além disso, a criptografia em repouso é aplicada aos arquivos de usuário carregados nos servidores Wrike no armazenamento de arquivos por meio do aplicativo Web e da API; os arquivos são criptografados automaticamente usando a criptografia AES de 256 bits. Além disso, todos os servidores são criptografados em repouso usando a criptografia do sistema de arquivos e, além disso, o Wrike oferece o suplemento Wrike Lock para chave de criptografia gerenciada por um cliente, consulte https://www.wrike.com/add-on-wrike-lock/ e https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock. Como camada adicional de segurança de dados, o Wrike oferece a funcionalidade auditoria e relatório que permite que os administradores realizem revisões de segurança completas e, ao mesmo tempo, possam aumentar a visibilidade do que está acontecendo em sua conta do Wrike, mais detalhes podem ser encontrados em https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports. Por fim, o Wrike fornece funcionalidade que permite o acompanhamento granular de funções de acesso para ajudar os clientes a auditar totalmente o compartilhamento de dados existentes em https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports.
O acesso aos dados do cliente pode ser considerado em dois casos:
- Acesso pela equipe de suporte do Wrike: no caso de solução de problemas ou verificação do problema, é necessário suporte para acessar sua conta; que o acesso só pode ser concedido por você. Isso é habilitado por um token de segurança gerado pelo sistema que você fornece fora de banda para nossa equipe de suporte, permitindo que o Suporte se aprofunde na solução do problema por um período limitado. Essa abordagem sistêmico garante confidencialidade adicional para seus dados armazenados no Wrike.
- Acesso pela equipe operacional do Wrike: a equipe operacional do Wrike é responsável pela manutenção e suporte ao ambiente de produção, incluindo monitoramento, aplicação de patch e atualização, entrega dos novos builds para produção, etc. Nesse caso, o acesso é estritamente proibido de aspectos processuais e técnicos e de controles de autorização fortes, incluindo VPN, 2FA e certificado pessoal, além disso, ele é monitorado em detalhes usando HIDS (Sistema de Detecção de Intrusão baseado em host) e revisado pela equipe de Segurança Operacional do Wrike. No caso do Amazon KMS (funcionalidade wrike Lock), os dados do cliente são armazenados criptografados no banco de dados wrike, portanto, os dados não estão diretamente ou indiretamente disponíveis pela equipe operacional do Wrike, pois os dados podem ser descriptografados usando o acesso ao Amazon KMS do cliente, que é gerenciado e controlado apenas pelo cliente.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de todos os dados de OII (informações de identificação organizacional) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

