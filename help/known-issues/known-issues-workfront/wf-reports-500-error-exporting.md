---
title: '“Relatórios: erro 500 ao exportar um relatório”'
description: Quando um usuário tenta exportar um relatório, ele não é exportado e o usuário vê um erro. Uma solução alternativa está disponível.
hidefromtoc: true
feature: Reports and Dashboards
exl-id: 5ebdf00e-122b-4646-b9d8-8775d6e7c1cf
source-git-commit: cebbfd27b0d07c77706a609e38935f01d9727404
workflow-type: tm+mt
source-wordcount: '105'
ht-degree: 27%

---

# Relatórios: erro 500 ao exportar um relatório

>[!NOTE]
>
>O problema foi corrigido em sábado, 5 de abril de 2024.

Quando um usuário tenta exportar um relatório, ele não é exportado e o usuário vê o seguinte erro:

500: Não é possível invocar &quot;com.attask.biz.Parameter.getDisplayType()&quot; porque o &quot;parâmetro&quot; é nulo /attask/api-internal/report/export

Isso ocorre quando o relatório faz referência a um campo de moeda personalizado no nível do projeto.

**Solução alternativa**

Remova a coluna que faz referência ao campo de moeda personalizado e exporte o relatório novamente.

_Relatado pela primeira vez em sexta-feira, 4 de abril de 2024._
