---
title: '“Aprovações: a delegação de aprovação é definida com o número incorreto de dias”'
description: Quando um usuário programa a Folga pessoal e delega suas aprovações para esse período, a delegação de aprovação pode incluir dias antes ou depois do horário agendado.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
hidefromtoc: true
source-git-commit: 688d728782638489aacc76a1a12c38ab12215f8e
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 100%

---

# Aprovações: a delegação de aprovação é definida com o número incorreto de dias

>[!NOTE]
>
>Esse problema foi encerrado porque não é um problema.

Quando um usuário programa a folga pessoal e delega suas aprovações para esse período, a delegação de aprovação pode incluir dias antes ou depois do horário agendado.

**Solução alternativa**

Essa discrepância resulta de uma diferença entre o fuso horário em um perfil de usuário e o fuso horário do agendamento atribuído pelo usuário.

Recomendamos criar um agendamento exclusivo para cada fuso horário do qual os usuários trabalham e atribuir cada usuário ao agendamento que corresponde ao fuso horário em seu perfil de usuário.

_Reportado pela primeira vez em 24 de março de 2022._
