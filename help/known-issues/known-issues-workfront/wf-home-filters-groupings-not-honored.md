---
title: "Nova página inicial: os padrões de filtro e agrupamento de widgets não seguem o modelo de layout"
description: Quando um usuário visualiza o widget Meus projetos, Minhas tarefas ou Meus problemas na nova experiência Página inicial, o filtro e o agrupamento padrão desse widget não são a configuração padrão no modelo de layout atribuído a esse usuário.
hidefromtoc: true
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
source-git-commit: 036cedbdabb7dd32cd78cb0c924dbcefabeb05bb
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 36%

---

# Nova [!UICONTROL Página inicial]: os padrões de filtro e agrupamento de widgets não seguem o modelo de layout

>[!NOTE]
>
>Este problema foi encerrado porque o programa está funcionando conforme projetado.

Quando um usuário visualiza o dispositivo [!UICONTROL Meus Projetos], [!UICONTROL Minhas Tarefas] ou [!UICONTROL Meus problemas] na nova experiência da [!UICONTROL Página inicial], o filtro e o agrupamento padrão desse dispositivo não estão na configuração padrão do modelo de layout atribuído a esse usuário.

**Solução alternativa**:

Ao usar a Nova página inicial, é importante lembrar que as configurações do usuário (preferências) são priorizadas. Como resultado, se você definir um filtro ou agrupamento padrão para um widget específico usando um modelo de layout, ele pode não ter efeito imediatamente devido às preferências do usuário existentes. Para aplicar o novo filtro ou agrupamento, talvez seja necessário redefinir as preferências ou o usuário. Isso pode ser feito anexando `/resetUser` ao URL.

_Relatado pela primeira vez em 3 de janeiro de 2024._
