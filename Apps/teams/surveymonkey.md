---
title: Informações do aplicativo para SurveyMonkey por SurveyMonkey
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para SurveyMonkey, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f4898e476e0848ba728d07d0d851fc09f239aecf
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/12/2021
ms.locfileid: "59276573"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pelo SurveyMonkey à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | SurveyMonkey |
| ID | WA104381088 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | SurveyMonkey |
| URL do site do parceiro | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| URL da página Teams de informações do aplicativo | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| URL da Política de Privacidade | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| URL dos Termos de Uso | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pelo SurveyMonkey sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | delegado | Não | Para fornecer uma lista de grupos/canais para compartilhar uma pesquisa com | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Somente a ID do usuário MS é armazenada no SurveyMonkey para associar respostas e pesquisas ao usuário da equipe. |  | Para as equipes, usamos Microsoft Teams SDK javascript no módulo de tarefas criar e de resultados de pesquisa. |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Fazemos uma chamada para v3/conversations/{id}/pagedmembers para verificar se o aplicativo foi adicionado a uma equipe e obter a contagem de membros. É para o controle interno do uso, só vemos o tamanho da lista de chat, outras informações são ignoradas. | Sim, o tamanho do chat é armazenado (um único inteiro) |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>EUII - Um log de sucesso/falha é criado sempre que uma pesquisa obtém uma resposta e tentamos enviar essa resposta para o Teams por meio do conector, esse log inclui user_id, survey_id, integration_id (que no banco de dados pode ser usado para procurar ID de equipe MS, ID de usuário MS)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Nosso data center principal está localizado em Las Vegas, NV e nosso data center secundário está localizado em Santa Clara, CA. SurveyMonkey possui e opera todos os seus servidores e infraestrutura nesses locais. Também temos a residência de dados canadense disponível para determinados clientes Enterprise SurveyMonkey localizados no Canadá. Todos os dados são criptografados em repouso usando o TDE com o AES256 e os dados em trânsito são criptografados usando o TLS 1.2.

SurveyMonkey usa a autenticação do usuário central para manter o gerenciamento de identidade e acesso. Esse sistema gerencia toda a autenticação e autorização para toda e qualquer infraestrutura corporativa e de produção, sistemas e serviços. Políticas de acesso estritas são mantidas e revisadas trimestralmente. As avaliações incluem, mas não se limitam a: listas de acesso do usuário, grupos de políticas e avaliações de acesso de terceiros. Para acessar nosso ambiente de produção (ou seja, para obter uma conta privilegiada), é necessário obter a aprovação do gerente, concluir vários treinamentos necessários e obter aprovação de nossa equipe de segurança. Nesse momento, uma conta VPN adicional é provisionada, o que diferencia &#8216;conta&#8217; de uma conta &#8216;de&#8217; privilegiada.

Somente dispositivos emitidos pela empresa têm permissão para acessar nossa rede de produção. Todos os padrões do fornecedor sem fio são alterados antes da instalação, incluindo, mas não se limitando às chaves de criptografia sem fio padrão, senhas e cadeias de caracteres de comunidade SNMP. 2FA e VPN são necessários para fazer isso remotamente. Temos uma rede wifi separada para acesso de convidados em nossos escritórios corporativos.

Todos os serviços, protocolos e portas permitidas devem ter uma justificativa e aprovação de negócios documentadas, incluindo o uso de recursos de segurança implementados para esses protocolos considerados inseguros. Roteadores e firewalls são configurados para limitar a divulgação de IP a terceiros não autorizados ou não intencionados e limitar o acesso à Internet de entrada a endereços IP no Firewall DMZ e os rulesets do roteador são revisados pelo menos a cada seis meses.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

