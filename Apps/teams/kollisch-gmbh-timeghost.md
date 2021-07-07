---
title: Informações do aplicativo para timeghost por K&#246;llisch GmbH
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Todas as informações de segurança e conformidade disponíveis para o timeghost, suas políticas de tratamento de dados, suas Microsoft Cloud App Security de catálogo de aplicativos e informações de segurança/conformidade no Registro STAR do CSA.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1a6a6cda6c7f70fff9df1c5fa6dbfb009ea12ed1
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/02/2021
ms.locfileid: "53281784"
---
# <a name="timeghost"></a>timeghost

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Última atualização pelo desenvolvedor em: 24 de fevereiro de 2021</p>

* <a href="https://teams.microsoft.com/l/app/e3956558-7399-4ec1-848a-c61a2aa95bc1" target="_blank">Exibir no Teams store</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001532" target="_blank">Exibir no AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Informações gerais

Informações fornecidas por K&#246;llisch GmbH para a Microsoft:

| **Information** | **Response** |
|:----------------|:-------------|
| Nome do aplicativo | timeghost |
| ID | WA200001532 |
| Office 365 clientes com suporte | Microsoft Teams |
| Nome da empresa de parceiro | K&#246;llisch GmbH |
| URL do site do parceiro | [https://timeghost.io](https://timeghost.io) |
| URL da página Teams de informações do aplicativo | [https://timeghost.io](https://timeghost.io) |
| URL da Política de Privacidade | [https://timeghost.io/privacy-policy/](https://timeghost.io/privacy-policy/) |
| URL dos Termos de Uso | [https://timeghost.io/terms-and-conditions/](https://timeghost.io/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Como o aplicativo lida com dados

Essas informações foram fornecidas por K&#246;llisch GmbH sobre como esse aplicativo coleta e armazena dados organizacionais e o controle que sua organização terá sobre os dados coletados pelo aplicativo.

#### <a name="data-access-using-microsoft-graph"></a>Acesso a dados usando o Microsoft Graph

Listar [todas as permissões Graph microsoft que](https://docs.microsoft.com/graph/permissions-reference) este aplicativo exige.

>| **Permissão**  | **Tipo de permissão (Delegada/Aplicativo)** | **Os dados são coletados? Justificativa para colecioná-lo?** | **Os dados são armazenados? Justificativa para armazenar isso?** | **ID do aplicativo do Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | delegado | Titel, Startdatum, Enddatum, ID | Kalenderdaten werden beim Buchen eines Kalendereintrages auf ein Projekt gespeichert. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| People.Read | delegado | Email-Adresse | Die Daten werden gespeichert um weitere Team-Mitglieder hinzuzuf&#252;gen und die Avatare der Nutzer anzuzeigen. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| User.Read | delegado | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| User.ReadBasic.All | delegado | Um das Profilbild anzuzeigen. | Keine Daten werden gespeichert. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| openid | delegado | ID  | Speicherung der ID des Users zur Zuordnung des Users. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |
>| perfil | delegado | Vorname, Nachname, E-Mail-Adresse, Organisation, Telefonnummer, Rolle, Sprache, Location | Beim Anlegen eines timeghost User-Profils werden diese Daten gespeichert, um die Benutzererfahrung zu verbessern. | f6f894ce-5b44-4c9b-aff4-253d2fbe8a99 |


#### <a name="non-microsoft-services-used"></a>Não serviços Microsoft usado

Se o aplicativo transferir ou compartilhar dados organizacionais com o serviço não Microsoft, liste o serviço que não é da Microsoft que o aplicativo usa, quais dados serão transferidos e inclua uma justificativa para o motivo pelo qual o aplicativo precisa transferir essas informações.

>| **Todos os não serviços Microsoft OII são transferidos para** |  **Qual OII é transferido?** | **Justificativa para transferir o OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Sentry.io, Chargebee | Vorname, Nachname, E-Mail-Adresse, Firmenname  | Zur Fehlerermittlung, Zahlungs&#252;bermittlung |

#### <a name="data-access-via-bots"></a>Acesso a dados por meio de bots

Se este aplicativo contiver um bot ou uma extensão de mensagens, ele poderá acessar as informações de identificação do usuário final (EUII): a lista (nome, sobrenome, nome de exibição, endereço de email) de qualquer membro da equipe em uma equipe ou chat ao que é adicionado. Esse aplicativo usa esse recurso?

>Nenhum EUII é acessado.


#### <a name="telemetry-data"></a>Dados de telemetria

Quaisquer informações de identificação organizacional (OII) ou informações de identificação do usuário final (EUII) aparecem na telemetria ou nos logs desse aplicativo? Se sim, descreva quais dados são armazenados e quais são as políticas de retenção e remoção?

>Email-Adresse, ID do Usuário

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Controles organizacionais para dados armazenados pelo parceiro

Descrever como os administradores da organização podem controlar suas informações em sistemas parceiros? por exemplo, exclusão, retenção, auditoria, arquivamento, política de usuário final, etc.

>Auditoria

#### <a name="human-review-of-organizational-information"></a>Revisão humana de informações organizacionais

Os humanos estão envolvidos na revisão ou análise de dados OII (informações de identificação organizacional) coletados ou armazenados por esse aplicativo?

>Sim

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

As informações do [catálogo Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) são exibidas abaixo.

<iframe height='1020' title='Microsoft Cloud App Security Informações' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36447" target="_blank">Exibir em uma nova guia</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Informações de identidade

Essas informações foram fornecidas por K&#246;llisch GmbH sobre como esse aplicativo lida com autenticação, autorização, práticas recomendadas de registro de aplicativo e outros critérios de Identidade.

| **Information** | **Response** |
|:----------------|:-------------|
| Você se integra à Plataforma de Identificação da Microsoft (Azure AD)?  | Sim |
| Você já analisou e cumpriu todas as práticas recomendadas aplicáveis descritas na lista de verificação plataforma de identidade da Microsoft integração?  | Sim |
| Seu aplicativo usa o MSAL (Biblioteca de Autenticação da Microsoft) para autenticação? | verdadeiro |
| Seu aplicativo dá suporte a políticas de Acesso Condicional? | Não |
| Seu aplicativo solicita permissões de privilégios mínimos para seu cenário? | Sim |
| As permissões registradas estaticamente do seu aplicativo refletem com precisão as permissões que seu aplicativo solicitará dinamicamente e incrementalmente? | Sim |
| Seu aplicativo dá suporte a multi-enancy? | Sim |
| Seu aplicativo tem um cliente confidencial? | Sim |
| Você possui todo o URI (Identificador de Recurso Unificado) de redirecionamento registrado para seu aplicativo? | Sim |
| Para seu aplicativo, o que você evita usar? | - URIs de redirecionamento curinga,<br/>- OAuth2 Flow, a menos que seja necessário para um SPA<br/> |
| Seu aplicativo expõe alguma APIs da Web? | Sim |
| Seu modelo de permissão só permite que as chamadas recebam êxito se o aplicativo cliente receber o consentimento adequado? | Sim |
| Seu aplicativo usa APIs de visualização? | Sim |
| Seu aplicativo usa APIs preteridas? | Não |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
