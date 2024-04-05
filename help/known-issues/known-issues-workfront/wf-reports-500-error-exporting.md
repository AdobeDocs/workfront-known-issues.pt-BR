---
title: "Relatórios: erro 500 ao exportar um relatório"
description: '"Quando um usuário tenta exportar um relatório, ele não é exportado e o usuário vê um erro. Uma solução alternativa está disponível.”'
hidefromtoc: true
feature: Reports and Dashboards
source-git-commit: 0dbb29f11088b5c963f7972f3ec9e64ee55d6263
workflow-type: tm+mt
source-wordcount: '99'
ht-degree: 16%

---


# Relatórios: erro 500 ao exportar um relatório

Quando um usuário tenta exportar um relatório, ele não é exportado e o usuário vê o seguinte erro:

500: Não é possível invocar &quot;com.attask.biz.Parameter.getDisplayType()&quot; porque o &quot;parâmetro&quot; é nulo /attask/api-internal/report/export

Isso ocorre quando o relatório faz referência a um campo de moeda personalizado no nível do projeto.

**Solução alternativa**

Remova a coluna que faz referência ao campo de moeda personalizado e exporte o relatório novamente.

_Relatado pela primeira vez em sexta-feira, 4 de abril de 2024._

