---
title: 'O módulo Workfront Fusion: Pesquisa no Jira retorna um erro'
description: O módulo de pesquisa usado pelo conector Jira herdado pode resultar em um erro. Uma solução alternativa está disponível
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 0f4dba4664f645920752cc0c346782c9582b0e54
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 2%

---


# O módulo Workfront Fusion: Pesquisa no Jira retorna um erro

>[!NOTE]
>
>Esse problema se deve a uma alteração que a Jira fez em seu produto.

O módulo de pesquisa usado pelo conector Jira herdado pode resultar no seguinte erro:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046`

Isso se deve a uma descontinuação no lado de Jira.

Observe que:

* Somente o módulo de Pesquisa é afetado. No momento, outros endpoints da API Jira usados pelo conector Fusion não são afetados por essa desativação.

* A implantação geográfica pode causar inconsistências. A Atlassian está lançando essa alteração regionalmente, o que significa que algumas instâncias do Jira Cloud ainda podem oferecer suporte temporário a endpoints mais antigos. Isso pode levar a um comportamento inconsistente entre ambientes.

**Solução alternativa**

Se encontrar esse erro, você poderá substituir o módulo de pesquisa do conector Jira herdado pelo módulo de pesquisa do novo conector. Observe que o novo conector permite selecionar a versão da API usada. Certifique-se de selecionar **V3** no campo **Versão da API** ao criar a conexão.

_Relatado pela primeira vez em terça-feira, 15 de setembro de 2025._

