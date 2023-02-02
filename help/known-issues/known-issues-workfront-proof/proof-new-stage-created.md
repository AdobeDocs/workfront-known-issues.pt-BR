---
title: '“Provas: nova etapa criada porque o prazo não pode corresponder ao prazo final da etapa existente”'
description: Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
hidefromtoc: true
source-git-commit: 3826558093ba7d8aa6ee25211010c60610d03fcc
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 100%

---

# Provas: nova etapa criada porque o prazo não pode corresponder ao prazo final da etapa existente

Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Portanto, o novo usuário não pode ser adicionado a um estágio com um prazo que termina em :15 ou :45, pois os prazos não podem ser combinados. Em vez disso, o novo usuário é adicionado a um novo estágio, com um prazo definido em incrementos de 30 minutos.

**Solução alternativa**:

* Se estiver selecionando um prazo para uma nova prova, defina o prazo como um horário que termina em :00 ou :30 (10:00, 10:30, 11:00, etc.).
* Se o prazo for definido automaticamente no momento da criação da prova, defina manualmente o prazo da prova para um horário que termine em :00 ou :30 (10:00, 10:30, 11:00, etc.).
