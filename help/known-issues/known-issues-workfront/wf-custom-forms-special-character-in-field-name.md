---
title: '“Formulários personalizados: não é possível usar o campo no cálculo se o nome do campo contiver aspas ou um apóstrofo”'
description: “Quando um usuário está criando uma expressão de campo calculado e tenta incluir um campo de digitação antecipada que tenha um nome com um apóstrofo ou aspas, o cálculo não é aceito e o usuário vê a mensagem Esta expressão personalizada é inválida, tente novamente.”
hidefromtoc: true
source-git-commit: 254339d1baa9d8d7825e851aeafc9b27b1a1b669
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 100%

---


# Formulários personalizados: não é possível usar o campo no cálculo se o nome do campo contiver apóstrofos ou aspas

>[!NOTE]
>
>A equipe do produto está avaliando a resolução do problema, que pode exigir melhorias do produto. As melhorias do produto são comunicadas nos Anúncios do produto e não nas Atualizações de manutenção.

Quando um usuário cria uma expressão de campo calculado e tenta incluir um campo de digitação antecipada que tem um nome com um `'` ou `"`, o cálculo não é aceito e o usuário vê a mensagem “[!UICONTROL Esta expressão personalizada é inválida. Tente novamente.]”

Esse problema existe apenas com campos de digitação antecipada. Campos de texto com `'` ou `"` no nome podem ser usados em expressões de campo calculado sem problemas.

_Reportado pela primeira vez em 10 de novembro de 2022._

