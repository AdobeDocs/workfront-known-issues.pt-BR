---
title: '“Página inicial: as tarefas em projetos com status Aprovado ou Em planejamento não são incluídas em Minhas tarefas ou na Lista de trabalho da página inicial”'
description: “As tarefas de projetos com o status Aprovado ou Em planejamento não são exibidas na Página inicial. Uma solução alternativa está disponível.”
hidefromtoc: true
feature: Get Started with Workfront
source-git-commit: 5b22b37a13774e4552ec9390a70040f0182851d3
workflow-type: ht
source-wordcount: '166'
ht-degree: 100%

---


# Página inicial: as tarefas em projetos com status Aprovado ou Em planejamento não são incluídas em Minhas tarefas ou na Lista de trabalho da página inicial

Tarefas de projetos com o status Aprovado ou Em planejamento não são exibidas nas seguintes áreas:

* Página inicial clássica: Lista de trabalho
* Nova página inicial: dispositivo Minhas tarefas

Isso ocorre porque as tarefas de projetos nesses status estão atualmente incluídas no limite de consulta de 2000 itens, mas não são exibidas em Minhas tarefas ou na Lista de trabalho da página inicial. Isso pode criar uma situação em que essas tarefas não estejam visíveis para uma pessoa com um número de tarefas menor que 2000.

**Solução alternativa**

Crie um Relatório de atribuições personalizado que inclua os seguintes filtros do modo de texto:

Quando a atribuição estiver em AWAITING_ACCEPTANCE, inclua os projetos CURRENT|APPROVED:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

Quando a atribuição estiver como ACCEPTED, inclua os projetos CURRENT|APPROVED|PLANNING:

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
