---
title: 'Integrações: erro do outlookIdentityToken ao usar o Workfront para Outlook'
description: Quando um usuário usa a integração do Workfront para Outlook, pode ocorrer um erro.
hidefromtoc: true
feature: Workfront Integrations and Apps
source-git-commit: 19d438b3a368b076aa03a89fe6648ec4b225225f
workflow-type: tm+mt
source-wordcount: '127'
ht-degree: 0%

---


# Integrações: erro do outlookIdentityToken ao usar o Workfront para Outlook

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
