---
title: 'Workfront Fusion: o módulo de pesquisa do Jira retorna um erro'
description: O módulo de pesquisa usado pelo conector do Jira legado pode resultar em um erro. Há uma solução alternativa disponível
hidefromtoc: true
feature: Workfront Fusion
exl-id: 9502ffb3-f287-47b2-9b35-1a906345e924
source-git-commit: 8c2968464f1a7c8347a21367b940b8c298fde727
workflow-type: ht
source-wordcount: '186'
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
