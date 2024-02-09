---
title: '“Workfront Fusion: saída de formatação de datas”'
description: “Quando as datas são geradas como strings, a data pode ser gerada como uma string UTC ou ISO. Isso depende da lógica em um painel de mapeamento.”
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---


# Workfront Fusion: saída de formatação de datas

Quando as datas são geradas como strings, a data pode ser gerada como uma string UTC ou ISO. Isso depende da lógica em um painel de mapeamento:

* Se uma data em uma função estiver unida a uma string, a string será gerada no formato **UTC**.
* Se a data não estiver unida em uma função, ela será gerada como uma **String ISO**.

Clientes devem usar as funções `toString` (para ISO) ou `formatDate` para garantir que os resultados estejam no formato necessário.
