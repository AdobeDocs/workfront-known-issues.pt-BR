---
title: 'Folhas de horas: folhas de horas fixadas levam a uma página em branco'
description: Quando uma pessoa clica em um pino no Workfront que deveria levar à sua folha de horas, em vez disso, o pino leva a uma página em branco. Há uma solução alternativa disponível.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '126'
ht-degree: 100%
---
# Folhas de horas: folhas de horas fixadas levam a uma página em branco

<!--article live for workaround-->

Quando uma pessoa clica em um pino no Workfront que deveria levar à sua folha de horas, em vez disso, o pino leva a uma página em branco.

Isso ocorre devido a uma alteração no URL da folha de horas. `/own` no fim do URL não é mais o URL correto. Se a pessoa tiver fixado um URL que inclua `/own`, esse pino levará a uma página em branco.

**Solução**

1. Desafixe a folha de horas.
1. Remova `/own` do fim do URL
1. Fixe a folha de horas novamente.

_Relatado pela primeira vez em quarta-feira, 7 de maio de 2024._
