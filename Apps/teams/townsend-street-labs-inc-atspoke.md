---
title: Informações do aplicativo para atSpoke by Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 04/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o atSpoke, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 86a4512603429feff61ceeee485e8e4042bb9a6d
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413303"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de junho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo Laboratórios de Rua Desabilados, Inc. para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | atSpoke |
| ID | WA200001454 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Townsend Street Labs, Inc. |
| URL do site do parceiro | [https://www.atspoke.com/](https://www.atspoke.com/) |
| URL da Política de Privacidade | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL dos Termos de Uso | [https://www.atspoke.com/terms-of-service/](https://www.atspoke.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo Laboratórios de Rua Desabilados, Inc. sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | atSpoke armazena a ID de grupo da Microsoft | Permite a capacidade de ler e gravar informações de grupo entre atSpoke e Microsoft Teams.  | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| User.ReadWrite.All | delegado | atSpoke armazena o email do usuário e a ID do usuário | Permite a capacidade de ler e gravar informações do usuário entre atSpoke e Microsoft Teams. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |
>| offline_access | delegado | atSpoke não está armazenar dados para isso. | Isso é usado para sincronização em segundo plano. | [dfaf15dc-4e94-4484-a25d-79358fe70d8b](https://docs.microsoft.com/microsoft-365-app-certification/azure/dfaf15dc-4e94-4484-a25d-79358fe70d8b) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Sim, usamos serviços de terceiros para eficiência operacional. Google, Inc.: Dados armazenados em volumes lógicos, backups de armazenamento em rede nativa do Google Cloud, logs de serviço e API ou logs de aplicativos. Eventos transacionais registrados podem conter identificadores de usuário, informações de contato e conteúdo do cliente. MongoDB, Inc.: Dados armazenados em coleções de banco de dados baseadas em nuvem. - Conteúdo do cliente que inclui solicitações arquivadas por usuários, respostas a solicitações adicionadas por usuários e artigos de conhecimento adicionados pelos usuários. - Identificadores de usuário (Nome, email, avatar e número de telefone usados para criar uma conta de usuário de Fala). Tecnologias Mailgun, Inc.: Informações de contato e identificador de usuário para enviar comunicações de email (por exemplo, nome e email). Twilio, Inc.: Número de telefone do usuário e conteúdo do cliente: conteúdo trocado por meio do uso dos Serviços do Twilio&#8217;, como texto, corpo da mensagem, mídia de voz e vídeo, imagens e som. Mixpanel, Inc.: Os dados pessoais transferidos incluem nome, email, endereço IP e dados pessoais incluídos no conteúdo da mensagem. Cloudinary, Inc.: Conteúdo do cliente baseado em arquivo enviado pelos usuários finais. Elasticsearch, Inc.: Eventos transacionais de aplicativos conectados podem conter texto truncado do conteúdo do cliente. Stitch, Inc.: Informações de contato, informações de uso, identificadores não tradicionais dos Usuários Autorizados do Assinante e quaisquer outros Dados Pessoais que o Assinante ou seus Usuários Autorizados enviem à Plataforma. Mode Analytics, Inc.: Informações de identificadores de usuário para fornecer análises por usuário. DataDog: eventos transacionais de aplicativo registrado podem conter texto truncado do conteúdo do cliente; a retenção de log é de 14 dias. Fullstory, Inc.: Gravações de ações realizadas em nossa interface de usuário da Web; inclui a conta de usuário do Spoke para fins de identificação. |  | Estamos usando a API REST da Estrutura de Bot. Usamos essa API para enviar e receber mensagens para o serviço de bot askSpoke. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Ele permite que o atSpoke sincronize os usuários Microsoft Teams criar usuários e definir permissões. | o atSpoke armazena apenas o email para que Microsoft Teams usuários possam fazer logoff no atSpoke como um usuário válido. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Contido em nossos logs de aplicativos, há o nome e sobrenome de um usuário, o endereço de email do usuário e a ID de objeto atribuída ao Azure para usuários e grupos. Os logs são retidos apenas por 14 dias em que expiram automaticamente. O acesso ao log é protegido contra violações e apenas determinadas equipes têm acesso para exibir os logs.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados em uma instância gerenciada do MongoDB. O acesso ao serviço gerenciado Banco de dados do Atlas MongoDB é provisionado por meio de um processo de solicitação de acesso de usuário padronizado que exige aprovações. As revisões periódicas de acesso do usuário são realizadas com a aprovação de gerenciamento. Restringemos o número de funcionários com acesso a dados confidenciais do cliente e não permitimos modificar dados de nenhum computador diretamente.&#8232; Acesso remoto a esse banco de dados requer autenticação multifator. O banco de dados e todos os backups são criptografados em repouso usando a criptografia de bits do AES-256.


#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


