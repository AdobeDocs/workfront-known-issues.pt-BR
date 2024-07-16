---
title: '“Provas: nova etapa criada porque o prazo não pode corresponder ao prazo final da etapa existente”'
description: Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
hidefromtoc: true
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 100%

---

# Provas: nova etapa criada porque o prazo não pode corresponder ao prazo final da etapa existente

<!--Requested article-->

Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Portanto, o novo usuário não pode ser adicionado a um estágio com um prazo que termina em :15 ou :45, pois os prazos não podem ser combinados. Em vez disso, o novo usuário é adicionado a um novo estágio, com um prazo definido em incrementos de 30 minutos.

**Solução alternativa**:

* Se estiver selecionando um prazo para uma nova prova, defina o prazo como um horário que termina em :00 ou :30 (10:00, 10:30, 11:00, etc.).
* Se o prazo for definido automaticamente no momento da criação da prova, defina manualmente o prazo da prova para um horário que termine em :00 ou :30 (10:00, 10:30, 11:00, etc.).
