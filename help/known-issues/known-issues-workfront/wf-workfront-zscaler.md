---
title: 'Workfront: as configurações do ZScaler podem causar uma redução do desempenho'
description: O serviço da web do ZScaler usa http/1.1 por padrão, o que pode causar uma redução do desempenho no Workfront.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '83'
ht-degree: 100%
---
# Workfront: as configurações do ZScaler podem causar uma redução do desempenho

>[!NOTE]
>
>Esse é um problema com o ZScaler e não será corrigido pelo Workfront.

O serviço da web do ZScaler usa `http/1.1` por padrão, o que pode causar uma redução do desempenho no Workfront.

**Solução alternativa**

Configure o seu software do ZScaler para usar `http/2`. Isso não pode ser configurado no Workfront.

Você pode encontrar informações sobre `http/2` na documentação do ZScaler.

_Relatado pela primeira vez em 18 de novembro de 2024._
