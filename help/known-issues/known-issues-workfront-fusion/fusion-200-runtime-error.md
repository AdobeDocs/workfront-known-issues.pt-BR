---
title: "Workfront Fusion: RuntimeError com resposta 200 do módulo Workfront"
description: Um módulo Workfront pode retornar uma resposta "RuntimeError [200]". O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.
hidefromtoc: true
feature: Workfront Fusion
exl-id: 99967e3b-08bd-4035-b0b2-b90eff8cf1a1
source-git-commit: 50f79121e0b027c3f0283cd43d19c885dde8268b
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 78%

---

# Workfront Fusion: RuntimeError com resposta 200 do módulo Workfront

<!--

>[!NOTE]
>
>This issue was fixed on March 28, 2024.

-->

Um módulo do Workfront pode retornar uma resposta `RuntimeError [200]`. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.

Isso pode ocorrer se a resposta for extremamente longa. Os dados são retornados ao Fusion, mas não podem ser processados por ele.

_Relatado pela primeira vez em quinta-feira, 3 de janeiro de 2024._
