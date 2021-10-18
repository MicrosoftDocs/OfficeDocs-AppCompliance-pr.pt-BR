---
title: Informações do aplicativo para Studi.ly pelo inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 06/18/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Studi.ly, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 478c078c5f74535ff8b0381aa4eac038fa29dab7
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430823"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo inLogic-Office Store para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Studi.ly |
| ID | WA200001668 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | inLogic-Office Store |
| URL do site do parceiro | [https://www.inlogic.dk](https://www.inlogic.dk) |
| URL da Política de Privacidade | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| URL dos Termos de Uso | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo inLogic-Office Store sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Gravar Diretório nos grupos para atribuições e materiais. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | aplicação | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Gravar Diretório nos grupos para atribuições e materiais. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | aplicação | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, pois se a recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Leia Classes de Educação, Escola, Membros e Termos.Obter todas as classes e escolas de um locatário para sincronização no banco de dados de aplicativos. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Leia Classes de Educação, Escola, Membros e Termos.Obter todas as classes e escolas de um locatário para sincronização no banco de dados de aplicativos. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | aplicação | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Leia Classes de Educação, Escola, Membros e Termos.Obter todas as classes e escolas de um locatário para sincronização no banco de dados de aplicativos. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Essa permissão permitiu que o aplicativo recebe eventos de claender diferentes para grupos de locatário.,assunto,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | ambos | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Essa permissão permitiu que o aplicativo recebe eventos de claender diferentes para grupos de locatário.,assunto,start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | aplicação |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | ambos | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | ReadWrite Files from One Drive | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Lendo informações do usuário | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | delegado | Estamos armazenamento de classes, escolas e membros e informações de termos da api de educação em nossa api e precisamos dela, porque se nós o recebermos sempre da api gráfica que faz com que nosso aplicativo funcione com lentidão. Nós o sincronizamos em um evento baseado em tempo da api educacional para nosso banco de dados. | Lendo informações do usuário | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Esses dados não aparecem nos logs

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Ele é armazenado no banco de dados do Azure cosmos e qualquer criptografia e armazenamento que está disponível por padrão com o banco de dados do cosmos é aplicável a esse aplicativo.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

