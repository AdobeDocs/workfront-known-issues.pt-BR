---
title: '“Formulários personalizados: não é possível usar o campo no cálculo se o nome do campo contiver aspas ou um apóstrofo”'
description: “Quando um usuário está criando uma expressão de campo calculado e tenta incluir um campo de digitação antecipada que tenha um nome com um apóstrofo ou aspas, o cálculo não é aceito e o usuário vê a mensagem Esta expressão personalizada é inválida, tente novamente.”
hidefromtoc: true
source-git-commit: 3307a9be28555d0b9561e8ae96e3667cb1fee711
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 100%

---


# Formulários personalizados: não é possível usar o campo no cálculo se o nome do campo contiver apóstrofos ou aspas

>[!NOTE]
>
>Esse problema foi corrigido em 2 de março de 2023.

Quando um usuário cria uma expressão de campo calculado e tenta incluir um campo de digitação antecipada que tem um nome com um `'` ou `"`, o cálculo não é aceito e o usuário vê a mensagem “[!UICONTROL Esta expressão personalizada é inválida. Tente novamente.]”

Esse problema existe apenas com campos de digitação antecipada. Campos de texto com `'` ou `"` no nome podem ser usados em expressões de campo calculado sem problemas.

_Reportado pela primeira vez em 10 de novembro de 2022._

