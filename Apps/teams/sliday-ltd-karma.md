---
title: Informações do aplicativo para karma por Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para o Karma, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9da5f26e68be07cc9817c50434e214de3f3784c4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551631"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Sliday LTD à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Karma |
| ID | WA104381640 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | Sliday LTD |
| URL do site de parceiros | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| URL da página de informações do aplicativo Teams | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL da Política de Privacidade | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| URL de Termos de Uso | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Sliday LTD sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | aplicação | Nome, sobrenome e endereço de e-mail da empresa. Primeiro nome, sobrenome para administrador que enfrenta reportagem. Endereço de e-mail para comunicação em relação ao Karma, fins de faturamento e herarquia. | Nome de exibição de consentimento administrativo. Faça login e leia o perfil do usuário. Descrição do consentimento do administrador. Permite que os usuários faça login no aplicativo e permite que o aplicativo leia o perfil dos usuários inscritos. Ele também permite que o aplicativo leia informações básicas da empresa sobre usuários de assinatura. Nome de exibição de consentimento do usuárioSigná-lo e ler seu perfil. Descrição do consentimento do usuário. Permite que você faça login no aplicativo com sua conta organizacional e deixe o aplicativo ler seu perfil. Ele também permite que o aplicativo leia informações básicas da empresa. | 9ff28b02-ccc5-4cac-9d17-4cf6987c371f |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>| **Justificativa para acessar o EUII?**  | **O EUII está armazenado em banco de dados?** | **Justificativa para armazenar euii?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Nome, sobrenome e endereço de e-mail da empresa Nome primeiro nome, sobrenome para administrador que enfrenta o endereço de e-mail de relatórios para comunicação em relação ao Karma. A lista é necessária para fins de faturamento e para dividir os usuários em massa em departaments separados. | Nome, sobrenome e endereço de e-mail da empresa Nome primeiro nome, sobrenome para administração que enfrenta relatórios. Endereço de e-mail para comunicação em relação ao Karma, propósitos de faturamento e hierarquia de usuários do Karma. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos as identificaçãos dos inquilinos e os IDs do usuário em logs. Ambos não são identificáveis.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>1. **Alguma solução DLP está em vigor? O que é implementado para evitar vazamentos de dados?**

Sim, os dados são criptografados tanto em trânsito quanto em repouso.

2. **Que tipo de mecanismos você implementa para garantir que a Integridade dos Dados esteja protegida contra erros, corrupção ou uso indevido e com que frequência eles são controlados**

Todos os servidores executam raid de hardware com diferentes níveis de RAID, mas em cada caso, ele requer várias falhas de unidade ao mesmo tempo para que qualquer perda de dados ocorra. Nós vamos extra seguro e temos backups automáticos e manuais. Os bancos de dados são automaticamente armazenados todos os dias e armazenados por sete dias.
Os VMs são automaticamente armazenados toda semana e armazenados por 1 mês.

**Instantâneos e backups são armazenados em uma rede interna não visível publicamente.**

3. **Descreva como você se certifica de que os dados do cliente estão devidamente segregados dos de outros clientes em soluções multi-inquilinos e como você controla que os dados de produção não são replicados ou usados em ambientes não produtivos**

Armazenado em diferentes bancos de dados.

4. **Que tipo de criptografia você propõe (algoritmos, protocolos, comprimentos-chave) para dados em trânsito e dados em repouso**

Todos os dados em trânsito são criptografados por TLS ou SSL. HTTP é criptografado pelo tráfego de banco de dados TLS 1.2 ou TLS 1.3 criptografado pelo SSL.

Os dados são armazenados no centro de nuvem oceânica digital em data centers dos EUA.

5. **Descreva como você gerencia chaves de criptografia exclusivas (processo, armazenamento, uso, RACI, SOD) para seu próprio uso e para cada um de seus inquilinos**

Manipulado pela Digital Ocean.

6. **Descreva o processo de gerenciamento de acesso em vigor no final do provedor apontando como você garante a remoção oportuna de acessos que não são mais necessários e como você controla a adequação dos privilégios para o papel de trabalho. Descrever também os processos de revalidação e a frequência de sua execução**

Usamos autenticação de dois fatores para acessar o painel de controle. Apenas 3 pessoas têm acesso a isso, alteramos senhas todos os meses, mantemos os registros de acesso auditados e garantimos que as pessoas que não trabalham mais conosco tenham suas contas removidas da plataforma.

7. **Forneça o procedimento implementado ao seu final para gerenciar seus IDs compartilhados (por exemplo, raiz, Sys, System, etc.), IDs do grupo (contas genéricas usadas por vários indivíduos pertencentes à mesma equipe, por exemplo) e contas locais. Descreva como você restringe, registra e monitora o uso de contas privilegiadas e o acesso a dispositivos de segurança (por exemplo, hipervisores, firewalls, scanners de vulnerabilidade, farejadores de rede, APIs, etc.), como você garante que os usuários que mudam de equipe ou saem não podem mais acessar o ID do grupo e qual é o nível de rastreabilidade de tais IDs**

Usamos o 1Password para compartilhar&#8217;de ID, temos um feed de atividades separados toda vez que o recurso compartilhado foi acessado a partir de um depositário de senha compartilhado. A menos que seja absolutamente necessário, não usamos contas compartilhadas e usamos contas individuais. Nenhuma informação no banco de dados karma poderia ser acessada através de um login compartilhado. 2FA é usado para acessar 1Password para recuperar um login individual.

8. **Descreva o processo para garantir e monitorar que a Segregação de Deveres é respeitada e com que frequência ela é controlada**

Fizemos reuniões mensais que cobrem a segregação de direitos, a importância do uso dedicado do login e do 2FA todos os logins possíveis.

Nosso SIEM contém: logs de firewall, logs de servidores web e registros de aplicativos. O SIEM está sendo analisado diariamente e ao receber. Os registros são retidos por 1 mês e removidos com segurança depois disso.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

