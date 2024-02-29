---
title: '“Workfront Fusion: RuntimeError com resposta 200 do módulo Workfront”'
description: “Um módulo Workfront pode retornar uma resposta `RuntimeError [200]`. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.”
hidefromtoc: true
feature: Workfront Fusion
source-git-commit: 67ae05de95f667bb3fa7c1b06271bbe644682472
workflow-type: ht
source-wordcount: '90'
ht-degree: 100%

---


# Workfront Fusion: RuntimeError com resposta 200 do módulo Workfront

Um módulo do Workfront pode retornar uma resposta `RuntimeError [200]`. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.

Isso pode ocorrer se a resposta for extremamente longa. Os dados são retornados ao Fusion, mas não podem ser processados por ele.

_Relatado pela primeira vez em quinta-feira, 3 de janeiro de 2024._
