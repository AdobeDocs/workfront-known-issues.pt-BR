---
title: "Workfront Fusion: formatação de saída para datas"
description: "Quando as Datas são geradas como Cadeias de Caracteres, a data pode ser gerada como UTC ou ISO. Isso depende da lógica em um painel de mapeamento."
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 32196793e652b6b498e623ba8857039d6311c796
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 0%

---


# Workfront Fusion: formatação de saída para datas

Quando as Datas são geradas como Cadeias de Caracteres, a data pode ser gerada como uma UTC ou uma cadeia de caracteres ISO. Depende da lógica em um painel de mapeamento:

* Se uma Data em uma função estiver unida a uma string, a string será gerada em **UTC** formato.
* Se a Data não estiver unida em uma função, ela será gerada como um **String ISO**.

Os clientes devem usar o `toString` (para ISO) ou `formatDate` funções para garantir que os resultados estejam no formato necessário.
