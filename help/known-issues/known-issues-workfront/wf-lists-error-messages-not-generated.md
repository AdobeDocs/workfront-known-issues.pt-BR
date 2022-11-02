---
title: "Listas: A edição em linha de erros por usuário não causa mensagens de erro"
description: "Quando um usuário está editando um objeto em linha e faz um erro que deve criar uma mensagem de erro, nenhuma mensagem de erro é exibida. O erro em si não é salvo no Workfront, portanto, os dados não são afetados, mas a falta de uma mensagem de erro pode causar confusão."
hidefromtoc: true
source-git-commit: ed5bd591f4be66631dba19d666b7d280eda1e1ab
workflow-type: tm+mt
source-wordcount: '165'
ht-degree: 2%

---


# Listas: Erros de edição embutidos pelo usuário não causam mensagens de erro

Quando um usuário está editando um objeto em linha e faz um erro que deve criar uma mensagem de erro, nenhuma mensagem de erro é exibida. O erro em si não é salvo no Workfront, portanto, os dados não são afetados, mas a falta de uma mensagem de erro pode causar confusão.

Isso foi relatado nas seguintes situações:

* Predecessores: Um loop predecessor é criado, como atribuir uma tarefa a si mesmo
* Datas: Uma data impossível é definida, como uma Data de conclusão anterior à Data de início ou que esteja além da Data de conclusão do projeto

_Reportado pela primeira vez em 26 de outubro de 2022._

