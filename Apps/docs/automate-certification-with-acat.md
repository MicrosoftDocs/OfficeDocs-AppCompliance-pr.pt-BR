---
title: Automatizar a Microsoft 365 com a Ferramenta de Automação de Conformidade do Aplicativo para Microsoft 365
description: Usar a Ferramenta de Automação de Conformidade do Aplicativo Microsoft 365 (ACAT) para automatizar a certificação Microsoft 365 aplicativo.
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: 6a18e64f3b75f6d197c9867830d0a061ce298584
ms.sourcegitcommit: 0865622c8abffc11115e56d966729e5318d67ab9
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/20/2022
ms.locfileid: "65608799"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>Automatizar a Microsoft 365 com a Ferramenta de Automação de Conformidade do Aplicativo para Microsoft 365

A ACAT (App Compliance Automation Tool for Microsoft 365) colabora com o programa de conformidade do aplicativo Microsoft 365 para atender a alguns dos controles necessários para Microsoft 365 certificação. Este artigo ajudará você a começar a usar o ACAT e a usar as avaliações de conformidade com a Microsoft 365 certificação.

> [!IMPORTANT]
> O ACAT está em versão prévia privada no momento. Se você quiser ingressar no programa de visualização privada, inscreva-se [aqui](https://aka.ms/acat/private/signup).

> [!NOTE]
> Se você quiser fornecer comentários para a versão prévia privada do ACAT, poderá começar a partir deste [formulário](https://aka.ms/acat/feedback). A equipe do produto ACAT acompanhará você assim que recebermos suas mensagens. 

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>Criar seu primeiro relatório de conformidade para integrar o ACAT

O ACAT permite que você se concentre na conformidade do aplicativo ou no ambiente específico de um aplicativo (por exemplo, produção, preparo etc.). Ele permite que você crie um relatório  de conformidade no qual você pode definir o limite de conformidade com base na infraestrutura de nuvem do aplicativo ou no ambiente específico de um aplicativo.

> [!IMPORTANT]
> Como o ACAT está em versão prévia privada, você não pode pesquisá-lo portal do Azure diretamente. Inscreva-se no [programa de visualização privada do ACAT](https://aka.ms/acat/private/signup) e obtenha acesso da equipe de suporte.

- Pesquise e inicie ***a Ferramenta de Automação de Conformidade do Aplicativo Microsoft 365*** no portal do Azure.
- Vá para ***Relatórios*** da esquerda.

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="Criar relatório de conformidade":::
   Ir para Relatórios para criar um novo relatório de conformidade :::image-end:::

- Selecione ***Criar novo relatório para*** começar a criar seu primeiro relatório de conformidade com a configuração adequada. 
    - **Noções básicas**
        - **Nome do** relatório: o nome do relatório de conformidade é necessário e não pode ser duplicado no locatário. Pode ser a combinação de números, alfabetos e sublinhados. É recomendável usar um nome significativo com o relatório de conformidade, por exemplo, indicando o aplicativo ou o ambiente específico.
        - **Tempo de gatilho**: o ACAT gerará as avaliações de conformidade para o relatório de conformidade diariamente. Essa configuração é usada para especificar quando a geração deve ser disparada. 
        - **Selecionar assinatura**: em versão prévia privada, o ACAT permite que você defina o escopo do relatório de conformidade escolhendo os recursos do Azure em uma assinatura específica. Você pode escolher a assinatura adequada com base em sua infraestrutura de nuvem. Se a assinatura do aplicativo não estiver na lista, você precisará solicitar permissão do administrador. 
        - **Selecionar recursos**: depois que a assinatura for especificada, selecione os recursos adequados com base em sua infraestrutura de nuvem. Como padrão, todos os recursos serão selecionados automaticamente. Você também pode pesquisar os recursos por filtros (por exemplo, grupo de recursos, marca etc.) e, em seguida, selecionar os recursos. 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="Configuração básica":::
       Configuração básica para o relatório de conformidade :::image-end:::

    - **Microsoft 365:** a configuração de Microsoft 365 de certificação é opcional durante a criação.  Ele poderá ser configurado posteriormente depois que você começar a publicar seu aplicativo.
        - **GUID da** oferta: o GUID da oferta é o identificador exclusivo da oferta do marketplace [no Microsoft Partner Network](https://partner.microsoft.com/dashboard). Selecione Saiba *mais para* obter uma instrução passo a passo sobre como obter o identificador exclusivo.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365 de certificação":::
       Configuração sobre a Microsoft 365 certificação:::image-end:::

Depois de confirmar a configuração e criar o relatório de conformidade, o ACAT coletará os dados relacionados à conformidade automaticamente das fontes abaixo. 

- Habilite [o Microsoft Defender para Nuvem](https://azure.microsoft.com/services/defender-for-cloud/) (camada gratuita) para sua assinatura. 
- Habilite algumas políticas personalizadas para sua assinatura. 

> [!NOTE]
> Se a criação for bem-sucedida, o ACAT começará a coletar e gerar as avaliações de conformidade para o relatório de conformidade a partir do dia seguinte. 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>Auditar as avaliações de conformidade com seu relatório de conformidade

Com o ACAT, você pode aprender o status em tempo de execução do relatório de conformidade e auditar facilmente as avaliações de conformidade. 

- Vá para ***Relatórios*** da esquerda. Você pode obter um breve resumo dos relatórios de conformidade existentes.
    - **Status de tempo de execução**: o status de tempo de execução indica se o ACAT ainda gerencia o relatório de conformidade corretamente na última geração. Há três estados para o status de tempo de execução. 
        - **Ativo**: o relatório de conformidade está sendo executado continuamente e com êxito. 
        - **Falha**: o ACAT falhou ao gerar as avaliações de conformidade para este relatório de conformidade para a última geração. Esse estado pode acontecer por vários motivos, por exemplo, há uma configuração incorreta em sua assinatura para bloquear os dados de conformidade roteados para o ACAT, há falha ou interrupção do sistema com o ACAT etc. 
        - **Desabilitado**: esse relatório de conformidade é desabilitado (pausado) manualmente por você. Esse recurso não está habilitado na versão prévia privada. 
    - **Hora do último gatilho** **e hora do próximo** gatilho: o ACAT gerará as avaliações de conformidade para o relatório de conformidade diariamente. *A hora do último* gatilho indica quando a última geração foi disparada e a  hora do gatilho Next indica a hora do gatilho para a próxima geração. 
    - **Microsoft 365:** entenda o status do relatório de conformidade para Microsoft 365 de certificação. Os três estados para o status Microsoft 365 de conformidade de certificação incluem:
        - **Aprovado**: não há falhas para os controles de Microsoft 365 de certificação totalmente automatizados.
        - **Falha**: há responsabilidades do cliente com falha detectadas para os controles de Microsoft 365 de certificação totalmente automatizados.
        - **Manual**: esse estado inclui dois tipos de controles: o controle *manual automatizado parcial* que é parcialmente automatizado pelo ACAT e ainda precisa de algum esforço manual para coletar evidências de conformidade e o controle *manual* que requer esforço manual completo para coletar evidências de conformidade. O ACAT automatiza partes das responsabilidades do cliente para o controle parcialmente automatizado. Você pode usar o estado de conformidade dele para referência, mas não pode usá-lo para Microsoft 365 auditoria de certificação diretamente.
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="Lista de relatórios de conformidade":::
       Lista de relatórios de conformidade existentes.
    :::image-end:::

Além de aprender o resumo de alto nível dos relatórios de conformidade existentes, você também pode auditar os detalhes da avaliação de conformidade com sua equipe no ACAT. Obtenha os detalhes da avaliação de conformidade para o relatório de conformidade específico clicando no nome do relatório. O ACAT mostrará os detalhes conforme mostrado abaixo.

- **Configurações**: você pode alterar a configuração do relatório de conformidade com *Configurações*. Na versão prévia privada, você pode alterar a configuração Microsoft 365 relacionada à certificação. 
- **Baixar relatório**: o ACAT permite que você baixe as avaliações do relatório de conformidade como arquivos csv em um formato que pode ser compartilhado com parceiros para colaboração.
    - **Inventário de infraestrutura de** nuvem: esse arquivo contém os detalhes do recurso deste relatório de conformidade. Ele pode ser usado para descrever o inventário de nuvem do seu aplicativo. 
    - **Microsoft 365 avaliação de conformidade** de certificação: esse arquivo inclui as avaliações de conformidade do relatório de conformidade da exibição Microsoft 365 de certificação. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="Barra de ferramentas do relatório de conformidade":::
    Barra de ferramentas para o relatório de conformidade.
:::image-end:::

- **Conceitos básicos**: esta seção indica o status e a configuração do relatório de conformidade. 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="Conceitos básicos do relatório de conformidade":::
    Conceitos básicos para o relatório de conformidade.
:::image-end:::

- **Resultados da avaliação**
    - O estado de conformidade do controle Microsoft 365 de certificação é classificado em cinco categorias. 
        - **Aprovado**: não há falhas para os controles de Microsoft 365 de certificação totalmente automatizados.
        - **Falha**: há responsabilidades do cliente com falha detectadas para os controles de Microsoft 365 de certificação totalmente automatizados.
        - **Aprovado – Evidência adicional necessária**: não há falhas para os controles de certificação Microsoft 365 parcialmente automatizados. Você ainda precisa coletar evidências adicionais para os controles manualmente.
        - **Falha – Evidência adicional necessária**: há falhas nas responsabilidades do cliente detectadas para os controles de Microsoft 365 de certificação parcialmente automatizados.
        - **Controle manual**: o ACAT não automatiza nenhuma responsabilidade do cliente para os controles Microsoft 365 de certificação. 
    - As avaliações de conformidade são organizadas por uma família Microsoft 365 controle e família de controle de certificação. 
        - Saiba mais sobre os detalhes do controle de conformidade e como coletar evidências de conformidade para controle manual clicando no nome do controle. 
        - Ao expandir o controle totalmente automatizado e o controle parcialmente automatizado, você pode aprender mais detalhes de conformidade da responsabilidade do cliente desse controle. 
        - Para cada responsabilidade do cliente, você também pode descobrir o estado de conformidade dos recursos relacionados e as etapas de correção do recurso com falha clicando no botão de ação. 
            - **Recursos não íntegros**: você precisa acompanhar as etapas de correção para corrigir os recursos não íntegros. 
            - **Recursos não aplicáveis**: você precisa acompanhar o motivo de N/A para configurar os recursos e, em seguida, o ACAT pode coletar as avaliações de conformidade para os recursos.

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="Avaliações de relatório de conformidade":::
    Avaliações de conformidade para o relatório de conformidade.
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Usar seu primeiro relatório de conformidade com a auditoria de certificação do Microsoft r365

Antes de usar o relatório de conformidade Microsoft 365 certificação, você precisa configurar o GUID da oferta para associar o relatório de conformidade à sua oferta do marketplace. Há duas opções: 

- Durante o processo de criação do relatório de conformidade, configure o GUID da oferta *Microsoft 365 guia de certificação*. 
- Se o relatório de conformidade já estiver criado, vá para o *Configurações* deste relatório de conformidade para configurar o GUID da oferta.

Depois que o GUID da oferta estiver configurado, vá para o [Microsoft Partner Network](https://partner.microsoft.com/dashboard) para iniciar a conformidade do aplicativo. A *Documentação Inicial* é a primeira fase da Microsoft 365 certificação. Nesta fase, se você escolher *Sim* para a questão de se está usando o ACAT, poderá escolher o relatório de conformidade adequado para essa auditoria. A Microsoft 365 certificação enviará as avaliações de conformidade de controles totalmente automatizados para o auditor automaticamente, economizando seu tempo e esforço. 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>Obter visão geral de alto nível de seus relatórios de conformidade 

A ***Visão geral*** fornece uma melhor compreensão do status de alto nível para seus relatórios de conformidade. 

- **Status de tempo de execução do relatório de conformidade**: esta visão geral fornecerá a estatística do status de tempo de execução para seus relatórios de conformidade.
    - **Ativo**: o relatório de conformidade está sendo executado continuamente e com êxito. 
    - **Falha**: o ACAT falhou ao gerar as avaliações de conformidade para esse relatório de conformidade na última geração. Esse estado pode acontecer por vários motivos, por exemplo, há uma configuração incorreta em sua assinatura para bloquear os dados de conformidade roteados para o ACAT, ocorreu falha ou interrupção do sistema com o ACAT etc. 
    - **Desabilitado**: esse relatório de conformidade é desabilitado (pausado) manualmente por você. Esse recurso não está habilitado na versão prévia privada. 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="Visão geral do status de tempo de execução":::
    Visão geral do status de tempo de execução do relatório de conformidade.
:::image-end:::

- **Relatórios de Conformidade Regulatória Ativas**: esta visão geral fornecerá a estatística dos resultados de conformidade para cada *relatório de* conformidade ativo.
    - **Aprovado**: não há falhas para os controles de Microsoft 365 de certificação totalmente automatizados.
    - **Falha**: há responsabilidades do cliente com falha detectadas para os controles de Microsoft 365 de certificação totalmente automatizados.
    - **Manual**: esse estado inclui dois tipos de controles: o controle *manual automatizado parcial* que é parcialmente automatizado pelo ACAT e ainda precisa de algum esforço manual para coletar evidências de conformidade e o controle *manual* que requer esforço manual completo para coletar evidências de conformidade. O ACAT automatiza partes das responsabilidades do cliente para o controle parcialmente automatizado. Você pode usar o estado de conformidade dele para referência, mas não pode usá-lo para Microsoft 365 auditoria de certificação diretamente.

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="Visão geral do status de conformidade":::
    Visão geral do status de conformidade para relatórios de conformidade ativos.
:::image-end:::

## <a name="troubleshooting"></a>Solução de problemas 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>Por que o relatório de conformidade criado falhou devido a um erro de autorização? 

Ao criar um relatório de conformidade, o ACAT configurará o ambiente com sua assinatura para coletar os dados de conformidade automaticamente, e essa ação requer permissão específica da assinatura. Você pode verificar a permissão da sua assinatura, conforme mostrado abaixo. 

- Pesquise e inicie **as Assinaturas** [portal do Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
- Vá para a assinatura que você deseja usar para criar o relatório de conformidade. 
- Vá para **o controle de acesso (IAM)** à esquerda. 
- Selecione **Exibir meu acesso** para verificar sua permissão.
    - Se sua organização estiver usando [funções internas do Azure](/azure/role-based-access-control/built-in-roles), suas atribuições de função deverão incluir pelo menos uma das seguintes funções:
        - [Colaborador da Política de Recursos](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) e [Administrador de Segurança](/azure/role-based-access-control/built-in-roles#security-admin)
        - Outra atribuição de função que tem permissão mais alta (por exemplo, [Proprietário](/azure/role-based-access-control/built-in-roles#owner) etc.)

### <a name="how-to-report-an-acat-issue-or-warning"></a>Como relatar um problema ou aviso do ACAT? 

Quando você encontrar um problema no ACAT e quiser entrar em contato com o programa de visualização privada [do ACAT](mailto:acatprivatepreview@microsoft.com) para obter ajuda, precisamos de sua ajuda para coletar as evidências para entender melhor seu cenário.

- Obter os detalhes do erro ou aviso do ACAT
    - Vá para **as Notificações** na parte superior [portal do Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Selecionar **Mais eventos no log de atividades** 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="Notificações do ACAT":::
        Vá para o log de atividades para verificar as notificações do ACAT.
    :::image-end:::
    
    - Altere **o Período de Tempo** corretamente para filtrar o erro ou aviso do ACAT no Log de Atividades. 
    - Descubra o erro ou aviso do ACAT, selecione para obter os detalhes e salvar os detalhes como um arquivo.
    
- Verifique se sua assinatura está configurada corretamente pelo ACAT. 
    - Pesquise e inicie **as Assinaturas** [portal do Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D).
    - Vá para a assinatura que você deseja usar para criar o relatório de conformidade. 
    - Selecione **Provedor de** Recursos para verificar se o status desses provedores é *Registrado*.
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Voltar para [portal do Azure](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D) e iniciar **o Resource Graph Explorer**.
    - Selecionar **Nova consulta**
    - Execute essa consulta para verificar a atribuição de política e baixar o resultado como CSV. 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - Execute essa consulta para verificar a automação e baixar o resultado como CSV.

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - Execute essa consulta para verificar a avaliação e baixar o resultado como CSV. Você precisa substituir o espaço reservado ***your-subscriptionId*** pela assinatura específica que deseja consultar.

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```