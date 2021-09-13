---
title: Informações do aplicativo para Senso por Senso
ms.author: elmalova
author: elenamalova
ms.date: 08/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para Senso, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: a44620633f9eee6c5d5e18997a58158a16c5e801
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276476"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 2 de agosto de 2021</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por Senso à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Senso |
| ID | WA200002571 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Senso |
| URL do site do parceiro | [https://www.senso.cloud](https://www.senso.cloud) |
| URL da página Teams de informações do aplicativo | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| URL da Política de Privacidade | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| URL dos Termos de Uso | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por Senso sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | aplicação | Leia os nomes e descrições do canal para todos os canais para identificar onde uma violação foi sinalizada.   | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | aplicação | Leia a lista de membros e as mensagens de chat de todos os canais. | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | aplicação | Listar mensagens do canal | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | aplicação | Ler todas as mensagens de bate-papo | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | aplicação | Ler Dados do Diretório | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | aplicação | Ler arquivos em todos os conjuntos de sites | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | delegado | Entrar e ler o perfil do usuário | Usado para o login único | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | aplicação | Ler os perfis completos de todos os usuários | Quando ocorre uma violação, o nome do remetente (De), o nome(s) dos destinatários (Para), o nome do canal, a data, a hora e as mensagens desse canal de chat são registrados para fornecer contexto a uma violação.  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud usa os seguintes sub-processadores para o desempenho de seu serviço: https://www.senso.cloud/privacy-policy/ Seção 5. Divulgações de seus dados pessoais. | Os tipos de dados que compartilhamos com contas de terceiros e provedores de terceiros são definidos na seção 5, coluna à direita da tabela ( https://www.senso.cloud/privacy-policy/) . | A base legal para o processamento de cada um se baseia no desempenho de um contrato com você ou necessário para nossos interesses legítimos (para executar nossos negócios, arquivamento de dados, provisionamento de serviços de administração e TI, segurança de rede, para evitar fraudes e violações de dados. Por exemplo, endereço de email comercial, endereço de email é necessário para enviar as notificações de contato de cobrança para o cliente ou se for pago por cartão de crédito, as informações são necessárias para levantar um tíquete de suporte ao acessar o suporte ao cliente. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud usa os seguintes sub-processadores para o desempenho de seu serviço: https://www.senso.cloud/privacy-policy/ Seção 5. Divulgações de seus dados pessoais. | Os tipos de dados que compartilhamos com contas de terceiros e provedores de terceiros são definidos na seção 5, coluna à direita da tabela ( https://www.senso.cloud/privacy-policy/) . | A base legal para o processamento de cada um se baseia no desempenho de um contrato com você ou necessário para nossos interesses legítimos (para executar nossos negócios, arquivamento de dados, provisionamento de serviços de administração e TI, segurança de rede, para evitar fraudes e violações de dados. Por exemplo, endereço de email comercial, endereço de email é necessário para enviar as notificações de contato de cobrança para o cliente ou se for pago por cartão de crédito, as informações são necessárias para levantar um tíquete de suporte ao acessar o suporte ao cliente. |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>O Senso monitora mensagens de chat em bibliotecas de detecção de ameaças de palavras-chave e imagem.  Se ocorrer uma combinação, registraremos as informações a seguir no gatilho de violação; Hora e data, ID do Site, Frase/Imagem, gravidade, De, Para, Nome do Canal, Status e Biblioteca de disparos para revisão pelo usuário final.  Manteremos apenas o PII pelo tempo necessário para cumprir as finalidades para as quais o coletamos, incluindo para fins de satisfazer quaisquer requisitos legais, operacionais, contábeis ou de relatórios

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Acesso limitado a Desenvolvedores Sênior, IP bloqueado, Autenticação de 2 Fatores e Trilhas de Auditoria.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por Senso sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativos e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | Sim |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Sim |
| Listar os tipos de políticas com suporte | Permissões de acesso baseadas em função |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/><br/>- Fluxo ROPC (Resource Owner Password Credential) |
| Seu aplicativo expõe alguma APIs da Web? | Não |
| Seu aplicativo usa APIs de visualização? | Não |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
