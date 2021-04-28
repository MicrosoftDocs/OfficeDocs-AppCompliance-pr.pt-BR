---
ms.author: oromalle
title: Guia de Envio de Certificação do Microsoft 365
author: orionomalley
description: Exibição granular do Guia de Envio de Certificação do Microsoft 365
keywords: equipes de certificação de aplicativos Microsoft 365 security compliance m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 4d0f09b3a1dd6bde7022e93d08a491e2855d90a7
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/28/2021
ms.locfileid: "52070799"
---
# <a name="microsoft-365-certification-submission-guide"></a>Guia de Envio de Certificação do Microsoft 365

**Neste artigo:**
- [Introdução](#introduction)
- [Pré-requisitos](#prerequisites) 
- [Atualizações de especificação de certificação do Microsoft 365](#microsoft-365-certification-specification-updates)
- [Escopo de certificação](#certification-scope)
- [Processo de Certificação](#certification-process)
- [Evidências de conformidade](#compliance-evidence) 
- [Envio inicial de documento](#initial-document-submission) 
- [Atividades de coleta e avaliação de evidências](#evidence-collection-and-assessment-activities)
- [Critérios de certificação](#app-certification-criteria)
- [Segurança de Aplicativo](#application-security)
- [Segurança Operacional](#operational-security) 
- [Segurança e privacidade de tratamento de dados](#data-handling-security-and-privacy)
- [Revisão de estruturas de conformidade externa opcionais](#optional-external-compliance-frameworks-review)
- [Apêndice A](#appendix-a)
- [Apêndice B](#appendix-b) 
- [Apêndice C](#appendix-c) 
- [Apêndice D](#appendix-d) 
- [Apêndice E](#appendix-e) 
- [Apêndice F](#appendix-f) 
- [Apêndice G ](#appendix-g)
- [Saiba mais](#learn-more) 
- [Glossário](#glossary) 


## <a name="introduction"></a>Introdução

Parte do programa de Conformidade de Aplicativos do Microsoft 365, a Certificação do Microsoft 365 oferece garantia e confiança às organizações corporativas de que os dados e a privacidade são adequadamente protegidos e protegidos ao integrar aplicativos/complementos de desenvolvedores de terceiros à plataforma do Microsoft 365. Aplicativos e complementos que passam na validação serão designados **Microsoft 365 Certified** em todo o ecossistema do Microsoft 365. 

Ao participar do programa de Certificação do Microsoft 365, você está concordando com esses termos complementares e em conformidade com qualquer documentação que acompanha a sua participação no programa de Certificação do Microsoft 365 com a Microsoft Corporation ("Microsoft", "nós", "nós" ou "nosso"). Você representa e nos garante que tem autoridade para aceitar estes termos complementares de Certificação do Microsoft 365 em nome de si mesmo, de uma empresa e/ou de outra entidade, conforme aplicável. Podemos alterar, alterar ou encerrar esses termos suplementares a qualquer momento. Sua participação contínua no programa de Certificação do Microsoft 365 após qualquer alteração ou alteração significa que você concorda com os novos termos complementares. Se você não concordar com os novos termos suplementares ou se encerrarmos esses termos suplementares, você deve parar de participar do programa de Certificação do Microsoft 365.

Este documento destina-se a ISVs (Fornecedores de Software Independentes) para fornecer informações sobre o processo de Certificação do Microsoft 365, pré-requisitos para iniciar o processo e detalhes de controles de segurança específicos que os ISVs devem ter no local.  Informações gerais do programa de Conformidade de Aplicativos do Microsoft 365 podem ser encontradas na página Programa de Conformidade de [Aplicativos](https://docs.microsoft.com/microsoft-365-app-certification/overview)do Microsoft 365. 

> [!IMPORTANT]
> Atualmente, a Certificação do Microsoft 365 é limitada:
>* Aplicativos do Microsoft Teams (Guias, Bots etc.) .
>* Aplicativos/Complementos do Sharepoint
>* Complementos do Office (Word, Excel, PowerPoint, Outlook, Project, OneNote)

## <a name="prerequisites"></a>Pré-requisitos

### <a name="publisher-attestation"></a>Atestado do Publisher

Antes de receber o processo de Certificação do Microsoft 365, você deve ter concluído o Atestado do Publisher. No entanto, você pode iniciar o processo de Certificação do Microsoft 365 antes de concluir o Atestado do Publisher.  

### <a name="read-the-microsoft-365-certification-specification"></a>Ler a Especificação de Certificação do Microsoft 365

A Microsoft recomenda que todos os ISVs (Fornecedor de Software Independente) leiam essa Especificação de Certificação do Microsoft 365 em sua totalidade para garantir que todos os controles aplicáveis sejam atendidos pelo ambiente no escopo e pelo aplicativo/complemento. Isso ajudará a garantir um processo de avaliação suave.

## <a name="microsoft-365-certification-specification-updates"></a>Atualizações de especificação de certificação do Microsoft 365 

Atualizações para a especificação de Certificação do Microsoft 365 são previstas aproximadamente a cada seis a doze meses. Essas atualizações podem introduzir novos domínios de segurança de destino e/ou controles de segurança. As atualizações serão baseadas em comentários do desenvolvedor, alterações no cenário de ameaças e para aumentar a linha de base de segurança do programa à medida que ele amadurece. 

Os ISVs que já iniciaram a avaliação de Certificação do Microsoft 365 podem continuar a avaliação com a versão da Especificação de Certificação do Microsoft 365 que foi válida quando a avaliação foi iniciada. Todos os novos envios, incluindo a recertificação anual, serão necessários para serem avaliados em relação à versão publicada.

> [!NOTE]
> Você não precisa estar em conformidade com todos os controles dentro desta Especificação de Certificação do Microsoft 365 para receber uma certificação. No entanto, os limites de passagem (que não serão divulgados) estão em uso para cada um dos domínios de segurança discutidos nesta Especificação de Certificação do Microsoft 365. Alguns controles serão classados como um "**Falha** Difícil ", o que significa que a falta desses controles de segurança resultará em uma avaliação com falha. 

## <a name="certification-scope"></a>Escopo de certificação

O **ambiente no escopo** é o ambiente que dá suporte à entrega do código do aplicativo/do add-in e dá suporte a todos os sistemas back-end com os que o aplicativo/add-in possa estar se comunicando. Quaisquer ambientes conectados adicionais também serão incluídos no escopo, a menos que a segmentação adequada esteja no local e os ambientes conectados não poderão afetar a segurança do ambiente no escopo. Quaisquer ambientes de recuperação de desastres também precisarão ser incluídos no escopo da avaliação, pois esses ambientes seriam necessários para cumprir o serviço caso algo acontecesse com o ambiente principal.  O termo **componentes do sistema** no escopo fazem referência a TODOS os dispositivos   e sistemas usados no ambiente no escopo.  Os componentes no escopo incluem, mas não estão limitados a:
* Os aplicativos Web.
* Servidores.
* Firewalls (ou equivalentes).
* Alterna.
* Balanceadores de carga.
* Infraestrutura virtual.
* Portais de gerenciamento da Web do provedor de nuvem 

> [!IMPORTANT]
> O ambiente no escopo deve ter um DMZ e o ambiente de suporte do aplicativo/add-in deve ser segmentado dos sistemas corporativos internos e ambientes corporativos, limitando assim o escopo das atividades de avaliação apenas para os sistemas no escopo. Os analistas de certificação validam técnicas de segmentação durante a avaliação, juntamente com a revisão de relatórios de teste de penetração, que devem incluir testes para validar a eficácia de quaisquer técnicas de segmentação em uso.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>Infraestrutura como serviço (IaaS), Plataforma como Serviço (PaaS) e Software como serviço (SaaS) 
Onde o IaaS e/ou PaaS é usado para dar suporte à infraestrutura da entrega de código do aplicativo ou do complemento em revisão, o provedor da plataforma cloud será responsável por alguns dos controles de segurança avaliados durante todo o processo de certificação. Portanto, os analistas de certificação precisarão receber uma verificação externa independente das práticas recomendadas de segurança pelo provedor de plataformas de nuvem por meio de relatórios de conformidade externos, como o AOC (Atestado de Conformidade do [PCI DSS),](bookmark://pci-dss)os relatórios   ISO27001 ou [SOC 2](bookmark://soc-2)   Type II. 

O Apêndice F fornece detalhes sobre quais controles de segurança provavelmente serão aplicáveis com base nos seguintes tipos de implantação e com base em se o aplicativo/add-in exfiltra os dados do M365 ou não: 
* ISV hospedado 
* IaaS hospedado 
* PaaS/Serverless Hospedado 
* Híbrida Hospedada 
* Hospedado compartilhado 

Onde o IaaS ou o PaaS é implantado, você precisará fornecer evidências do ambiente que está sendo hospedado nesses tipos de implantação.

### <a name="sampling"></a>Amostragem

As solicitações de evidências em suporte à avaliação de certificação devem ser baseadas em um exemplo dos componentes do sistema no escopo em consideração de diferentes sistemas operacionais, função primária do dispositivo e tipos de dispositivo diferentes. Um exemplo adequado será selecionado no início do processo de certificação. A tabela a seguir deve ser usada como um guia sobre o tamanho da amostra:

|Tamanho da população              | Amostra                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4 |

> [!NOTE]
>Se discrepâncias são identificadas entre dispositivos incluídos no exemplo inicial, o tamanho da amostra pode ser aumentado durante a avaliação. 

## <a name="certification-process"></a>Processo de Certificação

Antes de iniciar o processo de certificação, você precisaria ter iniciado ou concluído com êxito o Atestado do Publisher. Suas respostas de atestado serão usadas em suporte ao processo de Certificação do Microsoft 365 e prosseguirão da seguinte forma: 

1. Revise sua documentação de Atestado do Publisher para garantir o alinhamento com seu ambiente atual 
2. Solicitar progresso para a Certificação do Microsoft 365 por email <AppCert@microsoft.com> 
3. Os analistas de certificação abrirão um diálogo antes de iniciar o processo de Certificação do Microsoft 365   
4. Enviar o [envio inicial do documento](#initial-document-submission)
5. O analista de certificação fornecerá uma listagem de controles para os quais as evidências são necessárias, o que inicia formalmente o processo de Certificação do Microsoft 365
6. Enviar evidências que demonstram que todos os controles de Certificação do Microsoft 365 no escopo foram atendidos em uma janela de 60 dias para concluir a Certificação do Microsoft 365 

> [!IMPORTANT]
> **Período de tempo de envio:** É previsto que, em média, o processo de avaliação deve levar 15 dias, desde que você possa responder às solicitações de evidência em tempo hábil. A Microsoft recomenda que você verifique se esse guia de envio de certificação foi lido e tenha certeza de que você pode atender aos controles definidos nele e que você pode fornecer evidências suficientes antes de iniciar o processo de certificação. Ao iniciar o processo de certificação, um máximo de 60 dias é permitido para concluir a avaliação, caso contrário, as evidências já coletadas se tornam eslavas. Se, após o período de 60 dias, uma avaliação bem-sucedida não for atingida, o envio será emitido como uma falha e o processo deverá ser reapurado. Se uma falha for emitida devido à falha ao atender à Especificação de Certificação do Microsoft 365 ou porque o período de tempo de 60 dias é atingido e evidências suficientes não são fornecidas, os resultados com falha não serão divulgados pela Microsoft. 

## <a name="compliance-evidence"></a>Evidências de conformidade

Embora não seja necessário, se você estiver em conformidade com outras estruturas de segurança externas, poderá optar por usar essas certificações para satisfazer alguns dos controles de Certificação do Microsoft 365. Os analistas de certificação revisarão a cobertura de escopo e controle de segurança de quaisquer estruturas de segurança externa com suporte para determinar quais controles podem ser excluídos da avaliação de Certificação do Microsoft 365, fornecendo o escopo das estruturas de segurança externas incluem os ambientes no escopo da avaliação de Certificação do Microsoft 365. 

Os analistas de certificação tentarão alinhar as estruturas de segurança externa existentes à especificação de Certificação do Microsoft 365. No entanto, se a documentação de suporte não puder fornecer garantias de que os controles de Certificação do Microsoft 365 foram avaliados como parte da auditoria/avaliação de estruturas de segurança externas, você precisará fornecer evidências adicionais sobre a adoção desses controles. 

Atualmente, as estruturas de segurança externas que podem ser usadas no suporte à avaliação de Certificação do Microsoft 365 incluem:

*  [ISMS](#isms) / [IEC](#iec) - Especificação IS0/IEC 27001 
*  [PCI DSS](#pci-dss)
*  [SOC 2](#soc-2)

A documentação deve demonstrar adequadamente que o ambiente no escopo para a Certificação do Microsoft 365 foi incluído no escopo dessas estruturas de segurança externas. A validação dessas estruturas de segurança será atendida aceitando evidências de certificações válidas conduzidas por empresas de terceiros externos confiáveis. Essas empresas confiáveis devem ser membros de entidades de credenciamento internacionais para programas de conformidade relevantes.Consulte Padrões de certificação e conformidade [ISO](https://www.iso.org/certification.html) para ISO 27001 e Avaliadores de Segurança [Qualificados](https://www.pcisecuritystandards.org/assessors_and_solutions/qualified_security_assessors) (QSA) para PCI DSS. 

A tabela a seguir destaca a documentação necessária pelos analistas de certificação como parte desse processo de validação:

| **Standard** | **Requisitos** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Será necessária uma versão pública da **Declaração de** Aplicabilidade (SOA) e uma cópia do certificado ISO 27001 emitido.  O SOA resume sua posição em cada um dos 114 controles de segurança de informações e será usado para identificar se há exclusão de controles que não são detalhados satisfatoriamente no certificado ISO 27001. Se isso não puder ser determinado revendo a versão pública do SOA, o analista poderá precisar de acesso ao SOA completo se a ISO 27001 for usada para validar alguns dos controles de Especificação de Certificação do Microsoft 365.  Além de validar o escopo das atividades de avaliação da ISO 27001, os analistas também confirmarão a validade da empresa de auditoria, conforme descrito acima.|
|**[PCI DSS](#pci-dss)**| Um documento AOC (Atestado de Conformidade) de Nível **1** válido deve ser fornecido identificando claramente os componentes do aplicativo e do sistema no escopo.  Um AOC de autoavaliação **não será** aceito como evidência das práticas recomendadas de segurança de reunião. O AOC será usado para determinar quais dos controles de Especificação de Certificação do Microsoft 365 foram avaliados e confirmados como parte da avaliação do PCI DSS.|
|**[SOC 2](#soc-2)**|O relatório **SOC 2 (Tipo I** ou Tipo II) deve ser atual (emitido nos últimos 15 meses e o período declarado iniciado nos últimos 27 meses) para ser usado como evidência de conformidade com qualquer um dos controles de avaliação dentro desta Especificação de Certificação do Microsoft 365.|


## <a name="microsoft-365-certification"></a>Certificação do Microsoft 365

As estruturas de segurança externa com suporte podem ser usadas como evidência de reunião de alguns dos controles de Certificação do Microsoft 365. Antes que as estruturas de segurança externas possam ser consideradas, os analistas de certificação revisarão a cobertura de escopo e controle de segurança da estrutura de segurança externa usando a documentação enviada acima. 

Os apêndices a seguir podem ser usados para identificar onde possíveis lacunas entre a estrutura de segurança externa e a especificação de Certificação do Microsoft 365 existem da seguinte forma: 

|**Framework** | **Considerações adicionais** |
|-------------- | --------------------|
|ISO 27001| [**Apêndice C**](#appendix-c): Coleção Evidence – Deltas para ISO 27001.|
|PCI DSS | [**Apêndice D**](#appendix-d): Coleção Evidence – Deltas para PCI DSS.|
|SOC 2| [**Apêndice E**](#appendix-e): Coleção Evidence – Deltas para SOC 2.|

> [!NOTE]
> Embora os padrões/estruturas de segurança externos mencionados acima possam ser enviados como prova para atender a alguns dos controles de Certificação do Microsoft 365, passar a Certificação do Microsoft 365 não significa que você passará com êxito em uma auditoria em relação a esses padrões/estruturas. A Especificação de Certificação do Microsoft 365 é apenas um pequeno subconjunto desses padrões/estruturas de segurança que permite que a Microsoft obtenha um nível de garantia em referência à sua postura de segurança.

## <a name="initial-document-submission"></a>Envio inicial de documento

O envio inicial do documento ajudará os analistas de certificação a executar o escopo e a determinar o que estará no escopo de sua avaliação. Depois disso, você será obrigado a enviar documentação de suporte e evidências usadas para realizar a avaliação. Seu envio inicial deve incluir as informações especificadas abaixo:

| **Visão &nbsp; geral da documentação**     |   **Detalhes da documentação**  |
| -------------------------| -----------------------------|
|**Descrição do aplicativo/do complemento** | Uma descrição da finalidade e funcionalidade do aplicativo/add-in. Isso deve fornecer ao analista de certificação uma boa compreensão de como o aplicativo/complemento funciona e qual é o uso pretendido
|**Relatório de Testes de Penetração** |Um relatório de teste de penetração concluído nos últimos 12 meses. Este relatório deve incluir o ambiente que dá suporte à implantação do aplicativo/adicionar juntamente com qualquer ambiente adicional que suporte a operação do aplicativo/add-in. **Observação:** se você não fizer testes anuais de penetração, poderá optar por fazê-los por meio do processo de certificação.|
|**Diagramas de arquitetura**|Um diagrama de arquitetura lógica que representa uma visão geral de alto nível da infraestrutura de suporte do seu aplicativo/complemento. Isso deve incluir **todos os ambientes** de hospedagem e a infraestrutura de suporte que suporta o aplicativo/complemento. Este diagrama DEVE representar todos os diferentes componentes do sistema de suporte no ambiente para ajudar os analistas de certificação a entender os sistemas no escopo e ajudar a determinar a amostragem. Indique também qual tipo de ambiente de hospedagem é usado; ISV Hospedado, IaaS, PaaS ou Híbrido. **Observação:** Onde o SaaS é usado, indique os vários serviços SaaS usados para fornecer os serviços de suporte dentro do ambiente.|
|**Public Footprint** | Detalhando **todos os** endereços IP públicos e URLs usados pela infraestrutura de suporte. Isso deve incluir o intervalo de IP de tabela completa alocado para o ambiente, a menos que a segmentação adequada tenha sido implementada para dividir o intervalo em uso (evidências adequadas de segmentação serão necessárias)|
|**Diagramas de fluxo de dados** |Diagramas de fluxo detalhando o seguinte:
||&#x2713; M365 Data flui de e para o Aplicativo/Add-in (incluindo [EUII](#euii) e [OII](#oii) ).|
||&#x2713; M365 Data flui dentro da infraestrutura de suporte (quando aplicável)|
||&#x2713; Diagramas que realçam onde e quais dados são armazenados, como os dados são passados para terceiros externos (incluindo detalhes de quais terceiros) e como os dados são protegidos em trânsito sobre redes públicas e abertas e em repouso.|
|**Detalhes do ponto de extremidade da API**| Uma listagem completa de todos os pontos de extremidade da API usados pelo aplicativo. Para ajudar a entender o escopo do ambiente, forneça locais de ponto de extremidade da API em seu ambiente.                                
|**Permissões de API da Microsoft**| Forneça documentação detalhando **TODAS** as APIs da Microsoft que são usadas juntamente com quais permissões estão sendo solicitadas para que o aplicativo/add-in funcionem juntamente com uma justificativa para as permissões solicitadas|
|**Tipos de armazenamento de dados** |Armazenamento de dados e manipulação de documentos que descrevem:|
||&#x2713; Até que ponto seus clientes M365 Data [EUII](#euii) e [OII](#oii) estão sendo recebidos e armazenados|
||&#x2713; O período de retenção de dados.|
||&#x2713; por que o cliente M365 Data está sendo capturado.|
||&#x2713; onde o cliente M365 Data é armazenado (deve ser incluído nos diagramas de fluxo de dados fornecidos acima).|
|**Confirmação de conformidade**|Documentação de suporte para estruturas de segurança externas incluídas no envio de Atestado do Publisher ou a serem consideradas ao analisar controles de Certificação do Microsoft 365. Atualmente, os três seguintes são suportados:|
||&#x2713; atestado de conformidade (AOC) pci [DSS.](#pci-dss)|
||&#x2713; relatórios [SOC 2](#soc-2) Tipo I/Type II.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - IEC 1S0/IEC 27001 Declaração de Aplicabilidade (SoA) e Certificação.|
|**Dependências da Web**|Documentação listando todas as dependências usadas pelo aplicativo/complemento com as versões em execução atuais.|
|**Inventário de software**|Um inventário de software atualizado que inclui todos os softwares usados no ambiente no escopo juntamente com as versões.|
|**Inventário de Hardware**| Um inventário de hardware atualizado usado pela infraestrutura de suporte. Isso será usado para ajudar na amostragem ao executar a fase de avaliação. Se seu ambiente incluir o PaaS, forneça detalhes dos serviços consumidos.|

## <a name="evidence-collection-and-assessment-activities"></a>Atividades de coleta e avaliação de evidências

Por meio de atividades robustas de coleta e avaliação de evidências, os analistas de certificação poderão avaliar sua postura de segurança para obter um nível adequado de garantia de segurança de dados e adesão aos controles de Especificação de Certificação do Microsoft 365. Os analistas de certificação alcançarão isso da seguinte forma: 

**Coleção Evidence**

* Documentação inicial, realçada na seção [Envio de Documentação](#initial-document-submission) Inicial acima 
* Documentos de política 
* Processar documentos 
* Configurações do sistema 
* Alterar tíquetes 
* Alterar registros de controle 
* Relatórios do sistema

Vários métodos serão usados para coletar as evidências necessárias para concluir o processo de avaliação.  Essa coleção de evidências pode estar na forma de: 
* Documentos 
* Capturas de tela 
* Entrevistas 
* Compartilhamento de tela 

As técnicas de coleta de evidências usadas serão determinadas durante o processo de avaliação. 

**Atividades de Avaliação**

Os analistas de certificação analisarão as evidências fornecidas para determinar se você atendeu adequadamente aos controles dentro desta Especificação de Certificação do Microsoft 365. 

Sempre que possível e para reduzir o tempo necessário para concluir a avaliação, toda ou qualquer documentação detalhada no [Envio](#initial-document-submission)Inicial de Documentação deve ser fornecida   com antecedência.

Os analistas de certificação primeiro revisarão as evidências fornecidas do envio da documentação inicial e as informações de Atestado do Publisher para identificar linhas apropriadas de investigação, tamanho de amostragem e a necessidade de obter mais evidências conforme detalhado acima.  Os analistas de certificação analisarão todas as informações coletadas para tirar conclusões sobre como e se você está a atender aos controles dentro desta Especificação de Certificação do Microsoft 365. 

## <a name="app-certification-criteria"></a>Critérios de certificação de aplicativos

Seu aplicativo, a infraestrutura de suporte e a documentação de suporte serão avaliados nos seguintes domínios de segurança:

1. [**Segurança de Aplicativo**](#application-security)
1. [**Segurança Operacional / Implantação Segura**](#operational-security)
1. [**Segurança e privacidade de tratamento de dados**](#data-handling-security-and-privacy)
1. [**Revisão opcional da Estrutura de Conformidade Externa**](#optional-external-compliance-frameworks-review)

Cada um desses domínios de segurança inclui controles de chave específicos que abrangem um ou mais requisitos específicos que serão avaliados como parte do processo de avaliação. Para garantir que a Certificação do Microsoft 365 seja inclusiva para desenvolvedores de todos os tamanhos, cada um dos quatro domínios de segurança é avaliado usando um sistema de pontuação para determinar uma pontuação geral de cada um dos domínios. As pontuações para cada um dos controles de Certificação do Microsoft 365 são alocadas entre 1 (baixo) e 3 (alto) com base no risco percebido de que o controle não está sendo atendido. Cada um dos quatro domínios de segurança terá uma marca percentual mínima a ser considerada uma passagem. Determinados elementos dessa especificação incluem alguns critérios de falha automática:

- Permissões de API que não seguem o princípio de privilégio mínimo (PoLP).  
- Nenhum relatório de teste de penetração quando necessário.
- Sem defesas anti-malware
- A autenticação multifafação não está sendo usada para proteger o acesso administrativo.  
- Sem processos de correção.  
- Nenhuma notificação de [privacidade do RGPD](#gdpr) adequada.  

## <a name="application-security"></a>Segurança de Aplicativo

O domínio de segurança do aplicativo se concentra nas três áreas a seguir: 
* Validação de permissão GraphAPI 
* Verificações de Conectividade Externa
* Teste de Segurança de Aplicativo 

**Validação de permissão GraphAPI**

A validação de permissão GraphAPI é realizada para validar que o aplicativo/add-in não solicita permissões muito permissivas. Isso é realizado verificando manualmente quais permissões são solicitadas. Os analistas de certificação fazem referência cruzada a essas verificações em relação ao envio de Atestado do Publisher e avaliam o nível de acesso que está sendo solicitado para garantir que as práticas de "privilégio mínimo" sejam atendidas. Onde os analistas de certificação acreditam que essas práticas de "privilégio mínimo" não estão sendo atendidas, os analistas de certificação terão uma discussão aberta com você para validar a justificativa comercial para as permissões que estão sendo solicitadas. Quaisquer discrepâncias em relação ao envio de Atestado do Publisher encontrados durante esta revisão também receberão comentários para que o Atestado do Publisher possa ser atualizado. 

**Verificações de Conectividade Externa**

Como parte da avaliação, um Analista realizará uma leve caminhada pela funcionalidade de aplicativos para identificar conexões fora do M365.  Todas as conexões que não são identificadas como sendo da Microsoft ou conexões diretas com seu serviço serão sinalizadas e discutidas durante a avaliação.

**Teste de Segurança de Aplicativo**

Uma revisão adequada dos riscos associados ao seu aplicativo/add-in e ao ambiente de suporte é essencial para fornecer aos clientes garantia na segurança do aplicativo/do add-in. O teste de segurança do aplicativo na forma de teste de penetração DEVE ser realizado se seu aplicativo tiver alguma conectividade com qualquer serviço que não seja publicado pela Microsoft. Se seu aplicativo operar autônomo sem conectividade com nenhum serviço ou back-end que não seja da Microsoft, o teste de penetração não será necessário.


### <a name="penetration-testing-scope"></a>Escopo de teste de penetração

As atividades  de teste de penetração DEVEM incluir o ambiente que dá suporte à implantação do aplicativo/add-in (por exemplo, onde o código do aplicativo/add-in está hospedado, que normalmente será o recurso dentro do arquivo de manifesto) juntamente com qualquer ambiente adicional que suporte a operação do aplicativo/add-in (por exemplo, se o aplicativo/add-in falar com outros aplicativos Web fora do Microsoft 365).  Ao definir o escopo, é necessário ter cuidado para garantir que todos os sistemas ou ambientes "conectados" que possam afetar a segurança do ambiente no escopo também sejam incluídos em TODAS as atividades de teste de penetração. 

Onde as técnicas são usadas para segmentar os ambientes no escopo de outros ambientes, as atividades de teste de penetração DEVEM validar a eficácia das técnicas de segmentação. Isso deve ser detalhado no relatório de teste de penetração. 
 

### <a name="testspecification"></a>Especificação de teste 

|Testar | Controles |
|-------|-----------|
|**Teste de penetração**| Testes de penetração de aplicativo e infraestrutura **DEVEM** ser realizados anualmente (a cada 12 meses) e conduzidos por uma empresa independente confiável. A correção de vulnerabilidades críticas  e de alto risco identificadas deve ser concluída dentro de um mês após a conclusão do teste de penetração ou mais cedo, dependendo do processo de correção documentado.O espaço externo completo (endereços IP, URLs, pontos de extremidade da API, etc.) DEVE ser incluído no escopo do teste de penetração e deve ser documentado no relatório de teste de penetração. O espaço externo completo (endereços IP, URLs, pontos de extremidade da API, etc.) **DEVE** ser incluído no escopo do teste de penetração e deve ser documentado no relatório de teste de penetração.                                                                                                                                                                           O teste de penetração de aplicativo Web DEVE incluir todas as classes de vulnerabilidade; por exemplo, o CWE OWASP Top 10 ou SANS Top 25 mais atual.                                                                                                                                                                                O reteste de vulnerabilidades identificadas pela empresa de teste de penetração não é necessário — a  correção e a autoavaliação são suficientes, no entanto, evidências adequadas para demonstrar a correção suficiente DEVEM ser fornecidas durante a avaliação.|

### <a name="application-security-testing-reportreview"></a>Revisão do Relatório de Teste de Segurança de Aplicativos

Os relatórios de teste de penetração serão revisados para garantir que não haja vulnerabilidades que atendem aos seguintes critérios de **falha automática:**

* Presença de um sistema operacional sem suporte. 

* Presença de contas administrativas padrão, enumeradas ou previsíveis.

* Presença de SQL de injeção.*

* Presença de script entre sites.*

* Presença de vulnerabilidades atravessadas de diretório (caminho de arquivo).*

* Presença de vulnerabilidades HTTP, por exemplo, divisão de resposta de cabeçalho, roubo de solicitação e ataques de Desync.*

* Presença de divulgação de código-fonte (incluindo [LFI](#lfi)).*

* Qualquer pontuação crítica ou alta, conforme definido pelas diretrizes de gerenciamento de patch CVSS.

* Qualquer vulnerabilidade técnica significativa que possa ser prontamente explorada para comprometer uma grande quantidade de EUII ou OUI.

*Independentemente das vulnerabilidades pontuação do CVSS

> [!IMPORTANT]
>Os relatórios devem ser capazes de fornecer garantia suficiente de que tudo o que está detalhado na seção Especificação de Teste de Segurança de Aplicativo pode ser demonstrado.


### <a name="penetration-testing-requirements-and-cost"></a>Requisitos e custo de testes de penetração

Para ISVs que atualmente não se envolvem em testes de penetração, o teste de penetração está incluído na Certificação do Microsoft 365. A Microsoft organizará e cobrirá o custo de um teste de penetração por até 12 dias de teste manual. Os custos dos testes de penetração são calculados com base no número de dias necessários para testar o ambiente. Quaisquer despesas superiores a 12 dias de teste serão de responsabilidade do ISV. O ISV também será responsável por demonstrar que as vulnerabilidades identificadas no teste de penetração foram remediadas antes da certificação ser concedida, mas não precisam produzir um relatório limpo.

Depois que um teste de penetração é organizado, o ISV é responsável pelas taxas associadas à remarcação e cancelamentos da seguinte forma:

| **Escala de tempo de taxa de remarcação** | **Proporção a pagar** |
|------------------|------------------------|
| A solicitação de nova agendamento recebeu mais de 30 dias antes da data de início agendada. | 0% a ser pago |
| A solicitação de nova agendamento recebeu de 8 a 30 dias antes da data de início agendada. | 25% a pagar |
| Nova solicitação de agendamento recebida dentro de 2 a 7 dias antes da data de início agendada com uma data de re reserva firme.| 50% a pagar |
| A solicitação de nova agendamento recebeu menos de 2 dias antes da data de início. | 100% a pagar |

| **Escala de Tempo da Taxa de Cancelamento** | **Proporção a pagar** |
|------------------|------------------------|
| A solicitação de cancelamento recebeu mais de 30 dias antes da data de início agendada. | 25% a pagar |
| Solicitação de cancelamento recebida de 8 a 30 dias antes da data de início agendada. | 50% a pagar |
| Solicitação de cancelamento recebida dentro de 7 dias antes da data de início agendada. | 90% a pagar |

## <a name="operational-security"></a>Segurança Operacional

Esse domínio mede o alinhamento dos processos de infraestrutura e implantação de suporte do seu aplicativo com as práticas recomendadas de segurança.

### <a name="test-specification"></a>Especificação de teste

|Testar | Controles |
| ------------------------|------------------------------ |
| **Proteção contra Malware** | Você deve implantar mecanismos de proteção contra malware em todos os sistemas no escopo que são comumente afetados por malware. Esses mecanismos de proteção podem incluir o uso de software antivírus ou técnicas de controle de aplicativos que protegem contra malware. Quando o software antivírus ou o controle de aplicativo é usado, ele deve atender aos seguintes critérios.                                                                                            O antivírus (incluindo também produtos anti-malware) DEVE atender ao seguinte: |
||&#x2713; software antivírus está em execução em todos os componentes do sistema no escopo.|
||&#x2713; software antivírus é mantido atualizado (dentro de 30 dias).|
||&#x2713; assinaturas antivírus são mantidas atualizadas (dentro de 1 dia).|
||&#x2713; verificação no acesso e/ou verificações periódicas com notificações devem ser configuradas.  Onde a verificação ao acessar é  usada, verificações semanais TAMBÉM DEVEM ser configuradas, no entanto, se a verificação no acesso não estiver configurada, a verificação diária deve ser configurada.|
||&#x2713; software antivírus **DEVE** ser configurado da seguinte forma.|
||&emsp;&#x25fc; bloquear o malware suspeito.|
||&emsp;&#x25fc; malware suspeito de quarentena.|
||&emsp;&#x25fc; fornecer um alerta sobre malware suspeito.|
||&#x2713; software antivírus **DEVE** ser configurado para registrar todas as atividades.
||&#x2713; políticas e procedimentos **devem** estar em prática para promover práticas anti-malware fortes.|
||ou|
||Os controles de aplicativo DEVEM ser configurados em todo o sistema no escopo para atender ao seguinte:|
||&#x2713; Todos os aplicativos permitidos para execução em componentes do sistema no escopo devem ser formalmente aprovados pela organização..|
||&#x2713; A organização deve manter uma lista completa de aplicativos aprovados com justificativa comercial para o aplicativo.|
||&#x2713; mecanismos de controle de aplicativos específicos DEVEM estar totalmente documentados: ou seja, locais em branco; assinatura de código, etc.|
||&#x2713; Controle de aplicativo deve ser configurado como documento.|
||&#x2713; processo documentado para aprovações de aplicativo deve estar no local e auditável.|
|**Gerenciamento de patches**|Você **DEVE** ter políticas e procedimentos de correção documentados no local que garantem que a correção seja realizada em tempo hábil. Um processo robusto **DEVE** estar em vigor que identifica, classifica e remenda novas vulnerabilidades de segurança com base nas Pontuações recomendadas de Classificação de Risco do CVSS V3.1 ou taxonomia de pontuação equivalente: 
||**Pontuações recomendadas de classificação de** risco (intervalo de pontuação base cvss v3.1)|
||&emsp;**Crítico:** 9,0 - 10,0.|
||&emsp;**Alto**: 7,0 - 8,9.|
||&emsp;**Médio**: 4,0 - 6,9.|
||&emsp;**Baixo**: 0,1 - 3,9.|
||&emsp;**Nenhum**: 0,0 |
|| **IMPORTANTE**: O processo para identificar novas vulnerabilidades deve ser robusto o suficiente para permitir a identificação e correção de vulnerabilidades em linha com a janela de correção documentada que você definiu. |
|**Patching**|&#x2713; Quaisquer problemas críticos, altos  ou médios de risco DEVEM ser corrigidas em um período pré-determinado e documentado decidido pelo ISV, que representa a janela mínima de tempo antes que o problema seja **resolvido.**  Embora a janela de correção seja definida pelo ISV, a janela precisa estar dentro de um período de tempo razoável. Por exemplo, três meses para corrigir uma vulnerabilidade Crítica não seria razoável e, portanto, rejeitado na sua avaliação de Certificação do Microsoft 365.|
||&#x2713; políticas e procedimentos que detalham como  a correção deve ser realizada e **DEVEM** incluir todos os sistemas operacionais, aplicativos e componentes de software aplicáveis usados no ambiente. Isso inclui quaisquer dependências da Web usadas no aplicativo/complemento.|
||&#x2713; Componentes de software e sistemas operacionais não mais suportados pelo fornecedor **não** devem ser usados no ambiente. As políticas **de** suporte devem estar em funcionamento para garantir que os componentes de software/sistemas operacionais sem suporte sejam removidos do ambiente e um processo para identificar quando os componentes de software vão para o fim da vida útil deve estar no local.|
|**Verificação de vulnerabilidade**|A verificação de vulnerabilidade deve incluir:|
||&#x2713; verificação de vulnerabilidade externa trimestral realizada  em relação ao espaço público COMPLETO do ambiente no escopo (URLs e endereços IP para verificação de infraestrutura e aplicativo Web).|
||&#x2713; verificação trimestral de vulnerabilidade interna autenticada realizada em componentes do sistema no escopo (não para PaaS).|
||&#x2713; Uma política de correção de  vulnerabilidade documentada deve estar em uso para garantir que os componentes do sistema estão livres de vulnerabilidades conhecidas, detalhando a linha do tempo para corrigir vulnerabilidades com base em suas pontuações de classificação de risco recomendadas do CVSS **** definidas (consulte acima).|
||&#x2713; As verificações contínuas  devem ser realizadas até que as vulnerabilidades classificadas de risco identificadas sejam remediadas dentro da linha do tempo necessária, conforme definido pela política de correção do ISV. Embora a linha do tempo de correção seja definida pelo ISV, a janela precisa estar dentro de um prazo razoável. Por exemplo, três meses para correção de uma vulnerabilidade crítica não seria razoável e, portanto, rejeitada na sua avaliação de Certificação do Microsoft 365.|
|**Firewalls**|Sua infraestrutura de suporte deverá ter um firewall (ou equivalente onde os serviços de Nuvem estão sendo consumidos) configurado da seguinte forma:|
||&#x2713; deve **ser** instalado em todas as conexões da Internet expondo os ambientes no escopo.|
||&#x2713; **deve** ser instalado entre todas as DMZs (Zonas Desmilitarizadas) e quaisquer redes confiáveis.|
||&#x2713; Todo o acesso **público DEVE** ser encerrado em uma DMZ (Zona Desmilitarizada). |
||&#x2713; As credenciais administrativas **padrão devem** ser alteradas antes da instalação em ambientes de produção.|
||&#x2713; Todo o tráfego permitido por firewalls no escopo (em qualquer direção) **DEVE** passar por um processo de aprovação e todos os protocolos, serviços e portas devem ser documentados com justificativas comerciais.|
||&#x2713; regras de Firewall devem ser configuradas em linha com as regras permitidas documentadas.|
||&#x2713; criptografia forte, em linha com **o Apêndice B**, **DEVE** ser habilitada em todas as interfaces administrativas de firewall que não sejam de console.|
||&#x2713; MFA (autenticação multifatória) **DEVE** estar habilitada para acesso administrativo do firewall.|
||&#x2713; **Deverão** ser realizadas pelo menos a cada seis meses.|
||A análise de certificação revisará a base de regras de firewall para a presença de fluxos de tráfego de saída para terceiros potenciais para validar o compartilhamento de dados externo de terceiros.  |
||**WaF (Web Application Firewall)**. O crédito adicional será dado se uma waf ou medida equivalente for implantada para ajudar a proteger contra ameaças e vulnerabilidades de aplicativos Web. Se presente, as políticas e os procedimentos de suporte **devem** estar no local juntamente com as seguintes configurações waf: |
||&#x2713; WAF DEVE operar no modo de defesa ativo (bloqueando automaticamente ataques identificados) ou no modo de monitoramento (monitorando/investigando alertas ativamente).|
||&#x2713; WAF configurado para dar suporte ao descarregamento [SSL.](#ssl)|
||&#x2713; WAF DEVE ser configurado de acordo com o Conjunto de Regras [OWASP](#owasp) **Core**   (3.0 ou 3.1) para proteger contra a maioria dos seguintes:|
||&emsp;&#x25fc; protocolo e problemas de codificação.|
||&emsp;&#x25fc; injeção de header, solicitação de roubo e divisão de resposta.|
||&emsp;&#x25fc; ataques de rota e arquivo.|
||&emsp;&#x25fc; ataques de inclusão remota de arquivo (RFI).|
||&emsp;&#x25fc; ataques de execução de código remoto.|
||&emsp;&#x25fc; ataques de injeção PHP.|
||&emsp;&#x25fc; ataques de script entre sites.|
||&emsp;&#x25fc; SQL de injeção.|
||&emsp;&#x25fc; ataques de fixação de sessão.|
|**Alterar Controle**|As políticas de  controle e os procedimentos de alteração devem estar em vigor para garantir que as alterações sejam implementadas de forma a manter a segurança, a estabilidade e a integridade do ambiente. Os seguintes critérios de controle de **alteração são** necessários:|
||&#x2713; separação de funções — ambientes de desenvolvimento e teste **DEVEM** ser separados dos ambientes de produção.|
||&#x2713; dados confidenciais de ambientes de produção **NÃO DEVEM** ser usados em ambientes de desenvolvimento/teste.|
||&#x2713; Todas as alterações DEVEM ser testadas em um ambiente de teste/desenvolvimento antes de serem introduzidas no ambiente de produção.|
||&#x2713; Solicitações de **alteração são** aferdas e autorizadas **ANTES** de entrar em produção.|
||&#x2713; No mínimo, as solicitações de alteração **devem** incluir:|
||&emsp;&#x25fc; Documentação de impacto.|
||&emsp;&#x25fc; procedimentos de back-out documentados.|
||&#x2713; Solicitações de alteração **DEVEM** ser marcadas como concluídas, somente **DEPOIS que** o teste de funcionalidade bem-sucedido tiver sido realizado.|
|**Desenvolvimento/implantação de software seguro**|A segurança precisa estar à frente das práticas de desenvolvimento de software para minimizar o risco de introduzir vulnerabilidades de codificação no aplicativo/complemento, mantendo assim um ambiente seguro e garantindo dados. As seguintes práticas seguras de desenvolvimento de software **DEVEM** estar em prática: |
||&#x2713; Você DEVE ter um processo de desenvolvimento de software estabelecido e documentado cobrindo todo o ciclo de vida do desenvolvimento de software.|
||&#x2713; Todas as alterações de código DEVEM passar por um processo de revisão e autorização por outra pessoa que não seja o desenvolvedor original.|
||&#x2713; práticas de codificação seguras e técnicas de revisão **DEVEM** abordar as [10](https://owasp.org/www-project-top-ten) principais classes de vulnerabilidade do OWASP ou [SANS 25 top 25 CWE.](https://www.sans.org/top25-software-errors)|
||&#x2713; **desenvolvedores devem passar** por treinamento de codificação de software seguro pelo menos anualmente.|
||&#x2713; Repositórios de código **devem** ser protegidos por MFA.|
||&#x2713; Controles de acesso **adequados devem** estar em posição para proteger repositórios de código contra modificações de código mal-intencionados.|
||**Observação**: a [](https://www.microsoft.com/en-us/securityengineering/sdl/) Microsoft publicou o Ciclo de Vida de Desenvolvimento de Segurança (SDL) que a Microsoft segue para dar suporte aos requisitos de segurança e conformidade em seus produtos. O SDL ajuda os desenvolvedores a criar software mais seguro reduzindo o número e a gravidade das vulnerabilidades no software, reduzindo o custo de desenvolvimento.|
|**Gerenciamento de contas**| O gerenciamento de contas de componentes do sistema no escopo, bem como políticas e procedimentos de suporte **devem** atender ao seguinte: |
||&#x2713; credenciais padrão (Fornecedor ou ISV) **são** desabilitadas ou removidas em todos os componentes do sistema no escopo.|
||&#x2713; criação, modificação e exclusão da conta **DEVE** passar por um processo de aprovação estabelecido.|
||&#x2713; contas que não são usadas há  mais de 3 meses DEVEM ser desabilitadas ou excluídas, portanto, o ISV precisa ter um mecanismo para alcançar isso.|
||&#x2713;políticas de senha forte ou outra mitigação **adequada DEVEM** ser configuradas para proteger as credenciais do usuário. A seguinte política de senha deve ser usada como uma diretriz:|
||&emsp;&#x25fc; comprimento mínimo de senha de oito caracteres|
||&emsp;&#x25fc; limite de bloqueio de conta de no máximo 10 tentativas|
||&emsp;&#x25fc; Histórico de senhas de no mínimo cinco senhas|
||&emsp;&#x25fc; imposição do uso de senhas fortes|
||&#x2713; contas de usuário exclusivas DEVEM ser emitidas para cada usuário; nenhuma conta compartilhada deve ser usada.|
||&#x2713; Princípios de privilégios mínimos **devem** ser aplicados a todos os usuários, o mecanismo usado para isso deve ser documentado (ou seja, o uso de grupos). |
||&#x2713; manutenção adequada da conta **deve** ser documentada e realizada, por exemplo, logon interativo desabilitado, logons limitados a hosts específicos, etc. |
||&#x2713; de Acesso Remoto **DEVEM:** |
||&emsp;&#x25fc; usar mFA (Autenticação multifatória)|
||&emsp;&#x25fc; utilizar um perfil de proteção de trânsito que atenda ou exceda o perfil de configuração de dados em trânsito, conforme descrito no Apêndice A|
||&#x2713; Onde o gerenciamento do DNS Público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações dns devem ser configuradas para usar o MFA.|
||**Observação** : Os Portais de Gerenciamento de Nuvem também precisarão atender aos requisitos aplicáveis de gerenciamento de contas, consulte Apêndice F para obter mais detalhes.|
|**Detecção e prevenção contra intrusões (OPCIONAL)**| O crédito extra será dado onde o IDPS (Sistema de Prevenção e Detecção de Intrusões) é usado no perímetro dos ambientes de suporte no escopo.  Os seguintes controles recomendados incluem: |
||&#x2713; IDPS deve ser implantado no perímetro do ambiente de suporte |
||&#x2713; assinaturas IDPS DEVEM ser mantidas atuais, no último dia |
||&#x2713; IDPS DEVE ser configurado para inspeção TLS |
||&#x2713; IDPS DEVE ser configurado para TODO o tráfego de entrada e saída |
||&#x2713; IDPS DEVE ser configurado para alerta |
|**Log de Eventos** |A cobertura de **log DEVE** incluir **todos os** componentes e aplicativos do sistema no escopo, incluindo mecanismos de proteção contra malware. Os seguintes eventos **DEVEM** ser registrados:|
||&emsp;&#x25fc; acesso dos usuários aos componentes do sistema e ao aplicativo|
||&emsp;&#x25fc; todas as ações realizadas por um usuário com privilégios elevados|
||&emsp;&#x25fc; de acesso lógico inválido|
||&emsp;&#x25fc; criação/modificação de conta privilegiada|
||&emsp;&#x25fc; de log de eventos|
||&emsp;&#x25fc; desabilitação de ferramentas de segurança; por exemplo, Anti-Malware ou registro em log de eventos|
||&emsp;&#x25fc; registro em log anti-malware; por exemplo, atualizações, detecção de malware, falhas de verificação|
||&emsp;&#x25fc; eventos IDPS/WAF (se configurado)|
||Os logs **de eventos DEVEM** incluir as seguintes informações:|
||&emsp;&#x25fc; identificação do usuário |
||&emsp;&#x25fc; Tipo de evento |
||&emsp;&#x25fc; data e hora |
||&emsp;&#x25fc; indicador de sucesso/falha|
||&emsp;&#x25fc; Rótulo para identificar o sistema afetado |
||A sincronização de tempo **DEVE** ser usada em todos os componentes do sistema no escopo para ajudar nas investigações forenses.|
||A sincronização de tempo **DEVE** ser configurada para utilizar a mesma fonte de tempo principal (e secundária, se necessário)|
||Sistemas públicos voltados para o público (sistemas dentro do DMZ) **DEVEM** gravar logs em um repositório de registro em log centralizado interno. O repositório de registro em log centralizado não deve estar dentro do DMZ.|
||As trilhas de **auditoria DEVEM** ser protegidas para garantir que os dados de log não podem ser alterados por um ator de ameaças. O acesso ao repositório de registro em log centralizado deve ser limitado somente a funcionários autorizados.|
||Os **logs DEVEM** estar disponíveis imediatamente por 30 dias. Os dados **de registro em log** devem ser mantidos por um mínimo de 90 dias.|
|**Revisão** |Analisar processos, bem como dar suporte a políticas e procedimentos **DEVE** atender ao seguinte:|
||&#x2713; realizar avaliações diárias de log ou utilizar a análise de log automatizada e a tecnologia de alerta para revisar eventos de todos os componentes do sistema no escopo para identificar possíveis eventos de segurança.|
||&#x2713; Possíveis eventos de **segurança DEVEM** ser acompanhados imediatamente.|
|**Alerta** |O alerta de processos, bem como políticas e procedimentos de suporte **deve** atender ao seguinte: |
||&#x2713; eventos de segurança conectados que representam um risco para a segurança de seus sistemas, operações ou dados DEVEM disparar um alerta imediato, por exemplo (não uma lista exaustiva):|
||&emsp;&#x25fc; criação/modificações de conta privilege|
||&emsp;&#x25fc; malware|
||&emsp;&#x25fc; desabilitar ferramentas de segurança|
||&emsp;&#x25fc; de log de eventos|
||&emsp;&#x25fc; eventos IDPS /WAF (se configurado) |
||&#x2713; a equipe deve estar sempre disponível (24/7) para reagir aos alertas disparados.|
|**Gerenciamento de risco**|Uma metodologia de avaliação de risco deve ser desenvolvida e conduzida que inclua o seguinte:|
||&#x2713; um processo formalmente definido.|
||&#x2713; realizada pelo menos anualmente.|
||&#x2713; Inclui todos os ativos no ambiente no escopo.|
||&#x2713; identifica ameaças e vulnerabilidades contra todos os ativos incluídos.|
||&#x2713; Inclui o uso de matrizes de impacto e probabilidade definidas.|
||&#x2713; Resulta na criação de um registro de risco e de um plano de tratamento de risco correspondente.|
|**Resposta a incidentes**|Um plano de resposta a incidentes **completo é** necessário e **deve** incluir como mínimo:|
||&#x2713; No mínimo, a cobertura dos componentes e aplicativos de sistemas no escopo.|
||&#x2713; procedimentos específicos de resposta a incidentes para modelos de ameaça esperados.|
||&#x2713; processo de comunicações documentadas, garantindo a notificação o tempo há tempo de todos os principais participantes e quaisquer entidades externas relevantes, como; marcas de pagamento/adquirentes, órgãos regulatórios e autoridades de supervisão ([RGPD](#gdpr)) em conformidade com os requisitos de relatório obrigatórios.|
||&#x2713; A resposta a incidentes é atualizada com base em lições aprendidas, alterações organizacionais e para incorporar desenvolvimentos do setor.|
||&#x2713; treinamento anual para membros da equipe de resposta a incidentes.|

## <a name="data-handling-security-and-privacy"></a>Segurança e privacidade de tratamento de dados

Os dados em trânsito entre o usuário do aplicativo, os serviços intermediários e os sistemas do ISV serão necessários para serem protegidos pela criptografia por meio de uma conexão TLS que suporte um mínimo de TLS v1.1. *Consulte* [**Apêndice A**](#appendix-a).

Onde seu aplicativo recupera e armazena dados M365, você será obrigado a implementar um esquema de criptografia de armazenamento de dados que siga a especificação conforme definido no [**Apêndice B**](#appendix-a).

### <a name="test-specification"></a>Especificação de teste

|Testar | Controles |
| -----------------------|-------------------------------- |
|**Dados em Trânsito**| A transmissão de dados confidenciais DEVE usar um mínimo de TLS 1.1 com algumas exceções descritas no Apêndice A.|
||A transmissão de dados confidenciais **DEVE** ser criptografada de acordo com os perfis de criptografia descritos no Apêndice B.|
||A compactação TLS deve ser desabilitada.|
||HSTS (Segurança estrita de transporte HTTP) **DEVE** ser configurado para >= 15552000|
|**Dados em Repouso**| O armazenamento de **dados confidenciais DEVE** ser protegido de acordo com os perfis de criptografia descritos no Apêndice B que abrangem requisitos mínimos de criptografia, algoritmos, tamanhos de chave, hash e autenticação de mensagens.|
||Todos os tipos de dados armazenados DEVEM ser documentados.|
|**Retenção e descarte de dados**|O armazenamento de dados **confidenciais DEVE** ser mantido no mínimo implementando políticas de retenção e descarte de dados, procedimentos e processos que incluam minimamente:|
||&#x2713; documente e limite a quantidade de armazenamento de dados e o tempo de retenção para o que é necessário para requisitos legais, regulatórios e/ou comerciais.|
||&#x2713; documente e implante processos para exclusão segura de dados confidenciais quando não for mais necessário, em linha com políticas documentadas.|
||&#x2713; documente e implante um processo trimestral para identificar e excluir com segurança dados confidenciais armazenados que excedam o período de retenção definido.|
|**Gerenciamento de Acesso a Dados**|Limitar o acesso de dados a pessoas com um motivo de negócios legítimo ajuda as organizações a evitar o uso inexperiência ou malícia de dados confidenciais. Dados confidenciais, recebidos pelo aplicativo/add-in e acesso a chaves de criptografia exigem aprovação documentada (eletrônica ou por escrito) para as partes autorizadas em todos os níveis de acesso para acessar e devem incluir uma listagem de privilégios aprovados e verificados demonstrando que a política incorpora os requisitos especificados da seguinte forma: |
||&#x2713; definindo as necessidades de acesso e as atribuições de privilégios apenas para funções que exigem especificamente esse acesso privilegiado. |
||&#x2713; restringir o acesso aos mínimos privilégios necessários para executar responsabilidades de trabalho.|
||&#x2713; garantir que os contratos de compartilhamento de dados estão em uso com todos os terceiros que consomem dados M365.|
|**RGPD**| Como parte do processo de Certificação do Microsoft 365, você deve demonstrar a adesão ao RGPD, seja por:|
||&#x2713; Fornecendo uma revisão independente da conformidade do RGPD por uma empresa de auditoria externa experiente. Você será obrigado a enviar o relatório para revisão ou permitir que o analista veja o relatório. O relatório deve fornecer detalhes suficientes para não apenas validar a avaliação do auditor externo, mas também fornecer confiança suficiente de que a revisão externa tenha confirmado a conformidade com o RGPD.|
||ou|
||&#x2713; enviar mais evidências para fornecer garantia adicional do seu compromisso com as leis de privacidade de dados, da seguinte forma:|
||&#x25fc; Um processo de solicitação de acesso de assunto documentado (SAR) projetado para atender às solicitações dos clientes e atender aos requisitos de trinta dias do RGPD. É recomendável que a ferramenta adequada de descoberta de dados seja feita para garantir que uma SAR seja atendida nesses quadros de tempo. **Observação** : onde essas ferramentas não são usadas, você precisará demonstrar como isso funciona e demonstrar como os processos são capazes de garantir a descoberta de todas as informações do assunto de dados.|
||&#x25fc;Avisos de Privacidade devem estar presentes no site e conter as seguintes informações:
||
||Quando um relatório RGPD independente não estiver disponível, o seguinte deve ser feito para ser revisado como parte da avaliação de Certificação M365: |
||&#x2713; Um processo de solicitação de acesso de assunto documentado (SAR) projetado para atender às solicitações dos clientes e atender aos requisitos de trinta dias do RGPD.  É recomendável que a ferramenta adequada de descoberta de dados seja feita para garantir que uma SAR seja atendida dentro desses períodos, onde essas ferramentas não são usadas, você precisará demonstrar como isso funciona e demonstrar como os processos são capazes de garantir a descoberta de todas as informações do sujeito de dados.|
||&#x2713; Avisos de Privacidade devem estar presentes no site e conter as seguintes informações:|
||&emsp;&emsp;&#x25a1; detalhes de contato das organizações.|
||&emsp;&emsp;&#x25a1; Tipo de dados pessoais sendo processados.|
||&emsp;&emsp;&#x25a1; legalidade do processamento de dados pessoais (*Artigo 6*).|
||&emsp;&emsp;&#x25a1; detalhes dos direitos do assunto de dados:|
||&emsp;&emsp;&#x25a1; Direito de ser informado (*Artigos13 e 14*).
||&emsp;&emsp;&#x25a1; direito de acesso pelo assunto de dados (*Artigo 15*).|
||&emsp;&emsp;&#x25a1; Direito de retificação (*Artigo 16*).|
||&emsp;&emsp;&#x25a1; direito de apagar (*Artigo 17*).|
||&emsp;&emsp;&#x25a1; direito à restrição do processamento (*Artigo 18*).|
||&emsp;&emsp;&#x25a1; direito à portabilidade de dados (*Artigo 20*).|
||&emsp;&emsp;&#x25a1; direito ao objeto (*Artigo 21*).|
||&emsp;&emsp;&#x25a1; direitos em relação à marcação de decisão automatizada, incluindo a criação de perfil (*Artigo 22*).|
||&#x2713; o compartilhamento de informações com terceiros deve ter acordos em curso para garantir que o processamento dos dados do assunto de dados está em linha com as leis de privacidade de dados.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisão de estruturas de conformidade externa opcionais

Se as estruturas de segurança externas foram incluídas no Atestado do Publisher, os analistas de certificação precisarão verificar a validade dessas estruturas de conformidade de segurança como parte da avaliação de Certificação do Microsoft 365.
As evidências das seguintes estruturas de conformidade de segurança externa com suporte incluem:

* [ISMS](#isms) /  [IEC](#iec) - Especificação IS0/IEC 27001</h5>
* [PCI DSS](#pci-dss)
* [SOC 2](#soc-2)

A documentação identificada na seção [Evidências de](#compliance-evidence) Conformidade será usada para executar essa revisão.

### <a name="test-specifications"></a>Especificações de teste

&#x2713; O ambiente de suporte de  aplicativo/add-in E quaisquer processos corporativos de suporte devem ser incluídos no escopo de quaisquer estruturas de conformidade de segurança externa com suporte e devem ser claramente indicados na documentação fornecida. 

&#x2713; As **estruturas** de conformidade de segurança externa suportadas devem ser atuais, ou seja, nos últimos 12 meses (ou dentro de 15 meses, se a reavaliação estiver sendo realizada no momento e as evidências possam ser fornecidas).

&#x2713; estruturas de conformidade de segurança externa suportadas **devem** ser executadas por uma empresa credenciada independente.

## <a name="appendix-a"></a>Apêndice A

### <a name="tls-profile-configuration-requirements"></a>Requisitos de configuração do perfil TLS

Todo o tráfego de rede, seja em uma rede virtual, serviço de nuvem ou data center, deve ser protegido com um mínimo de TLS v1.1 (TLS v1.2+ é recomendado) ou outro protocolo aplicável. As exceções a esse requisito são:

* **Redirecionamento HTTP-para-HTTPS.** Seu aplicativo pode responder por HTTP para redirecionar clientes para HTTPS, mas a resposta não deve conter dados confidenciais (cookies, cabeçalhos, conteúdo). Nenhuma outra resposta HTTP além de redirecionamentos para HTTPS e a resposta a sondas de saúde são permitidas. Confira a seguir.
* **Sondas de saúde**. Seu aplicativo só poderá responder a sondas de saúde por **HTTP** se as sondas de saúde HTTPS não são suportadas pela parte de verificação.
* **Acesso ao certificado**. O acesso aos pontos de extremidade CRL, OCSP e AIA para fins de validação de certificado e verificação de revogação é permitido em HTTP.
* **Comunicações locais**. Seu aplicativo pode usar HTTP (ou outros protocolos não protegidos) para comunicações que não saem do sistema operacional, e. g. conectando-se a um ponto de extremidade do servidor Web exposto no localhost.

A compactação TLS **DEVE** ser desabilitada.

## <a name="appendix-b"></a>Apêndice B

### <a name="encryption-profile-configuration-requirements"></a>Requisitos de configuração de perfil de criptografia

Somente primitivas criptográficas e parâmetros são permitidos da seguinte maneira:

### <a name="symmetric-cryptography"></a>Criptografia simétrica

**Encryption**

&emsp;&#x2713; AES, BitLocker, Mamoeiro ou TDES são permitidos. Qualquer um dos comprimentos de chave com suporte >=128 são permitidos (128, 192 e 256 bits) e podem ser usados (teclas de 256 bits são recomendadas).

&emsp;&#x2713; modo CBC somente é permitido. Cada operação de criptografia deve usar um vetor de inicialização (IV) recém-gerado aleatoriamente.

&emsp;&#x2713; Uso de codificações de fluxo, como RC4, **NÃO É** permitido.

**Funções hash**

&emsp;&#x2713; Todos os novos códigos devem usar SHA-256, SHA-384 ou SHA-512 (conhecido coletivamente como SHA-2). A saída pode ser truncada para não menos de 128 bits

&emsp;&#x2713; SHA-1 só pode ser usado por motivos de compatibilidade.

&emsp;&#x2713; uso de MD5, MD4, MD2 e outras funções de hash NÃO É permitido, mesmo para aplicativos não criptográficos.

**Autenticação de mensagens**

&emsp;&#x2713; Todos os novos códigos devem usar o HMAC com uma das funções de hash aprovadas. A saída do HMAC pode ser truncada para no menos 128 bits.

&emsp;&#x2713; HMAC-SHA1 só pode ser usado por motivos de compatibilidade.

&emsp;&#x2713; tecla HMAC deve ter pelo menos 128 bits. As teclas de 256 bits são recomendadas.

### <a name="asymmetric-algorithms"></a>Algoritmos assimétricos

**Encryption**

&emsp;&#x2713; RSA é permitido. A **tecla DEVE** ter pelo menos 2048 bits e o preenchimento OAEP deve ser usado. O uso do preenchimento PKCS só é permitido por motivos de compatibilidade.

**Assinaturas**

&emsp;&#x2713; RSA é permitido. A **tecla DEVE** ter pelo menos 2.048 bits e o preenchimento PSS deve ser usado. O uso do preenchimento PKCS só é permitido por motivos de compatibilidade.

&emsp;&#x2713;é permitido ECDSA. A **tecla DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

**Chave do Exchange**

&emsp;&#x2713; ecdh é permitido. A **tecla DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

&emsp;&#x2713; ecdh é permitido. A **tecla DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

## <a name="appendix-c"></a>Apêndice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Coleção Evidence – Delta para ISO 27001

Onde você já atingiu a conformidade ISO27001, as seguintes lacunas do delta não totalmente cobertas pela ISO 27001 precisarão, no mínimo, ser revisadas como parte desta Certificação do Microsoft 365.

> [!NOTE]
> Como parte de sua avaliação de Certificação do Microsoft 365, o analista de certificação determinará se algum dos controles ISO 27001 mapeados não foi incluído como parte da avaliação iso 27001 e também poderá decidir por exemplo os controles que foram encontrados incluídos para fornecer mais garantia. Quaisquer requisitos ausentes da ISO 27001 precisarão ser incluídos em suas atividades de avaliação de Certificação do Microsoft 365.

**Proteção contra Malware – Antivírus**

Se a proteção contra malware estiver em prática usando o controle do aplicativo e for atestada no Relatório ISO 27001, nenhuma investigação mais será necessária. Se nenhum controle de aplicativo estiver em prática, os analistas de certificação precisarão identificar e avaliar evidências de mecanismos de controle de aplicativos para evitar a detonação de malware no ambiente. Isso exigirá que você:

* Demonstre que o software antivírus está sendo executado em todos os componentes do sistema amostrados.

* Demonstre que o antivírus está configurado em todos os componentes do sistema amostrados para bloquear automaticamente o malware, para colocar em quarentena & alerta ou para alertar.

* O software antivírus **DEVE** ser configurado para registrar todas as atividades.

**Gerenciamento de Patch – Patching**

Como as auditorias iso 27001 não avaliam especificamente essa categoria, isso exigirá que você:

* Componentes de software e sistemas operacionais não mais suportados pelo fornecedor **NÃO DEVEM** ser usados no ambiente. As políticas de suporte devem estar em funcionamento para garantir que os componentes de software/sistemas operacionais sem suporte sejam removidos do ambiente e um processo para identificar quando os componentes de software chegar ao fim da vida útil devem estar no local

**Verificação de vulnerabilidade**  

Como as auditorias iso 27001 não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que a verificação trimestral de vulnerabilidade interna e externa é realizada.

* Confirme se a documentação de suporte está em uso para correção de vulnerabilidade com base na classificação de risco e em linha com a especificação da seguinte forma:
 
 &#x2713; correção de todos os problemas de risco Críticos e Altos em linha com a classificação de risco para verificação interna.
 
 &#x2713; correção de todos os problemas críticos, altos e médios de risco em linha com a classificação de risco para verificação externa.
 
 &#x2713; Demonstre que a correção é conduzida em linha com a política de correção de vulnerabilidade documentada.

**Firewall – Firewalls (ou tecnologias equivalentes)**

Como as auditorias iso 27001 não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que os firewalls estão instalados no limite do ambiente no escopo.

* Demonstre que firewalls são instalados entre o DMZ e redes confiáveis.

*   Demonstre que todo o acesso público termina no DMZ.

*   Demonstre que as credenciais administrativas padrão são alteradas antes da instalação no ambiente ao vivo.

*   Demonstre que todo o tráfego permitido por meio dos firewalls passa por um processo de autorização que resulta na documentação de todo o tráfego com uma justificativa comercial.

*   Demonstre que todos os firewalls estão configurados para soltar o tráfego não definido explicitamente.

*   Demonstre que os firewalls suportam apenas criptografia forte em todas as interfaces administrativas que não são do console.

*   Demonstre que as interfaces administrativas não console do firewall expostas ao MFA de suporte à Internet.

*   Demonstrar que as revisões de regra de firewall são realizadas pelo menos a cada 6 meses

**Firewall – Firewalls de Aplicativo Web (WAF)**  

Crédito adicional será fornecido se um WAF for implantado para ajudar a proteger contra a infinidade de ameaças e vulnerabilidades de aplicativos Web às que o aplicativo pode ser exposto. Quando um WAF ou semelhante estiver presente, isso exigirá que você:

* Demonstre que o WAF está configurado no modo de defesa ativo ou monitorando mais com alertas.

* Demonstre que o WAF está configurado para dar suporte ao Descarregamento SSL.

* É configurado de acordo com o Conjunto de Regras Principais OWASP (3.0 ou 3.1) para proteger contra a maioria dos seguintes tipos de ataque:

&#x2713; protocolo e problemas de codificação.

&#x2713; injeção de header, solicitação de roubo e divisão de resposta.

&#x2713; ataques de caminho e arquivo.

&#x2713; ataques de inclusão remota de arquivo (RFI).

&#x2713; ataques de execução de código remoto.

&#x2713; ataques de injeção PHP.

&#x2713; ataques de script entre sites.

&#x2713; SQL injeção.

&#x2713; ataques de fixação de sessão.

**Alterar Controle**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de Solicitação de Alteração, isso exigirá que você:

* Demonstre que as solicitações de alteração têm os seguintes detalhes:

&#x2713; impacto documentado.

&#x2713; Detalhes sobre quais testes de funcionalidade devem ser conduzidos.

&#x2713; detalhes de quaisquer procedimentos de back-out.

* Demonstre que o teste de funcionalidade é realizado depois que as alterações são concluídas.

* Demonstre que as solicitações de alteração são assinadas após a realização do teste de funcionalidade.

**Gerenciamento de contas**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de gerenciamento de contas, isso exigirá que você:

*   Demonstre como &#x2713;são implementadas para atenuar ataques de repetição (por exemplo, MFA, Kerberos).
*   Demonstre como contas que não foram usadas em três meses são desabilitadas ou excluídas.
*   &#x2713; ou outras mitigações adequadas devem ser configuradas para proteger as credenciais do usuário. A seguinte política de senha mínima deve ser usada como uma diretriz:

&#x2713; comprimento mínimo de senha de 8 caracteres.

&#x2713; limite de bloqueio de conta de no máximo 10 tentativas.
 
&#x2713; Histórico de senhas de no mínimo cinco senhas.
 
&#x2713; imposição do uso de senhas fortes.
 
*   Demonstre que o MFA está configurado para todas as soluções de acesso remoto.

*   Demonstre que a criptografia forte está configurada em todas as soluções de acesso remoto.

*   Onde o gerenciamento do DNS Público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações dns devem ser configuradas para usar o MFA.

**Detecção e prevenção contra intrusões (OPCIONAL)**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos dos Serviços de Detecção e Prevenção de Intrusão (IDPS), isso exigirá que você:

*   O IDPS **deve** ser implantado no perímetro do ambiente de suporte.

*   As assinaturas IDPS **DEVEM** ser mantidas atuais, no último dia.

*   O IDPS **DEVE** ser configurado para inspeção TLS.

*   O IDPS **DEVE** ser configurado para todo o tráfego de entrada e saída.

*   O IDPS **DEVE** ser configurado para alertas.

**Log de Eventos**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de registro em log de eventos de segurança, isso exigirá que você:

* Demonstre que os sistemas públicos voltados para o registro em log em uma solução de registro em log centralizado que não está dentro do DMZ.

* Demonstre como um mínimo de 30 dias de dados de registro em log está disponível imediatamente, com 90 dias sendo mantidos.

**Revisão (Dados de Log)**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dessa categoria, isso exigirá que você:

*   Demonstre como as avaliações diárias de log são conduzidas e como exceções e anomalias são identificadas mostrando como elas são tratadas.

**Alerta**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dessa categoria, isso exigirá que você:

* Demonstre como os eventos de segurança são configurados para disparar alertas para triagem imediata.

* Demonstre como a equipe está disponível 24/7 para responder a alertas de segurança.

**Gerenciamento de Riscos**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de avaliação de risco, isso exigirá que você:

* Demonstre que um processo formal de gerenciamento de riscos está estabelecido.

**Resposta a incidentes**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos de políticas e processos de resposta a incidentes, isso exigirá que você:

*   Demonstre que o plano/procedimento de resposta a incidentes inclui:

&#x2713; procedimentos de resposta específicos para modelos de ameaça esperados.

&#x2713; de tratamento de incidentes alinhados à Estrutura de Segurança Cibernética do NIST (Identificar, Proteger, Detectar, Responder, Recuperar).
 
&#x2713; O IRP abrange os sistemas no escopo.
 
&#x2713; treinamento anual para a equipe de resposta a incidentes.

## <a name="appendix-d"></a>Apêndice D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Coleção Evidence – Deltas para PCI DSS

Onde você já atingiu a conformidade com o PCI DSS, os seguintes deltas (lacunas) não totalmente cobertos pelo PCI DSS precisarão, no mínimo, ser revisados como parte dessa Certificação do Microsoft 365.

> [!NOTE]
> Como parte da avaliação de Certificação do Microsoft 365, o analista de certificação determinará se qualquer um dos controles PCI DSS mapeados não foi incluído como parte da avaliação do PCI DSS e também poderá decidir por exemplo os controles que foram encontrados incluídos para fornecer mais garantia. Quaisquer requisitos ausentes do PCI DSS precisarão ser incluídos nas atividades de avaliação de certificação do Microsoft 365.

**Proteção contra Malware - Controle de Aplicativos**

Se a proteção contra malware estiver no local por meio do uso de antivírus e for atestada no Pci DSS Report, nenhuma investigação será necessária. Se nenhum anti-vírus estiver em uso, os analistas de certificação precisarão identificar e avaliar evidências de mecanismos de controle de aplicativos para evitar a detonação de malware no ambiente. Isso exigirá que você: 

*   Demonstre como a aprovação do aplicativo é conduzida e confirme se ela foi concluída.

*   Demonstre que existe uma lista completa de aplicativos aprovados com justificativa comercial.

*   Forneça ou demonstre que a documentação de suporte está em prática detalhando como o software de controle de aplicativos é configurado para atender a mecanismos de controle de aplicativos específicos (por exemplo, whitelisting, assinatura de código, etc.).

*   Demonstre que em todos os componentes do sistema amostrados, o controle de aplicativo é configurado como documentado.

**Gerenciamento de Patch – Classificação de Risco**

Como as auditorias pci DSS não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre como a classificação de risco de vulnerabilidades é conduzida.

**Verificação de vulnerabilidade**

Como as auditorias pci DSS não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que a correção é conduzida em linha com a política de correção de vulnerabilidade documentada.

**Firewall – Firewalls (ou tecnologias equivalentes)**

Como as auditorias pci DSS não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que os firewalls suportam apenas criptografia forte em todas as interfaces administrativas que não são do console.

* Demonstre que as interfaces administrativas não console do firewall expostas ao MFA de suporte à Internet.

Crédito adicional será fornecido se um WaF (Firewall de Aplicativo Web) for implantado para ajudar a proteger contra a infinidade de ameaças e vulnerabilidades de aplicativos Web às que o aplicativo pode ser exposto. Quando um WAF ou semelhante estiver presente, isso exigirá que você:

* Demonstre que o WAF está configurado no modo de defesa ativo ou monitorando mais com alertas.

* Demonstre que o WAF está configurado para dar suporte ao descarregamento SSL.

* É configurado de acordo com o Conjunto de Regras Principais OWASP (3.0 ou 3.1) para proteger contra a maioria dos seguintes tipos de ataque:

&#x2713; protocolo e problemas de codificação.

&#x2713; injeção de header, solicitação de roubo e divisão de resposta.

&#x2713; ataques de caminho e arquivo.

&#x2713; ataques de inclusão remota de arquivo (RFI).

&#x2713; ataques de execução de código remoto.

&#x2713; ataques de injeção PHP.

&#x2713; ataques de script entre sites.

&#x2713; SQL injeção.

&#x2713; ataques de fixação de sessão.

**Alterar Controle**

Como as auditorias pci DSS não avaliam especificamente alguns elementos dos processos de Solicitação de Alteração, isso exigirá que você:

* Demonstre que as solicitações de alteração são ativas antes de serem feitas em ambientes de produção.

* Demonstre que as alterações são autorizadas antes de entrar em produção.

* Demonstre que o teste de funcionalidade é realizado depois que as alterações são concluídas.

* Demonstre que as solicitações de alteração são assinadas após a realização do teste de funcionalidade.

**Desenvolvimento/implantação de software seguro**

Como as auditorias do PCI DSS não acessam especificamente alguns elementos de processos seguros de desenvolvimento e implantação de software; isso exigirá para você:

* Repositórios de código DEVEM ser protegidos pelo MFA.

*   Os controles de acesso adequados devem estar no local para proteger repositórios de código contra modificações de código mal-intencionados.

**Gerenciamento de contas**

Como as auditorias do PCI DSS não avaliam especificamente alguns elementos dos processos de gerenciamento de contas, isso exigirá que você:

* Demonstre como os mecanismos de autorização são implementados para atenuar ataques de repetição (por exemplo, MFA, Kerberos).

* Políticas de senha fortes ou outras mitigações adequadas devem ser configuradas para proteger as credenciais do usuário. A seguinte política de senha mínima deve ser usada como uma diretriz: 

&#x2713; comprimento mínimo de senha de 8 caracteres.

&#x2713; limite de bloqueio de conta de no máximo 10 tentativas.

&#x2713; Histórico de senhas de no mínimo cinco senhas.

&#x2713; imposição do uso de senhas fortes.

* Demonstre que a criptografia forte está configurada em todas as soluções de acesso remoto.

* Onde o gerenciamento do DNS Público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações dns devem ser configuradas para usar o MFA.

**Detecção e prevenção contra intrusões (OPCIONAL)**

Como as auditorias do PCI DSS não avaliam especificamente alguns elementos dos processos dos Serviços de Detecção e Prevenção de Intrusões (IDPS), isso exigirá que você:

* O IDPS DEVE ser configurado para inspeção TLS.

*   O IDPS DEVE ser configurado para todo o tráfego de entrada e saída.

**Gerenciamento de Riscos**

Como as auditorias pci DSS não avaliam especificamente alguns elementos de processos de avaliação de risco, isso exigirá que você:

* A demonstração da avaliação de risco inclui matrizes de impacto e probabilidade.

**Resposta a incidentes**

Como as auditorias pci DSS não avaliam especificamente alguns elementos de políticas e processos de resposta a incidentes, isso exigirá que o desenvolvedor:

* Demonstrar recursos de tratamento de incidentes alinhados à Estrutura de Segurança Cibernética do NIST (Identificar, Proteger, Detectar, Responder, Recuperar).

## <a name="appendix-e"></a>Apêndice E

### <a name="evidence-collection---deltas-for-soc-2"></a>Coleção Evidence - Deltas para SOC 2

Onde você já atingiu a conformidade do SOC 2, os seguintes delta (lacunas) não totalmente cobertos pelo SOC 2 precisarão ser revisados como parte dessa Certificação do Microsoft 365.

> [!NOTE]
> Como parte da avaliação de Certificação do Microsoft 365, o analista de certificação determinará se algum dos controles SOC 2 mapeados não foi incluído como parte da sua avaliação do SOC 2 e também poderá decidir por exemplo os controles que foram encontrados incluídos para fornecer mais garantia. Quaisquer requisitos ausentes da avaliação do SOC 2 precisarão ser incluídos como parte das atividades de avaliação de Certificação do Microsoft 365.

**Proteção contra Malware - Controle de Aplicativos**

Se a proteção contra malware estiver no local por meio do uso de antivírus e for atestada no relatório do SOC 2, nenhuma investigação mais será necessária. Se nenhum anti-vírus estiver em uso, os analistas de certificação precisarão identificar e avaliar evidências de mecanismos de controle de aplicativos para evitar a detonação de malware no ambiente. Isso exigirá que você:

* Forneça ou demonstre que a documentação de suporte está em prática detalhando como o software de controle de aplicativos é configurado para atender a mecanismos de controle de aplicativos específicos (por exemplo, whitelisting, assinatura de código, etc.).

* Demonstre como a aprovação do aplicativo é conduzida e confirme se ela foi concluída.

*   Demonstre que existe uma lista completa de aplicativos aprovados com justificativa comercial.

*   Demonstre que em todos os componentes do sistema amostrados, o controle de aplicativo é configurado como documentado.

**Gerenciamento de Patch – Patching**

Como as auditorias do SOC 2 não avaliam especificamente essa categoria, isso exigirá que você:

*   Qualquer problema Baixo, Médio, Alto ou Crítico deve ser remendado em janelas de atividade de correção normais.

*   Componentes de software e sistemas operacionais não mais suportados pelo fornecedor NÃO DEVEM ser usados no ambiente. As políticas de suporte devem estar em funcionamento para garantir que os componentes de software/sistemas operacionais sem suporte sejam removidos do ambiente e um processo para identificar quando os componentes de software vão para o fim da vida útil deve estar no local.

**Firewall – Firewalls**

Como as auditorias do SOC 2 não avaliam especificamente os controles de alteração nas listas de controle de acesso ao firewall, isso exigirá que você:

* Demonstre que todo o tráfego permitido por meio dos firewalls passa por um processo de autorização que resulta na documentação de todo o tráfego com uma justificativa comercial.

* Demonstre que as revisões de regra de firewall são realizadas pelo menos a cada seis meses.

O crédito adicional será fornecido se um WAF (Firewall de Aplicativo Web) ou semelhante for implantado para ajudar a proteger contra a infinidade de ameaças e vulnerabilidades de aplicativos Web às que o aplicativo pode ser exposto. Quando um WAF ou semelhante estiver presente, isso exigirá que você:

* Demonstre que o WAF está configurado no modo de defesa ativo ou monitorando mais com alertas.

* Demonstre que o WAF está configurado para dar suporte ao descarregamento SSL.

* É configurado de acordo com o Conjunto de Regras Principais OWASP ((3.0 ou 3.1) para proteger contra a maioria dos seguintes tipos de ataque:

&emsp;&#x2713; protocolo e problemas de codificação.

&emsp;&#x2713; injeção de header, solicitação de roubo e divisão de resposta.

&emsp;&#x2713; ataques de rota e arquivo.

&emsp;&#x2713; ataques de inclusão remota de arquivo (RFI).

&emsp;&#x2713; ataques de execução de código remoto.

&emsp;&#x2713; ataques de injeção PHP.

&emsp;&#x2713; ataques de script entre sites.

&emsp;&#x2713; SQL de injeção.

&emsp;&#x2713; ataques de fixação de sessão.

**Alterar Controle**

Como as auditorias do SOC 2 não avaliam especificamente alguns elementos dos processos de Solicitação de Alteração, isso exigirá que o desenvolvedor:

* Demonstre como ambientes de desenvolvimento/teste são separados do ambiente de produção que aplica a separação de funções.

* Demonstre como os dados ao vivo não são usados nos ambientes de desenvolvimento/teste.

* Demonstre que o teste de funcionalidade é realizado depois que as alterações são concluídas.

* Demonstre que as solicitações de alteração são assinadas após a realização do teste de funcionalidade.

**Desenvolvimento/implantação de software seguro**

Como as auditorias do SOC 2 não acessam especificamente alguns elementos de processos seguros de desenvolvimento e implantação de software; isso exigirá para você:

*   Você DEVE ter um processo de desenvolvimento de software estabelecido e documentado que abrange todo o ciclo de vida do desenvolvimento de software.

*   Os desenvolvedores DEVEM passar por treinamento de codificação de software seguro pelo menos anualmente.

*   Repositórios de código DEVEM ser protegidos pelo MFA.

*   Os controles de acesso adequados devem estar no local para proteger repositórios de código contra modificações de código mal-intencionados.

**Gerenciamento de contas**

Como as auditorias do SOC2 não avaliam especificamente alguns elementos dos processos de gerenciamento de contas, isso exigirá que você:

*   Demonstre como os mecanismos de autorização são implementados para atenuar ataques de repetição (por exemplo, MFA, Kerberos).

*   Demonstre como contas que não foram usadas em três meses são desabilitadas ou excluídas.

*   Políticas de senha fortes ou outras mitigações adequadas devem ser configuradas para proteger as credenciais do usuário. A seguinte política de senha mínima deve ser usada como uma diretriz:

&emsp;&#x2713; comprimento mínimo de senha de 8 caracteres.

&emsp;&#x2713; limite de bloqueio de conta de no máximo 10 tentativas.

&emsp;&#x2713; Histórico de senhas de no mínimo 5 senhas.

&emsp;&#x2713; imposição do uso de senhas fortes

*   Demonstre que contas de usuário exclusivas são emitidas para todos os usuários.

*   Onde o gerenciamento do DNS Público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações dns devem ser configuradas para usar o MFA.

**Detecção e prevenção contra intrusões (OPCIONAL).**

Como as auditorias do SOC 2 não avaliam especificamente alguns elementos dos processos dos Serviços de Detecção e Prevenção de Intrusões (IDPS), isso exigirá que você:

*   Assinaturas IDPS DEVEM ser mantidas atuais, no último dia

*   IDPS DEVE ser configurado para inspeção TLS

*   IDPS DEVE ser configurado para todo o tráfego de entrada e saída

**Log de Eventos**

Como as auditorias do SOC 2 não avaliam especificamente alguns elementos dos processos de registro em log de eventos de segurança, isso exigirá que você:

* Demonstrar como, em todos os componentes do sistema no conjunto de exemplos, o sistema a seguir é configurado para registrar os seguintes eventos

&emsp;&#x2713; acesso do usuário aos componentes do sistema e aos aplicativos.

&emsp;&#x2713; todas as ações realizadas por um usuário com privilégios elevados.

&emsp;&#x2713; tentativas de acesso lógico inválidas.

Demonstrar que os eventos registrados contêm; no mínimo, as seguintes informações:

&emsp;&#x2713; User.

&emsp;&#x2713; Tipo de Evento.

&emsp;&#x2713; Data e Hora.

&emsp;&#x2713; indicador de sucesso/falha.

&emsp;&#x2713; Rótulo para identificar o sistema afetado.

*   Demonstre que todos os componentes do sistema no conjunto de exemplos estão configurados para utilizar a sincronização de tempo e que eles são os mesmos que os servidores de tempo primário/secundário.

* Demonstre que os sistemas públicos voltados para o registro em log em uma solução de registro em log centralizado que não está dentro do DMZ.

*   Demonstre que os sistemas públicos voltados para o registro em log em uma solução de registro em log centralizado que não está dentro do DMZ.

* Demonstre como a solução de registro em log centralizado é protegida contra violações não autorizadas de dados em log.

* Demonstre como um mínimo de 30 dias de dados de registro em log está disponível imediatamente, com 90 dias ou mais sendo mantidos.

**Gerenciamento de Riscos**

Como as auditorias do SOC2 não avaliam especificamente alguns elementos dos processos de avaliação de risco, isso exigirá que você:

* Demonstre que uma avaliação formal de risco é conduzida pelo menos anualmente.

*Resposta a incidentes.*

Como as auditorias soc2 não avaliam especificamente alguns elementos de políticas e processos de resposta a incidentes, isso exigirá que você:

* Demonstre que o plano/procedimento de resposta a incidentes inclui:

&emsp;&#x2713; procedimentos de resposta específicos para modelos de ameaça esperados.

&emsp;&#x2713; processo de comunicações documentados para garantir a notificação em tempo há tempo dos principais participantes (marcas de pagamento/adquirentes, órgãos regulatórios, autoridades de supervisão, diretores, clientes, etc.

## <a name="appendix-f"></a>Apêndice F

### <a name="hosting-deployment-types"></a>Tipos de implantação de hospedagem

A Microsoft reconhece que você implantará aplicativos e armazenará código de aplicativo/complemento em diferentes ambientes de hospedagem. As responsabilidades gerais de alguns dos controles de segurança dentro da Certificação do Microsoft 365 dependerão do ambiente de hospedagem que está sendo usado. O Apêndice F analisa os tipos comuns de implantação e os mapeia em relação aos controles de segurança avaliados como parte do processo de avaliação. Os seguintes tipos de implantação de hospedagem foram identificados:

|  |  |
|-----|------|
|**ISV hospedado**|Os tipos hospedados pelo ISV podem ser definidos como onde você é responsável pela infraestrutura usada para dar suporte ao ambiente de aplicativo/complemento. Isso pode estar fisicamente localizado em seus próprios data centers ou data centers de terceiros com um serviço de co-localização. Por fim, você tem total propriedade e controle administrativo sobre a infraestrutura de suporte e o ambiente operacional.|
|**Infraestrutura como serviço (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infraestrutura como serviço é um serviço fornecido pelo qual a infraestrutura de suporte físico é gerenciada e mantida em seu nome pelo provedor de serviços de nuvem (CSP). Normalmente, rede, armazenamento, servidores físicos e a infraestrutura de virtualização são de responsabilidade do CSP. O Sistema Operacional, Middleware, Tempo de Execução, Dados e Aplicativos são as responsabilidades de você. Os recursos de firewall também seriam gerenciados e mantidos por terceiros, no entanto, a manutenção da base de regras de firewall normalmente ainda seria responsabilidade dos consumidores.|
|**Plataforma como serviço/sem servidor (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Com Platform as a Service, você é provisionado com uma plataforma gerenciada apresentando um serviço que pode ser consumido. Você não precisa executar funções sysadmin, pois o sistema operacional e a infraestrutura de suporte são gerenciados pelo CSP. Isso normalmente seria usado quando as organizações não querem se preocupar em apresentar um serviço Web e, em vez disso, podem se concentrar em criar o código-fonte do aplicativo Web e publicar o aplicativo Web nos serviços Web gerenciados na nuvem.  Outro exemplo pode ser um serviço de banco de dados em que a conectividade é dada a um banco de dados, no entanto, a infraestrutura de suporte e o aplicativo de banco de dados são abstraídos do consumidor.   **Observação: Serverless e PaaS são semelhantes para a finalidade do Microsoft 365 Certification Hosting Deployment Type's Serverless e PasS são considerados da mesma forma**|
|**Híbrida Hospedada**|Com o tipo hospedado híbrido, você pode utilizar vários tipos hospedados para dar suporte a várias partes do ambiente de suporte. Esse pode ser mais o caso em que aplicativos/complementos são usados em várias pilhas M365. Embora a Certificação do Microsoft 365 suporte onde aplicativos/complementos em vários serviços M365 são desenvolvidos, uma avaliação de todo o ambiente de suporte (entre aplicativos/complementos) precisaria ser avaliada de acordo com cada um dos "Mapeamentos de Tipos Hospedados" aplicáveis. Ocasionalmente, você pode utilizar diferentes tipos hospedados para um único complemento, onde isso está sendo executado, a aplicabilidade dos critérios ainda precisará seguir os critérios "Mapeamentos de Tipos Hospedados" entre os vários tipos hospedados.|
|**Hospedagem Compartilhada**|A hospedagem compartilhada é onde você hospeda o ambiente em uma plataforma compartilhada por vários consumidores individuais. A Especificação de Certificação do Microsoft 365 não foi escrita para levar em conta isso devido à adoção da nuvem, a hospedagem compartilhada não é comum. Se você acredita que isso está sendo usado, entre em contato com a Microsoft, pois os requisitos adicionais precisarão ser criados para levar em conta os riscos adicionais sob esse tipo de hospedagem.|


## <a name="appendix-g"></a>Apêndice G

### <a name="microsoft-365-certification-process-workflow"></a>Fluxo de trabalho do processo de certificação do Microsoft 365

![Fluxo de trabalho](ProcessFlow.jpg)

## <a name="learn-more"></a>Saiba mais

[Visão geral do Programa de Conformidade de Aplicativos do Microsoft 365](~/overview.md)  
[O que é Atestado do Microsoft 365 App Publisher?](~/docs/attestation.md)  
[O que é a certificação do Microsoft 365?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossário

### <a name="aia"></a>AIA

*Acesso a Informações de Autoridade é um descritor de local de serviço usado para localizar o certificado da autoridade de certificação de emissão.

### <a name="crl"></a>CRL

*A Lista de Revogação de Certificados fornece um meio para um ponto de extremidade SSL (Secure Sockets Layer) verificar se um certificado recebido de um host remoto é válido e confiável.

### <a name="cvss-score"></a>Pontuação CVSS

*Common Vulnerability Scoring System é um padrão publicado que mede a vulnerabilidade e calcula uma pontuação numérica com base em sua gravidade.

### <a name="cvss-patch-management-guidelines"></a>Diretrizes de gerenciamento de patch CVSS

* Crítico (9,0 - 10,0)
* Alto (7,0 - 8,9)
* Médio (4,0 - 6,9)
* Baixo (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*Zona desmilitarizada é uma rede intermediária física ou lógica que interage diretamente com redes externas ou sem propriedade, mantendo a rede interna e privada do host separada e isolada.

### <a name="euii"></a>EUII

*Informações de identificação do usuário final*.

### <a name="gdpr"></a>RGPD

*O Regulamento Geral de Proteção de Dados é uma regulamentação de privacidade e proteção de dados da União Europeia (UE) para todos os dados de todos os cidadãos da UE, independentemente de onde seu site de aplicativo está localizado.

### <a name="hsts"></a>HSTS

*A Segurança Estrita de Transporte HTTP utiliza um cabeçalho de resposta HTTP instruindo o navegador da Web a acessar somente conteúdo por HTTPS.  Isso foi projetado para proteger contra ataques de rebaixamento e roubo de cookies.

### <a name="iec"></a>IEC

*International Electrotechnical Commission.

### <a name="isms"></a>ISMS

*Sistema de Gerenciamento de Segurança da Informação.

### <a name="isv"></a>ISV

Fornecedores de Segurança Independentes são indivíduos e organizações que desenvolvem, comercializam e vendem softwares executados em plataformas de hardware e software de terceiros.

### <a name="iso-27001"></a>ISO 27001

Uma estrutura de especificação do sistema de gerenciamento de segurança de informações para todos os controles técnicos em processos e políticas de gerenciamento de riscos de organizações.

### <a name="lfi"></a>LFI

*A Inclusão de Arquivo Local* permite que um invasor inclua arquivos em um servidor por meio do navegador da Web.

### <a name="nist"></a>NIST

O *Instituto* Nacional de Padrões (NIST), uma agência não regulamentar do Departamento de Comércio dos EUA, fornece orientações para que organizações do setor privado nos EUA avaliem e aprovem sua capacidade de impedir, detectar e responder a ataques cibernéticos.

### <a name="non-significant-changes"></a>Alterações não significativas

* Correções de bug secundárias.
* Pequenas melhorias de desempenho.
* Sistemas operacionais/bibliotecas/patches de aplicativos de cliente e servidor.

### <a name="ocsp"></a>OCSP

*O Protocolo de Status do Certificado Online* é usado para verificar o status de revogação de certificados digitais X.509.

### <a name="oii"></a>OII

*Informações de identificação organizacional*.

### <a name="owasp"></a>OWASP

*Open Web Application Security Project*.

### <a name="pci-dss"></a>PCI DSS

*Payment Card Industry Data Security Standard*, uma organização que mantém padrões para a segurança de dados de titulares de cartão em todo o mundo.

### <a name="pen-testing"></a>Teste de caneta

*O teste de* penetração é um método de teste de um aplicativo Web simulando ataques mal-intencionados para encontrar vulnerabilidades de segurança que um invasor poderia explorar.

### <a name="saml"></a>SAML

*Security Assertion Markup Language* é um padrão aberto para trocar dados de autenticação e autorização entre o usuário, o provedor de identidade e o provedor de serviços.

### <a name="sensitive-data"></a>Dados Confidenciais

* Acessar dados de controle.
* Conteúdo do cliente.
* Informações de identidade do usuário final.
* Suporte a dados.
* Dados pessoais públicos.
* Informações pseudonimous do usuário final.

### <a name="significant-changes"></a>Alterações significativas

* Realocação do ambiente de hospedagem.
* Principais atualizações para a infraestrutura de suporte; por exemplo, implementação de um novo firewall, grandes atualizações para serviços voltados para a frente, etc.
* Adição de recursos e /ou extensões ao seu aplicativo.
* Atualizações para seu aplicativo que capturam dados confidenciais adicionais.
* Alterações nos fluxos de dados ou nos modelos de autorização do aplicativo
* Adição de pontos de extremidade da API ou funções de ponto de extremidade da API.

### <a name="soc-2"></a>SOC 2

Controle da Organização do *Serviço 2*, um procedimento de auditoria técnica composto por cinco Princípios de Serviço de Confiança para garantir que os provedores de serviços gerenciem com segurança os dados e a privacidade dos clientes de uma organização.

### <a name="ssl"></a>SSL

*Camada de Soquetes Seguros*.

### <a name="tls"></a>TLS

*Segurança da Camada de Transporte*.
