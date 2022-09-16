---
title: Atualizações de manutenção do Workfront para 2021
description: Histórico das atualizações de manutenção de 2021 para [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
source-git-commit: 7fa90198186a7b0f392683d432a7da0424943da2
workflow-type: tm+mt
source-wordcount: '10019'
ht-degree: 3%

---

# 2021 [!DNL Workfront] Atualizações de manutenção

As seguintes atualizações de manutenção foram efetuadas em 2021:

## Atualizações em dezembro de 2021

+++**Atualização de manutenção em 23 de dezembro de 2021**

**Novas tarefas assumem o padrão de restrição de tarefa incorreta**

_Tarefas_

Quando um usuário cria uma nova tarefa usando o &quot;[!UICONTROL Nova tarefa]&quot; e o botão [!UICONTROL Novo Início Padrão da Tarefa] A opção Data está definida como &quot;[!UICONTROL Hoje],&quot; a restrição de tarefa da tarefa criada é definida como &quot;[!UICONTROL Logo que possível]&quot; em vez de &quot;[!UICONTROL Iniciar não antes de].&quot; Isso também pode ocorrer ao usar modelos de projeto.

**Horário de abertura em [!UICONTROL Grupos] A área leva a página em branco**

_Configuração_

Quando um usuário está visualizando grupos na [!UICONTROL Configuração] e tenta abrir, editar ou copiar uma programação, a programação não abre e o usuário vê uma página em branco.

**As alterações não são exibidas ao reorganizar a navegação à esquerda**

_Navegação_

Quando um usuário tenta reorganizar o painel de navegação esquerdo arrastando um item, ele aparece de volta em seu lugar anterior quando o usuário o solta. Se o usuário atualizar a página, o painel esquerdo exibirá a nova ordem.

**O link para enviar um documento solicitado leva a uma página em branco.**

_Documentos_

Quando um usuário recebe uma solicitação para enviar um documento e clica no link para o objeto no qual o documento foi solicitado, o link leva a uma página em branco. Isso pode ocorrer ao clicar em um link em um email ou em uma notificação no aplicativo.

**[!UICONTROL Balanceador de Carga de Trabalho] mostra 0 horas alocadas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário exibe a variável [!UICONTROL Balanceador de Carga de Trabalho] e tem o &quot;[!UICONTROL Mostrar datas projetadas]&quot; ativada, qualquer data no futuro exibirá 0 horas alocadas.

**Provas desaparecem intermitentemente das pastas**

_[!DNL Workfront Proof]_

Quando um usuário que está conectado [!DNL Workfront Proof] visualiza uma pasta, a pasta aparece vazia. Se o usuário fizer o check-back posteriormente, as provas ficarão visíveis.

+++

+++**Atualização de manutenção em 16 de dezembro de 2021**

**Clicar no anúncio na lista de notificações leva a uma página em branco**

_Notificações_

Quando um usuário abre sua lista de notificações da [!UICONTROL Notificações] , em seguida, clicar em um anúncio, eles serão levados para uma página em branco e o anúncio não será exibido.

**O painel Resumo mostra &quot;[!UICONTROL Nenhuma seleção]&quot; quando a tarefa é selecionada**

_Tarefas_

Quando um usuário abre um resumo de documento na [!UICONTROL Documentos] de um projeto, vá para a lista de tarefas, selecione uma tarefa e tente abrir o resumo da tarefa, o resumo da tarefa não será exibido e o usuário visualizará a seguinte mensagem:

[!UICONTROL Nenhuma seleção. Selecione um documento na lista para ver os detalhes.]

A mensagem menciona documentos mesmo que o usuário esteja na lista de tarefas.

**[!UICONTROL Trabalho Não Atribuído] não carrega**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário na [!UICONTROL Balanceador de Carga de Trabalho] cria um filtro usando o [!UICONTROL Atribuição:ID de função] , o [!UICONTROL Trabalho Não Atribuído] não carrega.

**Anexar modelo usando &quot;[!UICONTROL Personalizar e anexar]&quot; limpa valores de campo personalizados**

_Projetos_

Se um usuário anexar um modelo a um projeto usando o &quot;[!UICONTROL Personalizar e anexar]&quot; e o projeto já tiver um formulário personalizado anexado a ele, os valores de campo personalizado não serão transferidos e deverão ser inseridos manualmente novamente. Isso ocorre mesmo quando o modelo inclui o mesmo formulário personalizado.

+++

+++**Atualização de manutenção (hotfix) em 10 de dezembro de 2021**

**[!UICONTROL Boias] erro ao anexar o modelo ao projeto existente**

_Projetos_

Quando um usuário tenta anexar um modelo a um projeto existente, o modelo não é anexado e o usuário vê o seguinte erro:

&quot;[!UICONTROL Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

+++

+++**Atualização de manutenção em 9 de dezembro de 2021**


**Painel de navegação esquerdo recolhido expande-se no carregamento da página**

_Navegação_

Quando um usuário define sua navegação à esquerda para ser recolhida e, em seguida, atualiza uma página, a navegação à esquerda é expandida na página recarregada. A navegação à esquerda também é expandida se o usuário abrir uma página em uma nova guia.

**[!UICONTROL Balanceador de Carga de Trabalho] mostra 0 horas alocadas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário exibe a variável [!UICONTROL Balanceador de Carga de Trabalho] e tem o &quot;[!UICONTROL Mostrar datas projetadas]&quot; ativada, qualquer data no futuro exibirá 0 horas alocadas.

+++

+++**Atualização de manutenção em 8 de dezembro de 2021**

**A aprovação é redefinida quando uma atualização é feita**

_Aprovações_

Se um usuário tomar uma decisão sobre uma aprovação usando o cabeçalho do objeto e fizer imediatamente uma atualização no objeto, os ícones de aprovação reaparecerão no cabeçalho e a decisão de aprovação não será salva.

**[!UICONTROL Não é possível editar uma atribuição em linha em um relatório]**

_Relatórios_

Quando um usuário tenta editar uma atribuição em linha em um relatório, o valor do campo não é alterado e a edição não é salva.


+++

+++**Atualização de manutenção em 2 de dezembro de 2021**

**Barra extra adicionada ao digitar manualmente o URL**

_Solicitações_

Quando um usuário preenche uma solicitação e começa manualmente a digitar em um URL, uma barra extra é adicionada em algum ponto próximo ao início do URL. O usuário não pode excluir a barra.

**As seções personalizadas não podem ser removidas do painel de navegação esquerdo**

_Navegação_

Quando um usuário tenta remover uma seção personalizada do painel de navegação esquerdo clicando no X ao lado da seção , ela não é removida.

**Trabalho não atribuído não é carregado**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário na [!UICONTROL Balanceador de Carga de Trabalho] cria um filtro usando o [!UICONTROL Atribuição:ID de função] , o [!UICONTROL Trabalho Não Atribuído] não carrega.

**Páginas que não estão carregando em determinados navegadores**

_[!DNL Workfront]_

Quando um usuário está trabalhando no [!DNL Workfront], as páginas não são carregadas e o usuário vê a seguinte mensagem de erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

Isto foi reportado em

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Este erro ocorre aleatoriamente e pode afetar qualquer área do [!DNL Workfront].

+++


## Atualizações em novembro de 2021

+++**Atualização de manutenção em 18 de novembro de 2021**

**[!DNL Workfront]para [!DNL Jira] &quot;[!UICONTROL ClientID ou clientSecret inválido]&quot; erro no logon**

_Integrações do Workfront_

Os usuários foram desconectados do [!DNL Jira] para integração com o Workfront. Quando um usuário tenta fazer logon na [!DNL Workfront for Jira] , eles não podem fazer logon e veem o seguinte erro:

&quot;[!UICONTROL ClientID ou clientSecret inválido]&quot;

**O formulário personalizado anexado à solicitação não é atualizado quando o novo Tópico da fila é selecionado**

_Solicitações_

Quando um usuário cria uma solicitação e seleciona um Tópico da fila que anexa automaticamente um formulário personalizado à solicitação e seleciona um Tópico da fila diferente, o formulário personalizado do primeiro Tópico da fila permanece anexado à solicitação.

**Os ícones são exibidos incorretamente**

_[!DNL Workfront]_

Imagens de ícones são exibidas incorretamente. Isso foi relatado em muitas áreas em várias [!UICONTROL Workfront].

**As tarefas não são exportadas para o PDF quando a opção &quot;Outros tamanhos&quot; está selecionada.**

_Tarefas_

Se um usuário tentar exportar uma lista de tarefas para o PDF e selecionar o &quot;[!UICONTROL Outros tamanhos]&quot;, eles podem selecionar um tamanho e clicar em [!UICONTROL Exportar], mas a lista não exporta. Não há mensagem de erro e nenhuma outra indicação de que a exportação foi malsucedida.

**O indicador de imagem não é exibido nas notificações por email**

_Notificações_

Quando um usuário adiciona uma imagem a uma atualização e uma notificação por email é enviada ao recipient da atualização, o email não inclui um indicador de que há uma imagem na atualização.

**Páginas que não estão carregando em determinados navegadores**

_[!DNL Workfront]_

Quando um usuário está trabalhando no [!DNL Workfront], as páginas não são carregadas e o usuário vê a seguinte mensagem de erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

Isto foi reportado em

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Esse erro ocorre aleatoriamente e pode afetar qualquer área do Workfront.

+++

+++**Atualização de manutenção em 11 de novembro de 2021**

**Problema com integrações de documentos, página em branco no pop-up de upload de documento[!DNL Google Drive*]*

_Documentos_

Quando um usuário tenta adicionar um novo documento a [!DNL Workfront] from [!DNL Google Drive] usando [!UICONTROL Adicionar novo] >[!UICONTROL De [!DNL Google Drive]], a tela de pop-up para upload permanece em branco.

**Não é possível usar mais de um filtro no Balanceador de Carga de Trabalho**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário está tentando usar mais de um filtro na [!UICONTROL Balanceador de Carga de Trabalho], eles veem os seguintes problemas:

* Se o usuário selecionar dois filtros, somente o filtro inferior será aplicado.
* Se o usuário selecionar mais de dois filtros, nenhum resultado será exibido.

**&quot;[!UICONTROL Pastas do projeto]&quot; Cabeçalho do documento ausente da área de documentos do projeto**

_Projetos_

Quando um usuário está em um projeto e exibe os documentos do projeto, o cabeçalho &quot;[!UICONTROL Pastas do projeto]&quot; está faltando na navegação à esquerda. A seta suspensa ainda existe e o usuário pode selecionar uma pasta.

**As colunas no quadro Kanban são muito largas e não podem ser ajustadas**

_Agile_

Quando um usuário exibe um quadro Kanban com várias colunas, as colunas são muito largas e o usuário deve rolar para exibir ou mover cartões para as colunas mais à direita. As larguras de coluna não são ajustáveis, portanto, o usuário não pode tornar as colunas menores, de modo que todas estejam visíveis na tela ao mesmo tempo.

**Interface aprimorada para criar uma nova equipe**

_Equipes_

Criar equipes agora é mais intuitivo com novas dicas visuais. Ao selecionar a variável [!UICONTROL Trocar equipes] em qualquer página do grupo, o ícone [!UICONTROL Criar novo grupo] o link tem um ícone para indicar &quot;[!UICONTROL novo],&quot; e o link é separado do restante da lista, de modo que não pareça um nome de equipe. Essa interface é a mesma para equipes ágeis e não ágeis.

+++

+++**Atualização de manutenção em 4 de novembro de 2021**

**Novas tarefas assumem o padrão de restrição de tarefa incorreta**

_Tarefas_

Quando um usuário cria uma nova tarefa usando o &quot;[!UICONTROL Nova tarefa]&quot; e a opção Nova Data de Início Padrão da Tarefa está definida como &quot;[!UICONTROL Hoje],&quot; a restrição de tarefa da tarefa criada é definida como &quot;[!UICONTROL Logo que possível]&quot; em vez de &quot;[!UICONTROL Iniciar não antes de].&quot;

**Os campos não são exibidos nos cartões de história ágil**

_Ágil_

Quando um usuário visualiza um storyboard do ágil, os cartões são exibidos somente na variável [!UICONTROL Descrição] e [!UICONTROL Status] campos. Nenhum outro campo, incluindo qualquer campo personalizado, será exibido.

**Os cartões retornam à coluna original antes de passar para a nova coluna**

_Ágil_

Quando um usuário arrasta um cartão para uma nova coluna no storyboard, ele pode ver o cartão que está sendo arrastado. No entanto, quando o usuário solta o cartão na nova coluna, o cartão aparece brevemente na coluna original antes de ser exibido na nova coluna.

**Valores não disponíveis para campo personalizado no filtro**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta criar um filtro usando um campo personalizado, o valor desse campo personalizado não é exibido e não pode ser inserido no filtro.

**Páginas que não estão sendo carregadas no [!DNL Firefox] navegador**

_[!DNL Workfront]_

Quando um usuário está trabalhando no [!DNL Workfront] usando um [!DNL Firefox] no navegador, as páginas não são carregadas e o usuário vê a seguinte mensagem de erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

Este erro ocorre aleatoriamente e pode afetar qualquer área do [!DNL Workfront].

**Erro relacionado à data ao criar projeto a partir do modelo.**

_Modelos_

Se um usuário criar um projeto a partir de um modelo e definir o modo de agendamento como [!UICONTROL Data inicial], em seguida, seleciona uma restrição de tarefa; quando o usuário tenta criar o projeto, o projeto não é criado e o usuário vê uma mensagem de erro com base na restrição de tarefa.

**[!UICONTROL Exportar Gráfico de Gantt] não responde**

_Gráfico de Gantt_

Se um usuário no novo [!DNL Workfront] a experiência tenta exportar a variável [!UICONTROL Gráfico de Gantt] e seleciona o &quot;[!UICONTROL O que vejo]&quot;, a [!UICONTROL Gráfico de Gantt] não exporta e a caixa de diálogo não responde. O usuário não pode fechar ou clicar fora da caixa de diálogo.

**Os ícones são exibidos incorretamente**

_[!DNL Workfront]_

Imagens de ícones são exibidas incorretamente. Foram reportadas situações que incluem, mas não se limitam a:

* Imagens para funções ou grupos de trabalho ao compartilhar um objeto
* Ícones da esquerda e da direita em relatórios de calendário
* Classificar ícones nas colunas do relatório

**Adicionar caixas de seleção a solicitações na [!UICONTROL Enviado] da seção [!UICONTROL Solicitações] area**

_Solicitações_

Adicionamos caixas de seleção à esquerda dos nomes das solicitações no [!UICONTROL Lista enviada] do [!UICONTROL Solicitações] área. Isso facilita a seleção de uma solicitação e a visualização de informações adicionais.

**Os Trimestres personalizados agora são suportados nos filtros de Balanceador de Carga de Trabalho**

_[!UICONTROL Balanceador de carga de trabalho]_

Os filtros na [!UICONTROL Balanceador de Carga de Trabalho] agora oferecem suporte a trimestres personalizados.

**Operador de filtro atualizado para o campo Duração nos Filtros do Balanceador de Carga de Trabalho**

_[!UICONTROL Balanceador de carga de trabalho]_

Atualizamos os operadores de filtro ao filtrar a variável[!UICONTROL  Balanceador de Carga de Trabalho] por [!UICONTROL Duração].

+++


## Atualizações em outubro de 2021

+++**Atualização de manutenção em 28 de outubro de 2021**

**[!UICONTROL Início] e [!UICONTROL Meu trabalho] exibição de página em branco**

_[!UICONTROL Início] / [!UICONTROL Meu trabalho]_

Quando um usuário navega para [!UICONTROL Início] Para Meu trabalho, a página é exibida em branco.

**Não é possível visualizar ou editar [!UICONTROL Grupo de tópicos] detalhes**

_Solicitações_

Quando um usuário tenta visualizar ou editar os detalhes de um Grupo de Tópicos, a página que abre mostra &quot;[!UICONTROL Detalhes do grupo de tópicos]&quot; no cabeçalho, mas está em branco

**Os botões de opção obrigatórios em branco são preenchidos automaticamente**

_Solicitações_

Quando um usuário envia uma solicitação com um campo de botão de opção obrigatório e não seleciona um valor para esse campo antes de enviar a solicitação, o primeiro valor é automaticamente selecionado quando a solicitação é enviada.

+++

+++**Atualização de manutenção em 21 de outubro de 2021**

**Não é possível adicionar um filtro em [!UICONTROL Balanceador de Carga de Trabalho]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário na [!UICONTROL Balanceador de Carga de Trabalho] tenta adicionar um filtro, a variável [!UICONTROL Adicionar filtro] O painel é aberto, mas o conteúdo do painel não é carregado e o usuário não pode adicionar o filtro.

**Quadro de Scrum ágil não exibindo histórias**

_Ágil_

Quando um usuário tenta exibir o Quadro de verificação na iteração de um grupo, o quadro de avaliação é exibido em branco.

**O quadro do artigo de soma fica em branco ao usar filtros**

_Ágil_

Quando um usuário tenta exibir um quadro de história de Soma usando qualquer filtro, exceto o &quot;[!UICONTROL Todos os Grupos]&quot;, uma tela em branco é exibida. O usuário não pode voltar para o &quot;[!UICONTROL Todos os Grupos]&quot; filtro.

**As listas são visíveis somente em uma pequena área da tela**

_Listas_

Quando um usuário tenta exibir uma lista ao usar um [!DNL Safari] em um [!DNL Mac] usando o [!DNL Big Sur OS], a lista é exibida somente em uma pequena área da tela. O usuário pode rolar pela lista, mas a área pode ser tão pequena que a lista é difícil ou impossível de ler.

**Os botões de opção obrigatórios em branco são preenchidos automaticamente**

_Solicitações_

Quando um usuário envia uma solicitação com um campo de botão de opção obrigatório e não seleciona um valor para esse campo antes de enviar a solicitação, o primeiro valor é automaticamente selecionado quando a solicitação é enviada.

+++

+++**Atualização de manutenção (hotfix) em 21 de outubro de 2021**

**[!UICONTROL Início] e [!UICONTROL Meu trabalho] exibição de página em branco**

_[!UICONTROL Início] / [!UICONTROL Meu trabalho]_

Quando um usuário navega para [!UICONTROL Início] ou [!UICONTROL Meu trabalho], a página será exibida em branco.

+++

+++**Atualização de manutenção em 20 de outubro de 2021**

**[!UICONTROL Balanceador de Carga de Trabalho] definir como a opção de agendamento padrão**

_[!UICONTROL Balanceador de carga de trabalho]_

Se um usuário que tem a variável [!UICONTROL Scheduler] configurada como padrão para usá-la, ela verá que a variável [!UICONTROL Balanceador de Carga de Trabalho] foi definida como padrão.

+++

+++**Atualização de manutenção (hotfix) em 19 de outubro de 2021**

**Não é possível atribuir uma solicitação ao criá-la**

_Solicitações_

Quando um usuário no novo [!DNL Workfront] a experiência está criando uma solicitação e tenta atribuir um usuário digitando seu nome no [!UICONTROL Atribuições] , o campo não exibe a lista suspensa e o usuário não pode selecionar o nome do destinatário.

**O quadro do artigo de soma fica em branco ao usar filtros**

_Ágil_

Quando um usuário tenta exibir um quadro de história de Soma usando qualquer filtro, exceto o &quot;[!UICONTROL Todos os Grupos]&quot;, uma tela em branco é exibida. O usuário não pode voltar para o &quot;[!UICONTROL Todos os Grupos]&quot; filtro.

+++

+++**Atualização de manutenção em 14 de outubro de 2021**

**Os modelos compartilhados em todo o sistema não estão visíveis**

_Modelos_

Quando um usuário cria um projeto e tenta usar um modelo que foi compartilhado no sistema inteiro, ele não pode ver o modelo na lista de modelos disponíveis e não pode usar o modelo.

**Erro ao criar projetos a partir de modelos**

_Modelos_

Quando um usuário tenta criar um projeto a partir de um modelo que inclui um formulário personalizado com uma seção visível somente para administradores, ele não pode criar o projeto, e a seguinte mensagem é exibida:

&quot;[!UICONTROL Categoria com valor(s) da chave primária &quot;xxxxxxxxxxxxxxxx&quot; não encontrada]&quot;

**Links atualizados para copiar e mover tarefas**

_Tarefas_

Os links para copiar e mover tarefas foram atualizados para &quot;[!UICONTROL Copiar para]&quot; e &quot;[!UICONTROL Mover para]&quot; tanto na página de tarefas quanto em uma lista de tarefas.

**Remover limite para pesquisa de função de trabalho ao substituir taxas de faturamento de um projeto**

Função no trabalho

OBSERVAÇÃO: Esta atualização está no ambiente de Visualização e estará em Produção com a versão 2.1 Produção. Para obter mais informações, consulte &quot;Visão geral da versão 2.1&quot;.

Substituir as taxas de faturamento de funções de trabalho em um projeto agora pesquisa todas as funções de trabalho no sistema.

Anteriormente, [!DNL Workfront] pesquisou funções de trabalho nas primeiras 2000 em ordem alfabética.

+++

+++**Atualização de manutenção em 7 de outubro de 2021**

**[!UICONTROL As notificações no aplicativo desaparecem do] centro de notificações**

_Notificações_

Quando um usuário exibe o centro de notificações, algumas notificações anteriormente visíveis não ficam mais visíveis. Em alguns casos, a notificação pode desaparecer antes que o usuário a visualize.

**Os anúncios não estão visíveis na variável [!UICONTROL Todos os anúncios] página**

_Notificações_

Quando um usuário abre o [!UICONTROL Todos os anúncios] da página [!UICONTROL Notificações] , não há anúncios visíveis nas seguintes áreas:

* [!UICONTROL Caixa de entrada]
* [!UICONTROL Favoritos]
* [!UICONTROL Rascunhos]
* [!UICONTROL Excluído]

**Erro ao fazer atribuição no [!UICONTROL Balanceador de Carga de Trabalho]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta fazer uma atribuição do [!UICONTROL Balanceador de Carga de Trabalho], o trabalho não é atribuído e o usuário vê o seguinte erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

+++


## Atualizações em setembro de 2021

+++**Atualização de manutenção em 30 de setembro de 2021**

**Erro ao navegar rapidamente para ou para [!UICONTROL Início]**

_Início_

Quando um usuário navega rapidamente para ou sai de [!UICONTROL Início], a página não é carregada e o usuário vê o seguinte erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

Isso também pode ocorrer ao navegar para o [!UICONTROL Início] através de um pino.

+++

+++**Atualização de manutenção em 23 de setembro de 2021**

**[!UICONTROL Acesso negado] erro ao visualizar ingressos enviados para[!DNL Workfront]**

_Problemas_

Quando um usuário enviar um tíquete para [!DNL Workfront] e tentar visualizar o tíquete, eles verão o seguinte erro:

&quot;[!UICONTROL Acesso negado: Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

**O Resumo de caso de negócios mostra valores incorretos**

_Projetos_

Quando um usuário exibe a variável [!UICONTROL Caso de negócios] painel de resumo, os valores exibidos não refletem os valores no individual [!UICONTROL Caso de negócios] seções.

**Os cabeçalhos de coluna não estão alinhados com colunas em listas**

_Configuração_

Quando um usuário estiver no [!UICONTROL Configuração] e exibe uma lista, como [!UICONTROL Forms personalizada] ou [!UICONTROL Níveis de acesso], os cabeçalhos de coluna para essa lista não estão alinhados com as colunas na lista.

**Os usuários sem as permissões de compartilhamento adequadas podem anexar formulários personalizados a objetos**

_Formulários personalizados_

Quando um formulário personalizado no novo [!DNL Adobe Workfront] estiver definida para ser visível em todo o sistema, todos os usuários poderão anexar esse formulário personalizado a um objeto. No entanto, eles só devem ser capazes de exibir o formulário personalizado e não podem anexá-lo a um objeto, a menos que ele tenha sido compartilhado especificamente com eles.

+++

+++**Atualização de manutenção em 16 de setembro de 2021**

**Não é possível editar grupos**

_Grupos_

Quando um usuário tenta editar ou excluir um grupo, ele não é editado ou excluído e o usuário vê a seguinte mensagem:

&quot;[!UICONTROL Vamos tentar novamente. Grupo com valores da chave primária &quot;(ID do grupo)&quot; não encontrado]&quot;

**[!UICONTROL Portfolio Otimizer] não exibindo projetos**

_Portfólios_

Quando um usuário tenta exibir projetos na [!UICONTROL Portfolio Otimizer], a lista de projetos não é exibida e, portanto, o usuário não pode interagir com os projetos.

+++

+++**Atualização de manutenção (hotfix) em 10 de setembro de 2021**

**Data e hora marcadas como UTC ao editar em linha**

_Listas_

Quando um usuário edita uma data ou hora em linha (em uma lista de objetos), a data e a hora são marcadas como UTC. A data e a hora não estão definidas em UTC em [!DNL Workfront]. Esse problema afeta apenas a exibição, não os dados reais.

**A cor do texto não é exibida corretamente quando a formatação condicional é aplicada**

_Relatórios_

Quando um usuário exibe um relatório com formatação condicional que altera a cor do texto, a cor do texto é exibida como inalterada.

+++

+++**Atualização de manutenção em 9 de setembro de 2021**

**Problemas não estão exibindo detalhes do problema**

_Início_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência seleciona um problema no [!UICONTROL Lista de Trabalho], a visualização no painel direito exibe determinados campos como não tendo valores inseridos. No entanto, se você navegar até o problema e exibir a variável [!UICONTROL Detalhes do problema], esses campos têm valores inseridos.

**Os usuários precisam de permissões do Contribute para visualizar o [!UICONTROL Aprovações] na nova Workfront Experience**

_Aprovações_

Os usuários precisam [!UICONTROL Contribute] permissões em um objeto para exibir o [!UICONTROL Aprovações] na nova seção [!DNL Workfront] Experiência. Eles só devem precisar [!UICONTROL Exibir] permissões para exibir o [!UICONTROL Aprovações] quando houver um processo de aprovação no objeto.

**[!UICONTROL Boias] erro ao usar filtros**

_Listas_

Quando um usuário tenta usar um dos seguintes filtros:

* [!UICONTROL Todos os Projetos]
* [!UICONTROL Projetos em que estou trabalhando]
* [!UICONTROL Minhas tarefas atuais]

a lista fica em branco e o usuário vê o seguinte erro:

&quot;[!UICONTROL Vamos tentar novamente.]&quot;

**[!UICONTROL Tarefas] seção fica em branco ao editar em linha**

_Modelos_

Quando um usuário tenta editar as tarefas em linha em um modelo usando uma exibição que inclui o &quot;[!UICONTROL Atribuir a: Nome]&quot; e a atribuição contém um usuário, a variável [!UICONTROL Tarefas] fica em branco e o usuário não pode editar as tarefas do template.

**Não é possível exportar [!UICONTROL Portfolio Otimizer]**

_Portfólios_

Quando um usuário tenta exportar a variável [!UICONTROL Portfolio Otimizer] e clicar em qualquer uma das opções de exportação, a variável [!UICONTROL Portfolio Otimizer] não exporta.

**As notificações não estão sendo enviadas para respostas**

_Notificações_

Quando um usuário responde a uma atualização em [!DNL Workfront], outros usuários no encadeamento de comentários não estão recebendo notificações.

**As alterações nos dados personalizados causam atraso**

_Campos personalizados_

Quando um usuário modifica dados personalizados que acionam alterações em outros dados exibidos, as alterações são carregadas lentamente.

**Agrupamento &quot;[!UICONTROL Recolher ou expandir tudo]&quot; ícone não é exibido**

_Relatórios_

O &quot;[!UICONTROL Recolher ou expandir tudo]&quot; ícone não é exibido no cabeçalho de uma lista ou relatório quando os agrupamentos são aplicados à lista ou ao relatório.

**[!UICONTROL Verificar] e [!UICONTROL Cancelar] opções não visíveis ao alterar alocações de tarefas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta alterar a alocação da tarefa para uma tarefa e o período dessa tarefa se estende até ou além da borda da página visível, a variável [!UICONTROL Verificar] e [!UICONTROL Cancelar] Os botões não estão visíveis e o usuário não pode salvar ou cancelar as alterações de alocação.

**Adição de um campo personalizado a [!UICONTROL Início] causa ausência de dados de campo**

_[!UICONTROL Início]_

Quando um campo personalizado é adicionado a [!UICONTROL Início], outros campos começam com dados ausentes e são exibidos incorretamente.

**Não é possível exibir itens vinculados quando conectado como outro usuário**

_Integrações_

Se um administrador tentou exibir itens vinculados de um provedor externo enquanto estava conectado como outro usuário, ele não pôde abrir as pastas vinculadas e não pôde exibir os itens.

+++

+++**Atualização de manutenção em 2 de setembro de 2021**

**Não é possível fixar o painel personalizado**

_Painéis de Controle_

Quando um usuário tenta prender um painel personalizado, o painel não é fixado e o usuário vê o seguinte erro:

&quot;[!UICONTROL Algo deu errado ao pinçar. Entre em contato [!DNL Workfront] então podemos consertar isso.]&quot;

**[!DNL Workfront Proof]o resumo da impressão está em branco**

[!DNL Workfront Proof]

Quando um usuário abre o resumo de impressão para imprimir uma prova, o cabeçalho é exibido, mas o resumo em si fica em branco.

+++


## Atualizações em agosto de 2021

+++**Atualização de manutenção em 26 de agosto de 2021**

**Em [!DNL Safari] há um plano de fundo cinza escuro no texto dos cabeçalhos da coluna**

_Listas_

No [!DNL Safari] no navegador, há um plano de fundo cinza escuro nos cabeçalhos da coluna, destacando o texto. Isso não é um problema com outros navegadores compatíveis.

**Erro inesperado ao definir predecessores**

_Tarefas_

Quando um usuário tenta definir uma tarefa como antecessor usando a edição em linha, o antecessor não é definido e o usuário vê a seguinte mensagem:

&quot;[!UICONTROL Ocorreu um erro inesperado]&quot;

+++

+++**Atualização de manutenção em 19 de agosto de 2021**

**Filtros salvos ausentes após selecionar um filtro que não exibe problemas**

_Listas_

Filtros salvos estão ausentes em uma lista de problemas depois de selecionar um filtro que não exibe resultados.

**Problemas não estão exibindo detalhes do problema**

_[!UICONTROL Início] resumo_

Quando um usuário [!DNL Adobe Workfront Classic] seleciona um problema do [!UICONTROL Lista de Trabalho], a visualização no painel direito exibe determinados campos como não tendo valores inseridos. No entanto, se você navegar até o problema e exibir a variável [!UICONTROL Detalhes do problema], esses campos têm valores inseridos.

+++

+++**Atualização de manutenção em 12 de agosto de 2021**

**Não é possível personalizar a exibição ágil no projeto**

_Ágil_

Quando um usuário tenta personalizar uma visualização ágil existente anteriormente em um projeto, a janela é fechada e o usuário não consegue editá-la.

**O nome não é alterado nas novas versões do documento**

_Documentos_

Quando um usuário carrega uma nova versão de um documento, o nome do documento não é atualizado para corresponder ao nome da versão mais recente.

**O ícone antecessor não fica verde quando o antecessor é concluído.**

_Tarefas_

Quando uma tarefa tem uma tarefa antecessora e essa tarefa antecessora é concluída, o ícone antecessor na tarefa dependente não fica verde.

Quando um formulário personalizado no novo [!DNL Adobe Workfront] estiver definida para ser visível em todo o sistema, todos os usuários poderão anexar esse formulário personalizado a um objeto. No entanto, eles só devem ser capazes de exibir o formulário personalizado e não podem anexá-lo a um objeto, a menos que ele tenha sido compartilhado especificamente com eles.

+++

+++**Atualização de manutenção (hotfix) em 6 de agosto de 2021**

**Não é possível selecionar calendários em [!DNL Outloo]k Configurações do calendário**

_Início_

Quando um usuário no novo [!DNL Workfront] a experiência está visualizando [!DNL Outlook] O calendário na página inicial e abre as configurações, as caixas de seleção para selecionar calendários estão ausentes. Se o usuário clicar em onde a caixa de seleção estaria, o calendário responderá como se a caixa de seleção estivesse lá.

**Não é possível reautorizar ou verificar a conexão com o [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

[!DNL Adobe Workfront Fusion] usuários com cenários conectados a [!UICONTROL Webdam] deve estar ciente de que [!UICONTROL Webdam] as conexões exigem reautenticação manual a cada 14 dias. O [!UICONTROL Webdam] No momento, a API não suporta reautorização automática.

+++

+++**Atualização de manutenção em 5 de agosto de 2021**

**Não é possível interagir com o documento em [!UICONTROL Painel Resumo] ou [!UICONTROL Mais] menu**

_Documentos_

Quando um usuário no novo [!DNL Workfront] A experiência está visualizando um documento e tenta fazer uma seleção no [!UICONTROL Painel Resumo] ou [!UICONTROL Mais] , o documento é desmarcado, fazendo com que a variável [!UICONTROL Painel Resumo] ou [!UICONTROL Mais] para deixar em branco.

**[!UICONTROL Nova solicitação] botão ausente**

_Solicitações_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência vai para a [!UICONTROL Solicitações] página, o [!UICONTROL Nova solicitação] não é exibido e não é possível enviar uma solicitação.

**Os usuários sem as permissões de compartilhamento adequadas podem anexar formulários personalizados a objetos**

_Formulários personalizados_

Quando um formulário personalizado no novo [!DNL Adobe Workfront] estiver definida para ser visível em todo o sistema, todos os usuários poderão anexar esse formulário personalizado a um objeto. No entanto, eles só devem ser capazes de exibir o formulário personalizado e não podem anexá-lo a um objeto, a menos que ele tenha sido compartilhado especificamente com eles.

**Não é possível alterar as configurações de prova ao criar uma nova prova**

_[!DNL Workfront Proof]_

Quando um usuário cria uma nova prova e tenta alterar as configurações, a configuração é revertida para uma configuração anterior.

**[!UICONTROL Quadro de história] não carregar corretamente**

_Ágil_

Quando um usuário no novo [!DNL Adobe Workfront] experiência navega para uma [!UICONTROL Quadro de história], pode levar até 10 segundos para carregar a placa. O atraso no carregamento é devido ao sistema carregar todas as placas quando ele deve carregar apenas 50 placas de cada vez.

+++


## Atualizações em julho de 2021

+++**Atualização de manutenção (hotfix) em 29 de julho de 2021**

**Não é possível carregar nova prova ou nova versão de prova**

_[!DNL Workfront Proof]_

Quando um usuário tenta fazer upload de uma nova prova ou de uma nova versão de uma prova no [!DNL Workfront] , a nova página de prova ou nova versão fica em branco e o usuário não pode fazer upload da prova ou da versão.

+++

+++**Atualização de manutenção em 29 de julho de 2021**

**[!UICONTROL Atividade de prova] e [!UICONTROL Configurações do visualizador de prova] páginas sempre disponíveis**

_[!DNL Workfront Proof]_

O [!UICONTROL Atividade de prova] e [!UICONTROL Visualizador de prova] Agora, as páginas de configurações estão sempre visíveis, mesmo se o usuário não tiver acesso para atualizar essas páginas.

Anteriormente, quando um usuário com um Perfil de permissão de prova personalizado navegava para um documento, a variável [!UICONTROL Atividade de prova] e [!UICONTROL Configurações do visualizador de prova] as páginas à esquerda nem sempre estavam visíveis.

**Mensagem de erro ao usar [!UICONTROL Porcentagem] opção para [!UICONTROL Horas alocadas]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário seleciona a variável [!UICONTROL Porcentagem] opção para [!UICONTROL Horas alocadas]e há trabalhos listados na variável [!UICONTROL Trabalho não atribuído] , o usuário vê o seguinte erro:

&quot;[!UICONTROL Ocorreu um error e estamos trabalhando para resolver o problema. Para continuar seu trabalho, experimente atualizar esta página do seu navegador.]&quot;

+++

+++**Atualização de manutenção em 22 de julho de 2021**

**Novos nomes de versão de prova sendo cortados**

_[!DNL Workfront Proof]_

Quando um usuário [!DNL Adobe Workfront Classic] carrega uma nova versão de uma prova que contém um ponto no nome do arquivo, o nome do arquivo é cortado no final.

+++

+++**Atualização de manutenção (hotfix) em 19 de julho de 2021**

**Erro ao tentar navegar para projetos, folhas de ponto, tarefas ou programas**

No novo [!DNL Adobe Workfront] , quando um usuário tenta navegar para projetos, folhas de ponto, tarefas ou programas, ele vê a mensagem de erro &quot;[!UICONTROL Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

+++

+++**Atualização de manutenção em 15 de julho de 2021**

**A prioridade padrão em novas solicitações está incorreta**

_Solicitações_

Quando um usuário no novo [!DNL Adobe Workfront] experiência cria uma solicitação, a solicitação não respeita a prioridade padrão definida em [!UICONTROL Preferências do projeto] e não conseguem ajustar a prioridade antes de enviar a solicitação.

**[!UICONTROL Ir para prova] link não direciona para comentário**

_Notificações de email_

Quando um usuário recebe uma notificação por email para um comentário de prova e clica em [!UICONTROL Ir para prova], são direcionadas ao comentário errado na prova ou não são direcionadas a nenhum comentário.

**Valores de campo Rich Text não transferidos após converter um problema em uma tarefa**

_Formulários personalizados_

Quando um usuário converte um problema em uma tarefa e o problema tem um formulário personalizado anexado com um valor inserido em um campo de texto com formatação Rich Text, o valor no campo de texto não é transferido após a conversão.

**Os valores de campo personalizado são alterados após a seleção**

_[!DNL Workfront Proof]_

Quando um usuário no novo [!DNL Adobe Workfront] estiver criando uma nova prova e inserir um valor em alguns campos personalizados em uma prova, o valor de alguns campos anteriores será revertido para os valores padrão em vez do valor inserido pelo usuário.

**[!UICONTROL Atribuir a] typeforward não funciona**

_[!UICONTROL Início]_

Quando um usuário [!DNL Adobe Workfront Classic] cria um projeto, tarefa ou solicitação do [!UICONTROL Início] área, a [!UICONTROL Atribuir a] O campo typeahead não preenche nomes de usuários.

**Arredondamento de horas incorretamente**

_Planilhas de horas_

Quando um usuário no novo [!DNL Adobe Workfront] experiência navega para [!UICONTROL Folhas de Horas] > [!UICONTROL Todas as Folhas de Horas], eles veem que os números totais de horas de algumas folhas de horas são arredondados para uma casa decimal em vez de em incrementos de .25, mas o total de horas é exibido corretamente na folha de horas individual. Por exemplo, na área Todas as Folhas de Horário, uma folha de ponto mostra 44,8 horas totais, mas ao abrir a folha de ponto, mostra 44,75 horas totais.

**Não é possível delegar aprovações**

_[!UICONTROL Início]_

Quando um usuário [!DNL Adobe Workfront Classic] cliques [!UICONTROL Delegar Minhas Aprovações] no [!UICONTROL Início] e começam a digitar o nome do usuário ao qual estão tentando delegar, nenhum resultado é exibido no [!UICONTROL typeahead] e não podem selecionar um usuário.

**[!UICONTROL Gráfico de Gantt] a exibição não está disponível para relatórios de Tarefa**

_Relatórios_

OBSERVAÇÃO: Isso também está afetando os relatórios do Projeto.

Quando um usuário no novo [!DNL Adobe Workfront] a experiência abre um relatório de Tarefa, a opção para selecionar um [!UICONTROL Gráfico de Gantt] está ausente na barra de ferramentas do relatório. Se a variável [!UICONTROL Gráfico de Gantt] for selecionada para exibição por padrão no relatório, em vez disso, será exibido um formato de lista.

**Clicar [!UICONTROL Veja Mais] no relatório não carrega nada**

_Painéis de Controle_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência está visualizando um relatório em um painel e eles clicam no [!UICONTROL Veja Mais] , nada acontece e não é possível exibir todos os itens no relatório.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 1 de julho de 2021**

**A cópia de módulos não funciona**

_[!DNL Adobe Workfront Fusion]_

Quando um usuário seleciona vários módulos e tenta copiá-los e colá-los, os módulos não são colados.

+++

+++**Atualização de manutenção em 1 de julho de 2021**

**Conjunto de cores para cartões não respeitado**

_Kanban_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência define cores específicas do cartão nas configurações do grupo, essas cores não são refletidas nos cartões Kanban.

**Não é possível colar texto no campo de mensagem personalizado**

_[!DNL Workfront Proof]_

Quando um usuário cria uma nova prova na variável [!UICONTROL Visualizador de Provas da Web] e eles tentam colar o texto no [!UICONTROL Mensagem] no campo [!UICONTROL Notificação por e-mail] não é possível colar o texto. Isso só parece ocorrer quando o texto tem formatação de parágrafo e há uma quebra de parágrafo.

**As solicitações são enviadas com campos obrigatórios em branco**

_Solicitações_

Quando um usuário faz uma solicitação e a envia, as informações nos campos obrigatórios não são enviadas com a solicitação.

**[!UICONTROL Nova solicitação] botão ausente**

_Solicitações_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência vai para a [!UICONTROL Solicitações] página, o [!UICONTROL Nova solicitação] não é exibido e não é possível enviar uma solicitação.

**Erro ao expandir um formulário personalizado**

_Projetos_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência tenta expandir um formulário personalizado anexado a um projeto, eles não conseguem abrir o formulário personalizado e ver a mensagem de erro &quot;[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.]&quot; Atualizar a página não resolve o problema.

**[!DNL Adobe Workfront]a marca agora aparece nos emails do centro de anúncios**

Emails

Como [!DNL Adobe Workfront] a marca é distribuída pelo aplicativo, as seguintes atualizações foram feitas aos emails do centro de anúncio:

* O [!DNL Adobe Workfront] Um leão foi adicionado à área de conteúdo principal.
* O [!DNL Adobe Workfront] foi adicionado ao rodapé.

No futuro, essa marca será mostrada em tipos adicionais de emails do Workfront.

+++


## Atualizações em junho de 2021

+++**Atualização de manutenção em 24 de junho de 2021**

**Não é possível editar uma equipe**

_Ágil_

Quando um usuário no novo [!DNL Adobe Workfront] cliques na experiência [!UICONTROL Editar] para abrir o [!DNL Edit] Página de equipe de um grupo Ágil, a página é carregada inicialmente, em seguida, as configurações desaparecem e ficam em branco.

**Dados removidos da solicitação enviada**

_Solicitações_

Quando um usuário no novo [!DNL Adobe Workfront] A experiência preenche uma solicitação, a solicitação enviada não possui os valores inseridos para alguns campos personalizados, às vezes incluindo campos obrigatórios.

**As colunas não estão sendo exibidas**

_Kanban_

Quando um usuário no novo [!DNL Adobe Workfront] experiência adiciona uma [!UICONTROL Campos adicionais] para um Quadro Kanban, todos os cabeçalhos de coluna param de ser exibidos no quadro.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 23 de junho de 2021**

**Remoção de links quebrados nos emails de notificação**

_[!DNL Adobe Workfront Fusion]_

Removemos o link para as configurações de notificação de [!DNL Adobe Workfront Fusion] e-mails de notificação.
Para obter informações sobre como alterar configurações de notificação, consulte [!DNL Adobe Workfront Fusion] organizações e equipes.

+++

+++**Atualização de manutenção em 17 de junho de 2021**

**[!UICONTROL Gráfico de Gantt] a exibição não está disponível para o Relatório de tarefa**

_Relatórios_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência abre um relatório de Tarefa, a opção para selecionar um [!UICONTROL Gráfico de Gantt] está ausente na barra de ferramentas do relatório. Se a variável [!UICONTROL Gráfico de Gantt] for selecionada para exibição por padrão no relatório, em vez disso, será exibido um formato de lista.

**Erro de limite de caracteres não ocorre nos envios de solicitação**

_Solicitações_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência tenta enviar uma solicitação e elas excedem o limite de caracteres para um campo, não conseguem enviar a solicitação e nenhuma mensagem de erro é exibida. Em [!DNL Adobe Workfront Classic], o usuário vê o aviso &quot;[!UICONTROL [número] os caracteres terminados e quando tentarem enviar a solicitação, eles verão a mensagem de erro &quot;Verifique o seguinte: Introduza no máximo 2000 caracteres (introduziu [número] caracteres).]&quot;

+++

+++**Atualização de manutenção em 10 de junho de 2021**

**Tarefas de modelo reordenadas não são movidas**

_Modelos_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência arrasta uma tarefa de modelo para um novo local em uma lista, o número de atualizações da tarefa de modelo, mas ela não é reordenada.

**Tarefas secundárias não selecionadas com tarefas principais**

_Modelos_

Quando um usuário seleciona uma tarefa pai em um projeto criado de um modelo, as tarefas filho não são selecionadas automaticamente.

**Marcos de edição em linha em uma lista de tarefas exibem todos os marcos**

_Projetos_

Quando um projeto tem um caminho de marco adicionado a ele e um usuário no novo [!DNL Adobe Workfront] a experiência em linha edita a variável [!UICONTROL Marco: Nome] nessa lista de tarefas, todos os caminhos de marcos são exibidos no menu suspenso, em vez de apenas os caminhos de marcos anexados a esse projeto.

+++

+++**Atualização de manutenção em 3 de junho de 2021**

**O prompt faz com que a página treme**

_Relatórios_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência executa um relatório com um prompt, as colunas no relatório movem-se rapidamente da esquerda para a direita.

**Algumas frases no [!UICONTROL Nova prova] não estão traduzindo corretamente**

_[!DNL Workfront Proof]_

Quando um usuário navega até a variável [!UICONTROL Nova criação de prova] em [!DNL Workfront Proof] e o conteúdo está sendo traduzido para um idioma diferente do inglês, algumas frases ainda são exibidas em inglês.

**Rótulos desativados e excluídos adicionados aos usuários[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

[!UICONTROL Desativado] e [!UICONTROL Excluído] os rótulos do usuário foram adicionados às seguintes áreas em [!DNL Workfront] Prova:

* [!UICONTROL Detalhes da prova] página
* [!UICONTROL Exibições de prova]
* [!UICONTROL Visualizador de prova]
* [!UICONTROL Fluxos de trabalho de revisão]
* [!UICONTROL Imprimir comentários] página
* [!UICONTROL Usuário] página

+++


## Atualizações em maio de 2021

+++**Atualização de manutenção em 27 de maio de 2021**

**[!UICONTROL Data de confirmação] calendário é exibido para atualizações**

_Tarefas_

Quando um usuário no novo [!DNL Adobe Workfront] estiver informando uma atualização em uma tarefa, a [!UICONTROL Data de confirmação] o calendário é exibido sem que o usuário selecione o [!UICONTROL Data de confirmação] campo.

**[!UICONTROL Mais] menu ausente em filtros, visualizações e agrupamentos**

_Listas_

Quando um usuário no novo [!DNL Adobe Workfront] a experiência exibe os filtros, exibições ou agrupamentos de uma lista, a [!UICONTROL Mais] O ícone de menu está ausente, o que impede o compartilhamento ou, se tiverem acesso, a remoção de filtros, visualizações ou agrupamentos.

**Copiar e colar um projeto [!UICONTROL Número de referência] adiciona &quot;[!UICONTROL Essa]&quot;**

_Projetos_

Quando um usuário no novo [!DNL Workfront] a experiência navega para um projeto, copia a variável [!UICONTROL Número de referência] do [!UICONTROL Visão geral] e cola, a palavra &quot;[!UICONTROL Essa]&quot; é adicionado ao final do número.

**[!UICONTROL Resumo diário] os emails estão sendo enviados quando desativados**

_Notificações de email_

Alguns usuários estão recebendo [!UICONTROL Resumo diário] notificações por email quando não tiverem sido ativadas nas configurações do usuário.

**Erro de objeto não existe mais**

_Objetos_

Quando um usuário no novo [!DNL Workfront] A experiência tenta abrir determinados objetos, eles veem a mensagem de erro &quot;[!UICONTROL O (objeto) não existe mais: Você pode ter digitado incorretamente o endereço da Web. Verifique-o novamente e tente inserir o endereço novamente.]&quot; O link do objeto ainda aparece em listas, recents, favoritos, resultados de pesquisa etc., mas eles não podem acessá-lo e ele não aparece na Lixeira com objetos excluídos.



+++

+++**Atualização de manutenção em 20 de maio de 2021**

**Opções de prova ausentes**

_Provas_

Quando um usuário carrega outra versão de uma prova em [!DNL Workfront], o [!UICONTROL Abrir prova] e [!UICONTROL Fluxo de trabalho de prova] os links estão ausentes, fazendo parecer que é um documento em vez de uma prova. Quando esses links estiverem ausentes, o rótulo [!UICONTROL Pending] também exibe e outros usuários não podem gerar a prova enquanto ela estiver nessa [!UICONTROL Pending] status.

**Usuários que não recebem entregas programadas de relatórios**

_Relatórios_

Quando alguns relatórios são agendados para entrega de relatórios, os usuários às vezes não os recebem.

**Não é possível remover o acesso ao modelo de layout**

_Painéis de Controle_

Quando um usuário abre [!UICONTROL Compartilhamento] opções para um painel remover o acesso de um modelo de layout, não [!UICONTROL Excluir] O ícone é exibido ao lado do Modelo de layout e não é possível remover o acesso.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 17 de maio de 2021**

**O Painel da Organização agora exibe corretamente o número de cenários ativos**

_[!DNL Workfront Fusion]_

O [!UICONTROL Organização] anteriormente, o painel mostrava um campo em branco em vez do número de cenários que estão sendo utilizados.

**A navegação do armazenamento de dados agora mostra rótulos de coluna**

_[!DNL Workfront Fusion]_

As estruturas de dados que utilizavam rótulos de coluna anteriormente exibiam o nome da coluna na [!UICONTROL navegação do armazenamento de dados] exibir.  Agora, o rótulo da coluna é exibido.  Se nenhum rótulo for identificado para a coluna, o nome da coluna será exibido.

**O erro de inicialização de cenário não afeta mais os dados do webhook**

_[!DNL Workfront Fusion]_

Anteriormente, um cenário iniciado por um webhook (incluindo aqueles que estão usando eventos em tempo real para acionar) que ocorria um erro durante a inicialização do cenário poderia resultar na perda do acesso a esses dados do webhook.  Agora, se ocorrer um erro durante a inicialização do cenário (como não ser possível verificar uma conexão), os dados do webhook serão mantidos na fila do webhook e a execução será repetida automaticamente.  Após três tentativas malsucedidas, o cenário é desativado e as informações ainda permanecerão na fila.

**Os registros em filas de webhook agora são processados em lotes menores**

_[!DNL Workfront Fusion]_

Anteriormente, se um usuário ativava um cenário inativo que tinha uma fila de webhook associada de muitos registros, [!DNL Workfront Fusion] tentaria processar toda a fila em uma única execução (embora com vários ciclos).  Dependendo da quantidade de registros processados, às vezes a execução única pode exceder a quantidade máxima de tempo de execução (40 minutos).  Agora, quando você ativa um cenário inativo que tem uma fila de webhook associada de registros, o Workfront Fusion processará até o número máximo de registros identificados em uma única execução (geralmente 2 registros por execução).

**Agora, os armazenamentos de dados exibem corretamente os valores de &quot;0&quot;**

_[!DNL Workfront Fusion]_

Anteriormente, os valores do armazenamento de dados de 0 eram exibidos como vazios. &lt;..>

+++

+++**Atualização de manutenção em 13 de maio de 2021**

**O calendário suspenso é exibido atrás do [!UICONTROL Trabalho Não Atribuído] header**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário navega até a variável [!UICONTROL Balanceador de Carga de Trabalho] em [!DNL Workfront Classic], a parte superior do datepicker está oculta atrás do [!UICONTROL Trabalho Não Atribuído] , o que impede que o usuário navegue para meses diferentes.

**Não é possível colar texto no campo de mensagem personalizado**

_[!DNL Workfront Proof]_

Observação: Esse problema parece afetar apenas a [!DNL Google Chrome] navegador da Web no momento.

Quando um usuário cria uma nova prova em [!DNL Workfront Proof] e tentam colar texto de um email no [!UICONTROL Mensagem] no campo [!UICONTROL Notificação por e-mail] não é possível colar o texto.

**Campos não suportados são exibidos no construtor**

_Formulários personalizados_

Quando um usuário está criando um Formulário personalizado e tenta criar um campo calculado usando um campo dinâmico, como [!UICONTROL Número de riscos em aberto]—a caixa de cálculo destaca vermelho e não permite salvar as alterações. Campos dinâmicos não devem ser exibidos no seletor para campos calculados.

**Visualizar para tarefas em [!UICONTROL Lista de Trabalho] não carrega**

_Início_

Quando um usuário no novo [!DNL Workfront] experiência é atribuída a um modelo de layout que inclui campos personalizados em [!UICONTROL Início], a página não responde e não carrega tarefas do [!UICONTROL Lista de Trabalho] se os usuários selecionarem.

**Objetos em [!UICONTROL Lista de Trabalho] não carregando em [!UICONTROL Início]**

_[!UICONTROL Início]_

Quando um usuário clica em um objeto no [!UICONTROL Lista de Trabalho Doméstica], o cabeçalho do objeto é exibido no painel direito, mas os detalhes do objeto não são exibidos. Eventualmente, o usuário vê a mensagem &quot;[!UICONTROL Páginas sem resposta.]&quot;

**Problemas de campo de texto formatado no[!DNL Microsoft Outlook]**

_Integrações do Workfront_

Quando um usuário está atualizando um campo de rich text com a variável [!DNL Workfront for Outlook] integração, não é possível:

* Backspace
* Copiar texto
* Colar texto
* Enviar uma solicitação quando todos os campos forem preenchidos

+++

+++**Atualização de manutenção em 6 de maio de 2021**

**[!UICONTROL Moeda] campo que não funciona conforme esperado**

_Listas_

Quando um usuário tenta editar a opção em linhaEm uma lista, não é possível salvar as alterações devido aos seguintes problemas:

* Listas de tarefas e ocorrências não permitindo a entrada de símbolos de moeda
* Listas que não permitem a entrada de abreviações de moeda ao usar uma localidade diferente de inglês
* Listas de subtarefas e emissões que permitem somente a abreviação de moeda do USD, independentemente da moeda do projeto definida

**Nome não atualizado para corresponder ao novo nome de prova**

_Documentos_

Quando um usuário cria uma nova versão de uma prova e atualiza o nome da prova, o objeto do documento em [!DNL Workfront] retém o nome original em vez de corresponder ao novo nome de prova.

**[!UICONTROL Caso de negócios] botões não funcionam quando formulários personalizados são anexados**

_Projetos_

Quando um projeto no novo [!DNL Workfront] A experiência é criada a partir de um modelo de projeto e há um formulário personalizado anexado, os usuários não podem enviar, rejeitar ou aprovar um caso comercial.

**Provas arquivadas exibidas em listas e relatórios**

_Provas_

Quando um usuário exibe sua lista de trabalho em [!UICONTROL Início] ou [!UICONTROL Meu trabalho], as provas que já foram arquivadas são exibidas na lista. Provas arquivadas também aparecem em relatórios e painéis.

**O projeto criado a partir do modelo tem configurações de acesso incorretas**

_Projetos_

Quando um usuário cria um projeto a partir de um modelo, as configurações de acesso do modelo não são transferidas para o novo projeto criado.

**Objetos em [!UICONTROL Lista de Trabalho] não carregando em [!UICONTROL Início]**

_[!UICONTROL Início]_

Quando um usuário clica em um objeto no [!UICONTROL Lista de Trabalho Doméstica], o cabeçalho do objeto é exibido no painel direito, mas os detalhes do objeto não são exibidos. Eventualmente, o usuário vê a mensagem &quot;[!UICONTROL Páginas sem resposta.]&quot;

+++


## Atualizações em abril de 2021

+++**Atualização de manutenção em 29 de abril de 2021**

**[!DNL SharePoint]a integração é autenticada usando credenciais de uma integração separada**

_Integrações do Workfront_

Quando um usuário tiver mais de um [!DNL SharePoint] integração, um [!DNL SharePoint] a autenticação tenta autenticar usando as credenciais de outro [!DNL SharePoint] integração.

**Não é possível carregar ou exportar arquivos de [!DNL Adobe] products**

_Integrações do Workfront_

Quando um usuário tenta fazer upload ou exportar arquivos usando o [!DNL Workfront for Adobe Creative Cloud] , eles verão a mensagem de erro &quot;[!UICONTROL Não é possível ler a propriedade &#39;estágios&#39; de indefinido]&quot; e não podem carregar ou exportar os arquivos.

**Os arquivos não estão visíveis em[!DNL Internet Explorer]**

_Documentos_

Quando um usuário com um [!DNL Internet Explorer] navegue até o [!UICONTROL Documentos] área de um objeto, a variável [!UICONTROL Documentos] estiver em branco e não carregar os arquivos. Para alguns usuários, a tela carrega alguns arquivos, mas o número de arquivos exibidos não corresponde ao número exibido ao lado do [!UICONTROL Documentos] seção.

+++

+++**Atualização de manutenção em 22 de abril de 2021**

**Tarefas adicionadas na ordem errada**

_Modelos_

Quando um usuário adiciona uma tarefa a um template, a tarefa não recebe o número da tarefa que espera e a tarefa é adicionada no lugar errado.

**Agora, as provas são combinadas em um único email**

_Provas_

[!DNL Workfront] O agora envia um email para provas combinadas, em vez de enviar um email para cada arquivo incluído.
+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 15 de abril de 2021**

**&quot;[!UICONTROL Cenário rejeitado]&quot; ao executar um cenário**

_[!DNL Workfront Fusion]_

Quando um usuário tenta executar um cenário, ele não é executado e o usuário recebe a mensagem &quot;[!UICONTROL Cenário rejeitado.]&quot;

+++

+++**Atualização de manutenção em 15 de abril de 2021**

**[!UICONTROL Balanceador de Carga de Trabalho] exibe horas planejadas incorretas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário exibe as horas planejadas de uma tarefa na [!UICONTROL Balanceador de Carga de Trabalho] o valor das horas planejadas não corresponde às horas planejadas atribuídas à tarefa.

**A barra de navegação superior não está visível em[!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Quando um usuário navega para qualquer [!DNL Workfront Proof] diferente da página Painel , a barra de navegação superior desaparece. O usuário não pode acessar a funcionalidade na barra de navegação, como as configurações da conta ou o perfil.

**Aprimoramento de formulários personalizados**

_Formulários personalizados no meu grupo_

Para obter uma melhor experiência ao preencher um formulário personalizado, melhoramos a forma como os rótulos de campos personalizados longos são exibidos. Quando há espaço horizontal suficiente para exibi-los na totalidade, esses rótulos não são mais truncados.

+++

+++**Atualização de manutenção em 8 de abril de 2021**

**Não é possível criar provas em [!DNL Adobe Creative Cloud] integração**

_Integrações do Workfront_

Quando um usuário tenta criar uma prova diretamente do [!DNL Adobe Creative Cloud], a prova não é gerada.

+++

+++**Atualização de manutenção em 1 de abril de 2021**

**Problemas ao visualizar o painel de resumo em[!DNL Chrome]**

_[!UICONTROL Resumo]_

Quando um usuário abre o [!UICONTROL Resumo] ao usar o [!DNL Chrome] No navegador, a interface do usuário do painel de resumo não se comporta conforme esperado. O usuário não pode rolar, os ícones podem desaparecer e o conteúdo pode se sobrepor a outro conteúdo.

**[!UICONTROL Equipes] área em [!UICONTROL Configuração] não exibir todas as equipes**

_[!UICONTROL Configuração]_

Quando um administrador vai para o [!UICONTROL Equipes] área de [!UICONTROL Configuração], eles podem exibir somente as equipes que criaram. As equipes criadas por outros administradores não estão visíveis.

**Não é possível adicionar atualizações ao projeto no [!UICONTROL Aprovação pendente] status**

_Projetos_

Se um usuário tentar adicionar uma atualização a um projeto em [!UICONTROL Aprovação pendente] e não são o usuário atribuído para aprovar o projeto, a atualização não é adicionada e eles veem o seguinte aviso:

Um projeto com um &#39;[!DNL Pending Approval]Não é possível editar o status &#39;. Você pode modificar o projeto alterando o status.

+++


## Atualizações em março de 2021

+++**Atualização de manutenção em 26 de março de 2021**

**Botões em um caso comercial são exibidos incorretamente**

_Projetos_

Quando um usuário estiver visualizando um caso comercial e a janela estiver no modo de tela cheia, a variável [!UICONTROL Salvar] e [!UICONTROL Cancelar] os botões são exibidos perto do meio da tela, sobrepondo os elementos do caso comercial.

**Não é possível alterar a classificação de um relatório**

_Relatórios_

Quando um usuário tenta alterar a classificação de um relatório no novo [!DNL Workfront] , a classificação não muda da classificação selecionada durante a criação do relatório.

**Compartilhamento desativado em novas provas**

_[!DNL Workfront Proof]_

Quando um usuário tiver [!UICONTROL Compartilhamento público] habilitado nas configurações de prova padrão cria uma prova, a prova é criada com o compartilhamento desativado. Outros usuários não podem ver a variável [!UICONTROL Compartilhar] ou compartilhe a prova.

**&quot;[!UICONTROL Falha ao gerar prova]&quot; erro ao criar prova**

_[!DNL Workfront Proof]_

Quando um usuário tenta criar uma prova, a prova não é criada e o usuário vê a seguinte mensagem de erro:

&quot;[!UICONTROL Falha na prova ao gerar — erro interno]&quot;

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 25 de março de 2021**

**Remoção do campo de referência ou coleção redundante do painel de mapeamento**

_[!DNL Workfront Fusion]2,0_

Quando um usuário usa um termo da variável [!DNL Workfront] API para selecionar uma coleção ou um campo de referência a ser incluído na saída de um [!DNL Workfront] módulo, a saída desse módulo mostra esse campo com dois pontos (como [!UICONTROL proprietário:nome]) e também nos atributos (o nome é um campo sob o proprietário). O campo rotulado com dois pontos não contém dados e fornece dados incorretos se mapeados para um módulo posteriormente no cenário.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 18 de março de 2021**

**As configurações do modelo de projeto agora se aplicam aos projetos criados por meio de [!DNL Workfront Fusion] 2,0**

_[!DNL Workfront Fusion]2,0_

Ao criar um projeto a partir de um modelo usando o [!DNL Workfront Fusion] 2.0, as configurações do modelo são aplicadas ao novo projeto. Esse comportamento é o mesmo ao criar um projeto a partir de um modelo no [!DNL Workfront] aplicativo.

+++

+++**Atualização de manutenção em 18 de março de 2021**

**As configurações do modelo de projeto agora se aplicam aos projetos criados por meio da API**

_[!DNL Workfront]API_

Ao criar um projeto a partir de um modelo usando o [!DNL Workfront] API, as configurações do modelo são aplicadas ao novo projeto. Esse comportamento é o mesmo ao criar um projeto a partir de um modelo no [!DNL Workfront] aplicativo.

+++

+++**Atualização de manutenção (hotfix) em 15 de março de 2021**

**O componente compartilhado não está funcionando como esperado**

_[!DNL Workfront Proof]_

Se independente [!DNL Workfront Proof] contas são movidas para um componente compartilhado, a seguinte funcionalidade pode ocorrer quando um usuário adiciona uma nova versão de uma prova ou documento:

* O usuário não pode excluir o usuário [!UICONTROL Prova de Studio].
* A mensagem padrão não é exibida na nova versão.

**Compartilhamento de link público não ativado na nova versão de uma prova**

_Documentos_

Quando um usuário ativa o compartilhamento de link público em uma prova e, em seguida, carrega uma nova versão da prova, o compartilhamento de link público não é ativado automaticamente na nova versão da prova.

**[!UICONTROL Aprovar], [!UICONTROL Alterações], [!UICONTROL Rejeitar] botões ausentes da prova**

_[!DNL Workfront Proof]_

Quando um usuário exibe uma prova no Visualizador de prova, a variável [!UICONTROL Aprovar], [!UICONTROL Alterações]e [!UICONTROL Rejeitar] estão ausentes na parte superior da tela.

**Não é possível alterar a classificação de um relatório**

_Relatórios_

Quando um usuário tenta alterar a classificação de um relatório no novo [!DNL Workfront] , a classificação não muda da classificação selecionada durante a criação do relatório.

**Mensagem personalizada na prova que não está sendo transferida para a nova versão**

_[!DNL Workfront Proof]_

Quando um usuário anexa uma mensagem personalizada a uma prova e, em seguida, carrega uma nova versão dessa prova, a mensagem personalizada não é exibida na nova prova.

**A lista de usuários não é exibida**

_Listas_

Quando um usuário tenta visualizar uma lista de usuários, e a exibição inclui o &quot;[!UICONTROL Ícones de status]&quot;, a lista não é exibida.

**&quot;[!UICONTROL Notificar destinatários sobre esta prova]&quot; opção desabilitada independentemente das configurações do fluxo de trabalho**

_[!DNL Workfront Proof]_

Quando um usuário cria uma nova prova e não ativa manualmente o &quot;[!UICONTROL Notificar destinatários sobre esta prova]&quot;, o recipient pretendido não é notificado. Isso é verdade mesmo se a opção estiver habilitada nas configurações do fluxo de trabalho.

**Não é possível alterar o intervalo de tempo**

_[!UICONTROL Análise aprimorada]_

Quando um usuário exibe [!UICONTROL Análise aprimorada] e clicar no calendário para ajustar o intervalo de datas, as datas não serão alteradas.

**Não é possível baixar o documento compartilhado publicamente**

_Documentos_

Quando um usuário clica em um link compartilhado para baixar um documento, o documento não é baixado e o usuário vê um erro do navegador informando que a página não existe.

+++

+++**Atualização de manutenção em 11 de março de 2021**

**Seção de formulário personalizado que não exporta para não administradores**

_Formulários personalizados_

Se um formulário personalizado anexado a um objeto tiver uma quebra de seção que exija algo acima de &quot;[!UICONTROL Exibir]&quot; acesso necessário para visualizar o conteúdo da seção, o conteúdo da seção não pode ser exportado por ninguém além de um Administrador.

**O documento baixado tem nome incorreto**

_[!DNL Workfront Proof]_

Quando um usuário baixa um documento do [!UICONTROL Visualizador de prova], o do documento tem o nome de uma versão anterior do documento, não a versão que foi baixada.

+++

+++**Atualização de manutenção em 4 de março de 2021**

**Erro ao acessar modelo de layout**

_Modelos de layout_

Quando um usuário se inscreveu no novo [!DNL Workfront] a experiência muda para a [!DNL Classic] e tentativas de acessar uma [!DNL Classic] modelo de layout, eles veem o erro &quot;[!UICONTROL Essa página não existe.]&quot;

**Não é possível editar filtros na [!UICONTROL Balanceador de Carga de Trabalho]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta editar um filtro na [!UICONTROL Balanceador de Carga de Trabalho], o construtor de filtros não abre.

**&quot;[!UICONTROL Ver todas as notificações]&quot; link na notificação por email redireciona para a página incorreta**

_Notificações de email_

Quando um usuário clica no &quot;[!UICONTROL Ver todas as notificações]&quot; em uma notificação por email, eles são redirecionados para uma página com a seguinte mensagem:

&quot;[!UICONTROL O usuário não existe mais. Talvez tenha digitado o endereço incorreto. Verifique e digite o endereço novamente.]&quot;

**O usuário não é direcionado ao comentário de prova em que está marcado**

_Notificações de email_

Quando um usuário estiver marcado em um comentário de prova e clicar no botão [!UICONTROL Ir para prova] em uma notificação por email, elas são direcionadas à prova, mas não ao comentário específico. Se o usuário estiver em [!DNL Workfront Classic], são direcionadas para a variável [!UICONTROL Detalhes do documento] em vez do comentário na prova.

**Usuários adicionados a [!DNL Workfront] estágio recebendo notificações por email**

_[!DNL Workfront Proof]_

Quando um usuário que não está no workflow abre uma prova de [!DNL Workfront], o sistema cria automaticamente um estágio, adiciona esse usuário à prova e envia um [!UICONTROL Nova prova] notificação por email.

**O painel de resumo do documento escurece, tornando as ações indisponíveis**

_Documentos_

Quando um usuário está em uma página de documento e passa o mouse sobre o painel de resumo do documento, o painel fica escuro e pode mostrar outros botões. O usuário não pode clicar nas ações no painel de resumo.

**Atualizar alterações de desempenho do fluxo**

_Atualizar fluxo_

Reduzimos o número de atualizações de usuários exibidas no [!UICONTROL Atualizações] de 50 a 25 de cada vez para melhorar o desempenho.

+++

+++**Atualização de manutenção (hotfix) em 1 de março de 2021**

**Novos emails de prova não estão sendo enviados**

_[!DNL Workfront Proof]_

OBSERVAÇÃO: Esse problema foi corrigido no novo [!DNL Workfront] experiência em 26 de fevereiro de 2021.
Foi corrigido no [!DNL Classic] experiência em 1 de março de 2021.

Quando um usuário cria uma nova prova e ativa a opção [!UICONTROL Notificar destinatários sobre esta prova], não há nenhum email enviado para notificar o recipient.

+++


## Atualizações em fevereiro de 2021

+++**Atualização de manutenção em 25 de fevereiro de 2021**

**[!UICONTROL Agendamento] a ferramenta não será carregada em nenhuma área**

_Gerenciamento de recursos_

Quando um usuário com um apóstrofo em seu nome de usuário tenta acessar a variável [!UICONTROL Agendamento] na ferramenta em [!DNL Workfront Classic], a página fica em branco e a ferramenta nunca é carregada.

**O nome não é alterado em novas versões de prova**

_Documentos_

Quando um usuário no novo [!DNL Workfront] a experiência faz upload de uma nova versão de um documento com um nome diferente, o nome não é atualizado para corresponder ao nome da versão mais recente.

**[!UICONTROL Compartilhamento de documentos] erro ao excluir projetos**

_Projetos_

Quando um usuário administrador do sistema tem acesso a um projeto que foi copiado e tenta excluí-lo ou excluir um documento do projeto, ele não pode excluir o objeto e vê o erro &quot;[!UICONTROL Compartilhamento de documentos com valores de chave primária não encontrado.]&quot;

**O relatório do usuário não está aplicando todos os filtros**

_Relatórios_

Quando um usuário no novo [!DNL Workfront] a experiência cria um relatório de Usuário com uma regra de filtro que inclui a variável [!UICONTROL ID principal] , nenhuma outra regra de filtro no relatório está sendo aplicada.

**Campos calculados não são recalculados após edições**

_Formulários personalizados_

Quando um usuário no novo [!DNL Workfront] A experiência edita e salva um Formulário personalizado que contém campos calculados; esses campos não são atualizados.

**Documentos excluindo quando o formulário personalizado é excluído**

_Formulários personalizados_

Quando um usuário no novo [!DNL Workfront] a experiência exclui um formulário personalizado Documentos anexado a documentos, esses documentos também são excluídos.

+++

+++**Atualização de manutenção em 18 de fevereiro de 2021**

**Caixa de seleção desnecessária removida de [!UICONTROL Solicitações] area**

_Solicitações_

Removemos a caixa de seleção à esquerda dos nomes das solicitações na lista Enviada do [!UICONTROL Solicitações] área. Essa caixa de seleção não estava conectada a nenhuma funcionalidade, portanto, a removemos para eliminar uma experiência confusa.

**Não é possível acessar documentos a partir de links**

_Documentos_

Quando um usuário no novo [!DNL Workfront] a experiência clica em alguns links de documento, eles não podem acessar o documento e veem a mensagem de erro &quot;[!UICONTROL O Documento não existe mais: Você pode ter digitado incorretamente o endereço da Web. Verifique-o novamente e tente inserir o endereço novamente.]&quot;Esse mesmo erro ocorre com o [!UICONTROL Exibir detalhes] nas notificações por email de prova.

+++

+++**Atualização de manutenção do Workfront Fusion em 16 de fevereiro de 2021**

**[!DNL Workfront Fusion]2.0 mostra fusos horários imprecisos**

_Cenários_

Esta atualização corrigiu um problema em que [!DNL Fusion] 2.0 estava exibindo fusos horários do usuário com imprecisão. Agora, os usuários podem ver o fuso horário exibido em campos de entrada para datas.

+++

+++**Atualização de manutenção em 11 de fevereiro de 2021**

**As provas não estão sendo carregadas na pasta selecionada**

_[!DNL Workfront Proof]_

Quando um usuário abre uma pasta e adiciona uma nova prova, a prova é carregada para o [!UICONTROL Documentos] área do objeto em vez de dentro da pasta.

**Muitas páginas afixadas fazem com que a Navegação superior desapareça**

_Navegação_

Quando um usuário tem mais de 60 páginas fixas, a Navegação superior para de ser exibida, impedindo que o usuário acesse [!UICONTROL Pesquisar], o [!UICONTROL Menu principal], [!UICONTROL Notificações]e muito mais.

**O usuário não pode digitar texto em campo Rich Text**

_Listas_

Quando um usuário tenta editar um campo Rich Text em linha, ele só pode digitar um único caractere.

+++

+++**Atualização de manutenção em 4 de fevereiro de 2021**

**Relatórios exportados exibem [!DNL Workfront Classic] identidade visual**

_Relatórios_

Quando um usuário na nova experiência do Workfront exporta um relatório, o logotipo exibido no relatório exportado corresponde ao [!DNL Workfront Classic] configurações encontradas em [!UICONTROL Configuração] > [!UICONTROL Sistema] > [!UICONTROL Marca].

+++


## Atualizações em janeiro de 2021

+++**Atualização de manutenção em 28 de janeiro de 2021**

**Comentários que não exibem &quot;[!UICONTROL em nome de]&quot;**

_Atualizações_

Quando uma [!DNL Workfront] o administrador faz logon como outro usuário e responde a um comentário na [!UICONTROL Atualizações] área de um objeto, o texto &quot;[!UICONTROL em nome de]&quot; não é exibido antes do nome do usuário.

**Não é possível anexar um documento**

_Solicitações_

Quando um usuário no novo [!DNL Workfront] a experiência tenta adicionar um documento a uma nova solicitação de um provedor de documentos externo, a variável [!UICONTROL Documentos] não carrega, o que impede que o usuário selecione o documento e conclua a solicitação.

**Largura da tela se expandindo à direita, causando problemas de navegação**

_[!UICONTROL Calendário doméstico]_

Quando um usuário no novo [!DNL Workfront] a experiência abre o [!UICONTROL Calendário doméstico] E têm itens que devem ser vencidos em algumas semanas, a tela se expande para a direita, impedindo-os de visualizar a semana inteira de uma só vez. Se o usuário selecionar um item para abrir o [!UICONTROL Detalhes] nesse estado, e eles desejam exibir os detalhes de outro item, eles precisam rolar para a esquerda, o que fecha o [!UICONTROL Detalhes] painel.

**Rótulo do processo de aprovação de utilização única corrigido**

_Projetos_

Ao usar um processo de aprovação de uso único para um projeto no novo [!DNL Workfront] agora é exibido como &quot;[!UICONTROL Processo de aprovação de uso único]&quot; em vez de &quot;\&lt;custom>&quot; na [!UICONTROL Editar projeto] caixa. Isso ainda não está disponível para tarefas e problemas.

**Aparência e comportamento aprimorados para formulários personalizados**

_Projetos_

Melhoramos a aparência de trabalhar com formulários personalizados nos novos [!DNL Workfront] experiência para projetos.

**A funcionalidade de API para moeda do projeto agora corresponde à funcionalidade no aplicativo**

_Projetos_

Não é possível alterar a moeda de um projeto quando já há informações financeiras sobre o projeto. Com a atualização de manutenção mais recente, a funcionalidade da API para esse caso agora corresponde à experiência no [!DNL Workfront] interface.

**Não gerar automaticamente a semana seguinte**

_Planilhas de horas_

Quando um usuário navega até a variável [!UICONTROL Folhas de Horas] área, eles só visualizam a folha de ponto da semana atual. A folha de horas das próximas semanas não é gerada automaticamente.

+++

+++**Atualização de manutenção em 21 de janeiro de 2021**

**A classificação manual por coluna exibe todos os resultados**

_Relatórios_

Quando um usuário no novo [!DNL Workfront] a experiência clica em uma barra no gráfico de um relatório, em seguida, clica em um cabeçalho de coluna para classificar manualmente os resultados desse agrupamento, todos os resultados do relatório são exibidos, não apenas os resultados do agrupamento selecionado originalmente.

**&quot;[!UICONTROL Permitir compartilhamento de prova via URL ou código incorporado]&quot; alterações na configuração**

_[!DNL Workfront Proof]_

Quando um usuário cria uma prova e desmarca a configuração [!UICONTROL Permitir compartilhamento de prova via URL ou código incorporado], a configuração é verificada novamente após a prova ser gerada. Se o usuário deixar a configuração marcada, ela será desmarcada após gerar a prova.

**[!DNL Mac]os usuários não podem colar em campos de texto no visualizador de prova**

_[!DNL Workfront Proof]_

Quando um usuário tenta colar o texto em determinados campos no visualizador de prova, ele não é exibido no campo .

+++

+++**Atualização de manutenção em 14 de janeiro de 2021**

**Não é possível atualizar as configurações de Notificações por email**

_Configuração_

Quando um usuário tenta atualizar as configurações para notificações por email, ele não consegue acessar o [!UICONTROL Notificações por email] e veja a mensagem de erro &quot;[!UICONTROL Vamos tentar de novo. Uau! Um erro inesperado aconteceu. Entre em contato [!DNL Workfront] então podemos descobrir o que deu errado e consertá-lo.]&quot;

**[!UICONTROL Gráfico de Gantt] faz com que alguns campos fiquem truncados**

_Listas_

Quando um usuário abre o [!UICONTROL Gráfico de Gantt] em algumas áreas de lista, determinados campos, como [!UICONTROL Descrição]—truncar o texto. O usuário precisa clicar duas vezes no campo para ver o texto completo.

**Não é possível enviar arquivos de [!UICONTROL Detalhes do documento]**

_Documentos_

Quando um usuário no novo [!DNL Workfront] a experiência tenta enviar um documento do [!UICONTROL Detalhes do documento] , eles visualizarão a mensagem de erro &quot;[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.]&quot;

+++

+++**Atualização de manutenção em 7 de janeiro de 2021**

**A caixa de diálogo Delegar aprovações é fechada**

_Início_

Quando um usuário tenta delegar aprovações em [!UICONTROL Início] e clicar em qualquer data, a caixa de diálogo será fechada sem selecionar a data ou permitir que o usuário conclua a delegação do usuário.

**Problema ao mover um documento para uma tarefa**

_Documentos_

Quando um usuário tenta mover um documento ou uma prova no novo [!DNL Workfront] , algumas tarefas fora do projeto não listam o projeto pai conforme esperado.

**PDF baixado com nome incorreto**

_[!DNL Workfront Proof]_

Quando um usuário recebe um link de download por email ([!UICONTROL Prova] > [!UICONTROL Imprimir comentários] > [!UICONTROL PDF]) e eles exportam o arquivo, o arquivo baixado é intitulado de números aleatórios em vez da ID da prova.

+++
