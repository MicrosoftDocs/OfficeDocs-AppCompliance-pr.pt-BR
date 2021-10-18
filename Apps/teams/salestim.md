---
title: Informações de aplicativo para SalesTim por SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/09/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Todas as informações de segurança e conformidade disponíveis para SalesTim, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: db0568c2669525deae86e69292698f6a85ffb157
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60440761"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Última atualização pelo desenvolvedor em: 9 de outubro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SalesTim à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SalesTim |
| ID | WA200001393 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | SalesTim |
| URL do site do parceiro | [https://www.salestim.com](https://www.salestim.com) |
| URL da página Teams de informações do aplicativo | [https://www.salestim.com](https://www.salestim.com) |
| URL da Política de Privacidade | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL dos Termos de Uso | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo SalesTim sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.ReadWrite.All | delegado | ID dos usuários convidados para um canal por nossa política de associação | ID dos usuários convidados para um canal por nossa política de associação são armazenados em nossas trilhas de auditoria | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | delegado | ID do usuário. Permite que um usuário selecione outros usuários em vários locais no aplicativo, como selecionar aprovadores em um fluxo de trabalho. | ID do usuário. Permite que um usuário selecione outros usuários em vários locais no aplicativo, como selecionar aprovadores em um fluxo de trabalho. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | ambos | Não&#8217;apenas grupos/IDs de equipe,&#8217;não estamos armazenar conteúdo de grupos/equipes. Permite que o aplicativo crie grupos, leia todas as propriedades e associações de grupo em nome do usuário associado. Além disso, permite aos proprietários do grupo gerenciar seus grupos, e permite aos membros do grupo atualizar o conteúdo do grupo. | Não&#8217;apenas grupos/IDs de equipe,&#8217;não estamos armazenar conteúdo de grupos/equipes. Permite que o aplicativo crie grupos, leia todas as propriedades e associações de grupo em nome do usuário associado. Além disso, permite aos proprietários do grupo gerenciar seus grupos, e permite aos membros do grupo atualizar o conteúdo do grupo. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | delegado | IDs de usuário. Não&#8217;os metadados dessa ação, como a data de notificação, os destinatários, a ID da solicitação. | IDs de usuário. Não&#8217;os metadados dessa ação, como a data de notificação, os destinatários, a ID da solicitação. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | ambos | ID do usuário e dados de perfil. Permite que um usuário selecione outros usuários em vários locais no aplicativo, como selecionar aprovadores em um fluxo de trabalho. | ID do usuário. Permite que um usuário selecione outros usuários em vários locais no aplicativo, como selecionar aprovadores em um fluxo de trabalho. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offline_access | delegado | Token de atualização. Permite que o aplicativo execute algumas operações e ações em segundo plano como usuário. | Token de atualização. Permite que o aplicativo execute algumas operações e ações em segundo plano como usuário. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Marketplace | Sim | ID do locatário | Usado para gerenciar assinaturas de nossos clientes | ID do locatário | Usado para gerenciar assinaturas de nossos clientes |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Estamos usando o Intercom como nosso principal aplicativo de suporte ao cliente.  | ID do locatário | Estamos usando a ID de locatário da organização para correlacionar as solicitações de suporte dos clientes com um ambiente Microsoft 365 específico. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Todos os dados coletados são descritos aqui: conforme descrito, os logs são temporariamente armazenados https://developers.salestim.com/platform/datamanagement.html#application-data por 15 dias e excluídos automaticamente.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Estamos aplicando uma política de retenção como parte de nossa Revisão mensal de Descarte de Registros &quot; de &quot; Clientes.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pelo SalesTim sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Autenticação multifafação. Permitindo que apenas dispositivos inscritos do Intune acessem serviços específicos. Restrição de locais de usuários e intervalos de IP |
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
