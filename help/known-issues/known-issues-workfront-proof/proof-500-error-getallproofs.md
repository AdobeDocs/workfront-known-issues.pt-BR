---
title: 'Workfront Proof: erro 500 ao acessar o Workfront Proof por meio da API ou do Workfront Fusion'
description: 'Quando um usuário acessa a ação getAllProofs da API de prova, o servidor do Workfront Proof retorna a mensagem: 500 Erro interno do servidor'
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 69%
---
# [!DNL Workfront Proof]: erro 500 ao acessar o [!DNL Workfront Proof] por meio da API ou do [!DNL Workfront Fusion]

>[!NOTE]
>
>A equipe do produto está avaliando a resolução do problema, que pode exigir melhorias do produto. As melhorias do produto são comunicadas nos Anúncios do produto e não nas Atualizações de manutenção.

<!--This article is on Proof and Fusion TOCs-->

Quando um usuário acessa a ação [!UICONTROL `getAllProofs`] da API do [!DNL Workfront Proof], o servidor retorna a seguinte mensagem:

[!UICONTROL Erro interno 500 do servidor]

Visto que o [!DNL Workfront Fusion] usa a API do [!DNL Workfront Proof] para módulos do [!DNL Workfront Proof], esse erro pode ser retornado em um módulo, interrompendo um cenário.

_Reportado pela primeira vez em sábado, 28 de abril de 2023._
