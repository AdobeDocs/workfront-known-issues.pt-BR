---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 67155ccf8996661fb9429c6174a7f5d0cf4a6d8a
workflow-type: tm+mt
source-wordcount: '1085'
ht-degree: 80%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2024.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em janeiro de 2024

+++**Atualização de manutenção em sexta-feira, 25 de janeiro de 2024**

### Atualização de manutenção em sexta-feira, 25 de janeiro de 2024

#### Quadros

**Cartões não são movidos para a coluna apropriada quando o status é alterado**

Quando o status de um objeto vinculado a um cartão conectado é alterado diretamente no objeto, o cartão não é movido para a coluna apropriada. Se o status do objeto é alterado no cartão ou se o cartão é arrastado para a nova coluna, o cartão se comporta conforme esperado.

#### Notificações

**A marcação de notificações como vistas não persiste**

Quando um usuário marca suas notificações como vistas e, em seguida, navega para uma página diferente no [!DNL Workfront], o ícone notificações ainda mostra o número de notificações não lidas existentes antes de o usuário as marcar como visualizadas e as notificações ainda serão listadas quando o usuário clicar no ícone. Isso continua se o usuário os marcar como vistos e navegar para outra página ou de volta para a página original.

+++

+++**Atualização de manutenção em sexta-feira, 18 de janeiro de 2024**

### Atualização de manutenção em sexta-feira, 18 de janeiro de 2024

#### Quadros

**Não é possível anexar um documento a um cartão**

Quando um usuário tenta anexar um documento a um cartão conectado, é possível selecionar o documento a ser anexado, mas ele não aparece na área de documento do cartão e não é anexado ao objeto ao qual o cartão está conectado.

Isso foi relatado nos problemas de cartões conectados.

**O cartão é exibido em vários sprints**

Quando uma pessoa visualiza um sprint em Quadros, cartões que estão em sprints diferentes são exibidos no quadro. Esse problema é intermitente.

**O cartão não fecha ao usar a visualização Quadros em um projeto**

Quando uma pessoa visualiza a exibição de quadros em uma lista de tarefas de um projeto e cria um cartão, o cartão não é fechado nem salvo. Isso impede que o usuário retorne ao projeto.

Para fechar o cartão, o usuário precisa editar o URL para remover o “quadro” e qualquer item à direita do “quadro”.

**Os cartões persistem ao alterar a iteração**

Quando uma pessoa visualiza uma iteração em um quadro e, em seguida, altera para outra iteração, os cartões exibidos na nova iteração permanecem sendo os mesmos cartões da anterior.

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

#### Formulários personalizados no meu grupo

**Não é possível adicionar ou remover formulários personalizados em massa em tarefas de modelo**

Se uma pessoa tentar adicionar ou remover formulários personalizados em massa em uma tarefa de modelo, eles não serão adicionados ou removidos e o seguinte erro é exibido:

[!UICONTROL Vamos tentar novamente. Parâmetro inválido: valor da ID do modelo &quot;XXXXXXXXXXXXXXXX&quot;]

Se a pessoa localizar o modelo com a GUID especificada e tentar adicionar ou remover formulários personalizados no restante das tarefas do modelo, o erro ocorrerá novamente usando outra ID de modelo.

Formulários personalizados podem ser adicionados ou removidos em uma única tarefa de modelo. Esse erro se aplica somente à adição ou remoção em massa.

#### Portfólios

**A terminologia personalizada não se aplica à página do grupo**

Quando um usuário define terminologia personalizada no nível do Portfolio, a terminologia não se aplica à página de nível do grupo.

#### Configuração

**Não é possível ocultar status opcionais**

Quando uma pessoa tenta ocultar status opcionais em um nível de sistema e de grupo, o status não é oculto. Se a pessoa visualizar o status, a opção para ocultar o status não estará habilitada, mesmo que ela a tenha habilitado e salvo as alterações.

**Status de problema padrão ausentes em alguns tipos de problema na Configuração**

Quando uma pessoa visualiza os status de problemas na Configuração, ela verá que os status padrão para problemas (Novo, Em andamento e Concluído) estão ausentes em alguns tipos de problemas. Os status padrão não têm a opção para alterar o tipo de problema, portanto, a pessoa não pode reconfigurar os status para serem exibidos para os tipos de problema afetados.

#### Equipes

**Problemas com a configuração dos status da equipe para o [!UICONTROL Concluído] botão**

Os seguintes problemas foram relatados em relação aos status do botão [!UICONTROL Concluído] ao editar ou criar uma equipe:

* Alguns status podem estar faltando na área do botão Concluído da janela [!UICONTROL Nova equipe] ou na área [!UICONTROL Configurações da equipe] de uma equipe já existente.
* Se a pessoa tentar salvar a equipe, poderá ver o erro “Você precisa selecionar pelo menos um status em cada categoria.”

#### Modelos

**Erro ao anexar modelo ao projeto**

Quando um usuário tenta anexar um modelo a um projeto, o seguinte erro é exibido:

“Ops! Um erro inesperado aconteceu. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.”

Isso ocorre quando o usuário não tem permissão de Visualização para um formulário personalizado anexado ao modelo.

#### Atualizações

**Os comentários não são transferidos entre a experiência antiga e a nova experiência**

Um comentário feito na experiência de comentários herdada pode não estar visível na nova experiência de comentários. O inverso também pode ocorrer.

+++

+++**Atualização de manutenção em quinta-feira, 11 de janeiro de 2023**

### Atualização de manutenção em 11 de janeiro de 2023

#### Quadros

**Cartões concluídos não são carregados corretamente em quadros dinâmicos**

Anteriormente, a única maneira de incluir um trabalho concluído em um quadro dinâmico era carregar os cartões como cartões arquivados. Caso contrário, os cartões concluídos não seriam carregados no quadro. Isso causou problemas na localização dos cartões.

Agora, ao criar um quadro dinâmico, os cartões concluídos são carregados por padrão como cartões arquivados, mas você pode selecionar Não arquivar cartões concluídos para carregar todos os cartões concluídos no quadro como cartões visíveis na coluna Concluído.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2023](2023-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2022](2022-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2021](2021-updates.md)
