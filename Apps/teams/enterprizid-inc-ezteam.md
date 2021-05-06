---
title: Informações do aplicativo para ezTeam por EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o ezTeam, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: cd6d7c3880cbf25db68a16c3780f11f2af1b1158
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250699"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de fevereiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo EnterprizID Inc para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ezTeam |
| ID | WA200002546 |
| Recursos | Bot, Guia |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | EnterprizID Inc |
| URL do site do parceiro | [https://enterprizid.com](https://enterprizid.com) |
| URL da página Teams de informações do aplicativo | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL da Política de Privacidade | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL dos Termos de Uso | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela EnterprizID Inc sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | delegado | Lista de aplicativos disponíveis no Teams para que possamos exibi-la no Teams de criação de solicitação | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | delegado | Permite que o aplicativo leia aplicativos e entidades de serviço em nome do usuário conectado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | delegado | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | delegado | Permite ao aplicativo ler dados no diretório da sua organização, como usuários, grupos e aplicativos. | Teams Informações sobre propriedade e associação  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | aplicação | Permite ao aplicativo ler dados no diretório da sua organização, como usuários, grupos e aplicativos, sem um usuário conectado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | delegado | Permite que o aplicativo leia e escreva dados no diretório da sua organização, como usuários e grupos | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | aplicação | Permite ao aplicativo ler e registrar dados no diretório de sua organização, como usuários e grupos, sem um usuário conectado. Não permite a exclusão de usuários ou grupos. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | aplicação | Permite ao aplicativo ler todos os arquivos em todos os conjuntos de sites sem um usuário conectado. | Quantidade de dados sob a governança do usuário final em GB | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | aplicação | Permite que o aplicativo crie grupos sem um usuário in-loca. | Novos detalhes das propriedades do grupo. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | delegado | Permite ao aplicativo listar grupos, e ler suas propriedades e todas as associações do grupo em nome do usuário conectado. Usado para determinar Minhas Teams  | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | aplicação | Permite que o aplicativo leia propriedades e associações de grupo e leia o calendário e as conversas de todos os grupos, sem um usuário associado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | delegado | Permite ao aplicativo criar grupos e ler todas as propriedades e associações do grupo em nome do usuário conectado.  | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | aplicação | Permite que o aplicativo crie grupos, leia todas as propriedades e associações do grupo, atualize propriedades e associações de grupo e exclua grupos. Também permite que o aplicativo leia e escreva calendários e conversas de grupo.  | Última atividade da Equipe. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | aplicação | Permite que o aplicativo leia grupos e as propriedades básicas do grupo para todos os grupos sem um usuário conectado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | aplicação | Permite que o aplicativo liste grupos, leia propriedades básicas, leia e atualize a associação dos grupos aos quais esse aplicativo tem acesso sem um usuário conectado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | aplicação | Permite que o aplicativo leia a lista pontuada de qualquer usuário de pessoas relevantes, sem um usuário com assinatura. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | delegado | Permite que um aplicativo leia todos os relatórios de uso de serviço em nome do usuário conectado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | aplicação | Permite que um aplicativo leia todos os relatórios de uso de serviço sem um usuário conectado. | Última atividade do usuário por grupo | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | aplicação | Permite ao aplicativo criar, ler, atualizar e excluir documentos e listar itens em todos os conjuntos de sites sem um usuário conectado. | Top 10 sites por tamanho para cada usuário | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | delegado | Permite aos usuários entrar no aplicativo e permite ao aplicativo ler o perfil de usuários conectados. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | aplicação | Permite que o aplicativo leia perfis de usuário sem um usuário assinado. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | delegado | Permite que o aplicativo veja e atualize os dados aos que você deu acesso a ele, mesmo quando os usuários não estão usando o aplicativo no momento.  | Notificações de bot | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | delegado | Permite aos usuários entrar no aplicativo com contas corporativas ou de estudante e permite ao aplicativo ver informações básicas do perfil do usuário. | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| perfil | delegado | Permite que o aplicativo veja o perfil básico dos usuários (nome, imagem, nome do usuário) | N/D | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Notificações de mensagens, aprovação e atestado de boas-vindas | Armazenamos o nome de exibição das identidades  | Nossa ferramenta permite que os usuários finais criem solicitação para itens de serviço diferentes e armazenamos o nome de exibição do solicitante. Uma solicitação seguiria um fluxo de trabalho de aprovação e precisamos do nome de exibição do aprovador para mostrar os detalhes da solicitação. Além disso, nos membros de um processo de certificação de equipe listamos o nome de exibição dos membros. |



#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>EndUser e Nome Completo da Organização. As políticas de retenção e remoção podem ser encontradas https://enterprizid.com/privacy-policy na seção Retenção de Seus Dados &quot; &quot; Pessoais

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Habilitamos o Gerenciamento de Acesso Privilegiado (PMA) no Azure e as identidades com privilégio de se conectar aos recursos usam o 2FA para aumentar a segurança. Usamos o Azure como nosso provedor de parceiros de nuvem e estamos sujeitos à privacidade e aos termos de uso do Azure

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela EnterprizID Inc sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
