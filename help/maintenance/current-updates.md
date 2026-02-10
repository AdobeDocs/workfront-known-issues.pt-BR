---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 50106ee9af1f41283cabe146785f0c792601ccf2
workflow-type: tm+mt
source-wordcount: '859'
ht-degree: 53%

---

# Atualizações de manutenção do [!DNL Workfront]

>[!NOTE]
>
>Para obter informações sobre interrupções de manutenção para todos os produtos Adobe, incluindo o Workfront, consulte a [página Status da Adobe](https://status.adobe.com/pt/).

Esta página descreve os problemas corrigidos nas atualizações semanais do Workfront.

Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2026, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

As seguintes atualizações de manutenção foram efetuadas em 2026.

## Atualizações em fevereiro de 2026

+++**Semana de atualização de manutenção de 8 a 14 de fevereiro de 2026**

### Atualização de manutenção semana de 8 a 14 de fevereiro de 2026

#### Relatórios

**A consulta do Data Lake não retorna os resultados esperados**

Quando o data lake é consultado, ele não retorna todos os resultados esperados.

#### Solicitações

**Problemas com rascunhos na nova experiência de solicitação**

Os seguintes problemas foram relatados em relação aos rascunhos na nova experiência de solicitação:

* As solicitações criadas como rascunho e enviadas em seguida mostram somente a primeira letra do assunto na lista “Solicitações”.
* Os rascunhos descartados não são removidos da lista de solicitações e resultam no erro: “Falha ao recuperar o rascunho”.

+++

+++**Semana de atualização de manutenção de 1 a 7 de fevereiro de 2026**

### Atualização de manutenção semana de 1 a 7 de fevereiro de 2026

#### Documentos

**O painel Resumo está em branco**

Quando um usuário visualiza uma lista Documentos e clica em um documento, o painel Resumo é aberto, mas permanece em branco. O usuário não pode fechar o Painel de resumo.

Se o usuário recarregar a página, o painel Resumo poderá ser preenchido conforme esperado. No entanto, se o usuário clicar em um documento diferente, o painel de resumo desse documento ficará em branco.

#### Solicitações

**&quot;Nenhum assunto&quot; é exibido na lista de solicitações**

Quando um usuário visualiza a lista de solicitações na nova experiência de solicitação, algumas solicitações exibem &quot;Nenhum assunto&quot; na coluna Assunto.

Se o usuário abrir uma dessas solicitações, verá que a solicitação tem um assunto.

**Erro &quot;Você não tem acesso suficiente&quot; ao copiar solicitações**

Quando um usuário tenta copiar uma solicitação por meio da página de solicitação, a solicitação não é copiada e o usuário vê o seguinte erro:

&quot;Você não tem acesso suficiente para editar esse problema.&quot;

**Erro &quot;Você deve ser um administrador do sistema&quot; ao copiar solicitações**

Quando um usuário copia uma solicitação e tenta salvar, a solicitação não é salva e o usuário vê a seguinte mensagem:

&quot;Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado.&quot;

#### Usuários

**Os usuários não foram provisionados corretamente na Adobe Admin Console**

Se um usuário já existir em um Adobe Admin Console e for provisionado automaticamente em um Console que inclua o Workfront, ele não será provisionado corretamente para o novo Console.

#### Balanceador de carga de trabalho

**As horas por usuário não foram calculadas corretamente**

Quando um usuário visualiza as horas de um usuário no Balanceador de carga de trabalho, essas horas podem ser calculadas incorretamente. Por exemplo, a exibição semana pode exibir um cálculo de horas, mas a exibição 4 semanas exibe um número diferente de horas para essa semana.

+++

## Atualizações em janeiro de 2026

+++**Semana de atualização de manutenção de 25 a 31 de janeiro de 2026**

### Atualização de manutenção da semana de 25 a 31 de janeiro de 2026

#### Aprovações

**O widget “Minhas aprovações” mostra aprovações concluídas**

Quando um usuário visualiza o widget “Minhas aprovações” na página inicial, o widget inclui provas que já foram aprovadas.

+++

+++**Semana de atualização de manutenção de 18 a 24 de janeiro de 2026**

### Semana de atualização de manutenção de 18 a 24 de janeiro de 2026

#### Solicitações

**Problemas com rascunhos na nova experiência de solicitação**

Os seguintes problemas foram relatados em relação aos rascunhos na nova experiência de solicitação:

* As solicitações criadas como rascunho e enviadas em seguida mostram somente a primeira letra do assunto na lista “Solicitações”.
* Rascunhos descartados não são removidos da lista de solicitações,

#### Cronogramas

**Não é possível ver as exceções dos anos anteriores**

Quando um usuário exibe o calendário de exceção e tenta exibir anos anteriores, ele não pode exibir os anos anteriores.

+++

+++**Semana de atualização de manutenção de 11 a 17 de janeiro de 2026**

### Semana de atualização de manutenção de 11 a 17 de janeiro de 2026

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do Workfront enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++**Atualizações de manutenção do Workfront Fusion na semana de 4 a 10 de janeiro de 2026**

### Atualizações de manutenção na semana de 4 a 10 de janeiro de 2026

**Erro de cabeçalho ausente em módulos do AWS**

Os módulos do AWS estão falhando com o seguinte erro:

“Cabeçalho obrigatório ausente para esta solicitação”

+++

+++**Atualizações de manutenção na semana de 4 a 10 de janeiro de 2026**

### Atualizações de manutenção na semana de 4 a 10 de janeiro de 2026

#### Aprovações

**O widget “Minhas aprovações” mostra aprovações concluídas**

Quando um usuário visualiza o widget “Minhas aprovações” na página inicial, o widget inclui provas que já foram aprovadas.

#### Provas

**As alterações no status da prova atrasam**

Quando uma decisão sobre uma prova é tomada, essa decisão não é exibida na área de documentos do projeto por até 24 horas. Isso pode causar confusão, pois o status ainda é exibido como “Pendente” ou outro status desatualizado, mesmo que uma decisão já tenha sido tomada.

#### Solicitações

**As filas de solicitações aparecem várias vezes**

Quando um usuário começa a criar uma solicitação e seleciona uma fila de solicitações, a mesma fila de solicitações aparece várias vezes na lista suspensa.


+++


## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [Arquivo de atualizações de manutenção do [!DNL Workfront] — 2025](2025-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] — 2024](2024-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2023](2023-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2022](2022-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2021](2021-updates.md)
