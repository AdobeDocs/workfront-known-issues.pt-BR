---
title: ""
description: ""
hidefromtoc: true
source-git-commit: 63a50bd96799fb0c5338119dc4283100b0b01582
workflow-type: tm+mt
source-wordcount: '44'
ht-degree: 9%

---


# Formulários personalizados: A função HOUR em campos calculados usa UTC

Quando um campo calculado inclui a função HOUR , a função retorna valores com base em UTC, em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HOUR está incorreto.

_Reportado pela primeira vez em 17 de outubro de 2022._

