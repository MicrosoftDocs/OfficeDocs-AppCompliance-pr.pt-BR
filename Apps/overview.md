---
title: Programa de Conformidade de Aplicativos do Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introdução e visão geral do programa
keywords: microsoft 365 aplicativo m365 certificação do Atestado do Editor
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: 17aab158f4fc7803966afed9df88adf9688fcc63
ms.sourcegitcommit: af065aeee2812a85ead9e0de968fc474204a6e8a
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/22/2022
ms.locfileid: "63697063"
---
# <a name="microsoft-365-app-compliance-program"></a>Programa de Conformidade de Aplicativos do Microsoft 365

O Programa de Conformidade do Aplicativo do Microsoft 365 é uma abordagem de duas etapas para a segurança e conformidade do aplicativo e inclui a Verificação do Publisher e a Certificação do Microsoft 365. Cada camada se baseia na próxima, oferecendo um programa em camadas para dar aos usuários a confiança de que precisam para usar aplicativos no ecossistema do Microsoft 365.  

Nossa missão: dar aos clientes da Microsoft uma maneira de confiar completamente nos aplicativos que administram suas organizações.

![Abordagem de 2 camadas para a Conformidade de Aplicativos](media/Microsoft365AppComplianceBanner.png)

## <a name="publisher-verification"></a>Verificação do Editor

A [Verificação do Editor](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) ajuda administradores e usuários a entenderem a autenticidade dos desenvolvedores de aplicativos integrados à plataforma de identidade da Microsoft. Quando um aplicativo é marcado como verificado pelo editor, significa que o editor verificou sua identidade usando uma conta do Microsoft Partner Network que concluiu o processo de verificação e associou essa conta do MPN ao registro do aplicativo.
A Verificação do Editor se aplica aos aplicativos que atendem às seguintes condições:  
- Usando o OAuth 2.0 e o OpenID Connect para conectar os usuários e solicitar acesso aos dados usando service-side APIs, como o Microsoft Graph. 
- Registrado no Azure AD como multilocatário.  

> [!IMPORTANT]
> A Verificação do Editor não impede que um desenvolvedor de aplicativos inicie ou conclua o Atestado do Editor ou a Certificação Microsoft 365. Se não se aplicar ao aplicativo, a verificação pode ser ignorada e o atestado pode ser iniciado.

## <a name="microsoft-365-certification"></a>Certificação Microsoft 365
A Certificação do Microsoft 365 tem duas fases: **Atestado** e **Certificação**.
1.  O **atestado** envolve a conclusão de um questionário sobre os atributos de segurança, tratamento de dados e conformidade de um aplicativo que são mais importantes para os clientes. Todas as informações são publicadas em um único lugar e em um formato consistente e fácil de ler. O objetivo é facilitar e acelerar o processo de adoção de aplicativos, garantindo aos clientes que os aplicativos usados nos seus locatários atendem aos seus padrões organizacionais.
1.  A **certificação** envolve uma auditoria completa de um aplicativo em relação a um conjunto de controles derivados de estruturas padrão líderes do setor. OS ISVs serão solicitados a fornecer evidências para demonstrar que estão atendendo a cada controle antes de receber uma certificação. O objetivo é dar aos clientes a garantia de que eles podem confiar que os aplicativos que receberam uma Certificação do Microsoft 365 têm práticas de segurança e conformidade fortes para proteger sua segurança de dados e privacidade.


A Certificação Microsoft 365 se aplica a todos os aplicativos que se integram aos seguintes produtos da Microsoft:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- Microsoft Office SharePoint Online
- Project
- OneNote
- **Webapps** (aplicativos SaaS publicados por meio do mercado comercial no Partner Center estão atualmente em uma visualização privada, se você estiver interessado em participar, preencha este [formulário](https://forms.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR3Om82jEdWlAkFiVJRhmM_xUQkY0SjVVOVVLR0RUN0RYNlRWMDRTSjVQRy4u).

### <a name="get-started"></a>Introdução
- [Como concluir a Verificação do Publisher](https://docs.microsoft.com/azure/active-directory/develop/mark-app-as-publisher-verified)
- [Como concluir a certificação do Microsoft 365](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification)

