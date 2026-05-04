---
title: 'Workfront Fusion: saída de formatação de datas'
description: Quando as datas são geradas como strings, a data pode ser gerada como uma string UTC ou ISO. Isso depende da lógica em um painel de mapeamento.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 92%

---

# Workfront Fusion: saída de formatação de datas

Quando as datas são geradas como strings, a data pode ser gerada como uma string UTC ou ISO. Isso depende da lógica em um painel de mapeamento:

* Se uma data em uma função estiver unida a uma string, a string será gerada no formato **UTC**.
* Se a data não estiver unida em uma função, ela será gerada como uma **String ISO**.

Clientes devem usar as funções `toString` (para ISO) ou `formatDate` para garantir que os resultados estejam no formato necessário.
