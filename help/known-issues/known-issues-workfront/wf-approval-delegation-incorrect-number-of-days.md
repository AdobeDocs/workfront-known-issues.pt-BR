---
title: '"Aprovações: A delegação de aprovação é definida para o número incorreto de dias'''
description: Quando um usuário programa o Horário Pessoal Desativado e delega suas aprovações para esse período, a delegação de aprovação pode incluir dias antes ou depois do horário agendado.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
hidefromtoc: true
source-git-commit: de7f66f7acba1a0ac32a1257b2e643a767eae7fb
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# Aprovações: A delegação de aprovação é definida para o número incorreto de dias

>[!NOTE]
>
>Esse problema foi fechado porque não é um problema.

Quando um usuário programa a folga pessoal e delega suas aprovações para esse horário, a delegação de aprovação pode incluir dias antes ou depois da hora agendada.

**Solução alternativa**

Essa discrepância resulta de uma diferença entre o fuso horário em um perfil de usuário e o fuso horário do agendamento atribuído pelo usuário.

Recomendamos criar um agendamento exclusivo para cada fuso horário do qual os usuários trabalham e atribuir cada usuário ao agendamento que corresponde ao fuso horário em seu perfil de usuário.

_Primeiro reportado em 24 de março de 2022._
