---
title: "Página inicial: as tarefas em projetos com status Aprovado ou Planejamento não estão incluídas em Minhas tarefas ou na Lista de trabalho da página inicial"
description: "Tarefas de projetos com o status Aprovado ou Planejamento não são exibidas na Página inicial. Uma solução alternativa está disponível."
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 3%

---


# Página inicial: as tarefas em projetos com status Aprovado ou Planejamento não são incluídas em Minhas tarefas ou na Lista de trabalho da página inicial

Tarefas de projetos com o status Aprovado ou Planejamento não são exibidas nas seguintes áreas:

* Página inicial clássica: Lista de trabalho
* Nova Página inicial: o widget Minhas tarefas

Isso ocorre porque as tarefas de projetos nesses status estão atualmente incluídas no limite de consulta de item 2000, mas não são mostradas em Minhas tarefas ou na Lista de trabalho da página inicial. Isso pode criar uma situação em que um usuário com menos de 2000 tarefas, essas tarefas não estarão visíveis.

**Solução alternativa**

Crie um relatório de Atribuições personalizado que inclua os seguintes filtros do modo de texto:

Quando a atribuição estiver AWAITING_ACCEPTANCE, inclua os projetos ATUAIS|APROVADOS:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Quando a atribuição for ACEITA, inclua os projetos ATUAIS|APROVADOS|PLANEJAMENTO:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_Relatado pela primeira vez em 6 de novembro de 2023._
