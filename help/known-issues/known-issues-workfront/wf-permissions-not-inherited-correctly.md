---
title: 'Permissões: as permissões do objeto não são herdadas corretamente'
description: Permissões herdadas não estão sendo aplicadas corretamente a objetos. Isso pode ocorrer devido à complexidade das permissões herdadas.
hidefromtoc: true
feature: Projects, Tasks, Work Management
source-git-commit: 798be3dd7ef5e7bf0ecf14484242f7758ac9d9a4
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 22%

---


# Permissões: as permissões do objeto não são herdadas corretamente

>[!NOTE]
>
>A equipe do produto está avaliando a resolução do problema, que pode exigir melhorias do produto. As melhorias do produto são comunicadas nos Anúncios do produto e não nas Atualizações de manutenção.

Permissões herdadas não estão sendo aplicadas corretamente a objetos. Isso pode ocorrer devido à complexidade das permissões herdadas, que podem ser afetadas pelo seguinte:

* O objeto é compartilhado com um grande número de pessoas
* Um grande número de objetos é afetado por uma alteração de permissão herdada

**Solução alternativa**

Limitar o tamanho ou a complexidade dos objetos pode ajudar a evitar esse problema. Recomendamos que você não tenha mais de 10.000 objetos filho em nenhum objeto pai.

_Relatado pela primeira vez em sábado, 21 de março de 2025._
