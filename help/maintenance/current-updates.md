---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção para [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: 38e86575a1c495bc2340899562d68e59cbce7b06
workflow-type: tm+mt
source-wordcount: '13831'
ht-degree: 3%

---

# [!DNL Workfront] Atualizações de manutenção

As seguintes atualizações de manutenção foram efetuadas em 2022.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. [!DNL Workfront] O suporte o notificará quando um problema enviado for corrigido.

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

## Atualizações em outubro de 2022

+++**Atualização de manutenção em 6 de outubro de 2022**

**Novo tipo de blueprint**

*Blueprints*

O tipo de blueprint &quot;Dashboard&quot; foi adicionado ao catálogo de blueprints. Anteriormente, somente Modelos de projeto e blueprints de estrutura organizacional estavam disponíveis.

**Sobreposição de elementos no painel esquerdo**

*Formulários personalizados no meu grupo*

Quando um usuário está trabalhando no construtor de formulários e o formulário tem mais de 100 campos, a mensagem notificando o usuário sobre o limite de campo faz com que os elementos no painel esquerdo se sobreponham.

**O seletor de datas abre automaticamente no foco**

*Navegação*

Agora, ao navegar pelo teclado, os seletores de data não são mais abertos e ativados automaticamente ao receber foco do teclado.

**Atribuir várias equipes resulta em somente uma equipe atribuída**

*Equipes*

>[!NOTE]
>
>Esse problema existe apenas no ambiente de Visualização.

Quando um usuário atribui várias equipes a uma tarefa ou problema, somente uma equipe é exibida na lista de atribuições. Esse problema também afeta os relatórios. Os relatórios que mostram atribuições de equipe são imprecisos porque apenas uma equipe aparece como atribuída à tarefa ou ocorrência.

**&quot;[!UICONTROL Suas alterações recentes não foram salvas]&quot;erro ao salvar automaticamente alterações em uma folha de ponto**

*Planilhas de horas*

Quando um usuário tenta editar uma folha de ponto de uma maneira que acionaria um salvamento automático, as alterações não são salvas e o usuário vê a seguinte mensagem:

&quot;[!UICONTROL Suas alterações recentes não foram salvas. Atualize a página para visualização.]&quot;

Isso foi relatado ao editar o seguinte:

* Horas
* Tarefas

**As notificações por email são atrasadas**

*Prova do Workfront*

Quando um evento ocorre em [!DNL Workfront Proof] que aciona uma notificação por email, o usuário não recebe a notificação imediatamente. A notificação pode ser adiada por várias horas.

+++

+++**Atualização de manutenção em 3 de outubro de 2022**

**Salve manualmente a folha de ponto quando as funções de trabalho anteriores forem alteradas**

*Planilhas de horas*

Se uma função de trabalho para a qual você fez o logon tiver sido alterada e a variável [!UICONTROL Atribuir funções de tarefa a entradas de hora manualmente] tiver sido desativada, você deve salvar manualmente as entradas de tempo até que as horas não sejam mais registradas para a função de trabalho que foi alterada.

+++

## Atualizações em setembro de 2022

+++**Atualização de manutenção em 29 de setembro de 2022**

**O usuário não retorna à página anterior ao fechar a prova**

*Provas*

Quando um usuário que esteja exibindo uma prova em [!DNL Workfront] fecha a prova, não retorna a página em que estava antes de abrir a prova. Em vez disso, elas são redirecionadas para outra página no [!DNL Workfront].

**Não é possível abrir a prova em[!DNL Workfront]**

*Provas*

Quando um usuário exibe um documento em [!DNL Workfront] e tenta abrir a prova, a prova não abre e o usuário é retornado para a [!UICONTROL Detalhes do documento] página.

**As horas não são salvas ao usar [!UICONTROL Tabulação] key**

*Planilhas de horas*

Quando um usuário preenche uma folha de tempo e navega entre células com a variável [!UICONTROL Tabulação] , as horas não são salvas. O [!UICONTROL Salvar automaticamente] A notificação não é exibida na parte inferior da tela e, se o usuário atualizar a página, poderá ver que as horas não foram salvas.

**Páginas em branco ao visualizar uma prova com várias páginas**

*[!DNL Workfront Proof]*

Quando um usuário exibe uma prova com várias páginas, o usuário pode ver miniaturas das páginas, mas as páginas não abrem no visualizador principal.



+++

+++**Atualização de manutenção em 22 de setembro de 2022**

**Não é possível fechar o cartão de usuário no fluxo de atualização**

*Atualizações*

Quando um usuário está visualizando atualizações e passa o mouse sobre um nome, um cartão com detalhes sobre o usuário cujo nome é aberto e não é fechado automaticamente. A página não responde até que o cartão seja fechado manualmente clicando no X no canto superior direito.

+++

+++**Atualização de manutenção em 15 de setembro de 2022**

**&quot;[!UICONTROL Alguém tentou salvar este projeto]&quot; erro ao inserir horas**

*Planilhas de horas*

Quando um usuário tenta registrar horas em uma tarefa em sua folha de ponto, as horas não são salvas automaticamente e o usuário vê o seguinte erro:

&quot;[!UICONTROL Erro de Edição conatual a um registro locado. Recuperação automática falhou. Tente a transação mais tarde.]&quot;

**Não é possível fechar o cartão de usuário no fluxo de atualização**

*Atualizações*

Quando um usuário está visualizando atualizações e passa o mouse sobre um nome, um cartão com detalhes sobre o usuário cujo nome é aberto e não é fechado automaticamente. A página não responde até que o cartão seja fechado manualmente clicando no X no canto superior direito.

**O &quot;[!UICONTROL Atribuição de função de tarefa]&quot; campo foi renomeado para &quot;[!UICONTROL Atribuição de função]&quot; ao atribuir trabalho em massa usando o [!UICONTROL Balanceador de Carga de Trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Para refletir a nova funcionalidade de poder atribuir tarefas e problemas em massa do [!UICONTROL Trabalho Não Atribuído] , renomeamos o &quot;[!UICONTROL Atribuição de função de tarefa]&quot; campo para &quot;[!UICONTROL Atribuição de função]&quot; na [!UICONTROL Balanceador de Carga de Trabalho]. O campo se refere às funções de tarefas que foram atribuídas a tarefas ou problemas e é exibido ao atribuir usuários a itens na [!UICONTROL Atribuições em massa] caixa.

+++

+++**[!DNL Workfront Scenario Planner]Atualização de manutenção em 15 de setembro de 2022**

**O filtro compartilhado com um Grupo agora é exibido no [!DNL Scenario Planner]&#39;s  [!UICONTROL Importar projetos] lista de membros de todos os subgrupos**

*[!DNL Workfront Scenario Planner]*

Agora, ao compartilhar um filtro de projeto com um grupo que tem subgrupos adicionais, o filtro fica visível para todos os membros do grupo e do subgrupo que visualizam projetos na [!UICONTROL Importar projetos] caixa de um plano na [!DNL Scenario Planner].

+++

+++**Atualização de manutenção em 8 de setembro de 2022**

**Nomes atualizados revertidos para os campos de atribuição de usuário e função**

*Atribuições*

Os campos de atribuição temporariamente renomeados na semana passada foram revertidos para seus nomes originais:

* [!UICONTROL Usuários atribuídos]
* [!UICONTROL Funções das atribuições]

**Erro ao remover o Proprietário do Projeto do cabeçalho**

*Projetos*

Quando um usuário tenta remover um [!UICONTROL Proprietário do projeto] no cabeçalho de um projeto, a variável [!UICONTROL Proprietário do projeto] não for removido e o usuário visualizar a seguinte mensagem de erro:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Redimensionado [!UICONTROL Descrição] retorna ao tamanho original**

*Projetos, tarefas e problemas*

Quando um usuário redimensiona a variável [!UICONTROL Descrição] na área de detalhes de um item de trabalho para aumentá-lo e, em seguida, começar a digitar na caixa, a caixa retorna ao seu tamanho original. O usuário ainda pode digitar na caixa e o conteúdo é salvo conforme esperado

**Saída inadvertida ao criar tarefas ou problemas**

*Tarefas e problemas*

Quando um usuário está criando uma tarefa ou um problema em um projeto e clica fora da pop-up de criação, a pop-up é fechada sem aviso e todas as informações inseridas anteriormente são perdidas.

**Remoção da capacidade de enviar uma prova por email para um dropzone**

*[!DNL Workfront Proof]*

A partir de quinta-feira, 8 de setembro de 2022, removemos a capacidade de enviar uma prova por email para uma área designada como independente [!DNL Workfront Proof] produto.

Você ainda pode usar as áreas de soltar de outras maneiras para enviar novas provas e novas versões de provas para sua conta sem precisar entrar em sua conta. Consulte [Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) para obter mais informações.

+++

+++**Atualização de manutenção em 6 de setembro de 2022**

**Datas projetadas adicionadas à lista de campos para cabeçalhos de projetos personalizáveis**

*Projetos*

Acrescentamos o [!UICONTROL Data Inicial Projetada] e [!UICONTROL Data de Conclusão Projetada] à lista de campos para cabeçalhos de projeto personalizáveis ao usar um modelo de layout.

**Novo limite com uma mensagem de confirmação que exibe o número de itens adicionados a uma folha de ponto**

*Planilhas de horas*

Ao selecionar mais de 50 itens para adicionar a uma folha de ponto, você receberá uma mensagem de confirmação que exibe o número de itens a serem adicionados à folha de ponto e oferece a oportunidade de alterar o curso e não adicionar todos os itens. Todos os itens adicionados se tornam automaticamente fixados à folha de ponto e precisarão ser removidos manualmente da folha de ponto atual e de todas as futuras.

+++

+++**Atualização de manutenção em 2 de setembro de 2022**

Adicione o [!UICONTROL Integrações] para o cabeçalho personalizado do projeto

*Integrações*

Agora é possível adicionar a variável [!UICONTROL Integrações] para o cabeçalho personalizado de um projeto ao usar um modelo de layout. Depois de adicionado, o campo exibirá um link para um item externo vinculado ao projeto que está localizado em [!DNL Salesforce] ou [!DNL Anaplan], dependendo da integração.

>[!NOTE]
>
>Essa atualização de manutenção foi lançada anteriormente no ambiente de Visualização em 25 de agosto de 2022 e agora está em produção.

+++

+++**Atualização de manutenção em 1 de setembro de 2022**

**Itens concluídos removidos da delegação**

*Delegações*

Agora, somente itens incompletos cujas datas correspondem às datas de uma delegação serão delegados a outros usuários quando a delegação de itens de trabalho começar. Se os itens foram concluídos antes da delegação começar, eles não serão delegados. Os itens concluídos durante o período de delegação permanecerão na Lista de Trabalho da Área Inicial do delegado e do destinatário por duas semanas antes de serem removidos automaticamente, se a delegação não tiver terminado durante essas semanas.

**Atualizações de metadados para a [!DNL Adobe Workfront] para [!DNL Experience Manager Assets] e [!DNL Assets Essentials] integrações**

*Integrações*

Os metadados são enviados automaticamente ao adicionar um ativo a uma pasta vinculada.

Anteriormente, os metadados eram enviados somente quando você adicionava um ativo usando o [!UICONTROL Adicionar novo] menu suspenso.

**Não é possível aprovar ou rejeitar horas em um problema**

*Problemas*

Quando um usuário tenta aprovar ou rejeitar horas na [!UICONTROL Horas] de um problema, a guia [!UICONTROL Aprovar] e [!UICONTROL Rejeitar] botões ausentes.

**A conversão de um problema em um projeto usando um modelo exibe uma mensagem de erro incorreta**

*Problemas*

Ao converter um problema em um projeto usando um modelo e um erro for encontrado, o usuário recebe uma página com a mensagem &quot;[!UICONTROL O projeto não existe mais]&quot; em vez da mensagem de erro correta que explica a causa da conversão com falha.

**Não é possível criar prova para arquivos com mais de 1,5 GB**

*[!DNL Workfront Proof]*

Ao criar uma nova prova, se um usuário carregar um arquivo com mais de 1,5 GB, o nome do arquivo ficará vermelho e a prova não poderá ser criada.

+++

## Atualizações em agosto de 2022

+++**Atualização de manutenção em 25 de agosto de 2022**

**Os links do Balanceador de carga de trabalho são exibidos incorretamente nos painéis**

*Painéis de Controle*

Os links de Balanceador de carga de trabalho compartilhável são exibidos incorretamente quando adicionados a um painel como uma página externa. Em vez de usar a visualização/filtros exclusivos associados ao link, o painel usa a visualização/filtros aplicados mais recentemente no Balanceador de carga de trabalho.

**Adicione o [!UICONTROL Integrações] para o cabeçalho personalizado do projeto**

*Projetos*

Agora é possível adicionar a variável [!UICONTROL Integrações] para o cabeçalho personalizado de um projeto ao usar um modelo de layout. Depois de adicionado, o campo exibirá um link para um item externo vinculado ao projeto que está localizado em [!DNL Salesforce] ou [!DNL Anaplan], dependendo da integração.

>[!NOTE]
>
>No momento, essa atualização de manutenção está somente no ambiente de Visualização. Ele será lançado para produção uma semana após o lançamento da Pré-visualização.

**Os dados personalizados não são preservados ao converter um problema em um projeto em branco**

*Projetos*

Quando um usuário converte um problema em um projeto em branco (sem um modelo), os dados em campos calculados não são transferidos para o novo projeto.

**Erro &quot;Modo de planejamento de linha do tempo&quot; ao alterar uma data em um projeto**

*Projetos*

Quando um usuário tenta alterar uma data em um projeto que tem a variável [!UICONTROL Modo de Plano] defina como [!UICONTROL Salvar manualmente] > [!UICONTROL Planejamento de linha do tempo], a data não muda e o usuário vê um erro.

&quot;[!UICONTROL O modo de Planejamento de Linha do Tempo está disponível somente quando a data da linha do tempo é carregada. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

**Consistência ao abrir o Balanceador de Carga de Trabalho usando a visualização Mês**

*Balanceador de carga de trabalho*

Agora, o Balanceador de Carga de Trabalho exibe os itens atribuídos dos usuários expandidos ao exibi-los na [!UICONTROL Dia], [!UICONTROL Semana]ou [!UICONTROL Mês] exibições. Antes dessa atualização, os itens atribuídos eram exibidos expandidos para o [!UICONTROL Dia] e [!UICONTROL Semana] exibições e recolhidas para a [!UICONTROL Mês] exibir.


+++

+++**Atualização de manutenção em 18 de agosto de 2022**

**&quot;[!UICONTROL Adicionar à iteração]&quot; e &quot;[!UICONTROL Adicionar ao Quadro Kanban]&quot; opções não disponíveis ao editar tarefas em linha em um relatório**

*Relatórios*

Quando um usuário exibe uma lista de tarefas em um relatório e abre o [!UICONTROL Mais] (três pontos), o menu &quot;[!UICONTROL Adicionar à iteração]&quot; e &quot;[!UICONTROL Adicionar ao Quadro Kanban]&quot; não estão disponíveis na lista suspensa. Se o relatório for visualizado em um painel, a variável[!UICONTROL Adicionar à iteração]&quot; e &quot;[!UICONTROL Adicionar ao Quadro Kanban]&quot; estão disponíveis na lista suspensa.

**Relatórios de matriz são exibidos incorretamente ao rolar**

*Relatórios*

Quando um usuário exibe um relatório de matriz e rola, alguns elementos visuais do relatório podem se sobrepor ou duplicar.

**[!UICONTROL Marco] exibição removida da lista de projetos de Folhas de Horas**

*Planilhas de horas*

O [!UICONTROL Marco] A exibição foi removida da lista de projetos da folha de ponto ao adicionar um projeto.

**Os hiperlinks em uma prova interativa não estão ativos**

*[!DNL Workfront Proof]*

Quando um usuário está visualizando uma prova interativa e clica em um link ou botão que contém um link, o usuário não é levado para a página à qual o link ou botão é vinculado.

**Nova página de prova sem campos de texto**

*[!DNL Workfront Proof]*

No [!DNL New Proof] muitos campos de texto não são exibidos (incluindo rótulos de campo, opções suspensas e nomes de caixas de seleção).

**Os usuários não recebem notificações quando marcados em uma prova**

*[!DNL Workfront Proof]*

Quando um usuário é marcado em um comentário de prova, ele não recebe uma notificação por email sobre o comentário.

+++

+++**Atualização de manutenção em 12 de agosto de 2022**

**Novo campo de cabeçalho personalizável adicionado ao início do cabeçalho**

*Cabeçalhos*

Ao adicionar um novo campo a um cabeçalho personalizável, o campo agora é adicionado como o primeiro campo à esquerda no cabeçalho ou imediatamente após o [!UICONTROL Pesquisar] dentro do Modelo de layout. Antes dessa alteração, o campo era adicionado como o último campo no cabeçalho.

+++

+++**Atualização de manutenção em 11 de agosto de 2022**

**Não é possível editar formulários personalizados devido ao limite de caracteres incorreto em campos de texto Descritivo**

*Formulários personalizados no meu grupo*

Quando um usuário tenta editar um formulário personalizado e ele tem uma [!UICONTROL Texto descritivo] que contém mais de 512 caracteres no momento, o usuário não pode salvar as edições no formulário personalizado e vê o seguinte erro:

&quot;Os seguintes campos são inválidos: (Campo) é muito longo, máx. 512&quot;

Isso afeta [!UICONTROL Texto descritivo] campos que antes funcionavam bem, apesar de terem mais de 512 caracteres.

**Os dados em campos ocultos pela quebra de seção não são preservados ao converter um problema em um projeto**

*Formulários personalizados no meu grupo*

Quando um usuário está convertendo um problema em um projeto e o problema inclui um formulário personalizado com dados em uma quebra de seção que pode ser ocultada usando a lógica de exibição, os dados nessa seção não são transportados para o novo projeto.

**Os dados em campos ocultos pela quebra de seção não são preservados ao converter uma solicitação em um projeto**

*Formulários personalizados no meu grupo*

Quando um usuário converte uma solicitação em um projeto e ela inclui um formulário personalizado com dados em uma quebra de seção que pode ser ocultada usando a lógica de exibição, os dados dessa seção não são transportados para o novo projeto.

**Não é possível editar formulários personalizados devido ao campo Texto Descritivo**

*Formulários personalizados no meu grupo*

Quando um usuário tenta editar um formulário personalizado que inclui um campo de Texto descritivo, o rótulo do campo não é preenchido. O usuário vê o erro &quot;[!UICONTROL Este campo é obrigatório]&quot; no campo de rótulo e o usuário não pode editar o formulário personalizado devido a esse erro.

**Não é possível remover instruções de um campo personalizado no construtor de formulários personalizado**

*Formulários personalizados no meu grupo*

Quando um usuário está editando um campo personalizado e tenta remover o texto existente no [!UICONTROL Instruções] , o texto não é removido quando o campo é salvo. O usuário pode editar o texto, mas não pode removê-lo totalmente.

**Atribuição de equipe ao criar solicitação não aparece em nova solicitação**

*Solicitações*

Quando um usuário cria uma solicitação e atribui uma equipe à solicitação e, em seguida, envia a solicitação, a equipe não é atribuída à solicitação que é criada. Isso afeta somente a atribuição de equipe. As atribuições de usuário funcionam conforme esperado.

+++

+++**Atualização de manutenção em 4 de agosto de 2022**

Esses problemas foram corrigidos somente no novo [!DNL Workfront] experiência.

Todos [!DNL Workfront Classic] foi removida em 14 de julho de 2022.

**Erro ao alterar a Data de Conclusão Planejada no cabeçalho de uma tarefa ou problema**

*Tarefas e problemas*

Quando um usuário tenta alterar a variável [!UICONTROL Data de Conclusão Planejada] no cabeçalho de uma tarefa ou problema, a data não é alterada e o usuário vê um erro semelhante ao seguinte:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Atualizações em julho de 2022

+++**Atualização de manutenção em 28 de julho de 2022**

Esses problemas foram corrigidos somente no novo [!DNL Workfront] experiência.

Todos [!DNL Workfront Classic] foi removida em 14 de julho de 2022.

**Erro ao abrir um item do [!UICONTROL Lista de Trabalho Doméstica]**

*[!UICONTROL Início]*

Quando um usuário tenta abrir um item em suas [!UICONTROL Lista de Trabalho Doméstica], o item não abre e o usuário vê a seguinte mensagem:

&quot;[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.]&quot;

**Tarefas e problemas delegados a um usuário não aparecem na Lista de Trabalho Doméstico do usuário**

*[!UICONTROL Início]*

Quando o usuário exibe suas [!UICONTROL Lista de Trabalho Doméstica], quaisquer tarefas ou questões delegadas ao usuário não aparecem na lista e o usuário pode não estar ciente das delegações.

**Os relatórios agendados não são enviados a todos os destinatários**

*Relatórios*

Quando um relatório agendado é enviado, ele não é enviado para todos os usuários no[!UICONTROL Enviar para]seção &quot;. Os usuários omitidos são aleatórios e podem variar cada vez que o relatório é enviado.

**[!UICONTROL Não é possível desmarcar tarefas ao anexar o modelo]**

*Modelos*

Quando um usuário anexa e personaliza um modelo, ele é solicitado a desmarcar as tarefas que não deseja incluir. No entanto, nenhuma das tarefas é exibida como selecionada e o usuário não pode desmarcá-las.

**Os campos &quot;Localidade&quot; agora têm rótulos mais específicos**

*Terminologia*

Para fazer a função do &quot;[!UICONTROL Localidade]&quot; campos mais claros, atualizamos seus rótulos.

* O &quot;[!UICONTROL Localidade]&quot; no perfil do usuário agora é rotulado como &quot;[!UICONTROL Localidade de email]&quot;
* O &quot;[!UICONTROL Localidade]&quot; encontrado no campo [!UICONTROL Configuração] >[!UICONTROL Sistema] >[!UICONTROL Informações do cliente] área agora rotulada como &quot;[!UICONTROL Localidade de email padrão]&quot;

A funcionalidade desses campos não foi alterada.

**Problemas ao criar folhas de horas**

*Planilhas de horas*

Os seguintes problemas foram relatados em relação à criação de folhas de ponto:

* Quando um usuário tenta criar uma folha de ponto para uma Função, a folha de ponto não é criada e o usuário vê o erro &quot;[!UICONTROL Usuário com valores de chave primária &#39;XXXXXXXXXXX&#39; não encontrado.]&quot;
* Quando um usuário tenta criar uma folha de ponto para uma Equipe, a [!UICONTROL typeahead] não é preenchido com equipes e a variável [!UICONTROL Criar folha de ponto] está desativado.


**Áreas de [!DNL Workfront Proof] não atualize quando uma prova for criada, movida ou arquivada**

*[!DNL Workfront]Prova*

A prova está enfrentando atrasos de indexação no momento. Isso pode afetar a experiência do usuário de formas que incluem o seguinte:

* Os painéis não mostram o número correto de provas
* As pastas não são atualizadas quando uma prova é criada ou movida
* As provas arquivadas permanecem em listas de prova ativas.

+++

+++**Atualização de manutenção (hotfix) em 26 de julho de 2022**

Esses problemas foram corrigidos somente no novo [!DNL Workfront] experiência.

Todos [!DNL Workfront Classic] foi removida em 14 de julho de 2022.

**As horas mostradas na folha de ponto são diferentes da lista Folhas de ponto**

*Planilhas de horas*

Quando um usuário abre uma folha de ponto para exibi-la, as horas exibidas são diferentes de quando o usuário exibe a mesma folha de ponto em uma lista de folha de ponto.


**Solicitação convertida em projeto com modelo mostra o grupo da fila de solicitações, não o grupo do modelo**

*Solicitações*

Quando um usuário converte uma solicitação em um projeto usando um modelo, o projeto recém-criado é associado ao grupo que possui a fila de solicitações, não ao grupo atribuído no modelo. Isso ocorre mesmo quando o projeto está sendo criado, o grupo associado ao modelo é preenchido na variável [!UICONTROL Grupo] campo.

+++

+++**Atualização de manutenção em 21 de julho de 2022**

Esses problemas foram corrigidos somente no novo [!DNL Workfront] experiência.

Todos [!DNL Workfront Classic] foi removida em 14 de julho de 2022.

**O status de rejeição associado a uma aprovação respeita o fluxo de trabalho de aprovação**

**OBSERVAÇÃO: Essa funcionalidade foi lançada em 22 de julho de 2022.**

*Aprovações*

Se você selecionar um status associado a um processo de aprovação como status de rejeição para um caminho de aprovação, o objeto rejeitado será movido para o status selecionado e será marcado como &quot;[!UICONTROL Aprovação pendente]&quot;. Por exemplo, se você selecionar [!UICONTROL Em Espera] para o status de rejeição e o [!UICONTROL Em Espera] estiver associado a um processo de aprovação, o objeto rejeitado será colocado no status de &quot;[!UICONTROL Em Retenção - Aprovação pendente]&quot;, exigindo a aprovação.

Antes dessa atualização, o objeto ignorava o processo de aprovação do status de rejeição e ele era colocado no [!UICONTROL Em Espera] status.

**Configurar um URL de ajuda personalizado**

*[!UICONTROL Menu principal]*

Se sua organização tiver um site de ajuda interno personalizado, você poderá configurar a variável [!UICONTROL Menu principal] [!UICONTROL Ajuda] ícone para acessar esse site. Isso é útil se o site de ajuda contiver informações sobre como sua organização usa o [!DNL Workfront].
Esse URL personalizado não afeta o link principal da Ajuda na área superior de [!DNL Workfront], nem os links de ajuda sensíveis ao contexto em [!DNL Workfront], que leva os usuários para a [!DNL Workfront] Site de ajuda.

**Não é possível selecionar Tempo decorrido ao editar em linha [!UICONTROL Duração da tarefa]**

*Tarefas*

Quando um usuário está visualizando uma lista de tarefas e tenta editar a variável [!UICONTROL Duração da tarefa], as seguintes unidades de duração não estão disponíveis:

* [!UICONTROL Minutos corridos]
* [!UICONTROL Horas corridas]
* [!UICONTROL Dias corridos]
* [!UICONTROL Semanas corridas]
* [!UICONTROL Meses decorridos]

**[!UICONTROL Minhas atualizações] página está em branco**

*Atualizações*

Quando um usuário tenta exibir seus [!UICONTROL Minhas atualizações] a página não é carregada. O usuário pode visualizar somente a variável [!DNL Workfront] cabeçalho de navegação.

**&quot;[!UICONTROL Permitir apenas a autenticação SAML 2.0]&quot; está faltando ao copiar um usuário**

*Usuários*

Quando um administrador de grupo copia um usuário e cancela a seleção de &quot;[!UICONTROL Enviar um email de convite para esta pessoa]&quot;, a opção &quot;O[!UICONTROL Permitir apenas a autenticação SAML 2.0]&quot; a caixa de seleção não é exibida conforme esperado. Isso pode ocorrer mesmo quando todos os requisitos de acesso e permissão para essa ação forem atendidos.

+++

+++**Atualização de manutenção em 14 de julho de 2022**

Esses problemas foram corrigidos somente no novo [!DNL Workfront] experiência.

Todos [!DNL Workfront Classic] foi removida em 14 de julho de 2022.

**Erro ao redefinir a senha**

*Logon*

Quando um usuário tenta redefinir sua senha, ele não pode redefini-la e vê uma mensagem informando que não tem acesso. O usuário não pode fazer logon no Workfront.

**Não é possível solicitar mais acesso a um relatório**

*Relatórios*

Quando um usuário com acesso limitado a um relatório tenta solicitar mais acesso a um relatório, a opção para solicitar mais acesso não está disponível na variável [!UICONTROL ações de relatório] menu.

**Mensagem de confirmação atualizada ao excluir um rascunho de solicitação**

*Solicitações*

Ao descartar uma solicitação esboçada, a mensagem de confirmação é exibida após clicar em &quot;[!UICONTROL Descartar rascunho]&quot; exibe o seguinte:

* [!UICONTROL O rascunho foi descartado] (esta é uma notificação para que você saiba que o rascunho foi descartado)
* [!UICONTROL Desfazer] (este é um link que você pode clicar para reverter a ação de excluir o rascunho. Isso manterá o rascunho em vez de excluí-lo.)

Antes dessa alteração, as opções eram:

* [!UICONTROL O rascunho será descartado]
* [!UICONTROL Cancelar]

**Valores de data para campos de Entrada de diário incorretos quando acessados por meio da API**

*Atualizações*

Quando um usuário altera um valor de data em um objeto e, em seguida, a Entrada de diário que representa essa alteração de data é acessada por meio da API, os valores de data para [!UICONTROL oldDateVal] e [!UICONTROL newDateVal] retornados pela API estão incorretos.

**Erro ao tentar desfazer o comentário**

*Atualizações*

Quando um usuário tenta desfazer um comentário, ele não é desfeito e o usuário vê o seguinte erro:

[!UICONTROL Erro 403: Você não tem acesso suficiente para excluir esta Nota /attask/api-internal/NOTE]

**Nova limitação ao número de caracteres em uma atualização na Visualização**

*Atualizações*

Para melhorar o desempenho do [!UICONTROL Atualizações] , introduzimos um novo limite para o número de caracteres que podem ser inseridos em uma atualização ou em uma resposta a uma atualização existente. O novo limite é de 15.000 caracteres. Essa atualização não alterou o número de caracteres permitidos ao usar a API. O limite de caracteres da API para atualizações é 4.000.

**Erro ao fazer upload do anexo de [!DNL Workfront] para integração com o Outlook**

*Integrações do Workfront*

Quando um usuário tenta fazer upload de um anexo usando o [!DNL Workfront for Outlook] , o anexo não é carregado e o usuário vê a seguinte mensagem:

[!UICONTROL Alguns anexos não foram carregados. Motivo: Algo deu errado com o carregamento de anexos.]

**Atualização de notificação por email de prova**

*[!DNL Workfront]Prova*

No início deste mês, como parte de um sistema para [!DNL Workfront] No ambiente de produção, corrigimos alguns erros no sistema de notificação por email de prova. Essa alteração não foi comunicada na atualização de manutenção quando foi lançada. Adicionamos as seguintes informações ao [Atualização de manutenção em 2 de junho de 2022](#maintenance-update-on-june-2-2022) :

Como resultado dessas correções de erros, o endereço de email usado para enviar notificações de prova foi alterado.

Anteriormente, os endereços de email de prova continham o subdomínio de sua organização. Por exemplo, notificações@[domínio da empresa].my.workfront.com

Agora, a criação de perfis de endereços de email não contém mais um subdomínio de organização. Todas as notificações por email de prova serão enviadas pelo seguinte endereço: notification@my.workfront.com

Como resultado, recomendamos que você execute as seguintes ações caso ainda não o tenha feito:

* Atualize seus filtros de spam para aceitar emails de notification@my.workfront.com
* Atualize suas listas de permissões para aceitar emails de notification@my.workfront.com

**As opções de usuário não podem ser modificadas após a configuração inicial em Modelos de fluxo de trabalho**

*[!DNL Workfront Proof]*

Quando um usuário está adicionando um usuário a um Modelo de fluxo de trabalho, ele pode configurar opções. No entanto, após a conclusão da configuração inicial, o usuário não poderá mais modificar o seguinte:

* &quot;[!UICONTROL Resolver comentários e aplicar ações]&quot; capacidade
* [!UICONTROL &quot;Compartilhar prova marcando]&quot; capacidade
* Função de prova ([!UICONTROL Revisor], [!UICONTROL Aprovador], etc.)

**&quot;[!UICONTROL Itens de trabalho deste projeto]&quot; foi restaurado no projeto [!UICONTROL Balanceador de Carga de Trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Restauramos o filtro &quot;Itens de trabalho deste projeto&quot; no [!UICONTROL Atribuído] ao acessar a variável [!UICONTROL Balanceador de Carga de Trabalho] de um projeto.

Esse filtro agora está listado abaixo de &quot;[!UICONTROL Sugerido]&quot;seção dos filtros para a [!UICONTROL Trabalho Atribuído] área de um projeto [!UICONTROL Balanceador de Carga de Trabalho].

+++

## Atualizações em junho de 2022

+++**Atualização de manutenção em 30 de junho de 2022**

**Exiba o [!UICONTROL Balanceador de Carga de Trabalho] por uma semana**

*[!UICONTROL Balanceador de carga de trabalho]*

Com base no feedback que recebemos de muitos clientes, agora adicionamos uma opção para exibir a variável [!UICONTROL Balanceador de Carga de Trabalho] por uma semana. Antes dessa atualização, você poderia exibir o [!UICONTROL Balanceador de Carga de Trabalho] para 4, 6 e 12 semanas. Com esta atualização, também alteramos a opção de 12 semanas para 3 meses.

**O painel Delegar agora está disponível no Balanceador de Carga de Trabalho**

*[!UICONTROL Balanceador de carga de trabalho]*

OBSERVAÇÃO: Essa atualização existe somente no ambiente de Visualização. A funcionalidade associada a esta atualização estará disponível em Produção com a versão 22.3.

Agora é possível visualizar os delegados de uma tarefa ou problema no Balanceador de Carga de Trabalho. Ao atribuir uma tarefa ou um problema do Balanceador de Carga de Trabalho, você pode exibir uma lista de atribuições, bem como uma lista de delegados para a tarefa ou problema, se eles forem delegados no momento.

**Não é possível abrir informações de ponto de extremidade no API Explorer**

*API*

Quando um usuário exibe a variável [!DNL API Explorer] e cliques em um endpoint, as informações do endpoint não são exibidas.

**Problemas com [!UICONTROL Detalhes] ao usar o [!UICONTROL Calendário doméstico]**

*Início*

Quando um usuário estiver usando a variável [!UICONTROL Calendário doméstico] e clicar em uma tarefa, um dos seguintes poderá ocorrer:

* O [!UICONTROL Detalhes] aparece brevemente e depois desaparece. O usuário não pode acessar os detalhes.
* O [!UICONTROL Detalhes] não é exibido. O usuário não pode acessar os detalhes.
* O [!UICONTROL Detalhes] é exibido, mas não está no local correto. O usuário pode clicar no botão para acessar os detalhes.

+++

+++**Atualização de manutenção (hotfix) em 24 de junho de 2022**

**O seletor de datas não é fechado ao editar o formulário personalizado**

*Formulários personalizados*

Quando um usuário edita um formulário personalizado e tenta alterar uma data, o seletor de datas não é fechado quando a data é selecionada. O usuário não pode fechar o seletor de datas salvando, cancelando ou clicando fora dele.

Isso foi relatado nas seguintes áreas:

* [!UICONTROL Atualizações] area
* [!UICONTROL Início]

**O usuário não pode se mover para outro estágio de uma prova**

*Provas*

Quando um usuário exibe a variável [!UICONTROL Fluxo de trabalho de prova] de uma prova e tentativas de se arrastar para um estágio diferente da prova, o nome do usuário se ajusta de volta ao estágio original e não é adicionado ao estágio desejado.

+++

+++**Atualização de manutenção em 23 de junho de 2022**

**[!UICONTROL Não é possível adicionar nova solicitação através do painel]**

*Painéis de Controle*

Quando um usuário está visualizando um painel em um projeto e tenta adicionar uma nova solicitação clicando no botão [!UICONTROL +Nova solicitação] , o botão não responde e o usuário não pode adicionar uma nova solicitação.

**Erro ao visualizar itens na Lista de Trabalho Doméstica**

*[!UICONTROL Início]*

Quando um usuário exibe a [!UICONTROL Lista de Trabalho Doméstica] e cliques em um item no [!UICONTROL Aprovações que enviei] , a página exibe o seguinte erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

Se o usuário atualizar a página, clique em qualquer item no [!UICONTROL Lista de Trabalho], o erro será exibido. O problema não afeta mais somente os itens na variável [!UICONTROL Aprovações que enviei] seção.

**A seção Personalizada em um objeto inclui resultados que não estão nesse objeto**

*Objetos*

Quando um usuário exibe uma [!UICONTROL custom] em um objeto, a seção personalizada exibe itens que não fazem parte desse objeto. Isso foi relatado quando a seção personalizada é adicionada diretamente ao objeto e quando uma seção personalizada é adicionada por meio de um modelo de layout.

**As tarefas são movidas para um projeto incorreto**

*Tarefas*

Quando um usuário move tarefas do Projeto A para o Projeto B, em seguida move mais tarefas do Projeto A para o Projeto C, as tarefas originalmente movidas para o Projeto B aparecem no Projeto C.

**Alguns botões/ícones não funcionam ao acessar [!UICONTROL Balanceador de Carga de Trabalho] de um link ou painel compartilhado**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário vai para a variável [!UICONTROL Balanceador de Carga de Trabalho] por um link compartilhado ou um link em um painel e tenta usar o elemento na parte superior da tela, os elementos não funcionam. Isso foi relatado para os seguintes elementos:

* [!UICONTROL Hoje]
* Setas para trás e para a frente
* [!UICONTROL Semanas]
* Ícone Calendário (seletor de datas)

+++

+++**[!DNL Workfront]Atualização de manutenção do planejador de cenário em 23 de junho de 2022**

**Usuários com [!UICONTROL Gerenciar] permissões para um plano podem compartilhá-lo com outras pessoas**

Como um usuário com [!UICONTROL Gerenciar] permissões para um plano no [!DNL Scenario Planner], agora você pode compartilhá-lo com outros usuários. Antes desta atualização, somente o criador do plano poderia compartilhar o plano com outros usuários.

+++

+++**Atualização de manutenção em 16 de junho de 2022**

**O administrador de grupo não pode adicionar membros ao grupo**

*Grupos*

Quando um administrador de grupo tenta adicionar um usuário a um grupo, a lista suspensa para selecionar o usuário não é preenchido. O administrador do grupo não pode selecionar nenhum usuário e, portanto, não pode adicionar nenhum usuário ao grupo.

**Quartos personalizados que não aparecem ao definir um filtro**

*Filtros*

Quando um usuário cria um filtro e filtros por campo de data, a lista suspensa de operadores disponíveis para o campo de data não inclui trimestres personalizados adicionados recentemente.

**Erro &quot;Boops&quot; ao converter um problema em um projeto por meio de um modelo**

*Projetos*

Quando um usuário tenta converter um problema em um projeto por meio de um modelo e o problema tem um formulário personalizado que contém uma seção somente de administrador, o problema não é convertido e o usuário vê o seguinte erro:

&quot;[!UICONTROL Vamos tentar novamente. Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

**As solicitações são enviadas sem os campos obrigatórios preenchidos**

*Solicitações*

Quando um usuário cria uma solicitação e não preenche os campos obrigatórios e, em seguida, envia a solicitação, a solicitação é enviada sem dados nos campos obrigatórios. O comportamento esperado é que a solicitação não seja enviada e que o usuário seja notificado de que precisa preencher os campos obrigatórios antes de enviar a solicitação.

**Novos trimestres personalizados não parecem salvar**

*Configuração*

Quando um usuário está adicionando um novo trimestre personalizado da área Projetos da Configuração e clica em [!UICONTROL Salvar], não há nenhuma indicação visual do salvamento. O usuário não vê uma mensagem de sucesso e a variável [!UICONTROL Salvar] ainda presente e ativo. No entanto, se o usuário atualizar a página, poderá ver que os novos trimestres aparecem na lista de trimestres personalizados.

Se o usuário adicionar um novo trimestre, clique em [!UICONTROL Salvar], não recebe nenhuma indicação do salvamento, adiciona outro trimestre sem atualizar a página e clicar em [!UICONTROL Salvar] novamente, o segundo trimestre adicionado pode não ser salvo.

**[!UICONTROL Solicitações de Trabalho da Equipe] página está em branco**

*Equipes*

OBSERVAÇÃO: Esse problema existe apenas no ambiente de Visualização.

Quando um usuário tenta abrir o [!UICONTROL Solicitações de trabalho] em uma página da equipe, a página fica em branco. O usuário pode visualizar a barra de navegação superior, mas nenhum conteúdo de página.

+++

+++**Atualização de manutenção em 9 de junho de 2022**

**Não é possível selecionar objetos para filtrar [!UICONTROL Portfolio Otimizer] preferências**

*Portfólios*

Quando um usuário está no [!UICONTROL Portfolio Otimizer] e exibe a [!UICONTROL Filtros do projeto] na guia no [!UICONTROL Preferências] , as caixas de seleção ao lado dos objetos estão ausentes. O usuário não pode marcar ou desmarcar caixas e, portanto, não pode selecionar objetos para filtrar.

**Não é possível alterar [!UICONTROL Data de início planejada] ou [!UICONTROL Data de Conclusão Planejada] quando &quot;[!UICONTROL Agendar de]&quot; não está marcado**

*Projetos*

Quando um usuário tenta editar a variável [!UICONTROL Data de início planejada] ou [!UICONTROL Data de Conclusão Planejada] de um projeto e o &quot;[!UICONTROL Agendar de]&quot; para esse projeto não estiver marcada, a opção [!UICONTROL Data de início planejada] e [!UICONTROL Data de Conclusão Planejada] As áreas estão desativadas e o usuário não pode editar essas datas.

**Não é possível editar o nível de acesso dos usuários**

*Usuários*

Quando um usuário que tenha acesso ao Planejador que inclua o acesso de Administrador de usuário (usuários de grupo) tenta editar os usuários no grupo para o qual eles são administradores, a variável [!UICONTROL Acesso] O campo de nível está desativado e o usuário não pode editar o nível de acesso.

+++

+++**[!DNL Workfront Scenario Planner]Atualização de manutenção em 9 de junho de 2022**

**Painel esquerdo redimensionável no[!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

Agora é possível redimensionar o painel esquerdo em um Plano, na [!DNL Scenario Planner]. Isso permite que nomes de iniciativas mais longos sejam totalmente exibidos. Antes dessa atualização, nomes de iniciativa mais longos eram truncados.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 9 de junho de 2022**

**Dados de formulários personalizados não estão disponíveis em [!DNL Workfront Fusion] [!DNL Workfront] módulos**

*[!DNL Workfront Fusion]*

Quando um usuário está configurando um [!DNL Workfront] módulo em [!DNL Workfront Fusion]e tentar selecionar saídas para o módulo, os campos de formulários personalizados não estarão visíveis. Isso ocorre quando o formulário personalizado foi criado para um tipo de [!DNL Workfront] e outro tipo foi adicionado a ele. [!DNL Workfront Fusion] exibe somente campos de formulários personalizados originalmente criados para o tipo de objeto selecionado.

**Não é possível rolar para exibir todas as execuções de cenário**

*[!DNL Workfront Fusion]*

Quando um usuário exibe o histórico de execução de um cenário e tenta rolar para baixo para visualizar mais execuções, as execuções param de ser carregadas e o usuário não pode visualizá-las. Além disso, o usuário não pode rolar de volta para as execuções mais recentes.

+++

+++**Atualização de manutenção em 2 de junho de 2022**

**[!UICONTROL Portfolio Otimizer] mostra uma pontuação de 0 ao usar um idioma diferente do inglês**

*Portfólios*

Quando um usuário estiver usando [!DNL Workfront] em um idioma diferente do inglês e exibe a variável [!UICONTROL Portfolio Otimizer], a pontuação será exibida como 0. Isso pode ocorrer mesmo quando o caso comercial não estiver completo.

**Valores de campo calculados incorretos ao criar projeto a partir do modelo**

*Projetos*

Quando um usuário cria um projeto a partir de um modelo que inclui campos calculados, os valores de campo que aparecem no novo projeto estão incorretos.

**Não é possível editar [!UICONTROL Condições] em [!UICONTROL Preferências do projeto] área de [!UICONTROL Configuração]**

*[!UICONTROL Configuração]*

Quando um usuário tenta editar [!UICONTROL Condições] no [!UICONTROL Preferências do projeto] área de [!UICONTROL Configuração], a página fica em branco.

**Nova limitação ao número de caracteres em uma atualização na Visualização**

*[!UICONTROL Balanceador de carga de trabalho]*

>[!NOTE]
>
>Essa atualização se aplica somente ao ambiente de Visualização.

Para melhorar o desempenho da área Atualizações, introduzimos um novo limite para o número de caracteres que podem ser inseridos em uma atualização ou em uma resposta a uma atualização existente. O novo limite é de 15.000 caracteres. Essa atualização não alterou o número de caracteres permitidos ao usar a API. O limite de caracteres da API para atualizações é 4.000. Atualizações Suporte para campos personalizados do tipo Typehead em filtros de Balanceador de Carga de Trabalho

Agora oferecemos suporte a filtros com base no [!UICONTROL Digitalização antecipada] digite campos personalizados no Balanceador de carga de trabalho. Antes deste patch, a filtragem desse tipo de campos personalizados não era possível no Balanceador de Carga de Trabalho.

**Não é possível editar permissões na função de um usuário**

*[!DNL Workfront Proof]*

Quando um usuário tenta editar o &quot;[!UICONTROL Resolver comentários e aplicar ações]&quot; ou &quot;[!UICONTROL Compartilhar uma prova marcando]&quot; permissões na função de um usuário em [!DNL Workfront Proof], as alterações não são salvas. O usuário recebe uma notificação de que o modelo foi atualizado, mas se o usuário abrir as permissões de função novamente, poderá ver que as alterações não foram salvas.

+++


## Atualizações em maio de 2022

+++**Atualização de manutenção em 26 de maio de 2022**

Esses problemas foram corrigidos somente no novo [!DNL Workfront] experiência. [!DNL Adobe Workfront Classic] não é mais compatível.

Todos [!DNL Workfront Classic] A funcionalidade será removida em julho de 2022. Faça a transição para a nova experiência o mais rápido possível.

**Separadores de navegação estrutural atualizados**

*[!DNL Workfront]*

OBSERVAÇÃO: Essa atualização foi lançada em 24 de maio de 2022.

Atualizamos os separadores de navegação estrutural em todas as áreas em que há navegação estrutural disponível. Agora, os objetos na navegação estrutural são separados por barra vertical (|). Antes dessa atualização, eles eram separados por barras (/).

**Não é possível editar formulários personalizados com quebras de seção**

*Formulários personalizados*

Quando um usuário tenta editar um formulário personalizado com uma quebra de seção, ele não pode editar o formulário e vê a seguinte mensagem:

[!UICONTROL A segurança de quebra de seção especificada não pode ser aplicada em todos os tipos de objeto]

**Problemas ao imprimir painéis no PDF**

*Painéis de Controle*

Os seguintes problemas foram relatados ao imprimir um painel em um PDF: O PDF não imprime todas as linhas no relatório. Quando as linhas estiverem faltando, somente será exibido espaço em branco.
O PDF inclui espaços em branco entre os cabeçalhos da coluna e a primeira linha do relatório.

**[!DNL Portfolio Optimizer]mostra uma pontuação de 0 ao usar um idioma diferente do inglês**

*Portfólios*

Quando um usuário estiver usando [!DNL Workfront] em um idioma diferente do inglês e exibe a variável [!UICONTROL Portfolio Otimizer], a pontuação será exibida como 0. Isso pode ocorrer mesmo quando o caso comercial não estiver completo.

**Alguns formulários personalizados não são exibidos ao editar um modelo**

*Modelos*

Quando um usuário tenta editar os formulários personalizados em um modelo clicando em [!UICONTROL Editar] no cabeçalho do modelo, a variável [!UICONTROL Editar modelo] exibe somente um dos formulários personalizados anexados ao modelo.

**O link compartilhado para o Balanceador de Carga de Trabalho exibe o trabalho atribuído incorretamente**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário exibe a variável [!UICONTROL Balanceador de Carga de Trabalho] usando um link compartilhado, a variável [!DNL Workload Balancer] inclui [!UICONTROL Trabalho Atribuído] no [!UICONTROL Trabalho Não Atribuído] seção. [!UICONTROL Trabalho Atribuído] não tem uma seção separada. Quando o usuário exibe a variável [!UICONTROL Balanceador de Carga de Trabalho] sem usar o link compartilhado, [!UICONTROL Trabalho Atribuído] é exibido conforme esperado.

+++

+++**Atualização de manutenção em 19 de maio de 2022**

**Não é possível criar uma prova a partir de uma[!DNL PowerPoint]**

*[!DNL Workfront Proof]*

Quando um usuário tenta criar uma prova a partir de um [!DNL PowerPoint] que inclui um gráfico, a criação da prova falha.

**Não é possível criar uma prova a partir de uma [!UICONTROL Palavra] documento**

*[!DNL Workfront Proof]*

Quando um usuário tenta criar uma prova a partir de um [!DNL Word] documento que inclui um gráfico, a criação da prova falha.

**Não é possível adicionar mensagem personalizada ao compartilhar uma prova**

*[!DNL Workfront Proof]*

Quando um usuário está visualizando uma prova, o abre o [!UICONTROL Compartilhar prova] e seleciona a variável [!UICONTROL Adicionar mensagem personalizada] , o usuário não pode digitar na caixa de texto que é aberta. Quando o usuário tenta digitar nessa caixa, a caixa imediatamente desaparece.

**Não é possível fechar a prova**

*[!DNL Workfront Proof]*

Quando um usuário exibe uma prova e tenta fechá-la, o X para fechar a prova está ausente no canto superior direito da prova.

**Não é possível adicionar ou remover o administrador de grupo**

*Grupos*

Se um usuário estiver visualizando uma [!UICONTROL Grupo] e tenta adicionar ou remover um administrador de grupo usando o [!UICONTROL Administradores de grupo] no cabeçalho, as alterações não são salvas e o usuário vê o seguinte erro:

[!UICONTROL Erro! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]

**Barra de rolagem horizontal bloqueia o item no final da lista**

*Projetos*

Quando um usuário está visualizando uma lista usando uma exibição que se estende para fora da tela, a barra de rolagem horizontal bloqueia a exibição do usuário do último item na lista.

**&quot;[!UICONTROL Erro inesperado]&quot; ao converter um problema em um projeto usando um modelo**

*Listas*

Quando um usuário tenta converter um problema em um projeto usando um modelo, o problema não é convertido e o usuário vê a seguinte mensagem:

[!UICONTROL Ocorreu um erro inesperado: ]

**O [!UICONTROL Status] campo em uma exibição de folha de ponto agora é somente leitura**

*Planilhas de horas*

Nós mudamos a [!UICONTROL Status] em uma exibição de folha de ponto para ser somente leitura. Antes dessa alteração, os usuários podiam editar o status em linha de uma folha de ponto que permitia que eles substituíssem a decisão dos aprovadores da folha de ponto.

+++

+++**Atualização de manutenção em 12 de maio de 2022**

**[!UICONTROL Salvar] botão não interrompe o carregamento ao editar um projeto**

*Projetos*

Quando um usuário edita um projeto e tenta salvar, ele observa que a variável [!UICONTROL Salvar] exibe a palavra &quot;[!UICONTROL Carregamento].&quot; Se o usuário clicar nesse botão para salvar as alterações no projeto, o botão não responderá e as alterações não serão salvas.

**Os rótulos de campo não aparecem ao visualizar um objeto em [!UICONTROL Início]**

*Início*

Quando um usuário seleciona um objeto de [!UICONTROL Lista de Trabalho Doméstica], a área à direita da [!UICONTROL Lista de Trabalho Doméstica] que exibe o objeto não inclui rótulos de campo. Os valores de campo estão presentes.

**O Filtro rápido não se concentra automaticamente na barra de pesquisa**

*Listas*

Quando um usuário está em uma lista, clica na lupa para filtrar rapidamente e, em seguida, começa a digitar, o texto não é exibido. Isso ocorre porque o foco permanece no ícone da lupa em vez de transferir para a barra de pesquisa.

Clicar na barra de pesquisa transfere o foco e permite que o usuário insira o texto de sua pesquisa.

**Usuários não podem editar campos em um relatório**

*Relatórios*

Quando um usuário tenta editar um campo em um relatório e ele é extraído de um formulário personalizado, ele não pode editar o campo. Isso ocorre quando o formulário personalizado foi criado originalmente para um tipo de objeto diferente do objeto ao qual ele está anexado.

**Rótulo e texto de botão não visíveis ao criar uma prova**

*[!DNL Workfront Proof]*

OBSERVAÇÃO: Esse problema existe apenas no ambiente de Visualização.

Quando um usuário tenta criar uma prova, o texto não fica visível para opções ou botões. Portanto, o usuário não sabe o que cada opção ou botão representa e não pode configurar a prova.

+++

+++**Atualização de manutenção em 5 de maio de 2022**

**Não é possível adicionar um novo Registro de Faturamento**

*Projetos*

Quando um usuário está no [!UICONTROL Registros de cobrança] área de um projeto e está usando a variável [!UICONTROL Novo Registro de Faturamento] Exibir, se o usuário tentar adicionar um novo Registro de Faturamento, os campos de um novo Registro de Faturamento não aparecerão e o Registro de Faturamento não poderá ser criado.

**Erro ao fazer atribuição em massa em [!UICONTROL Balanceador de Carga de Trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário tenta fazer atribuições no [!DNL Workload Balancer] de um projeto, o usuário é redirecionado para uma página com a seguinte mensagem:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

O usuário não pode sair desta página até que atualize a página.

**Navegação atualizada para abrir o [!UICONTROL Resumo] painel para tarefas e problemas no [!UICONTROL Balanceador de Carga de Trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Agora, basta clicar em uma barra de tarefas ou problemas na [!UICONTROL Balanceador de Carga de Trabalho] abre o Painel de resumo. Antes desta atualização, você tinha que clicar no botão [!UICONTROL Abrir resumo] na barra de ferramentas e, em seguida, clique na tarefa ou problema. Esta experiência revelou-se confusa e está agora corrigida. Como alternativa, você pode clicar no botão [!UICONTROL Mais] ao lado do nome da tarefa ou do problema e clique em [!UICONTROL Abrir resumo].

**O administrador de grupo não pode exibir detalhes dos usuários no grupo**

*Usuários*

Quando um usuário é atribuído a um nível de acesso que inclui a variável [!UICONTROL Administrador do usuário (usuários do grupo)] as tentativas de configuração de acesso para exibir detalhes de um usuário em seu grupo exibem o seguinte erro:

&quot;[!UICONTROL Vamos tentar novamente. Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

**Não é possível excluir o status do grupo personalizado**

*Grupos*

Quando um usuário tenta excluir um status de grupo personalizado do [!UICONTROL Grupo] página, a página fica em branco e o status não é excluído.

**As configurações de alerta de email são inconsistentes entre a área Contatos e Detalhes do usuário**

*[!DNL Workfront Proof]*

Configurações de alerta de email exibidas na [!UICONTROL Contatos] área de [!DNL Workfront Proof] para um determinado usuário são diferentes da configuração de alerta por email definida no [!UICONTROL Detalhes do usuário].

**Não é possível usar a ferramenta Texto ao fazer um comentário em uma prova**

*[!DNL Workfront Proof]*

Quando um usuário faz um comentário em uma prova e tenta abrir a variável [!UICONTROL Texto] , a ferramenta não abre e o usuário vê a seguinte mensagem:

&quot;[!UICONTROL Os dados de texto desta página ainda estão sendo baixados. Por favor, espere.]&quot;

**Os emails de prova irão para o email principal do usuário**

*[!DNL Workfront Proof]*

Estamos fazendo ajustes em como as notificações por email de prova são enviadas. Agora, as notificações vão para o endereço de email principal do usuário, em vez do email alias gerado pelo sistema.

Para obter mais informações sobre por que o sistema gera emails de alias, consulte Sincronização do usuário entre o Adobe [!DNL Workfront] e [!DNL Workfront Proof].

+++

## Atualizações em abril de 2022

+++**Atualização de manutenção em 28 de abril de 2022**

**Não é possível rolar para [!UICONTROL Salvar] ao editar uma folha de ponto**

*Planilhas de horas*

Quando um usuário está editando uma folha de ponto, ele não pode rolar a janela de edição o suficiente para ver a variável [!UICONTROL Salvar] e, portanto, não pode editar a folha de ponto.

**A assinatura eletrônica agora verifica a ID da Federação**

*Provas*

Ao assinar uma prova eletronicamente, o sistema agora verifica a ID da Federação, caso tenha o SSO configurado em [!DNL Workfront Proof], além do email em [!DNL Workfront].

Anteriormente, o sistema verificava somente seu email no Workfront.

+++

+++**Atualização de manutenção (hotfix) em 25 de abril de 2022**

**[!UICONTROL Balanceador de Carga de Trabalho] não carrega**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário tenta abrir o [!UICONTROL Balanceador de Carga de Trabalho], o cabeçalho e a carga de navegação à esquerda, mas o conteúdo do Balanceador de Carga de Trabalho não é carregado. O usuário vê quadrados cinza piscando em vez de dados. Ocasionalmente, parte do conteúdo é carregada, mas o usuário ainda vê quadrados cinza piscando, onde os dados ausentes estariam.

+++

+++**Atualização de manutenção em 21 de abril de 2022**

**Adicionar uma tarefa faz com que a página salte para baixo**

*Tarefas*

Quando um usuário adiciona uma tarefa abaixo de uma tarefa existente em uma lista, a página salta para baixo na lista. Embora a nova tarefa esteja no local correto, o usuário deve rolar de volta para localizá-la.

**Os usuários adicionados a uma prova não podem acessar o item de trabalho da prova em[!DNL Workfront]**

*Provas*

Se um usuário for adicionado a um estágio no fluxo de trabalho de uma prova, ele não será adicionado ao Compartilhamento de documentos e não obterá permissões para o item de trabalho da prova em [!DNL Workfront]. Quando o usuário estiver em [!DNL Workfront] e tentar abrir o item de trabalho ao qual a prova está anexada, eles verão a seguinte mensagem:

&quot;[!UICONTROL Você não tem acesso suficiente para visualizar isso (objeto)]&quot;

Esse problema é específico para provas já criadas e usuários adicionados após o fato. Adicionar usuários ao fluxo de trabalho antes da criação da prova funcionar conforme esperado.

**Não é possível enviar email de redefinição de senha a partir de[!DNL Workfront]**

*Usuários*

Quando um usuário tenta enviar um email de redefinição de senha a partir de uma lista de usuários em [!DNL Workfront], a opção para enviar o email não está disponível.

**O botão exibe &quot;[!UICONTROL Problema inicial]&quot; em vez de &quot;[!UICONTROL Iniciar solicitação]&quot;**

*Solicitações*

Quando um usuário exibe uma solicitação atribuída à equipe, ele vê um &quot;[!UICONTROL Problema inicial]&quot; no cabeçalho em vez de um &quot;[!UICONTROL Iniciar solicitação]Botão &quot;.

**&quot;[!UICONTROL Desfazer comentário]&quot; remove os usuários marcados**

*Atualizações*

Quando um usuário marca outro usuário em um comentário, publica esse comentário e, em seguida, seleciona o &quot;[!UICONTROL Desfazer comentário]&quot;, o comentário aparece em uma caixa de atualização como de costume, mas o usuário marcado não está no [!UICONTROL Usuários marcados] caixa.

**Não é possível rolar ao usar [!UICONTROL Marco] exibir em um relatório**

*Relatórios*

Quando um usuário exibe um relatório e seleciona a variável [!UICONTROL Marco] , a página exibe a visualização do Marco, mas não é mais rolada, e o usuário não pode visualizar os marcos que estariam mais abaixo na página.

**Moeda incorreta quando o relatório é exibido no painel**

*Relatórios*

Quando um usuário exibe um relatório em um painel, a moeda usada no relatório está incorreta. Quando o usuário exibe o relatório fora do painel, a moeda está correta.

**O filtro concluído não está exibindo o item de trabalho Concluído**&#x200B; s

*[!UICONTROL Início]*

Quando um usuário exibe sua [!UICONTROL Lista de Trabalho Doméstica] com o [!UICONTROL Concluído] filtro selecionado, os itens de trabalho concluídos não são exibidos na lista. Quando a variável [!UICONTROL Todos] for selecionado, os itens Concluídos serão incluídos na lista, mostrando que os itens Concluídos existem.

**[!DNL Workfront]não carrega**

*[!DNL Workfront]*

Quando um usuário tenta fazer logon em [!DNL Workfront], a página parece estar presa em um loop de redirecionamentos ou atualizações e não é carregada.

+++

+++**Atualização de manutenção em 14 de abril de 2022**

**Não é possível adicionar uma tarefa de um relatório em uma seção personalizada em uma tarefa**

*Tarefas*

Quando um usuário exibe uma seção personalizada em uma tarefa e a seção contém um relatório de tarefa, o usuário não pode adicionar uma tarefa a partir desse relatório. O [!UICONTROL Adicionar tarefa] O botão realça o relatório, mas não abre uma janela para o usuário adicionar uma tarefa.

**Botão Concluído no local errado ao editar uma exibição**

*Visualizações*

Quando um usuário edita uma exibição, a variável [!UICONTROL Concluído] aparece mais alto na tela e pode sobrepor o texto.

O usuário pode editar a visualização como de costume. A funcionalidade não é afetada.

**Não é possível rolar ao usar [!UICONTROL Marco] exibir em um relatório**

*Relatórios*

Quando um usuário exibe um relatório e seleciona a variável [!UICONTROL Marco] , a página exibe a visualização do Marco, mas não é mais rolada, e o usuário não pode visualizar os marcos que estariam mais abaixo na página.

**Tela em branco ao visualizar atualizações**

*Atualizações*

Quando um usuário está visualizando atualizações e rola a tela para exibi-las ainda mais para baixo, a tela fica em branco e o usuário não pode visualizar nenhuma atualização.

**Erro ao atribuir o usuário em massa à tarefa que não está atribuída à função do usuário**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário na [!UICONTROL Balanceador de Carga de Trabalho] tenta atribuir tarefas a um usuário cuja Função de Trabalho não corresponde à função Trabalho atribuída às tarefas, o usuário vê uma mensagem de que a tarefa será atribuída usando a Função de Trabalho principal do usuário atribuído. No entanto, quando o usuário clica em &quot;[!UICONTROL Atribuir],&quot; as tarefas não são atribuídas e o usuário vê o seguinte erro:

&quot;[!UICONTROL Erro. O servidor encontrou um erro desconhecido.]&quot;

+++

+++**Atualização de manutenção em 7 de abril de 2022**

**Os usuários adicionados às provas têm funções incorretas**

*Provas*

Quando um usuário adiciona outro usuário a uma prova, a função dele na prova é definida como &quot;[!UICONTROL Somente leitura]&quot; apesar da função de prova real do usuário.

**Não é possível enviar email de redefinição de senha para o usuário**

*Usuários*

Quando um usuário tenta enviar uma redefinição de senha para outro usuário, ele vê que a variável [!UICONTROL Enviar e-mail de Esquecimento de Senha] não está disponível na variável [!UICONTROL Mais] menu.

**[!UICONTROL Atualizar tudo] envia atualizações para perfis de usuário em vez de projeto**

*Atualizações*

Quando um usuário exibe a variável [!UICONTROL Pessoas] área de um projeto e seleciona a variável [!UICONTROL Atualizar tudo] , em seguida insere uma atualização, a atualização não é postada no próprio projeto. Em vez disso, é publicado nos perfis de usuário individuais de cada usuário no projeto.

**Número excessivo de páginas ao imprimir atualizações**

*Atualizações*

Quando um usuário está visualizando um fluxo de atualização que seria mais de uma página impressa e tenta imprimir a página, a tela de impressão mostra que o número de páginas está muito acima do número real de páginas necessárias para imprimir as atualizações. Se o usuário tentar imprimir no PDF, a criação do PDF falhará.

**Os usuários não podem ver toda a lista de entidades compartilhadas com um relatório quando a variável &quot;[!UICONTROL Sistema visível]&quot; está ativada**

*Relatórios*

Ao compartilhar relatórios com várias entidades da [!UICONTROL Acesso ao Relatório] , os usuários não conseguem rolar para a parte inferior da lista para ver toda a lista quando o &quot;[!UICONTROL Sistema visível]&quot; ativada.

**Moeda incorreta usada em relatórios**

*Relatórios*

Se um usuário definir que a moeda de um projeto seja diferente da moeda padrão e, em seguida, visualizar um relatório sobre esse projeto, a moeda será exibida como a moeda padrão em vez da moeda do projeto.

**Últimas informações visualizadas que não foram atualizadas em [!UICONTROL Uso de relatórios] relatórios**

*Relatórios*

Quando um usuário exibe um relatório que exibe informações sobre a última vez que o relatório foi visualizado, essas informações podem estar em branco ou ser dados antigos. Esse problema afeta campos, incluindo o seguinte:

* [!UICONTROL Última Visualização realizada por]
* [!UICONTROL Últimos dados visualizados]
* [!UICONTROL Últimos X Viewers]
* [!UICONTROL Exibições neste mês/trimestre/ano]

**Tarefas concluídas exibindo em [!UICONTROL Lista de Trabalho Doméstica]**

*[!UICONTROL Início]*

Quando um usuário exibe a [!UICONTROL Lista de Trabalho Doméstica], eles visualizam Concluir tarefas na lista, mesmo quando a opção para exibir Tarefas concluídas não está selecionada.

**Botão Agendar não visível para agendar a atualização da sandbox**

*Ambiente de sandbox*

O [!UICONTROL Agendar] O botão usado para programar uma atualização da sandbox não está visível no banner superior do ambiente da sandbox.

**As alterações em um campo calculado afetam todos os campos calculados em um formulário**

*Formulários personalizados*

Quando um usuário está no Construtor de formulários personalizado e altera o valor de um formulário calculado, todos os campos calculados no formulário mostram o novo valor. Isso pode afetar campos calculados novos ou existentes.

**Cores que cintilam no construtor de formulários personalizado**

*Formulários personalizados*

Quando um usuário está trabalhando com campos calculados no construtor de formulários personalizado, as cores dos campos e expressões cintilam.

**[!UICONTROL Não é possível rejeitar uma aprovação]**

*Aprovações*

Quando um usuário tenta rejeitar uma aprovação, a variável [!UICONTROL Rejeitar] não responde, e a aprovação não é rejeitada.

**[!UICONTROL Projetos] guia assume como padrão a seção Todos os projetos apesar da seleção anterior**

*Projetos*

Quando um usuário acessa uma página de Projetos por meio de uma guia que foi fixada como parte do modelo de layout, a página assume o padrão de [!UICONTROL Todos os projetos] área da navegação à esquerda. Isso ocorre mesmo quando o usuário escolhe outra área da navegação à esquerda e, em seguida, navega para fora da página Projetos e para trás.

+++


## Atualizações em março de 2022

+++**Atualização de manutenção em 31 de março de 2022**

**Fusos horários não são consistentes entre [!DNL Workfront] e[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando o perfil de um usuário é definido como um fuso horário específico em [!DNL Workfront], o fuso horário do usuário em [!DNL Workfront Proof] é definido como um fuso horário diferente.

**Link para enviar um documento solicitado leva a uma página em branco**

*Documentos*

Quando um usuário recebe uma solicitação para enviar um documento e clica no link para o objeto no qual o documento foi solicitado, o link leva a uma página em branco. Isso pode ocorrer ao clicar em um link em um email ou em uma notificação no aplicativo.

**O grupo é atribuído incorretamente ao converter o problema em projeto**

Grupos

Quando um usuário converte um problema em um projeto usando um modelo, a funcionalidade é:

* Se o modelo tiver um grupo atribuído, esse grupo será exibido na janela de conversão de problemas como o grupo para o novo projeto.
* Se o modelo não tiver nenhum grupo atribuído, o grupo padrão do usuário que está convertendo o problema é exibido na janela de conversão de emissão como o grupo para o novo projeto.
* Se o modelo não tiver um grupo, o novo projeto deve herdar o grupo do projeto do problema.

**Não é possível anexar formulário personalizado entre objetos à fila de solicitações**

Solicitações

Quando um usuário tenta adicionar um formulário personalizado entre objetos à página de detalhes de uma fila, o formulário entre objetos não é exibido na lista suspensa de formulários disponíveis e o usuário não pode selecioná-lo para adicioná-lo aos detalhes da fila.

**Os usuários não podem ser atribuídos com a função de trabalho secundário em [!UICONTROL Balanceador de Carga de Trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário tenta atribuir outro usuário a uma tarefa na [!UICONTROL Balanceador de Carga de Trabalho]e a tarefa for atribuída a uma função de trabalho diferente da função de trabalho primária do usuário atribuído, o usuário será atribuído à tarefa pela função de trabalho principal e a seguinte mensagem será exibida:

&quot;\&lt;name> não corresponde à função de \&lt;task role=&quot;&quot; assignment=&quot;&quot;>. 1 item de trabalho atualmente atribuído à função de &lt;\Tarefa atribuição de função\> será atribuído a \&lt;name> na função de \&lt;primary job=&quot;&quot; role=&quot;&quot;>.&quot;

Isso ocorre mesmo se o usuário tiver a função de trabalho da atribuição da função Tarefa como uma função de trabalho secundária.

**Problema com a Placa de Rolagem &quot;Mostrar mais itens de trabalho&quot; b**&#x200B; ar

*Agile*

Quando um usuário clica no botão [!UICONTROL Mostrar mais itens de trabalho] barra em um Quadro de controle, em seguida, role para ver os novos itens, a [!UICONTROL Mostrar mais itens de trabalho] A barra gruda no Quadro de controle e se move com ele ao rolar. Isso pode tornar os cartões difíceis de ler.

**Os pontos vermelhos são exibidos nos campos obrigatórios em formulários personalizados**

Formulários personalizados

Quando um usuário exibe um campo obrigatório em um formulário personalizado, ele vê dois pontos vermelhos abaixo do asterisco que indica que o campo é obrigatório.

**Tempo limite suspenso cortado em prompts**

*Relatórios*

Quando um usuário está preenchendo as solicitações de um relatório e encontra um seletor de datas, o seletor de tempo na parte inferior do seletor de datas não exibe horas além de 2 e o usuário não pode selecionar nenhum valor de hora além de 1 ou 2.

+++

+++**Atualização de manutenção (hotfix) em 29 de março de 2022**

**Não é possível modificar ou salvar cálculos no Criador de formulários personalizado**

*Formulários personalizados no meu grupo*

Se um usuário insere manualmente um cálculo em um campo de cálculo no construtor de Formulários personalizados e salva o formulário, o cálculo não é salvo. Se o usuário reabrir o formulário personalizado, esse campo ficará em branco.

Se um usuário digitar um cálculo em um campo de cálculo no Criador de formulários personalizado usando os menus suspensos e salvar o formulário, esse valor será salvo. No entanto, se o usuário reabrir o formulário personalizado, não poderá editar esse campo ou remover o valor manualmente ou com a lista suspensa.

OBSERVAÇÃO: Essa correção de problema incluía funcionalidade adicional. Agora, quando você começa a digitar em um campo calculado, expressões possíveis ou cálculos são exibidos em uma lista suspensa abaixo, da mesma forma que no Editor de cálculos. Clique em um item na lista suspensa para adicioná-lo ao campo calculado.

+++

+++**Atualização de manutenção em 24 de março de 2022**

**Fusos horários não são consistentes entre [!DNL Workfront] e[!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

Quando o perfil de um usuário é definido como um fuso horário específico em [!DNL Workfront], o fuso horário do usuário em [!DNL Workfront Proof] é definido como um fuso horário diferente.

**Erro de campo obrigatório para campos personalizados preenchidos ao anexar um modelo**

*Projetos*

Ao anexar um modelo com campos personalizados obrigatórios a um projeto em que o campo já existe e é preenchido, os usuários veem o seguinte erro: &quot;[!UICONTROL Há campos incompletos. Insira valores para os campos obrigatórios antes de continuar.]&quot; Clicando em &quot;[!UICONTROL Leve-me lá]&quot; permite que eles vejam que os campos estão preenchidos e podem anexar o modelo com êxito.

**O [!UICONTROL Balanceador de Carga de Trabalho] flashes quando você alterna entre datas**

*[!UICONTROL Balanceador de carga de trabalho]*

As horas do usuário listadas primeiro na [!UICONTROL Balanceador de Carga de Trabalho] não exibir ao atualizar a linha do tempo. O usuário e suas horas são exibidas com todas as caixas cinza que apenas piscam. Isso acontece se você avançar e retroceder na linha do tempo.

Atualizar o filtro parece redefinir a exibição. No entanto, mover-se para trás e para a frente na linha do tempo faz com que o flash de exibição volte e o horário do usuário não seja exibido.

**A terminologia personalizada está inconsistente**

*Modelos de layout*

Os usuários relatam isso quando a variável [!DNL Workfront] O administrador personaliza a terminologia de alguns objetos usando um Modelo de layout, o novo nome do objeto é exibido de forma inconsistente na interface.

Por exemplo, no [!UICONTROL Projetos] ainda é possível ver o título da página exibido como &quot;[!UICONTROL Projetos]&quot;, embora a variável [!DNL Workfront] o administrador alterou o nome de &quot;[!UICONTROL Projetos]&quot; para outra coisa.

Isso causa confusão para os usuários finais.

+++

+++**Atualização de manutenção em 17 de março de 2022**

**As miniaturas e imagens principais ficam em branco ao visualizar arquivos de várias páginas usando [!DNL Safari] navegador**

*[!DNL Workfront Proof]*

Quando um usuário tenta visualizar um arquivo com várias páginas na [!DNL Safari] no navegador, as imagens da página de miniatura ficam em branco. Ocasionalmente, a imagem principal também pode estar em branco.

**Lista de usuários incorreta ao fazer atribuições em massa no [!UICONTROL Balanceador de Carga de Trabalho]**

*[!UICONTROL Balanceador de carga de trabalho]*

Quando um usuário faz uma atribuição em massa na [!UICONTROL Balanceador de Carga de Trabalho] e seleciona um Projeto e uma Função de trabalho, a lista de usuários disponíveis está incorreta. Pode mostrar usuários sem as permissões Função de trabalho ou Projeto e os usuários com as permissões Função de trabalho e Projeto não aparecem na lista.

**[!UICONTROL A classificação não está funcionando nos relatórios]**

*Relatórios*

Quando um usuário clica em uma coluna para classificar por ela, a classificação parece funcionar, mas instantaneamente os resultados são revertidos para a classificação original como eram exibidos antes de clicar na coluna. A classificação em qualquer coluna não é retida.

**Selecionar &quot;[!UICONTROL Nada]&quot; reverte para o [!UICONTROL Padrão do relatório] agrupamento**

*Relatórios*

Quando um relatório tem um agrupamento incorporado e o usuário tenta selecionar &quot;[!UICONTROL Nada]&quot; na [!UICONTROL Agrupamento] no menu suspenso , o relatório é exibido brevemente sem agrupamento e, em seguida, reverte para o [!UICONTROL Padrão do relatório] agrupamento.

**Removido &quot;[!UICONTROL Acesso a blueprints]&quot; guia de preferências do Blueprints**

*Blueprints*

OBSERVAÇÃO: Esse problema existe apenas no ambiente de Visualização.

O [!UICONTROL Acesso a blueprints] A guia foi removida do modal de preferências Blueprints. Nenhuma funcionalidade foi removida das preferências do Blueprints.

+++

+++**Atualização de manutenção (hotfix) em 14 de março de 2022**

**Não é possível rolar a lista de usuários para baixo ao fazer atribuição no quadro Kanban**

*Ágil*

Quando um usuário exibe uma [!DNL Kanban] quadro e tenta fazer uma atribuição, a lista de usuários exibida quando eles digitam continua pulando de volta para o topo à medida que rolam para baixo. O usuário não pode selecionar um usuário que não esteja perto do topo da lista e não pode salvar a alteração de atribuição.

**[!UICONTROL Marco] A visualização no relatório do projeto causa erro**

*Relatórios*

Ao exibir um relatório de projeto usando o [!UICONTROL Marco] Exibir, os usuários obtêm um &quot;[!UICONTROL APIModel INTERNAL não suporta o nomeQuery TILE:milestone-view (UIVW)]&quot;.

**A terminologia personalizada está inconsistente**

*Modelos de layout*

Os usuários relatam isso quando a variável [!DNL Workfront] O administrador personaliza a terminologia de alguns objetos usando um Modelo de layout, o novo nome do objeto é exibido de forma inconsistente na interface.

Por exemplo, no [!UICONTROL Projetos] ainda é possível ver o título da página exibido como &quot;[!UICONTROL Projetos]&quot;, embora a variável [!DNL Workfront] o administrador alterou o nome de &quot;[!UICONTROL Projetos]&quot; para outra coisa.

Isso causa confusão para os usuários finais.

**Não é possível atualizar cálculos para campos calculados existentes**

*Formulários personalizados*

Os usuários não podem atualizar/alterar os cálculos nos campos calculados. Se o campo foi criado e salvo com sem um cálculo, toda vez que você tenta adicionar uma expressão e salvar/aplicar, o construtor volta a ficar em branco.

Se você criar um campo calculado com uma determinada expressão e salvá-lo, sempre que tentar alterar o cálculo, ele será revertido para o valor anterior.

**[!UICONTROL Parâmetro inválido] erro ao redefinir senhas**

*Logon*

Os usuários não podem redefinir suas senhas em nenhum ambiente. Quando eles entram no email e tentam continuar, eles veem um erro.

[!UICONTROL Erro: Parâmetro inválido: Valor do parâmetro de pesquisa &quot;domínio&quot;].

+++

+++**Atualização de manutenção em 10 de março de 2022**

**Problemas ao fazer logon no ambiente de Visualização**

*Logon*

Os seguintes problemas com o logon no ambiente de Visualização foram relatados.

Quando um usuário tenta fazer logon no ambiente de Visualização, é exibida uma mensagem indicando que ele colocou a ID ou a senha incorreta.

Quando um usuário tenta redefinir sua senha, ele vê o erro &quot;[!UICONTROL ?Vários usuários foram encontrados com o endereço de email <example@example.com>?]&quot;

**Os formulários personalizados são carregados lentamente em [!UICONTROL Detalhes do projeto] area**

*Projetos*

Quando um usuário tenta visualizar o relatório de um projeto [!UICONTROL Detalhes do projeto] , todos os formulários personalizados anexados ao projeto são carregados somente após um atraso de 15 segundos ou mais. O [!UICONTROL Adicionar formulários personalizados] também é afetada por esse atraso.

**Valores de campos de formulário personalizados não salvos no painel de resumo do documento**

*Documentos*

Quando um usuário atualiza campos de formulário personalizados no painel de resumo do documento, e um ou mais deles é um campo do tipo , salva as alterações e sai do painel de resumo, as atualizações não são salvas. Isso ocorre somente quando um campo typeahead é editado, embora todos os campos sejam afetados.

**Dados não preservados ao converter modelos devido ao compartilhamento de modelos de níveis de acesso**

*Projetos*

Quando um usuário que tem acesso à Exibição em um modelo compartilhado tenta converter um problema em um projeto, quaisquer dados em seções de formulário personalizadas que exigem [!UICONTROL Contributo] ou o acesso superior à visualização não é transferido para o projeto criado.

**Erro ao carregar a nova versão do documento**

*Documentos*

Quando um usuário tenta fazer upload de uma nova versão de um documento na lista de documentos, o documento não é carregado e o usuário vê o seguinte erro:

[!UICONTROL Erro Não é possível invocar &quot;com.attask.boz.Document.getCurrentVersion()&quot; porque &quot;document&quot; é nulo]

**Não é possível editar taxas de faturamento**

*Projetos*

Quando um usuário tenta editar uma taxa de faturamento no [!UICONTROL Taxas de Faturamento] de um projeto, clicando na guia [!UICONTROL Editar] botão abre [!UICONTROL Editar] brevemente, mas será fechado antes que o usuário possa editar a taxa de faturamento. Clicar no botão novamente não abre a janela de edição.

**Link público para documentos leva a página em branco**

*Documentos*

Quando um usuário tenta abrir um documento usando um link público, o link leva a uma página em branco. Isso ocorre quando o link é aberto em uma janela em que um [!DNL Workfront] sessão aberta.

**Erro Whops ao adicionar tarefa ou problema à lista**

*Tarefas e problemas*

Quando um usuário que não é um administrador tenta adicionar uma tarefa ou um problema a uma lista e preenche campos personalizados, a tarefa ou o problema não é criado e o usuário vê o seguinte erro:

[!UICONTROL Erro! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]

**Deixar uma atualização após uma alteração de status reverte o objeto para um estado anterior**

Projetos, tarefas e problemas

Alterar o status de um projeto, tarefa ou problema e começar imediatamente a digitar uma atualização sem atualizar a página faz com que a caixa de atualização mostre o status anterior. Se a atualização for publicada, o objeto será revertido para o status anterior.

**Os usuários adicionados às provas têm funções incorretas**

*Provas*

Quando um usuário adiciona outro usuário a uma prova, a função dele na prova é definida como &quot;[!UICONTROL Somente leitura]&quot; apesar da função de prova real do usuário.

Solução alternativa: Defina a função de prova do usuário em seu perfil para outra coisa e redefina para a função correta.

**O formulário personalizado não carrega ao converter o problema em um projeto usando o modelo**

*Formulários personalizados no meu grupo*

Quando um usuário tenta converter um problema em um projeto usando um modelo, um ou mais formulários personalizados anexados ao modelo podem não ser carregados. Quando o usuário configura o modelo para o novo projeto, em vez dos formulários personalizados, ele vê a seguinte mensagem:

&quot;[!UICONTROL Algo deu errado, não foi possível carregar o formulário].&quot;

**O usuário não pode adicionar o problema em linha com o campo suspenso personalizado exibido na exibição**

*Listas*

Quando um usuário está adicionando um problema embutido e há uma exibição personalizada com campos suspensos personalizados aplicados à lista, há um erro quando ele preenche apenas o campo suspenso. O usuário tem acesso para editar um formulário personalizado e é o proprietário do projeto com direitos de gerenciamento ao projeto.

[!UICONTROL Erro: Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo!]

**As permissões para adicionar tarefas a um projeto não são necessárias para mover ou copiar uma tarefa para o projeto**

*Tarefas*

Agora é possível mover ou copiar uma tarefa para outra tarefa em um projeto sem ter permissões para adicionar tarefas ao projeto de destino. Você deve ter permissões para adicionar tarefas a pelo menos uma das tarefas do projeto de destino. Antes desta atualização, você tinha permissões para adicionar tarefas ao projeto para mover ou copiar uma tarefa para o projeto ou para qualquer uma de suas tarefas.  Essa atualização está disponível no ambiente de Produção. Ele está disponível no ambiente de Visualização, a partir da atualização de manutenção de 24 de março de 2022.

OBSERVAÇÃO: Essa atualização estará disponível no ambiente de Produção ao copiar ou mover problemas após a versão 2.2 Produção. Para obter mais informações sobre a versão atual, consulte workfront.com/release.

**O menu suspenso Prompt é cortado**

*Relatórios*

Ao usar um prompt em um relatório, os menus suspensos que permitem selecionar os critérios de filtragem do relatório são cortados. Como resultado, os critérios na parte inferior do menu suspenso de seleção não são exibidos.

**O item de trabalho reverte para o status anterior quando uma atualização é feita**

*Atualizações*

Quando um usuário altera o status de um item de trabalho no cabeçalho, o status não é atualizado na variável [!UICONTROL Atualizar] área. Se o usuário fizer uma atualização, a lista suspensa ainda mostrará o status anterior. Quando a atualização é salva, esse status anterior e incorreto substitui o status definido no cabeçalho.

+++

+++**Atualização de manutenção em 3 de março de 2022**

**Não é possível adicionar documento a partir de[!DNL Google Drive]**

*Documentos*

Quando um usuário tenta adicionar um documento de [!DNL Google Drive], a seleção não responde e o usuário não pode selecionar documentos para adicionar.

**Os usuários marcados não são adicionados ao thread de atualização**

*Atualizações*

Quando um usuário é marcado em uma atualização, ele não é mostrado no &quot;[!UICONTROL Para]&quot; área da atualização ou suas respostas.

**O usuário de prova tem duas contas de prova separadas**

*[!DNL Workfront Proof]*

O endereço de email de um usuário em [!DNL Workfront Proof] pode estar em duas contas separadas com IDs separadas, dando ao usuário duas contas. Isso pode dificultar a localização da conta correta.

**Erro de toques exibido nos cabeçalhos do relatório**

*Relatórios*

Quando um usuário exibe um relatório, o seguinte erro é exibido no cabeçalho do relatório:

&quot;[!UICONTROL Vamos tentar novamente. Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

Se o usuário estiver visualizando um painel, o erro poderá aparecer no cabeçalho de todos os relatórios no painel.

**Os dados em campos exclusivos de edição de administrador do formulário personalizado não são preservados durante a conversão de problemas em projetos**

*Projetos*

Quando um usuário não administrador tenta converter um problema em um projeto usando um modelo e o problema contém dados em campos que só podem ser editados por um administrador, os dados nesses campos não são transferidos para o novo projeto.

Quando um administrador converte o problema, os dados são transportados para o novo projeto, como esperado.

**[!DNL XLS]e [!DNL XLSX] limite de tamanho de arquivo temporariamente reduzido para 100 MB para provas**

*Prova*

Para solucionar um problema de segurança, limitamos temporariamente o tamanho máximo de arquivo para [!DNL XLS] e [!DNL XLSX] para 100 MB ao criar uma prova.

OBSERVAÇÃO: Essa atualização foi realizada no ambiente de Visualização em 24 de fevereiro e estará no ambiente Produção em 3 de março.

**Atualizar para Workfront Search**

Pesquisar

Uma implantação em fases começou esta semana para atualizar a infraestrutura para a [!DNL Workfront] Funcionalidade de pesquisa. A atualização tornará as melhorias futuras da Pesquisa mais fáceis e confiáveis. Com essas alterações, os itens adicionados a [!DNL Workfront] serão indexados mais rapidamente e, portanto, retornarão nos resultados da pesquisa mais cedo.

A distribuição em fases continuará por 2 semanas.

**Barras de ferramentas atualizadas para relatórios nos painéis**

Relatórios

Os relatórios nos painéis agora mostram uma nova barra de ferramentas. Essa barra de ferramentas faz parte das atualizações para listas e relatórios que estão acontecendo em todo o [!DNL Workfront].

+++


## Atualizações em fevereiro de 2022

+++**Atualização de manutenção (hotfix) em 24 de fevereiro de 2022**

**Dados não preservados ao converter problemas em projetos se o campo estiver oculto no modelo**

*Projetos*

Quando um usuário converte um problema em um modelo e o modelo inclui um formulário personalizado que exibe ou oculta campos com base nos valores em outros campos, os dados nos campos ocultos no modelo (sem dados) no momento da conversão não são transportados para o novo projeto.

**Não é possível exportar o planejador de recursos por Função**

*Planejamento de recursos*

Quando um usuário tenta exportar a variável [!DNL Resource Planner] ao usar a variável [!UICONTROL Exibir por função] , a exportação não é bem-sucedida e o usuário recebe um email com a seguinte mensagem:

Ocorreu um erro ao exportar o [!DNL Resource Planner] dados.

**Botão Copiar solicitação não funciona**

*Solicitações*

Quando um usuário tenta copiar uma solicitação, a variável [!UICONTROL Copiar solicitação] não funcionará se o usuário não tiver acesso de Exibição ao tópico da fila.

+++

+++**Atualização de manutenção em 24 de fevereiro de 2022**

**Os dados personalizados do formulário desaparecem quando outros campos de formulário são preenchidos**

*Formulários personalizados no meu grupo*

Quando um usuário preenche um formulário personalizado como parte da conversão de um problema em um projeto, o preenchimento de um campo personalizado pode fazer com que os dados de outro campo personalizado desapareçam. Se o usuário digitar os dados ausentes novamente, ao tentar criar o projeto, verá a seguinte mensagem de erro:

&quot;[!UICONTROL Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado]&quot;

**&quot;[!UICONTROL Esse processo de aprovação pode ser usado por..]&quot; campo ausente**

*Aprovações*

Quando um usuário cria ou edita um processo de aprovação na [!UICONTROL Configuração] área, o &quot;[!UICONTROL Esse processo de aprovação pode ser usado por..]&quot; campo ausente. Isso pode ocorrer ao criar um processo de aprovação ou ao editar um existente.

**O administrador do sistema não pode reatribuir usuários ao excluir um grupo**

*Grupos*

Quando um administrador do sistema excluir um grupo, ele só terá a opção de reatribuir os usuários desse grupo a grupos para os quais o administrador do sistema é um administrador de grupo. Outros grupos não aparecem na lista suspensa e o administrador não pode selecioná-los.

**Erro Whops ao converter o problema em projeto**

*Projetos*

Quando um usuário tenta converter um problema em um projeto usando um modelo e adiciona ou remove formulários personalizados do modelo, o problema não é convertido e o usuário vê a seguinte mensagem:

[!UICONTROL Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]

**Não é possível abrir prova; atualizações de página**

*Provas*

Quando um usuário tenta abrir uma prova, ela não consegue abri-la. Eventualmente, a página é atualizada.

**[!DNL XLS]e [!DNL XLSX] limite de tamanho de arquivo temporariamente reduzido para 100 MB para provas**

*Prova*

Para solucionar um problema de segurança, limitamos temporariamente o tamanho máximo de arquivo para [!DNL XLS] e [!DNL XLSX] para 100 MB ao criar uma prova.

OBSERVAÇÃO: Essa atualização estará no ambiente de Pré-visualização em 24 de fevereiro e no ambiente Produção em 3 de março.

**Permissões para adicionar tarefas ou problemas a um projeto não são necessárias para mover ou copiar uma tarefa ou um problema para o projeto**

*Projetos*

Agora é possível mover ou copiar uma tarefa ou um problema para outra tarefa em um projeto sem ter permissões para adicionar tarefas ou problemas ao projeto de destino. Você deve ter permissões para adicionar tarefas ou problemas a pelo menos uma das tarefas do projeto de destino. Antes desta atualização, você tinha permissões para adicionar tarefas ou problemas ao projeto para mover ou copiar uma tarefa ou um problema para o projeto ou para qualquer uma de suas tarefas. Esta atualização está disponível somente no ambiente de Visualização.

OBSERVAÇÃO: Essa atualização estará disponível no ambiente de Produção ao copiar ou mover tarefas em 10 de março. Essa atualização estará disponível no ambiente de Produção ao copiar ou mover problemas com a versão 2.2 Produção. Para obter mais informações sobre a versão atual, consulte workfront.com/release.

**Atualizar para Workfront Search**

*Pesquisar*

Uma implantação em fases começou esta semana para atualizar a infraestrutura para a [!DNL Workfront] Funcionalidade de pesquisa. A atualização tornará as melhorias futuras da Pesquisa mais fáceis e confiáveis. Com essas alterações, os itens adicionados a [!DNL Workfront] serão indexados mais rapidamente e, portanto, retornarão nos resultados da pesquisa mais cedo.

A distribuição em fases continuará por 2 semanas.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 18 de fevereiro de 2022**

**Validação do tipo de valor de campo adicionada a [!DNL Anaplan] propriedades de itens de lista**

*[!DNL Adobe Workfront Fusion]*

Foi corrigido um problema que permitia aos usuários colocar o tipo de dados incorreto em campos para propriedades de Itens de lista. A validação do tipo de propriedade permite [!DNL Fusion] para garantir que o tipo de dados correto seja enviado para Anaplan, eliminando erros causados por tipos de dados incorretos.

+++

+++**Atualização de manutenção em 17 de fevereiro de 2022**

**Erro ao excluir o antecessor da guia Predecessores**

*Tarefas*

Quando um usuário tenta excluir um antecessor do [!UICONTROL Predecessores] em uma tarefa, a tarefa não é excluída e o usuário vê o seguinte erro:

[!UICONTROL Tarefa com valor(s) de chave primária &quot;&quot; não encontrada]

**Ocorre erro ao abrir a página de usuários**

*Usuários*

Quando um usuário tenta abrir o [!UICONTROL Usuários] , a página não abre e o usuário vê o seguinte erro:

[!UICONTROL Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]

**Sobreposição de elementos no cabeçalho de um relatório em um painel**

*Painéis de Controle*

Quando um usuário exibe um relatório em um painel, ele vê que o ícone de agrupamentos e o rótulo se sobrepõem aos links para [!UICONTROL Detalhes] e [!UICONTROL Resumo].

**Problemas com &quot;[!UICONTROL Mais]&quot; para documentos e provas**

*Documentos*

Quando um usuário seleciona um documento ou uma prova em um [!DNL Workfront Classic] lista de documentos, em seguida, clica em &quot;[!UICONTROL Mais],&quot; eles podem observar um dos seguintes problemas: O botão não responde. Todas as opções no botão são rotuladas como &quot;[!UICONTROL Objeto]&quot; e não pode ser usado.

**Erro &quot;Você deve ser um administrador do sistema&quot; ao criar um projeto**

*Projetos*

Quando um usuário que não é um administrador tenta criar um projeto e anexa um formulário personalizado que tem uma seção disponível somente para administradores, ele não pode criar o projeto e vê o seguinte erro:

&quot;Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado&quot;

**Os dados na seção somente de administrador do formulário personalizado não são preservados ao converter problemas em projetos**

*Projetos*

Quando um usuário converte um problema em um projeto usando um modelo que tem um formulário personalizado com uma seção somente de administrador, os dados na seção somente de administrador não são transferidos para o novo projeto. Isso ocorre mesmo se um administrador estiver convertendo o problema.

+++

+++**Atualização de manutenção em 10 de fevereiro de 2022**

**&quot;[!UICONTROL Você deve ser um administrador do sistema]&quot; ao criar um projeto**

*Projetos*

Quando um usuário que não é um administrador tenta criar um projeto e anexa um formulário personalizado que tem uma seção disponível somente para administradores, ele não pode criar o projeto e vê o seguinte erro:

&quot;[!UICONTROL Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado]&quot;

**Os usuários que foram desativados e reativados não aparecem em [!UICONTROL Contatos de prova]**

*[!DNL Workfront Proof]*

Quando um usuário exibe sua lista de contatos em [!DNL Workfront Proof], os usuários que foram desativados e reativados não aparecem na lista.

**Mensagem &quot;Ocorreu um erro&quot; ao converter um problema em um projeto usando um modelo**

*Projetos*

Quando um usuário que não é um administrador tenta converter um problema em um projeto usando um modelo, os campos de formulário personalizado que estão visíveis apenas para administradores mostram a seguinte mensagem:

&quot;[!UICONTROL Algo deu errado, não foi possível carregar o formulário]&quot;

**Erro &quot;Não é possível carregar conteúdo da página&quot; ao exibir as preferências do projeto**

*Configuração*

Quando um usuário administrador tenta exibir projetos, tarefas ou problemas em [!UICONTROL Preferências do projeto] no [!UICONTROL Configuração] , a página não é carregada e o usuário vê o seguinte erro:

&quot;[!UICONTROL Não é possível carregar o conteúdo da página. Experimente atualizar a página.]&quot;

+++

+++**Atualização de manutenção em 3 de fevereiro de 2022**

**[!UICONTROL BizContext] erro ao fazer logon**

*Logon*

Quando um usuário está tentando fazer logon no [!DNL Workfront], o logon não é bem-sucedido e a seguinte mensagem é exibida:

&quot;[!UICONTROL Vamos tentar novamente. Erro do banco de dados: Falha na confirmação de BizContext!]&quot;

Isso foi relatado no ambiente de Visualização.

**O fluxo de atualização de problema desaparece se o problema estiver pendente de aprovação**

*Atualizações*

Quando um usuário clica no [!UICONTROL Nova atualização] na sequência de atualização de um problema que está pendente de aprovação, todo o fluxo de atualização desaparece.

**Erro ao carregar a nova versão de um documento**

*Documentos*

Quando um usuário tenta fazer upload de uma nova versão de um documento, a nova versão não é carregada e o usuário vê um dos seguintes erros:

* [!UICONTROL documentID não pode ser nulo]
* [!UICONTROL Erro: Parâmetro inválido: valor &quot;undefined&quot; de documentID]

**Link público para documentos leva a página em branco**

*Documentos*

Quando um usuário tenta abrir um documento usando um link público, o link leva a uma página em branco. Isso ocorre quando o link é aberto em uma janela em que um [!DNL Workfront] sessão aberta.

**Controles de lista não funcionam em relatórios em painéis**

*Painéis de Controle*

Quando um usuário exibe um relatório em um painel e tenta alterar o filtro, o agrupamento ou a visualização do relatório, o filtro, o agrupamento ou a visualização não são alterados.

**&quot;[!UICONTROL Você deve ser um administrador do sistema]&quot; ao criar um projeto**

*Projetos*

Quando um usuário que não é um administrador tenta criar um projeto e anexa um formulário personalizado que tem uma seção disponível somente para administradores, ele não pode criar o projeto e vê o seguinte erro:

&quot;[!UICONTROL Você precisa ser um administrador do sistema para mudar este valor do parâmetro de um dado personalizado]&quot;

**Dados personalizados não preservados ao converter o problema em um projeto**

*Projetos*

Quando um usuário converte um problema em um projeto usando um modelo, os dados de um formulário personalizado sobre a emissão não são transferidos para o formulário personalizado comparável no projeto. Isso acontece com dados que estão em campos personalizados e que podem ser ocultos com base nos valores de outros campos personalizados.

**Erro ao converter o problema em projeto**

*Projetos*

Quando um usuário tenta converter um problema em um projeto, o problema não é convertido e o seguinte erro é exibido:

&quot;[!UICONTROL Um erro inesperado ocorreu]&quot;

+++


## Atualizações em janeiro de 2022

+++**Atualização de manutenção em 27 de janeiro de 2022**

**Dados personalizados não preservados ao converter o problema em um projeto**

*Projetos*

Quando um usuário converte um problema em um projeto usando um modelo, os dados de um formulário personalizado sobre a emissão não são transferidos para o formulário personalizado comparável no projeto. Isso acontece com dados que estão em campos personalizados e que podem ser ocultos com base nos valores de outros campos personalizados.

**A lista de usuários em um quadro ágil não é alfabética**

*Ágil*

Quando um usuário exibe a lista de usuários em um quadro ágil, os usuários não são exibidos em ordem alfabética. Em vez disso, os usuários com mais atribuições são listados primeiro.

**Links atualizados para copiar e mover problemas**

*Problemas*

No ambiente de Visualização, os links para copiar e mover problemas foram atualizados para &quot;[!UICONTROL Copiar para]&quot; e &quot;[!UICONTROL Mover para]&quot; tanto na página de edição quanto em uma lista de problemas.

**Adicione até 45 endereços IP à [!DNL Workfront]  lista de permissões**

*Configuração*

O limite de endereços IP adicionados ao [!DNL Workfront] lista de permissões aumentou de 30 para 45.

+++

+++**Atualização de manutenção em 20 de janeiro de 2022**

**&quot;[!UICONTROL Parâmetro inválido]&quot; erro ao criar projeto a partir do modelo**

*Projetos*

Quando um usuário tenta criar um projeto a partir de um modelo e remove um formulário personalizado do modelo ao criar o projeto, o projeto não é criado e o usuário vê um &quot;[!UICONTROL Parâmetro inválido]&quot; mensagem de erro que menciona um campo obrigatório no formulário personalizado removido.

**A lista de usuários não é carregada no [!DNL Safari] navegador**

*Usuários*

Quando um usuário vai para a variável [!UICONTROL Usuários] , o cabeçalho é exibido, mas a lista de usuários não é carregada.

**Atraso ao arrastar tarefas em uma lista faz com que a tarefa se mova para o local errado**

*Listas*

Quando um usuário tenta mover uma tarefa em uma lista arrastando-a, a linha azul que indica onde a tarefa será movida se move muito mais lentamente do que o cursor. Quando o usuário solta a tarefa, ela é movida para onde está a linha azul, mesmo que o cursor aponte para um local diferente na lista.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 14 de janeiro de 2022**

**Alguns campos mapeados são redefinidos ao selecionar [!UICONTROL novo campo a ser mapeado]**

*[!DNL Workfront Fusion]*

Quando pelo menos um campo na variável [!DNL Workfront] [!UICONTROL Criar] ou [!UICONTROL Atualizar] módulos possui mapeamento ativado e um usuário seleciona um novo campo para mapear, os campos mapeados anteriormente ativados perdem os valores de mapeamento.

+++

+++**Atualização de manutenção em 13 de janeiro de 2022**

**Não é possível adicionar um hiperlink a um comentário no painel Resumo**

*Tarefas*

Quando um usuário faz um comentário no painel de resumo de uma tarefa e tenta adicionar um hiperlink ao comentário, a janela do hiperlink é aberta, mas assim que o usuário clica na janela, ela é fechada e não pode adicionar um hiperlink. Se um usuário acessar a janela, ele poderá digitar ou colar um link no campo, mas o hiperlink não será salvo. Em ambos os casos, a tarefa fica desmarcada.

**A página Editar Equipe não é fechada**

*Equipes*

Quando um usuário tenta editar uma equipe, a variável [!DNL Edit team] página não é fechada. O usuário não pode fechar a página clicando em qualquer um dos botões, clicando no X ou navegando para fora da página.

**As notificações por email e no aplicativo não estão sendo enviadas**

*Notificações*

Quando um evento que deve acionar uma notificação ocorre, a notificação não é enviada. Isso pode ocorrer para notificações por email ou no aplicativo, e pode ocorrer mesmo se outras notificações estiverem sendo enviadas.

**[!UICONTROL Meu trabalho] a lista aparece vazia**

*[!UICONTROL Meu trabalho]*

Quando um usuário exibe sua [!UICONTROL Meu trabalho] e o modelo de layout para suas [!UICONTROL Meu trabalho] lista inclui um valor numérico como [!UICONTROL Porcentagem concluída], o [!UICONTROL Meu trabalho] não é exibida.

**[!UICONTROL Porcentagem concluída] e [!UICONTROL Horas concluídas] não pode ser modificado no Agile Board**

*Ágil*

Quando um usuário seleciona &quot;[!UICONTROL Mostrar mais itens de trabalho]&quot; no Agile Board, em seguida, tenta alterar o [!UICONTROL Porcentagem concluída] ou [!UICONTROL Horas concluídas] em um dos itens de trabalho recém-carregados, eles não podem alterar a porcentagem concluída ou as horas concluídas. O [!UICONTROL Porcentagem concluída] também está em cinza, indicando que está inativo.

+++

+++**Atualização de manutenção em 6 de janeiro de 2022**

**&quot;[!UICONTROL Parâmetro inválido]&quot;erro ao anexar modelos ou formulários personalizados a projetos**

*Projetos*

Quando um usuário tenta anexar um formulário personalizado ou um modelo a um projeto existente, preenche os campos obrigatórios no formulário ou modelo personalizado e salva as alterações no projeto, as alterações não são salvas e o usuário vê um &quot;[!UICONTROL Parâmetro inválido]&quot; na parte superior da página de detalhes do projeto.

**Comentários de prova não são exibidos em Atualizações de documento**

*Provas*

Quando um usuário exibe uma prova na variável [!UICONTROL Documentos] , os comentários feitos na prova em si não serão exibidos na variável [!UICONTROL atualizações] área do documento.

**[!UICONTROL Balanceador de carga de trabalho]: &quot;[!UICONTROL ?[Objeto]?]&quot; é exibido nas informações de atribuição excessiva**

*[!UICONTROL Balanceador de carga de trabalho]*

Se um usuário se mostrar superalocado na [!UICONTROL Balanceador de Carga de Trabalho] devido a uma sobreposição de tarefa com o tempo limite do usuário e outro usuário visualizar sua sobrealocação, o &quot;[!UICONTROL Capacidade]&quot; a área das informações de atribuição excessiva exibe &quot;[!UICONTROL ?[Objeto]?]&quot; em vez da capacidade real do usuário.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [[!DNL Workfront] Arquivo de atualizações de manutenção - 2021](2021-updates.md)
