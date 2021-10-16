---
title: Informações do aplicativo para Workbench Intelligence por Temporall
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Workbench Intelligence, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 7adf907a083a4fcf5c7c57fe0cf048ba771d0d6e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414427"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 22 de setembro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Temporall para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Workbench Intelligence |
| ID | WA200002705 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Temporall |
| URL do site do parceiro | [https://www.temporall.com](https://www.temporall.com) |
| URL da página Teams de informações do aplicativo | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| URL da Política de Privacidade | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Temporall sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | delegado | Obtém uma lista de aplicativos do teams instalados para obter a ID do aplicativo local para a ID externa conhecida. | A ID do aplicativo local. Necessário para identificar o aplicativo quando instalado em um locatário diferente. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | aplicação | Nome da id &amp; do canal. Justificativa: Permitir a junção/saída do canal para sincronizar a atividade da mensagem.  | O objeto de dados brutos retornado do canal de obter. Justificativa: o Trabalho Temporal permite que os usuários filtrem e categorizem dados de acordo com os canais. Esses dados brutos são salvos para ter referência ao objeto original | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | aplicação | O tipo de &amp; atividade da mensagem, juntamente com o destino do &amp; remetente. Dados recebidos dessas rotas: /teams/${teamId}/channels/${channelId}/messages /teams/${teamId}/channels/${channelId}/messages/${messageId}. Justificativa: para poder calcular o relatório de métricas &amp; sobre a atividade da mensagem. Isso forma o núcleo do módulo de análise de rede organizacional para poder desenhar um diagrama de atividade entre as equipes de &amp; usuários. | Detectamos a quantidade de novas mensagens/respostas/reações/menções que armazenam essas métricas juntamente com &amp; o objeto de mensagem bruto retornado. Os dados são necessários à medida que fazem parte de nossos principais recursos. Executar a análise nos dados da mensagem exige que ele seja salvo no banco de dados para obter um desempenho ideal - isso também reduz a necessidade de acompanhamento de chamadas para os mesmos dados | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | aplicação | ClientId, Lista de usuários, lista de organizações e sub-canais. Justificativa: necessário para ler usuários &amp; de sincronização para o Trabalho Temporal | Nome do usuário, Email, Ícone, Referência De Conversa. Justification:&#160;Temporall Workbench permite que os usuários filtrem e categorizem dados de acordo com os canais. Os dados da organização são armazenados para se reconectar às equipes após a instalação | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | aplicação | Nome da ID do &amp; grupo. Justificativa: para instalar o aplicativo em cada grupo/canal | Nome da id &amp; de grupo juntamente com o objeto de dados brutos para referência. Justificativa: o Trabalho Temporal permite que os usuários filtrem e categorizem dados de acordo com grupos/equipes. Esses dados brutos são salvos para ter referência ao objeto original | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | aplicação | Associação do usuário à equipe. Justificativa: permite a sincronização de todos os usuários no Teams com a Temporall Workbench | Endereço de email, nome e sobrenome. Justificativa: Permitir a correspondência de usuários em equipes com usuários no Trabalho Temporal para permitir a sincronização de usuários por email. | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | aplicação | Lista de leitura dos aplicativos instalados para a Equipe. Justificativa: verifique se nosso aplicativo já está instalado caso contrário o instala para poder obter atividade de mensagem por meio da api gráfica | N/D | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | aplicação | Ler lista de aplicativos instalados. Verifique se nosso aplicativo já está instalado caso contrário o instala para interagir com o usuário por meio de um questionário | NA | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | delegado | Informações &amp; básicas da empresa do usuário. Justificativa: usada para categorizar a atividade de mensagem pelo usuário, permite que o bot participe de mensagens proativas. | Nome do usuário, Email, Ícone, Referência De Conversa. Justificativa: permite que nosso bot envie mensagens proativamente para os usuários com informações relevantes. Usuários de grupo para exibição de dados | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud | Informações LDAP | Nossa plataforma reside na plataforma Google Cloud |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Nenhum OII ou EUII aparece nos logs ou telemetria de aplicativos.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>https://temporall.com/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas pela Temporall sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

