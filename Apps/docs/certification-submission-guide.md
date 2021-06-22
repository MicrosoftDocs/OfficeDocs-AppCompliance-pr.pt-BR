---
ms.author: oromalle
title: Microsoft 365 Guia de Envio de Certificação
author: orionomalley
description: Microsoft 365 Exibição granular do Guia de Envio de Certificação
keywords: equipes de certificação de aplicativos Microsoft 365 conformidade de segurança m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 5e99defd75573b1335975ddc19e851c50da7721f
ms.sourcegitcommit: 0d46955e7b4c0e1d4208843813793c382344b2f5
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/22/2021
ms.locfileid: "53053445"
---
# <a name="microsoft-365-certification-submission-guide"></a>Microsoft 365 Guia de Envio de Certificação

**Neste artigo:**
- [Introdução](#introduction)
- [Pré-requisitos](#prerequisites) 
- [Microsoft 365 Atualizações de especificação de certificação](#microsoft-365-certification-specification-updates)
- [Escopo de certificação](#certification-scope)
- [Processo de Certificação](#certification-process)
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

Parte do programa de Conformidade de Aplicativos do Microsoft 365, a Certificação Microsoft 365 oferece garantia e confiança às organizações corporativas de que os dados e a privacidade estão adequadamente protegidos e protegidos ao integrar aplicativos/complementos de desenvolvedores de terceiros na plataforma Microsoft 365. Aplicativos e complementos que passam na validação serão designados Microsoft 365 **Certificados** em todo o Microsoft 365 ecossistema. 

Ao participar do programa de Certificação Microsoft 365, você está concordando com esses termos complementares e em conformidade com qualquer documentação que acompanha a sua participação no programa de Certificação Microsoft 365 com a Microsoft Corporation ("Microsoft", "nós", "nós" ou "nosso"). Você representa e garante que tem autoridade para aceitar esses termos complementares de Certificação Microsoft 365 em nome de si mesmo, de uma empresa e/ou de outra entidade, conforme aplicável. Podemos alterar, alterar ou encerrar esses termos suplementares a qualquer momento. Sua participação contínua no programa Microsoft 365 certificação após qualquer alteração ou alteração significa que você concorda com os novos termos suplementares. Se você não concordar com os novos termos suplementares ou se encerrarmos esses termos suplementares, você deve parar de participar do programa Microsoft 365 Certificação.

Este documento destina-se a ISVs (Fornecedores de Software Independentes) para fornecer informações sobre o processo de Certificação Microsoft 365, pré-requisitos para iniciar o processo e detalhes de controles de segurança específicos que os ISVs devem ter no local.  Informações gerais do programa Microsoft 365 Conformidade de Aplicativos podem ser encontradas na página Microsoft 365 do programa de Conformidade de [Aplicativos.](https://docs.microsoft.com/microsoft-365-app-certification/overview) 

> [!IMPORTANT]
> Atualmente, a Microsoft 365 certificação é limitada:
>* Microsoft Teams aplicativos (Guias, Bots etc.) .
>* Aplicativos/Complementos do Sharepoint
>* Office Complementos (Word, Excel, PowerPoint, Outlook, Project, OneNote)

## <a name="prerequisites"></a>Pré-requisitos

### <a name="publisher-attestation"></a>Atestado do Editor

Antes de receber o Microsoft 365 de Certificação, você deve ter concluído Publisher Atestado. No entanto, você pode iniciar o Microsoft 365 de Certificação antes de concluir Publisher Atestado.  

### <a name="read-the-microsoft-365-certification-specification"></a>Ler a especificação Microsoft 365 certificação

A Microsoft recomenda que todos os ISVs (Fornecedor de Software Independente) leiam essa Especificação de Certificação Microsoft 365 em sua totalidade para garantir que todos os controles aplicáveis sejam atendidos pelo ambiente no escopo e pelo aplicativo/complemento. Isso ajudará a garantir um processo de avaliação suave.

## <a name="microsoft-365-certification-specification-updates"></a>Microsoft 365 Atualizações de especificação de certificação 

As atualizações para a especificação Microsoft 365 certificação são previstas aproximadamente a cada seis a doze meses. Essas atualizações podem introduzir novos domínios de segurança de destino e/ou controles de segurança. As atualizações serão baseadas em comentários do desenvolvedor, alterações no cenário de ameaças e para aumentar a linha de base de segurança do programa à medida que ele amadurece. 

OS ISVs que já iniciaram a avaliação de certificação Microsoft 365 podem continuar a avaliação com a versão da Especificação de Certificação Microsoft 365 que foi válida quando a avaliação foi iniciada. Todos os novos envios, incluindo a recertificação anual, serão necessários para serem avaliados em relação à versão publicada.

> [!NOTE]
> Você não precisa estar em conformidade com todos os controles dentro Microsoft 365 Especificação de Certificação para receber uma certificação. No entanto, os limites de passagem (que não serão divulgados) estão em uso para cada um dos domínios de segurança discutidos neste Microsoft 365 Especificação de Certificação. Alguns controles serão classados como um "**Falha** Difícil ", o que significa que a falta desses controles de segurança resultará em uma avaliação com falha. 

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

Antes de iniciar o processo de certificação, você precisará ter escompletado com êxito seu Publisher Atestado. Suas respostas de atestado serão usadas em suporte ao processo de Certificação Microsoft 365 e continuarão da seguinte forma:

1.  Revise sua documentação Publisher atestado para garantir que ela ainda esteja precisa com seu ambiente atual.
2.  Revise o guia Microsoft 365 de envio de certificação para garantir que você possa atender a todos os controles antes de iniciar.
3.  Clique em "Iniciar Certificação" no Partner Center e envie seu Envio Inicial de Documento. Suas respostas aqui ajudarão a determinar o escopo da avaliação.
4.  Você receberá uma listagem completa de controles para os quais você precisará fornecer evidências para sua avaliação.
5.  Enviar evidências que demonstram que todos os controles de certificação no escopo Microsoft 365 foram atendidos em uma janela de 60 dias.
6.  Verifique o envio com frequência para ver se você tem algum comentário ou solicitações pendentes que exigem sua atenção. Depois que as evidências foram aprovadas para todos os controles, você receberá uma certificação Microsoft 365. 


> [!IMPORTANT]
> **Período de tempo de envio:** É previsto que, em média, o processo de avaliação deve levar 30 dias, desde que você possa verificar o status do envio com frequência e responder a comentários e solicitações de evidências complementares em tempo hábil. Ao iniciar o processo de certificação, é permitido um máximo de 60 dias para concluir a avaliação. Se todos os envios não foram concluídos dentro do período de tempo de 60 dias, o envio será emitido como uma falha e o processo deve começar novamente. Esses resultados não serão divulgados.


## <a name="initial-document-submission"></a>Envio inicial de documento

O envio inicial do documento ajudará os analistas de certificação a executar o escopo e a determinar o que estará no escopo de sua avaliação. Depois disso, você será obrigado a enviar documentação de suporte e evidências usadas para realizar a avaliação. Seu envio inicial deve incluir as informações especificadas abaixo:

| **Visão &nbsp; geral da documentação**     |   **Detalhes da documentação**  |
| -------------------------| -----------------------------|
|**Descrição do aplicativo/do complemento** | Uma descrição da finalidade e funcionalidade do aplicativo/add-in. Isso deve fornecer ao analista de certificação uma boa compreensão de como o aplicativo/complemento funciona e qual é o uso pretendido
|**Relatório de Testes de Penetração** |Um relatório de teste de penetração concluído nos últimos 12 meses. Este relatório deve incluir o ambiente que dá suporte à implantação do aplicativo/adicionar juntamente com qualquer ambiente adicional que suporte a operação do aplicativo/add-in. **Observação:** se você não fizer testes anuais de penetração, poderá optar por fazê-los por meio do processo de certificação.|
|**Diagramas de arquitetura**|Um diagrama de arquitetura lógica que representa uma visão geral de alto nível da infraestrutura de suporte do seu aplicativo/complemento. Isso deve incluir **todos os ambientes** de hospedagem e a infraestrutura de suporte que suporta o aplicativo/complemento. Este diagrama DEVE representar todos os diferentes componentes do sistema de suporte no ambiente para ajudar os analistas de certificação a entender os sistemas no escopo e ajudar a determinar a amostragem. Indique também qual tipo de ambiente de hospedagem é usado; ISV Hospedado, IaaS, PaaS ou Híbrido. **Observação:** Onde o SaaS é usado, indique os vários serviços SaaS usados para fornecer os serviços de suporte dentro do ambiente.|
|**Public Footprint** | Detalhando **todos os** endereços IP públicos e URLs usados pela infraestrutura de suporte. Isso deve incluir o intervalo de IP de tabela completa alocado para o ambiente, a menos que a segmentação adequada tenha sido implementada para dividir o intervalo em uso (evidências adequadas de segmentação serão necessárias)|
|**Diagramas de fluxo de dados** |Flow diagramas detalhando o seguinte:
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
|**Confirmação de conformidade**|Documentação de suporte para estruturas de segurança externas incluídas no Publisher envio de Atestado ou a serem consideradas ao analisar os controles Microsoft 365 Certificação. Atualmente, os três seguintes são suportados:|
||&#x2713; atestado de conformidade (AOC) pci [DSS.](#pci-dss)|
||&#x2713; relatórios [SOC 2](#soc-2) Tipo I/Type II.|
||&#x2713; [ISMS](#isms)  /  [IEC](#iec) - IEC 1S0/IEC 27001 Declaração de Aplicabilidade (SoA) e Certificação.|
|**Dependências da Web**|Documentação listando todas as dependências usadas pelo aplicativo/complemento com as versões em execução atuais.|
|**Inventário de software**|Um inventário de software atualizado que inclui todos os softwares usados no ambiente no escopo juntamente com as versões.|
|**Inventário de Hardware**| Um inventário de hardware atualizado usado pela infraestrutura de suporte. Isso será usado para ajudar na amostragem ao executar a fase de avaliação. Se seu ambiente incluir o PaaS, forneça detalhes dos serviços consumidos.|

## <a name="evidence-collection-and-assessment-activities"></a>Atividades de coleta e avaliação de evidências

Os analistas de certificação precisarão revisar evidências em todos os componentes do sistema no conjunto de exemplos definido. Os tipos de evidência necessários para dar suporte ao processo de avaliação incluem qualquer ou todos os seguintes:

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

Os analistas de certificação analisarão as evidências fornecidas para determinar se você atendeu adequadamente aos controles desta especificação Microsoft 365 Certificação. 

Sempre que possível e para reduzir o tempo necessário para concluir a avaliação, toda ou qualquer documentação detalhada no [Envio](#initial-document-submission)Inicial de Documentação deve ser fornecida   com antecedência.

Os analistas de certificação primeiro revisarão as evidências fornecidas do envio da documentação inicial e as informações de atestado Publisher para identificar linhas apropriadas de investigação, tamanho de amostragem e a necessidade de obter mais evidências conforme detalhado acima.  Os analistas de certificação analisarão todas as informações coletadas para tirar conclusões sobre como e se você está a atender aos controles dentro desta especificação de certificação Microsoft 365 certificação. 

## <a name="app-certification-criteria"></a>Critérios de certificação de aplicativos

Seu aplicativo, a infraestrutura de suporte e a documentação de suporte serão avaliados nos seguintes domínios de segurança:

1. [**Segurança de Aplicativo**](#application-security)
1. [**Segurança Operacional / Implantação Segura**](#operational-security)
1. [**Segurança e privacidade de tratamento de dados**](#data-handling-security-and-privacy)

Cada um desses domínios de segurança inclui controles de chave específicos que abrangem um ou mais requisitos específicos que serão avaliados como parte do processo de avaliação. Para garantir que Microsoft 365 certificação seja inclusiva para desenvolvedores de todos os tamanhos, cada um dos domínios de segurança é avaliado usando um sistema de pontuação para determinar uma pontuação geral de cada um dos domínios. As pontuações para cada um dos controles de certificação Microsoft 365 são alocadas entre 1 (baixo) e 3 (alto) com base no risco percebido de que o controle não está sendo atendido. Cada um dos domínios de segurança terá uma marca percentual mínima a ser considerada uma passagem. Determinados elementos dessa especificação incluem alguns critérios de falha automática:

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

### <a name="graphapi-permission-validation"></a>Validação de permissão GraphAPI

A validação de permissão GraphAPI é realizada para validar que o aplicativo/add-in não solicita permissões muito permissivas. Isso é realizado verificando manualmente quais permissões são solicitadas. Os analistas de certificação referenciam essas verificações Publisher envio de Atestado e avaliam o nível de acesso solicitado para garantir que as práticas de "privilégio mínimo" sejam atendidas. Onde os analistas de certificação acreditam que essas práticas de "privilégio mínimo" não estão sendo atendidas, os analistas de certificação terão uma discussão aberta com você para validar a justificativa comercial para as permissões que estão sendo solicitadas. Quaisquer discrepâncias em relação Publisher envio de Atestado encontrado durante esta revisão também receberão comentários para que seu Publisher Atestado possa ser atualizado. 

### <a name="external-connectivity-checks"></a>Verificações de Conectividade Externa

Como parte da avaliação, um Analista realizará uma leve caminhada pela funcionalidade de aplicativos para identificar conexões fora do M365.  Todas as conexões que não são identificadas como sendo da Microsoft ou conexões diretas com seu serviço serão sinalizadas e discutidas durante a avaliação.

### <a name="application-security-testing"></a>Teste de Segurança de Aplicativo

Uma revisão adequada dos riscos associados ao seu aplicativo/add-in e ao ambiente de suporte é essencial para fornecer aos clientes garantia na segurança do aplicativo/do add-in. O teste de segurança do aplicativo na forma de teste de penetração DEVE ser realizado se seu aplicativo tiver alguma conectividade com qualquer serviço que não seja publicado pela Microsoft. Se seu aplicativo operar autônomo sem conectividade com nenhum serviço ou back-end que não seja da Microsoft, o teste de penetração não será necessário.


**Escopo de teste de penetração**

As atividades  de teste de penetração DEVEM incluir o ambiente que dá suporte à implantação do aplicativo/add-in (por exemplo, em que o código do aplicativo/add-in está hospedado, que normalmente será o recurso dentro do arquivo de manifesto) juntamente com qualquer ambiente adicional que suporte a operação do aplicativo/add-in (por exemplo, se o aplicativo/complemento falar com outros aplicativos Web fora do Microsoft 365).  Ao definir o escopo, é necessário ter cuidado para garantir que todos os sistemas ou ambientes "conectados" que possam afetar a segurança do ambiente no escopo também sejam incluídos em TODAS as atividades de teste de penetração. 

Onde as técnicas são usadas para segmentar os ambientes no escopo de outros ambientes, as atividades de teste de penetração DEVEM validar a eficácia das técnicas de segmentação. Isso deve ser detalhado no relatório de teste de penetração. 

Os relatórios de teste de penetração serão revisados **** para garantir que não haja vulnerabilidades que atendem aos seguintes critérios de falha automática descritos nos controles abaixo.
 
**Requisitos de teste de penetração**
||**Controles de Teste de Penetração**|
| -------------------------|-----------------------------|
|**Critérios Gerais**| **Controls**|
|| Testes de penetração de aplicativo e infraestrutura **DEVEM** ser realizados anualmente (a cada 12 meses) e conduzidos por uma empresa independente confiável. |
|| A correção de vulnerabilidades críticas  e de alto risco identificadas deve ser concluída dentro de um mês após a conclusão do teste de penetração ou mais cedo, dependendo do processo de correção documentado. |
|| O espaço externo completo (endereços IP, URLs, pontos de extremidade da API, etc.) DEVE ser incluído no escopo do teste de penetração e deve ser documentado no relatório de teste de penetração. |
|| O teste de penetração de aplicativo Web DEVE incluir todas as classes de vulnerabilidade; por exemplo, o CWE OWASP Top 10 ou SANS Top 25 mais atual. |
|| O reteste de vulnerabilidades identificadas pela empresa de teste de penetração não é necessário — a  correção e a autoavaliação são suficientes, no entanto, evidências adequadas para demonstrar a correção suficiente DEVEM ser fornecidas durante a avaliação.|
|**Critérios de falha automática:**|**Controls**|
|| Presença de um sistema operacional sem suporte. |
|| Presença de contas administrativas padrão, enumeradas ou previsíveis.|
|| Presença de SQL de injeção.|
|| Presença de scripts entre sites.|
|| Presença de vulnerabilidades atravessadas de diretório (caminho de arquivo).|
|| Presença de vulnerabilidades HTTP, por exemplo, divisão de resposta do cabeçalho, roubo de solicitação e ataques de Desync.|
|| Presença de divulgação de código-fonte (incluindo [LFI](#lfi)).|
|| Qualquer pontuação crítica ou alta, conforme definido pelas diretrizes de gerenciamento de patch CVSS.|
|| Qualquer vulnerabilidade técnica significativa que possa ser prontamente explorada para comprometer uma grande quantidade de EUII ou OUI.|






> [!IMPORTANT]
>Os relatórios devem ser capazes de fornecer garantia suficiente de que tudo o que está detalhado na seção Especificação de Teste de Segurança de Aplicativo pode ser demonstrado.


**Requisitos e custo de testes de penetração**

Para ISVs que atualmente não se envolvem em testes de penetração, o teste de penetração está incluído na certificação Microsoft 365. A Microsoft organizará e cobrirá o custo de um teste de penetração por até 12 dias de teste manual. Os custos dos testes de penetração são calculados com base no número de dias necessários para testar o ambiente. Quaisquer despesas superiores a 12 dias de teste serão de responsabilidade do ISV. O ISV também será responsável por demonstrar que as vulnerabilidades identificadas no teste de penetração foram remediadas antes da certificação ser concedida, mas não precisam produzir um relatório limpo.

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

### <a name="controls"></a>Controles

|**Família de Controle**| **Controls**|
| ------------------------|------------------------------ |
| **Proteção contra Malware**|Forneça documentação de política que rege práticas e procedimentos anti-vírus.|
||Forneça evidências demonstradas de que o software antivírus está sendo executado em todos os componentes do sistema amostrados.|
||Forneça evidências demonstrativas de que as assinaturas de antivírus estão atualizadas em todos os ambientes (dentro de 1 dia).|
||Forneça evidências demonstradas de que o antivírus está configurado para executar a verificação no acesso ou a verificação periódica em todos os componentes do sistema amostrados. Observação: se a verificação ao acessar não estiver habilitada, um mínimo de verificação e alerta diário deve ser habilitado.|
||Forneça evidências demonstradas de que o antivírus está configurado para bloquear automaticamente malware ou quarentena e alertar todos os componentes do sistema amostrados.|
|**Controles de** aplicativo : somente necessário se o anti-malware tradicional não for usado|Forneça evidências demonstradas de que os aplicativos são aprovados antes de serem implantados.|
||Forneça evidências demonstradas de que uma lista completa de aplicativos aprovados com justificativa comercial existe e é mantida.|
||Forneça documentação de suporte detalhando que o software de controle de aplicativo está configurado para atender a mecanismos de controle de aplicativo específicos. (Exemplo: listagem permitida: sample1, sample3, assinatura de código)|
||Forneça evidências demonstradas de que o controle do aplicativo está configurado como documentado de todos os componentes do sistema amostrados.|
|**Gerenciamento de Patch - Classificação de Risco**| Documentação de política de fornecimento que rege como novas vulnerabilidades de segurança são identificadas e atribuídas a uma pontuação de risco.|
||Forneça evidências de como novas vulnerabilidades de segurança são identificadas.|
||Forneça evidências demonstrando que todas as vulnerabilidades são atribuídas a uma classificação de risco uma vez identificada.|
|**Patch Managmeent - Patching**|Fornecer documentação de política para correção de componentes do sistema no escopo que inclui o período de tempo mínimo de correção adequado para vulnerabilidades críticas, de alto e médio risco; e desativação de qualquer software e sistemas operacionais sem suporte.|
||Forneça evidências demonstradas de que todos os componentes do sistema amostrados estão sendo remendados.|
||Forneça evidências demonstradas de que quaisquer sistemas operacionais e componentes de software sem suporte não são usados no ambiente.|
|**Verificação de vulnerabilidade**|Forneça os relatórios de verificação de vulnerabilidade de aplicativo Web e infraestrutura trimestral. A verificação precisa ser realizada em todo o espaço público (endereços IP e URLs) e intervalos IP internos.|
||Forneça evidências demonstrativas de que a correção de vulnerabilidades identificadas durante a verificação de vulnerabilidades são corrigidas em linha com seu período de tempo de correção documentado.|
|**Firewalls**|Forneça documentação de política que rege práticas e procedimentos de gerenciamento de firewall.|
||Forneça evidências demonstrativas de que quaisquer credenciais administrativas padrão são alteradas antes da instalação em ambientes de produção.|
||Forneça evidências demonstrativas de que os firewalls estão instalados no limite do ambiente no escopo e instalados entre a rede de perímetro (também conhecida como DMZ, zona desmilitarizada e sub-rede de tela) e redes confiáveis internas.|
||Forneça evidências demonstrativas de que todo o acesso público termina na zona desmilitarizada (DMZ).|
||Forneça evidências demonstraveis de que todo o tráfego permitido pelo firewall passa por um processo de aprovação.|
||Forneça evidências demonstraveis de que a base de regras de firewall está configurada para soltar o tráfego não definido explicitamente.|
||Forneça evidências demonstrativas de que o firewall oferece suporte apenas a criptografia forte em todas as interfaces administrativas que não são do console.|
||Forneça evidências demonstrativas de que você está executando avaliações de regras de firewall pelo menos a cada 6 meses.|
|**WaF (OPTIONAL)**: Crédito adicional será recompensado por satisfazer os seguintes controles.|Forneça evidências demonstradas de que o WaF (Web Application Firewall) está configurado para monitorar, alertar e bloquear ativamente o tráfego mal-intencionado.|
||Forneça evidências demonstrativas de que o WAF dá suporte ao descarregamento SSL.|
||Forneça evidências demonstrativas de que o WAF está protegido contra algumas ou todas as classes de vulnerabilidades a seguir, de acordo com o Conjunto de Regras Principais OWASP (3.0 ou 3.1) |
|**Alterar Controle**|Forneça documentação de política que rege processos de controle de alteração.|
||Forneça evidências demonstrativas de que ambientes de desenvolvimento e teste impõem a separação de funções do ambiente de produção.|
||Forneça evidências demonstrativas de que dados de produção confidenciais não são usados nos ambientes de desenvolvimento ou teste.|
||Forneça evidências demonstradas de que as solicitações de alteração documentadas contêm impacto da alteração, detalhes dos procedimentos de back-out e dos testes a serem executados.|
||Forneça evidências demonstradas de que as solicitações de alteração passam por um processo de autorização e aprovação.|
|**Desenvolvimento/implantação de software seguro**| Forneça políticas e procedimentos que oferecem suporte a desenvolvimento e implantação de software seguro, incluindo diretrizes de práticas práticas de codificação seguras contra classes comuns de vulnerabilidade, como, OWASP Top 10 ou SANS Top 25 CWE.|
|| Forneça evidências demonstrativas de que as alterações de código passam por um processo de revisão e autorização por um segundo revistor.|
|| Forneça evidências demonstraáveis de que os desenvolvedores passam por treinamento de desenvolvimento de software seguro anualmente.|
|| Forneça evidências demonstrativas de que repositórios de código são protegidos com autenticação multifator (MFA).|
|| Forneça evidências demonstrativas de que os controles de acesso estão no local para proteger repositórios de código.
|**Gerenciamento de contas**| Forneça a documentação de política que rege as práticas e os procedimentos de gerenciamento de contas.
||Forneça evidências demonstrativas de que as credenciais padrão estão desabilitadas, removidas ou alteradas nos componentes do sistema amostrados.|
||Forneça evidências demonstradas de que a criação, modificação e exclusão da conta passa por um processo de aprovação estabelecido.|
||Forneça evidências demonstrativas de que um processo está em uso para desabilitar ou excluir contas não usadas dentro de 3 meses.|
||Forneça evidências demonstrativas de que uma política de senha forte ou outras mitigações adequadas para proteger as credenciais do usuário estão em uso.  O seguinte deve ser usado como uma diretriz mínima: comprimento mínimo de senha de 8 caracteres, limite de bloqueio de conta de no máximo 10 tentativas, histórico de senha de no mínimo 5 senhas, imposição do uso de senha forte|
|**Detecção e prevenção contra intrusões (OPCIONAL):** Crédito adicional será recompensado por satisfazer os seguintes controles|Forneça evidências demonstrativas de que os Sistemas de Detecção e Prevenção de Intrusões (IDPS) são implantados no perímetro dos ambientes no escopo.|
||Forneça evidências demonstrativas de que as assinaturas IDPS são mantidas atuais (dentro de 24 horas).|
||Forneça evidências demonstrativas de que o IDPS está configurado para dar suporte à inspeção TLS de todo o tráfego web de entrada.|
||Forneça evidências demonstrativas de que o IDPS está configurado para monitorar todos os fluxos de tráfego de entrada.|
||Forneça evidências demonstrativas de que o IDPS está configurado para monitorar todos os fluxos de tráfego de saída.|
|**Log de Eventos de Segurança** |Forneça documentação de política para práticas recomendadas e procedimentos que governam o registro em log de eventos de segurança.|
|| Forneça evidências demonstrativas que mostram que o log de eventos de segurança está definido em todos os componentes do sistema amostrados para registrar os seguintes eventos: acesso do usuário aos componentes do sistema e ao aplicativo, Todas as ações tomadas por um usuário com privilégios elevados, tentativas de acesso lógico inválidos Criação ou modificação de conta privilegiada, adulteração de log de eventos, Desabilitação de ferramentas de segurança (como antimalware ou registro em log de eventos) , Registro em log antimalware (como atualizações, detecção de malware e falhas de verificação).,eventos IDPS e WAF, se configurados|
||Forneça evidências demonstrativas de que os eventos de segurança registrados contêm as seguintes informações mínimas: Usuário, Tipo de evento, Data e hora, Indicadores de sucesso ou falha, Rótulo que identifica o sistema afetado|
||Forneça evidências demonstradas de que todos os componentes do sistema amostrados são sincronizados em tempo com os mesmos servidores primários e secundários.|
||Forneça evidências demonstradas quando sistemas públicos voltados para o público estão em uso, de que os logs de eventos de segurança estão sendo enviados para uma solução de registro em log centralizada que não está dentro da rede de perímetro.|
||Forneça evidências demonstraveis para mostrar que a solução de registro em log centralizado está protegida contra violações não autorizadas de dados de registro em log.|
||Forneça evidências demonstraveis de que um mínimo de 30 dias de dados de registro em log de eventos de segurança está disponível imediatamente, com 90 dias de logs de eventos de segurança sendo mantidos.|
|**Revisão (Dados de Log)** |Forneça documentação de política que rege práticas e procedimentos de revisão de log.|
||Forneça evidências demonstrativas de que os logs são revisados diariamente por uma ferramenta humana ou automatizada para identificar possíveis eventos de segurança.|
||Forneça evidências demonstrativas de que possíveis eventos e anomalias de segurança são investigados e remediados.|
|**Alerta** | Forneça documentação de política que rege práticas e procedimentos de alerta de eventos de segurança.|
|| Forneça evidências demonstrativas de que os alertas são disparados para triagem imediata para os seguintes tipos de eventos de segurança: criação ou modificações de conta privilegiadas, eventos de vírus ou malware, adulteração de log de eventos, IDPS ou eventos WAF
|**Gerenciamento de risco**|Forneça evidências demonstradas de que um processo formal de gerenciamento de risco de segurança de informações está estabelecido.|
||Forneça evidências demonstrativas de que uma avaliação formal de risco ocorre anualmente, no mínimo.|
||Forneça evidências demonstrativas de que a avaliação de risco de segurança da informação inclui ameaças, vulnerabilidades ou o equivalente.|
||Forneça evidências demonstrativas de que a avaliação de risco de segurança da informação inclui impacto, matriz de risco de probabilidade ou o equivalente.|
||Forneça evidências demonstrativas de que a avaliação de risco de segurança da informação inclui um registro de risco e um plano de tratamento.|
|**Resposta a incidentes**|Forneça o plano de resposta a incidentes de segurança (IRP).|
||Forneça evidências demonstrativas de que o IRP de segurança inclui um processo de comunicação documentado para garantir a notificação em tempo há tempo para os principais participantes, como marcas de pagamento e adquirentes, órgãos regulatórios, autoridades de supervisão, diretores e clientes.|
||Forneça evidências demonstraveis de que todos os membros da equipe de resposta a incidentes concluíram o treinamento anual ou um exercício de tabela superior.|
||Forneça evidências demonstraveis para mostrar que o IRP de segurança é atualizado com base em lições aprendidas ou alterações organizacionais.|

## <a name="data-handling-security-and-privacy"></a>Segurança e privacidade de tratamento de dados

Os dados em trânsito entre o usuário do aplicativo, os serviços intermediários e os sistemas do ISV serão necessários para serem protegidos pela criptografia por meio de uma conexão TLS que suporte um mínimo de TLS v1.1. *Consulte* [**Apêndice A**](#appendix-a).

Onde seu aplicativo recupera e armazena dados M365, você será obrigado a implementar um esquema de criptografia de armazenamento de dados que siga a especificação conforme definido no [**Apêndice B**](#appendix-a).

### <a name="controls"></a>Controles

|**Família de Controle**| **Controls** |
| -----------------------|-------------------------------- |
|**Dados em Trânsito**| Fornecer evidências demonstrativas de que a configuração TLS atende ou excede os requisitos de criptografia dentro dos requisitos de configuração de [perfil TLS](https://docs.microsoft.com/microsoft-365-app-certification/docs/certification-submission-guide#appendix-a)|
||Forneça evidências demonstrativas de que a compactação TLS está desabilitada em todos os serviços voltados para o público que lidam com solicitações da Web.|
||Forneça evidências demonstrativas de que a segurança estrita de transporte TLS HTTP está habilitada e configurada para >= 15552000 em todos os sites.|
|**Dados em Repouso**| Forneça evidências demonstrativas de que os dados em repouso são criptografados em linha com os requisitos de perfil de criptografia, usando algoritmos de criptografia como AES, Maivosa, TDES e tamanhos de chave de criptografia de 128 bits e 256 bits.|
||Forneça evidências demonstraíveis de que a função hash ou autenticação de mensagem (HMAC-SHA1) é usada apenas para proteger dados em repouso em linha com requisitos de perfil de criptografia.|
||Forneça um inventário mostrando todos os dados armazenados, incluindo o local de armazenamento e a criptografia usada para proteger os dados.|
|**Retenção e descarte de dados**|Forneça evidências demonstradas de que um período de retenção de dados aprovado e documentado está formalmente estabelecido.|
||Forneça evidências demonstradas de que os dados mantidos coincidem com o período de retenção definido.|
||Forneça evidências demonstrativos de que os processos estão no local para excluir dados com segurança após o período de retenção.|
|**Gerenciamento de Acesso a Dados**|Forneça uma lista de todos os indivíduos com acesso a dados ou chaves de criptografia, incluindo a justificativa comercial.|
||Forneça evidências demonstrativas de que os indivíduos amostrados que têm acesso a dados ou chaves de criptografia foram formalmente aprovados, detalhando os privilégios necessários para sua função de trabalho.|
||Forneça evidências demonstrativas de que os indivíduos amostrados que têm acesso a dados ou chaves de criptografia têm apenas os privilégios incluídos na aprovação.|
||Forneça uma lista de todos os terceiros com os dados do cliente compartilhados.|
||Forneça evidências demonstrativas de que todos os dados do cliente de terceiros que consomem possuem contratos de compartilhamento.|
|**RGPD** (se aplicável)| Forneça um processo de solicitação de acesso de assunto documentado (SAR) e forneça evidências demonstrando que os titulares de dados são capazes de criar SARs.|
||Forneça evidências demonstradas de que você é capaz de identificar todos os locais dos dados dos titulares de dados ao responder a um SAR.|
||Você mantém um aviso de privacidade que deve conter os detalhes das empresas (Nome, Endereço, etc.).|
||Você mantém um aviso de privacidade que deve explicar os tipos de dados pessoais que estão sendo processados.|
||Você mantém um aviso de privacidade que deve explicar a legalidade do processamento de dados pessoais|
||Você mantém um aviso de privacidade que explica em detalhes os direitos do sujeito dos dados: Direito de ser informado, Direito de acesso pelo assunto de dados, Direito à eliminação, Direito à restrição do processamento, Direito à portabilidade de dados, Direito a objeto, Direitos em relação à tomada de decisão automatizada, incluindo criação de perfil.|
|| Você mantém um aviso de privacidade que deve explicar por quanto tempo os dados pessoais serão mantidos.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisão de estruturas de conformidade externa opcionais

Embora não seja necessário, se você estiver em conformidade com ISO 27001, PCI DSS ou SOC2, poderá optar por usar essas certificações para atender a alguns dos controles de Certificação Microsoft 365. Os analistas de certificação tentarão alinhar as estruturas de segurança externa existentes à especificação Microsoft 365 Certificação. No entanto, se a documentação de suporte não puder fornecer garantia de que os controles de certificação do Microsoft 365 foram avaliados como parte da auditoria/avaliação de estruturas de segurança externas, você precisará fornecer evidências adicionais sobre a adoção desses controles.

A documentação deve demonstrar adequadamente que o ambiente no escopo da certificação Microsoft 365 foi incluído no escopo dessas estruturas de segurança externas. A validação dessas estruturas de segurança será atendida aceitando evidências de certificações válidas conduzidas por empresas de terceiros externos confiáveis. Essas empresas confiáveis devem ser membros de entidades de credenciamento internacionais para programas de conformidade relevantes. Consulte Padrões de certificação e conformidade ISO para ISO 27001 e Avaliadores de Segurança Qualificados (QSA) para PCI DSS.

A tabela a seguir destaca as estruturas externas e a documentação exigidas pelos analistas de certificação como parte desse processo de validação:

| **Standard** | **Requisitos** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Será necessária uma versão pública da **Declaração de** Aplicabilidade (SOA) e uma cópia do certificado ISO 27001 emitido.  O SOA resume sua posição em cada um dos 114 controles de segurança de informações e será usado para identificar se há exclusão de controles que não são detalhados satisfatoriamente no certificado ISO 27001. Se isso não puder ser determinado revendo a versão pública do SOA, o analista poderá precisar de acesso à SOA completa se a ISO 27001 for usada para validar alguns dos controles de Especificação de Certificação Microsoft 365.  Além de validar o escopo das atividades de avaliação da ISO 27001, os analistas também confirmarão a validade da empresa de auditoria, conforme descrito acima.|
|**[PCI DSS](#pci-dss)**| Um documento AOC (Atestado de Conformidade) de Nível **1** válido deve ser fornecido identificando claramente os componentes do aplicativo e do sistema no escopo.  Um AOC de autoavaliação **não será** aceito como evidência das práticas recomendadas de segurança de reunião. O AOC será usado para determinar quais dos controles de Especificação de Certificação Microsoft 365 foram avaliados e confirmados como parte da avaliação do PCI DSS.|
|**[SOC 2](#soc-2)**|O relatório **SOC 2 (Tipo I** ou Tipo II) deve ser atual (emitido nos últimos 15 meses e o período declarado iniciado nos últimos 27 meses) para ser usado como evidência de conformidade com qualquer um dos controles de avaliação dentro desta Especificação de Certificação Microsoft 365.|

Se as estruturas de segurança externas foram incluídas no atestado de Publisher, os analistas de certificação precisarão verificar a validade dessas estruturas de conformidade de segurança como parte da avaliação Microsoft 365 Certificação.

|**Framework** | **Considerações adicionais** |
|-------------- | --------------------|
|ISO 27001| [**Apêndice C**](#appendix-c): Coleção Evidence – Deltas para ISO 27001.|
|PCI DSS | [**Apêndice D**](#appendix-d): Coleção Evidence – Deltas para PCI DSS.|
|SOC 2| [**Apêndice E**](#appendix-e): Coleção Evidence – Deltas para SOC 2.|

> [!NOTE]
> Embora os padrões/estruturas de segurança externos mencionados acima possam ser enviados como prova para atender a alguns dos controles de Certificação do Microsoft 365, passar a Certificação do Microsoft 365 não significa que você passará com êxito em uma auditoria em relação a esses padrões/estruturas. A Microsoft 365 especificação de certificação é apenas um pequeno subconjunto desses padrões/estruturas de segurança que permite que a Microsoft obtenha um nível de garantia em referência à sua postura de segurança.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Requisitos para usar estruturas de conformidade externas

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

**Chave Exchange**

&emsp;&#x2713; ecdh é permitido. A **tecla DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

&emsp;&#x2713; ecdh é permitido. A **tecla DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

## <a name="appendix-c"></a>Apêndice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Coleção Evidence – Delta para ISO 27001

Onde você já atingiu a conformidade ISO27001, as seguintes lacunas do delta não totalmente cobertas pela ISO 27001 precisarão, no mínimo, ser revisadas como parte desta Certificação Microsoft 365.

> [!NOTE]
> Como parte da sua avaliação de certificação do Microsoft 365, o analista de certificação determinará se algum dos controles ISO 27001 mapeados não foi incluído como parte da avaliação iso 27001 e também poderá decidir por exemplo os controles que foram encontrados incluídos para fornecer mais garantia. Todos os requisitos ausentes da ISO 27001 precisarão ser incluídos em suas atividades de avaliação Microsoft 365 Certificação.

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

&#x2713; SQL de injeção.

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

Onde você já atingiu a conformidade com PCI DSS, os seguintes deltas (lacunas) não totalmente cobertos pelo PCI DSS precisarão, no mínimo, ser revisados como parte dessa certificação Microsoft 365.

> [!NOTE]
> Como parte da avaliação de certificação do Microsoft 365, o analista de certificação determinará se qualquer um dos controles PCI DSS mapeados não foi incluído como parte da avaliação do PCI DSS e também poderá decidir por exemplo os controles que foram encontrados incluídos para fornecer mais garantia. Quaisquer requisitos ausentes do PCI DSS precisarão ser incluídos nas atividades de avaliação Microsoft 365 Certificação.

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

&#x2713; SQL de injeção.

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

Quando você já tiver atingido a conformidade do SOC 2, os seguintes deltas (lacunas) não totalmente cobertos pelo SOC 2 precisarão ser revisados como parte dessa Certificação Microsoft 365.

> [!NOTE]
> Como parte da avaliação de certificação do Microsoft 365, o analista de certificação determinará se algum dos controles SOC 2 mapeados não foi incluído como parte da avaliação do SOC 2 e também poderá decidir por exemplo os controles que foram encontrados incluídos para fornecer mais garantia. Quaisquer requisitos ausentes da avaliação do SOC 2 precisarão ser incluídos como parte das atividades de avaliação Microsoft 365 Certificação.

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

&emsp;&#x2713; SQL injeção.

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

A Microsoft reconhece que você implantará aplicativos e armazenará código de aplicativo/complemento em diferentes ambientes de hospedagem. As responsabilidades gerais de alguns dos controles de segurança dentro do Microsoft 365 Certificação dependerão do ambiente de hospedagem que está sendo usado. O Apêndice F analisa os tipos comuns de implantação e os mapeia em relação aos controles de segurança avaliados como parte do processo de avaliação. Os seguintes tipos de implantação de hospedagem foram identificados:

|Tipos de hospedagem  |Descrição  |
|-----|------|
|**ISV hospedado**|Os tipos hospedados pelo ISV podem ser definidos como onde você é responsável pela infraestrutura usada para dar suporte ao ambiente de aplicativo/complemento. Isso pode estar fisicamente localizado em seus próprios data centers ou data centers de terceiros com um serviço de co-localização. Por fim, você tem total propriedade e controle administrativo sobre a infraestrutura de suporte e o ambiente operacional.|
|**Infraestrutura como serviço (IaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-iaas/)|Infraestrutura como serviço é um serviço fornecido pelo qual a infraestrutura de suporte físico é gerenciada e mantida em seu nome pelo provedor de serviços de nuvem (CSP). Normalmente, rede, armazenamento, servidores físicos e a infraestrutura de virtualização são de responsabilidade do CSP. O Sistema Operacional, Middleware, Tempo de Execução, Dados e Aplicativos são as responsabilidades de você. Os recursos de firewall também seriam gerenciados e mantidos por terceiros, no entanto, a manutenção da base de regras de firewall normalmente ainda seria responsabilidade dos consumidores.|
|**Plataforma como serviço/sem servidor (PaaS)** (https://azure.microsoft.com/en-gb/overview/what-is-paas/)| Com Platform as a Service, você é provisionado com uma plataforma gerenciada apresentando um serviço que pode ser consumido. Você não precisa executar funções sysadmin, pois o sistema operacional e a infraestrutura de suporte são gerenciados pelo CSP. Isso normalmente seria usado quando as organizações não querem se preocupar em apresentar um serviço Web e, em vez disso, podem se concentrar em criar o código-fonte do aplicativo Web e publicar o aplicativo Web nos serviços Web gerenciados na nuvem.  Outro exemplo pode ser um serviço de banco de dados em que a conectividade é dada a um banco de dados, no entanto, a infraestrutura de suporte e o aplicativo de banco de dados são abstraídos do consumidor.   **Observação: Serverless e PaaS são semelhantes para a finalidade do tipo de implantação de implantação de hospedagem de certificação do Microsoft 365 Serverless e PasS são considerados da mesma forma**|
|**Híbrida Hospedada**|Com o tipo hospedado híbrido, você pode utilizar vários tipos hospedados para dar suporte a várias partes do ambiente de suporte. Esse pode ser mais o caso em que aplicativos/complementos são usados em várias pilhas M365. Embora a Certificação Microsoft 365 seja suportada em que aplicativos/complementos em vários serviços M365 são desenvolvidos, uma avaliação de todo o ambiente de suporte (entre aplicativos/complementos) precisaria ser avaliada de acordo com cada um dos "Mapeamentos de Tipos Hospedados" aplicáveis. Ocasionalmente, você pode utilizar diferentes tipos hospedados para um único complemento, onde isso está sendo executado, a aplicabilidade dos critérios ainda precisará seguir os critérios "Mapeamentos de Tipos Hospedados" entre os vários tipos hospedados.|
|**Hospedagem Compartilhada**|A hospedagem compartilhada é onde você hospeda o ambiente em uma plataforma compartilhada por vários consumidores individuais. A Microsoft 365 Especificação de Certificação não foi escrita para levar em conta isso devido à adoção da nuvem, a hospedagem compartilhada não é comum. Se você acredita que isso está sendo usado, entre em contato com a Microsoft, pois os requisitos adicionais precisarão ser criados para levar em conta os riscos adicionais sob esse tipo de hospedagem.|


## <a name="appendix-g"></a>Apêndice G

### <a name="microsoft-365-certification-process-workflow"></a>Microsoft 365 Fluxo de trabalho do processo de certificação

![Fluxo de trabalho](ProcessFlow.jpg)

## <a name="learn-more"></a>Saiba mais

[Microsoft 365 Visão geral do programa de conformidade do aplicativo](~/overview.md)  
[O que Microsoft 365 app Publisher Atestado?](~/docs/attestation.md)  
[O que é Microsoft 365 Certificação?](~/docs/enterprise-app-certification-guide.md)

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

*Abra o aplicativo Web Security Project*.

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
