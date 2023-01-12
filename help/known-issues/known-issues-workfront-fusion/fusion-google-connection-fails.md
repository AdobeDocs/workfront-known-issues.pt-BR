---
title: '“Workfront Fusion: não é possível criar a conexão com o Google”'
description: Quando um usuário tenta criar uma conexão em qualquer um dos conectores do Google (como Google Sheets ou Google Drive), a conexão não é criada e o usuário vê várias mensagens de erro.
hidefromtoc: true
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
source-git-commit: dd093aff6103901898c561c9f6f544c1648682a3
workflow-type: tm+mt
source-wordcount: '109'
ht-degree: 94%

---

# [!DNL Workfront Fusion]: não é possível criar uma conexão com o [!DNL Google]

>[!NOTE]
>
>Esse problema foi corrigido em 9 de janeiro de 2023.

Ao tentar criar uma conexão em qualquer um dos conectores do [!DNL Google] (como [!DNL Google Sheets] ou [!DNL Google Drive]), o usuário vê uma janela com o seguinte erro:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Quando o usuário fecha essa janela, a conexão falha com o seguinte erro no [!DNL Fusion]:

“[!UICONTROL Erro: falha na solicitação devido à falha de uma solicitação anterior. Nenhum token de acesso especificado.]”

_Reportado pela primeira vez em 21 de novembro de 2022._
