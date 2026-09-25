---
title: 'Modelos de layout: campos de dados personalizados não são exibidos quando adicionados ao resumo da tarefa por meio do modelo de layout'
description: Quando um administrador adiciona um campo de dados personalizado à seção “Resumo da tarefa” por meio de um modelo de layout, o campo é exibido como vazio aos usuários que visualizam a seção de resumo de uma tarefa.
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 100%
---
# Modelos de layout: campos de dados personalizados não são exibidos quando adicionados ao resumo da tarefa por meio do modelo de layout

>[!NOTE]
>
>Esse problema foi encerrado porque o funcionamento está correto conforme projetado. Confira a solução abaixo.

Quando um administrador adiciona um campo de dados personalizado à seção “Resumo da tarefa” por meio de um modelo de layout, o campo é exibido como vazio aos usuários que visualizam a seção de resumo de uma tarefa.

**Solução**

Evite usar pontos (“.”) em nomes de campos personalizados para evitar esse problema. É possível renomear o campo personalizado na seção “Resumo” e incluir um ponto, se desejado.

_Relatado pela primeira vez em 2 de outubro de 2024._
