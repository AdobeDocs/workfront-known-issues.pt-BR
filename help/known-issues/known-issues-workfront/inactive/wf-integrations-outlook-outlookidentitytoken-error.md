---
title: 'Integrações: erro do outlookIdentityToken ao usar o Workfront para Outlook'
description: Quando um usuário usa a integração do Workfront para Outlook, pode ocorrer um erro.
hidefromtoc: true
feature: Workfront Integrations and Apps
exl-id: a5abe90c-4583-467e-8131-60bead300673
source-git-commit: 87c56abf4a5020632877263329f1455bbf4cc7f3
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 0%

---

# Integrações: erro do outlookIdentityToken ao usar o Workfront para Outlook

>[!NOTE]
>
>A integração do Workfront para Outlook não está mais disponível. Este artigo será removido em breve.

Quando um usuário usa a integração do Workfront para Outlook, o seguinte erro pode aparecer:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Solução alternativa**


Para resolver esse erro, você deve ativar os tokens herdados do Microsoft 365 para para sua organização. Como isso deve ser feito no Microsoft 365, a Workfront não pode habilitar esses tokens para sua organização.

Para obter instruções sobre como habilitar tokens herdados do Microsoft 365, consulte [Ativar ou desativar tokens herdados do Exchange Online](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) na documentação do Microsoft.

Para obter mais informações sobre tokens herdados, consulte [Posso ativar novamente os tokens herdados do Exchange Online?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) na documentação do Microsoft.


_Reportado pela primeira vez em 3 de março de 2025, 2024._
