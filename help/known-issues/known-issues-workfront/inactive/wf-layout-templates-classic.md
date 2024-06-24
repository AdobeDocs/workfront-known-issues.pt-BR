---
title: '“Modelos de layout: os modelos de layout causam inconsistências nos relatórios”'
description: Os modelos de layout da experiência clássica do Workfront não estão mais disponíveis na interface, mas ainda podem afetar os dados. Isso pode causar inconsistências em campos afetados por modelos de layout (como “Compartilhado com”) em relatórios ou painéis.
hidefromtoc: true
feature: System Setup and Administration
exl-id: 1542291f-4797-477e-83b8-0706ac6801ae
source-git-commit: 875945978c7bdb4a7128ade826b6fbc31da04ae9
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 100%

---

# Modelos de layout: modelos de layout causam inconsistências nos relatórios

<!--Can delete after 9/24/2024-->

>[!NOTE]
>
>Esse problema foi resolvido.

Os modelos de layout da experiência clássica do [!DNL Workfront] não estão mais disponíveis na interface do [!DNL Workfront], mas ainda podem afetar os dados do [!DNL Workfront]. Isso pode causar inconsistências em campos afetados por modelos de layout (como [!UICONTROL “Compartilhado com”]) em relatórios ou painéis.

**Solução alternativa**

Exclua os modelos de layout clássicos usando uma chamada de API. É necessário estar conectado ao Workfront.

>[!NOTE]
>
>Os modelos de layout Global e Sistema não podem ser excluídos.

1. Localize o modelo de layout que deseja excluir usando a seguinte chamada de API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Anote a ID do modelo de layout que deseja excluir.
1. Localize sua ID de sessão usando a seguinte chamada de API:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Nunca compartilhe sua ID de sessão com ninguém.

1. Insira a ID do modelo de layout e a ID de sessão na seguinte chamada de API:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Cole a chamada de API da etapa 4 na barra de URL do navegador e pressione Enter.

   Isso excluirá o modelo de layout.
