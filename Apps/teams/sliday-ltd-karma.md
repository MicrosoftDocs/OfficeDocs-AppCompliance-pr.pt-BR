---
title: Informações do aplicativo para o Karma pela Sliday LTD
ms.author: elmalova
author: elenamalova
ms.date: 09/14/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o Karma, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 69163a7c191e9a7e8d460a7f20623466d208042e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410905"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 16 de dezembro de 2019</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela Sliday LTD à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Karma |
| ID | WA104381640 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | Sliday LTD |
| URL do site do parceiro | [https://sliday.com](https://sliday.com) |
| URL da página Teams de informações do aplicativo | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| URL da Política de Privacidade | [https://karmabot.readme.io/docs/privacy-policy-for-microsof...](https://karmabot.readme.io/docs/privacy-policy-for-microsoft-teams) |
| URL dos Termos de Uso | [https://karmabot.readme.io/docs/terms-and-conditions](https://karmabot.readme.io/docs/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela Sliday LTD sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegado/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | aplicação | Nome, sobrenome e endereço de email da empresa. Nome, sobrenome para relatórios voltados para administrador. Endereço de email para comunicação em relação ao Karma, fins de cobrança e herarquia. | Nome de exibição de consentimento do administrador. Entre e leia o perfil do usuário. Descrição do consentimento do administrador. Permite que os usuários se inscrevam no aplicativo e permitem que o aplicativo leia o perfil de usuários assinados. Ele também permite que o aplicativo leia informações básicas da empresa de usuários assinados. Nome de exibição de consentimento do usuárioSigne você e leia seu perfil. Descrição do consentimento do usuário. Permite que você entre no aplicativo com sua conta organizacional e permita que o aplicativo leia seu perfil. Ele também permite que o aplicativo leia informações básicas da empresa. | [9ff28b02-ccc5-4cac-9d17-4cf6987c371f](https://docs.microsoft.com/microsoft-365-app-certification/azure/9ff28b02-ccc5-4cac-9d17-4cf6987c371f) |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são usados.

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>| **Justificativa para acessar a EUII?**  | **O EUII é armazenado em banco de dados(s)?** | **Justificativa para armazenar EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Nome, sobrenome e endereço de email da empresa Nome, sobrenome do administrador voltado para o endereço de email de relatório para comunicação em relação ao Karma. A lista é necessária para fins de cobrança e para dividir os usuários em massa em departaments separados. | Nome, sobrenome e endereço de email da empresa Nome, sobrenome para relatórios voltados para administrador. Endereço de email para comunicação em relação ao Karma, fins de cobrança e hierarquia de usuários do Karma. |  |


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Armazenamos IDs de locatários e IDs de usuário em logs. Ambos não são identificáveis.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>1. **Existe alguma solução DLP? O que é implementado para evitar vazamentos de dados?**

SIM, os dados são criptografados em trânsito e em repouso.

2. **Que tipo de mecanismos você implementa para garantir que a Integridade de Dados seja protegida contra erros, corrupção ou uso indevido e com que frequência eles são controlados**

Todos os servidores executarão RAID de hardware com níveis RAID diferentes, mas, em cada caso, ele requer várias falhas de unidade ao mesmo tempo para que qualquer perda de dados ocorra. Vamos com segurança extra e temos backups automáticos e manuais. Os bancos de dados são automaticamente armazenados todos os dias e armazenados por sete dias.
As VMs são automaticamente respaldadas toda semana e armazenadas por 1 mês.

**Instantâneos e Backups são armazenados em uma rede interna não visível publicamente.**

3. **Descreva como você garante que os dados do cliente estão corretamente segregados dos de outros clientes em soluções de vários locatários e como você controla que os dados de produção não são replicados ou usados em ambientes que não são de produção**

Armazenado em bancos de dados diferentes.

4. **Que tipo de criptografia você propõe (algoritmos, protocolos, comprimentos de chave) para dados em trânsito e dados em repouso**

Todos os dados em trânsito são criptografados por TLS ou SSL. HTTP é criptografado pelo tráfego de banco de dados TLS 1.2 ou TLS 1.3 criptografado por SSL.

Os dados são armazenados no Centro de nuvem do oceano digital em data center dos EUA.

5. **Descrever como você gerencia chaves de criptografia exclusivas (processo, armazenamento, uso, RACI, SOD) para seu próprio uso e para cada um de seus locatários**

Manipulado pelo Digital Ocean.

6. **Descreva o processo de gerenciamento do Access no final do provedor, indicando como você garante a remoção em tempo há tempo dos acessos que não são mais necessários e como você controla a adequação dos privilégios à função de trabalho. Também descreva os processos de revalidação e a frequência de sua execução**

Usamos a autenticação de dois fatores para acessar o painel de controle. Somente 3 pessoas têm acesso a isso, alteramos senhas todos os meses, fazemos auditoria de logs de acesso e asseguramos que as pessoas que não trabalham mais conosco tenham suas contas removidas da plataforma.

7. **Forneça o procedimento implementado no final para gerenciar suas IDs Compartilhadas (por exemplo, raiz, Sys, Sistema, etc.), IDs de Grupo (contas genéricas usadas por vários indivíduos pertencentes à mesma equipe, por exemplo) e contas locais. Descreva como restringir, registrar e monitorar o uso de contas privilegiadas e o acesso a dispositivos de segurança (por exemplo, hipervisores, firewalls, scanners de vulnerabilidades, farejadores de rede, APIs etc.), como você garante que os usuários que estão alterando a equipe ou deixando não possam mais acessar a ID do Grupo e qual é o nível de rastreabilidade dessas IDs**

Usamos o 1Password para compartilhar IDs compartilháveis&#8217;, temos um feed de atividade separado sempre que o recurso compartilhado foi acessado de um depositário de senha compartilhado. A menos que seja absolutamente necessário, não usamos contas compartilhadas e usamos contas individuais. Nenhuma informação no banco de dados do Karma pode ser acessada por meio de um logon compartilhado. O 2FA é usado para acessar o 1Password para recuperar um logon individual.

8. **Descreva o processo para garantir e monitorar se a Segregação de Funções é respeitada e com que frequência ela é controlada**

Fizemos reuniões mensais que abrangem a segregação de direitos, a importância do uso de logon dedicado e 2FA a cada logon possível.

Nosso SIEM contém: logs de firewall, logs de servidor Web e logs de aplicativos. SIEM está sendo analisado diariamente e ao receber. Os logs são mantidos por 1 mês e removidos com segurança depois disso.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


