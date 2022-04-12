---
ms.author: oromalle
title: Microsoft 365 certificação – Guia de envio inicial de documento
author: orionomalley
manager: tonybal
description: O envio inicial do documento faz parte da fase de pré-avaliação da certificação.
keywords: equipes de certificação Microsoft 365 de conformidade de segurança m365 envio de documento inicial
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784500"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification – Guia de envio inicial do documento

O envio inicial do documento faz parte da fase de pré-avaliação da certificação. As informações fornecidas fornecerão aos analistas de certificação o plano de fundo necessário para identificar quais controles e componentes do sistema estarão no escopo para sua avaliação. Este documento destina-se a servir apenas como um exemplo do que é esperado do envio inicial do documento. A documentação que você fornecer variará dependendo de como sua solução é arquiteta, implementada e gerenciada.

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>Qual é o ambiente de hospedagem ou o modelo de serviço usado para executar seu aplicativo?
- A IaaS (infraestrutura como serviço) é um modelo de serviço de nuvem em que o provedor de serviços de nuvem hospeda seus componentes de infraestrutura, mas os ISVs ainda são responsáveis por implantar e gerenciar os componentes individualmente, como Máquinas Virtuais/Sistemas Operacionais, Armazenamentos de Dados e Componentes de Rede. Exemplos disso são a Máquina Virtual do Azure e o Azure Disk Armazenamento.
- A PaaS (plataforma como serviço) é um modelo de serviço de nuvem em que os componentes de infraestrutura são gerenciados pelo provedor de serviços de nuvem. Os ISVs são responsáveis apenas pela implantação de seus próprios aplicativos e serviços. Exemplos disso são serviços Azure App, Azure Functions e CDN do Azure.
- O ISV hospedado nesse contexto significa que nenhum provedor de serviços de nuvem é usado. O ISV gerencia fisicamente seus próprios Servidores, Discos, Rede independentemente localmente.
- Híbrido nesse contexto significa que um dos modelos acima é usado. Por exemplo, alguns ISVs podem optar por usar uma combinação de Serviços de IaaS e serviços de PaaS para dar suporte ao aplicativo, ou podem ter alguns componentes hospedados pelo ISV local e terceirizar outros para um provedor de serviços de nuvem. Se você usar um dos mais modelos de serviço, selecione híbrido.

## <a name="penetration-test-report"></a>Relatório de Teste de Penetração

Inclua o relatório de teste de penetração completo com datas que evidenciam que ele foi concluído nos últimos 12 meses. 
-   Esse relatório deve ser produzido a partir do teste de penetração manual, não pode ser a saída de uma ferramenta de verificação/teste automatizada.
-   Esse relatório deve incluir o ambiente que dá suporte à implantação do aplicativo/adicionar juntamente com qualquer ambiente adicional que dê suporte à operação do aplicativo/suplementos.


## <a name="system-component-inventory"></a>Inventário de Componentes do Sistema

Um inventroy atualizado de todos os componentes do sistema usados pela infraestrutura de suporte. Isso será usado para ajudar na amostragem ao executar a fase de avaliação. Se seu ambiente incluir PaaS, será útil se você puder fornecer detalhes de todos os serviços de PaaS consumidos.

**Nota:** IaaS/PaaS não teria nenhum hardware que estaria sob o controle ISVs.  Nesse caso, forneça uma lista ou captura de tela de todos os recursos viruais.

**Exemplo:**

|Nome do Ativo|Tipo de Ativo|Descrição|Fabricante|Modelo|
|---|---|---|---|---|
|D212|Windows computador|Máquina Virtual|N/D|N/D|
|LT101|Laptop|Workstation|Microsoft|Surface 3|
|C2938|Parâmetro|Parâmetro|N/D|N/D|
|LXM2|Computador Linux|Máquina de Teste|N/D|N/D|


## <a name="software-inventory"></a>Inventário de software

Um inventário atualizado de todos os ativos de software, incluindo todos os softwares usados no ambiente no escopo, juntamente com as versões.

**Exemplo:**

|Software|Publisher|Versão|Objetivo|
|---|---|---|---|
|Windows Server|Microsoft 2016 |Build 14393|Sistema operacional do servidor para o ambiente de produção|
|Linux Ubuntu|N/D|16,04 (Xenial)|Sistema operacional do servidor em uso na DMZ.|
|Esxi|Vmware|6.5.0 (build 13004031)|Usado para dar suporte aos servidores virtuais.|
|Mysql (Windows)|N/D|8.0.2.1|Servidor de banco de dados para armazenar o histórico de chat.|
|Tomcat|Apache|7.0.92|Portal do cliente.|
|IIS|Microsoft|10.0|Dá suporte às APIs.|


## <a name="third-party-dependencies"></a>Dependências de terceiros

Documentação listando todas as dependências usadas pelo aplicativo/suplemento com as versões em execução atuais.

**Exemplo:**

|Dependências da Web|Versão atual em uso|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|Bootstrap|4.5.2|
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>Endereços IP públicos

Detalhando todos os endereços IP públicos e URLs usados pela infraestrutura de suporte. Isso deve incluir o intervalo de IP roteável completo alocado para o ambiente, a menos que a segmentação adequada tenha sido implementada para dividir o intervalo em uso (a evidência adequada de segmentação será necessária).

**Exemplo:**

|URLs|Endereço IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/A (Jump Server)|40.113.200.200|


## <a name="resource-endpoints"></a>Pontos de extremidade de recurso

Endereço do ponto de extremidade de nome de API https://customerapi.contoso.com contoso api do cliente Contoso Serviço de Bot https://bot.contoso.com API de Arquivos contosohttps://filesapi.contoso.com

Uma listagem completa de todos os pontos de extremidade de API usados pelo seu aplicativo, incluindo pontos de extremidade de recursos externos e desenvolvidos internamente. Para ajudar a entender o escopo do ambiente, forneça locais de ponto de extremidade de API em seu ambiente.

**Exemplo:**

|Nome da API|  Endereço do ponto de extremidade|
|-|-|
|API de Cliente da Contoso|  https://customerapi.contoso.com|
|Contoso Serviço de Bot|   https://bot.contoso.com|
|API de Arquivos da Contoso| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagrama arquitetônico

Um diagrama de arquitetura lógica que representa uma visão geral de alto nível da infraestrutura de suporte do seu aplicativo/suplemento. Isso deve incluir todos os ambientes de hospedagem e a infraestrutura de suporte que dá suporte ao aplicativo/suplemento. Este diagrama DEVE descrever todos os diferentes componentes do sistema de suporte dentro do ambiente para ajudar os analistas de certificação a entender os sistemas no escopo e ajudar a determinar a amostragem. Indique também qual tipo de ambiente de hospedagem é usado; ISV Hospedado, IaaS, PaaS ou Híbrido. Onde a PaaS é usada, indique os vários serviços de PaaS usados para fornecer os serviços de suporte dentro do ambiente.

![Diagrama arquitetônico](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Fluxo de Dados diagrama

Flow diagramas detalhando o seguinte:
-   Os dados fluem de e para o Aplicativo/Suplemento (incluindo dados do cliente).
-   Fluxos de dados dentro da infraestrutura de suporte (quando aplicável)
-   Diagramas que realçam onde e quais dados são armazenados, como os dados são passados para terceiros externos (incluindo detalhes de quais terceiros) e como os dados são protegidos em trânsito por redes abertas/públicas e em repouso.

![Fluxo de Dados diagrama](../media/Dataflowdiagram.png)



