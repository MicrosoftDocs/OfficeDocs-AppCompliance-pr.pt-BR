---
title: Informações do aplicativo para DISASTERTech DICE pela DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para DisasterTech DICE, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d8eec2ad9c7047a33dae446943c3ab2d934cc78c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59277482"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela DisasterTech para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | DisasterTech |
| URL do site do parceiro | [https://www.disastertech.com](https://www.disastertech.com) |
| URL da Política de Privacidade | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL dos Termos de Uso | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela DisasterTech sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | delegado | Endereço de email do usuário armazenado para estabelecer direitos de acesso, bem como o nome de usuário para identificar usuários pelo nome | Permite que o usuário entre e dê acesso ao aplicativo para seu UPN para habilitar o logon silencioso, bem como Teams logon, também para estabelecer nomes de usuário e endereços de email. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| email | delegado | Nenhum | Obrigatório para Teams single Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| offline_access | delegado | Nenhum | Obrigatório para Teams single Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| openid | delegado | Nenhum | Obrigatório para Teams single Sign-On | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |
>| perfil | delegado | Nenhum | Obrigatório para Teams login único. | [36d23b76-c58b-4a34-a60f-dceac6962bad](https://docs.microsoft.com/microsoft-365-app-certification/azure/36d23b76-c58b-4a34-a60f-dceac6962bad) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos o nome de usuário, nome e sobrenome em um banco de dados PostgreSQL hospedado pelo Azure para permitir que os usuários colaborem juntos no aplicativo. Os controles são de que apenas os funcionários do Disaster Tech têm acesso direto ao banco de dados. Quando um usuário é removido do aplicativo, arquivaremos as informações. Os usuários mantêm o direito de remover seus dados pessoais do sistema a qualquer momento. No entanto, remover essas informações também proibiria o uso do aplicativo.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados em um banco de dados PostgreSQL no Azure que é criptografado em repouso. Nenhum usuário tem acesso direto ao banco de dados ou à API de back-end. Todas as chamadas de API são protegidas com um Token de Acesso do Active Directory.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

