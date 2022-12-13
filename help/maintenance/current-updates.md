---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 707324aea99a9f77e7664afa555a4b7b9d6e4cef
workflow-type: tm+mt
source-wordcount: '16388'
ht-degree: 97%

---

# Atualizações de manutenção do [!DNL Workfront] 

As seguintes atualizações de manutenção foram efetuadas em 2022.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

Para obter atualizações de manutenção anteriores a 2022, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em dezembro de 2022

+++**Atualização de manutenção em 15 de dezembro de 2022**

**&quot;[!UICONTROL Boias]&quot;erro ao criar um projeto a partir de um modelo**

*Projetos*

Quando um usuário tenta criar um projeto a partir de um modelo, o projeto não é criado e o usuário vê o seguinte erro:

“[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

**O gráfico de combinação exibe os mesmos dados duas vezes**

*Relatórios*

Quando um usuário visualiza um gráfico de combinação, o gráfico exibe um conjunto de valores duas vezes em vez de comparar dois conjuntos de valores. Os conjuntos de valores corretos podem ser encontrados nos detalhes do relatório.

**Usuários desativados disponíveis ao selecionar aprovador de folha de horas**

*Folhas de horas*

Quando um usuário cria uma folha de horas e tenta atribuir um aprovador, a lista suspensa inclui usuários desativados. Se um usuário desativado for selecionado, a folha de horas não será salva e o usuário verá a seguinte mensagem:

“[!UICONTROL Erro. Desculpe, somente usuários com licença de Plano podem aprovar ou rejeitar folhas de horas. Entre em contato com o administrador do sistema.]”

Como o usuário desativado não pode ser atribuído, o usuário deve selecionar um usuário ativado. Portanto, a folha de horas funciona conforme o esperado, mas os usuários desativados na lista podem causar confusão ou inconveniência para o usuário.

+++

+++**Atualização de manutenção em 8 de dezembro de 2022**

**O status do projeto não segue as preferências do projeto do Grupo**

*Projetos*

Quando um usuário cria um projeto a partir de um modelo, o novo projeto não assume o status definido nas preferências do projeto do Grupo. Se um projeto for criado sem um modelo, o status refletirá as preferências do projeto do Grupo, conforme esperado.

**Não é possível adicionar subtarefa**

*Tarefas*

Quando um usuário tenta adicionar uma subtarefa usando o[!UICONTROL +Novo]&quot;, nenhuma opção é exibida no [!UICONTROL Nova tarefa] e o usuário vê a seguinte mensagem:

&quot;[!UICONTROL Não é possível ler propriedades de indefinido (lendo &#39;validações&#39;)]&quot;

**Erros ao fechar ou salvar folhas de ponto**

*Folhas de horas*

Quando um usuário tenta adicionar tempo ou fechar uma folha de ponto, ela não é salva e o usuário vê os seguintes erros:

* Erro de SQL.
* Suas alterações recentes não foram salvas. Atualize a página para visualizar as últimas alterações salvas.

+++

+++**Atualização de manutenção (hotfix) em 1 de dezembro de 2022**

**Erros de edição embutidos pelo usuário não causam mensagens de erro**

*Listas*

Quando um usuário está editando um objeto em linha e faz um erro que deveria criar uma mensagem de erro, nenhuma mensagem de erro é exibida. O erro em si não é salvo no Workfront, portanto, os dados não são afetados, mas a falta de uma mensagem de erro pode causar confusão.

Esse problema foi relatado para as seguintes situações:

* Predecessores: um loop predecessor é criado, como atribuir uma tarefa a si mesmo
* Datas: uma data impossível é definida, como uma Data de conclusão anterior à Data de início ou que esteja além da Data de conclusão do projeto

**Opção &quot;Mover para&quot; não disponível em relatórios de problemas**

*Relatórios*

Quando um usuário visualiza um relatório de problema e tenta mover um problema, a opção Mover para não fica disponível no menu Mais (três pontos).


**Não é possível fechar o cartão de usuário no fluxo de atualização**

*Atualizações*

Quando um usuário está visualizando atualizações e passa o mouse sobre um nome, um cartão com detalhes sobre o usuário é aberto e não é fechado automaticamente. A página não responde até que o cartão seja fechado manualmente clicando no X no canto superior direito.


+++

+++**Atualização de manutenção em 1 de dezembro de 2022**

**a tarefa tem uma ordem de backlog Kanban de 0**

*Agile*

Quando um usuário exibe o backlog de uma equipe Kanban, uma ou mais tarefas mostram uma ordem de backlog de 0.

Mensagem **“[!UICONTROL Expressão personalizada inválida]” ao fazer referência a “[!UICONTROL proprietário]” em um campo calculado**

*Formulários personalizados*

Quando um usuário está adicionando um campo calculado a um formulário personalizado em nível de problema e tenta adicionar qualquer referência a um “[!UICONTROL proprietário]” (como `ownerID`), o campo não é salvo e o usuário visualiza a seguinte mensagem:

“[!UICONTROL Esta expressão de cliente é inválida, tente novamente.]”

Isso ocorre mesmo quando a expressão é válida.

**Não é possível acessar elementos da integração do [!DNL Workfront for Jira]**

*Integrações*

Os seguintes elementos não podem ser acessados a integração do [!DNL Workfront for Jira] com o [!DNL Jira Cloud]:

* A página [!UICONTROL Configuração]
* O botão “[!UICONTROL Abrir Workfront]” em um problema do [!DNL Jira]

**A adição de mensagem personalizada causa um problema no visualizador de prova**

*Provas*

Quando um usuário está compartilhando uma prova e tenta adicionar uma mensagem personalizada, ocorre o seguinte:

* O visualizador de prova amplia a prova.
* As áreas na navegação à esquerda não são mais responsivas.

**Usuários desativados disponíveis ao selecionar aprovador de folha de horas**

*Folhas de horas*

Quando um usuário cria uma folha de horas e tenta atribuir um aprovador, a lista suspensa inclui usuários desativados. Se um usuário desativado for selecionado, a folha de horas não será salva e o usuário verá a seguinte mensagem:

“[!UICONTROL Erro. Desculpe, somente usuários com licença de Plano podem aprovar ou rejeitar folhas de horas. Entre em contato com o administrador do sistema.]”

Como o usuário desativado não pode ser atribuído, o usuário deve selecionar um usuário ativado. Portanto, a folha de horas funciona conforme o esperado, mas os usuários desativados na lista podem causar confusão ou inconveniência para o usuário.

**A folha de horas não é gerada**

*Folhas de horas*

As folhas de horas não são geradas apesar das configurações de perfil da folha de horas. Como a folha de horas nunca é gerada, ela não está disponível para o usuário inserir horas e não está visível em listas.

+++

## Atualizações em novembro de 2022

+++**Atualização de manutenção em 17 de novembro de 2022**

**Os documentos são colocados na [!UICONTROL Lixeira] se não estiverem selecionados ao mover uma tarefa ou um problema**

*Documentos*

Agora, ao desmarcar a opção [!UICONTROL Documentos] no processo de mover uma tarefa ou um problema, os documentos anexados à tarefa ou o problema serão colocados na [!UICONTROL Lixeira] por 30 dias. Um administrador pode restaurá-los, se necessário. O usuário que desmarcar a opção Documentos no processo de movimentação receberá um aviso sobre esse comportamento na caixa [!UICONTROL Mover tarefa] ou [!UICONTROL Mover problema]. Antes dessa melhoria, os documentos eram permanentemente excluídos.

**Ocultar um item oculta o item incorreto**

*Modelos de layout*

Quando um usuário altera o item que está oculto ou exibido, essas alterações são refletidas em um item diferente no modelo de layout.


+++

+++**Atualização de manutenção em 10 de novembro de 2022**

**Tarefas de edição em massa alteram atribuições de tarefas**

*Tarefas*

Quando um usuário edita qualquer campo em massa para um conjunto de tarefas, as Atribuições da primeira tarefa são aplicadas a todas as tarefas. Isso exclui atribuições anteriores.

**Não é possível abrir uma prova interativa**

*Prova do Workfront*

Ao tentar abrir uma prova interativa, a prova não abre e o usuário vê a seguinte mensagem:

“[!UICONTROL Prova não carregada (501) Tente novamente]”

+++

+++**Atualização de manutenção (Hot fix) em 4 de novembro de 2022**

**problemas com tarefas adicionadas a uma iteração**

*Ágil*

Os seguintes problemas foram relatados em relação a tarefas adicionadas a uma iteração:

* Algumas subtarefas de uma tarefa adicionada a uma iteração não aparecem na página [!UICONTROL Iteração].
* Quando um usuário tenta adicionar uma tarefa ausente à iteração, ela não é adicionada e o usuário vê a seguinte mensagem:

   “[!UICONTROL ocorreu o seguinte erro: não foi possível mover nenhum dos itens selecionados, porque não estão atribuídos a uma Equipe Ágil ou não são itens de Equipe Ágil]”

**tarefas atribuídas por meio da edição em massa não aparecem na lista de pendências da equipe**

*Ágil*

Quando um usuário atribui tarefas a uma equipe do Scrum usando a edição em massa, essas tarefas não aparecem na lista de pendências da equipe.

As equipes Kanban não são afetadas por esse problema.

A caixa de texto **“[!UICONTROL Novos recipients de prova]” é muito pequena**

*Provas*

Quando um usuário visualiza uma prova e tenta compartilhar a prova na guia [!UICONTROL Compartilhamento], a caixa de texto “[!UICONTROL Novos recipients da prova]” é muito pequena. O usuário pode digitar um nome, mas como a caixa é muito pequena, o texto fica ilegível.

**As informações de uso do relatório não são atualizadas**

*Relatórios*

Quando um usuário visualiza um relatório, as informações da Última visualização, como a Última data de visualização e a Última visualização por, não são atualizadas. Isso significa que qualquer informação de uso pode estar incorreta.

Esse comportamento foi relatado quando o usuário acessa o relatório das seguintes maneiras:

* Pesquisar
* Pins
* Favoritos
* Recentes

O acesso aos relatórios por meio de um painel atualiza as informações da Última visualização.

**[!DNL Workfront]: erro 500 ao fazer alterações em um objeto do [!DNL Workfront]**+

*[!DNL Workfront]*

Ao tentar fazer alterações em um objeto do [!DNL Workfront], as alterações não são salvas e o usuário vê o seguinte erro:

“[!UICONTROL 500: erro de banco de dados devido à instrução SQL inválida.]”

Esse problema foi relatado as seguintes situações:

* Alteração do status de um objeto
* Recálculo de linhas do tempo
* Anexo de um modelo
* Registro de hora

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 3 de novembro de 2022**

**Erro relacionado a [!UICONTROL apiKey] no módulo [!DNL Workfront] > [!UICONTROL Eventos de observação]**

*[!DNL Workfront Fusion]*

Ao tentar adicionar um webhook no módulo [!DNL Workfront] > [!UICONTROL Eventos de observação], o usuário recebe o seguinte erro:

“[!UICONTROL A apiKey fornecida estava vazia ou era considerada inválida.]”

+++

+++**Atualização de manutenção em 3 de novembro de 2022**

**Renomeie as seções “Cronograma” e “Planejando” para equipes e projetos no modelo de layout**

*Modelos de layout*

As guias “Cronograma” e “Planejando” disponíveis para adicionar um modelo de layout ao painel esquerdo de uma equipe ou projeto foram renomeadas para “Balanceador de carga de trabalho”.

**Erros ao acessar configurações de notificação por email**

*Notificações*

>[!NOTE]
>
>Esse problema existe nos ambientes Produção e Pré-visualização.

Ao tentar alterar as configurações de notificação por email, o usuário pode ver os seguintes erros:

* “[!UICONTROL Vamos tentar novamente. Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

* “[!UICONTROL Falha ao obter notificação por email]”

Esse problema foi relatado nas seguintes áreas:

* [!UICONTROL Configuração] > [!UICONTROL Notificações por email]
* [!UICONTROL Usuário] > [!UICONTROL Editar usuário]
* [!UICONTROL Grupos]

**Novos ícones de informações para folhas de ponto, perfis de folha de ponto e preferências de folha de ponto**

*Workfront*

>[!NOTE]
>
>Esta atualização foi lançada somente no ambiente de Visualização. Ele será lançado para produção com a versão 23.1.

Adicionamos vários ícones de informações às seguintes configurações:

* Caixa de seleção &quot;Pode editar hora&quot; ao criar ou editar uma folha de ponto ou um perfil de folha de ponto para indicar que, quando ativada, os aprovadores também podem enviar, reabrir ou editar a folha de ponto, a menos que o administrador restrinja essas ações na área Preferências da folha de ponto da Configuração.
* &quot;Restringir a edição da folha de ponto a proprietários e administradores&quot; na área Folha de horas e preferências de hora da configuração para indicar que, quando desativado, os usuários a seguir também podem editar as folhas de horas: usuários com acesso administrativo a folhas de ponto e horas, aprovadores de folha de ponto com permissão para editar tempo e gerentes de proprietários de folha de ponto.

Observe que a funcionalidade dessas configurações não foi alterada e somente os ícones de informações foram adicionados para esclarecer o escopo das configurações.

+++

## Atualizações em outubro de 2022

+++**Atualização de manutenção em 27 de outubro de 2022**

A função **[!UICONTROL HORA] em campos calculados usa UTC**

*Formulários personalizados*

Quando um campo calculado inclui a função [!UICONTROL HORA], a função retorna valores com base em UTC, em vez do fuso horário esperado. Portanto, qualquer cálculo baseado no valor HORA está incorreto.

O **[!UICONTROL Filtro rápido] não retorna resultados ao pesquisar por equipes**

*Listas*

Quando um usuário tenta usar o [!UICONTROL Filtro rápido] em uma lista para procurar uma equipe, inserir o nome da equipe não retorna resultados, mesmo quando a equipe está visível na lista (como no campo [!UICONTROL Atribuído a]). Pesquisar a palavra “[!UICONTROL equipe]” também não retorna nenhum resultado.

**Não é possível fixar novamente uma página após a remoção do pino**

*Navegação*

>[!NOTE]
>
>Esse problema foi corrigido na Pré-visualização em 13 de outubro de 2022. Foi corrigido na Produção em 27 de outubro de 2022.

Ao selecionar a opção “[!UICONTROL Remover pino]” em um pino, o usuário recebe uma mensagem sobre a remoção e tenta substituir o pino clicando em “[!UICONTROL Desfazer]” na mensagem. O pino não é substituído na navegação superior, nem é adicionado à lista de pinos na lista [!UICONTROL Mais pinos] (o menu de três pontos na área [!UICONTROL Pinos]).

Se um usuário tentar fixar novamente a página indo até a página e fixando o pino, o pino não será criado e o usuário não poderá fixar a página.

**Todos os usuários listados no [!UICONTROL Balanceador de carga de trabalho] ao usar um link compartilhável no [!DNL Safari] navegador**

*[!UICONTROL Balanceador de carga de trabalho]*

Ao seguir um link compartilhável para o [!UICONTROL Balanceador de carga de trabalho] ao usar um navegador do [!DNL Safari], o usuário vê todos os usuários em vez de apenas os membros da equipe listados.

+++

+++**Atualização de manutenção em 20 de outubro de 2022**

**Erro ao atribuir uma equipe em massa**

*Atribuições*

Quando um usuário edita tarefas ou problemas em massa e atribui uma equipe após atribuir um indivíduo, as atribuições não são salvas e o usuário vê o seguinte erro:

“[!UICONTROL Vamos tentar novamente. Ocorreu o seguinte erro: teamAssignments deve ser uma lista de objetos ou uma lista de IDs]”

Erro **“[!UICONTROL Falha ao carregar arquivo]”**

*Documentos*

Quando um usuário tenta fazer upload de um arquivo para a área [!UICONTROL Documentos], o arquivo não é carregado e o usuário vê o erro “[!UICONTROL Falha ao fazer upload do arquivo].”

Esse problema foi relatado ao tentar fazer upload de arquivos MP4.

**A contagem de problemas na navegação à esquerda da tarefa está incorreta**

*Problemas*

Quando um usuário está visualizando uma tarefa, o número exibido na seção [!UICONTROL Problemas] da navegação à esquerda não representa precisamente o número real de problemas anexados à tarefa.


O ícone **[!UICONTROL Predecessor] não aparece no cabeçalho da tarefa**

*Tarefas*

Quando um usuário está visualizando uma tarefa, o ícone predecessor da tarefa não aparece no cabeçalho.

+++

+++**Atualização de manutenção em 13 de outubro de 2022**

**Não é possível fixar novamente uma página após a remoção do pino**

*Navegação*

>[!NOTE]
>
>Esse problema será corrigido na Pré-visualização em 13 de outubro de 2022. Ele será corrigido na Produção em 27 de outubro de 2022.

Ao selecionar a opção “[!UICONTROL Remover pino]” em um pino, o usuário recebe uma mensagem sobre a remoção e tenta substituir o pino clicando em “[!UICONTROL Desfazer]” na mensagem. O pino não é substituído na navegação superior, nem é adicionado à lista de pinos na lista [!UICONTROL Mais pinos] (o menu de três pontos na área [!UICONTROL Pinos]).

Se um usuário tentar fixar novamente a página indo até a página e fixando o pino, o pino não será criado e o usuário não poderá fixar a página.

**Não é possível nomear ou salvar os filtros recém-criados**

*[!UICONTROL Planejamento de recursos]*

Quando um usuário tenta nomear um novo filtro no [!UICONTROL Planejador de recursos], a caixa de nome permanece em branco. Além disso, se o usuário pressionar a barra de espaço, o botão [!UICONTROL Salvar] ficará desativado.

**Não é possível editar o nome ou porcentagem concluída de uma tarefa ou problema**

*Tarefas e problemas*

Usuários com acesso ao [!UICONTROL Contribute] a uma tarefa ou problema não pode editar o nome da tarefa ou problema no cabeçalho. Além disso, os usuários com acesso ao [!UICONTROL Contribute] não pode editar o percentual concluído de uma tarefa ou problema.

**Solicitantes e Revisores entram na contagem de licenças de uma organização**

*[!DNL Workfront Proof]*

Quando adicionado a uma prova como Revisor ou Solicitante, o usuário obtém um perfil de permissões de “[!UICONTROL Visitante]”, que não deve usar uma licença do [!DNL Workfront Proof]. No entanto, quando o usuário é adicionado, a contagem de licenças do [!DNL Workfront Proof] aumenta.

+++

+++**Atualização de manutenção em 11 de outubro de 2022**

**Não é possível fixar novamente uma página após a remoção do pino**

*Navegação*

>[!NOTE]
>
>Esse problema foi corrigido na Pré-visualização em 13 de outubro de 2022. Ele será corrigido na Produção em 27 de outubro de 2022.

Ao selecionar a opção “[!UICONTROL Remover pino]” em um pino, o usuário recebe uma mensagem sobre a remoção e tenta substituir o pino clicando em “[!UICONTROL Desfazer]” na mensagem. O pino não é substituído na navegação superior, nem é adicionado à lista de pinos na lista [!UICONTROL Mais pinos] (o menu de três pontos na área [!UICONTROL Pinos]).

Se um usuário tentar fixar novamente a página indo até a página e fixando o pino, o pino não será criado e o usuário não poderá fixar a página.

+++

+++**Atualização de manutenção em 6 de outubro de 2022**

**Novo tipo de blueprint**

*Blueprints*

O tipo de blueprint “Painel” foi adicionado ao catálogo de blueprints. Anteriormente, somente Modelos de projeto e blueprints de estrutura organizacional estavam disponíveis.

**Sobreposição de elementos no painel esquerdo**

*Formulários personalizados*

Quando um usuário está trabalhando no construtor de formulários e o formulário tem mais de 100 campos, a mensagem notificando o usuário sobre o limite de campo faz com que os elementos no painel esquerdo se sobreponham.

**O seletor de datas não abre mais automaticamente no foco de entrada ou clique**

*Navegação*

Quando um usuário navega pelo teclado, os seletores de data não são mais abertos automaticamente na data de entrada recebendo foco do teclado. Em vez disso, os usuários do teclado devem ir até o ícone do seletor de datas e pressionar Enter para abrir o seletor de datas. Quando um usuário navega pelo mouse, os seletores de data não são mais abertos automaticamente na data de clique na entrada. Em vez disso, os usuários do mouse devem clicar no ícone do seletor de datas para abrir o seletor de datas.

Essa alteração foi feita para se adequar melhor aos padrões de UX do seletor de data padrão e para criar uma experiência mais acessível para usuários de teclado e leitor de tela.

**Atribuir várias equipes resulta em somente uma equipe atribuída**

*Equipes*

>[!NOTE]
>
>Esse problema existe apenas no ambiente de Visualização.

Quando um usuário atribui várias equipes a uma tarefa ou problema, somente uma equipe é exibida na lista de atribuições. Esse problema também afeta os relatórios. Os relatórios que mostram atribuições de equipe são imprecisos porque somente uma equipe aparece como atribuída à tarefa ou problema.

Erro **“[!UICONTROL As alterações recentes não foram salvas]” ao salvar automaticamente alterações em uma folha de horas**

*Folhas de horas*

Quando um usuário tenta editar uma folha de horas de uma maneira que acionaria um salvamento automático, as alterações não são salvas e o usuário vê a seguinte mensagem:

“[!UICONTROL Suas alterações recentes não foram salvas. Atualize a página para visualizar as últimas alterações salvas].”

Esse problema foi relatado ao editar o seguinte:

* Horas
* Tarefas

**as notificações por email estão atrasadas**

*Prova do Workfront*

Quando ocorre um evento no [!DNL Workfront Proof] que aciona uma notificação por email, o usuário não recebe a notificação imediatamente. A notificação pode ser adiada por várias horas.

+++

+++**Atualização de manutenção em 3 de outubro de 2022**

**Salve manualmente a folha de horas quando as funções de trabalho anteriores forem alteradas**

*Folhas de horas*

Se uma função de trabalho para a qual você fez o logon tiver sido alterada e a configuração [!UICONTROL Atribuir funções de tarefa a entradas de hora manualmente] tiver sido desativada, você deve salvar manualmente as entradas de tempo até que as horas não sejam mais registradas para a função de trabalho que foi alterada.

+++

## Atualizações em setembro de 2022

+++**Atualização de manutenção em 29 de setembro de 2022**

**O usuário não retorna à página anterior ao fechar a prova**

*Provas*

Quando um usuário que está visualizando uma prova no [!DNL Workfront] fecha a prova, ele não retorna à página em que estava antes de abrir a prova. Em vez disso, ele é redirecionado para outra página no [!DNL Workfront].

**Não é possível abrir a prova no[!DNL Workfront]**

*Provas*

Quando um usuário visualiza um documento no [!DNL Workfront] e tenta abrir a prova, a prova não abre e o usuário retorna para a página [!UICONTROL Detalhes do documento].

**As horas não são salvas ao usar[!UICONTROL  a tecla ]Tab**

*Folhas de horas*

Quando um usuário preenche uma folha de horas e navega entre células com a tecla [!UICONTROL Tab], as horas não são salvas. A notificação de [!UICONTROL Salvamento automático] não é exibida na parte inferior da tela e, se o usuário atualizar a página, ele poderá ver as horas que não foram salvas.

**Páginas em branco ao visualizar uma prova com várias páginas**

*[!DNL Workfront Proof]*

Quando um usuário visualiza uma prova com várias páginas, o usuário pode ver miniaturas das páginas, mas as páginas não abrem no visualizador principal.



+++

+++**Atualização de manutenção em 22 de setembro de 2022**

**Não é possível fechar o cartão de usuário no fluxo de atualização**

*Atualizações*

Quando um usuário está visualizando atualizações e passa o mouse sobre um nome, um cartão com detalhes sobre o usuário é aberto e não é fechado automaticamente. A página não responde até que o cartão seja fechado manualmente clicando no X no canto superior direito.

+++

+++**Atualização de manutenção em 15 de setembro de 2022**

Erro **“[!UICONTROL Alguém tentou salvar este projeto]” erro ao inserir horas**

*Folhas de horas*

Quando um usuário tenta registrar horas em uma tarefa em sua folha de horas, as horas não são salvas automaticamente e o usuário vê o seguinte erro:

“[!UICONTROL Desculpe, você não conseguiu salvar porque outra pessoa tentou salvar este projeto ao mesmo tempo. Tente salvar novamente.]”

**Não é possível fechar o cartão de usuário no fluxo de atualização**

*Atualizações*

Quando um usuário está visualizando atualizações e passa o mouse sobre um nome, um cartão com detalhes sobre o usuário é aberto e não é fechado automaticamente. A página não responde até que o cartão seja fechado manualmente clicando no X no canto superior direito.

**O campo “[!UICONTROL Atribuição de função de tarefa]” foi renomeado para “[!UICONTROL Atribuição de função]” ao atribuir trabalho em massa usando o [!UICONTROL Balanceador de carga de trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Para refletir a nova funcionalidade de poder atribuir tarefas e problemas em massa a área [!UICONTROL Trabalho não atribuído], renomeamos o campo “[!UICONTROL Atribuição de função de tarefa]” para “[!UICONTROL Atribuição de função]” no [!UICONTROL Balanceador de carga de trabalho]. O campo se refere às funções de trabalho que foram atribuídas a tarefas ou problemas e é exibido ao atribuir usuários a itens na caixa [!UICONTROL Atribuições em massa].

+++

+++**[!DNL Workfront Scenario Planner]Atualização de manutenção em 15 de setembro de 2022**

**O filtro compartilhado com um Grupo agora é exibido na lista [!UICONTROL Importar projetos] do [!DNL Scenario Planner] para membros de todos os subgrupos**

*[!DNL Workfront Scenario Planner]*

Agora, ao compartilhar um filtro de projeto com um grupo que tem subgrupos adicionais, o filtro fica visível para todos os membros do grupo e do subgrupo que visualizam projetos na caixa [!UICONTROL Importar projetos] de um plano no [!DNL Scenario Planner].

+++

+++**Atualização de manutenção em 8 de setembro de 2022**

**Nomes atualizados revertidos para os campos de atribuição de usuário e função**

*Atribuições*

Os campos de atribuição temporariamente renomeados na semana passada foram revertidos para seus nomes originais:

* [!UICONTROL Usuários atribuídos]
* [!UICONTROL Funções das atribuições]

**Erro ao remover o Proprietário do projeto do cabeçalho**

*Projetos*

Quando um usuário tenta remover um [!UICONTROL Proprietário do projeto] do cabeçalho, o [!UICONTROL Proprietário do projeto] não é removido e o usuário vê a mensagem de erro a seguir:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**A caixa [!UICONTROL Descrição] redimensionada volta ao tamanho original**

*Projetos, tarefas e problemas*

Quando um usuário redimensiona a caixa [!UICONTROL Descrição] na área de detalhes de um item de trabalho para aumentá-la e, em seguida, começa a digitar na caixa, ela retorna ao tamanho original. O usuário pode digitar na caixa e o conteúdo é salvo conforme esperado

**Saída involuntária ao criar tarefas ou problemas**

*Tarefas e problemas*

Quando um usuário está criando uma tarefa ou um problema em um projeto e clica fora da janela pop-up de criação, ela é fechada sem aviso e todas as informações inseridas anteriormente são perdidas.

**Remoção da capacidade de enviar uma prova por email para uma zona de lançamento**

*[!DNL Workfront Proof]*

Desde quinta-feira, 8 de setembro de 2022, removemos a capacidade de enviar uma prova por email para uma área de lançamento no produto [!DNL Workfront Proof] independente.

Você ainda pode usar as áreas de lançamento de outras maneiras para enviar novas provas e novas versões de provas para sua conta sem precisar entrar em sua conta. Consulte [A área de lançamento](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html?lang=pt-BR) para obter mais informações.

+++

+++**Atualização de manutenção em 6 de setembro de 2022**

**Datas projetadas adicionadas à lista de campos para cabeçalhos de projetos personalizáveis**

*Projetos*

Acrescentamos a [!UICONTROL Data inicial projetada] e a [!UICONTROL Data de conclusão projetada] à lista de campos para cabeçalhos de projeto personalizáveis ao usar um modelo de layout.

**Novo limite com uma mensagem de confirmação que exibe o número de itens adicionados a uma folha de horas**

*Folhas de horas*

Ao selecionar mais de 50 itens para adicionar a uma folha de horas, você receberá uma mensagem de confirmação que exibe o número de itens a serem adicionados à folha de horas e oferece a oportunidade de alterar o curso e não adicionar todos os itens. Todos os itens adicionados se tornam automaticamente fixados à folha de horas e precisarão ser removidos manualmente da folha de horas atual e de todas as futuras.

+++

+++**Atualização de manutenção em 2 de setembro de 2022**

Adicione o campo [!UICONTROL Integrações] ao cabeçalho personalizado do projeto

*Integrações*

Agora é possível adicionar o campo [!UICONTROL Integrações] ao cabeçalho personalizado de um projeto ao usar um modelo de layout. Depois de adicionado, o campo exibirá um link para um item externo vinculado ao projeto que está localizado em [!DNL Salesforce] ou [!DNL Anaplan], dependendo da integração.

>[!NOTE]
>
>Essa atualização de manutenção foi lançada anteriormente no ambiente de Visualização em 25 de agosto de 2022 e agora está em produção.

+++

+++**Atualização de manutenção em 1 de setembro de 2022**

**Itens concluídos removidos da delegação**

*Delegações*

Agora, somente itens incompletos cujas datas correspondem às datas de uma delegação serão delegados a outros usuários quando a delegação de itens de trabalho começar. Se foram concluídos antes da delegação começar, os itens não serão delegados. Os itens concluídos durante o período de delegação permanecerão na Lista de trabalho da Área inicial do delegado e do destinatário por duas semanas antes de serem removidos automaticamente, se a delegação não tiver terminado durante essas semanas.

**Atualizações de metadados para o [!DNL Adobe Workfront] para integrações do [!DNL Experience Manager Assets] e [!DNL Assets Essentials]**

*Integrações*

Os metadados são enviados automaticamente ao adicionar um ativo a uma pasta vinculada.

Anteriormente, os metadados eram enviados somente quando você adicionava um ativo usando o menu suspenso [!UICONTROL Adicionar novo].

**Não é possível aprovar ou rejeitar horas em um problema**

*Problemas*

Quando um usuário tenta aprovar ou rejeitar horas na guia [!UICONTROL Horas] de um problema, os botões [!UICONTROL Aprovar] e [!UICONTROL Rejeitar] não são exibidos.

**A conversão de um problema em um projeto usando um modelo exibe uma mensagem de erro incorreta**

*Problemas*

Se ao converter um problema em um projeto usando um modelo um erro for encontrado, o usuário verá uma página com a mensagem “[!UICONTROL O projeto não existe mais]” em vez da mensagem de erro correta que explica a causa da falha na conversão.

**Não é possível criar prova para arquivos com mais de 1,5 GB**

*[!DNL Workfront Proof]*

Ao criar uma nova prova, se um usuário carregar um arquivo com mais de 1,5 GB, o nome do arquivo ficará vermelho e não será possível criar a prova.

+++

## Atualizações em agosto de 2022

+++**Atualização de manutenção em 25 de agosto de 2022**

**Os links do Balanceador de carga de trabalho são exibidos incorretamente nos painéis**

*Painéis*

Os links compartilháveis do Balanceador de carga são exibidos incorretamente quando adicionados a um painel como uma página externa. Em vez de usar a visualização/filtros exclusivos associados ao link, o painel usa a visualização/filtros aplicados mais recentemente ao Balanceador de carga.

**Adicione o campo [!UICONTROL Integrações] ao cabeçalho personalizado do projeto**

*Projetos*

Agora é possível adicionar o campo [!UICONTROL Integrações] ao cabeçalho personalizado de um projeto ao usar um modelo de layout. Depois de adicionado, o campo exibirá um link para um item externo vinculado ao projeto que está localizado em [!DNL Salesforce] ou [!DNL Anaplan], dependendo da integração.

>[!NOTE]
>
>No momento, essa atualização de manutenção está somente no ambiente de Visualização. Ele será lançado para produção uma semana após o lançamento da Pré-visualização.

**Os dados personalizados não são preservados ao converter um problema em um projeto em branco**

*Projetos*

Quando um usuário converte um problema em um projeto em branco (sem um modelo), os dados em campos calculados não são transferidos para o novo projeto.

**Erro “Modo de planejamento de linha do tempo” ao alterar uma data em um projeto**

*Projetos*

Quando um usuário tenta alterar uma data em um projeto com o [!UICONTROL Modo de plano] definido como [!UICONTROL Salvar manualmente] > [!UICONTROL Planejamento de linha do tempo], a data não muda e o usuário vê um erro.

“[!UICONTROL O modo de Planejamento de linha do tempo está disponível somente quando a data da linha do tempo é carregada. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

**Consistência ao abrir o Balanceador de carga de trabalho usando a visualização Mês**

*Balanceador de carga de trabalho*

Agora, o Balanceador de carga de trabalho exibe os itens atribuídos dos usuários expandidos ao exibi-los nas visualizações [!UICONTROL Dia], [!UICONTROL Semana] ou [!UICONTROL Mês]. Antes dessa atualização, os itens atribuídos eram exibidos expandidos para as visualizações [!UICONTROL Dia] e [!UICONTROL Semana] e recolhidas para a visualização [!UICONTROL Mês].


+++

+++**Atualização de manutenção em 18 de agosto de 2022**

**As opções “[!UICONTROL Adicionar à iteração]” e “[!UICONTROL Adicionar ao Quadro Kanban]” não estão disponíveis ao editar tarefas em linha em um relatório**

*Relatórios*

Quando um usuário visualiza uma lista de tarefas em um relatório e abre o menu [!UICONTROL Mais] (três pontos), as opções “[!UICONTROL Adicionar à iteração]” e “[!UICONTROL Adicionar ao Quadro Kanban]” não estão disponíveis na lista suspensa. Se o relatório for visualizado em um painel, as opções “[!UICONTROL Adicionar à iteração]” e “[!UICONTROL Adicionar ao Quadro Kanban]” estarão disponíveis na lista suspensa.

**Relatórios de matriz são exibidos incorretamente ao rolar a página**

*Relatórios*

Quando um usuário exibe um relatório de matriz e rola a tela, alguns elementos visuais do relatório podem se sobrepor ou duplicar.

A exibição **[!UICONTROL Marco] foi removida da lista de projetos de Folhas de horas**

*Folhas de horas*

A exibição [!UICONTROL Marco] foi removida da lista de projetos da folha de horas ao adicionar um projeto.

**Os hiperlinks em uma prova interativa não estão ativos**

*[!DNL Workfront Proof]*

Quando um usuário está visualizando uma prova interativa e clica em um link ou botão que contém um link, o usuário não é levado para a página à qual o link ou botão é vinculado.

**Nova página de prova sem campos de texto**

*[!DNL Workfront Proof]*

Na página [!DNL New Proof], muitos campos de texto não são exibidos (incluindo rótulos de campo, opções suspensas e nomes de caixas de seleção).

**Os usuários não recebem notificações quando marcados em uma prova**

*[!DNL Workfront Proof]*

Quando um usuário é marcado em um comentário de prova, ele não recebe uma notificação por email sobre o comentário.

+++

+++**Atualização de manutenção em 12 de agosto de 2022**

**Novo campo de cabeçalho personalizável adicionado ao início do cabeçalho**

*Cabeçalhos*

Ao adicionar um novo campo a um cabeçalho personalizável, o campo agora é adicionado como o primeiro campo à esquerda no cabeçalho ou imediatamente após a caixa [!UICONTROL Pesquisar] dentro do Modelo de layout. Antes dessa alteração, o campo era adicionado como o último campo no cabeçalho.

+++

+++**Atualização de manutenção em 11 de agosto de 2022**

**Não é possível editar formulários personalizados devido ao limite de caracteres incorreto em campos de texto Descritivo**

*Formulários personalizados*

Quando um usuário tenta editar um formulário personalizado e ele tem um campo [!UICONTROL Texto descritivo] que contém mais de 512 caracteres no momento, o usuário não pode salvar as edições no formulário personalizado e vê o seguinte erro:

“Os seguintes campos são inválidos: (Campo) é muito longo, máx. 512”

Isso afeta os campos [!UICONTROL Texto descritivo] que antes funcionavam bem, apesar de terem mais de 512 caracteres.

**Os dados em campos ocultos pela quebra de seção não são preservados ao converter um problema em um projeto**

*Formulários personalizados*

Quando um usuário está convertendo um problema em um projeto e o problema inclui um formulário personalizado com dados em uma quebra de seção que pode ser ocultada usando a lógica de exibição, os dados nessa seção não são transportados para o novo projeto.

**Os dados em campos ocultos pela quebra de seção não são preservados ao converter uma solicitação em um projeto**

*Formulários personalizados*

Quando um usuário converte uma solicitação em um projeto e a solicitação inclui um formulário personalizado com dados em uma quebra de seção que pode ser ocultada usando a lógica de exibição, os dados nessa seção não são transportados para o novo projeto.

**Não é possível editar formulários personalizados devido ao campo Texto descritivo**

*Formulários personalizados*

Quando um usuário tenta editar um formulário personalizado que inclui um campo de Texto descritivo, o rótulo do campo não é preenchido. O usuário vê o erro “[!UICONTROL Este campo é obrigatório]” no campo de rótulo e não consegue editar o formulário personalizado devido a esse erro.

**Não é possível remover instruções de um campo personalizado no construtor de formulários personalizado**

*Formulários personalizados*

Quando um usuário está editando um campo personalizado e tenta remover o texto existente na área de [!UICONTROL Instruções], o texto não é removido quando o campo é salvo. O usuário pode editar o texto, mas não pode removê-lo totalmente.

**A atribuição de equipe ao criar solicitação não aparece na nova solicitação**

*Solicitações*

Quando um usuário cria uma solicitação e atribui uma equipe à solicitação e, em seguida, envia a solicitação, a equipe não é atribuída à solicitação que foi criada. Isso afeta somente a atribuição de equipe. As atribuições de usuário funcionam conforme esperado.

+++

+++**Atualização de manutenção em 4 de agosto de 2022**

Esses problemas foram corrigidos somente na nova experiência do [!DNL Workfront].

Todas as funcionalidades do [!DNL Workfront Classic] foram removidas em 14 de julho de 2022.

**Erro ao alterar a Data de conclusão planejada no cabeçalho de uma tarefa ou problema**

*Tarefas e problemas*

Quando um usuário tenta alterar a [!UICONTROL Data de conclusão planejada] no cabeçalho de uma tarefa ou problema, a data não é alterada e o usuário vê um erro semelhante ao seguinte:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Atualizações em julho de 2022

+++**Atualização de manutenção em 28 de julho de 2022**

Esses problemas foram corrigidos somente na nova experiência do [!DNL Workfront].

Todas as funcionalidades do [!DNL Workfront Classic] foram removidas em 14 de julho de 2022.

**Erro ao abrir um item da [!UICONTROL Lista de trabalho da página inicial]**

*[!UICONTROL Página inicial]*

Quando um usuário tenta abrir um item na [!UICONTROL Lista de trabalho da página inicial], o item não abre e o usuário vê a seguinte mensagem:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho tente atualizar esta página do navegador.]”

**Tarefas e problemas delegados a um usuário não aparecem na Lista de trabalho da página inicial do usuário**

*[!UICONTROL Página inicial]*

Quando o usuário visualiza a [!UICONTROL Lista de trabalho inicial], as tarefas ou questões delegadas ao usuário não aparecem na lista e o usuário pode não estar ciente das delegações.

**Os relatórios agendados não são enviados a todos os recipients**

*Relatórios*

Quando um relatório agendado é enviado, ele não é enviado para todos os usuários na seção “[!UICONTROL Enviar para]”. Os usuários omitidos são aleatórios e podem variar cada vez que o relatório é enviado.

**[!UICONTROL Não é possível desmarcar tarefas ao anexar o modelo]**

*Modelos*

Quando um usuário anexa e personaliza um modelo, ele é solicitado a desmarcar as tarefas que não deseja incluir. No entanto, nenhuma das tarefas é exibida como selecionada e o usuário não pode desmarcá-las.

**Os campos “Local” agora têm rótulos mais específicos**

*Terminologia*

Para tornar a função dos campos “[!UICONTROL Local]” mais clara, atualizamos seus rótulos.

* O campo “[!UICONTROL Local]” no perfil do usuário agora é rotulado como “[!UICONTROL Local de email]”
* O campo “[!UICONTROL Local]” encontrado na área [!UICONTROL Configuração] > [!UICONTROL Sistema] > [!UICONTROL Informações do cliente] agora está rotulado como “[!UICONTROL Local de email padrão]”

A funcionalidade desses campos não foi alterada.

**Problemas ao criar folhas de horas**

*Folhas de horas*

Os seguintes problemas foram relatados em relação à criação de folhas de horas:

* Quando um usuário tenta criar uma folha de horas para uma Função, a folha de horas não é criada e o usuário vê o erro “[!UICONTROL Usuário com valores de chave primária ‘XXXXXXXXXXX’ não encontrado].”
* Quando um usuário tenta criar uma folha de horas para uma Equipe, o campo [!UICONTROL digitação antecipada] não é preenchido com equipes e o botão [!UICONTROL Criar folha de horas] está desativado.


**As áreas do [!DNL Workfront Proof] não são atualizadas quando uma prova é criada, movida ou arquivada**

*[!DNL Workfront]Prova*

O Proof está enfrentando atrasos de indexação no momento. Isso pode afetar a experiência do usuário das seguintes formas:

* Os painéis não mostram o número correto de provas
* As pastas não são atualizadas quando uma prova é criada ou movida
* As provas arquivadas permanecem em listas de prova ativas.

+++

+++**Atualização de manutenção (hotfix) em 26 de julho de 2022**

Esses problemas foram corrigidos somente na nova experiência do [!DNL Workfront].

Todas as funcionalidades do [!DNL Workfront Classic] foram removidas em 14 de julho de 2022.

**As horas mostradas na folha de horas são diferentes da lista Folhas de horas**

*Folhas de horas*

Quando um usuário abre uma folha de horas, as horas exibidas são diferentes de quando o usuário abre a mesma folha de horas em uma lista de folhas de horas.


**Solicitação convertida em projeto com modelo mostra o grupo da fila de solicitações, não o grupo do modelo**

*Solicitações*

Quando um usuário converte uma solicitação em um projeto usando um modelo, o projeto recém-criado é associado ao grupo que tem a fila de solicitações, não ao grupo atribuído no modelo. Isso ocorre mesmo quando o projeto está sendo criado, o grupo associado ao modelo é preenchido no campo [!UICONTROL Grupo].

+++

+++**Atualização de manutenção em 21 de julho de 2022**

Esses problemas foram corrigidos somente na nova experiência do [!DNL Workfront].

Todas as funcionalidades do [!DNL Workfront Classic] foram removidas em 14 de julho de 2022.

**O status de rejeição associado a uma aprovação respeita o fluxo de trabalho de aprovação**

**OBSERVAÇÃO: essa funcionalidade foi lançada em 22 de julho de 2022.**

*Aprovações*

Se você selecionar um status associado a um processo de aprovação como status de rejeição para um caminho de aprovação, o objeto rejeitado será movido para o status selecionado e será marcado como “[!UICONTROL Aprovação pendente]”. Por exemplo, se você selecionar [!UICONTROL Em espera] para o status de rejeição e o status [!UICONTROL Em espera] estiver associado a um processo de aprovação, o objeto rejeitado será colocado no status “[!UICONTROL Em espera - Aprovação pendente]”, exigindo a aprovação.

Antes dessa atualização, o objeto ignorava o processo de aprovação do status de rejeição e era colocado no status [!UICONTROL Em espera].

**Configurar um URL de ajuda personalizado**

*[!UICONTROL Menu principal]*

Se sua organização tiver um site de ajuda interno personalizado, será possível configurar o ícone [!UICONTROL Menu principal] [!UICONTROL Ajuda] para acessar esse site. Isso é útil se o site de ajuda tiver informações sobre como sua organização usa o [!DNL Workfront].
Esse URL personalizado não afeta o link principal da Ajuda na área superior do [!DNL Workfront], nem os links de ajuda com reconhecimento de contexto no [!DNL Workfront], que direciona os usuários para o Site de ajuda do [!DNL Workfront].

**Não é possível selecionar Tempo decorrido ao editar a [!UICONTROL Duração da tarefa]** em linha

*Tarefas*

Quando um usuário está visualizando uma lista de tarefas e tenta editar a [!UICONTROL Duração da tarefa], as unidades de duração decorrida não estão disponíveis:

* [!UICONTROL Minutos corridos]
* [!UICONTROL Horas corridas]
* [!UICONTROL Dias corridos]
* [!UICONTROL Semanas corridas]
* [!UICONTROL Meses decorridos]

A página **[!UICONTROL Minhas atualizações] está em branco**

*Atualizações*

Quando um usuário tenta abrir a página [!UICONTROL Minhas atualizações], a página não carrega. O usuário pode visualizar somente o cabeçalho de navegação [!DNL Workfront].

A configuração **“[!UICONTROL Permitir apenas a autenticação SAML 2.0]” está ausente ao copiar um usuário**

*Usuários*

Quando um administrador de grupo copia um usuário e desmarca a opção “[!UICONTROL Enviar um email de convite para essa pessoa]”, a caixa de seleção [!UICONTROL Permitir apenas a autenticação SAML 2.0] não é exibida conforme esperado. Isso pode ocorrer mesmo quando todos os requisitos de acesso e permissão para essa ação forem atendidos.

+++

+++**Atualização de manutenção em 14 de julho de 2022**

Esses problemas foram corrigidos somente na nova experiência do [!DNL Workfront].

Todas as funcionalidades do [!DNL Workfront Classic] foram removidas em 14 de julho de 2022.

**Erro ao redefinir a senha**

*Logon*

Quando um usuário tenta redefinir sua senha, ele não pode redefini-la e vê uma mensagem informando que não tem acesso. O usuário não consegue fazer logon no Workfront.

**Não é possível solicitar mais acesso a um relatório**

*Relatórios*

Quando um usuário com acesso limitado a um relatório tenta solicitar mais acesso, a opção para solicitar mais acesso não está disponível no menu [!UICONTROL ações de relatório].

**Mensagem de confirmação atualizada ao excluir um rascunho de solicitação**

*Solicitações*

Ao descartar uma solicitação em rascunho, a mensagem de confirmação exibida ao clicar em “[!UICONTROL Descartar rascunho]” exibe o seguinte:

* [!UICONTROL O rascunho foi descartado] (esta é uma notificação para que você saiba que o rascunho foi descartado)
* [!UICONTROL Desfazer] (este é um link que você pode clicar para reverter a ação de excluir o rascunho. Essa ação manterá o rascunho em vez de excluí-lo.)

Antes dessa alteração, as opções eram:

* [!UICONTROL O rascunho será descartado]
* [!UICONTROL Cancelar]

**Valores de data para campos de Lançamento documentado incorretos quando acessados por meio da API**

*Atualizações*

Quando um usuário altera um valor de data em um objeto e, em seguida, o Lançamento documentado que representa essa alteração de data é acessado por meio da API, os valores de data para [!UICONTROL oldDateVal] e [!UICONTROL newDateVal] retornados pela API estão incorretos.

**Erro ao tentar desfazer o comentário**

*Atualizações*

Quando um usuário tenta desfazer um comentário, ele não é desfeito e o usuário vê o seguinte erro:

[!UICONTROL Erro 403: você não tem acesso suficiente para excluir esta Nota /attask/api-internal/NOTE]

**Nova limitação ao número de caracteres em uma atualização na Pré-visualização**

*Atualizações*

Para melhorar o desempenho da área [!UICONTROL Atualizações], introduzimos um novo limite para o número de caracteres que podem ser inseridos em uma atualização ou em uma resposta a uma atualização existente. O novo limite é de 15.000 caracteres. Essa atualização não alterou o número de caracteres permitidos ao usar a API. O limite de caracteres da API para atualizações é 4.000.

**Erro ao fazer upload do anexo de [!DNL Workfront] para integração com o Outlook**

*Integrações do Workfront*

Quando um usuário tenta fazer upload de um anexo usando o [!DNL Workfront for Outlook], o anexo não é carregado e o usuário vê a seguinte mensagem:

[!UICONTROL Alguns anexos não foram carregados. Motivo: algo deu errado com o carregamento de anexos.]

**Atualização de notificação por email de prova**

*[!DNL Workfront]Prova*

No início deste mês, como parte de uma correção para o ambiente de produção do [!DNL Workfront], corrigimos alguns erros no sistema de notificação por email de prova. Essa alteração não foi comunicada na atualização de manutenção quando foi lançada. Adicionamos as seguintes informações à [Atualização de manutenção em 2 de junho de 2022](#maintenance-update-on-june-2-2022):

Como resultado dessas correções de erros, o endereço de email usado para enviar notificações de prova foi alterado.

Anteriormente, os endereços de email de prova continham o subdomínio de sua organização. Por exemplo, notifications@[company domain].my.workfront.com

Agora, a criação de perfis de endereços de email não contém mais um subdomínio de organização. Todas as notificações por email de prova serão enviadas pelo seguinte endereço: notification@my.workfront.com

Como resultado, recomendamos que você execute as seguintes ações caso ainda não tenha feito:

* Atualize seus filtros de spam para aceitar emails de notification@my.workfront.com
* Atualize suas listas de permissões para aceitar emails de notification@my.workfront.com

**As opções de usuário não podem ser modificadas após a configuração inicial em Modelos de fluxo de trabalho**

*[!DNL Workfront Proof]*

Quando um usuário adiciona um usuário a um Modelo de fluxo de trabalho, é possível configurar opções. No entanto, após a conclusão da configuração inicial, o usuário não poderá mais modificar o seguinte:

* A capacidade de “[!UICONTROL Resolver comentários e aplicar ações]”
* A capacidade de “[!UICONTROL Compartilhar prova por meio de marcação]”
* Função de prova ([!UICONTROL Revisor], [!UICONTROL Aprovador], etc.)

O filtro **“[!UICONTROL Itens de trabalho deste projeto]” foi restaurado no [!UICONTROL Balanceador de carga de trabalho]** do projeto

*[!UICONTROL Balanceador de carga de trabalho]*

Restauramos o filtro “Itens de trabalho deste projeto” na área [!UICONTROL Atribuído] ao acessar o [!UICONTROL Balanceador de carga de trabalho] de um projeto.

Esse filtro agora está listado abaixo da seção “[!UICONTROL Sugerido]” dos filtros da área [!UICONTROL Trabalho atribuído] do [!UICONTROL Balanceador de carga de trabalho] de um projeto.

+++

## Atualizações em junho de 2022

+++**Atualização de manutenção em 30 de junho de 2022**

**Exibir o [!UICONTROL Balanceador de carga de trabalho] por uma semana**

*[!UICONTROL Balanceador de carga de trabalho]*

Com base no feedback que recebemos de muitos clientes, agora adicionamos uma opção para visualizar o [!UICONTROL Balanceador de carga de trabalho] por uma semana. Antes dessa atualização, você poderia visualizar o [!UICONTROL Balanceador de carga de trabalho] por 4, 6 e 12 semanas. Com esta atualização, também alteramos a opção de 12 semanas para 3 meses.

**O painel Delegar agora está disponível no Balanceador de carga de trabalho**

*[!UICONTROL Balanceador de carga de trabalho]*

OBSERVAÇÃO: essa atualização existe somente no ambiente de Pré-visualização. A funcionalidade associada a esta atualização estará disponível na Produção com a versão 22.3.

Agora é possível visualizar os delegados de uma tarefa ou problema no Balanceador de carga de trabalho. Ao atribuir uma tarefa ou um problema do Balanceador de carga de trabalho, você pode visualizar uma lista de atribuições, bem como uma lista de delegados para a tarefa ou problema, se eles estiverem delegados no momento.

**Não é possível abrir informações do ponto de extremidade no API Explorer**

*API*

Quando um usuário visualiza o [!DNL API Explorer] e clica em um ponto de extremidade, as informações do ponto de extremidade não são exibidas.

**Problemas com o botão [!UICONTROL Detalhes] ao usar o [!UICONTROL Calendário da página inicial]**

*Página inicial*

Quando um usuário estiver usando o [!UICONTROL Calendário da página inicial] e clicar em uma tarefa, uma das situações a seguir poderá ocorrer:

* O botão [!UICONTROL Detalhes] aparece brevemente e depois desaparece. O usuário não consegue acessar os detalhes.
* O botão [!UICONTROL Detalhes] não é exibido. O usuário não consegue acessar os detalhes.
* O botão [!UICONTROL Detalhes] é exibido, mas não está no local correto. O usuário consegue clicar no botão para acessar os detalhes.

+++

+++**Atualização de manutenção (hotfix) em 24 de junho de 2022**

**O seletor de datas não fecha ao editar o formulário personalizado**

*Formulários personalizados*

Quando um usuário edita um formulário personalizado e tenta alterar uma data, o seletor de datas não fecha quando a data é selecionada. O usuário não consegue fechar o seletor de datas salvando, cancelando ou clicando fora dele.

Esse problema foi relatado nas seguintes áreas:

* Área de [!UICONTROL Atualizações]
* [!UICONTROL Página inicial]

**O usuário não consegue se mover para outro estágio de uma prova**

*Provas*

Quando um usuário está visualizando o [!UICONTROL Fluxo de trabalho de prova] de uma prova e tenta ir para um estágio diferente da prova, o nome do usuário se ajusta de volta ao estágio original e ele não é adicionado ao estágio desejado.

+++

+++**Atualização de manutenção em 23 de junho de 2022**

**[!UICONTROL Não é possível adicionar nova solicitação através do painel]**

*Painéis*

Quando um usuário está visualizando um painel em um projeto e tenta adicionar uma nova solicitação clicando no botão [!UICONTROL +Nova solicitação], o botão não responde e o usuário não consegue adicionar uma nova solicitação.

**Erro ao visualizar itens na Lista de trabalho da página inicial**

*[!UICONTROL Página inicial]*

Quando um usuário visualiza a [!UICONTROL Lista de trabalho da página inicial] e clica em um item na seção [!UICONTROL Aprovações que enviei], a página exibe o seguinte erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

Se o usuário atualizar a página e clicar em qualquer item na [!UICONTROL Lista de trabalho], o erro aparece. O problema não afeta mais somente os itens na seção [!UICONTROL Aprovações que enviei].

**A seção personalizada em um objeto inclui resultados que não estão nesse objeto**

*Objetos*

Quando um usuário visualiza uma seção [!UICONTROL personalizada] em um objeto, a seção personalizada exibe itens que não fazem parte desse objeto. Isso foi relatado quando a seção personalizada é adicionada diretamente ao objeto e quando uma seção personalizada é adicionada por meio de um modelo de layout.

**As tarefas são movidas para um projeto incorreto**

*Tarefas*

Quando um usuário move tarefas do Projeto A para o Projeto B e, em seguida, move mais tarefas do Projeto A para o Projeto C, as tarefas originalmente movidas para o Projeto B aparecem no Projeto C.

**Alguns botões/ícones não funcionam ao acessar o [!UICONTROL Balanceador de carga de trabalho] de um link ou painel compartilhado**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário acessa o [!UICONTROL Balanceador de carga de trabalho] por um link compartilhado ou um link em um painel e tenta usar o elemento na parte superior da tela, os elementos não funcionam. Esse problema foi relatado para os seguintes elementos:

* [!UICONTROL Hoje]
* Setas para trás e para a frente
* [!UICONTROL Semanas]
* Ícone de calendário (seletor de datas)

+++

+++**[!DNL Workfront]Atualização de manutenção do planejador de cenário em 23 de junho de 2022**

**Usuários com permissões para [!UICONTROL Gerenciar] um plano podem compartilhá-lo com outras pessoas**

Como um usuário com permissões para [!UICONTROL Gerenciar] um plano no [!DNL Scenario Planner], agora você pode compartilhá-lo com outros usuários. Antes desta atualização, somente o criador do plano poderia compartilhar o plano com outros usuários..

+++

+++**Atualização de manutenção em 16 de junho de 2022**

**O administrador de grupo não consegue adicionar membros ao grupo**

*Grupos*

Quando um administrador de grupo tenta adicionar um usuário a um grupo, a lista suspensa para selecionar o usuário não é preenchida. O administrador do grupo não consegue selecionar nenhum usuário e, portanto, não pode adicionar nenhum usuário ao grupo.

**Trimestres personalizados não aparecem ao definir um filtro**

*Filtros*

Quando um usuário cria um filtro e filtra por um campo de data, a lista suspensa de operadores disponíveis para o campo de data não inclui trimestres personalizados adicionados recentemente.

**Erro ao converter um problema em um projeto por meio de um modelo**

*Projetos*

Quando um usuário tenta converter um problema em um projeto por meio de um modelo e o problema tem um formulário personalizado que contém uma seção somente de administrador, o problema não é convertido e o usuário vê o seguinte erro:

“[!UICONTROL Vamos tentar novamente. Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

**As solicitações são enviadas sem os campos obrigatórios preenchidos**

*Solicitações*

Quando um usuário cria uma solicitação e não preenche os campos obrigatórios e, em seguida, envia a solicitação, a solicitação é enviada sem dados nos campos obrigatórios. O comportamento esperado é que a solicitação não seja enviada e que o usuário seja notificado de que precisa preencher os campos obrigatórios antes de enviar a solicitação.

**Novos trimestres personalizados parecem não ser salvos**

*Configuração*

Quando um usuário está adicionando um novo trimestre personalizado da área Projetos da Configuração e clica em [!UICONTROL Salvar], não há nenhuma indicação visual do salvamento. O usuário não vê uma mensagem de sucesso e o botão [!UICONTROL Salvar] ainda está presente e ativo. No entanto, se o usuário atualizar a página, poderá ver que os novos trimestres aparecem na lista de trimestres personalizados.

Se o usuário adicionar um novo trimestre, clicar em [!UICONTROL Salvar], não receber nenhuma indicação do salvamento, adicionar outro trimestre sem atualizar a página e clicar em [!UICONTROL Salvar] novamente, o segundo trimestre adicionado pode não ser salvo.

A página **[!UICONTROL Solicitações de trabalho da equipe] está em branco**

*Equipes*

OBSERVAÇÃO: esse problema existe apenas no ambiente de Pré-visualização.

Quando um usuário tenta abrir a área [!UICONTROL Solicitações de trabalho] em uma página da equipe, a página fica em branco. O usuário consegue visualizar a barra de navegação superior, mas nenhum conteúdo da página.

+++

+++** Atualização de manutenção em 9 de junho de 2022**

**Não é possível selecionar objetos para filtrar nas preferências do [!UICONTROL Otimizador de portfólios]**

*Portfólios*

Quando um usuário está no [!UICONTROL Otimizador de portfólios] e visualiza a guia [!UICONTROL Filtros do projeto] na área [!UICONTROL Preferências], as caixas de seleção ao lado dos objetos não aparecem. O usuário não consegue marcar ou desmarcar caixas e, portanto, não pode selecionar objetos para filtrar.

**Não é possível alterar a [!UICONTROL Data inicial planejada] ou a [!UICONTROL Data de conclusão planejada] quando “[!UICONTROL Agendar de]” não está marcado**

*Projetos*

Quando um usuário tenta editar a [!UICONTROL Data inicial planejada] ou a [!UICONTROL Data de conclusão planejada] de um projeto e a opção “[!UICONTROL Agendar de]” para esse projeto não estiver marcada, as áreas [!UICONTROL Data inicial planejada] e [!UICONTROL Data de conclusão planejada] estão desativadas e o usuário não pode editar essas datas.

**Não é possível editar o nível de acesso dos usuários**

*Usuários*

Quando um usuário com acesso de Planejador que inclui o acesso de Administrador de usuário (usuários de grupo) tenta editar os usuários no grupo para o qual são administradores, o campo [!UICONTROL Nível de acesso] está desativado e o usuário não pode editar o nível de acesso.

+++

+++**[!DNL Workfront Scenario Planner] Atualização de manutenção em 9 de junho de 2022**

**Painel esquerdo redimensionável no [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Agora é possível redimensionar o painel esquerdo em um Plano no [!DNL Scenario Planner]. Isso permite que nomes de iniciativas mais longos sejam totalmente exibidos. Antes dessa atualização, nomes de iniciativa mais longos eram truncados.

+++

+++**[!DNL Workfront Fusion] Atualização de manutenção em 9 de junho de 2022**

**Dados de formulários personalizados não estão disponíveis em módulos do [!DNL Workfront Fusion] [!DNL Workfront]**

*[!DNL Workfront Fusion]*

Quando um usuário está configurando um módulo do [!DNL Workfront] no [!DNL Workfront Fusion] e tenta selecionar saídas para o módulo, os campos de formulários personalizados não estão visíveis. Isso ocorre quando o formulário personalizado foi criado para um tipo de objeto do [!DNL Workfront] e outro tipo foi adicionado a ele. O [!DNL Workfront Fusion] exibe somente campos de formulários personalizados originalmente criados para o tipo de objeto selecionado.

**Não é possível rolar a tela para exibir todas as execuções de cenário**

*[!DNL Workfront Fusion]*

Quando um usuário exibe o histórico de execução de um cenário e tenta rolar a tela para baixo para visualizar mais execuções, as execuções param de ser carregadas e o usuário não consegue visualizá-las. Além disso, o usuário não consegue voltar para as execuções mais recentes.

+++

+++**Atualização de manutenção em 2 de junho de 2022**

O **[!UICONTROL Otimizador de portfólios] mostra uma pontuação de 0 ao usar um idioma diferente do inglês**

*Portfólios*

Quando um usuário estiver usando o [!DNL Workfront] em um idioma diferente do inglês e visualiza o [!UICONTROL Otimizador de portfólios], a pontuação será exibida como 0. Isso pode ocorrer mesmo quando o business case não estiver completo.

**Valores de campo calculados incorretos ao criar projeto a partir do modelo**

*Projetos*

Quando um usuário cria um projeto a partir de um modelo que inclui campos calculados, os valores de campo que aparecem no novo projeto estão incorretos.

**Não é possível editar [!UICONTROL Condições] na área [!UICONTROL Preferências do projeto] da [!UICONTROL Configuração]**

*[!UICONTROL Configuração]*

Quando um usuário tenta editar as [!UICONTROL Condições] na área [!UICONTROL Preferências do projeto] da [!UICONTROL Configuração], a página fica em branco.

**Nova limitação ao número de caracteres em uma atualização na Pré-visualização**

*[!UICONTROL Balanceador de carga de trabalho]*

>[!NOTE]
>
>Essa atualização se aplica somente ao ambiente de Pré-visualização.

Para melhorar o desempenho da área Atualizações, introduzimos um novo limite para o número de caracteres que podem ser inseridos em uma atualização ou em uma resposta a uma atualização existente. O novo limite é de 15.000 caracteres. Essa atualização não alterou o número de caracteres permitidos ao usar a API. O limite de caracteres da API para atualizações é 4.000. Atualizações 
Suporte para campos personalizados do tipo digitação antecipada em filtros do Balanceador de carga de trabalho

Agora oferecemos suporte a filtros com base nos campos personalizados do tipo [!UICONTROL Digitação antecipada] no Balanceador de carga de trabalho. Antes deste patch, a filtragem desse tipo de campo personalizado não era possível no Balanceador de carga de trabalho.

**Não é possível editar permissões na função de um usuário**

*[!DNL Workfront Proof]*

Quando um usuário tenta editar as permissões “[!UICONTROL Resolver comentários e aplicar ações]” ou “[!UICONTROL Compartilhar uma prova marcando]” na função de um usuário no [!DNL Workfront Proof], as alterações não são salvas. O usuário recebe uma notificação de que o modelo foi atualizado, mas se o usuário abrir as permissões de função novamente, poderá ver que as alterações não foram salvas.

+++


## Atualizações em maio de 2022

+++**Atualização de manutenção em 26 de maio de 2022**

Esses problemas foram corrigidos somente na nova experiência do [!DNL Workfront]. O [!DNL Adobe Workfront Classic] não é mais compatível.

Todas as funcionalidades do [!DNL Workfront Classic] serão removidas em julho de 2022. Faça a transição para a nova experiência o mais rápido possível.

**Separadores de navegação estrutural atualizados**

*[!DNL Workfront]*

OBSERVAÇÃO: essa atualização foi lançada em 24 de maio de 2022.

Atualizamos os separadores de navegação estrutural em todas as áreas em que há navegação estrutural disponível. Agora, os objetos na navegação estrutural são separados por barras verticais (|). Antes dessa atualização, eles eram separados por barras (/).

**Não é possível editar formulários personalizados com quebras de seção**

*Formulários personalizados*

Ao tentar editar um formulário personalizado com uma quebra de seção, o usuário não consegue editar o formulário e vê a seguinte mensagem:

[!UICONTROL A segurança de quebra de seção especificada não pode ser aplicada em todos os tipos de objeto]

**Problemas ao imprimir painéis no PDF**

*Painéis*

Os seguintes problemas foram relatados ao imprimir um painel em um PDF: 
O PDF não imprime todas as linhas no relatório. Quando as linhas não aparecerem, somente será exibido um espaço em branco.
O PDF inclui espaços em branco entre os cabeçalhos da coluna e a primeira linha do relatório.

O **[!DNL Portfolio Optimizer] mostra uma pontuação de 0 ao usar um idioma diferente do inglês**

*Portfólios*

Quando um usuário estiver usando o [!DNL Workfront] em um idioma diferente do inglês e visualiza o [!UICONTROL Otimizador de portfólios], a pontuação será exibida como 0. Isso pode ocorrer mesmo quando o business case não estiver completo.

**Alguns formulários personalizados não são exibidos ao editar um modelo**

*Modelos*

Quando um usuário tenta editar os formulários personalizados em um modelo clicando em [!UICONTROL Editar] no cabeçalho do modelo, a janela [!UICONTROL Editar modelo] exibe somente um dos formulários personalizados anexados ao modelo.

**O link compartilhado para o Balanceador de carga de trabalho exibe o trabalho atribuído incorretamente**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário visualiza o [!UICONTROL Balanceador de carga de trabalho] usando um link compartilhado, o [!DNL Workload Balancer] inclui o [!UICONTROL Trabalho atribuído] na seção [!UICONTROL Trabalho não atribuído]. O [!UICONTROL Trabalho atribuído] não tem uma seção separada. Quando o usuário visualiza o [!UICONTROL Balanceador de carga de trabalho] sem usar o link compartilhado, o [!UICONTROL Trabalho atribuído] é exibido conforme esperado.

+++

+++**Atualização de manutenção em 19 de maio de 2022**

**Não é possível criar uma prova a partir de um [!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Quando um usuário tenta criar uma prova a partir de um [!DNL PowerPoint] que inclui um gráfico, a criação da prova falha.

**Não é possível criar uma prova de um documento do [!UICONTROL Word]**

*[!DNL Workfront Proof]*

Quando um usuário tenta criar uma prova de um documento do [!DNL Word] que inclui um gráfico, ocorre uma falha na criação da prova.

**Não é possível adicionar uma mensagem personalizada ao compartilhar uma prova**

*[!DNL Workfront Proof]*

Quando um usuário está visualizando uma prova, abre a área [!UICONTROL Compartilhar prova] e clica no botão [!UICONTROL Adicionar mensagem personalizada], não é possível digitar na caixa de texto que é exibida. Quando o usuário tenta digitar nessa caixa, ela imediatamente desaparece.

**Não é possível fechar a prova**

*[!DNL Workfront Proof]*

Quando um usuário visualiza uma prova e tenta fechá-la, o X para fechar a prova não aparece no canto superior direito da prova.

**Não é possível adicionar ou remover o administrador de grupo**

*Grupos*

Se um usuário estiver visualizando uma página de [!UICONTROL Grupo] e tenta adicionar ou remover um administrador de grupo usando a área [!UICONTROL Administradores de grupo] no cabeçalho, as alterações não são salvas e o usuário vê o seguinte erro:

[!UICONTROL Erro! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]

**A barra de rolagem horizontal bloqueia o item no final da lista**

*Projetos*

Quando um usuário está visualizando uma lista usando uma exibição que se estende para fora da tela, a barra de rolagem horizontal bloqueia a exibição do último item na lista.

**“[!UICONTROL Erro inesperado]” ao converter um problema em um projeto usando um modelo**

*Listas*

Quando um usuário tenta converter um problema em um projeto usando um modelo, o problema não é convertido e o usuário vê a seguinte mensagem:

[!UICONTROL Ocorreu um erro inesperado: ]

**O campo [!UICONTROL Status] em uma visualização de folha de horas agora é somente leitura**

*Folhas de horas*

Mudamos o campo [!UICONTROL Status] em uma visualização de folha de horas para somente leitura. Antes dessa alteração, os usuários podiam editar o status em linha de uma folha de horas que permitia que eles substituíssem a decisão dos aprovadores da folha de horas.

+++

+++**Atualização de manutenção em 12 de maio de 2022**

O botão **[!UICONTROL Salvar] não interrompe o carregamento ao editar um projeto**

*Projetos*

Quando um usuário edita um projeto e tenta salvar, ele observa que o botão [!UICONTROL Salvar] exibe a palavra “[!UICONTROL Carregando].” Se o usuário clicar nesse botão para salvar as alterações no projeto, o botão não responderá e as alterações não serão salvas.

**Os rótulos de campo não aparecem ao visualizar um objeto na [!UICONTROL Página inicial]**

*Página inicial*

Quando um usuário seleciona um objeto da [!UICONTROL Lista de trabalho da página inicial], a área à direita da [!UICONTROL Lista de trabalho da página inicial] que exibe o objeto não inclui rótulos de campo. Os valores de campo estão presentes.

**O Filtro rápido não se concentra automaticamente na barra de pesquisa**

*Listas*

Quando um usuário está em uma lista, clica na lupa para filtrar rapidamente e, em seguida, começa a digitar, o texto não é exibido. Isso ocorre porque o foco permanece no ícone da lupa em vez de transferir para a barra de pesquisa.

Clicar na barra de pesquisa transfere o foco e permite que o usuário insira o texto de sua pesquisa.

**Usuários não conseguem editar campos em um relatório**

*Relatórios*

Quando um usuário tenta editar um campo em um relatório e ele é extraído de um formulário personalizado, o campo não pode ser editado. Isso ocorre quando o formulário personalizado foi criado originalmente para um tipo de objeto diferente do objeto ao qual ele está anexado.

**Rótulo e texto de botão não visíveis ao criar uma prova**

*[!DNL Workfront Proof]*

OBSERVAÇÃO: esse problema existe apenas no ambiente de Pré-visualização.

Quando um usuário tenta criar uma prova, o texto não fica visível para opções ou botões. Portanto, o usuário não sabe o que cada opção ou botão representa e não pode configurar a prova.

+++

+++**Atualização de manutenção em 5 de maio de 2022**

**Não é possível adicionar um novo Registro de faturamento**

*Projetos*

Quando um usuário está na área [!UICONTROL Registros de cobrança] de um projeto e está usando a visualização [!UICONTROL Novo registro de cobrança], se o usuário tentar adicionar um novo Registro de cobrança, os campos de um novo Registro de cobrança não aparecerão e o Registro de cobrança não poderá ser criado.

**Erro ao fazer atribuição em massa no [!UICONTROL Balanceador de carga de trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário tenta fazer atribuições no [!DNL Workload Balancer] de um projeto, o usuário é redirecionado para uma página com a seguinte mensagem:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

O usuário não consegue sair desta página até atualizar a página.

**Navegação atualizada para abrir o painel [!UICONTROL Resumo] para tarefas e problemas no [!UICONTROL Balanceador de carga de trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Agora, basta clicar em uma barra de tarefas ou problemas no [!UICONTROL Balanceador de carga de trabalho] para abrir o Painel de resumo. Antes desta atualização, você tinha que clicar no ícone [!UICONTROL Abrir resumo] na barra de ferramentas e, em seguida, clicar na tarefa ou problema. Esta experiência era confusa e foi corrigida. Como alternativa, você pode clicar no botão [!UICONTROL Mais] ao lado do nome da tarefa ou do problema e clicar em [!UICONTROL Abrir resumo].

**O administrador de grupo não consegue visualizar detalhes dos usuários no grupo**

*Usuários*

Quando um usuário é atribuído a um nível de acesso que inclui a variável [!UICONTROL Administrador do usuário (usuários do grupo)], as tentativas de configuração de acesso para exibir detalhes de um usuário em seu grupo exibem o seguinte erro:

“[!UICONTROL Vamos tentar novamente. Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

**Não é possível excluir o status do grupo personalizado**

*Grupos*

Quando um usuário tenta excluir um status de grupo personalizado da página [!UICONTROL Grupo], a página fica em branco e o status não é excluído.

**As configurações de alerta de email são inconsistentes entre a área Contatos e Detalhes do usuário**

*[!DNL Workfront Proof]*

As configurações de alerta de email exibidas na área [!UICONTROL Contatos] do [!DNL Workfront Proof] para um determinado usuário são diferentes da configuração de alerta por email definida nos [!UICONTROL Detalhes do usuário].

**Não é possível usar a ferramenta Texto ao fazer um comentário em uma prova**

*[!DNL Workfront Proof]*

Quando um usuário faz um comentário em uma prova e tenta abrir a ferramenta [!UICONTROL Texto], a ferramenta não abre e o usuário vê a seguinte mensagem:

“[!UICONTROL Os dados de texto desta página ainda estão sendo baixados. Aguarde.]”

**Os emails de prova irão para o email principal do usuário**

*[!DNL Workfront Proof]*

Estamos fazendo ajustes em como as notificações por email de prova são enviadas. Agora, as notificações vão para o endereço de email principal do usuário, em vez do email de alias gerado pelo sistema.

Para obter mais informações sobre por que o sistema gera emails de alias, consulte Sincronização do usuário entre o Adobe [!DNL Workfront] e o [!DNL Workfront Proof].

+++

## Atualizações em abril de 2022

+++**Atualização de manutenção em 28 de abril de 2022**

**Não é possível rolar a tela até o botão [!UICONTROL Salvar] ao editar uma folha de horas**

*Folhas de horas*

Quando um usuário está editando uma folha de horas, ele não pode rolar a janela de edição o suficiente para ver o botão [!UICONTROL Salvar] e, portanto, não pode editar a folha de horas.

**A assinatura eletrônica agora verifica a ID da Federação**

*Provas*

Ao assinar uma prova eletronicamente, o sistema agora verifica a ID da Federação, caso você tenha o SSO configurado no [!DNL Workfront Proof], além do email no [!DNL Workfront].

Anteriormente, o sistema verificava somente seu email no Workfront.

+++

+++**Atualização de manutenção (hotfix) em 25 de abril de 2022**

O **[!UICONTROL Balanceador de carga de trabalho] não carrega**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário tenta abrir o [!UICONTROL Balanceador de carga de trabalho], o cabeçalho e a navegação à esquerda carregam, mas o conteúdo do Balanceador de carga de trabalho não carrega. O usuário vê quadrados cinza piscando em vez de dados. Ocasionalmente, parte do conteúdo é carregada, mas o usuário ainda vê quadrados cinza piscando, onde os dados ausentes estariam.

+++

+++**Atualização de manutenção em 21 de abril de 2022**

**Adicionar uma tarefa faz com que a página salte para baixo**

*Tarefas*

Quando um usuário adiciona uma tarefa abaixo de uma tarefa existente em uma lista, a página salta para baixo na lista. Embora a nova tarefa esteja no local correto, o usuário deve rolar a tela de volta para localizá-la.

**Os usuários adicionados a uma prova não conseguem acessar o item de trabalho da prova no [!DNL Workfront]**

*Provas*

Se um usuário for adicionado a um estágio no fluxo de trabalho de uma prova, ele não será adicionado ao Compartilhamento de documentos e não obterá permissões para o item de trabalho da prova no [!DNL Workfront]. Quando o usuário estiver no [!DNL Workfront] e tentar abrir o item de trabalho ao qual a prova está anexada, verá a seguinte mensagem:

“[!UICONTROL Você não tem acesso suficiente para visualizar este (objeto)]”

Esse problema é específico para provas já criadas e usuários adicionados após o fato. Adicionar usuários ao fluxo de trabalho antes da criação da prova funciona conforme esperado.

**Não é possível enviar email de redefinição de senha a partir do [!DNL Workfront]**

*Usuários*

Quando um usuário tenta enviar um email de redefinição de senha a partir de uma lista de usuários no [!DNL Workfront], a opção para enviar o email não está disponível.

**O botão exibe “[!UICONTROL Iniciar problema]” em vez de “[!UICONTROL Iniciar solicitação]”**

*Solicitações*

Quando um usuário visualiza uma solicitação atribuída à equipe, ele vê o botão “[!UICONTROL Iniciar problema]” no cabeçalho em vez do botão “[!UICONTROL Iniciar solicitação]”.

A opção **“[!UICONTROL Desfazer comentário]” remove os usuários marcados**

*Atualizações*

Quando um usuário marca outro usuário em um comentário, publica esse comentário e, em seguida, seleciona a opção “[!UICONTROL Desfazer comentário]”, o comentário aparece em uma caixa de atualização como de costume, mas o usuário marcado não está na caixa [!UICONTROL Usuários marcados].

**Não é possível rolar a tela ao usar a visualização de [!UICONTROL Marco] em um relatório**

*Relatórios*

Quando um usuário visualiza um relatório e seleciona a visualização de [!UICONTROL Marco], a página exibe a visualização do Marco, mas não pode ser mais rolada, e o usuário não pode visualizar os marcos que estariam mais abaixo na página.

**Moeda incorreta quando o relatório é exibido no painel**

*Relatórios*

Quando um usuário visualiza um relatório em um painel, a moeda usada no relatório está incorreta. Quando o usuário visualiza o relatório fora do painel, a moeda está correta.

**O filtro concluído não exibe os itens de trabalho concluído**&#x200B; s

*[!UICONTROL Página inicial]*

Quando um usuário visualiza a [!UICONTROL Lista de trabalho da página inicial] com o filtro [!UICONTROL Concluído] selecionado, os itens de trabalho concluídos não são exibidos na lista. Quando o filtro [!UICONTROL Todos] está selecionado, os itens Concluídos são incluídos na lista, mostrando que os itens Concluídos existem.

O **[!DNL Workfront]não carrega**

*[!DNL Workfront]*

Quando um usuário tenta fazer logon no [!DNL Workfront], a página parece estar presa em um loop de redirecionamentos ou atualizações e não é carregada.

+++

+++**Atualização de manutenção em 14 de abril de 2022**

**Não é possível adicionar uma tarefa de um relatório em uma seção personalizada em uma tarefa**

*Tarefas*

Quando um usuário exibe uma seção personalizada em uma tarefa e a seção contém um relatório de tarefa, o usuário não consegue adicionar uma tarefa a partir desse relatório. O botão [!UICONTROL Adicionar tarefa] realça o relatório, mas não abre uma janela para o usuário adicionar uma tarefa.

**Botão Concluído no local errado ao editar uma visualização**

*Visualizações*

Quando um usuário edita uma visualização, o botão [!UICONTROL Concluído] aparece mais alto na tela e pode sobrepor o texto.

O usuário pode editar a visualização como de costume. A funcionalidade não é afetada.

**Não é possível rolar a tela ao usar a visualização de [!UICONTROL Marco] em um relatório**

*Relatórios*

Quando um usuário visualiza um relatório e seleciona a visualização de [!UICONTROL Marco], a página exibe a visualização do Marco, mas não pode ser mais rolada, e o usuário não pode visualizar os marcos que estariam mais abaixo na página.

**Tela em branco ao visualizar atualizações**

*Atualizações*

Quando um usuário está visualizando atualizações e rola a tela para exibi-las ainda mais para baixo, a tela fica em branco e o usuário não pode visualizar nenhuma atualização.

**Erro ao atribuir o usuário em massa à tarefa que não está atribuída à função do usuário**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário no [!UICONTROL Balanceador de carga de trabalho] tenta atribuir tarefas a um usuário cuja Função de trabalho não corresponde à Função de trabalho atribuída às tarefas, o usuário vê uma mensagem de que a tarefa será atribuída usando a Função de trabalho principal do usuário atribuído. No entanto, quando o usuário clica em “[!UICONTROL Atribuir]”, as tarefas não são atribuídas e o usuário vê o seguinte erro:

“[!UICONTROL Erro. O servidor encontrou um erro desconhecido.]”

+++

+++**Atualização de manutenção em 7 de abril de 2022**

**Os usuários adicionados às provas têm funções incorretas**

*Provas*

Quando um usuário adiciona outro usuário a uma prova, a função dele na prova é definida como “[!UICONTROL Somente leitura]” apesar da função de prova real do usuário.

**Não é possível enviar email de redefinição de senha para o usuário**

*Usuários*

Quando um usuário tenta enviar uma redefinição de senha para outro usuário, ele vê que a opção [!UICONTROL Enviar email de esquecimento de senha] não está disponível no menu [!UICONTROL Mais].

**[!UICONTROL Atualizar tudo] envia atualizações para perfis de usuário em vez do projeto**

*Atualizações*

Quando um usuário visualiza a área [!UICONTROL Pessoas] de um projeto, seleciona a opção [!UICONTROL Atualizar tudo] e insere uma atualização, a atualização não é postada no próprio projeto. Em vez disso, é publicado nos perfis de usuário individuais de cada usuário no projeto.

**Número excessivo de páginas ao imprimir atualizações**

*Atualizações*

Quando um usuário está visualizando um fluxo de atualização que seria mais de uma página impressa e tenta imprimir a página, a tela de impressão mostra que o número de páginas está muito acima do número real de páginas necessárias para imprimir as atualizações. Se o usuário tentar imprimir no PDF, a criação do PDF falhará.

**Os usuários não podem ver toda a lista de entidades compartilhadas com um relatório quando a configuração “[!UICONTROL Visível em todo o sistema]” está ativada**

*Relatórios*

Ao compartilhar relatórios com várias entidades que exibem a caixa [!UICONTROL Acesso ao relatório], os usuários não conseguem rolar a tela para a parte inferior da lista para ver toda a lista quando a configuração “[!UICONTROL Visível em todo o sistema]” está ativada.

**Moeda incorreta usada em relatórios**

*Relatórios*

Se um usuário definir que a moeda de um projeto será diferente da moeda padrão e, em seguida, visualizar um relatório sobre esse projeto, a moeda será exibida como a moeda padrão em vez da moeda do projeto.

**As Últimas informações visualizadas não são atualizadas nos relatórios [!UICONTROL Uso de relatórios]**

*Relatórios*

Quando um usuário visualiza um relatório que exibe informações sobre a última vez que o relatório foi visualizado, essas informações podem estar em branco ou ser dados antigos. Esse problema afeta campos, incluindo o seguinte:

* [!UICONTROL Última Visualização realizada por]
* [!UICONTROL Últimos dados visualizados]
* [!UICONTROL Últimos X visualizadores]
* [!UICONTROL Visualizações neste mês/trimestre/ano]

**As tarefas concluídas são exibidas na [!UICONTROL Lista de trabalho da página inicial]**

*[!UICONTROL Página inicial]*

Ao visualizar a [!UICONTROL Lista de trabalho da página inicial], o usuário vê as tarefas concluídas na lista, mesmo quando a opção para exibir tarefas concluídas não está selecionada.

**O botão Agendar não está visível para agendar a atualização da sandbox**

*Ambiente de sandbox*

O botão [!UICONTROL Agendar] usado para programar uma atualização da sandbox não está visível no banner superior do ambiente da sandbox.

**As alterações em um campo calculado afetam todos os campos calculados em um formulário**

*Formulários personalizados*

Quando um usuário está no Construtor de formulários personalizado e altera o valor de um formulário calculado, todos os campos calculados no formulário mostram o novo valor. Esse problema pode afetar campos calculados novos ou existentes.

**As cores ficam piscando no construtor de formulários personalizados**

*Formulários personalizados*

Quando um usuário está trabalhando com campos calculados no construtor de formulários personalizado, as cores dos campos e expressões piscam.

**[!UICONTROL Não é possível rejeitar uma aprovação]**

*Aprovações*

Quando um usuário tenta rejeitar uma aprovação, o campo [!UICONTROL Rejeitar] não responde, e a aprovação não é rejeitada.

A guia **[!UICONTROL Projetos] é padronizada para a seção Todos os projetos apesar da seleção anterior**

*Projetos*

Quando um usuário acessa uma página de Projetos por meio de uma guia que foi fixada como parte do modelo de layout, a página é padronizada para a área [!UICONTROL Todos os projetos] da navegação à esquerda. Isso ocorre mesmo quando o usuário escolhe outra área da navegação à esquerda e, em seguida, navega para fora da página Projetos e para trás.

+++


## Atualizações em março de 2022

+++**Atualização de manutenção em 31 de março de 2022**

**Os fusos horários não são consistentes entre o [!DNL Workfront] e [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando o perfil de um usuário é definido com um fuso horário específico no [!DNL Workfront], o fuso horário do usuário no [!DNL Workfront Proof] é definido como um fuso horário diferente.

**O link para enviar um documento solicitado abre uma página em branco**

*Documentos*

Quando um usuário recebe uma solicitação para enviar um documento e clica no link para o objeto no qual o documento foi solicitado, o link abre uma página em branco. Isso pode ocorrer ao clicar em um link em um email ou em uma notificação no aplicativo.

**O grupo é atribuído incorretamente ao converter o problema em projeto**

Grupos

Quando um usuário converte um problema em um projeto usando um modelo, a funcionalidade é:

* Se o modelo tiver um grupo atribuído, esse grupo será exibido na janela de conversão de problemas como o grupo para o novo projeto.
* Se o modelo não tiver nenhum grupo atribuído, o grupo padrão do usuário que está convertendo o problema será exibido na janela de conversão do problema como o grupo do novo projeto.
* Se o modelo não tiver um grupo, o novo projeto deve herdar o grupo do projeto do problema.

**Não é possível anexar um formulário personalizado entre objetos à fila de solicitações**

Solicitações

Quando um usuário tenta adicionar um formulário personalizado entre objetos à página de detalhes de uma fila, o formulário entre objetos não é exibido na lista suspensa de formulários disponíveis e o usuário não pode selecioná-lo para adicioná-lo aos detalhes da fila.

**Os usuários não podem ser atribuídos com a função de trabalho secundário no [!UICONTROL Balanceador de carga de trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário tenta atribuir outro usuário a uma tarefa no [!UICONTROL Balanceador de carga de trabalho] e a tarefa é atribuída a uma função de trabalho diferente da função de trabalho principal do usuário atribuído, o usuário será atribuído à tarefa pela função de trabalho principal e a seguinte mensagem será exibida:

“&lt;Name> não corresponde à função de &lt;Task role assignment>. 1 item de trabalho atribuído à função de &lt;Task role assignment> será atribuído a &lt;Name> na função de &lt;Primary job role>.”

Isso ocorre mesmo se o usuário tiver a função de tarefa da atribuição de função de tarefa como uma função de trabalho secundária.

**Problema com a barra “Mostrar mais itens de trabalho” do quadro Scrum**&#x200B;

*Ágil*

Quando um usuário clica na barra [!UICONTROL Mostrar mais itens de trabalho] em um Quadro Scrum e rola a tela para ver os novos itens, a barra [!UICONTROL Mostrar mais itens de trabalho] fica presa no Quadro Scrum e se move com ele ao rolar a tela. Isso pode dificultar a leitura dos cartões.

**Pontos vermelhos são exibidos nos campos obrigatórios em formulários personalizados**

Formulários personalizados

Quando um usuário exibe um campo obrigatório em um formulário personalizado, ele vê dois pontos vermelhos abaixo do asterisco que indica que o campo é obrigatório.

**Lista suspensa de tempo cortada em prompts**

*Relatórios*

Quando um usuário está preenchendo as solicitações de um relatório e encontra um seletor de datas, o seletor de tempo na parte inferior do seletor de datas não exibe horas além de 2 e o usuário não pode selecionar nenhum valor de hora além de 1 ou 2.

+++

+++**Atualização de manutenção (hotfix) em 29 de março de 2022**

**Não é possível modificar ou salvar cálculos no Criador de formulários personalizado**

*Formulários personalizados*

Se um usuário insere manualmente um cálculo em um campo de cálculo no construtor de Formulários personalizados e salva o formulário, o cálculo não é salvo. Se o usuário reabrir o formulário personalizado, esse campo ficará em branco.

Se um usuário digitar um cálculo em um campo de cálculo no Criador de formulários personalizado usando os menus suspensos e salvar o formulário, esse valor será salvo. No entanto, se o usuário reabrir o formulário personalizado, não poderá editar esse campo ou remover o valor manualmente ou com a lista suspensa.

OBSERVAÇÃO: essa correção de problema incluía funcionalidade adicional. Agora, quando você começa a digitar em um campo calculado, expressões possíveis ou cálculos são exibidos em uma lista suspensa abaixo, da mesma forma que no Editor de cálculos. Clique em um item na lista suspensa para adicioná-lo ao campo calculado.

+++

+++**Atualização de manutenção em 24 de março de 2022**

**Os fusos horários não são consistentes entre o [!DNL Workfront] e [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando o perfil de um usuário é definido com um fuso horário específico no [!DNL Workfront], o fuso horário do usuário no [!DNL Workfront Proof] é definido como um fuso horário diferente.

**Erro de campo obrigatório para campos personalizados preenchidos ao anexar um modelo**

*Projetos*

Ao anexar um modelo com campos personalizados obrigatórios a um projeto em que o campo já existe e está preenchido, os usuários veem o seguinte erro: “[!UICONTROL Há campos incompletos. Insira valores para os campos obrigatórios antes de continuar.]” 
Clicar em “[!UICONTROL Leve-me lá]” permite que os usuários vejam que os campos estão preenchidos e podem anexar o modelo com êxito.

**O [!UICONTROL Balanceador de carga de trabalho] pisca ao alternar entre datas**

*[!UICONTROL Balanceador de carga de trabalho]*

As horas do usuário listadas primeiro no [!UICONTROL Balanceador de carga de trabalho] não são exibidas ao atualizar a linha do tempo. O usuário e suas horas são exibidos com todas as caixas cinzas que apenas piscam. Isso acontece se você avançar e retroceder na linha do tempo.

Atualizar o filtro parece redefinir a exibição. No entanto, mover-se para trás e para a frente na linha do tempo faz com que a tela pisque novamente e as horas do usuário não sejam exibidas.

**A terminologia personalizada está inconsistente**

*Modelos de layout*

Os usuários relatam isso quando o administrador do [!DNL Workfront] personaliza a terminologia de alguns objetos usando um Modelo de layout, o novo nome do objeto é exibido de forma inconsistente na interface.

Por exemplo, na página [!UICONTROL Projetos], ainda é possível ver o título da página exibido como “[!UICONTROL Projetos]”, embora o administrador do [!DNL Workfront] tenha alterado o nome de “[!UICONTROL Projetos]” para outra coisa.

Isso causa confusão para os usuários finais.

+++

+++**Atualização de manutenção em 17 de março de 2022**

**As miniaturas e imagens principais ficam em branco ao visualizar arquivos de várias páginas usando o navegador do [!DNL Safari]**

*[!DNL Workfront Proof]*

Quando um usuário tenta visualizar um arquivo com várias páginas no navegador do [!DNL Safari], as imagens da página de miniatura ficam em branco. Ocasionalmente, a imagem principal também pode estar em branco.

**Lista de usuários incorreta ao fazer atribuições em massa no [!UICONTROL Balanceador de carga de trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário faz uma atribuição em massa no [!UICONTROL Balanceador de carga de trabalho] e seleciona um Projeto e uma Função de trabalho, a lista de usuários disponíveis está incorreta. Ela pode mostrar usuários sem as permissões de Função de trabalho ou Projeto e os usuários com as permissões Função de trabalho e Projeto não aparecem na lista.

**[!UICONTROL A classificação não está funcionando nos relatórios]**

*Relatórios*

Quando um usuário clica em uma coluna para classificar por ela, a classificação parece funcionar, mas instantaneamente os resultados são revertidos para a classificação original como eram exibidos antes de clicar na coluna. A classificação em qualquer coluna não é mantida.

**Selecionar “[!UICONTROL Nada]” reverte para o agrupamento [!UICONTROL Padrão do relatório]**

*Relatórios*

Quando um relatório tem um agrupamento incorporado e o usuário tenta selecionar “[!UICONTROL Nada]” no menu suspenso [!UICONTROL Agrupamento] no menu suspenso, o relatório é exibido brevemente sem agrupamento e, em seguida, reverte para o agrupamento [!UICONTROL Padrão do relatório].

A guia **“[!UICONTROL Acesso a blueprints]” foi removida das Preferências de blueprints**

*Blueprints*

OBSERVAÇÃO: esse problema existe apenas no ambiente de Pré-visualização.

A guia [!UICONTROL Acesso a blueprints] foi removida do modal de Preferências de blueprints. Nenhuma funcionalidade foi removida das Preferências de blueprints.

+++

+++**Atualização de manutenção (hotfix) em 14 de março de 2022**

**Não é possível rolar a lista de usuários para baixo ao fazer a atribuição no quadro Kanban**

*Ágil*

Quando um usuário visualiza um quadro do [!DNL Kanban] e tenta fazer uma atribuição, a lista de usuários exibida ao digitar continua voltando para o topo à medida que a tela é rolada para baixo. O usuário não pode selecionar um usuário que não esteja perto do topo da lista e não pode salvar a alteração de atribuição.

A visualização **[!UICONTROL Marco] no relatório do projeto causa um erro**

*Relatórios*

Ao exibir um relatório de projeto usando a visualização [!UICONTROL Marco], os usuários obtêm o erro “[!UICONTROL APIModel INTERNAL não é compatível com a namedQuery TILE:milestone-view (UIVW)]”

**A terminologia personalizada está inconsistente**

*Modelos de layout*

Os usuários relatam isso quando o administrador do [!DNL Workfront] personaliza a terminologia de alguns objetos usando um Modelo de layout, o novo nome do objeto é exibido de forma inconsistente na interface.

Por exemplo, na página [!UICONTROL Projetos], ainda é possível ver o título da página exibido como “[!UICONTROL Projetos]”, embora o administrador do [!DNL Workfront] tenha alterado o nome de “[!UICONTROL Projetos]” para outra coisa.

Isso causa confusão para os usuários finais.

**Não é possível atualizar cálculos para campos calculados existentes**

*Formulários personalizados*

Os usuários não podem atualizar/alterar os cálculos nos campos calculados. Se o campo foi criado e salvo com um cálculo, toda vez que você tenta adicionar uma expressão e salvar/aplicar, o construtor volta a ficar em branco.

Se você criar um campo calculado com uma determinada expressão e salvá-lo, sempre que tentar alterar o cálculo, ele será revertido para o valor anterior.

Erro de **[!UICONTROL Parâmetro inválido] ao redefinir senhas**

*Logon*

Os usuários não conseguem redefinir suas senhas em nenhum ambiente. Quando entram no email e tentam continuar, eles veem um erro.

[!UICONTROL Erro: Parâmetro inválido: valor do parâmetro de pesquisa “domínio”].

+++

+++**Atualização de manutenção em 10 de março de 2022**

**Problemas ao fazer logon no ambiente de Pré-visualização**

*Logon*

Os seguintes problemas com o logon no ambiente de Pré- visualização foram relatados.

Quando um usuário tenta fazer logon no ambiente de Pré-visualização, é exibida uma mensagem indicando que ele inseriu a ID ou a senha incorreta.

Quando um usuário tenta redefinir sua senha, ele vê o erro “[!UICONTROL Vários usuários foram encontrados com o endereço de email <example@example.com>]”

**Os formulários personalizados são carregados lentamente na área [!UICONTROL Detalhes do projeto]**

*Projetos*

Quando um usuário tenta visualizar a área [!UICONTROL Detalhes do projeto] de um projeto, todos os formulários personalizados anexados ao projeto são carregados somente após 15 segundos ou mais. A opção [!UICONTROL Adicionar formulários personalizados] também é afetada por esse atraso.

**Os valores de campos de formulário personalizados não são salvos no painel de resumo do documento**

*Documentos*

Quando um usuário atualiza campos de formulário personalizados no painel de resumo do documento e um ou mais deles é um campo de digitação antecipada, salva as alterações e sai do painel de resumo, as atualizações não são salvas. Isso ocorre somente quando um campo de digitação antecipada é editado, embora todos os campos sejam afetados.

**Os dados não são preservados ao converter modelos devido ao compartilhamento de modelos de níveis de acesso**

*Projetos*

Quando um usuário que tem acesso de visualização em um modelo compartilhado tenta converter um problema em um projeto, os dados em seções de formulário personalizadas que exigem acesso do [!UICONTROL Contribute] ou superior para visualizar não são transferidos para o projeto criado.

**Erro ao carregar a nova versão do documento**

*Documentos*

Quando um usuário tenta fazer upload de uma nova versão de um documento na lista de documentos, o documento não é carregado e o usuário vê o seguinte erro:

[!UICONTROL Erro Não é possível invocar “com.attask.boz.Document.getCurrentVersion()” porque o “documento” é nulo]

**Não é possível editar taxas de faturamento**

*Projetos*

Quando um usuário tenta editar uma taxa de faturamento na guia [!UICONTROL Taxas de faturamento] de um projeto clicando no botão [!UICONTROL Editar], a janela [!UICONTROL Editar] abre brevemente, mas fecha antes que o usuário possa editar a taxa de faturamento. Clicar no botão novamente não abre a janela de edição.

**O link público para o documento abre uma página em branco**

*Documentos*

Quando um usuário tenta abrir um documento usando um link público, o link abre uma página em branco. Isso ocorre quando o link é aberto em uma janela em que uma sessão ativa do [!DNL Workfront] está aberta.

**Erro ao adicionar tarefa ou problema à lista**

*Tarefas e problemas*

Quando um usuário que não é um administrador tenta adicionar uma tarefa ou um problema a uma lista e preenche campos personalizados, a tarefa ou o problema não é criado e o usuário vê o seguinte erro:

[!UICONTROL Erro! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]

**Deixar uma atualização após uma alteração de status reverte o objeto para um estado anterior**

Projetos, tarefas e problemas

Alterar o status de um projeto, tarefa ou problema e começar imediatamente a digitar uma atualização sem atualizar a página faz com que a caixa de atualização mostre o status anterior. Se a atualização for publicada, o objeto será revertido para o status anterior.

**Os usuários adicionados às provas têm funções incorretas**

*Provas*

Quando um usuário adiciona outro usuário a uma prova, a função dele na prova é definida como “[!UICONTROL Somente leitura]” apesar da função de prova real do usuário.

Solução alternativa: 
Defina a função de prova do usuário em seu perfil para algo diferente e redefina para a função correta.

**O formulário personalizado não carrega ao converter o problema em um projeto usando o modelo**

*Formulários personalizados*

Quando um usuário tenta converter um problema em um projeto usando um modelo, um ou mais formulários personalizados anexados ao modelo podem não ser carregados. Quando o usuário configura o modelo para o novo projeto, em vez dos formulários personalizados, ele vê a seguinte mensagem:

“[!UICONTROL Algo deu errado, não foi possível carregar o formulário].”

**O usuário não pode adicionar o problema em linha com o campo suspenso personalizado exibido na visualização**

*Listas*

Quando um usuário adiciona um problema em linha e há uma exibição personalizada com campos suspensos personalizados aplicados à lista, ocorre um erro quando ele preenche apenas o campo suspenso. O usuário tem acesso para editar um formulário personalizado e é o proprietário do projeto com direitos de gerenciamento ao projeto.

[!UICONTROL Erro: ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]

**As permissões para adicionar tarefas a um projeto não são necessárias para mover ou copiar uma tarefa para o projeto**

*Tarefas*

Agora é possível mover ou copiar uma tarefa para outra tarefa em um projeto sem ter permissões para adicionar tarefas ao projeto de destino. Você deve ter permissões para adicionar tarefas a pelo menos uma das tarefas do projeto de destino. Antes desta atualização, você tinha permissões para adicionar tarefas ao projeto para mover ou copiar uma tarefa para o projeto ou para qualquer uma de suas tarefas.  Essa atualização está disponível no ambiente de Produção. Ela está disponível no ambiente de Pré-visualização desde a atualização de manutenção de 24 de março de 2022.

OBSERVAÇÃO: esta atualização estará disponível no ambiente de Produção ao copiar ou mover problemas após a versão de Produção 22.2. Para obter mais informações sobre a versão atual, consulte workfront.com/release.

**O menu suspenso Prompt está cortado**

*Relatórios*

Ao usar um prompt em um relatório, os menus suspensos que permitem selecionar os critérios de filtragem do relatório são cortados. Como resultado, os critérios na parte inferior do menu suspenso de seleção não são exibidos.

**O item de trabalho reverte para o status anterior quando uma atualização é feita**

*Atualizações*

Quando um usuário altera o status de um item de trabalho no cabeçalho, o status não é atualizado na área [!UICONTROL Atualização]. Se o usuário fizer uma atualização, a lista suspensa ainda mostrará o status anterior. Quando a atualização é salva, esse status anterior e incorreto substitui o status definido no cabeçalho.

+++

+++**Atualização de manutenção em 3 de março de 2022**

**Não é possível adicionar o documento a partir de [!DNL Google Drive]**

*Documentos*

Quando um usuário tenta adicionar um documento do [!DNL Google Drive], a seleção não responde e o usuário não pode selecionar documentos para adicionar.

**Os usuários marcados não são adicionados à thread de atualização**

*Atualizações*

Quando um usuário é marcado em uma atualização, ele não aparece na área “[!UICONTROL Para]” da atualização ou suas respostas.

**O usuário de prova tem duas contas de prova separadas**

*[!DNL Workfront Proof]*

O endereço de email de um usuário no [!DNL Workfront Proof] pode estar em duas contas separadas com IDs separadas, dando ao usuário duas contas. Isso pode dificultar a localização da conta correta.

**Erro exibido nos cabeçalhos do relatório**

*Relatórios*

Quando um usuário visualiza um relatório, o seguinte erro é exibido no cabeçalho do relatório:

“[!UICONTROL Vamos tentar novamente. Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

Se o usuário estiver visualizando um painel, o erro poderá aparecer no cabeçalho de todos os relatórios no painel.

**Os dados em campos exclusivos de edição de administrador do formulário personalizado não são preservados durante a conversão de problemas em projetos**

*Projetos*

Quando um usuário não administrador tenta converter um problema em um projeto usando um modelo e o problema contém dados em campos que só podem ser editados por um administrador, os dados nesses campos não são transferidos para o novo projeto.

Quando um administrador converte o problema, os dados são transportados para o novo projeto, como esperado.

O limite do tamanho de arquivo do **[!DNL XLS] e do [!DNL XLSX] foi temporariamente reduzido para 100 MB para provas**

*Prova*

Para solucionar um problema de segurança, limitamos temporariamente o tamanho máximo de arquivo do [!DNL XLS] e do [!DNL XLSX] para 100 MB ao criar uma prova.

OBSERVAÇÃO: essa atualização foi realizada no ambiente de Pré-visualização em 24 de fevereiro e estará no ambiente Produção em 3 de março.

**Atualizar para Pesquisa do Workfront**

Pesquisar

Uma implantação em fases começou esta semana para atualizar a infraestrutura da funcionalidade de pesquisa do [!DNL Workfront]. A atualização tornará a Pesquisa mais fácil e mais confiável. Com essas alterações, os itens adicionados ao [!DNL Workfront] serão indexados mais rapidamente e, portanto, retornarão nos resultados da pesquisa mais cedo.

A distribuição em fases continuará por 2 semanas.

**Barras de ferramentas atualizadas para relatórios nos painéis**

Relatórios

Os relatórios nos painéis agora mostram uma nova barra de ferramentas. Essa barra de ferramentas faz parte das atualizações de listas e relatórios que estão acontecendo em todo o [!DNL Workfront].

+++


## Atualizações em fevereiro de 2022

+++**Atualização de manutenção (hotfix) em 24 de fevereiro de 2022**

**Os dados não são preservados ao converter problemas em projetos se o campo estiver oculto no modelo**

*Projetos*

Quando um usuário converte um problema em um modelo e o modelo inclui um formulário personalizado que exibe ou oculta campos com base nos valores em outros campos, os dados nos campos ocultos no modelo (sem dados) no momento da conversão não são transportados para o novo projeto.

**Não é possível exportar o planejador de recursos por Função**

*Planejamento de recursos*

Quando um usuário tenta exportar o [!DNL Resource Planner] ao usar a opção [!UICONTROL Exibir por função], a exportação não é bem-sucedida e o usuário recebe um email com a seguinte mensagem:

Erro ao exportar dados do [!DNL Resource Planner].

**O botão Copiar solicitação não funciona**

*Solicitações*

Quando um usuário tenta copiar uma solicitação, o botão [!UICONTROL Copiar solicitação] não funciona se o usuário não tiver acesso de Visualização ao tópico da fila.

+++

+++**Atualização de manutenção em 24 de fevereiro de 2022**

**Os dados personalizados do formulário desaparecem quando outros campos de formulário são preenchidos**

*Formulários personalizados*

Quando um usuário preenche um formulário personalizado como parte da conversão de um problema em um projeto, o preenchimento de um campo personalizado pode fazer com que os dados de outro campo personalizado desapareçam. Se digitar os dados ausentes novamente ao tentar criar o projeto, o usuário verá a seguinte mensagem de erro:

“[!UICONTROL Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado]”

O campo **“[!UICONTROL Este processo de aprovação pode ser usado por...]” não é exibido**

*Aprovações*

Quando um usuário cria ou edita um processo de aprovação na área [!UICONTROL Configuração], o campo “[!UICONTROL Este processo de aprovação pode ser usado por..]” não é exibido. Isso pode ocorrer ao criar um processo de aprovação ou ao editar um existente.

**O administrador do sistema não pode reatribuir usuários ao excluir um grupo**

*Grupos*

Quando um administrador do sistema excluir um grupo, ele só terá a opção de reatribuir os usuários a grupos para os quais o administrador do sistema é um administrador de grupo. Outros grupos não aparecem na lista suspensa e o administrador não pode selecioná-los.

**Erro ao converter o problema em projeto**

*Projetos*

Quando um usuário tenta converter um problema em um projeto usando um modelo e adiciona ou remove formulários personalizados do modelo, o problema não é convertido e o usuário vê a seguinte mensagem:

[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]

**Não é possível abrir a prova; a página é atualizada**

*Provas*

Ao tentar abrir uma prova, o usuário não consegue abri-la. Por fim, a página é atualizada.

O limite do tamanho de arquivo do **[!DNL XLS] e do [!DNL XLSX] foi temporariamente reduzido para 100 MB para provas**

*Prova*

Para solucionar um problema de segurança, limitamos temporariamente o tamanho máximo de arquivo do [!DNL XLS] e do [!DNL XLSX] para 100 MB ao criar uma prova.

OBSERVAÇÃO: essa atualização estará no ambiente de Pré-visualização em 24 de fevereiro e no ambiente Produção em 3 de março.

**Permissões para adicionar tarefas ou problemas a um projeto não são necessárias para mover ou copiar uma tarefa ou um problema para o projeto**

*Projetos*

Agora é possível mover ou copiar uma tarefa ou um problema para outra tarefa em um projeto sem ter permissões para adicionar tarefas ou problemas ao projeto de destino. Você deve ter permissões para adicionar tarefas ou problemas a pelo menos uma das tarefas do projeto de destino. Antes desta atualização, você tinha permissões para adicionar tarefas ou problemas ao projeto para mover ou copiar uma tarefa ou um problema para o projeto ou para qualquer uma de suas tarefas. Esta atualização está disponível somente no ambiente de Pré-visualização.

OBSERVAÇÃO: essa atualização estará disponível no ambiente de Produção ao copiar ou mover tarefas em 10 de março. Essa atualização estará disponível no ambiente de Produção ao copiar ou mover problemas com a versão de Produção 22.2. Para obter mais informações sobre a versão atual, consulte workfront.com/release.

**Atualizar para Pesquisa do Workfront**

*Pesquisar*

Uma implantação em fases começou esta semana para atualizar a infraestrutura da funcionalidade de pesquisa do [!DNL Workfront]. A atualização tornará a Pesquisa mais fácil e mais confiável. Com essas alterações, os itens adicionados ao [!DNL Workfront] serão indexados mais rapidamente e, portanto, retornarão nos resultados da pesquisa mais cedo.

A distribuição em fases continuará por 2 semanas.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 18 de fevereiro de 2022**

**Validação do tipo de valor de campo adicionada às propriedades dos itens de lista do [!DNL Anaplan]**

*[!DNL Adobe Workfront Fusion]*

Foi corrigido um problema que permitia aos usuários colocar o tipo de dados incorreto em campos de propriedades de itens de lista. A validação do tipo de propriedade permite que o [!DNL Fusion] garanta que tipos de dados correto sejam enviados para Anaplan, eliminando erros causados por tipos de dados incorretos.

+++

+++**Atualização de manutenção em 17 de fevereiro de 2022**

**Erro ao excluir o predecessor da guia Predecessores**

*Tarefas*

Quando um usuário tenta excluir um predecessor da guia [!UICONTROL Predecessores] em uma tarefa, a tarefa não é excluída e o usuário vê o seguinte erro:

[!UICONTROL Tarefa com valores de chave primária &quot;&quot; não encontrada]

**Erro ao abrir a página de usuários**

*Usuários*

Quando um usuário tenta abrir a página [!UICONTROL Usuários], a página não abre e o usuário vê o seguinte erro:

[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]

**Sobreposição de elementos no cabeçalho de um relatório em um painel**

*Painéis*

Quando um usuário visualiza um relatório em um painel, ele vê que o ícone de agrupamentos e o rótulo se sobrepõem aos links para [!UICONTROL Detalhes] e [!UICONTROL Resumo].

**Problemas com o menu “[!UICONTROL Mais]” para documentos e provas**

*Documentos*

Ao selecionar um documento ou uma prova em uma lista de documentos do [!DNL Workfront Classic] e clicar em “[!UICONTROL Mais]”, o usuário pode observar um dos seguintes problemas:
O botão não responde. 
Todas as opções no botão são rotuladas como “[!UICONTROL objeto Objeto]” e não podem ser usadas.

Erro **“Você deve ser um administrador do sistema” para criar um projeto**

*Projetos*

Quando um usuário que não é um administrador tenta criar um projeto e anexa um formulário personalizado que tem uma seção disponível somente para administradores, ele não pode criar o projeto e vê o seguinte erro:

“Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado”

**Os dados na seção somente de administrador do formulário personalizado não são preservados ao converter problemas em projetos**

*Projetos*

Quando um usuário converte um problema em um projeto usando um modelo que tem um formulário personalizado com uma seção somente de administrador, os dados na seção somente de administrador não são transferidos para o novo projeto. Isso ocorre mesmo se um administrador estiver convertendo o problema.

+++

+++**Atualização de manutenção em 10 de fevereiro de 2022**

Erro **“[!UICONTROL Você deve ser um administrador do sistema]” para criar um projeto**

*Projetos*

Quando um usuário que não é um administrador tenta criar um projeto e anexa um formulário personalizado que tem uma seção disponível somente para administradores, ele não pode criar o projeto e vê o seguinte erro:

“[!UICONTROL Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado]”

**Os usuários que foram desativados e reativados não aparecem em [!UICONTROL Contatos de prova]**

*[!DNL Workfront Proof]*

Quando um usuário exibe sua lista de contatos no [!DNL Workfront Proof], os usuários que foram desativados e reativados não aparecem na lista.

A mensagem **“Ocorreu um erro” ao converter um problema em um projeto usando um modelo**

*Projetos*

Quando um usuário que não é um administrador tenta converter um problema em um projeto usando um modelo, os campos de formulário personalizado que estão visíveis apenas para administradores mostram a seguinte mensagem:

“[!UICONTROL Algo deu errado, não foi possível carregar o formulário]”

Erro **“Não é possível carregar conteúdo da página” ao exibir as preferências do projeto**

*Configuração*

Quando um usuário administrador tenta exibir projetos, tarefas ou problemas nas [!UICONTROL Preferências do projeto] na área [!UICONTROL Configuração], a página não é carregada e o usuário vê o seguinte erro:

“[!UICONTROL Não é possível carregar o conteúdo da página. Experimente atualizar a página.]”

+++

+++**Atualização de manutenção em 3 de fevereiro de 2022**

Erro **[!UICONTROL BizContext] ao fazer logon**

*Logon*

Quando um usuário está tentando fazer logon no [!DNL Workfront], o logon não é bem-sucedido e a seguinte mensagem é exibida:

“[!UICONTROL Vamos tentar novamente. Erro do banco de dados: falha na confirmação de BizContext!]”

Esse problema foi relatado no ambiente de Pré-visualização.

**O fluxo de atualização de problema desaparece se o problema estiver pendente de aprovação**

*Atualizações*

Quando um usuário clica na caixa [!UICONTROL Nova atualização] na sequência de atualização de um problema que está pendente de aprovação, todo o fluxo de atualização desaparece.

**Erro ao carregar a nova versão de um documento**

*Documentos*

Quando um usuário tenta fazer upload de uma nova versão de um documento, a nova versão não é carregada e o usuário vê um dos seguintes erros:

* [!UICONTROL documentID não pode ser nulo]
* [!UICONTROL Erro: Parâmetro inválido: valor de documentID “indefinido”]

**O link público para o documento abre uma página em branco**

*Documentos*

Quando um usuário tenta abrir um documento usando um link público, o link abre uma página em branco. Isso ocorre quando o link é aberto em uma janela em que uma sessão ativa do [!DNL Workfront] está aberta.

**Controles de lista não funcionam em relatórios em painéis**

*Painéis*

Quando um usuário visualiza um relatório em um painel e tenta alterar o filtro, o agrupamento ou a visualização do relatório, o filtro, o agrupamento ou a visualização não são alterados.

Erro **“[!UICONTROL Você deve ser um administrador do sistema]” para criar um projeto**

*Projetos*

Quando um usuário que não é um administrador tenta criar um projeto e anexa um formulário personalizado que tem uma seção disponível somente para administradores, ele não pode criar o projeto e vê o seguinte erro:

“[!UICONTROL Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado]”

**Os dados personalizados não são preservados ao converter um problema em um projeto**

*Projetos*

Quando um usuário converte um problema em um projeto usando um modelo, os dados de um formulário personalizado sobre o problema não são transferidos para o formulário personalizado comparável no projeto. Isso acontece com dados que estão em campos personalizados e que podem ser ocultos com base nos valores de outros campos personalizados.

**Erro ao converter o problema em projeto**

*Projetos*

Quando um usuário tenta converter um problema em um projeto, o problema não é convertido e o seguinte erro é exibido:

“[!UICONTROL Um erro inesperado ocorreu]”

+++


## Atualizações em janeiro de 2022

+++**Atualização de manutenção em 27 de janeiro de 2022**

**Os dados personalizados não são preservados ao converter um problema em um projeto**

*Projetos*

Quando um usuário converte um problema em um projeto usando um modelo, os dados de um formulário personalizado sobre o problema não são transferidos para o formulário personalizado comparável no projeto. Isso acontece com dados que estão em campos personalizados e que podem ser ocultos com base nos valores de outros campos personalizados.

**A lista de usuários em um quadro Agile não está em ordem alfabética**

*Ágil*

Quando um usuário exibe a lista de usuários em um quadro Agile, os usuários não são exibidos em ordem alfabética. Em vez disso, os usuários com mais atribuições são listados primeiro.

**Links atualizados para copiar e mover problemas**

*Problemas*

No ambiente de Pré-visualização, os links para copiar e mover problemas foram atualizados para “[!UICONTROL Copiar para]” e “[!UICONTROL Mover para]” tanto na página de edição quanto em uma lista de problemas.

**Adicione até 45 endereços IP à lista de permissões do [!DNL Workfront]**

*Configuração*

O limite de endereços IP adicionados à lista de permissões do [!DNL Workfront] aumentou de 30 para 45.

+++

+++**Atualização de manutenção em 20 de janeiro de 2022**

Erro **“[!UICONTROL Parâmetro inválido]” ao criar um projeto a partir do modelo**

*Projetos*

Quando um usuário tenta criar um projeto a partir de um modelo e remove um formulário personalizado do modelo ao criar o projeto, o projeto não é criado e o usuário vê uma mensagem de erro “[!UICONTROL Parâmetro inválido]” que menciona que um campo obrigatório no formulário personalizado foi removido.

**A lista de usuários não é carregada no [!DNL Safari] navegador**

*Usuários*

Quando um usuário acessa a área [!UICONTROL Usuários], o cabeçalho é exibido, mas a lista de usuários não é carregada.

**Atraso ao arrastar tarefas em uma lista faz com que a tarefa se mova para o local errado**

*Listas*

Quando um usuário tenta mover uma tarefa em uma lista arrastando-a, a linha azul que indica onde a tarefa será movida se move muito mais lentamente do que o cursor. Quando o usuário solta a tarefa, ela é movida para onde está a linha azul, mesmo que o cursor aponte para um local diferente na lista.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 14 de janeiro de 2022**

**Alguns campos mapeados são redefinidos ao selecionar [!UICONTROL novo campo a ser mapeado]**

*[!DNL Workfront Fusion]*

Quando pelo menos um campo nos módulos [!DNL Workfront] [!UICONTROL Criar] ou [!UICONTROL Atualizar] tem o mapeamento ativado e um usuário seleciona um novo campo para mapear, os campos mapeados anteriormente ativados perdem os valores de mapeamento.

+++

+++**Atualização de manutenção em 13 de janeiro de 2022**

**Não é possível adicionar um hiperlink a um comentário no painel Resumo**

*Tarefas*

Quando um usuário faz um comentário no painel de resumo de uma tarefa e tenta adicionar um hiperlink ao comentário, a janela do hiperlink é aberta, mas assim que o usuário clica na janela, ela é fechada e não é possível adicionar um hiperlink. Se um usuário acessar a janela, ele poderá digitar ou colar um link no campo, mas o hiperlink não será salvo. Em ambos os casos, a tarefa fica desmarcada.

**A página Editar equipe não fecha**

*Equipes*

Quando um usuário tenta editar uma equipe, a página [!DNL Edit team] não fecha. O usuário não pode fechar a página clicando em qualquer um dos botões, clicando no X ou navegando para fora da página.

**As notificações por email e no aplicativo não estão sendo enviadas**

*Notificações*

Quando um evento que deve acionar uma notificação ocorre, a notificação não é enviada. Isso pode ocorrer para notificações por email ou no aplicativo, e pode ocorrer mesmo se outras notificações estiverem sendo enviadas.

A lista **[!UICONTROL Meu trabalho] aparece vazia**

*[!UICONTROL Meu trabalho]*

Quando um usuário visualiza a lista [!UICONTROL Meu trabalho] e o modelo de layout para sua lista [!UICONTROL Meu trabalho] inclui um valor numérico como [!UICONTROL Percentual concluído], a lista [!UICONTROL Meu trabalho] não é exibida.

**[!UICONTROL Percentual concluído] e [!UICONTROL Horas concluídas] não podem ser modificados no Quadro Agile**

*Ágil*

Quando um usuário seleciona “[!UICONTROL Mostrar mais itens de trabalho]” no Quadro Agile e tenta alterar o [!UICONTROL Percentual concluído] ou as [!UICONTROL Horas concluídas] em um dos itens de trabalho recém-carregados, não é possível alterar o percentual concluído ou as horas concluídas. O botão [!UICONTROL Percentual concluído] também está em cinza, indicando que está inativo.

+++

+++**Atualização de manutenção em 6 de janeiro de 2022**

Erro **“[!UICONTROL Parâmetro inválido]” ao anexar modelos ou formulários personalizados a projetos**

*Projetos*

Quando um usuário tenta anexar um formulário personalizado ou um modelo a um projeto existente, preenche os campos obrigatórios no formulário ou modelo personalizado e salva as alterações no projeto, as alterações não são salvas e o usuário vê o erro “[!UICONTROL Parâmetro inválido]” na parte superior da página de detalhes do projeto.

**Comentários de prova não são exibidos em Atualizações de documento**

*Provas*

Quando um usuário visualiza uma prova na área [!UICONTROL Documentos], os comentários feitos na prova em si não serão exibidos na área [!UICONTROL Atualizações] do documento.

**[!UICONTROL Balanceador de carga de trabalho]: “[!UICONTROL ?[objeto Objeto]?]” é exibido nas informações de superalocação**

*[!UICONTROL Balanceador de carga de trabalho]*

Se um usuário estiver superalocado no [!UICONTROL Balanceador de carga de trabalho] devido a uma sobreposição de tarefa com o tempo limite do usuário e outro usuário visualizar a superalocação, a área “[!UICONTROL Capacidade]” das informações de superalocação exibe “[!UICONTROL ?[objeto Objeto]?]” em vez da capacidade real do usuário.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [[!DNL Workfront] Arquivo de atualizações de manutenção - 2021](2021-updates.md)
