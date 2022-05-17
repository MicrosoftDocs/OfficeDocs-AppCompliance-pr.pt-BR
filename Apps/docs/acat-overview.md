---
title: Ferramenta de Automação de Conformidade do Aplicativo para Microsoft 365
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: Visão geral da Ferramenta de Automação Microsoft 365 Conformidade do Aplicativo
keywords: aplicativo de automação de certificação Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: debd3c9e2ecd1538446d09f5019ea995260345fd
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433367"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>Ferramenta de Automação de Conformidade do Aplicativo para Microsoft 365
Neste artigo, você aprenderá o que é a ACAT (App Compliance Automation Tool for Microsoft 365) e como ela simplifica a conformidade e a obtenção da certificação Microsoft 365 aplicativo.

> [!IMPORTANT]
> O ACAT está *em versão prévia* privada no momento. Se você quiser ingressar no programa de visualização privada, entre em contato com [acatprivatepreview@microsoft.com](mailto:acatprivatepreview@microsoft.com).

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>O que é a Ferramenta de Automação de Conformidade do Aplicativo para Microsoft 365
A ACAT (Ferramenta de Automação de Conformidade do Aplicativo para Microsoft 365) é um serviço no Portal do Azure que ajuda a simplificar o percurso de conformidade para qualquer aplicativo que consome Microsoft 365 dados do cliente e é publicado por meio do Partner Center. A Ferramenta de Automação de Conformidade de Aplicativos para Microsoft 365 é uma ferramenta de automação de conformidade centrada no aplicativo que ajuda você a concluir Microsoft 365 certificação com maior facilidade e conveniência. Na Versão Prévia Privada, o ACAT está disponível para aplicativos em execução no Azure.

Com essa ferramenta, você poderá definir rapidamente o limite de conformidade para seus aplicativos, monitorar os resultados de conformidade automaticamente e concluir a auditoria de conformidade com mais facilidade. O limite de conformidade é a infraestrutura de nuvem que dá suporte à entrega do aplicativo e a todos os sistemas de back-end com os qual o aplicativo pode estar se comunicando.

Além de fornecer uma faixa mais rápida para Microsoft 365 certificação, o ACAT pode ajudá-lo em vários cenários de conformidade para Microsoft 365 aplicativos:

- Etapas detalhadas de exibição e correção para Microsoft 365 de certificação.
- Relatórios diários automáticos para ajudá-lo a obter resultados de conformidade continuamente.
- Práticas recomendadas de segurança e conformidade que podem ser usadas como diretrizes na fase inicial do ciclo de vida do aplicativo.

## <a name="benefits-of-acat"></a>Benefícios do ACAT
Jornada de conformidade centrada no aplicativo.
- O ACAT relata o status de conformidade diariamente para o ambiente de nuvem de seus aplicativos, que você pode integrar à sua estratégia de conformidade de infraestrutura de nuvem atual.
- Os desenvolvedores podem invocar o ACAT mesmo durante a fase de desenvolvimento do aplicativo.

Acelera o processo de certificação Microsoft 365 certificado.
- O ACAT automatiza totalmente determinados Microsoft 365 de certificação.
- Há uma lista de automação em crescimento contínuo que está sendo desenvolvida ativamente pela Microsoft.

Integração nativa com o fluxo Microsoft 365 de certificação.
- O ACAT é totalmente integrado ao Partner Center para Microsoft 365 de certificação.

## <a name="concepts-of-acat"></a>Conceitos do ACAT
### <a name="regulatory-compliance-report"></a>Relatório de Conformidade Regulatória 
No ACAT, você pode auditar o status de conformidade do aplicativo criando um relatório de conformidade para ele. Você pode definir o limite de conformidade para seu aplicativo especificando os recursos do Azure que criam o aplicativo. Crie vários relatórios para um aplicativo, com base em diferentes ambientes e estágios de desenvolvimento.

Depois que o relatório for criado, o ACAT começará a coletar os dados de conformidade em seu tempo de gatilho predefinido e, em seguida, gerará os resultados de conformidade como um relatório para você. Enquanto isso, o ACAT continuará monitorando as alterações de conformidade do relatório de conformidade continuamente até que você opte por excluir o relatório.

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365 de controle de certificação
No Relatório de Conformidade Regulatória, os resultados de conformidade são organizados por controles com seus estados correspondentes sinalizados pelo ACAT:
- **Aprovado**: não há falhas para os controles de Microsoft 365 de certificação totalmente automatizados.
- **Falha**: há responsabilidades do cliente com falha detectadas para os controles de Microsoft 365 de certificação totalmente automatizados.
- **Aprovado – Evidência adicional necessária**: não há falhas para os controles *de certificação* Microsoft 365 parcialmente automatizados.
- **Falha – Evidência adicional necessária**: há falhas nas responsabilidades do cliente detectadas para os controles *de Microsoft 365 de* certificação parcialmente automatizados.
- **Controle manual**: o ACAT não automatiza nenhuma responsabilidade do cliente para os controles Microsoft 365 de certificação.

### <a name="customer-responsibility"></a>Responsabilidade do cliente
Há um conjunto de responsabilidades do cliente associadas a cada controle que precisa ser atendido. São responsabilidades retidas por você nas seguintes áreas: dados, pontos de extremidade, conta, gerenciamento de acesso etc.

O ACAT coleta dados para cada responsabilidade do cliente e retorna um resultado de avaliação para ele. Ele também fornece uma ação de correção, que é nossa orientação que ajuda você a se alinhar aos Microsoft 365 de certificação.


## <a name="faq"></a>Perguntas frequentes
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>O que são controles manuais e controles parcialmente automatizados?
Cada controle de conformidade está associado a um conjunto de responsabilidades do cliente, para o qual o ACAT coleta dados de conformidade. No entanto, nem todos os controles Microsoft 365 certificação são cobertos pelo ACAT a partir de agora (há um esforço contínuo para expandir a cobertura). Para o controle parcialmente automatizado, o ACAT automatiza partes das responsabilidades do cliente. Você pode usar o estado de conformidade dele para referência, mas não pode usá-lo para Microsoft 365 auditoria de certificação diretamente. Para os controles manuais, o ACAT atualmente não automatiza nenhuma responsabilidade do cliente.

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>Fiz as alterações sugeridas com base na sugestão de correção, mas o controle ainda está falhando
Depois de executar uma ação para resolver a falha, você precisa aguardar o ACAT buscar os resultados da avaliação atualizados para atualizar o status do controle. As avaliações são executadas a cada 24 horas no tempo de gatilho pré-definido.

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>Como o relatório de conformidade é usado no processo de certificação?
O ACAT é integrado perfeitamente ao [Partner Center](https://partner.microsoft.com/dashboard) para concluir seu Microsoft 365 de certificação. Durante a criação do relatório de conformidade, você pode editar a configuração Microsoft 365 de certificação, ou seja, GUID da oferta. Ele é opcional durante a criação e você pode configurá-lo posteriormente quando começar a publicar o aplicativo.

## <a name="learn-more"></a>Saiba mais

* [Introdução com o ACAT](https://aka.ms/acat/getstarted)
* [Saiba mais sobre a Microsoft 365 certificação](https://aka.ms/acat/m365cert)
