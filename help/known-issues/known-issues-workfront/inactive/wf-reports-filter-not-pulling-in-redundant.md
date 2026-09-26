---
title: 'Relatórios: o filtro de relatório não retorna os resultados esperados'
description: Um filtro em um relatório pode não retornar todos os resultados esperados. Há uma solução alternativa disponível.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '100'
ht-degree: 100%
---
# Relatórios: o filtro de relatório não retorna os resultados esperados

>[!NOTE]
>
>Esse problema foi encerrado.

Um filtro em um relatório pode não retornar todos os resultados esperados.

Isso pode ocorrer quando o filtro é configurado para retornar resultados com determinados critérios e inclui uma regra OU que retorna resultados que são um subconjunto desses mesmos critérios.

**Solução**

Certifique-se de que os blocos OU do filtro não incluam critérios de avaliação idênticos.

_Relatado pela primeira vez em terça-feira, 11 de março de 2024._
