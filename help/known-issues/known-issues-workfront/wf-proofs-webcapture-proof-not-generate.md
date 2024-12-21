---
title: 'Provas: as provas do Webcapture não geram'
description: Quando um usuário tenta criar uma prova de captura da Web, a prova não é gerada com sucesso.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: tm+mt
source-wordcount: '98'
ht-degree: 16%

---

# Provas: as provas do Webcapture não geram

>[!NOTE]
>
>Este problema foi encerrado porque o botão está funcionando conforme projetado. Consulte a solução alternativa abaixo.

Quando um usuário tenta criar uma prova de captura da Web, a prova não é gerada com sucesso.

**Solução alternativa**

Esse problema é causado por longos tempos de geração de prova para determinados arquivos PDF. Para aumentar o tempo limite da geração do padrão de 30 segundos, edite a propriedade abaixo em Configurações de processamento no nível da conta em Administrador de prova:

`WebCaptureNavigationTimeout -> 120`

_Relatado pela primeira vez em sexta-feira, 3 de outubro de 2024._
