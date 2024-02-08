---
title: '“Gerenciamento de recursos: cálculos financeiros incorretos devido a problemas de Função de trabalho”'
description: “As horas e os cálculos financeiros podem estar incorretos, mostrando um custo de 0 mesmo que as horas estejam registradas em uma função de trabalho que tenha uma taxa de custo.”
hidefromtoc: true
feature: Resource Management
source-git-commit: f8579e17458f702580e1a4cf3600c14376d7591b
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---


# Gerenciamento de recursos: cálculos financeiros incorretos devido a problemas de Função de trabalho

>[!NOTE]
>
>Esse problema foi corrigido em sexta-feira, 8 de fevereiro de 2024.

As horas e os cálculos financeiros podem estar incorretos, mostrando um custo de 0 mesmo que as horas estejam registradas em uma função de trabalho que tenha uma taxa de custo.

Isso ocorre porque as Funções de trabalho estão criando automaticamente taxas duplicadas sem datas de início ou término. Como não têm datas de início ou término, elas são tratadas como um valor 0 quando os cálculos financeiros são executados.

**Solução alternativa**

1. Certifique-se de que os dados anteriores corretos foram salvos.
1. Exclua as taxas duplicadas sem datas de início ou término.
1. Recalcule as finanças.

_Relatado pela primeira vez em 18 de janeiro de 2023._
