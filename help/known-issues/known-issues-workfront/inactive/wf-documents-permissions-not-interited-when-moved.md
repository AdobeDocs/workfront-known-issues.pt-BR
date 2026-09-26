---
title: 'Documentos: as permissões não são herdadas quando um documento é movido para um novo projeto'
description: 'Quando um usuário move um documento para um projeto diferente, o documento não herda as permissões de compartilhamento do novo projeto. O documento não é compartilhado com os usuários para os quais o projeto é compartilhado. '
feature: Digital Content and Documents
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '182'
ht-degree: 100%
---
# Documentos: as permissões não são herdadas quando um documento é movido para um novo projeto

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

Quando um usuário move um documento para um projeto diferente, o documento não herda as permissões de compartilhamento do novo projeto. O documento não é compartilhado com os usuários para os quais o projeto é compartilhado.

**Solução alternativa:**

1. Navegue até o objeto principal do documento, como um Projeto, Tarefa ou Problema.

1. Remova as permissões herdadas da lista de compartilhamento do objeto principal clicando no “X” ao lado das permissões herdadas e, em seguida, clique em **[!UICONTROL Salvar]**.

1. Adicione novamente as permissões herdadas navegando de volta para a lista de compartilhamento do objeto principal e clicando em **[!UICONTROL Desfazer]** ao lado das permissões herdadas e, em seguida, clique em **[!UICONTROL Salvar]**.

Como alternativa, você pode anotar a ID do documento (encontrada no URL da página [!UICONTROL Detalhes do documento]) e entrar em contato com o suporte ao cliente do [!DNL Workfront].

_Relatado pela primeira vez em 6 de janeiro de 2023._



<!--CHECK ME - 1 VIEW APRIL-JUNE 2025 (June 11 and 27)-->
