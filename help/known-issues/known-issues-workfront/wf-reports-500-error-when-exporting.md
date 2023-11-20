---
title: "Relatórios: erro 500 ao exportar um relatório"
description: "Quando um usuário tenta exportar um relatório, a exportação falha com um erro 500."
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 8fcd13b3586664d7540e64fb855f7f84e6e7cdc7
workflow-type: tm+mt
source-wordcount: '59'
ht-degree: 0%

---


# Relatórios: erro 500 ao exportar um relatório

Quando um usuário tenta exportar um relatório, a exportação falha com o seguinte erro:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Esse problema foi relatado em relatórios que usam um `valueexpression` para referenciar a `lastNote` texto da nota.

_Reportado pela primeira vez em 8 de novembro de 2023._
