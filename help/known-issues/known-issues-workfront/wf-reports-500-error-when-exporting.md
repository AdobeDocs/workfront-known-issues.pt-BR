---
title: '“Relatórios: erro 500 ao exportar um relatório”'
description: Quando alguém tenta exportar um relatório, a exportação falha com um erro 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 45cea090d9e54514be9983b5443e7ee54b1f2d94
workflow-type: ht
source-wordcount: '59'
ht-degree: 100%

---

# Relatórios: erro 500 ao exportar um relatório

Quando alguém tenta exportar um relatório, a exportação falha com o seguinte erro:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Esse problema foi relatado em relatórios que usam um `valueexpression` para referenciar o texto da nota `lastNote`.

_Relatado pela primeira vez em 8 de novembro de 2023._
