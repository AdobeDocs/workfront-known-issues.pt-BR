---
title: 'Permissões: as permissões de objetos não são herdadas corretamente'
description: Permissões herdadas não são aplicadas corretamente a objetos. Isso pode ocorrer devido à complexidade das permissões herdadas.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 100%
---
# Permissões: as permissões de objetos não são herdadas corretamente

>[!NOTE]
>
>A equipe do produto está avaliando a resolução do problema, que pode exigir melhorias do produto. As melhorias do produto são comunicadas nos Anúncios do produto e não nas Atualizações de manutenção.

Permissões herdadas não são aplicadas corretamente a objetos. Isso pode ocorrer devido à complexidade das permissões herdadas, que podem ser afetadas pelo seguinte:

* O objeto é compartilhado com um grande número de pessoas
* Um grande número de objetos é afetado por uma alteração em uma permissão herdada

**Solução**

Limitar o tamanho ou a complexidade dos objetos pode ajudar a evitar esse problema. Recomendamos que você não tenha mais de 10 mil objetos secundários em nenhum objeto principal.

_Relatado pela primeira vez em 21 de março de 2025._
