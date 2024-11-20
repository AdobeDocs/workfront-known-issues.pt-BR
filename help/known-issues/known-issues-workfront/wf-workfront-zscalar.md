---
title: "Workfront: configurações de ZScalar podem causar redução no desempenho"
description: "O serviço Web de ZScalar usa http/1.1 por padrão, o que pode causar redução no desempenho no Workfront."
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 77345937934851b8ebfdf257f44e25133eade971
workflow-type: tm+mt
source-wordcount: '81'
ht-degree: 6%

---


# Workfront: configurações de ZScalar podem causar redução no desempenho

>[!NOTE]
>
>Esse é um problema com ZScalar e não será corrigido pelo Workfront.

O serviço Web de ZScalar usa `http/1.1` por padrão, o que pode causar redução no desempenho do Workfront.

**Solução alternativa**

Configurar o software ZScalar para usar `http/2`. Isso não pode ser configurado no Workfront.

Você pode encontrar informações sobre `http/2` na documentação ZScalar.

_Relatado pela primeira vez em terça-feira, 18 de novembro de 2024._
