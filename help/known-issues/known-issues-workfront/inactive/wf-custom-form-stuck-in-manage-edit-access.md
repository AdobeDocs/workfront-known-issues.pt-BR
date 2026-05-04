---
title: 'Formulários personalizados: formulários personalizados entre objetos exigem acesso de Gerenciar ou Editar para editar campos'
description: Quando um usuário cria um formulário com objetos cruzados que permitem somente o acesso Gerenciar ou Editar e, em seguida, remove esse tipo de objeto, o formulário personalizado continua a exigir o acesso Gerenciar ou Editar para editar os campos. Não há nenhuma indicação visual de que os campos exigem acesso de Gerenciar ou Editar, nem como redefinir o formulário.
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
source-git-commit: 92419281092e3172a33499e288dd7867567a4ad5
workflow-type: tm+mt
source-wordcount: '188'
ht-degree: 92%

---

# Formulários personalizados: formulários personalizados entre objetos exigem acesso de [!UICONTROL Gerenciamento] ou [!UICONTROL Edição] para editar campos

<!--Won't fix, live for workaround-->

>[!NOTE]
>
>Esse problema foi encerrado

Quando um usuário cria um formulário com objetos cruzados que permitem somente o acesso [!UICONTROL Gerenciar] ou [!UICONTROL Editar] e, em seguida, remove esse tipo de objeto, o formulário personalizado continua a exigir o acesso [!UICONTROL Gerenciar] ou [!UICONTROL Editar] para editar os campos. Não há nenhuma indicação visual de que os campos exigem acesso de Gerenciar ou Editar, nem como redefinir o formulário.

**Solução**

1. Adicione uma quebra de seção ao formulário com valores padrão se for preenchido.
2. Mova a quebra de seção para a parte superior do formulário.
3. Salve o formulário.
4. Remova a quebra de seção recém-adicionada e salve o formulário novamente.

_Relatado pela primeira vez em quinta-feira, 9 de novembro de 2022._
