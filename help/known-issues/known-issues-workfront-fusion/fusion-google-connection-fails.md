---
title: "Workfront Fusion: Não é possível criar a conexão com o Google"
description: "Quando um usuário tenta criar uma conexão em qualquer um dos conectores do Google (como Google Sheets ou Google Drive), a conexão não é criada e o usuário vê várias mensagens de erro."
hidefromtoc: true
source-git-commit: 7d50ddbd99edf3421ce92564590a2d8db76ae939
workflow-type: tm+mt
source-wordcount: '103'
ht-degree: 3%

---


# [!DNL Workfront Fusion]: Não é possível criar conexão com [!DNL Google]

Quando um usuário tenta criar uma conexão em qualquer uma das [!DNL Google] conectores (como [!DNL Google Sheets] ou [!DNL Google Drive]), eles veem uma janela aberta com o seguinte erro:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

Quando o usuário fecha essa janela, a conexão falha com o seguinte erro no [!DNL Fusion]:

&quot;[!UICONTROL Erro: A solicitação falhou devido à falha de uma solicitação anterior. Nenhum token de acesso especificado.]&quot;

_Reportado pela primeira vez em 21 de novembro de 2022._

