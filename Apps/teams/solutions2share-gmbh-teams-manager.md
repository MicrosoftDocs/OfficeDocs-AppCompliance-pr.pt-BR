---
title: Informações do aplicativo Teams Pelo Solutions2Share GmbH
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Teams Manager, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e51b08446bed1f22f1e058b92604841ce255eb8f
ms.sourcegitcommit: 3ac3366e04e24db2d12183ef212738d5b599f553
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/28/2021
ms.locfileid: "59971793"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Solutions2Share GmbH para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Teams Manager |
| ID | WA200000764 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Solutions2Share GmbH |
| URL do site do parceiro | [https://teams-manager.com](https://teams-manager.com) |
| URL da página Teams de informações do aplicativo | [https://teams-manager.com](https://teams-manager.com) |
| URL da Política de Privacidade | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| URL dos Termos de Uso | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Solutions2Share GmbH sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | ambos | Estamos armazenar o TenantID e o TeamId para mapear os modelos.  | Permitir listagem de todos os Teams e também criar Teams. | [b9a1aab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| Notes.ReadWrite.All | aplicação | Nenhum | Permite que o aplicativo adicione blocos de anotações a uma equipe aprovada. | [b9a1aab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read | delegado | Nenhum | Permite que o usuário entre e dê acesso ao aplicativo ao UPN para habilitar o logon silencioso. | [b9a1aab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.Read.All | ambos | Salvamos a id do usuário inserido na seção aprovador/administrador. | Listar todos os usuários para exibi-los no selador de pessoas dentro do aplicativo. | [b9a1aab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |
>| User.ReadBasic.All | delegado | Nenhum | Listar todos os usuários para exibi-los no selador de pessoas dentro do aplicativo. | [b9a1aab-e8aa-4b92-b4ce-f13cae74caa7](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Estamos fazendo logoff no Azure Log Analytics e estamos usando suas políticas de arquivamento/retenção.
Estamos registrando a ID do locatário e a ID da equipe para identificar problemas e ajudar os clientes a resolver problemas.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Temos conformidade e processo de operação para controle de acesso. Todos os dados e tokens relacionados ao usuário são criptografados. Os dados são armazenados em um Banco de Dados SQL do Azure. Estamos usando o Firewall para permitir apenas conexões de IP específicos (intervalos de IP protegidos entre sistemas). Habilitamos o Gerenciamento de Acesso Privilegiado (PMA) no Azure.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Solutions2Share GmbH sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Não |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/> |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
