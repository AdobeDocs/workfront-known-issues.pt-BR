---
title: 'Portfólios: usuários não conseguem definir o portfólio'
description: Usuários não podem alterar portfólios em um projeto se não tiverem acesso ao portfólio.
feature: Work Management
exl-id: 38ad277a-2087-486c-8715-93e275488697
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 100%
---
# Portfólios: usuários não conseguem definir o portfólio

>[!NOTE]
>
>Esse problema foi encerrado porque o funcionamento está correto conforme projetado.

Usuários não podem alterar portfólios em um projeto se não tiverem acesso ao portfólio.

Esse problema foi relatado nos seguintes cenário:

* Se um usuário não tiver acesso a um portfólio atribuído em um projeto, ele não poderá alterar o portfólio conforme necessário, mesmo que tenha acesso ao portfólio para o qual está tentando mover o projeto.
* Ao tentar criar um projeto usando um modelo de projeto, se o usuário que está criando o projeto não tiver acesso ao portfólio ou programa no modelo, o projeto não será criado com esses objetos atribuídos e o projeto será exibido como independente (sem portfólio ou atribuição de projeto).

**Solução**

A administração pode conceder acesso ou fazer ajustes, conforme necessário.

_Relatado pela primeira vez em 26 de junho de 2024._
