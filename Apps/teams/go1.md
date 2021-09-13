---
title: Informações do aplicativo para Go1 por Go1
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Go1, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d6fa3c9d0ecf710724379da869fba4b0cec23f6a
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276295"
---
# <a name="go1"></a>Go1

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de junho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/c859de61-8a6b-42e6-ba88-f639df33bc72" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001484" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Go1 para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Go1 |
| ID | WA200001484 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Go1 |
| URL do site do parceiro | [https://www.go1.com/user/login](https://www.go1.com/user/login) |
| URL da Política de Privacidade | [https://www.go1.com/en-au/terms/privacy-policy](https://www.go1.com/en-au/terms/privacy-policy) |
| URL dos Termos de Uso | [https://www.go1.com/en-au/terms/user-terms](https://www.go1.com/en-au/terms/user-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Go1 sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | aplicação | app não armazena dados de arquivos | permite que os usuários carreguem e compartilhem arquivos do onedrive | [c859de61-8a6b-42e6-ba88-f639df33bc72](https://docs.microsoft.com/microsoft-365-app-certification/azure/c859de61-8a6b-42e6-ba88-f639df33bc72) |
>| Group.ReadWrite.All | aplicação | Teams nome do canal e id exclusiva armazenada para dar suporte ao ambiente de aprendizagem de gerenciamento de aplicativos | permite que o aplicativo configure dinamicamente Teams canais para dar suporte ao aprendizado estruturado Teams ambiente | [c859de61-8a6b-42e6-ba88-f639df33bc72](https://docs.microsoft.com/microsoft-365-app-certification/azure/c859de61-8a6b-42e6-ba88-f639df33bc72) |
>| User.Read.All | aplicação | nome dos usuários, email e UPN armazenados para fornecer experiência direta do aluno pessoal | permite usos para assinar e dar suporte ao compartilhamento de recursos de aprendizagem entre membros da equipe | [c859de61-8a6b-42e6-ba88-f639df33bc72](https://docs.microsoft.com/microsoft-365-app-certification/azure/c859de61-8a6b-42e6-ba88-f639df33bc72) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Os usuários de primeiro e último nome podem ser compartilhados com os provedores de conteúdo do GO1 ao jogar conteúdo do curso. Isso é compartilhado apenas quando o provedor de conteúdo exige isso para provedor de uma experiência de aprendizado personalizada. |  | N/A |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O GO1 minimiza o armazenamento de qualquer informação de identificação pessoal ou organizacional. Os logs de aplicativos de detalhes que armazenam esses dados são excluídos em até 90 dias após a criação.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>O 2FA é necessário para todos os sistemas de equipe. Acesso ao sistema GO1 gerenciado por função. Somente as funções que exigem acesso para executar seus trabalhos têm acesso aos sistemas de produção. As políticas internas exigem que os dados sempre são criptografados em trânsito e em repouso.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

