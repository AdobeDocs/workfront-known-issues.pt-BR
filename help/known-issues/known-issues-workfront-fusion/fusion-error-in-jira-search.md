---
title: 'Workfront Fusion: o módulo de pesquisa do Jira retorna um erro'
description: O módulo de pesquisa usado pelo conector do Jira legado pode resultar em um erro. Há uma solução alternativa disponível
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 100%
---
# Workfront Fusion: o módulo de pesquisa do Jira retorna um erro

>[!NOTE]
>
>Esse problema deve-se a uma alteração que o Jira fez em seu produto.

O módulo de pesquisa usado pelo conector do Jira legado pode resultar no seguinte erro:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Deve-se a uma descontinuação feita pelo Jira.

Observe que:

* Somente o módulo de pesquisa é afetado. No momento, outros pontos de acesso da API do Jira usados pelo conector do Fusion não são afetados por essa descontinuação.

* A implantação geográfica pode causar inconsistências. A Atlassian está implantando essa alteração regionalmente, o que significa que algumas instâncias da Jira Cloud ainda podem ser compatíveis temporariamente com pontos de acesso mais antigos. Isso pode levar a um comportamento inconsistente entre ambientes.

**Solução**

Se você se deparar com esse erro, poderá substituir o módulo de pesquisa do conector do Jira legado pelo módulo de pesquisa do novo conector. Observe que o novo conector permite selecionar a versão da API usada. Certifique-se de selecionar **V3** no campo **Versão da API** ao criar a conexão.

_Relatado pela primeira vez em 15 de setembro de 2025._
