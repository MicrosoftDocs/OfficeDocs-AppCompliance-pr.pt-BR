---
ms.author: oromalle
title: Microsoft 365 Certificação - Guia inicial de envio de documentos
author: orionomalley
description: Microsoft 365 Exibição granular do Guia de Envio de Certificação
keywords: equipes de certificação de aplicativos Microsoft 365 conformidade de segurança m365 envio de documento inicial
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0352b64649d87b40d185a2bc06ce23da6cf341ef
ms.sourcegitcommit: d67be08c82a50cc263a4bdeb176f41dd60716159
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/15/2021
ms.locfileid: "60378809"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365 Ceritification - Guia inicial de envio de documento

O envio inicial do documento faz parte da fase de pré-avaliação da certificação. As informações fornecidas darão aos analistas de certificação o plano de fundo necessário para identificar quais controles e componentes do sistema estarão no escopo de sua avaliação. Este documento destina-se a servir apenas como um exemplo do que é esperado do envio inicial do documento. A documentação que você fornecer variará dependendo de como sua solução é arquiteta, implementada e gerenciada.

## <a name="penetration-test-report"></a>Relatório de Teste de Penetração

Inclua o relatório de teste de penetração completa com datas que foram concluídas nos últimos 12 meses. 
-   Esse relatório deve ser produzido a partir de testes de penetração manual, não pode ser a saída de uma ferramenta de verificação/teste automatizada.
-   Este relatório deve incluir o ambiente que dá suporte à implantação do aplicativo/adicionar juntamente com qualquer ambiente adicional que suporte a operação do aplicativo/complementos.


## <a name="system-component-inventory"></a>Inventário de Componentes do Sistema

Um inventarátório atualizado de todos os componentes do sistema usados pela infraestrutura de suporte. Isso será usado para ajudar na amostragem ao executar a fase de avaliação. Se seu ambiente incluir PaaS, será útil se você puder fornecer detalhes de todos os serviços PaaS consumidos.

**Observação:** IaaS/PaaS não teria nenhum hardware que estaria sob o controle ISVs.  Nesse caso, forneça uma lista ou captura de tela de todos os recursos viruais.

**Exemplo:**

|Nome do ativo|    Tipo de ativo| Descrição|    Fabricante|   Modelo|
|-|-|-|-|-|
|D212|  Windows  Máquina|   Máquina Virtual|    N/D| N/D|
|LT101| Laptop| Estação de trabalho|    Microsoft|  Surface 3|
|C2938| Parâmetro| Parâmetro|N/D|N/D|     
|LXM2|  Máquina Linux|  Máquina de teste|N/D|N/D|       


## <a name="software-inventory"></a>Inventário de software

Um inventário atualizado de todos os ativos de software, incluindo todos os softwares usados no ambiente no escopo, juntamente com as versões.

**Exemplo:**

|Software|  Publisher|  Versão|     Objetivo|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | Build 14393| Sistema operacional do servidor para o ambiente de produção|.
|Linux Ubuntu|  N/D|    16,04 (Xenial)| Sistema operacional do servidor em uso no DMZ.|
|ESXi|  VMWare| 6.5.0 (build 13004031)| Usado para dar suporte aos servidores virtuais.|
|Mysql (Windows)|   N/D|    8.0.2.1|    Servidor de banco de dados para armazenar o histórico de chat.|
|Tomcat|        Apache| 7.0.92| Portal do cliente.|
|IIS|   Microsoft|  10.0|   Dá suporte às APIs.|


## <a name="third-party-dependencies"></a>Dependências de terceiros

Documentação listando todas as dependências usadas pelo aplicativo/complemento com as versões em execução atuais.

**Exemplo:**

|Dependências da Web|  Versão atual em uso|
|-|-|
|JQuery|    3.5.1|
|React| 16.13.1|
|Bootstrap| 4.5.2|
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>Endereços IP públicos

Detalhando todos os endereços IP públicos e URLs usados pela infraestrutura de suporte. Isso deve incluir o intervalo de IP de tabela completa alocado para o ambiente, a menos que a segmentação adequada tenha sido implementada para dividir o intervalo em uso (será necessária uma evidência adequada de segmentação).

**Exemplo:**

|URLs|  Endereço IP|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/A (Servidor de Salto)| 40.113.200.200|


## <a name="resource-endpoints"></a>Pontos de extremidade de recurso

Endereço de ponto de extremidade do nome da API do cliente Contoso API    https://customerapi.contoso.com contoso Bot Service https://bot.contoso.com Contoso Files API   https://filesapi.contoso.com

Uma listagem completa de todos os pontos de extremidade da API usados pelo aplicativo, incluindo pontos de extremidade de recurso externo e desenvolvidos internamente. Para ajudar a entender o escopo do ambiente, forneça locais de ponto de extremidade da API em seu ambiente.

**Exemplo:**

|Nome da API|  Endpoint Address|
|-|-|
|API do Cliente Contoso|  https://customerapi.contoso.com|
|Serviço de Bot contoso|   https://bot.contoso.com|
|API de Arquivos Contoso| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>Diagrama arquitetônico

Um diagrama de arquitetura lógica que representa uma visão geral de alto nível da infraestrutura de suporte do seu aplicativo/complemento. Isso deve incluir todos os ambientes de hospedagem e a infraestrutura de suporte que suporta o aplicativo/complemento. Este diagrama DEVE representar todos os diferentes componentes do sistema de suporte no ambiente para ajudar os analistas de certificação a entender os sistemas no escopo e ajudar a determinar a amostragem. Indique também qual tipo de ambiente de hospedagem é usado; ISV Hospedado, IaaS, PaaS ou Híbrido. Onde o PaaS é usado, indique os vários serviços PaaS usados para fornecer os serviços de suporte dentro do ambiente.

![Diagrama arquitetônico](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Diagrama Flow dados

Flow diagramas detalhando o seguinte:
-   Fluxos de dados de e para o Aplicativo/Add-in (incluindo dados do cliente).
-   Fluxos de dados dentro da infraestrutura de suporte (quando aplicável)
-   Diagramas que realçam onde e quais dados são armazenados, como os dados são passados para terceiros externos (incluindo detalhes de quais terceiros) e como os dados são protegidos em trânsito sobre redes abertas/públicas e em repouso.

![Diagrama Flow dados](../media/Dataflowdiagram.png)



