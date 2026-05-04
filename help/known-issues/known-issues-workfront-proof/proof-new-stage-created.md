---
title: 'Provas: uma nova etapa é criada porque o prazo não pode corresponder ao prazo final da etapa existente'
description: Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 44%

---

# Provas: uma nova etapa é criada porque o prazo não pode corresponder ao prazo final da etapa existente

<!--Requested article-->

Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Portanto, o novo usuário não pode ser adicionado a um estágio com um prazo final de :15 ou :45, pois os prazos finais não podem ser combinados. Em vez disso, o novo usuário é adicionado a um novo estágio, com um prazo definido em incrementos de 30 minutos.

**Solução alternativa**:

* Se estiver selecionando um prazo para uma nova prova, defina o prazo como um horário que termina em :00 ou :30 (10:00, 10:30, 11:00, etc.).
* Se o prazo for definido automaticamente no momento da criação da prova, defina manualmente o prazo da prova para um horário que termine em :00 ou :30 (10:00, 10:30, 11:00, etc.).
