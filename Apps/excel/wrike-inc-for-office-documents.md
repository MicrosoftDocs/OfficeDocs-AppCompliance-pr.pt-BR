---
title: Informações de aplicativo para Wrike para Office documentos pela Wrike Inc.
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para o Wrike para documentos Office, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c1304a161377b80c0248229aa1ef92f4f15e19d9
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251400"
---
# <a name="wrike-for-office-documents"></a>Wrike for Office Documents

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 23 de março de 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Wrike Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Wrike for Office Documents |
| ID | WA104379841 |
| Office 365 clientes com suporte | Excel 2016 ou posterior no Windows, Word 2013 ou posterior no Windows, PowerPoint 2013 ou posterior no Windows, Excel 2016 ou posterior no Mac, Excel na Web, Word 2016 ou posterior no Mac, Word na Web, PowerPoint 2016 ou posterior no Mac, PowerPoint na Web |
| Nome da empresa de parceiro | Wrike Inc. |
| URL do site do parceiro | [https://wrike.com/](https://wrike.com/) |
| URL da Política de Privacidade | [https://www.wrike.com/privacy](https://www.wrike.com/privacy) |
| URL dos Termos de Uso | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Wrike Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript para Office | Sim | O complemento usa a API Office.js para se integrar ao Office aplicativo. |  | Nenhum dado organizacional é armazenado nos bancos de dados do Wrike. |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| O Wrike tem as integrações com os seguintes fornecedores que têm acesso a alguns dados: Marketo é serviços de captura de líder de email - apenas nomes e emails são fornecidos a eles. O outreach é o envolvimento de vendas baseado em nuvem - apenas nomes e emails são fornecidos a eles. Sistema salesforce CRM - tem informações de contato e cobrança (sem dados confidenciais) de clientes. Zuora - cobrança e faturamento de clientes. Há uma DPA no local para todos os fornecedores. |  | Usamos a API de Office JS, no entanto, não coletamos/processam/armazenamos informações organizacionais. |



#### <a name="add-in-data-access"></a>Acesso a dados do complemento

Listar as permissões necessárias para acessar os dados da sua organização, a justificativa e a finalidade dessa permissão (para que o aplicativo usa essas informações?) e se o aplicativo armazena qualquer uma dessas informações em seus bancos de dados.

>| **Permissão**  | **Descrição** |
>|:----------------|:----------------|
>| Documento ReadWrite | Pode ler e fazer alterações no documento |
>| Enviar Dados | Pode enviar dados pela Internet |

#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Não

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O Wrike tem uma arquitetura de vários locatários que segrega logicamente os clientes&#8217; dados por meio do controle de acesso com base nos metadados do cliente. Os metadados estão associados ao locatário específico e seus direitos de acesso de acordo com as regras de acesso baseadas em função na conta wrike específica. Os dados são logicamente isolados e segregados, e o acesso aos dados só está disponível por meio do aplicativo para garantir segurança e privacidade. A segurança no nível do aplicativo impede que os locatários acessem ou modifiquem dados do aplicativo pertencentes a outro locatário. O aplicativo do Wrike tem autenticação extensiva, controle de acesso baseado em função, autorização e mecanismos de compartilhamento e controle de dados (consulte e que permitem o acesso de dados somente para usuários https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) autorizados. Além disso, a criptografia em repouso é aplicada aos arquivos de usuário carregados nos servidores Wrike no armazenamento de arquivos por meio de aplicativo Web e API; os arquivos são criptografados automaticamente usando a criptografia AES de 256 bits. Além disso, todos os servidores são criptografados em repouso usando criptografia do sistema de arquivos e, além disso, o Wrike oferece o complemento Wrike Lock para chave de criptografia gerenciada por um cliente, consulte https://www.wrike.com/add-on-wrike-lock/ e https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock . Como camada adicional de segurança de dados, o Wrike oferece a funcionalidade auditoria e relatório que permite que os administradores conduzam avaliações de segurança completas enquanto podem aumentar a visibilidade sobre o que está acontecendo em sua conta wrike, mais detalhes podem ser encontrados em https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports . Por fim, o Wrike fornece funcionalidade que permite o controle granular das funções de acesso para ajudar os clientes a auditar totalmente o compartilhamento de dados existentes, consulte detalhes em https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports .
O acesso aos dados do cliente pode ser considerado em dois casos:
- Access by Wrike Support team: in case of troubleshooting or verifying the issue requires Support to access to your account; que o acesso só pode ser concedido por você. Isso é habilitado por um token de segurança gerado pelo sistema que você fornece fora de banda para nossa equipe de Suporte, permitindo que o Suporte se aprofunde na solução do seu problema por um período limitado de tempo. Essa abordagem sistêmico garante confidencialidade adicional para seus dados armazenados no Wrike.
- Acesso pela equipe operacional wrike: a equipe operacional wrike é responsável pela manutenção e suporte ao ambiente de produção, incluindo monitoramento, correção e atualização, entrega das novas builds para produção, etc. O acesso neste caso é estritamente proibido de aspectos processuais e técnicos e controles de autorização fortes, incluindo VPN, 2FA e certificado pessoal, além disso, ele é monitorado em detalhes usando HIDS (Sistema de Detecção de Intrusão baseado em host) e revisado pela equipe de Segurança Operacional wrike. No caso do Amazon KMS (funcionalidade wrike Lock), os dados do cliente são armazenados criptografados no banco de dados Wrike, portanto, os dados não estão disponíveis direta ou indiretamente pela equipe operacional wrike, pois os dados podem ser descriptografados usando o acesso ao amazon KMS do cliente, que é gerenciado e controlado somente pelo cliente.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

