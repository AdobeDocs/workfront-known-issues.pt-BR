---
title: 'Provas: as provas de captura da web não são geradas'
description: Quando um usuário tenta criar uma prova de captura da web, ela não é gerada com sucesso.
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
source-git-commit: 7b66d253831c83bf6166cc5be39e18be704503a6
workflow-type: ht
source-wordcount: '98'
ht-degree: 100%

---

# Provas: as provas de captura da web não são geradas

>[!NOTE]
>
>Esse problema foi encerrado porque o funcionamento está correto conforme projetado. Confira a solução abaixo.

Quando um usuário tenta criar uma prova de captura da web, ela não é gerada com sucesso.

**Solução**

Esse problema é causado por longos tempos de geração de prova para determinados arquivos PDF. Para aumentar o tempo-limite de geração do padrão de 30 segundos, edite a propriedade abaixo em “Configurações de processamento” no nível da conta em “Administrador de provas”:

`WebCaptureNavigationTimeout -> 120`

_Relatado pela primeira vez em 3 de outubro de 2024._
