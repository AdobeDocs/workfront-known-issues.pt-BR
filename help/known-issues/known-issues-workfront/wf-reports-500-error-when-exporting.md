---
title: '“Relatórios: erro 500 ao exportar um relatório”'
description: Quando alguém tenta exportar um relatório, a exportação falha com um erro 500.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
source-git-commit: 88126bda7f7c51895ae512bb5f7686119febd32f
workflow-type: tm+mt
source-wordcount: '65'
ht-degree: 100%

---

# Relatórios: erro 500 ao exportar um relatório

>[!NOTE]
>
>Esse problema foi corrigido em 30 de novembro de 2023.

Quando alguém tenta exportar um relatório, a exportação falha com o seguinte erro:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Esse problema foi relatado em relatórios que usam um `valueexpression` para referenciar o texto da nota `lastNote`.

_Relatado pela primeira vez em 8 de novembro de 2023._
