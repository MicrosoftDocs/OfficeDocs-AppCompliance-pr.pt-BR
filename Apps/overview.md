---
title: Programa de Conformidade de Aplicativos do Microsoft 365
author: LGerrard
ms.author: Legerrar
description: Introdução e visão geral do programa
keywords: microsoft 365 aplicativo m365 certificação do Atestado do Editor
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: 17d5c8cdba50666e2c38912e42fc60dd36d00d091531294bf865d6c0f92a31f4
ms.sourcegitcommit: 717ca5bc90981def8914c4cd1fad992f67be4d5b
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 08/06/2021
ms.locfileid: "54803647"
---
# <a name="microsoft-365-app-compliance-program"></a>Programa de Conformidade de Aplicativos do Microsoft 365

O Programa de Conformidade de Aplicativos do Microsoft 365 é um método de três camadas para segurança e conformidade dos aplicativos. Cada camada se baseia na próxima, oferecendo um programa em camadas para dar aos usuários a confiança de que precisam para usar aplicativos no ecossistema do Microsoft 365. Atualmente, todas as camadas do programa são voluntárias e são concluídas a critério dos desenvolvedores do aplicativo. 

Nossa declaração de missão: os clientes da Microsoft têm total confiança nos aplicativos que administram suas organizações.

  ![Abordagem de 3 camadas para Conformidade de Aplicativos](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>Verificação do Editor

A [Verificação do Editor](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) ajuda administradores e usuários a entenderem a autenticidade dos desenvolvedores de aplicativos integrados à plataforma de identidade da Microsoft. Quando um aplicativo é marcado como verificado pelo editor, significa que o editor verificou sua identidade usando uma conta do Microsoft Partner Network que concluiu o processo de verificação e associou essa conta do MPN ao registro do aplicativo.
A Verificação do Editor se aplica aos aplicativos que atendem às seguintes condições:  
- Usando o OAuth 2.0 e o OpenID Connect para conectar os usuários e solicitar acesso aos dados usando service-side APIs, como o Microsoft Graph. 
- Registrado no Azure AD como multilocatário.  

> [!IMPORTANT]
> A Verificação do Editor não impede que um desenvolvedor de aplicativos inicie ou conclua o Atestado do Editor ou a Certificação Microsoft 365. Se não se aplicar ao aplicativo, a verificação pode ser ignorada e o atestado pode ser iniciado.

## <a name="publisher-attestation"></a>Atestado do Editor

O [Atestado de Editor](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) é onde os desenvolvedores compartilham informações gerais, de gerenciamento de dados e de segurança e conformidade sobre os serviços do aplicativo. Isso reduz a necessidade dos administradores de TI trabalharem diretamente com os editores de aplicativos. Todas as informações necessárias para tomar uma decisão informada podem ser encontradas sobre todos os aplicativos que concluíram o teste do editor em um único lugar e em um formato consistente. O objetivo é facilitar e acelerar o processo de adoção de aplicativos, garantindo aos clientes que os aplicativos usados nos seus locatários atendem aos seus padrões organizacionais.

O Atestado do Publisher aplica-se ao WebApps e a todos os aplicativos que se integram com os seguintes produtos da Microsoft:
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- Microsoft Office SharePoint Online
- Project
- OneNote

> [!IMPORTANT]
> A Microsoft não valida as informações fornecidas. O desenvolvedor afirma exclusivamente a veracidade, a precisão e a integridade da documentação de atestado e dos dados de desempenho do aplicativo correspondentes. 

## <a name="microsoft-365-certification"></a>Certificação Microsoft 365
A [Certificação Microsoft 365](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) oferece garantia e confiança às organizações de que os dados e a privacidade estão adequadamente protegidos ao usar aplicativos do Microsoft Teams. A certificação confirma que uma solução de aplicativo é compatível com as tecnologias da Microsoft, compatível com as práticas recomendadas de segurança de aplicativos na nuvem e com suporte da Microsoft. Durante esse processo, os desenvolvedores de aplicativos trabalham com um avaliador terceirizado para validar a segurança organizacional e os padrões de conformidade. A certificação do Microsoft 365 se aplica aos mesmos aplicativos que se qualificam para o Atestado do Publicador. 


