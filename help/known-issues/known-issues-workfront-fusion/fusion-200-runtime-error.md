---
title: 'Workfront Fusion: RuntimeError com resposta 200 do módulo Workfront'
description: Um módulo Workfront pode retornar uma resposta “RuntimeError [200]”. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: d88a785bb980ad4dcbb5ccb6b1b1bfb0cb61a161
workflow-type: tm+mt
source-wordcount: '96'
ht-degree: 100%

---

# Workfront Fusion: RuntimeError com resposta 200 do módulo Workfront

>[!NOTE]
>
>Esse problema foi corrigido em sexta-feira, 25 de julho de 2024.

Um módulo do Workfront pode retornar uma resposta `RuntimeError [200]`. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.

Isso pode ocorrer se a resposta for extremamente longa. Os dados são retornados ao Fusion, mas não podem ser processados por ele.

_Relatado pela primeira vez em quinta-feira, 3 de janeiro de 2024._
