---
title: Informações de aplicação para atSpoke pela Townsend Street Labs, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o atSpoke, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a159ce3ac976eb1916cd94b3eb1cf002f8e13c1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551191"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 3 de junho de 2020</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Townsend Street Labs, Inc. à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | atSpoke |
| ID | WA200001454 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Townsend Street Labs, Inc. |
| URL do site de parceiros | [https://www.atspoke.com](https://www.atspoke.com) |
| URL da Política de Privacidade | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| URL de Termos de Uso | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Townsend Street Labs, Inc. sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegada | atSpoke armazena o ID do grupo Microsoft | Permite a capacidade de ler e escrever informações em grupo entre o Microsoft Teams e o Microsoft Teams.  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | Delegada | atSpoke armazena o e-mail do usuário e iD do usuário | Permite a capacidade de ler e gravar informações do usuário entre a Microsoft Teams e a Microsoft Teams. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | Delegada | a atSpoke não está armazenando nenhum dado para isso. | Isto é usado para sincronização de fundo. | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sim, usamos serviços de terceiros para eficiência operacional. Google, Inc.: Dados armazenados em volumes lógicos, backups de armazenamento em rede nativa do Google Cloud, registros de serviços e API ou registros de aplicativos. Os eventos transacionais registrados podem conter identificadores de usuário, informações de contato e conteúdo do cliente. MongoDB, Inc.: Dados armazenados em coleções de bancos de dados baseados em nuvem. - Conteúdo do cliente que inclui solicitações apresentadas pelos usuários, respostas às solicitações adicionadas pelos usuários e artigos de conhecimento adicionados pelos usuários. - Identificadores de usuário (nome, e-mail, avatar e número de telefone usados para criar uma conta de usuário Spoke). Mailgun Technologies, Inc.: Identificador de usuários e informações de contato para enviar comunicações de e-mail (nome e e-mail). Twilio, Inc.: Número de telefone do usuário e conteúdo do cliente: conteúdo trocado por meio do uso de Serviços de Twilio&#8217;, como texto, corpos de mensagens, mídia de voz e vídeo, imagens e som. Mixpanel, Inc.: Os dados pessoais transferidos incluem nome, e-mail, endereço IP e dados pessoais incluídos no conteúdo da mensagem. Cloudinary, Inc.: Conteúdo do cliente baseado em arquivos enviado por usuários finais. Elasticsearch, Inc.: Eventos transacionais de aplicativos registrados podem conter texto truncado do conteúdo do cliente. Stitch, Inc.: Informações de contato, informações de uso, identificadores não tradicionais dos Usuários Autorizados do Assinante e quaisquer outros Dados Pessoais que o Assinante ou seus Usuários Autorizados enviam à Plataforma. Mode Analytics, Inc.: Informações do identificador de usuário para fornecer análises por usuário. DataDog: Eventos transacionais de aplicativos registrados podem conter texto truncado do conteúdo do cliente; a retenção de log é de 14 dias. Fullstory, Inc.: Gravações de ações realizadas em nossa interface de usuário web; inclui a conta de usuário do Spoke para fins de identificação. |  | Estamos usando API de Bot Framework REST. Usamos esta API para enviar e receber mensagens para o serviço de bot askSpoke. |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Ele permite que o atSpoke sincronize os usuários de Microsoft Teams para criar usuários e definir permissões. | o atSpoke armazena apenas o e-mail para que Microsoft Teams usuários possam fazer login no Spoke como um usuário válido. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Contido em nossos registros de aplicativos, há o nome e sobrenome do usuário, o endereço de e-mail do usuário e o ID de objeto atribuído ao Azure para usuários e grupos. Os registros só são retidos por 14 dias, momento em que expiram automaticamente. O acesso ao registro está protegido contra adulteração e apenas alguns funcionários têm acesso para visualizar os registros.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Os dados do aplicativo são armazenados em uma instância de MongoDB gerenciado. O acesso ao serviço gerenciado O Banco de dados Atlas MongoDB é provisionado através de um processo padronizado de solicitação de acesso ao usuário que requer aprovações. As revisões periódicas de acesso ao usuário são realizadas com aprovação de gerenciamento. Restringimos o número de funcionários com acesso a dados confidenciais do cliente e não permitimos modificar dados de nenhuma máquina diretamente.&#8232; acesso remoto a este banco de dados requer autenticação multifatorial. O banco de dados e todos os backups são criptografados em repouso usando criptografia de bits AES-256.


#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

