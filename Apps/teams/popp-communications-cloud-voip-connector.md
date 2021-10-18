---
title: Informações do aplicativo para o Conector voIP de nuvem DA PAPO pela COMUNICAÇÃO DO PAPO
ms.author: elmalova
author: elenamalova
ms.date: 10/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o CONECTOR VOIP da Nuvem DA PAPO, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: c13790c3baa08d584343e9d504251e3920204b22
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/18/2021
ms.locfileid: "60438720"
---
# <a name="popp-cloud-voip-connector"></a>Conector VoIP Nuvem POPP

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 20 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela COMUNICAÇÃO DA PAPO para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Conector VoIP Nuvem POPP |
| ID | WA200003306 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Comunicações POPP |
| URL do site do parceiro | [https://popp.com](https://popp.com) |
| URL da Política de Privacidade | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| URL dos Termos de Uso | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela COMUNICAÇÃO DA PAPO SOBRE como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | delegado | IDs de usuário e nomes de exibição de membros do canal atual. O aplicativo usa isso para apresentar ao usuário uma lista de membros do canal para chamar. | Metawitch não armazena esses dados. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | delegado |  Quais dados são coletados ou usados? Adicione justificativa para coletar ou usar os dados. IDs de usuário e nomes de exibição de membros do chat atual. O aplicativo usa isso para apresentar ao usuário uma lista de membros do chat para chamar. | Metawitch não armazena esses dados. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | delegado | IDs de usuário e nomes de exibição de membros da equipe atual. O aplicativo usa isso para apresentar ao usuário uma lista de membros da equipe para chamar. | Metawitch não armazena esses dados. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | delegado |  Quais dados são coletados ou usados? Adicione justificativa para coletar ou usar os dados. Os números de telefone celular e comercial dos usuários. Isso é necessário para que as chamadas telefônicas para esses números possam ser iniciadas. |   Metawitch não armazena esses dados | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | delegado | Um token de autorização para o usuário, autorizando o aplicativo a acessar os outros pontos de extremidade Graph API listados em seu nome. | Metawitch não armazena esses dados. | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>Acesso a dados usando outras APIs da Microsoft

Os aplicativos e os Microsoft 365 podem usar APIs adicionais da Microsoft que não Graph microsoft para coletar ou processar informações de identificação organizacional (OII). Listar as APIs da Microsoft que não Graph esse aplicativo usa.

>| **API** |  **O OII é coletado?** |  **Qual OII é Coletado?** | **Justificativa para coletar OII?** | **O OII está armazenado?** | **Justificativa para armazenar OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Plataforma de Identidade da Microsoft | Não |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Redes de metaswitch e comunicações DE PAPO | O OII a seguir é transferido para o MCT Hosted Bot Server: IDs de equipe de IDs de equipe do locatário do Azure AD Canal/IDs de chat O conteúdo da mensagem também é transferido, o que pode incluir OII OII a seguir pode ser transferido para a API JSON do CommPortal: Telefone números de usuários em um Grupo de Negócios Os domínios de endereços de email endereços IP do usuário | Add justification for why you need to transfer OII The app&#8217;principal purpose is to facilitate telephone calls. Se um usuário tentar fazer uma chamada telefônica, essas informações devem ser fornecidas para fazer logoff em sua conta commPortal e correlacionar a chamada de volta ao usuário correto.  O OII que é transferido para o MCT Hosted Bot Server é integrado à API da Estrutura de Bots, que é usada para se integrar ao Teams e não pode ser evitada. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| O aplicativo&#8217;principal é facilitar chamadas telefônicas. Se um usuário tentar fazer uma chamada telefônica, a EUII para todas as partes na chamada deve ser fornecida para estabelecer a chamada entre os usuários de telefonia corretos. | Não |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Metawitch e PAPO NÃO armazenam os dados por mais tempo do que a necessidade imediata de carregar as páginas da Web MCT da Web CommPortal. Os dados não são mantidos e são removidos imediatamente.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela COMUNICAÇÃO DA PAPO SOBRE como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Não |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Políticas de Acesso Condicional na medida em que esse suporte é fornecido automaticamente pela biblioteca MSAL usada para autenticação.  |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Não |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/> |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
