---
title: 'Workfront: as configurações do ZScaler podem causar uma redução do desempenho'
description: O serviço da web do ZScaler usa http/1.1 por padrão, o que pode causar uma redução do desempenho no Workfront.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
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
