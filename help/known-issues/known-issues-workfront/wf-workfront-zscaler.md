---
title: 'Workfront: as configurações do ZScaler podem causar redução no desempenho'
description: O serviço Web do ZScaler usa http/1.1 por padrão, o que pode causar redução de desempenho no Workfront.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
source-git-commit: 8bb5041a13374ce5dde6a1db173487f50d049f17
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---

# Workfront: as configurações do ZScaler podem causar redução no desempenho

>[!NOTE]
>
>Esse é um problema com o ZScaler e não será corrigido pelo Workfront.

O serviço Web do ZScaler usa `http/1.1` por padrão, o que pode causar redução de desempenho no Workfront.

**Solução alternativa**

Configurar o software ZScaler para usar o `http/2`. Isso não pode ser configurado no Workfront.

Você pode encontrar informações sobre `http/2` na documentação do ZScaler.

_Relatado pela primeira vez em terça-feira, 18 de novembro de 2024._
