---
title: Informações do aplicativo para MindManager pelo Corel
ms.author: elmalova
author: elenamalova
ms.date: 05/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para MindManager, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d9ed1eab16b73a84dcd3ddc41cc0b716865b9a29
ms.sourcegitcommit: dafa6701f28c66f003efaf2e3a70d61dc3240955
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/06/2021
ms.locfileid: "52790015"
---
# <a name="mindmanager"></a>MindManager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de maio de 2021</p>

* <a href="https://teams.microsoft.com/l/app/cebe4a59-b076-47f3-a7bf-79148daf82f7" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002261" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Corel para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | MindManager |
| ID | WA200002261 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Corel |
| URL do site do parceiro | [www.mindmanager.com](www.mindmanager.com) |
| URL da Política de Privacidade | [https://www.corel.com/en/corel-privacy-policy/](https://www.corel.com/en/corel-privacy-policy/) |
| URL dos Termos de Uso | [https://www.mindjet.com/go/mmcloudterms](https://www.mindjet.com/go/mmcloudterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Corel sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ChannelMessage.Send | delegado | Informações sobre as alterações feitas em um arquivo MindManager que podem ser postadas como uma mensagem | metadados de arquivo, conteúdo de arquivo - para navegador de arquivo, o usuário pode navegar por seus arquivos para abrir um arquivo MindManager (.mmap). | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| Chat.Send | delegado | Informações sobre as alterações feitas em um arquivo MindManager que podem ser postadas como uma mensagem | metadados de arquivo, conteúdo de arquivo - para navegador de arquivo, o usuário pode navegar por seus arquivos para abrir um arquivo MindManager (.mmap). | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| Files.ReadWrite | delegado | listagem de sites, listagem de pastas, metadados de arquivo, conteúdo de arquivo - para o navegador de arquivos, o usuário pode navegar por seus arquivos para abrir um arquivo MindManager (.mmap). | - dados de perfil: para identificar o usuário e mostrar seu perfil - conteúdo do arquivo: durante a sessão de co-edição (edição colaborativa em tempo real em arquivos .mmap mindManager) | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| Sites.ReadWrite.All | delegado | listagem de sites, listagem de pastas, metadados de arquivo, conteúdo de arquivo - para o navegador de arquivos, o usuário pode navegar por seus arquivos para abrir um arquivo MindManager (.mmap). | conteúdo do arquivo: durante a sessão de co-edição (edição colaborativa em tempo real em arquivos .mmap mindManager) | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| User.Read | delegado | dados de perfil: para identificar o usuário e mostrar seu perfil | dados de perfil: para identificar o usuário e mostrar seu perfil | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| offline_access | delegado | Isso nos permite salvar um arquivo de volta ao local original em nome do usuário mais tarde, se necessário. | conteúdo do arquivo: durante a sessão de co-edição (edição colaborativa em tempo real em arquivos .mmap mindManager) | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Amazon Web Services | Nome da organização, Domínio da Organização | A organização precisa de uma configuração de conta em nossa infraestrutura de aplicativos para usar o aplicativo dentro Teams |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Abordado aqui: https://www.mindjet.com/go/mmcloudterms

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo Corel sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Não |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
