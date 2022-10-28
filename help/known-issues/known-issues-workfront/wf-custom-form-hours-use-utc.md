---
title: "Formulários personalizados: A função HOUR em campos calculados usa UTC"
description: "Quando um campo calculado inclui a função HOUR, a função retorna valores com base em UTC, em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HOUR está incorreto."
hidefromtoc: true
source-git-commit: c2fd207043d8d813dbea4695198b49a4cda5fbc2
workflow-type: tm+mt
source-wordcount: '84'
ht-degree: 4%

---


# Formulários personalizados: [!UICONTROL HORA] em campos calculados usa UTC

Quando um campo calculado inclui a variável [!UICONTROL HORA] , a função retorna valores com base em UTC em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HOUR está incorreto.

_Reportado pela primeira vez em 17 de outubro de 2022._

