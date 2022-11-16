---
title: '“Formulários personalizados: a função HORA em campos calculados usa UTC”'
description: Quando um campo calculado inclui a função HORA, a função retorna valores com base em UTC, em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HORA está incorreto.
hidefromtoc: true
exl-id: f4f9fb6e-6226-4603-9518-4c935a644039
source-git-commit: 66e3bc22d8aef2d6287161f4a13fbbe0f3ac99c8
workflow-type: ht
source-wordcount: '90'
ht-degree: 100%

---

# Formulários personalizados: a função [!UICONTROL HORA] em campos calculados usa UTC

>[!NOTE]
>
>Esse problema foi corrigido em 3 de novembro de 2022.

Quando um campo calculado inclui a função [!UICONTROL HORA], a função retorna valores com base em UTC, em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HORA está incorreto.

_Reportado pela primeira vez em 17 de outubro de 2022._
