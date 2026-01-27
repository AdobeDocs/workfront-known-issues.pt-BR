---
title: 'Modelos de layout: campos de dados personalizados não são exibidos quando adicionados ao resumo da tarefa por meio do modelo de layout'
description: Quando um administrador adiciona um campo de dados personalizado à seção “Resumo da tarefa” por meio de um modelo de layout, o campo é exibido como vazio aos usuários que visualizam a seção de resumo de uma tarefa.
hidefromtoc: true
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
source-git-commit: 273f533553626082787f579b171ab4b314743d58
workflow-type: ht
source-wordcount: '137'
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
