---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: ee15f19ffd6010f637582fa484721596a25f0653
workflow-type: tm+mt
source-wordcount: '1447'
ht-degree: 86%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2024.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em fevereiro de 2024

+++**(Planejado) Atualização de manutenção em sexta-feira, 8 de fevereiro de 2024**

### (Planejado) Atualização de manutenção em 8 de fevereiro de 2024

#### Quadros

**Não é possível mover um cartão em uma coluna usando [!UICONTROL Mover] opções**

Quando um usuário tenta mover um cartão em uma coluna usando o &quot;[!UICONTROL Parte superior da coluna]&quot; ou &quot;[!UICONTROL Parte inferior da coluna]&quot; no menu de três pontos, o cartão não se move.

**Os cartões persistem ao alterar a iteração**

Quando uma pessoa visualiza uma iteração em um quadro e, em seguida, altera para outra iteração, os cartões exibidos na nova iteração permanecem sendo os mesmos cartões da anterior.

#### Relatórios

**A coluna &quot;Nenhum valor&quot; não exibe resultados**

Quando um relatório de gráfico tem um &quot;[!DNL No value]&quot;, a coluna não mostra nenhum dado, mesmo que os dados devam estar presentes.

+++

+++**Atualização de manutenção em sexta-feira, 1 de fevereiro de 2024**

### Atualização de manutenção em 1 de fevereiro de 2024

#### Logon

**Os usuários que usam SSO não são redirecionados para o local original ao fazer logon**

Quando um usuário está em uma página no [!DNL Workfront] e efetuar login com SSO, quando o login estiver concluído, eles serão direcionados para [!UICONTROL Início] em vez da página em que estavam antes de fazer logon.

#### Modelos

**Erro ao copiar modelos**

Quando alguém tenta copiar um modelo novo ou já existente, ele não é copiado e o seguinte erro é exibido:

“[!UICONTROL ID não pode ser nulo]”

+++

## Atualizações em janeiro de 2024

+++**Atualização de manutenção (hot fix) em quarta-feira, 30 de janeiro de 2024**

### Atualização de manutenção (hotfix) em 30 de janeiro de 2024

#### Relatórios

**O campo API externa não mostra todos os valores disponíveis em listas e relatórios**

Anteriormente, os usuários podiam ver o valor selecionado (e editar o valor) de um campo de pesquisa externo em listas e relatórios, mas não visualizavam a lista suspensa com as opções provenientes da API.

Agora, quando um campo personalizado de pesquisa externa é usado em uma lista ou relatório, a lista suspensa com todas as opções da API externa fica disponível.

+++

+++**Atualização de manutenção em sexta-feira, 25 de janeiro de 2024**

### Atualização de manutenção em sexta-feira, 25 de janeiro de 2024

#### Quadros

**Os cartões não são movidos para a coluna apropriada quando o status é alterado**

Quando o status de um objeto vinculado a um cartão conectado é alterado diretamente no objeto, o cartão não é movido para a coluna apropriada. Se o status do objeto é alterado no cartão ou se o cartão é arrastado para a nova coluna, o cartão se comporta conforme esperado.

#### Notificações

**Marcar notificações como vistas não persiste**

Quando uma pessoa marca as notificações como vistas e navega para uma página diferente no [!DNL Workfront], o ícone de notificações ainda mostra o número de notificações não lidas que existiam antes de ela marcá-las como vistas, e as notificações ainda são listadas quando se clica no ícone. Isso continua mesmo quando a pessoa as marca como vistas e navega para outra página ou de volta para a página original.

#### Atualizações

**Problemas com a marcação na experiência de comentários herdada**

Quando uma pessoa é marcada em um comentário na experiência de comentários herdada, os seguintes problemas ocorrem:

* Somente a primeira parte do nome do usuário está presente no comentário
* O nome do usuário não está marcado com um símbolo @
* O nome do usuário não está em azul
* O nome do usuário não é um link para o perfil dele

O usuário recebe uma notificação por email sobre a tag, conforme esperado.

+++

+++**Atualização de manutenção em sexta-feira, 18 de janeiro de 2024**

### Atualização de manutenção em sexta-feira, 18 de janeiro de 2024

#### Quadros

**Não é possível anexar um documento a um cartão**

Quando um usuário tenta anexar um documento a um cartão conectado, é possível selecionar o documento a ser anexado, mas ele não aparece na área de documento do cartão e não é anexado ao objeto ao qual o cartão está conectado.

Isso foi relatado nos problemas de cartões conectados.

**O cartão aparece em vários sprints**

Quando uma pessoa visualiza um sprint em Quadros, cartões que estão em sprints diferentes são exibidos no quadro. Esse problema é intermitente.

**O cartão não fecha ao usar a visualização de quadros em um projeto**

Quando uma pessoa visualiza a exibição de quadros em uma lista de tarefas de um projeto e cria um cartão, o cartão não é fechado nem salvo. Isso impede que o usuário retorne ao projeto.

Para fechar o cartão, o usuário precisa editar o URL para remover o “quadro” e qualquer item à direita do “quadro”.

**Os cartões persistem ao alterar a iteração**

Quando uma pessoa visualiza uma iteração em um quadro e, em seguida, altera para outra iteração, os cartões exibidos na nova iteração permanecem sendo os mesmos cartões da anterior.

**Erro na seção [!UICONTROL Comentários] dos cartões**

Quando uma pessoa visualiza um cartão e rola para a seção [!UICONTROL Comentários], os comentários não são exibidos e ela vê o seguinte erro:

“[!UICONTROL Algo não deu certo. Tente novamente mais tarde.]&quot;

**Problemas ao visualizar o status de subtarefas**

Os seguintes problemas foram relatados em relação à exibição do status de subtarefas em um cartão nos Quadros:

* O status é mostrado como “Selecionar status” mesmo quando a tarefa já possui um status. Esse status pode ser visto ao visualizar a tarefa diretamente.
* Se a pessoa tentar selecionar um status, a tela ficará em branco e precisará ser atualizada.

**“[!UICONTROL Você não tem acesso]” ao visualizar comentários em um cartão**

Quando uma pessoa tenta exibir comentários em um cartão que não está conectado a um objeto do [!DNL Workfront], a seguinte mensagem é exibida:

“[!UICONTROL Você não tem acesso para exibir comentários neste objeto]”

Isso pode ocorrer mesmo quando a pessoa podia ver comentários no cartão anteriormente.

#### Formulários personalizados no meu grupo

**Não é possível adicionar ou remover em massa formulários personalizados em tarefas de modelo**

Se uma pessoa tentar adicionar ou remover formulários personalizados em massa em uma tarefa de modelo, eles não serão adicionados ou removidos e o seguinte erro é exibido:

[!UICONTROL Vamos tentar novamente. Parâmetro inválido: valor da ID do modelo &quot;XXXXXXXXXXXXXXXX&quot;]

Se a pessoa localizar o modelo com a GUID especificada e tentar adicionar ou remover formulários personalizados no restante das tarefas do modelo, o erro ocorrerá novamente usando outra ID de modelo.

Formulários personalizados podem ser adicionados ou removidos em uma única tarefa de modelo. Esse erro se aplica somente à adição ou remoção em massa.

#### Portfólios

**A terminologia personalizada não se aplica à página do grupo**

Quando uma pessoa define a terminologia personalizada no nível do portfólio, a terminologia não se aplica à página no nível do grupo.

#### Configuração

**Não é possível ocultar status opcionais**

Quando uma pessoa tenta ocultar status opcionais em um nível de sistema e de grupo, o status não é oculto. Se a pessoa visualizar o status, a opção para ocultar o status não estará habilitada, mesmo que ela a tenha habilitado e salvo as alterações.

**Status de problemas padrão ausentes em alguns tipos de problemas na configuração**

Quando uma pessoa visualiza os status de problemas na Configuração, ela verá que os status padrão para problemas (Novo, Em andamento e Concluído) estão ausentes em alguns tipos de problemas. Os status padrão não têm a opção para alterar o tipo de problema, portanto, a pessoa não pode reconfigurar os status para serem exibidos para os tipos de problema afetados.

#### Equipes

**Problemas ao definir status de equipe para o botão [!UICONTROL Concluído] **

Os seguintes problemas foram relatados em relação aos status do botão [!UICONTROL Concluído] ao editar ou criar uma equipe:

* Alguns status podem estar faltando na área do botão Concluído da janela [!UICONTROL Nova equipe] ou na área [!UICONTROL Configurações da equipe] de uma equipe já existente.
* Se a pessoa tentar salvar a equipe, poderá ver o erro “Você precisa selecionar pelo menos um status em cada categoria.”

#### Modelos

**Erro ao anexar modelo ao projeto**

Quando um usuário tenta anexar um modelo a um projeto, o seguinte erro é exibido:

“Ops! Um erro inesperado aconteceu. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.”

Isso ocorre quando o usuário não tem permissão de Visualização para um formulário personalizado anexado ao modelo.

#### Atualizações

**Os comentários não são transferidos entre a experiência antiga e a nova**

Um comentário feito na experiência de comentários herdada pode não estar visível na nova experiência de comentários. O inverso também pode ocorrer.

+++

+++**Atualização de manutenção em sexta-feira, 11 de janeiro de 2024**

### Atualização de manutenção em sexta-feira, 11 de janeiro de 2024

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
