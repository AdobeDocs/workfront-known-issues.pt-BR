---
title: "Formulários personalizados: Não é possível usar o campo no cálculo se o nome do campo contiver aspas ou um apóstrofo"
description: "Quando um usuário está criando uma expressão de campo calculado e tenta incluir um campo typeahead que tenha um nome com um apóstrofo ou aspas, o cálculo não é aceito e o usuário vê a mensagem Esta é uma expressão personalizada inválida, tente novamente."
hidefromtoc: true
source-git-commit: 0c260518bc0b268d734e309bef11b613fee90172
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Formulários personalizados: Não é possível usar o campo no cálculo se o nome do campo contiver apóstrofos ou aspas

Quando um usuário cria uma expressão de campo calculado e tenta incluir um campo typeforward que tem um nome com uma `'` ou `"`, o cálculo não é aceito e o usuário vê a mensagem &quot;[!UICONTROL Esta é uma expressão personalizada inválida. Tente novamente.]&quot;

Esse problema existe apenas com campos typeahead. Campos de texto com `'` ou `"` no nome pode ser usado em expressões de campo calculado sem problemas.

_Reportado pela primeira vez em 10 de novembro de 2022._

