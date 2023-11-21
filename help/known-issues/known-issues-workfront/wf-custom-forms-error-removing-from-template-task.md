---
title: "Formulários personalizados: não é possível adicionar ou remover formulários personalizados em massa em tarefas de modelo"
description: "Se um usuário tentar adicionar ou remover um formulário personalizado em massa em uma tarefa de modelo, o formulário não será adicionado ou removido e o usuário verá um erro."
hidefromtoc: true
feature: Custom Forms
source-git-commit: 41df80641db82b225753338d8564e12b90566c40
workflow-type: tm+mt
source-wordcount: '153'
ht-degree: 5%

---


# Formulários personalizados: não é possível adicionar ou remover formulários personalizados em massa em tarefas de modelo

Se um usuário tentar adicionar ou remover um formulário personalizado em massa em uma tarefa de modelo, o formulário não será adicionado ou removido e o usuário verá o seguinte erro:

[!UICONTROL Vamos tentar novamente. Parâmetro inválido: valor de templateID &quot;XXXXXXXXXXXXXXXX&quot;]

Se o usuário localizar o modelo com a GUID especificada e tentar adicionar ou remover formulários personalizados no restante das tarefas do modelo, o erro ocorrerá novamente usando outra templateID.

Formulários personalizados podem ser adicionados ou removidos em uma única tarefa de modelo. Esse erro se aplica somente à adição ou remoção em massa.

_Relatado pela primeira vez em 10 de novembro de 2023._
