---
title: Informações do aplicativo para vídeo prezi por Prezi
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
description: Todas as informações de segurança e conformidade disponíveis para o Prezi Video, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 99d94e196109404452241300b43eb3003c10fde6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/30/2021
ms.locfileid: "52092233"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 23 de junho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Prezi para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Prezi Video |
| ID | WA200001577 |
| Recursos | Bot, Guia, Extensão de Mensagem |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Prezi |
| URL do site do parceiro | [https://prezi.com](https://prezi.com) |
| URL da Política de Privacidade | [https://prezi.com/privacy-policy/201910_NL/](https://prezi.com/privacy-policy/201910_NL/) |
| URL dos Termos de Uso | [https://prezi.com/terms-of-use/201910_NL/](https://prezi.com/terms-of-use/201910_NL/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Prezi sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>Este aplicativo não usa o Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Para obter detalhes, visite https://prezi.com/privacy-policy/ |  | As APIs/SDK a seguir são usadas para a integração junto com o 1. Botbuilder-SDK (python): usando esse SDK, armazenamos a ID do objeto Azure Active Directory (referida pela API como aad_object_id). Precisamos dessa informação para mapear um usuário Microsoft Teams para qualquer conteúdo relacionado ao Vídeo Prezi criado prezi.com.  2. Botbuilder-js (javascript): nenhum Microsoft Teams dados específicos são coletados usando esse SDK. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| O bot não acessa as informações de lista mencionadas. | O bot não acessa as informações de lista mencionadas. |  |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum EUII ou OII aparece nos logs do aplicativo.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Armazenamos as seguintes informações em um banco de dados RDS:

1. Azure Active Directory ID do objeto (referida pela API como aad_object_id) é armazenada para buscar um Microsoft Teams usuário&#8217;vídeos. O aad_object_id é recuperado com segurança usando o sdk de botbuilder oficial do Microsoft&#8217;em nossos servidores.

2. Links de vídeo criados prezi.com. O conteúdo criado prezi.com é armazenado conforme a seção 14 na seguinte URL: https://prezi.com/privacy-policy/ 

Os direitos de acesso a sistemas externos de alto risco (como AWS) são gerenciados por meio de uma plataforma de gerenciamento de acesso e identidade unificada de terceiros (OneLogin).

A política de senha e a autenticação multifação são impostas para a equipe na plataforma de gerenciamento de acesso e identidade unificada. Caso a caso, a autenticação multifa factor não é necessária dos endereços IP do office.

Serviços e bancos de dados hospedados pela AWS, por padrão, não são acessíveis de qualquer lugar; regras de entrada explícitas devem ser adicionadas manualmente.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

