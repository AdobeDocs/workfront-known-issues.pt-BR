---
title: 'Workfront Fusion: saída de formatação de datas'
description: Quando as datas são geradas como strings, a data pode ser gerada como uma string UTC ou ISO. Isso depende da lógica em um painel de mapeamento.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
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
source-wordcount: '120'
ht-degree: 92%
---
# Workfront Fusion: saída de formatação de datas

Quando as datas são geradas como strings, a data pode ser gerada como uma string UTC ou ISO. Isso depende da lógica em um painel de mapeamento:

* Se uma data em uma função estiver unida a uma string, a string será gerada no formato **UTC**.
* Se a data não estiver unida em uma função, ela será gerada como uma **String ISO**.

Clientes devem usar as funções `toString` (para ISO) ou `formatDate` para garantir que os resultados estejam no formato necessário.
