---
title: 'Aprovações: a delegação de aprovação é definida com o número incorreto de dias'
description: Quando um usuário programa a Folga pessoal e delega suas aprovações para esse período, a delegação de aprovação pode incluir dias antes ou depois do horário agendado.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 100%
---
# Aprovações: a delegação de aprovação é definida com o número incorreto de dias

<!--Live for workaround-->

>[!NOTE]
>
>Essa questão foi encerrada porque não é um problema.

Quando um usuário programa a folga pessoal e delega suas aprovações para esse período, a delegação de aprovação pode incluir dias antes ou depois do horário agendado.

**Solução**

Essa discrepância resulta de uma diferença entre o fuso horário em um perfil de usuário e o fuso horário do agendamento atribuído pelo usuário.

Recomendamos criar um agendamento exclusivo para cada fuso horário do qual os usuários trabalham e atribuir cada usuário ao agendamento que corresponde ao fuso horário em seu perfil de usuário.

_Relatado pela primeira vez em sexta-feira, 24 de março de 2022._
