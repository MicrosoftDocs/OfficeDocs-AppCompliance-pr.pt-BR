---
title: Informações do aplicativo para ezTeam pela EnterprizID Inc
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o ezTeam, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553172"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de fevereiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela EnterprizID Inc à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | ezTeam |
| ID | WA200002546 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | EnterprizID Inc |
| URL do site de parceiros | [https://enterprizid.com](https://enterprizid.com) |
| URL da página de informações do aplicativo Teams | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| URL da Política de Privacidade | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| URL de Termos de Uso | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela EnterprizID Inc sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | Delegada | Lista de aplicativos disponíveis em Teams para que possamos mostrá-lo em Teams processo de criação de solicitações | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | Delegada | Permite que o aplicativo leia aplicativos e entidades de serviço em nome do usuário conectado. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | Delegada | Permite ao aplicativo ter o mesmo acesso que o usuário conectado a informações no diretório. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | Delegada | Permite ao aplicativo ler dados no diretório da sua organização, como usuários, grupos e aplicativos. | Teams Informações sobre propriedade e associação  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | aplicação | Permite ao aplicativo ler dados no diretório da sua organização, como usuários, grupos e aplicativos, sem um usuário conectado. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | Delegada | Permite que o aplicativo leia e escreva dados no diretório da sua organização, como usuários e grupos | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | aplicação | Permite ao aplicativo ler e registrar dados no diretório de sua organização, como usuários e grupos, sem um usuário conectado. Não permite a exclusão de usuários ou grupos. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | aplicação | Permite ao aplicativo ler todos os arquivos em todos os conjuntos de sites sem um usuário conectado. | Quantidade de dados sob a governança do usuário final em GB | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | aplicação | Permite que o aplicativo crie grupos sem um usuário de assinatura. | Novos detalhes de propriedades do grupo. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | Delegada | Permite ao aplicativo listar grupos, e ler suas propriedades e todas as associações do grupo em nome do usuário conectado. Usado para determinar minha Teams  | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | aplicação | Permite que o aplicativo leia propriedades e associações do grupo e leia o calendário e as conversas para todos os grupos, sem um usuário de assinatura. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | Delegada | Permite ao aplicativo criar grupos e ler todas as propriedades e associações do grupo em nome do usuário conectado.  | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | aplicação | Permite que o aplicativo crie grupos, leia todas as propriedades e associações do grupo, atualize propriedades e associações do grupo e exclua grupos. Também permite que o aplicativo leia e escreva calendário de grupos e conversas.  | Última atividade da Equipe. | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | aplicação | Permite que o aplicativo leia grupos e as propriedades básicas do grupo para todos os grupos sem um usuário conectado. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | aplicação | Permite que o aplicativo liste grupos, leia propriedades básicas, leia e atualize a associação dos grupos aos quais esse aplicativo tem acesso sem um usuário conectado. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | aplicação | Permite que o aplicativo leia a lista de pessoas relevantes de qualquer usuário, sem um usuário de assinatura. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | Delegada | Permite que um aplicativo leia todos os relatórios de uso de serviço em nome do usuário conectado. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | aplicação | Permite que um aplicativo leia todos os relatórios de uso de serviço sem um usuário conectado. | Última atividade do usuário por grupo | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | aplicação | Permite ao aplicativo criar, ler, atualizar e excluir documentos e listar itens em todos os conjuntos de sites sem um usuário conectado. | Top 10 sites por tamanho para cada usuário | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | Delegada | Permite aos usuários entrar no aplicativo e permite ao aplicativo ler o perfil de usuários conectados. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | aplicação | Permite que o aplicativo leia perfis de usuários sem um usuário assinado. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | Delegada | Permite que o aplicativo veja e atualize os dados que você deu acesso, mesmo quando os usuários não estão usando o aplicativo no momento.  | Notificações de bot | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | Delegada | Permite aos usuários entrar no aplicativo com contas corporativas ou de estudante e permite ao aplicativo ver informações básicas do perfil do usuário. | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| perfil | Delegada | Permite que o aplicativo veja o perfil básico de seus usuários (nome, imagem, nome do usuário) | Não disponível | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Mensagem de boas-vindas, aprovação e notificações de processos de atestado | Nós armazenamos o nome de exibição das identidades  | Nossa ferramenta permite que os usuários finais criem solicitação para diferentes itens de serviço e armazenamos o nome de exibição do solicitante. Uma solicitação seguiria um fluxo de trabalho de aprovação e precisamos do nome de exibição do aprovador para mostrar nos detalhes da solicitação. Além disso, nos membros de um processo de certificação de equipe listamos o nome de exibição dos membros. |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>EndUser e Nome Completo da Organização. As políticas de retenção e remoção podem ser encontradas na https://enterprizid.com/privacy-policy &quot; seção Retenção de Dados Pessoais &quot;

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Nós habilitamos o Gerenciamento de Acesso Privilegiado (PMA) dentro do Azure e identidades com privilégio de se conectar aos recursos usa o 2FA para aumentar a segurança. Usamos o Azure como nosso provedor parceiro em nuvem e estamos sujeitos à privacidade e aos termos de uso do Azure

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela EnterprizID Inc sobre como este aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você integra-se com a Microsoft Identify Platform (Azure AD)?  | Sim |
| Você revisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação de integração plataforma de identidade da Microsoft?  | Sim |
| Seu aplicativo usa o MSAL (Microsoft Authentication Library) para autenticação? | Não |
| Seu aplicativo suporta políticas de acesso condicional? | Não |
| Seu aplicativo pede menos permissões privilegiadas para o seu cenário? | Sim |
| As permissões cadastradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará de forma dinâmica e incremental? | Sim |
| Seu aplicativo suporta multi-locação? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o identificador unificado de recursos (URI) cadastrado no seu aplicativo? | Sim |
| Para o seu aplicativo, o que você evita usar? | - Curinga redirecionar URIs,<br/>- OAuth2 Flow Implícita, a menos que seja necessário para um SPA<br/>- Fluxo de credencial de senha do proprietário de recursos (ROPC) |
| Seu aplicativo expõe alguma APIs web? | Sim |
| Seu modelo de permissão só permite que as chamadas tenham sucesso se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
