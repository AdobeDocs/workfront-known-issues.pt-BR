---
title: 'Provas: uma nova etapa é criada porque o prazo não pode corresponder ao prazo final da etapa existente'
description: Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.).
feature: Workfront Proof
exl-id: dc0725f4-d31b-4f55-a3ea-24486ce73ebf
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '243'
ht-degree: 64%
---
# Provas: uma nova etapa é criada porque o prazo não pode corresponder ao prazo final da etapa existente

<!--Requested article-->

Quando uma nova prova é criada, o prazo pode ser definido em um incremento de 15 minutos (10:00, 10:15, 10:30, 20:45, etc.). No entanto, quando um usuário é adicionado após a criação da prova, o prazo só pode ser definido em incrementos de 30 minutos (10:00, 10:30, 11:00, etc.). Portanto, o novo usuário não pode ser adicionado a um estágio com um prazo que termina em :15 ou :45, pois os prazos não podem ser combinados. Em vez disso, o novo usuário é adicionado a um novo estágio, com um prazo definido em incrementos de 30 minutos.

**Solução alternativa**:

* Se estiver selecionando um prazo para uma nova prova, defina o prazo como um horário que termine às 10h ou 30h (10h, 10h30, 11h, etc.).
* Se o prazo for definido automaticamente no momento da criação da prova, defina manualmente o prazo da prova para um horário que termine em :00 ou :30 (10:00, 10:30, 11:00, etc.).
