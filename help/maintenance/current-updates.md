---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: b74a577bc652f822b4ff9d835952f9b8145ae6dc
workflow-type: tm+mt
source-wordcount: '530'
ht-degree: 58%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2024.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em janeiro de 2024

+++**Atualização de manutenção em sábado, 12 de janeiro de 2024**

### Atualização de manutenção em 12 de janeiro de 2024

#### Quadros

**Não é possível anexar um documento a um cartão**

Quando um usuário tenta anexar um documento a um cartão conectado, é possível selecionar o documento a ser anexado, mas ele não aparece na área de documento do cartão e não é anexado ao objeto ao qual o cartão está conectado.

Isso foi relatado nos problemas de cartões conectados.

**O cartão é exibido em vários sprints**

Quando uma pessoa visualiza um sprint em Quadros, cartões que estão em sprints diferentes são exibidos no quadro. Esse problema é intermitente.

**O cartão não fecha ao usar a visualização Quadros em um projeto**

Quando um usuário visualiza a exibição Quadros em uma lista de tarefas em um projeto e cria um cartão, o cartão não é fechado ou salvo. Isso impede que o usuário retorne ao projeto.

Para fechar o cartão, o usuário deve editar o URL para remover o &quot;quadro&quot; e qualquer item à direita do &quot;quadro&quot;.

**Os cartões persistem ao alterar a iteração**

Quando um usuário visualiza uma iteração em um quadro e, em seguida, altera a iteração, os cartões exibidos para a nova iteração são os cartões de uma iteração que o usuário estava visualizando anteriormente.

**Erro no [!UICONTROL Comentários] seção de cartões**

Quando uma pessoa visualiza um cartão e rola para a seção [!UICONTROL Comentários], os comentários não são exibidos e ela vê o seguinte erro:

“[!UICONTROL Algo não deu certo. Tente novamente mais tarde.]&quot;

**Problemas ao visualizar o status de subtarefas**

Os seguintes problemas foram relatados em relação à exibição do status de subtarefas em um cartão nos Quadros:

* O status é mostrado como “Selecionar status” mesmo quando a tarefa já possui um status. Esse status pode ser visto ao visualizar a tarefa diretamente.
* Se a pessoa tentar selecionar um status, a tela ficará em branco e precisará ser atualizada.

**&quot;[!UICONTROL Você não tem acesso]&quot;ao visualizar comentários em um cartão**

Quando uma pessoa tenta exibir comentários em um cartão que não está conectado a um objeto do [!DNL Workfront], a seguinte mensagem é exibida:

“[!UICONTROL Você não tem acesso para exibir comentários neste objeto]”

Isso pode ocorrer mesmo quando a pessoa podia ver comentários no cartão anteriormente.

+++

+++**Atualização de manutenção em quinta-feira, 11 de janeiro de 2023**

### Atualização de manutenção em 11 de janeiro de 2023

#### Quadros

**Placas concluídas não carregam corretamente em placas dinâmicas**

Anteriormente, a única maneira de incluir o trabalho concluído em uma placa dinâmica era carregar as placas como cartões arquivados. Caso contrário, os cartões concluídos não eram carregados na placa. Isso causava problemas ao localizar cartões.

Agora, ao criar um quadro dinâmico, os cartões concluídos são carregados por padrão como cartões arquivados, mas você pode selecionar Não arquivar cartões concluídos para carregar todos os cartões concluídos no quadro como cartões visíveis na coluna Concluído.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2023](2023-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2022](2022-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2021](2021-updates.md)
