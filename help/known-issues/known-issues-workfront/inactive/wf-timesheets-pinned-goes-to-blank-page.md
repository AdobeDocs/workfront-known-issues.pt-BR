---
title: '“Folhas de horas: folhas de horas fixadas levam a uma página em branco”'
description: Quando uma pessoa clica em um pino no Workfront que deveria levar à sua folha de horas, em vez disso, o pino leva a uma página em branco. Uma solução alternativa está disponível.
hidefromtoc: true
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
source-git-commit: 1aed6a440155c99f8ce0b0f42c44dd9a3c660af4
workflow-type: ht
source-wordcount: '123'
ht-degree: 100%

---

# Folhas de horas: folhas de horas fixadas levam a uma página em branco

<!--article live for workaround-->

Quando uma pessoa clica em um pino no Workfront que deveria levar à sua folha de horas, ele leva a uma página em branco.

Isso ocorre devido a uma alteração no URL da folha de horas. `/own` no fim do URL não é mais o URL correto. Se a pessoa tiver fixado um URL que inclua `/own`, esse pino levará a uma página em branco.

**Solução alternativa**

1. Desafixe a folha de horas.
1. Remova `/own` do fim do URL
1. Fixe a folha de horas novamente.

_Relatado pela primeira vez em quarta-feira, 7 de maio de 2024._
