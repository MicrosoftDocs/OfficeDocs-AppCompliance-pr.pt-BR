---
title: Informações do aplicativo para ideias amplas por ideias amplas
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Ideias Amplas, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1e73a7aebbaaffa12572717f7a4a9968fd5667f7
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276460"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de junho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Ideias Amplas para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Wide Ideas |
| ID | WA200000819 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Wide Ideas |
| URL do site do parceiro | [https://getwideideas.com](https://getwideideas.com) |
| URL da Política de Privacidade | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| URL dos Termos de Uso | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Ideias Amplas sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | aplicação | Salvamos a ID do Grupo e quais usuários pertencem a quais grupos | Permite que o aplicativo leia dados no diretório da organização dos clientes, como usuários e grupos.  | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| Group.ReadWrite.All | aplicação | Salvamos a ID do canal que está associada ao grupo. | Permite que o usuário crie equipes, canais e guias dentro Microsoft Teams do Portal do Cliente. Isso também permite que o usuário sincronize as equipes existentes Microsoft Teams no Portal do Cliente. | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |
>| User.Read | delegado | Salvamos email de &amp; nome | Permite que os usuários entre e dê acesso ao Microsoft Graph em seu nome | [77baef51-6387-4aff-9b3f-23e4654c30cd](https://docs.microsoft.com/microsoft-365-app-certification/azure/77baef51-6387-4aff-9b3f-23e4654c30cd) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Email de email que é usado para notificações por email. |  | N/A |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Para criar usuários em nosso back-end e dar permissões para acessar conteúdo vinculado à equipe. | Armazenamos: Nome - Para mostrar o nome do usuário, endereço de email - Para identificar o usuário |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos apenas o número IP em nossos logs. 

A organização pode enviar uma solicitação para nós como um fornecedor se quiser que quaisquer dados sejam excluídos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Armazenamento de dados: todos os dados do cliente são armazenados Microsoft Azure serviços. Os usuários precisam ter 2 fatores autenticados por meio do Azure AD. O acesso baseado em função (RBAC) está no local. Todo o acesso ao Microsoft Azure é feito estritamente por meio de conexões criptografadas. Todos os dados são criptografados em repouso. Todos os serviços são protegidos pela prática mais prática do Centro de Segurança do Azure. 

Também temos uma Política de Acesso em funcionamento de acordo com o princípio do privilégio mínimo. 


#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

