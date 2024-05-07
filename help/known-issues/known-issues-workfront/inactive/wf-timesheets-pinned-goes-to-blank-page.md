---
title: "Folhas de horas: a folha de horas fixada vai para uma página em branco"
description: '"Quando um usuário clica em um pino no Workfront que deve ir para a folha de horas, o pino vai para uma página em branco. Uma solução alternativa está disponível.”'
hidefromtoc: true
feature: Timesheets
source-git-commit: 229d3accabec51a7c559279b680336ca096c0e70
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 7%

---


# Folhas de horas: a folha de horas fixada vai para uma página em branco

Quando um usuário clica em um pino no Workfront que deve ir para a folha de horas, o pino vai para uma página em branco.

Isso ocorre porque a URL da folha de horas mudou. o `/own` no final do URL não é mais o URL correto. Se o usuário tiver fixado um URL que inclua `/own`, esse pino abre uma página em branco.

**Solução alternativa**

1. Desafixar a folha de horas.
1. Remover `/own` do final do URL
1. Fixar novamente a folha de horas.

_Relatado pela primeira vez em quarta-feira, 7 de maio de 2024._

