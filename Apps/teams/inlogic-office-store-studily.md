---
title: Informações do aplicativo para Studi.ly pela inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações disponíveis de segurança e conformidade para Studi.ly, suas políticas de tratamento de dados, suas informações de catálogo de aplicativos Microsoft Cloud App Security e informações de segurança/conformidade no registro CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553052"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de agosto de 2020</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Vista na loja Teams</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas pela inLogic-Office Store à Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | Studi.ly |
| ID | WA200001668 |
| Office 365 clientes suportados | Microsoft Teams |
| Nome da empresa parceira | inLogic-Office Store |
| URL do site de parceiros | [https://www.studi.ly](https://www.studi.ly) |
| URL da Política de Privacidade | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| URL de Termos de Uso | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas pela inLogic-Office Store sobre como este aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando Graph microsoft

Liste quaisquer [permissões Graph microsoft](https://docs.microsoft.com/graph/permissions-reference) que este aplicativo exigir.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicação)** | **Os dados são coletados? Justificativa para recolhê-lo?** | **Os dados são armazenados? Justificativa para armazená-lo?** | **ID do aplicativo Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Escreva diretório nos grupos para atribuições e materiais. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | aplicação | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Escreva diretório nos grupos para atribuições e materiais. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | aplicação | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Leia Aulas de Educação, Escola, Membros e Termos.Obtenha todas as aulas e escolas de um inquilino para sincronização no banco de dados do aplicativo. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Leia Aulas de Educação, Escola, Membros e Termos.Obtenha todas as aulas e escolas de um inquilino para sincronização no banco de dados do aplicativo. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | aplicação | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Leia Aulas de Educação, Escola, Membros e Termos.Obtenha todas as aulas e escolas de um inquilino para sincronização no banco de dados do aplicativo. | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | ReadWrite Arquivos de Uma Unidade | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Essa permissão permitiu que o aplicativo recebesse diferentes eventos de claender para grupos do inquilino.,assunto,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | ambos | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Essa permissão permitiu que o aplicativo recebesse diferentes eventos de claender para grupos do inquilino.,assunto,start,end,extensions | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | aplicação |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | ambos | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | ReadWrite Arquivos de Uma Unidade | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Lendo informações do usuário | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | Delegada | Estamos armazenando aulas, escolas e membros e informações de termos da api educacional em nossa api e precisamos disso porque se o pegarmos todas as vezes a api gráfica que faz nossa aplicação funcionar devagar. Nós sincronizamos isso em um evento baseado no tempo, desde a api educacional até nosso banco de dados. | Lendo informações do usuário | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não-Microsoft, liste o serviço não-Microsoft que o aplicativo usa, quais dados são transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>Não serviços Microsoft não são utilizadas.

#### <a name="data-access-via-bots"></a>Acesso a dados via bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele pode acessar informações identificáveis pelo usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de e-mail) de qualquer membro da equipe em uma equipe ou chat a que é adicionado. Este aplicativo faz uso desse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Alguma informação identificável organizacional (OII) ou informações identificáveis pelo usuário final (EUII) aparece na telemetria ou registros deste aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Tais dados não aparecem nos registros

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados por parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas de parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Ele é armazenado no banco de dados cosmos do Azure e qualquer criptografia e armazenamento que esteja disponível por padrão com o banco de dados cosmos é aplicável a este aplicativo.

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os seres humanos estão envolvidos na revisão ou análise de quaisquer dados de informações organificáveis (OII) coletados ou armazenados por este aplicativo?

>Não

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) catálogo aparecem abaixo.

<iframe height='1020' title='Microsoft Cloud App Security informação' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

