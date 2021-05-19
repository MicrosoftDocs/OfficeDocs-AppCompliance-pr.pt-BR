---
title: Informações do aplicativo para SurveyMonkey por SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o SurveyMonkey, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552722"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela SurveyMonkey à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SurveyMonkey |
| ID | WA104381088 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | SurveyMonkey |
| URL do site de parceiros | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL da página de informações do aplicativo Teams | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL da Política de Privacidade | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| URL de Termos de Uso | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela SurveyMonkey sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Delegada | Não | Para fornecer uma lista de grupos/canais para compartilhar uma pesquisa com |  |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os OII não serviços Microsoft são transferidos para** |  **O que é transferido?** | **Justificativa para transferir OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Apenas o id do usuário de MS é armazenado no SurveyMonkey para associar respostas e pesquisas com o usuário da equipe. |  | Para as equipes, usamos o Microsoft Teams javascript SDK no módulo de tarefas criar, fazer pesquisa e pesquisar resultados do módulo de tarefas modal. |

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Fazemos uma chamada para v3/conversations/{id}/pagedmembers para verificar se o aplicativo é adicionado a uma equipe e obter a contagem de membros. É para rastreamento interno de uso, só olhamos para o tamanho da lista de bate-papo, outras informações são ignoradas. | Sim, o tamanho do chat é armazenado (um único inteiro) |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>EUII - Um registro de sucesso/falha é criado sempre que uma pesquisa obtém uma resposta, e tentamos enviar essa resposta para Teams através do conector, este log inclui user_id, survey_id, integration_id (que no banco de dados pode ser usado para procurar MS Team ID, MS User ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Nosso data center principal está localizado em Las Vegas, NV e nosso data center secundário está localizado em Santa Clara, CA. A SurveyMonkey possui e opera todos os seus servidores e infraestrutura nesses locais. Também temos residência de dados canadense disponível para certos clientes surveyMonkey Enterprise localizados no Canadá. Todos os dados são criptografados em repouso usando TDE com AES256 e os dados em trânsito são criptografados usando o TLS 1.2.

O SurveyMonkey usa autenticação central do usuário para manter o gerenciamento de identidade e acesso. Este sistema gerencia toda a autenticação e autorização para toda e qualquer empresa, e infraestrutura de produção, sistemas e serviços. Políticas de acesso rigorosas são mantidas e revisadas trimestralmente. As avaliações incluem, mas não se limitam a: listas de acesso ao usuário, grupos de políticas e avaliações de acesso de terceiros. Para acessar nosso ambiente de produção (ou seja, para obter uma conta privilegiada), é preciso obter a aprovação do gerente, completar uma série de treinamentos necessários e obter aprovação de nossa equipe de segurança. Nesse momento, é fornecida uma conta VPN adicional, o que diferencia a &#8216;conta normal de&#8217; de uma conta&#8217; privilegiada &#8216;.

Somente dispositivos emitidos pela empresa podem acessar nossa rede de produção. Todos os padrões de fornecedores sem fio são alterados antes da instalação, incluindo, mas não se limitando a chaves de criptografia sem fio padrão, senhas e strings da comunidade SNMP. 2FA e VPN são necessários para fazê-lo remotamente. Temos uma rede wi-fi separada para acesso de hóspedes em nossos escritórios corporativos.

Todos os serviços, protocolos e portos permitidos devem ter uma justificativa e aprovação de negócios documentadas, incluindo o uso de recursos de segurança implementados para esses protocolos considerados inseguros. Roteadores e firewalls são configurados para limitar a divulgação de IP a partes não autorizadas ou não intencionais e limitar o acesso à Internet de entrada a endereços IP dentro do Firewall DMZ e as regras do roteador são revisadas pelo menos a cada seis meses.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

