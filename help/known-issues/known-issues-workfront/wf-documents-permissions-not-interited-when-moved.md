---
title: '“Documentos: as permissões não são herdadas quando um documento é movido para um novo projeto”'
description: “Quando um usuário move um documento para um projeto diferente, o documento não herda as permissões de compartilhamento do novo projeto. O documento não é compartilhado com os usuários para os quais o projeto é compartilhado. “
hidefromtoc: true
source-git-commit: 05592905aecebd7c6f99f4ffa7513630baae5692
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 57%

---


# Documentos: as permissões não são herdadas quando um documento é movido para um novo projeto

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

Quando um usuário move um documento para um projeto diferente, o documento não herda as permissões de compartilhamento do novo projeto. O documento não é compartilhado com os usuários para os quais o projeto é compartilhado.

**Solução alternativa:**

1. Navegue até o objeto pai do documento, como Projeto, Tarefa ou Problema.

1. Remova as permissões herdadas da lista de compartilhamento do objeto pai clicando no &quot;x&quot; ao lado das permissões herdadas e clique em **[!UICONTROL Salvar]**.

1. Adicionar novamente as permissões herdadas navegando de volta para a lista de compartilhamento do objeto pai e clicando em **[!UICONTROL Desfazer]** ao lado de permissões herdadas, clique em **[!UICONTROL Salvar]**.

Como alternativa, você pode anotar a ID do documento (encontrada no URL da página Detalhes do documento ) e entrar em contato com o suporte ao cliente da Workfront.

_Relatado pela primeira vez em 6 de janeiro de 2023._

