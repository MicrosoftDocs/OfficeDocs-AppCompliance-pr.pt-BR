---
ms.author: oromalle
title: Microsoft 365 de Envio de Certificação do Microsoft 365
author: orionomalley
manager: tonybal
description: Microsoft 365 do Guia de Envio de Certificação do Microsoft 365
keywords: equipes de certificação Microsoft 365 conformidade de segurança m365
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 753b40f63b293fea83705ae8124f5f22cbebe394
ms.sourcegitcommit: 9cc3fe8502a6f21f3f6abb4dd23b99b116c51b8e
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 04/08/2022
ms.locfileid: "64720975"
---
# <a name="microsoft-365-certification-submission-guide"></a>Microsoft 365 de Envio de Certificação do Microsoft 365

**Neste artigo:**
- [Introdução](#introduction)
- [Pré-requisitos](#prerequisites) 
- [atualizações Microsoft 365 especificação de certificação do Microsoft 365](#microsoft-365-certification-specification-updates)
- [Escopo de certificação](#certification-scope)
- [Processo de certificação](#certification-process)
- [Envio inicial de documento](#initial-document-submission) 
- [Coleta de evidências e atividades de avaliação](#evidence-collection-and-assessment-activities)
- [Critérios de certificação](#app-certification-criteria)
- [Segurança de Aplicativo](#application-security)
- [Segurança operacional](#operational-security) 
- [Segurança e privacidade do tratamento de dados](#data-handling-security-and-privacy)
- [Revisão opcional de estruturas de conformidade externa](#optional-external-compliance-frameworks-review)
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

Parte do programa de Conformidade de Aplicativos do Microsoft 365, a Certificação Microsoft 365 oferece garantia e confiança às organizações corporativas de que os dados e a privacidade são adequadamente protegidos e protegidos ao integrar aplicativos/suplementos de desenvolvedores de terceiros à plataforma Microsoft 365. Aplicativos e suplementos aprovados na validação serão designados **Microsoft 365 Certificados** em todo o Microsoft 365 ecossistema. 

Ao participar do programa de Certificação do Microsoft 365, você está concordando com esses termos complementares e em conformidade com qualquer documentação complementar que se aplique à sua participação no programa de Certificação do Microsoft 365 com a Microsoft Corporation ("Microsoft", "nós", "nós" ou "nosso"). Você representa e garante a nós que tem autoridade para aceitar esses termos complementares de Certificação Microsoft 365 em nome de si mesmo, de uma empresa e/ou de outra entidade, conforme aplicável. Podemos alterar, alterar ou encerrar esses termos complementares a qualquer momento. Sua participação contínua no programa Microsoft 365 certificação após qualquer alteração ou alteração significa que você concorda com os novos termos complementares. Se você não concordar com os novos termos complementares ou se encerrarmos esses termos complementares, deverá parar de participar do programa Microsoft 365 Certificação.

Este documento destina-se a ISVs (Fornecedores Independentes de Software) para fornecer informações sobre o processo de Certificação do Microsoft 365, pré-requisitos para iniciar o processo e detalhes de controles de segurança específicos que os ISVs devem ter em vigor.  Informações gerais do programa Microsoft 365 conformidade do aplicativo podem ser encontradas na página Microsoft 365 do programa de Conformidade de [Aplicativos](../overview.md). 

> [!IMPORTANT]
> Atualmente, Microsoft 365 certificação é aplicável a todos:
>* Microsoft Teams aplicativos (Guias, Bots etc.).
>* Aplicativos/Suplementos do Sharepoint
>* Office suplementos (Word, Excel, PowerPoint, Outlook, Project, OneNote)
>* Webapps

## <a name="prerequisites"></a>Pré-requisitos

### <a name="publisher-attestation"></a>Atestado do Editor

Antes de receber o Microsoft 365 de Certificação, você deve ter concluído Publisher Atestado. No entanto, você pode iniciar o Microsoft 365 de Certificação antes de concluir Publisher atestado.  

### <a name="read-the-microsoft-365-certification-specification"></a>Ler a especificação Microsoft 365 certificação

A Microsoft recomenda que todos os ISVs (Fornecedor Independente de Software) leiam essa Especificação de Certificação Microsoft 365 em sua totalidade para garantir que todos os controles aplicáveis sejam atendidos pelo ambiente no escopo e pelo aplicativo/suplemento. Isso ajudará a garantir um processo de avaliação suave.

## <a name="microsoft-365-certification-specification-updates"></a>atualizações Microsoft 365 especificação de certificação do Microsoft 365 

As atualizações da especificação Microsoft 365 certificação são previstas aproximadamente a cada seis a doze meses. Essas atualizações podem introduzir novos domínios de segurança de destino e/ou controles de segurança. As atualizações serão baseadas nos comentários dos desenvolvedores, nas alterações no cenário de ameaças e no aumento da linha de base de segurança do programa conforme ele amadurece. 

Os ISVs que já iniciaram a avaliação de certificação Microsoft 365 podem continuar a avaliação com a versão da Especificação de Certificação Microsoft 365 que era válida quando a avaliação foi iniciada. Todos os novos envios, incluindo a recertificação anual, precisarão ser avaliados em relação à versão publicada.

> [!NOTE]
> Você não precisa estar em conformidade com todos os controles dentro desta especificação Microsoft 365 certificação para receber uma certificação. No entanto, os limites de passagem (que não serão divulgados) estão em vigor para cada um dos domínios de segurança discutidos nesta especificação Microsoft 365 certificação. Alguns controles serão classificados como uma "**Falha** Difícil", o que significa que a falta desses controles de segurança resultará em uma avaliação com falha. 

## <a name="certification-scope"></a>Escopo de certificação

O **ambiente no escopo** é o ambiente que dá suporte à entrega do código do aplicativo/suplemento e dá suporte a sistemas de back-end com os qual o aplicativo/suplemento pode estar se comunicando. Todos os ambientes conectados adicionais também serão incluídos no escopo, a menos que a segmentação adequada esteja em vigor e os ambientes conectados não possam afetar a segurança do ambiente no escopo. Todos os ambientes de recuperação de desastre também precisarão ser incluídos dentro do escopo da avaliação, pois esses ambientes seriam necessários para atender ao serviço caso algo acontecesse com o ambiente primário.  Os  **componentes do sistema**  de escopo termin referenciam **TODOS os** dispositivos e sistemas usados no ambiente no escopo. Os componentes no escopo incluem, mas não estão limitados a:
* Os aplicativos Web.
* Servidores.
* Firewalls (ou equivalentes).
* Interruptores.
* Balanceadores de carga.
* Infraestrutura virtual.
* Portais de gerenciamento da Web do provedor de nuvem 

> [!IMPORTANT]
> O ambiente no escopo deve ter uma DMZ e o ambiente de suporte do aplicativo/suplemento deve ser segmentado dos sistemas de negócios internos e ambientes corporativos, limitando assim o escopo das atividades de avaliação apenas aos sistemas no escopo. Os analistas de certificação validam técnicas de segmentação durante a avaliação, juntamente com a revisão de relatórios de testes de penetração, que devem ter incluído testes para validar a eficácia de todas as técnicas de segmentação em uso.

### <a name="infrastructure-as-a-service-iaas-platform-as-a-service-paas-and-software-as-a-service-saas"></a>IaaS (infraestrutura como serviço), PaaS (plataforma como serviço) e SaaS (software como serviço) 
Quando a IaaS e/ou PaaS é usada para dar suporte à infraestrutura do aplicativo ou da entrega de código de suplemento em revisão, o provedor de plataforma de nuvem será responsável por alguns dos controles de segurança avaliados em todo o processo de certificação. Portanto, os analistas de certificação precisarão ser fornecidos com a verificação externa independente das melhores práticas de segurança pelo provedor de plataforma de nuvem por meio de relatórios de conformidade externa, como relatórios de AOC (Atestado de Conformidade) de PCI DSS, ISO27001 ou SOC 2 Tipo II. 

O Apêndice F fornece detalhes sobre quais controles de segurança provavelmente serão aplicáveis com base nos seguintes tipos de implantação e com base em se o aplicativo/suplemento exfiltra dados M365 ou não: 
* ISV hospedado 
* IaaS hospedado 
* PaaS/Sem Servidor Hospedado 
* Hospedado híbrido 
* Hospedado Compartilhado 

Em que a IaaS ou PaaS é implantada, você precisará fornecer evidências do ambiente que está sendo hospedado dentro desses tipos de implantação.

### <a name="sampling"></a>Amostragem

As solicitações de evidência em suporte à avaliação de certificação devem ser baseadas em uma amostra dos componentes do sistema no escopo em consideração de diferentes sistemas operacionais, função primária do dispositivo e tipos de dispositivo diferentes. Uma amostra adequada será selecionada no início do processo de certificação. A tabela a seguir deve ser usada como um guia sobre qual pode ser o tamanho da amostra:

|Tamanho da População              | Amostra                  |
|---------------------------- |-------------------------|
|<5|1|
|>5 & <10|2|
|>9 & <25|3|
|>24|4|

> [!NOTE]
>Se discrepâncias forem identificadas entre dispositivos incluídos na amostra inicial, o tamanho da amostra poderá ser aumentado durante a avaliação. 

## <a name="certification-process"></a>Processo de certificação

Antes de iniciar o processo de certificação, você precisará ter concluído com êxito o atestado Publisher dados. Após a conclusão, Microsoft 365 processo de Certificação do Microsoft 365 continuará da seguinte maneira:

### <a name="preparation"></a>Preparação
1. Navegue até o Partner Center e examine a [documentação Publisher atestado](../docs/attestation.md). Se necessário, você pode editar e atualizar suas respostas; no entanto, se você fizer isso, precisará reenviar sua documentação de atestado para aprovação. Se o envio tiver mais de três meses, exigiremos que você reenvie Publisher atestado para revisão e validação. 
1. Leia cuidadosamente o guia [de envio Microsoft 365 certificação](../docs/certification-submission-guide.md) para entender o que será necessário para você. Verifique se você poderá atender aos requisitos de [controle](../docs/certification-submission-guide.md#app-certification-criteria) especificados no Guia de Envio Microsoft 365 Certificação.
1. No partner center, clique em "Iniciar Certificação". Isso levará você ao portal de envio de documento inicial. Envie o [envio inicial do documento](../docs/certification-submission-guide.md#initial-document-submission). Isso nos ajudará a determinar o que está no escopo de sua avaliação com base em como seu aplicativo é arquitetado e lida com os dados do cliente. Verifique esta página com frequência para ver se o envio foi aceito.

>[!NOTE]
>Para todos os aplicativos do Office, você pode referenciar [nosso guia Office do usuário do Aplicativos.](../docs/userguide.md) Para todos os WebApps, você pode referenciar nosso Guia [do Usuário do Aplicativo SaaS](../docs/saasuserguide.md).

### <a name="assessment"></a>Avaliação
1. Depois que o envio inicial do documento for aceito, o conjunto de controles de segurança necessários para seu aplicativo será exibido automaticamente no portal. Em seguida, você precisará enviar evidências para cada controle demonstrando que o controle está em vigor. Tenha em mente que você receberá **60 dias para** enviar todas as evidências. Um analista examinará suas evidências e aprovará o controle ou solicitará evidências novas ou adicionais. Verifique esta página com frequência para ver se sua evidência foi aceita.
### <a name="certification"></a>Certificação
1. Depois que o envio for validado por um analista, você será notificado sobre sua decisão de certificação. Os aplicativos que receberam uma certificação receberão uma notificação em seu aplicativo no **AppSource** e nas **páginas de documentos da Microsoft** . Você pode ler sobre os benefícios completos da [certificação aqui](../docs/enterprise-app-certification-guide.md#program-benefits).

## <a name="review-and-re-certification"></a>Revisão e re-certificação
No caso de seu aplicativo passar por [alterações](../docs/certification-submission-guide.md#significant-changes) significativas a qualquer momento, você precisará nos notificar.

Você também precisará passar pela recertificação anualmente. Isso exigirá a revalidação dos controles no escopo em relação ao seu ambiente atual. Esse processo pode começar até 90 dias antes da expiração da certificação. Sua certificação existente não expirará durante o período de certificação novamente. A nova certificação em todos os programas expira no aniversário de um ano da certificação Microsoft 365 serviço.

Se a certificação não for renovada antes da data de validade, o status de certificação dos aplicativos será revogado. Todos os badgings, ícones e a identidade visual de certificação associada serão removidos do seu aplicativo, e você será proibido de anunciar seu aplicativo como Microsoft 365 Certified.


> [!IMPORTANT]
> **Período de tempo de envio:** Espera-se que, em média, o processo de avaliação deva levar 30 dias, desde que você possa verificar o status de envio com frequência e responder a comentários e solicitações de evidência complementares em tempo hábil. Ao iniciar o processo de certificação, é permitido um máximo de 60 dias para concluir a avaliação. Se todos os envios não tiverem sido concluídos dentro do período de 60 dias, o envio receberá uma falha e o processo deverá ser iniciado novamente. Esses resultados não se tornarão públicos.


## <a name="initial-document-submission"></a>Envio inicial de documento


O envio inicial do documento ajudará os analistas de certificação a executar o escopo e determinar o que estará no escopo da sua avaliação. Depois disso, você precisará enviar documentação de suporte e evidências usadas para realizar a avaliação. Seu envio inicial deve incluir as informações especificadas abaixo. Para obter mais informações, consulte o Guia [de Submissão de Documentos Initital](../docs/initialdocumentsubguide.md).

| **DocumentationOverview&nbsp;**     |   **Detalhes da Documentação**  |
| -------------------------| -----------------------------|
|**Descrição do aplicativo/suplemento** | Uma descrição da finalidade e da funcionalidade do aplicativo/suplemento. Isso deve fornecer ao analista de certificação uma boa compreensão de como o aplicativo/suplemento funciona e qual é o uso pretendido
|**Relatório de testes de penetração** |Um relatório de teste de penetração concluído nos últimos 12 meses. Esse relatório deve incluir o ambiente que dá suporte à implantação do aplicativo/adicionar juntamente com qualquer ambiente adicional que dê suporte à operação do aplicativo/suplemento. **Observação:** se você não fizer testes de penetração anuais, poderá optar por fazê-los por meio do processo de certificação.|
|**Diagramas de arquitetura**|Um diagrama de arquitetura lógica que representa uma visão geral de alto nível da infraestrutura de suporte do seu aplicativo/suplemento. Isso deve incluir todos **os ambientes** de hospedagem e a infraestrutura de suporte que dá suporte ao aplicativo/suplemento. Este diagrama DEVE descrever todos os diferentes componentes do sistema de suporte dentro do ambiente para ajudar os analistas de certificação a entender os sistemas no escopo e ajudar a determinar a amostragem. Indique também qual tipo de ambiente de hospedagem é usado; ISV Hospedado, IaaS, PaaS ou Híbrido. **Nota:** Onde o SaaS é usado, indique os vários serviços saaS usados para fornecer os serviços de suporte dentro do ambiente.|
|**Volume público** | Detalhando **todos os** endereços IP públicos e URLs usados pela infraestrutura de suporte. Isso deve incluir o intervalo de IP roteável completo alocado para o ambiente, a menos que a segmentação adequada tenha sido implementada para dividir o intervalo em uso (a evidência adequada de segmentação será necessária)|
|**Diagramas de fluxo de dados** |Flow diagramas detalhando o seguinte:
||&#x2713; dados M365 flui de e para o aplicativo/suplemento (incluindo [EUII](#euii) e [OII](#oii) ).|
||&#x2713; fluxos de dados do M365 dentro da infraestrutura de suporte (quando aplicável)|
||&#x2713; Diagramas realçando onde e quais dados são armazenados, como os dados são passados para terceiros externos (incluindo detalhes de quais terceiros) e como os dados são protegidos em trânsito em redes abertas/públicas e em repouso.|
|**Detalhes do ponto de extremidade da API**| Uma listagem completa de todos os pontos de extremidade de API usados pelo seu aplicativo. Para ajudar a entender o escopo do ambiente, forneça locais de ponto de extremidade de API em seu ambiente.                                
|**Permissões de API da Microsoft**| Forneça documentação detalhando **TODAS** as APIs da Microsoft que são usadas junto com quais permissões estão sendo solicitadas para que o aplicativo/suplemento funcione, juntamente com uma justificativa para as permissões solicitadas|
|**Tipos de armazenamento de dados** |Armazenamento de dados e manipulação de documentos que descrevem:|
||&#x2713; até que ponto seus clientes M365 Data [EUII](#euii) e [OII](#oii) estão sendo recebidos e armazenados|
||&#x2713; período de retenção de dados.|
||&#x2713; por que os dados M365 do cliente estão sendo capturados.|
||&#x2713; onde os dados do cliente M365 são armazenados (devem ser incluídos nos diagramas de fluxo de dados fornecidos acima).|
|**Confirmação de conformidade**|Documentação de suporte para estruturas de segurança externas incluídas no envio Publisher atestado ou a ser considerada ao examinar Microsoft 365 de certificação. Atualmente, há suporte para os três seguintes:|
||&#x2713; atestado de conformidade (AOC) de [PCI DSS](#pci-dss) .|
||&#x2713; relatórios do TIPO I/Tipo II do [SOC 2](#soc-2) .|
||&#x2713; [ISMSIEC](#isms) /  - 1S0/IEC 27001 Declaração de Aplicabilidade (SoA) e Certificação.[](#iec)|
|**Dependências da Web**|Documentação listando todas as dependências usadas pelo aplicativo/suplemento com as versões em execução atuais.|
|**Inventário de Software**|Um inventário de software atualizado que inclui todos os softwares usados no ambiente no escopo junto com as versões.|
|**Inventário de hardware**| Um inventário de hardware atualizado usado pela infraestrutura de suporte. Isso será usado para ajudar na amostragem ao executar a fase de avaliação. Se seu ambiente incluir PaaS, forneça detalhes dos serviços consumidos.|

## <a name="evidence-collection-and-assessment-activities"></a>Coleta de evidências e atividades de avaliação

Os analistas de certificação precisarão examinar as evidências em todos os componentes do sistema dentro do conjunto de amostras definido. Os tipos de evidência necessários para dar suporte ao processo de avaliação incluem um ou todos os seguintes:

**Coleção evidence**

* Documentação inicial, realçada na seção [Envio da Documentação](#initial-document-submission) Inicial acima 
* Documentos de política 
* Processar documentos 
* Definições de configuração do sistema 
* Alterar tíquetes 
* Alterar registros de controle 
* Relatórios do sistema

Vários métodos serão usados para coletar as evidências necessárias para concluir o processo de avaliação.  Essa coleção de evidências pode estar na forma de: 
* Documentos 
* Capturas de tela 
* Entrevistas 
* Compartilhamento de tela 

As técnicas de coleta de evidências usadas serão determinadas durante o processo de avaliação. Para obter exemplos concretos do tipo de evidência necessária em seu envio, consulte o Guia [de Evidência de Exemplo](../docs/certification-sample-evidence-guide.md).

**Atividades de Avaliação**

Os analistas de certificação examinarão as evidências fornecidas para determinar se você atendeu adequadamente aos controles dentro desta especificação Microsoft 365 certificação. 

Sempre que possível e para reduzir o tempo necessário para concluir a avaliação, qualquer documentação ou toda a documentação detalhada no Envio de Documentação  [Inicial](#initial-document-submission)  deve ser fornecida com antecedência.

Os analistas de certificação primeiro examinarão as evidências fornecidas do envio inicial da documentação e as informações de atestado do Publisher para identificar linhas apropriadas de consulta, tamanho de amostragem e a necessidade de obter mais evidências, conforme detalhado acima.  Os analistas de certificação analisarão todas as informações coletadas para tirar conclusões sobre como e se você está a atender aos controles dentro desta especificação Microsoft 365 certificação. 

## <a name="app-certification-criteria"></a>Critérios de certificação de aplicativo

Seu aplicativo, a infraestrutura de suporte e a documentação de suporte serão avaliados nos seguintes domínios de segurança:

1. [**Segurança de Aplicativo**](#application-security)
1. [**Segurança operacional/implantação segura**](#operational-security)
1. [**Segurança e privacidade do tratamento de dados**](#data-handling-security-and-privacy)

Cada um desses domínios de segurança inclui controles de chave específicos que abrangem um ou mais requisitos específicos que serão avaliados como parte do processo de avaliação. Para garantir que Microsoft 365 certificação seja inclusiva para desenvolvedores de todos os tamanhos, cada um dos domínios de segurança é avaliado usando um sistema de pontuação para determinar uma pontuação geral de cada um dos domínios. As pontuações para cada um dos controles de certificação Microsoft 365 são alocadas entre 1 (baixo) e 3 (alto) com base no risco percebido de que esse controle não está sendo atendido. Cada um dos domínios de segurança terá uma marca de porcentagem mínima a ser considerada uma passagem. Determinados elementos dessa especificação incluem alguns critérios de falha automática:

- As permissões de API não estão seguindo o princípio de privilégios mínimos (PoLP).  
- Nenhum relatório de teste de penetração quando necessário.
- Nenhuma defesa antimalware
- A autenticação multifator não está sendo usada para proteger o acesso administrativo.  
- Nenhum processo de aplicação de patch.  
- Nenhum aviso de [privacidade do RGPD](#gdpr) adequado.  

## <a name="application-security"></a>Segurança de Aplicativo

O domínio de segurança do aplicativo se concentra nas três áreas a seguir: 
* Validação de permissão graphAPI 
* Verificações de conectividade externa
* Teste de segurança do aplicativo 

### <a name="graphapi-permission-validation"></a>Validação de permissão graphAPI

A validação de permissão graphAPI é realizada para validar se o aplicativo/suplemento não solicita permissões muito permissivas. Isso é feito verificando manualmente quais permissões são solicitadas. Os analistas de certificação fará referência cruzada a essas verificações em relação ao envio de atestado do Publisher e avaliarão o nível de acesso que está sendo solicitado para garantir que as práticas de "privilégios mínimos" estejam sendo atendidas. Quando os analistas de certificação acreditam que essas práticas de "privilégios mínimos" não estão sendo atendidas, os analistas de certificação terão uma discussão aberta com você para validar a justificativa comercial para as permissões que estão sendo solicitadas. Todas as discrepâncias em relação Publisher envio de atestado encontrados durante essa revisão também receberão comentários para que seu Publisher atestado possa ser atualizado. 

### <a name="external-connectivity-checks"></a>Verificações de conectividade externa

Como parte da avaliação, um analista executará uma leve explicação da funcionalidade de aplicativos para identificar conexões fora do M365.  Todas as conexões que não forem identificadas como microsoft ou conexões diretas com seu serviço serão sinalizadas e discutidas durante a avaliação.

### <a name="application-security-testing"></a>Teste de segurança do aplicativo

Uma revisão adequada dos riscos associados ao seu aplicativo/suplemento e ao ambiente de suporte é essencial para fornecer aos clientes garantia na segurança do aplicativo/suplemento. O teste de segurança do aplicativo na forma de teste de penetração DEVE ser realizado se o aplicativo tiver alguma conectividade com qualquer serviço não publicado pela Microsoft. Se seu aplicativo operar autônomo sem conectividade com nenhum serviço ou back-end que não seja da Microsoft, o teste de penetração não será necessário.


**Escopo do teste de penetração**

As atividades de  teste de penetração DEVEM ser realizadas no ambiente de produção ao vivo que dá suporte à implantação do aplicativo/suplemento (por exemplo, em que o código do aplicativo/suplemento está hospedado, que normalmente será o recurso dentro do arquivo de manifesto) juntamente com qualquer ambiente adicional que dê suporte à operação do aplicativo/suplemento (por exemplo, se o aplicativo/suplemento se comunicar com outros aplicativos Web fora do Microsoft 365).  Ao definir o escopo, é necessário ter cuidado para garantir que todos os sistemas ou ambientes "conectados" que possam afetar a segurança do ambiente no escopo também sejam incluídos em TODAS as atividades de teste de penetração. 

Quando as técnicas são usadas para segmentar os ambientes no escopo de outros ambientes, as atividades de teste de penetração DEVEM validar a eficácia dessas técnicas de segmentação. Isso deve ser detalhado no relatório de teste de penetração. 

Os relatórios de teste de penetração serão revisados para garantir que não haja vulnerabilidades que atendam aos seguintes critérios  **de** falha automática descritos nos controles abaixo.
 
**Requisitos de teste de penetração**

|**Tipo de Critérios**|**Controles de teste de penetração**|
| -------------------------|-----------------------------|
|**Critérios Gerais**| **Controls**|
|| Os testes de penetração  de aplicativo e infraestrutura DEVEM ocorrer anualmente (a cada 12 meses) e realizados por uma empresa confiável e independente. |
|| A correção de vulnerabilidades críticas e de alto risco  identificadaS DEVE ser concluída dentro de um mês após a conclusão do teste de penetração ou mais cedo, dependendo do processo de aplicação de patch documentado. |
|| O volume externo completo (endereços IP, URLs, pontos de extremidade de API etc.) DEVE ser incluído no escopo do teste de penetração e deve estar documentado no relatório de teste de penetração. |
|| O teste de penetração de aplicativo Web DEVE incluir todas as classes de vulnerabilidade; por exemplo, o mais atual OWASP Top 10 ou SANS Top 25 CWE. |
|| O reteste de vulnerabilidades identificadas pela empresa de teste de penetração não é necessário — a correção e a auto-revisão são suficientes, no entanto, evidências adequadas para demonstrar a correção suficiente DEVEM ser fornecidas durante a avaliação.|
|**Critérios de falha automática:**|**Controls**|
|| Presença de um sistema operacional sem suporte. |
|| Presença de contas administrativas padrão, enumeráveis ou adivinhadas.|
|| Presença de SQL de injeção.|
|| Presença de script entre sites.|
|| Presença de vulnerabilidades de passagem de diretório (caminho do arquivo).|
|| Presença de vulnerabilidades HTTP, por exemplo, divisão de resposta de cabeçalho, solicitação de falsificação e ataques de Desincronização.|
|| Presença de divulgação de código-fonte ( [includingLFI](#lfi)).|
|| Qualquer pontuação crítica ou alta, conforme definido pelas diretrizes de gerenciamento de patch do CVSS.|
|| Qualquer vulnerabilidade técnica significativa que possa ser prontamente explorada para comprometer uma grande quantidade de UEII ou UOI.|






> [!IMPORTANT]
>Os relatórios devem ser capazes de fornecer garantia suficiente de que tudo detalhado na seção Especificação de Teste de Segurança do Aplicativo possa ser demonstrado.


**Requisitos e regras de teste de penetração complementares**

- Para ISVs que atualmente não se envolvem em testes de penetração, os testes de penetração podem ser realizados gratuitamente no Microsoft 365 Certificação. A Microsoft organizará e cobrirá o custo de um teste de penetração por até 12 dias de teste manual. Os custos dos testes de penetração são calculados com base no número de dias necessários para testar o ambiente. Todas as despesas que excederem 12 dias de teste serão de responsabilidade do ISV. 
- Os ISVs serão necessários para enviar evidências e receber aprovação para 50% dos controles no escopo antes da realização do teste de penetração. Para começar, basta preencher o envio inicial do documento e optar por incluir testes de penetração como parte da avaliação. Você será contatado para definir o escopo e agendar o teste de penetração quando tiver concluído 50% dos controles.
- O relatório emitido depois que o pentest for concluído será fornecido ao ISV depois de concluir a certificação. Esse relatório, juntamente com sua Microsoft 365, pode ser usado para mostrar aos clientes potenciais que seu ambiente é seguro.
- Os ISVs também serão responsáveis por demonstrar que as vulnerabilidades identificadas no teste de penetração foram corrigidas antes da concessão de uma certificação, mas não precisam produzir um relatório limpo.

Depois que um teste de penetração é organizado, o ISV é responsável pelos valores associados à remarcação e cancelamentos da seguinte maneira:

| **Reescala da taxa de tempo** | **Proporção a pagar** |
|------------------|------------------------|
| A solicitação de nova agendamento recebeu mais de 30 dias antes da data de início agendada. | 0% a pagar |
| Solicitação de nova agenda recebida de 8 a 30 dias antes da data de início agendada. | 25% a pagar |
| Agende novamente a solicitação recebida dentro de 2 a 7 dias antes da data de início agendada com uma data de re reserva firme.| 50% a pagar |
| Re agende a solicitação recebida menos de 2 dias antes da data de início. | 100% a pagar |

| **Escala de Tempo da Taxa de Cancelamento** | **Proporção a pagar** |
|------------------|------------------------|
| A solicitação de cancelamento recebeu mais de 30 dias antes da data de início agendada. | 25% a pagar |
| A solicitação de cancelamento recebeu de 8 a 30 dias antes da data de início agendada. | 50% a pagar |
| Solicitação de cancelamento recebida dentro de 7 dias antes da data de início agendada. | 90% de pagamento |

## <a name="operational-security"></a>Segurança operacional

Esse domínio mede o alinhamento dos processos de infraestrutura e implantação de suporte do seu aplicativo com as práticas recomendadas de segurança.

### <a name="controls"></a>Controles

|**Família de Controle**| **Controls**|
| ------------------------|------------------------------ |
| **Proteção contra malware – Antivírus**|Forneça a documentação da política que rege práticas e procedimentos antivírus.|
||Forneça evidências demonstradas de que o software antivírus está em execução em todos os componentes do sistema amostrados.|
||Forneça evidências demonstradas de que as assinaturas de antivírus estão atualizadas em todos os ambientes (dentro de 1 dia).|
||Forneça evidências demonstraíveis de que o antivírus está configurado para executar a verificação ao acessar ou a verificação periódica em todos os componentes do sistema amostrados. Observação: se a verificação ao acessar não estiver habilitada, um mínimo de verificação diária e alertaS DEVERÁ ser habilitado.|
||Forneça evidências demonstradas de que o antivírus está configurado para bloquear automaticamente malware ou quarentena e alertar em todos os componentes do sistema amostrados.|
|**Controles de** aplicativo: obrigatório somente se antimalware tradicional não for usado|Forneça evidências demonstradas de que os aplicativos são aprovados antes de serem implantados.|
||Forneça evidências demonstradas de que existe e mantém uma lista completa de aplicativos aprovados com justificativa de negócios.|
||Forneça a documentação de suporte que detalha que o software de controle de aplicativo está configurado para atender a mecanismos específicos de controle de aplicativo. (Exemplo: listagem permitida: sample1, sample3, assinatura de código)|
||Forneça evidências demonstradas de que o controle de aplicativo está configurado como documentado de todos os componentes do sistema amostrados.|
|**Gerenciamento de Patches – Classificação de Risco**| Forneça a documentação da política que rege como novas vulnerabilidades de segurança são identificadas e atribuídas a uma pontuação de risco.|
||Forneça evidências de como novas vulnerabilidades de segurança são identificadas.|
||Forneça evidências demonstrando que todas as vulnerabilidades recebem uma classificação de risco uma vez identificada.|
|**Patch Managmeent – Aplicação de patch**|Forneça a documentação da política para a aplicação de patch de componentes do sistema no escopo que inclua um período de tempo de aplicação de patch mínimo adequado para vulnerabilidades críticas, de alto e médio risco; e desativação de sistemas operacionais e softwares sem suporte.|
||Forneça evidências demonstradas de que todos os componentes do sistema amostrados estão sendo corrigidos.|
||Forneça evidências demonstradas de que quaisquer sistemas operacionais e componentes de software sem suporte não são usados no ambiente.|
|**Verificação de vulnerabilidade**|Forneça os relatórios de verificação de vulnerabilidade de aplicativo Web e infraestrutura trimestral. A verificação precisa ser realizada em relação a todo o volume público (endereços IP e URLs) e intervalos de IP internos.|
||Forneça evidências demonstradas de que a correção de vulnerabilidades identificadas durante a verificação de vulnerabilidades são corrigidas de acordo com o período de tempo de aplicação de patch documentado.|
|**Firewalls**|Forneça a documentação da política que rege as práticas e os procedimentos de gerenciamento de firewall.|
||Forneça evidências demonstraveis de que todas as credenciais administrativas padrão são alteradas antes da instalação em ambientes de produção.|
||Forneça evidências de que os firewalls estão instalados no limite do ambiente no escopo e instalados entre a rede de perímetro (também conhecida como DMZ, zona desmilitarizada e sub-rede filtrada) e redes confiáveis internas.|
||Forneça evidências demonstraveis de que todo o acesso público termina na DMZ (zona desmilitarizada).|
||Forneça evidências de demonstração de que todo o tráfego permitido pelo firewall passa por um processo de aprovação.|
||Forneça evidências demonstraveis de que a base de regras de firewall está configurada para remover o tráfego não definido explicitamente.|
||Forneça evidências demonstraveis de que o firewall dá suporte apenas à criptografia forte em todas as interfaces administrativas que não são do console.|
||Forneça evidências demonstradas de que você está executando revisões de regra de firewall pelo menos a cada 6 meses.|
|**Firewall de Aplicativo Web (WAF) (OPCIONAL)**: crédito adicional será recompensado por atender aos seguintes controles.|Forneça evidências demonstradas de que o waf (Firewall de Aplicativo Web) está configurado para monitorar, alertar e bloquear ativamente o tráfego mal-intencionado.|
||Forneça evidências de demonstração de que o WAF dá suporte ao descarregamento de SSL.|
||Forneça evidências demonstraíveis de que o WAF está protegido contra algumas ou todas as classes de vulnerabilidades a seguir, de acordo com o conjunto de regras principal do OWASP (3.0 ou 3.1) |
|**Alterar Controle**|Forneça a documentação da política que rege os processos de controle de alterações.|
||Forneça evidências demonstradas de que os ambientes de desenvolvimento e teste impõem a separação de tarefas do ambiente de produção.|
||Forneça evidências demonstradas de que os dados de produção confidenciais não são usados nos ambientes de desenvolvimento ou teste.|
||Forneça evidências demonstradas de que as solicitações de alteração documentadas contêm o impacto da alteração, detalhes dos procedimentos de back-out e dos testes a serem executados.|
||Forneça evidências demonstradas de que as solicitações de alteração passam por um processo de autorização e aprovação.|
|**Desenvolvimento/implantação de software seguro**| Forneça políticas e procedimentos que dão suporte ao desenvolvimento e à implantação de software seguro, incluindo diretrizes de práticas recomendadas de codificação segura contra classes de vulnerabilidade comuns, como OWASP Top 10 ou SANS Top 25 CWE.|
|| Forneça evidências demonstrativas de que as alterações de código passam por um processo de revisão e autorização por um segundo revistor.|
|| Forneça evidências demonstradas de que os desenvolvedores passam por treinamento de desenvolvimento de software seguro anualmente.|
|| Forneça evidências demonstraíveis de que os repositórios de código são protegidos com MFA (autenticação multifator).|
|| Forneça evidências demonstradas de que os controles de acesso estão em vigor para proteger repositórios de código.
|**Gerenciamento de Contas**| Forneça a documentação da política que rege as práticas e os procedimentos de gerenciamento de conta.
||Forneça evidências demonstradas de que as credenciais padrão estão desabilitadas, removidas ou alteradas entre os componentes do sistema amostrados.|
||Forneça evidências demonstraíveis de que a criação, a modificação e a exclusão da conta passam por um processo de aprovação estabelecido.|
||Forneça evidências demonstradas de que um processo está em vigor para desabilitar ou excluir contas não usadas dentro de 3 meses.|
||Forneça evidências demonstradas de que uma política de senha forte ou outras mitigações adequadas para proteger as credenciais do usuário estão em vigor.  O seguinte deve ser usado como uma diretriz mínima: comprimento mínimo de senha de 8 caracteres, limite de bloqueio de conta de no máximo 10 tentativas, histórico de senha de no mínimo 5 senhas, imposição do uso de senha forte|
||Forneça evidências demonstradas de que contas de usuário exclusivas são emitidas para todos os usuários.|
||Forneça evidências demonstradas de que os princípios de privilégios mínimos estão sendo seguidos dentro do ambiente.|
||Forneça evidências demonstradas de que um processo está em vigor para proteger ou proteger contas de serviço e que o processo está sendo seguido.|
||Forneça evidências demonstrativas de que a MFA está configurada para todas as conexões de acesso remoto e todas as interfaces administrativas que não são do console.|
||Forneça evidências demonstrativas de que a criptografia forte está configurada para todas as conexões de acesso remoto e todas as interfaces administrativas que não são do console, incluindo o acesso a quaisquer repositórios de código e interfaces de gerenciamento de nuvem.|
||Forneça evidências demonstradas de que a MFA é usada para proteger o portal de administração que você usa para gerenciar e manter todos os registros DNS (serviço de nome de domínio público).|
|**Detecção e prevenção contra intrusões (OPCIONAL):** Crédito adicional será recompensado por atender aos seguintes controles|Forneça evidências demonstradas de que os Sistemas de Detecção e Prevenção de Intrusões (IDPS) são implantados no perímetro dos ambientes no escopo.|
||Forneça evidências demonstrativas de que as assinaturas IDPS são mantidas atuais (dentro de 24 horas).|
||Forneça evidências demonstradas de que o IDPS está configurado para dar suporte à inspeção TLS de todo o tráfego da Web de entrada.|
||Forneça evidências demonstradas de que o IDPS está configurado para monitorar todos os fluxos de tráfego de entrada.|
||Forneça evidências demonstradas de que o IDPS está configurado para monitorar todos os fluxos de tráfego de saída.|
|**Log de eventos de segurança** |Forneça a documentação da política para práticas recomendadas e procedimentos que regem o log de eventos de segurança.|
|| Forneça evidências demonstrativas que mostram que o log de eventos de segurança está configurado em todos os componentes do sistema amostrados para registrar os seguintes eventos: acesso do usuário aos componentes do sistema e ao aplicativo, Todas as ações executadas por um usuário com alto privilégio, tentativas de acesso lógico inválidas criação ou modificação de conta com privilégios, violação de log de eventos, desabilitação de ferramentas de segurança (como antimalware ou registro em log de eventos),  Registro em log antimalware (como atualizações, detecção de malware e falhas de verificação)., eventos IDPS e WAF, se configurados|
||Forneça evidências demonstraíveis de que os eventos de segurança registrados contêm as seguintes informações mínimas: Usuário, Tipo de evento, Data e hora, Indicadores de êxito ou falha, Rótulo que identifica o sistema afetado|
||Forneça evidências demonstradas de que todos os componentes do sistema amostrados são sincronizados com o tempo com os mesmos servidores primários e secundários.|
||Forneça evidências demonstraíveis quando os sistemas voltados para o público estiverem em uso de que os logs de eventos de segurança estão sendo enviados para uma solução de registro em log centralizada que não está dentro da rede de perímetro.|
||Forneça evidências de demonstração para mostrar que a solução de registro em log centralizada está protegida contra violação não autorizada de dados de registro em log.|
||Forneça evidências de que um mínimo de 30 dias de dados de log de eventos de segurança está disponível imediatamente, com 90 dias de logs de eventos de segurança sendo retidos.|
|**Revisando (dados de log)** |Forneça a documentação da política que rege as práticas e os procedimentos de revisão de logs.|
||Forneça evidências de que os logs são revisados diariamente por ferramentas humanas ou automatizadas para identificar possíveis eventos de segurança.|
||Forneça evidências de que possíveis eventos de segurança e anomalias são investigados e corrigidos.|
|**Alertando** | Forneça a documentação da política que rege as práticas e os procedimentos de alerta de eventos de segurança.|
|| Forneça evidências de que os alertas são disparados para triagem imediata para os seguintes tipos de eventos de segurança: criação ou modificações de conta com privilégios, eventos de vírus ou malware, violação de log de eventos, eventos IDPS ou WAF|
||Forneça evidências de demonstração que mostram que a equipe está sempre disponível, o dia todo, todos os dias, para responder a alertas de segurança.|
|**Gerenciamento de risco**|Forneça evidências demonstradas de que um processo formal de gerenciamento de risco de segurança da informação é estabelecido.|
||Forneça evidências de que uma avaliação formal de risco ocorre anualmente, no mínimo.|
||Forneça evidências demonstrativas de que a avaliação de risco de segurança da informação inclui ameaças, vulnerabilidades ou o equivalente.|
||Forneça evidências de demonstração de que a avaliação de risco de segurança da informação inclui impacto, matriz de risco de probabilidade ou o equivalente.|
||Forneça evidências demonstradas de que a avaliação de risco de segurança da informação inclui um registro de risco e um plano de tratamento.|
|**Resposta a incidentes**|Forneça o IRP (plano de resposta a incidentes de segurança).|
||Forneça evidências de que o IRP de segurança inclui um processo de comunicação documentado para garantir a notificação em tempo hábil aos principais stakeholders, como marcas de pagamento e adquirentes, órgãos regulatórios, autoridades de supervisão, diretores e clientes.|
||Forneça evidências demonstraveis de que todos os membros da equipe de resposta a incidentes concluiram o treinamento anual ou um exercício superior de tabela.|
||Forneça evidências demonstrativas para mostrar que o IRP de segurança é atualizado com base em lições aprendidas ou alterações organizacionais.|

## <a name="data-handling-security-and-privacy"></a>Segurança e privacidade do tratamento de dados

Os dados em trânsito entre o usuário do aplicativo, os serviços intermediários e os sistemas do ISV precisarão ser protegidos pela criptografia por meio de uma conexão TLS que dá suporte a um mínimo de TLS v1.1. *Consulte* [**o Apêndice A**](#appendix-a).

Onde seu aplicativo recupera e armazena dados M365, será necessário implementar um esquema de criptografia de armazenamento de dados que siga a especificação, conforme definido no [**Apêndice B**](#appendix-a).

### <a name="controls"></a>Controles

|**Família de Controle**| **Controls** |
| -----------------------|-------------------------------- |
|**Dados em trânsito**| Forneça evidências demonstraíveis de que a configuração do TLS atende ou excede os requisitos de criptografia dentro dos requisitos de configuração [do perfil TLS](../docs/certification-submission-guide.md#appendix-a)|
||Forneça evidências demonstradas de que a compactação TLS está desabilitada em todos os serviços voltados para o público que lidam com solicitações da Web.|
||Forneça evidências demonstradas de que a segurança estrita de transporte HTTP do TLS está habilitada e configurada para >= 15552000 em todos os sites.|
|**Dados inativos**| Forneça evidências demonstradas de que os dados em repouso são criptografados em linha com os requisitos de perfil de criptografia, usando algoritmos de criptografia como AES, Blowfish, TDES e tamanhos de chave de criptografia de 128 bits e 256 bits.|
||Forneça evidências demonstradas de que a função de hash ou a autenticação de mensagem (HMAC-SHA1) é usada apenas para proteger dados em repouso embutidos com requisitos de perfil de criptografia.|
||Forneça um inventário mostrando todos os dados armazenados, incluindo o local de armazenamento e a criptografia usada para proteger os dados.|
|**Retenção e descarte de dados**|Forneça evidências demonstradas de que um período de retenção de dados aprovado e documentado é estabelecido formalmente.|
||Forneça evidências demonstraíveis de que os dados retidos correspondem ao período de retenção definido.|
||Forneça evidências demonstraíveis de que os processos estão em vigor para excluir dados com segurança após seu período de retenção.|
|**Gerenciamento de Acesso a Dados**|Forneça uma lista de todos os indivíduos com acesso a dados ou chaves de criptografia, incluindo a justificativa comercial.|
||Forneça evidências demonstraíveis de que os indivíduos amostrados que têm acesso a dados ou chaves de criptografia foram formalmente aprovados, detalhando os privilégios necessários para sua função de trabalho.|
||Forneça evidências demonstradas de que os indivíduos amostrados que têm acesso a dados ou chaves de criptografia têm apenas os privilégios incluídos na aprovação.|
||Forneça uma lista de todos os terceiros com os dados do cliente compartilhados.|
||Forneça evidências demonstraíveis de que todos os terceiros que consomem dados do cliente têm contratos de compartilhamento em vigor.|
|**RGPD** (se aplicável)| Forneça um processo de SAR (solicitação de acesso de entidade) documentada e forneça evidências demonstrando que os titulares dos dados são capazes de gerar SARs.|
||Forneça evidências demonstraíveis de que você é capaz de identificar todos os locais dos dados dos titulares de dados ao responder a uma SAR.|
||Você mantém um aviso de privacidade que deve conter os detalhes das empresas (Nome, Endereço, etc.).|
||Você mantém um aviso de privacidade que deve explicar os tipos de dados pessoais que estão sendo processados.|
||Você mantém um aviso de privacidade que deve explicar a legalidade do processamento de dados pessoais|
||Você mantém um aviso de privacidade que explica em detalhes os direitos do titular dos dados: Direito de ser informado, Direito de acesso pelo titular dos dados, Direito de eliminação, Direito à restrição de processamento, Direito à portabilidade de dados, Direito a objeto, Direitos em relação à tomada de decisão automatizada, incluindo criação de perfil.|
|| Você mantém um aviso de privacidade que deve explicar por quanto tempo os dados pessoais serão mantidos.|

## <a name="optional-external-compliance-frameworks-review"></a>Revisão opcional de estruturas de conformidade externa

Embora isso não seja necessário, se você estiver em conformidade com ISO 27001, PCI DSS ou SOC2, poderá optar por usar essas certificações para atender a alguns dos controles de certificação Microsoft 365. Os analistas de certificação tentarão alinhar as estruturas de segurança externa existentes à especificação Microsoft 365 certificação. No entanto, se a documentação de suporte não puder fornecer garantia de que os controles de certificação do Microsoft 365 foram avaliados como parte da auditoria/avaliação das estruturas de segurança externas, você precisará fornecer evidências adicionais dos controles que estão em vigor.

A documentação deve demonstrar adequadamente que o ambiente no escopo da certificação Microsoft 365 foi incluído no escopo dessas estruturas de segurança externas. A validação dessas estruturas de segurança será atendida aceitando evidências de certificações válidas realizadas por empresas de terceiros externas confiáveis. Essas empresas confiáveis devem ser membros de órgãos de certificação internacionais para programas de conformidade relevantes. Consulte os padrões de certificação e conformidade ISO para ISO 27001 e QSA (Avaliadores de Segurança Qualificados) para PCI DSS.

A tabela a seguir destaca as estruturas externas e a documentação exigidas pelos analistas de certificação como parte desse processo de validação:

| **Standard** | **Requisitos** |
| ----- | ----- |
| **[ISO 27001](#iso-27001)** | Será necessária uma versão pública da **SOA (Declaração** de Aplicabilidade) e uma cópia do certificado ISO 27001 emitido.  O SOA resume sua posição em cada um dos 114 controles de segurança de informações e será usado para identificar se há exclusão de controles que não são detalhados satisfatoriamente no certificado ISO 27001. Se isso não puder ser determinado examinando a versão pública do SOA, o analista poderá precisar de acesso ao SOA completo se ISO 27001 for usado para validar alguns dos controles de Especificação de Certificação do Microsoft 365.  Além de validar o escopo das atividades de avaliação iso 27001, os analistas também confirmarão a validade da empresa de auditoria, conforme descrito acima.|
|**[PCI DSS](#pci-dss)**| Um documento **válido de Atestado** de Conformidade (AOC) de Nível 1 deve ser fornecido identificando claramente os componentes do aplicativo e do sistema no escopo.  Uma AOC de autoavaliação **não será** aceita como evidência das melhores práticas de segurança de reunião. O AOC será usado para determinar quais dos controles Microsoft 365 especificação de certificação foram avaliados e confirmados como parte da avaliação de PCI DSS.|
|**[SOC 2](#soc-2)**|O relatório **SOC 2 (Tipo I ou Tipo II)** deve ser atual (emitido nos últimos 15 meses e o período de tempo declarado iniciado nos últimos 27 meses) para ser usado como evidência de conformidade com qualquer um dos controles de avaliação dentro desta Especificação de Certificação Microsoft 365.|

Se estruturas de segurança externas tiverem sido incluídas no atestado do Publisher, os analistas de certificação precisarão verificar a validade dessas estruturas de conformidade de segurança como parte da avaliação de certificação Microsoft 365.

|**Framework** | **Considerações adicionais** |
|-------------- | --------------------|
|ISO 27001| [**Apêndice C**](#appendix-c): Coleção de evidências – Deltas para ISO 27001.|
|PCI DSS | [**Apêndice D**](#appendix-d): Coleção de evidências – Deltas para PCI DSS.|
|SOC 2| [**Apêndice E**](#appendix-e): Coleção de evidências – Deltas para SOC 2.|

> [!NOTE]
> Embora os padrões/estruturas de segurança externos mencionados acima possam ser enviados como evidência para atender a alguns dos controles de certificação do Microsoft 365, passar a Certificação do Microsoft 365 não significa que você passará com êxito em uma auditoria em relação a esses padrões/estruturas. A especificação Microsoft 365 certificação é apenas um pequeno subconjunto desses padrões/estruturas de segurança que permite que a Microsoft obtenha um nível de garantia em referência à sua postura de segurança.


### <a name="requirements-to-use-external-compliance-frameworks"></a>Requisitos para usar estruturas de conformidade externas

&#x2713; o ambiente de suporte de aplicativo/suplemento e todos os  processos de negócios de suporte  DEVEM ser incluídos no escopo de quaisquer estruturas de conformidade de segurança externa com suporte e devem ser claramente indicados na documentação fornecida.

&#x2713; as **estruturas de** conformidade de segurança externa com suporte DEVEM ser atuais, ou seja, nos últimos 12 meses (ou dentro de 15 meses, se a reavaliação estiver sendo realizada no momento e as evidências puderem ser fornecidas).

&#x2713; estruturas de conformidade de segurança externa com suporte **DEVEM** ser executadas por uma empresa credenciada independente.

## <a name="appendix-a"></a>Apêndice A

### <a name="tls-profile-configuration-requirements"></a>Requisitos de configuração do perfil TLS

Todo o tráfego de rede, seja em uma rede virtual, serviço de nuvem ou data center, deve ser protegido com um mínimo de TLS v1.1 (recomenda-se tLS v1.2+ ) ou outro protocolo aplicável. As exceções a esse requisito são:

* **Redirecionamento de HTTP para HTTPS**. Seu aplicativo pode responder via HTTP para redirecionar clientes para HTTPS, mas a resposta não deve conter dados confidenciais (cookies, cabeçalhos, conteúdo). Nenhuma outra resposta HTTP além de redirecionar para HTTPS e responder a investigações de integridade é permitida. Confira a seguir.
* **Investigações de integridade**. Seu aplicativo só poderá responder a investigações de integridade **por HTTP se** as investigações de integridade HTTPS não forem compatíveis com a parte de verificação.
* **Acesso ao certificado**. O acesso aos pontos de extremidade crl, OCSP e AIA para fins de validação de certificado e verificação de revogação é permitido via HTTP.
* **Comunicações locais**. Seu aplicativo pode usar HTTP (ou outros protocolos não protegidos) para comunicações que não saem do sistema operacional, e. g. conectando-se a um ponto de extremidade do servidor Web exposto no localhost.

A compactação TLS **DEVE** ser desabilitada.

## <a name="appendix-b"></a>Apêndice B

### <a name="encryption-profile-configuration-requirements"></a>Requisitos de configuração do perfil de criptografia

Somente primitivos criptográficos e parâmetros são permitidos da seguinte maneira:

### <a name="symmetric-cryptography"></a>Criptografia simétrica

**Encryption**

&emsp;&#x2713; somente AES, BitLocker, Blowfish ou TDES são permitidos. Qualquer um dos comprimentos de chave com suporte >=128 são permitidos (128, 192 e 256 bits) e podem ser usados (chaves de 256 bits são recomendadas).

&emsp;&#x2713; modo CBC é permitido. Cada operação de criptografia deve usar um IV (vetor de inicialização) novo e gerado aleatoriamente.

&emsp;&#x2713; uso de criptografias de fluxo, como RC4, **NÃO É** permitido.

**Funções de hash**

&emsp;&#x2713; todo o novo código deve usar SHA-256, SHA-384 ou SHA-512 (coletivamente conhecido como SHA-2). A saída pode ser truncada para não menos de 128 bits

&emsp;&#x2713; SHA-1 só pode ser usado por motivos de compatibilidade.

&emsp;&#x2713; uso de MD5, MD4, MD2 e outras funções de hash NÃO É permitido, mesmo para aplicativos não criptográficos.

**Autenticação de mensagem**

&emsp;&#x2713; todo o novo código DEVE usar HMAC com uma das funções de hash aprovadas. A saída de HMAC pode ser truncada para não menos de 128 bits.

&emsp;&#x2713; HMAC-SHA1 só pode ser usado por motivos de compatibilidade.

&emsp;&#x2713; chave HMAC DEVE ter pelo menos 128 bits. São recomendadas chaves de 256 bits.

### <a name="asymmetric-algorithms"></a>Algoritmos assimétricos

**Encryption**

&emsp;&#x2713; RSA é permitido. A **chave DEVE** ter pelo menos 2.048 bits e o preenchimento OAEP deve ser usado. O uso do preenchimento PKCS só é permitido por motivos de compatibilidade.

**Assinaturas**

&emsp;&#x2713; RSA é permitido. A **chave DEVE** ter pelo menos 2.048 bits e o preenchimento PSS deve ser usado. O uso do preenchimento PKCS só é permitido por motivos de compatibilidade.

&emsp;&#x2713;ECDSA é permitido. A **chave DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

**Chave Exchange**

&emsp;&#x2713; ECDH é permitido. A **chave DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

&emsp;&#x2713; ECDH é permitido. A **chave DEVE** ter pelo menos 256 bits. A curva NIST P-256, P-384 ou P-521 deve ser usada.

## <a name="appendix-c"></a>Apêndice C

### <a name="evidence-collection--delta-for-iso-27001"></a>Coleção de evidências – Delta para ISO 27001

Quando você já tiver atingido a conformidade com ISO27001, as lacunas (lacunas) do delta a seguir não totalmente cobertas pela ISO 27001 precisarão, no mínimo, ser revisadas como parte desta Certificação Microsoft 365.

> [!NOTE]
> Como parte da avaliação de certificação do Microsoft 365, o analista de certificação determinará se qualquer um dos controles ISO 27001 mapeados não foi incluído como parte da avaliação iso 27001 e também poderá decidir os controles de exemplo que foram incluídos para fornecer mais garantia. Todos os requisitos ausentes da ISO 27001 precisarão ser incluídos em suas atividades de avaliação Microsoft 365 certificação.

**Proteção contra malware – Antivírus**

Se a proteção contra malware estiver em vigor usando o controle de aplicativo e for atestada no relatório ISO 27001, nenhuma investigação adicional será necessária. Se nenhum controle de aplicativo estiver em vigor, os analistas de certificação precisarão identificar e avaliar evidências de mecanismos de controle de aplicativos para evitar a detonação de malware dentro do ambiente. Isso exigirá que você:

* Demonstre que o software antivírus está em execução em todos os componentes do sistema amostrados.

* Demonstre que o antivírus está configurado em todos os componentes do sistema amostrados para bloquear automaticamente o malware, colocar em quarentena & alerta ou para alertar.

* O software **antivírus DEVE** ser configurado para registrar todas as atividades.

**Gerenciamento de patch – aplicação de patch**

Como as auditorias iso 27001 não avaliam especificamente essa categoria, isso exigirá que você:

* Componentes de software e sistemas operacionais que não têm mais suporte do fornecedor **NÃO DEVEM** ser usados no ambiente. As políticas de suporte DEVEM estar em vigor para garantir que componentes de software/sistemas operacionais sem suporte sejam removidos do ambiente e um processo para identificar quando os componentes de software vão para o fim da vida útil deve estar em vigor

**Verificação de vulnerabilidade**  

Como as auditorias iso 27001 não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que a verificação de vulnerabilidade interna e externa trimestral é realizada.

* Confirme se a documentação de suporte está em vigor para correção de vulnerabilidade com base na classificação de risco e em conformidade com a especificação da seguinte maneira:
 
 &#x2713; corrigir todos os problemas de risco críticos e altos em linha com a classificação de risco para verificação interna.
 
 &#x2713; corrigir todos os problemas críticos, altos e médios de risco em linha com a classificação de risco para verificação externa.
 
 &#x2713; demonstrar que a correção é realizada em linha com a política de correção de vulnerabilidade documentada.

**Firewall – Firewalls (ou tecnologias equivalentes)**

Como as auditorias iso 27001 não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que os firewalls são instalados no limite do ambiente no escopo.

* Demonstre que os firewalls são instalados entre a DMZ e as redes confiáveis.

*   Demonstre que todo o acesso público termina na DMZ.

*   Demonstre que as credenciais administrativas padrão são alteradas antes da instalação no ambiente dinâmico.

*   Demonstre que todo o tráfego permitido por meio dos firewalls passa por um processo de autorização que resulta na documentação de todo o tráfego com uma justificativa comercial.

*   Demonstre que todos os firewalls estão configurados para remover o tráfego não definido explicitamente.

*   Demonstre que os firewalls dão suporte apenas a criptografia forte em todas as interfaces administrativas que não são do console.

*   Demonstre que as interfaces administrativas não console do firewall expostas à Internet dão suporte à MFA.

*   Demonstrar que as revisões de regra de firewall são realizadas pelo menos a cada 6 meses

**Firewall – WAF (Firewalls de Aplicativo Web)**  

Crédito adicional será fornecido se um WAF for implantado para ajudar a proteger contra a infinidade de ameaças e vulnerabilidades de aplicativo Web às qual o aplicativo pode ser exposto. Quando um WAF ou semelhante estiver presente, isso exigirá que você:

* Demonstre que o WAF está configurado no modo de defesa ativo ou monitorando mais com alertas.

* Demonstre que o WAF está configurado para dar suporte ao descarregamento de SSL.

* É configurado de acordo com o conjunto de regras principal do OWASP (3.0 ou 3.1) para proteger contra a maioria dos seguintes tipos de ataque:

&#x2713; protocolo e problemas de codificação.

&#x2713; injeção de cabeçalho, solicitação de tráfico e divisão de resposta.

&#x2713; arquivos e ataques de passagem de caminho.

&#x2713; RFI (inclusão remota de arquivo).

&#x2713; de execução remota de código.

&#x2713; ataques de injeção de PHP.

&#x2713; ataques de script entre sites.

&#x2713; SQL de injeção.

&#x2713; ataques de fixação de sessão.

**Alterar Controle**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de Solicitação de Alteração, isso exigirá que você:

* Demonstre que as solicitações de alteração têm os seguintes detalhes:

&#x2713; impacto documentado.

&#x2713; detalhes de qual teste de funcionalidade deve ser realizado.

&#x2713; detalhes de qualquer procedimento de back-out.

* Demonstre que o teste de funcionalidade é realizado após a conclusão das alterações.

* Demonstre que as solicitações de alteração são desativadas depois que o teste de funcionalidade é realizado.

**Gerenciamento de Contas**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de gerenciamento de conta, isso exigirá que você:

*   Demonstrar como &#x2713;são implementados para atenuar ataques de reprodução (por exemplo, MFA, Kerberos).
*   Demonstre como as contas que não foram usadas em três meses são desabilitadas ou excluídas.
*   &#x2713; ou outras mitigações adequadas devem ser configuradas para proteger as credenciais do usuário. A seguinte política de senha mínima deve ser usada como diretriz:

&#x2713; tamanho mínimo da senha de 8 caracteres.

&#x2713; limite de bloqueio de conta de no máximo 10 tentativas.
 
&#x2713; histórico de senhas de, no mínimo, cinco senhas.
 
&#x2713; imposição do uso de senhas fortes.
 
*   Demonstre que a MFA está configurada para todas as soluções de acesso remoto.

*   Demonstre que a criptografia forte está configurada em todas as soluções de acesso remoto.

*   Quando o gerenciamento do DNS público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações de DNS DEVEM ser configuradas para usar a MFA.

**Detecção e prevenção contra intrusões (OPCIONAL)**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos dos Serviços de Detecção e Prevenção de Intrusões (IDPS), isso exigirá que você:

*   O IDPS **DEVE** ser implantado no perímetro do ambiente de suporte.

*   As assinaturas IDPS **DEVEM** ser mantidas atuais, no último dia.

*   O IDPS **DEVE** ser configurado para inspeção de TLS.

*   O IDPS **DEVE** ser configurado para TODO o tráfego de entrada e saída.

*   O IDPS **DEVE** ser configurado para alertas.

**Registro em log de eventos**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de log de eventos de segurança, isso exigirá que você:

* Demonstre que os sistemas voltados para o público estão fazendo logon em uma solução de registro em log centralizada que não está dentro da DMZ.

* Demonstre como um mínimo de 30 dias de registro em log de dados está disponível imediatamente, com 90 dias sendo retidos.

**Revisando (dados de log)**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dessa categoria, isso exigirá que você:

*   Demonstre como as revisões de log diárias são realizadas e como as exceções e anomalias são identificadas, mostrando como elas são tratadas.

**Alertando**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dessa categoria, isso exigirá que você:

* Demonstrar como os eventos de segurança são configurados para disparar alertas para triagem imediata.

* Demonstre como a equipe está disponível 24 horas por dia, 7 dias por semana para responder a alertas de segurança.

**Gerenciamento de Riscos**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos dos processos de avaliação de risco, isso exigirá que você:

* Demonstrar que um processo formal de gerenciamento de riscos é estabelecido.

**Resposta a incidentes**

Como as auditorias iso 27001 não avaliam especificamente alguns elementos de processos e políticas de resposta a incidentes, isso exigirá que você:

*   Demonstre que o plano/procedimento de resposta a incidentes inclui:

&#x2713; procedimentos de resposta específicos para modelos de ameaça esperados.

&#x2713; de tratamento de incidentes alinhados à Estrutura de Segurança Cibernética do NIST (Identificar, Proteger, Detectar, Responder, Recuperar).
 
&#x2713; O IRP abrange os sistemas no escopo.
 
&#x2713; treinamento anual para a equipe de resposta a incidentes.

## <a name="appendix-d"></a>Apêndice D

### <a name="evidence-collection--deltas-for-pci-dss"></a>Coleta de evidências – Deltas para PCI DSS

Quando você já tiver atingido a conformidade com PCI DSS, as lacunas (lacunas) do delta a seguir não totalmente cobertas pelo PCI DSS precisarão, no mínimo, ser revisadas como parte desta certificação Microsoft 365.

> [!NOTE]
> Como parte da avaliação de certificação do Microsoft 365, o analista de certificação determinará se qualquer um dos controles PCI DSS mapeados não foi incluído como parte da avaliação de PCI DSS e também poderá decidir os controles de exemplo que foram considerados incluídos para fornecer mais garantia. Todos os requisitos ausentes do PCI DSS precisarão ser incluídos nas atividades de avaliação Microsoft 365 certificação.

**Proteção contra malware – Controle de Aplicativos**

Se a proteção contra malware estiver em vigor por meio do uso de antivírus e for atestada no Relatório PCI DSS, nenhuma investigação adicional será necessária. Se nenhum antivírus estiver em vigor, os analistas de certificação precisarão identificar e avaliar evidências de mecanismos de controle de aplicativos para evitar a detonação de malware dentro do ambiente. Isso exigirá que você: 

*   Demonstre como a aprovação do aplicativo é realizada e confirme se isso foi concluído.

*   Demonstre que existe uma lista completa de aplicativos aprovados com justificativa comercial.

*   Forneça ou demonstre que a documentação de suporte está em vigor, detalhando como o software de controle de aplicativos é configurado para atender a mecanismos específicos de controle de aplicativo (ou seja, lista de permissões, assinatura de código etc.).

*   Demonstre que, em todos os componentes do sistema amostrados, o controle de aplicativo está configurado como documentado.

**Gerenciamento de Patch – Classificação de Risco**

Como as auditorias de PCI DSS não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstrar como a classificação de risco de vulnerabilidades é realizada.

**Verificação de vulnerabilidade**

Como as auditorias de PCI DSS não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que a correção é realizada em linha com a política de correção de vulnerabilidade documentada.

**Firewall – Firewalls (ou tecnologias equivalentes)**

Como as auditorias de PCI DSS não avaliam especificamente essa categoria, isso exigirá que você:

* Demonstre que os firewalls dão suporte apenas a criptografia forte em todas as interfaces administrativas que não são do console.

* Demonstre que as interfaces administrativas não console do firewall expostas à Internet dão suporte à MFA.

Um crédito adicional será fornecido se um waf (Firewall de Aplicativo Web) for implantado para ajudar a proteger contra a infinidade de ameaças e vulnerabilidades de aplicativo Web às qual o aplicativo pode ser exposto. Quando um WAF ou semelhante estiver presente, isso exigirá que você:

* Demonstre que o WAF está configurado no modo de defesa ativo ou monitorando mais com alertas.

* Demonstre que o WAF está configurado para dar suporte ao descarregamento de SSL.

* É configurado de acordo com o conjunto de regras principal do OWASP (3.0 ou 3.1) para proteger contra a maioria dos seguintes tipos de ataque:

&#x2713; protocolo e problemas de codificação.

&#x2713; injeção de cabeçalho, solicitação de tráfico e divisão de resposta.

&#x2713; arquivos e ataques de passagem de caminho.

&#x2713; RFI (inclusão remota de arquivo).

&#x2713; de execução remota de código.

&#x2713; ataques de injeção de PHP.

&#x2713; ataques de script entre sites.

&#x2713; SQL de injeção.

&#x2713; ataques de fixação de sessão.

**Alterar Controle**

Como as auditorias de PCI DSS não avaliam especificamente alguns elementos dos processos de Solicitação de Alteração, isso exigirá que você:

* Demonstre que as solicitações de alteração são geradas antes de serem feitas em ambientes de produção.

* Demonstre que as alterações são autorizadas antes de entrar em produção.

* Demonstre que o teste de funcionalidade é realizado após a conclusão das alterações.

* Demonstre que as solicitações de alteração são desativadas depois que o teste de funcionalidade é realizado.

**Desenvolvimento/implantação de software seguro**

Como as auditorias de PCI DSS não acessam especificamente alguns elementos de processos seguros de desenvolvimento e implantação de software; isso exigirá que você:

* Os repositórios de código DEVEM ser protegidos pela MFA.

*   Os controles de acesso adequados DEVEM estar em vigor para proteger repositórios de código contra modificações de código mal-intencionado.

**Gerenciamento de Contas**

Como as auditorias de PCI DSS não avaliam especificamente alguns elementos dos processos de gerenciamento de conta, isso exigirá que você:

* Demonstrar como os mecanismos de autorização são implementados para atenuar ataques de reprodução (por exemplo, MFA, Kerberos).

* Políticas de senha forte ou outras mitigações adequadas devem ser configuradas para proteger as credenciais do usuário. A seguinte política de senha mínima deve ser usada como diretriz: 

&#x2713; tamanho mínimo da senha de 8 caracteres.

&#x2713; limite de bloqueio de conta de no máximo 10 tentativas.

&#x2713; histórico de senhas de, no mínimo, cinco senhas.

&#x2713; imposição do uso de senhas fortes.

* Demonstre que a criptografia forte está configurada em todas as soluções de acesso remoto.

* Quando o gerenciamento do DNS público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações de DNS DEVEM ser configuradas para usar a MFA.

**Detecção e prevenção contra intrusões (OPCIONAL)**

Como as auditorias de PCI DSS não avaliam especificamente alguns elementos dos processos dos Serviços de Detecção e Prevenção de Intrusões (IDPS), isso exigirá que você:

* O IDPS DEVE ser configurado para inspeção de TLS.

*   O IDPS DEVE ser configurado para TODO o tráfego de entrada e saída.

**Gerenciamento de Riscos**

Como as auditorias de PCI DSS não avaliam especificamente alguns elementos dos processos de avaliação de risco, isso exigirá que você:

* Demonstrar que a avaliação de risco inclui matrizes de impacto e probabilidade.

**Resposta a incidentes**

Como as auditorias de PCI DSS não avaliam especificamente alguns elementos de processos e políticas de resposta a incidentes, isso exigirá que o desenvolvedor:

* Demonstrar os recursos de tratamento de incidentes alinhados à Estrutura de Segurança Cibernética do NIST (Identificar, Proteger, Detectar, Responder, Recuperar).

## <a name="appendix-e"></a>Apêndice E

### <a name="evidence-collection---deltas-for-soc-2"></a>Coleção de evidências – Deltas para SOC 2

Quando você já tiver atingido a conformidade do SOC 2, as lacunas (lacunas) do delta a seguir não totalmente cobertas pelo SOC 2 precisarão ser revisadas como parte desta certificação Microsoft 365.

> [!NOTE]
> Como parte da avaliação de certificação do Microsoft 365, o analista de certificação determinará se qualquer um dos controles SOC 2 mapeados não foi incluído como parte da avaliação do SOC 2 e também poderá decidir os controles de exemplo que foram incluídos para fornecer mais garantia. Todos os requisitos ausentes da avaliação do SOC 2 precisarão ser incluídos como parte das atividades de avaliação Microsoft 365 certificação.

**Proteção contra malware – Controle de Aplicativos**

Se a proteção contra malware estiver em vigor por meio do uso de antivírus e for atestada em seu relatório SOC 2, nenhuma investigação adicional será necessária. Se nenhum antivírus estiver em vigor, os analistas de certificação precisarão identificar e avaliar evidências de mecanismos de controle de aplicativos para evitar a detonação de malware dentro do ambiente. Isso exigirá que você:

* Forneça ou demonstre que a documentação de suporte está em vigor, detalhando como o software de controle de aplicativos é configurado para atender a mecanismos específicos de controle de aplicativo (ou seja, lista de permissões, assinatura de código etc.).

* Demonstre como a aprovação do aplicativo é realizada e confirme se isso foi concluído.

*   Demonstre que existe uma lista completa de aplicativos aprovados com justificativa comercial.

*   Demonstre que, em todos os componentes do sistema amostrados, o controle de aplicativo está configurado como documentado.

**Gerenciamento de patch – aplicação de patch**

Como as auditorias do SOC 2 não avaliam especificamente essa categoria, isso exigirá que você:

*   Qualquer problema Baixo, Médio, Alto ou Crítico deve ser corrigido dentro das janelas normais de atividade de aplicação de patch.

*   Componentes de software e sistemas operacionais que não têm mais suporte do fornecedor NÃO DEVEM ser usados no ambiente. As políticas de suporte DEVEM estar em vigor para garantir que componentes de software/sistemas operacionais sem suporte sejam removidos do ambiente e um processo para identificar quando os componentes de software vão para o fim da vida útil deve estar em vigor.

**Firewall – Firewalls**

Como as auditorias do SOC 2 não avaliam especificamente os controles de alteração para listas de controle de acesso do firewall, isso exigirá que você:

* Demonstre que todo o tráfego permitido por meio dos firewalls passa por um processo de autorização que resulta na documentação de todo o tráfego com uma justificativa comercial.

* Demonstre que as revisões de regra de firewall são realizadas pelo menos a cada seis meses.

Um crédito adicional será fornecido se um WAF (Firewall de Aplicativo Web) ou semelhante for implantado para ajudar a proteger contra a infinidade de ameaças e vulnerabilidades do aplicativo Web às qual o aplicativo pode ser exposto. Quando um WAF ou semelhante estiver presente, isso exigirá que você:

* Demonstre que o WAF está configurado no modo de defesa ativo ou monitorando mais com alertas.

* Demonstre que o WAF está configurado para dar suporte ao descarregamento de SSL.

* É configurado de acordo com o conjunto de regras principal do OWASP ((3.0 ou 3.1) para proteger contra a maioria dos seguintes tipos de ataque:

&emsp;&#x2713; protocolo e problemas de codificação.

&emsp;&#x2713; injeção de cabeçalho, solicitação de tráfico e divisão de resposta.

&emsp;&#x2713; arquivos e ataques de passagem de caminho.

&emsp;&#x2713; RFI (inclusão remota de arquivo).

&emsp;&#x2713; de execução remota de código.

&emsp;&#x2713; ataques de injeção de PHP.

&emsp;&#x2713; ataques de script entre sites.

&emsp;&#x2713; SQL injeção de dados.

&emsp;&#x2713; ataques de fixação de sessão.

**Alterar Controle**

Como as auditorias do SOC 2 não avaliam especificamente alguns elementos dos processos de Solicitação de Alteração, isso exigirá que o desenvolvedor:

* Demonstrar como os ambientes de desenvolvimento/teste são separados do ambiente de produção que impõe a separação de tarefas.

* Demonstrar como os dados dinâmicos não são usados nos ambientes de desenvolvimento/teste.

* Demonstre que o teste de funcionalidade é realizado após a conclusão das alterações.

* Demonstre que as solicitações de alteração são desativadas depois que o teste de funcionalidade é realizado.

**Desenvolvimento/implantação de software seguro**

Como as auditorias do SOC 2 não acessam especificamente alguns elementos de processos seguros de desenvolvimento e implantação de software; isso exigirá que você:

*   Você DEVE ter um processo de desenvolvimento de software estabelecido e documentado que abrange todo o ciclo de vida de desenvolvimento de software.

*   Os desenvolvedores DEVEM passar por treinamento de codificação de software seguro pelo menos anualmente.

*   Os repositórios de código DEVEM ser protegidos pela MFA.

*   Os controles de acesso adequados DEVEM estar em vigor para proteger repositórios de código contra modificações de código mal-intencionado.

**Gerenciamento de Contas**

Como as auditorias do SOC2 não avaliam especificamente alguns elementos dos processos de gerenciamento de conta, isso exigirá que você:

*   Demonstrar como os mecanismos de autorização são implementados para atenuar ataques de reprodução (por exemplo, MFA, Kerberos).

*   Demonstre como as contas que não foram usadas em três meses são desabilitadas ou excluídas.

*   Políticas de senha forte ou outras mitigações adequadas devem ser configuradas para proteger as credenciais do usuário. A seguinte política de senha mínima deve ser usada como diretriz:

&emsp;&#x2713; tamanho mínimo da senha de 8 caracteres.

&emsp;&#x2713; limite de bloqueio de conta de no máximo 10 tentativas.

&emsp;&#x2713; histórico de senhas de, no mínimo, 5 senhas.

&emsp;&#x2713; imposição do uso de senhas fortes

*   Demonstre que contas de usuário exclusivas são emitidas para todos os usuários.

*   Quando o gerenciamento do DNS público está fora do ambiente no escopo, todas as contas de usuário capazes de fazer modificações de DNS DEVEM ser configuradas para usar a MFA.

**Detecção e prevenção contra intrusões (OPCIONAL).**

Como as auditorias do SOC 2 não avaliam especificamente alguns elementos dos processos dos Serviços de Detecção e Prevenção de Intrusões (IDPS), isso exigirá que você:

*   As assinaturas IDPS DEVEM ser mantidas atuais, no último dia

*   O IDPS DEVE ser configurado para inspeção de TLS

*   O IDPS DEVE ser configurado para TODO o tráfego de entrada e saída

**Registro em log de eventos**

Como as auditorias do SOC 2 não avaliam especificamente alguns elementos dos processos de log de eventos de segurança, isso exigirá que você:

* Demonstrar como, em todos os componentes do sistema dentro do conjunto de exemplos, o sistema a seguir é configurado para registrar os eventos a seguir

&emsp;&#x2713; acesso do usuário aos componentes do sistema e aos aplicativos.

&emsp;&#x2713; todas as ações executadas por um usuário com alto privilégio.

&emsp;&#x2713; tentativas de acesso lógico inválidas.

Demonstrar que os eventos registrados contêm; no mínimo, as seguintes informações:

&emsp;&#x2713; Usuário.

&emsp;&#x2713; tipo de evento.

&emsp;&#x2713; data e hora.

&emsp;&#x2713; indicador de êxito/falha.

&emsp;&#x2713; rótulo para identificar o sistema afetado.

*   Demonstre que todos os componentes do sistema no conjunto de exemplos estão configurados para utilizar a sincronização de tempo e que eles são os mesmos que os servidores de tempo primário/secundário.

* Demonstre que os sistemas voltados para o público estão fazendo logon em uma solução de registro em log centralizada que não está dentro da DMZ.

*   Demonstre que os sistemas voltados para o público estão fazendo logon em uma solução de registro em log centralizada que não está dentro da DMZ.

* Demonstrar como a solução de registro em log centralizada é protegida contra violação não autorizada de dados de log.

* Demonstre como um mínimo de 30 dias de registro em log de dados está disponível imediatamente, com 90 dias ou mais de retenção.

**Gerenciamento de Riscos**

Como as auditorias do SOC2 não avaliam especificamente alguns elementos dos processos de avaliação de risco, isso exigirá que você:

* Demonstrar que uma avaliação formal de risco é realizada pelo menos anualmente.

*Resposta a incidentes.*

Como as auditorias soC2 não avaliam especificamente alguns elementos de processos e políticas de resposta a incidentes, isso exigirá que você:

* Demonstre que o plano/procedimento de resposta a incidentes inclui:

&emsp;&#x2713; procedimentos de resposta específicos para modelos de ameaça esperados.

&emsp;&#x2713; processo de comunicação documentado para garantir a notificação em tempo hábil dos principais stakeholders (marcas de pagamento/adquirentes, órgãos reguladores, autoridades de supervisão, diretores, clientes etc.

## <a name="appendix-f"></a>Apêndice F

### <a name="hosting-deployment-types"></a>Tipos de implantação de hospedagem

A Microsoft reconhece que você implantará aplicativos e armazenará código de aplicativo/suplemento em diferentes ambientes de hospedagem. As responsabilidades gerais de alguns dos controles de segurança dentro do Microsoft 365 certificação dependerão do ambiente de hospedagem que está sendo usado. O Apêndice F examina os tipos de implantação comuns e os mapeia em relação aos controles de segurança que são avaliados como parte do processo de avaliação. Os seguintes tipos de implantação de hospedagem foram identificados:

|Tipos de hospedagem  |Descrição  |
|-----|------|
|**ISV hospedado**|Os tipos hospedados pelo ISV podem ser definidos como onde você é responsável pela infraestrutura usada para dar suporte ao ambiente de aplicativo/suplemento. Isso pode estar fisicamente localizado em seus próprios data centers ou data centers de terceiros com um serviço de colocalidade. Por fim, você tem controle administrativo e de propriedade total sobre a infraestrutura de suporte e o ambiente operacional.|
|**IaaS (infraestrutura como serviço)** (https://azure.microsoft.com/overview/what-is-iaas/)|A infraestrutura como serviço é um serviço fornecido pelo qual a infraestrutura de suporte físico é gerenciada e mantida em seu nome pelo CSP (provedor de serviços de nuvem). Normalmente, a rede, o armazenamento, os servidores físicos e a infraestrutura de virtualização são de responsabilidade do CSP. O sistema operacional, o middleware, o runtime, os dados e os aplicativos são as responsabilidades de você. Os recursos de firewall também seriam gerenciados e mantidos por terceiros, no entanto, a manutenção da base de regras de firewall geralmente ainda seria responsabilidade dos consumidores.|
|**Plataforma como serviço/PaaS (sem servidor)** (https://azure.microsoft.com/overview/what-is-paas/)| Com a Plataforma como Serviço, você é provisionado com uma plataforma gerenciada apresentando um serviço que pode ser consumido. Você não precisa executar funções sysadmin, pois o sistema operacional e a infraestrutura de suporte são gerenciados pelo CSP. Normalmente, isso seria usado quando as organizações não querem se preocupar com a apresentação de um serviço Web e, em vez disso, podem se concentrar na criação do código-fonte do aplicativo Web e na publicação do aplicativo Web nos serviços Web gerenciados na nuvem.  Outro exemplo pode ser um serviço de banco de dados em que a conectividade é fornecida a um banco de dados, no entanto, a infraestrutura de suporte e o aplicativo de banco de dados são abstraídos do consumidor.   **Observação: Sem servidor e PaaS são semelhantes, portanto, para a finalidade do tipo de implantação de hospedagem de Microsoft 365 de certificação sem servidor e PasS são considerados iguais**|
|**Hospedado híbrido**|Com o tipo hospedado híbrido, você pode utilizar vários tipos hospedados para dar suporte a várias partes do ambiente de suporte. Esse pode ser mais o caso em que aplicativos/suplementos são utilizados em várias pilhas M365. Embora a Certificação do Microsoft 365 seja compatível com o desenvolvimento de aplicativos/complementos em vários serviços M365, uma avaliação de todo o ambiente de suporte (entre aplicativos/suplementos) precisaria ser avaliada de acordo com cada um dos "Mapeamentos de Tipo Hospedado" aplicáveis. Ocasionalmente, você pode utilizar diferentes tipos hospedados para um único suplemento, onde isso está sendo executado, a aplicabilidade dos critérios ainda precisará seguir os critérios "Mapeamentos de Tipo Hospedado" entre os vários tipos hospedados.|
|**Hospedagem compartilhada**|A hospedagem compartilhada é o local em que você hospeda o ambiente em uma plataforma compartilhada por vários consumidores individuais. A Microsoft 365 especificação de certificação não foi gravada para isso devido à adoção da nuvem, a hospedagem compartilhada não é comum. Se você acredita que isso está sendo usado, entre em contato com a Microsoft, pois os requisitos adicionais precisarão ser criados para contabilitar os riscos adicionais sob esse tipo de hospedagem.|


## <a name="appendix-g"></a>Apêndice G

## <a name="learn-more"></a>Saiba mais

[Microsoft 365 do Programa de Conformidade de Aplicativos](~/overview.md)  
[O que é Microsoft 365 aplicativo Publisher atestado?](~/docs/attestation.md)  
[O que é Microsoft 365 certificação?](~/docs/enterprise-app-certification-guide.md)

## <a name="glossary"></a>Glossário

### <a name="aia"></a>AIA

*O Acesso a Informações da Autoridade é um descritor de local de serviço usado para localizar o certificado da autoridade de certificação emitindo.

### <a name="crl"></a>CRL

*A Lista de Certificados Revogados fornece um meio para um ponto de extremidade SSL (Secure Sockets Layer) verificar se um certificado recebido de um host remoto é válido e confiável.

### <a name="cvss-score"></a>Pontuação do CVSS

*O Common Vulnerability Scoring System é um padrão publicado que mede a vulnerabilidade e calcula uma pontuação numérica com base em sua gravidade.

### <a name="cvss-patch-management-guidelines"></a>Diretrizes de gerenciamento de patch do CVSS

* Crítico (9,0 – 10,0)
* Alta (7,0 a 8,9)
* Médio (4,0 a 6,9)
* Baixo (0,0 - 3,9)

### <a name="dmz"></a>DMZ

*Zona desmilitarizada é uma rede intermediária física ou lógica que interage diretamente com redes externas ou não de propriedade, mantendo a rede interna e privada do host separada e isolada.

### <a name="euii"></a>EUII

*Informações de identificação do usuário final*.

### <a name="gdpr"></a>RGPD

*O Regulamento Geral sobre a Proteção de Dados é uma regulamentação de privacidade e proteção de dados da União Europeia (UE) para todos os dados de cidadãos da UE, independentemente de onde seu site de aplicativo está localizado.

### <a name="hsts"></a>HSTS

*A Segurança de Transporte Estrito http utiliza um cabeçalho de resposta HTTP instruindo o navegador da Web a acessar apenas o conteúdo via HTTPS.  Isso foi projetado para proteger contra ataques de downgrade e sequestro de cookies.

### <a name="iec"></a>IEC

*International Electrotechnical Commission.

### <a name="isms"></a>ISMOS

*Sistema de Gerenciamento de Segurança da Informação.

### <a name="isv"></a>ISV

Fornecedores independentes de segurança são indivíduos e organizações que desenvolvem, comercializam e vendem softwares executados em plataformas de hardware e software de terceiros.

### <a name="iso-27001"></a>ISO 27001

Uma estrutura de especificação do sistema de gerenciamento de segurança de informações para todos os controles técnicos em processos de políticas e procedimentos de gerenciamento de riscos de organizações.

### <a name="lfi"></a>LFI

*A Inclusão de Arquivo Local* permite que um invasor inclua arquivos em um servidor por meio do navegador da Web.

### <a name="nist"></a>NIST

O NIST (National *Institute of Standards* ), uma agência não regulatória do Departamento de Comércio dos EUA, fornece diretrizes para que organizações do setor privado nos EUA avaliem e aprovem sua capacidade de evitar, detectar e responder a ataques cibernéticos.

### <a name="non-significant-changes"></a>Alterações não significativas

* Correções secundárias de bug.
* Pequenas melhorias de desempenho.
* Sistemas operacionais/bibliotecas/patches de aplicativo de cliente e servidor.

### <a name="ocsp"></a>OCSP

*O Protocolo de Status de Certificado Online* é usado para verificar o status de revogação de certificados digitais X.509.

### <a name="oii"></a>OII

*Informações de identificação organizacional*.

### <a name="owasp"></a>OWASP

*Abra o aplicativo Web Security Project*.

### <a name="pci-dss"></a>PCI DSS

*Padrão de Segurança de Dados do* Setor de Cartões de Pagamento, uma organização que mantém padrões para a segurança dos dados do titular do cartão em todo o mundo.

### <a name="pen-testing"></a>Teste de caneta

*O teste de* penetração é um método de testar um aplicativo Web simulando ataques mal-intencionados para encontrar vulnerabilidades de segurança que um invasor pode explorar.

### <a name="saml"></a>SAML

*A Linguagem de Marcação de Declaração* de Segurança é um padrão aberto para trocar dados de autenticação e autorização entre o usuário, o provedor de identidade e o provedor de serviços.

### <a name="sensitive-data"></a>Dados Confidenciais

* Dados de controle de acesso.
* Conteúdo do cliente.
* Informações de identidade do usuário final.
* Dados de suporte.
* Dados pessoais públicos.
* Informações pseudonimosas do usuário final.

### <a name="significant-changes"></a>Alterações significativas

* Realocação do ambiente de hospedagem.
* Principais atualizações para a infraestrutura de suporte; por exemplo, implementação de um novo firewall, atualizações principais para serviços voltados para a frente etc.
* Adição de funcionalidades e /ou extensões ao seu aplicativo.
* Atualizações em seu aplicativo que capturam dados confidenciais adicionais.
* Alterações nos fluxos de dados ou nos modelos de autorização do aplicativo
* Adição de pontos de extremidade de API ou funções de ponto de extremidade de API.

### <a name="soc-2"></a>SOC 2

*Controle da Organização do Serviço 2*, um procedimento de auditoria técnica composto por cinco Princípios de Serviço de Confiança para garantir que os provedores de serviços gerenciem com segurança os dados e a privacidade dos clientes de uma organização.

### <a name="ssl"></a>SSL

*Camada de soquetes seguros*.

### <a name="tls"></a>TLS

*Segurança da camada de transporte*.
