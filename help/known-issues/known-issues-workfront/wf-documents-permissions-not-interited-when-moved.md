---
title: 'Documentos: as permissões não são herdadas quando um documento é movido para um novo projeto'
description: '''Quando um usuário move um documento para um projeto diferente, o documento não herda as permissões de compartilhamento do novo projeto. O documento não é compartilhado com os usuários para os quais o projeto é compartilhado. ”'
hidefromtoc: true
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
source-git-commit: 17906db6aadc416c8be01e60d1b796143c97c061
workflow-type: tm+mt
source-wordcount: '179'
ht-degree: 100%

---

# Documentos: as permissões não são herdadas quando um documento é movido para um novo projeto

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Valid issue, won't fix.-->

Quando um usuário move um documento para um projeto diferente, o documento não herda as permissões de compartilhamento do novo projeto. O documento não é compartilhado com os usuários para os quais o projeto é compartilhado.

**Solução alternativa:**

1. Navegue até o objeto principal do documento, como um Projeto, Tarefa ou Problema.

1. Remova as permissões herdadas da lista de compartilhamento do objeto principal clicando no “X” ao lado das permissões herdadas e, em seguida, clique em **[!UICONTROL Salvar]**.

1. Adicione novamente as permissões herdadas navegando de volta para a lista de compartilhamento do objeto principal e clicando em **[!UICONTROL Desfazer]** ao lado das permissões herdadas e, em seguida, clique em **[!UICONTROL Salvar]**.

Como alternativa, você pode anotar a ID do documento (encontrada no URL da página [!UICONTROL Detalhes do documento]) e entrar em contato com o suporte ao cliente do [!DNL Workfront].

_Relatado pela primeira vez em 6 de janeiro de 2023._
