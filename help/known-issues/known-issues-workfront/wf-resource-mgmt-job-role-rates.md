---
title: "Gerenciamento de Recursos: cálculos financeiros incorretos devido a problemas de Função"
description: "As horas e os cálculos financeiros podem estar incorretos, mostrando um custo de 0 mesmo que as horas estejam registradas em uma função de trabalho que tenha uma taxa de custo."
hidefromtoc: true
feature: Resource Management
source-git-commit: e9a7ff289e7c9fcc9c9ff13b7c4b5b554e303c11
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 3%

---


# Gerenciamento de Recursos: cálculos financeiros incorretos devido a problemas de Função

Os cálculos de horas e finanças podem estar incorretos, mostrando um custo de 0 mesmo que as horas estejam conectadas em uma função de trabalho que tenha uma taxa de custo.

Isso ocorre porque as Funções de trabalho estão criando automaticamente taxas duplicadas sem datas de início ou término. Como não têm datas de início ou término, elas são tratadas como um valor 0 quando os cálculos financeiros são executados.

**Solução alternativa**

1. Salve os dados corretos passados.
1. Exclua as taxas duplicadas sem datas de início ou término.
1. Recalcule as finanças.

_Relatado pela primeira vez em 18 de janeiro de 2023._
