---
title: "Formulários personalizados: A função HOUR em campos calculados usa UTC"
description: "Quando um campo calculado inclui a função HOUR, a função retorna valores com base em UTC, em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HOUR está incorreto."
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 4%

---


# Formulários personalizados: [!UICONTROL HORA] em campos calculados usa UTC

>[!NOTE]
>
>Esse problema foi corrigido em 3 de novembro de 2022.

Quando um campo calculado inclui a variável [!UICONTROL HORA] , a função retorna valores com base em UTC em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HOUR está incorreto.

_Reportado pela primeira vez em 17 de outubro de 2022._

