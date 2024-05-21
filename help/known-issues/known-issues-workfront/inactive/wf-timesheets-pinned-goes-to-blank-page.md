---
title: '“Folhas de horas: folhas de horas fixadas levam a uma página em branco”'
description: “Quando uma pessoa clica em um pino no Workfront que deveria levar à sua folha de horas, ele leva a uma página em branco. Uma solução alternativa está disponível.”
hidefromtoc: true
feature: Timesheets
source-git-commit: 89eb14bfaccb517764af1711ca31e2926de63795
workflow-type: ht
source-wordcount: '123'
ht-degree: 100%

---


# Folhas de horas: folhas de horas fixadas levam a uma página em branco

Quando uma pessoa clica em um pino no Workfront que deveria levar à sua folha de horas, ele leva a uma página em branco.

Isso ocorre devido a uma alteração no URL da folha de horas. `/own` no fim do URL não é mais o URL correto. Se a pessoa tiver fixado um URL que inclua `/own`, esse pino levará a uma página em branco.

**Solução alternativa**

1. Desafixe a folha de horas.
1. Remova `/own` do fim do URL
1. Fixe a folha de horas novamente.

_Relatado pela primeira vez em quarta-feira, 7 de maio de 2024._

