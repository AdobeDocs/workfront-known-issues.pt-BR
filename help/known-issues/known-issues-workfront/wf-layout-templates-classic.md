---
title: '“Modelos de layout: modelos de layout causam inconsistências nos relatórios”'
description: “Os modelos de layout da Experiência clássica do Workfront não estão mais disponíveis em sua interface, mas ainda podem afetar seus dados. Isso pode causar inconsistências em campos afetados por modelos de layout (como “Compartilhado com”) em relatórios ou painéis.”
hidefromtoc: true
feature: System Setup and Administration
source-git-commit: 045e2bd200aa2fffaf2e763a73eb8729517be197
workflow-type: ht
source-wordcount: '195'
ht-degree: 100%

---


# Modelos de layout: modelos de layout causam inconsistências nos relatórios

Os modelos de layout da Experiência clássica do Workfront não estão mais disponíveis em sua interface, mas ainda podem afetar seus dados. Isso pode causar inconsistências em campos afetados por modelos de layout (como “Compartilhado com”) em relatórios ou painéis.

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

