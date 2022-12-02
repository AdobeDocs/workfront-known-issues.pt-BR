---
title: '“Listas: a edição em linha de erros por usuário não causa mensagens de erro”'
description: “Quando um usuário está editando um objeto em linha e faz um erro que deveria criar uma mensagem de erro, nenhuma mensagem de erro é exibida. O erro em si não é salvo no Workfront, portanto, os dados não são afetados, mas a falta de uma mensagem de erro pode causar confusão.”
hidefromtoc: true
source-git-commit: 2951a566384274e5f32544dd8be1872f3850af94
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 96%

---


# Listas: erros de edição em linha pelo usuário não causam mensagens de erro

>[!NOTE]
>
>Esse problema foi corrigido em 1º de dezembro de 2022.

Quando um usuário está editando um objeto em linha e faz um erro que deveria criar uma mensagem de erro, nenhuma mensagem de erro é exibida. O erro em si não é salvo no Workfront, portanto, os dados não são afetados, mas a falta de uma mensagem de erro pode causar confusão.

Esse problema foi relatado para as seguintes situações:

* Predecessores: um loop predecessor é criado, como atribuir uma tarefa a si mesmo
* Datas: uma data impossível é definida, como uma Data de conclusão anterior à Data de início ou que esteja além da Data de conclusão do projeto

_Reportado pela primeira vez em 26 de outubro de 2022._

