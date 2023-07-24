---
title: Atualizações de manutenção do Workfront de 2021
description: Histórico das atualizações de manutenção de 2021 do [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
feature: Get Started with Workfront
source-git-commit: 98d56729e44e7ab47e201bdfc00db8d40c5f15f6
workflow-type: ht
source-wordcount: '10019'
ht-degree: 100%

---

# Atualizações de manutenção de 2021 do [!DNL Workfront] 

As seguintes atualizações de manutenção foram efetuadas em 2021:

## Atualizações em dezembro de 2021

+++**Atualização de manutenção em 23 de dezembro de 2021**

**Novas tarefas padrão para restrição da tarefa incorreta**

_Tarefas_

Quando um usuário cria uma nova tarefa usando o botão “[!UICONTROL Nova tarefa]”, e a opção [!UICONTROL Data inicial padrão da nova tarefa] está definida como “[!UICONTROL Hoje]”, a restrição da tarefa criada é definida como “[!UICONTROL Assim que possível]” em vez de “[!UICONTROL Não começar antes de].” Isso também pode ocorrer ao usar modelos de projeto.

O **Horário de abertura na área [!UICONTROL Grupos] abre uma página em branco**

_Configuração_

Quando um usuário está visualizando grupos na área [!UICONTROL Configuração] e tenta abrir, editar ou copiar um agendamento, o agendamento não abre e o usuário vê uma página em branco.

**As alterações não são exibidas ao reorganizar a navegação à esquerda**

_Navegação_

Quando um usuário tenta reorganizar o painel de navegação esquerdo arrastando um item, ele aparece de volta em seu lugar anterior quando o usuário o solta. Se o usuário atualizar a página, o painel esquerdo exibirá a nova ordem.

**O link para enviar um documento solicitado abre uma página em branco.**

_Documentos_

Quando um usuário recebe uma solicitação para enviar um documento e clica no link para o objeto no qual o documento foi solicitado, o link abre uma página em branco. Isso pode ocorrer ao clicar em um link em um email ou em uma notificação no aplicativo.

O **[!UICONTROL Balanceador de carga de trabalho] mostra 0 horas alocadas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário está visualizando o [!UICONTROL Balanceador de carga] com a configuração “[!UICONTROL Mostrar datas projetadas]” ativada, qualquer data no futuro exibe 0 horas alocadas.

**Provas desaparecem intermitentemente das pastas**

_[!DNL Workfront Proof]_

Quando um usuário que está conectado ao [!DNL Workfront Proof] visualiza uma pasta, a pasta aparece vazia. Se o usuário verificar novamente mais tarde, as provas estarão visíveis.

+++

+++**Atualização de manutenção em 16 de dezembro de 2021**

**Clicar no anúncio na lista de notificações abre uma página em branco**

_Notificações_

Ao abrir a lista de notificações pelo ícone [!UICONTROL Notificações] e clicar em um anúncio, o usuário é direcionado a uma página em branco e o anúncio não é exibido.

**O painel Resumo mostra “[!UICONTROL Nenhuma seleção]” quando a tarefa é selecionada**

_Tarefas_

Quando um usuário abre um resumo de documento na área [!UICONTROL Documentos] de um projeto, acessa a lista de tarefas, seleciona uma tarefa e tenta abrir o resumo de tarefas, ele não é exibido e o usuário vê a seguinte mensagem:

[!UICONTROL Nenhuma seleção. Selecione um documento na lista para ver os detalhes.]

A mensagem menciona documentos mesmo que o usuário esteja na lista de tarefas.

**[!UICONTROL Trabalho não atribuído] não carrega**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário no [!UICONTROL Balanceador de carga de trabalho] cria um filtro usando o campo [!UICONTROL Atribuição:ID de função], a área [!UICONTROL Trabalho não atribuído] não carrega.

**Anexar um modelo usando a opção “[!UICONTROL Personalizar e anexar]” apaga os valores dos campos personalizados**

_Projetos_

Se um usuário anexar um modelo a um projeto usando a opção “[!UICONTROL Personalizar e anexar]” e o projeto já tiver um formulário personalizado anexado a ele, os valores de campo personalizado não serão transferidos e deverão ser inseridos manualmente de novo. Isso ocorre mesmo quando o modelo inclui o mesmo formulário personalizado.

+++

+++**Atualização de manutenção (hotfix) em 10 de dezembro de 2021**

**[!UICONTROL Ops] erro ao anexar o modelo ao projeto existente**

_Projetos_

Quando um usuário tenta anexar um modelo a um projeto existente, o modelo não é anexado e o usuário vê o seguinte erro:

“[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

+++

+++**Atualização de manutenção em 9 de dezembro de 2021**


**O painel de navegação esquerdo recolhido expande-se ao carregar a página**

_Navegação_

Quando um usuário define que a navegação à esquerda será recolhida e, em seguida, atualiza uma página, a navegação à esquerda se expande na página recarregada. A navegação à esquerda também é expandida se o usuário abrir uma página em uma nova guia.

O **[!UICONTROL Balanceador de carga de trabalho] mostra 0 horas alocadas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário está visualizando o [!UICONTROL Balanceador de carga] com a configuração “[!UICONTROL Mostrar datas projetadas]” ativada, qualquer data no futuro exibe 0 horas alocadas.

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

Quando um usuário preenche uma solicitação e começa manualmente a digitar um URL, uma barra extra é adicionada em algum ponto próximo ao início do URL. O usuário não pode excluir a barra.

**As seções personalizadas não podem ser removidas do painel de navegação esquerdo**

_Navegação_

Quando um usuário tenta remover uma seção personalizada do painel de navegação esquerdo clicando no X ao lado da seção, ela não é removida.

**Trabalho não atribuído não carrega**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário no [!UICONTROL Balanceador de carga de trabalho] cria um filtro usando o campo [!UICONTROL Atribuição:ID de função], a área [!UICONTROL Trabalho não atribuído] não carrega.

**Páginas não carregam em determinados navegadores**

_[!DNL Workfront]_

Quando um usuário está trabalhando no [!DNL Workfront], as páginas não são carregadas e o usuário vê a seguinte mensagem de erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

Este erro foi reportado em

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Este erro ocorre aleatoriamente e pode afetar qualquer área do [!DNL Workfront].

+++


## Atualizações em novembro de 2021

+++**Atualização de manutenção em 18 de novembro de 2021**

Erro **[!DNL Workfront]para [!DNL Jira] “[!UICONTROL Invalid clientID ou clientSecret]” no login**

_Integrações do Workfront_

Os usuários foram desconectados do [!DNL Jira] para integração com o Workfront. Quando um usuário tenta fazer logon na integração do [!DNL Workfront for Jira], não é possível fazer logon e o seguinte erro é exibido:

“[!UICONTROL Invalid clientID ou clientSecret]”

**O formulário personalizado anexado à solicitação não é atualizado quando o novo Tópico da fila é selecionado**

_Solicitações_

Quando um usuário cria uma solicitação e seleciona um Tópico da fila que anexa automaticamente um formulário personalizado à solicitação e seleciona um Tópico da fila diferente, o formulário personalizado do primeiro Tópico da fila permanece anexado à solicitação.

**Os ícones são exibidos incorretamente**

_[!DNL Workfront]_

Imagens de ícones são exibidas incorretamente. Isso foi relatado em muitas áreas no [!UICONTROL Workfront].

**As tarefas não são exportadas para PDF quando a opção “Outros tamanhos” está selecionada.**

_Tarefas_

Se um usuário tentar exportar uma lista de tarefas para o PDF e selecionar a opção “[!UICONTROL Outros tamanhos]”, é possível selecionar um tamanho e clicar em [!UICONTROL Exportar], mas a lista não é exportada. Não há mensagem de erro e nenhuma outra indicação de que a exportação foi malsucedida.

**O indicador de imagem não é exibido nas notificações por email**

_Notificações_

Quando um usuário adiciona uma imagem a uma atualização e uma notificação por email é enviada ao recipient da atualização, o email não inclui um indicador de que há uma imagem na atualização.

**Páginas não carregam em determinados navegadores**

_[!DNL Workfront]_

Quando um usuário está trabalhando no [!DNL Workfront], as páginas não são carregadas e o usuário vê a seguinte mensagem de erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

Este erro foi reportado em

* [!DNL Firefox]
* [!DNL Microsoft Edge]

Esse erro ocorre aleatoriamente e pode afetar qualquer área do Workfront.

+++

+++**Atualização de manutenção em 11 de novembro de 2021**

**Problema com integrações de documentos, página em branco no pop-up de upload de documento[!DNL Google Drive*]*

_Documentos_

Quando um usuário tenta adicionar um novo documento no [!DNL Workfront] a partir do [!DNL Google Drive] usando [!UICONTROL Adicionar novo] > [!UICONTROL De [!DNL Google Drive]], a tela pop-up de upload permanece em branco.

**Não é possível usar mais de um filtro no Balanceador de carga de trabalho**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta usar mais de um filtro no [!UICONTROL Balanceador de carga de trabalho], os seguintes problemas aparecem:

* Se o usuário selecionar dois filtros, somente o filtro inferior será aplicado.
* Se o usuário selecionar mais de dois filtros, nenhum resultado será exibido.

O cabeçalho do documento **“[!UICONTROL Pastas do projeto]” não aparece na área de documentos do projeto**

_Projetos_

Quando um usuário está em um projeto e visualiza os documentos do projeto, o cabeçalho “[!UICONTROL Pastas do projeto]” não aparece na navegação à esquerda. A seta suspensa ainda existe e o usuário pode selecionar uma pasta.

**As colunas no quadro Kanban são muito largas e não podem ser ajustadas**

_Agile_

Quando um usuário exibe um quadro Kanban com várias colunas, elas são muito largas e o usuário deve rolar a tela para exibir ou mover cartões para as colunas mais à direita. As larguras de coluna não são ajustáveis, portanto, o usuário não pode tornar as colunas menores para que todas fiquem visíveis na tela ao mesmo tempo.

**Interface aprimorada para criar uma nova equipe**

_Equipes_

Criar equipes agora ficou mais intuitivo com novas dicas visuais. Ao selecionar o ícone [!UICONTROL Trocar equipes] em qualquer página da equipe, o link [!UICONTROL Criar nova equipe] tem um ícone para indicar “[!UICONTROL novo]” e o link é separado do restante da lista, de modo que não pareça um nome de equipe. Essa interface é a mesma para equipes ágeis e não ágeis.

+++

+++**Atualização de manutenção em 4 de novembro de 2021**

**Novas tarefas padrão para restrição da tarefa incorreta**

_Tarefas_

Quando um usuário cria uma nova tarefa usando o botão “[!UICONTROL Nova tarefa]”, e a opção Data inicial padrão da nova tarefa está definida como “[!UICONTROL Hoje]”, a restrição da tarefa criada é definida como “[!UICONTROL Assim que possível]” em vez de “[!UICONTROL Não começar antes de].”

**Os campos não são exibidos nos cartões de história do Agile**

_Agile_

Quando um usuário visualiza um storyboard do Agile, os cartões são exibidos somente nos campos [!UICONTROL Descrição] e [!UICONTROL Status]. Nenhum outro campo, inclusive qualquer campo personalizado, será exibido.

**Os cartões retornam à coluna original antes de passar para a nova coluna**

_Agile_

Quando um usuário arrasta um cartão para uma nova coluna no storyboard, ele pode ver o cartão que está sendo arrastado. No entanto, quando o usuário solta o cartão na nova coluna, o cartão aparece brevemente na coluna original antes de ser exibido na nova coluna.

**Valores não disponíveis para campo personalizado no filtro**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta criar um filtro usando um campo personalizado, o valor desse campo personalizado não é exibido e não pode ser inserido no filtro.

**Páginas que não estão sendo carregadas no navegador do [!DNL Firefox]**

_[!DNL Workfront]_

Quando um usuário está trabalhando no [!DNL Workfront] usando um navegador do [!DNL Firefox], as páginas não carregam e o usuário vê a seguinte mensagem de erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

Este erro ocorre aleatoriamente e pode afetar qualquer área do [!DNL Workfront].

**Erro relacionado à data ao criar projeto a partir do modelo.**

_Modelos_

Se um usuário criar um projeto a partir de um modelo, definir o modo de agendamento como [!UICONTROL Data inicial] e selecionar uma restrição de tarefa, quando o usuário tentar criar o projeto, o projeto não será criado e o usuário verá uma mensagem de erro com base na restrição da tarefa.

A caixa de diálogo **[!UICONTROL Exportar Gráfico de Gantt] não responde**

_Gráfico de Gantt_

Se um usuário na nova experiência do [!DNL Workfront] tentar exportar o [!UICONTROL Gráfico de Gantt] e selecionar a opção “[!UICONTROL O que vejo]”, o [!UICONTROL Gráfico de Gantt] não é exportado e a caixa de diálogo não responde. O usuário não pode fechar ou clicar fora da caixa de diálogo.

**Os ícones são exibidos incorretamente**

_[!DNL Workfront]_

Imagens de ícones são exibidas incorretamente. Foram reportadas situações que incluem, mas não se limitam a:

* Imagens para funções ou grupos de trabalho ao compartilhar um objeto
* Ícones da esquerda e da direita em relatórios de calendário
* Classificar ícones nas colunas do relatório

**Adicionar caixas de seleção a solicitações na seção [!UICONTROL Enviado] da área [!UICONTROL Solicitações]**

_Solicitações_

Adicionamos caixas de seleção à esquerda dos nomes das solicitações na [!UICONTROL Lista enviada] da área [!UICONTROL Solicitações]. Isso facilita a seleção de uma solicitação e a visualização de informações adicionais.

**Os Trimestres personalizados agora são permitidos nos filtros de Balanceador de carga de trabalho**

_[!UICONTROL Balanceador de carga de trabalho]_

Os filtros no [!UICONTROL Balanceador de carga de trabalho] agora permitem trimestres personalizados.

**O operador de filtro foi atualizado para o campo Duração nos Filtros do balanceador de carga de trabalho**

_[!UICONTROL Balanceador de carga de trabalho]_

Atualizamos os operadores de filtro ao filtrar as áreas do [!UICONTROL Balanceador de carga de trabalho] por [!UICONTROL Duração].

+++


## Atualizações em outubro de 2021

+++**Atualização de manutenção em 28 de outubro de 2021**

**[!UICONTROL Página inicial] e [!UICONTROL Meu trabalho] exibem uma página em branco**

_[!UICONTROL Página inicial] / [!UICONTROL Meu trabalho]_

Quando um usuário navega para [!UICONTROL Página inicial] ou Meu trabalho, a página é exibida em branco.

**Não é possível visualizar ou editar detalhes do [!UICONTROL Grupo de tópicos]**

_Solicitações_

Quando um usuário tenta visualizar ou editar os detalhes de um Grupo de tópicos, a página que abre mostra “[!UICONTROL Detalhes do grupo de tópicos]” no cabeçalho, mas está em branco

**Os botões de opção obrigatórios em branco são preenchidos automaticamente**

_Solicitações_

Quando um usuário envia uma solicitação com um campo de botão de opção obrigatório e não seleciona um valor para esse campo antes de enviar a solicitação, o primeiro valor é automaticamente selecionado quando a solicitação é enviada.

+++

+++**Atualização de manutenção em 21 de outubro de 2021**

**Não é possível adicionar um filtro no [!UICONTROL Balanceador de carga de trabalho]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário no [!UICONTROL Balanceador de carga de trabalho] tenta adicionar um filtro, o painel [!UICONTROL Adicionar filtro] abre, mas o conteúdo do painel não é carregado e o usuário não pode adicionar o filtro.

**O quadro Agile Scrum não exibe histórias**

_Agile_

Quando um usuário tenta visualizar o quadro Scrum na iteração de uma equipe, o quadro Scrum é exibido em branco.

**O storyboard Scrum fica em branco ao usar filtros**

_Agile_

Quando um usuário tenta exibir um storyboard Scrum usando qualquer filtro, exceto o filtro “[!UICONTROL Todos os grupos]”, uma tela em branco é exibida. O usuário não pode voltar para o filtro “[!UICONTROL Todas as equipes]”.

**As listas são visíveis somente em uma pequena área da tela**

_Listas_

Quando um usuário tenta visualizar uma lista ao usar um navegador do [!DNL Safari] em um [!DNL Mac] usando o [!DNL Big Sur OS], a lista é exibida somente em uma pequena área da tela. O usuário pode percorrer a lista, mas a área pode ser tão pequena que a lista é difícil ou impossível de ler.

**Os botões de opção obrigatórios em branco são preenchidos automaticamente**

_Solicitações_

Quando um usuário envia uma solicitação com um campo de botão de opção obrigatório e não seleciona um valor para esse campo antes de enviar a solicitação, o primeiro valor é automaticamente selecionado quando a solicitação é enviada.

+++

+++**Atualização de manutenção (hotfix) em 21 de outubro de 2021**

**[!UICONTROL Página inicial] e [!UICONTROL Meu trabalho] exibem uma página em branco**

_[!UICONTROL Página inicial] / [!UICONTROL Meu trabalho]_

Quando um usuário navega para [!UICONTROL Página inicial] ou [!UICONTROL Meu trabalho], a página é exibida em branco.

+++

+++**Atualização de manutenção em 20 de outubro de 2021**

O **[!UICONTROL Balanceador de carga de trabalho] é definido como a opção de agendamento padrão**

_[!UICONTROL Balanceador de carga de trabalho]_

Se definir o [!UICONTROL Scheduler] como padrão, o usuário verá que o [!UICONTROL Balanceador de carga de trabalho] foi definido como padrão.

+++

+++**Atualização de manutenção (hotfix) em 19 de outubro de 2021**

**Não é possível atribuir uma solicitação ao criá-la**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Workfront] cria uma solicitação e tenta atribuir um usuário digitando seu nome no campo [!UICONTROL Atribuições], o campo não exibe a lista suspensa e o usuário não consegue selecionar o nome do destinatário.

**O storyboard Scrum fica em branco ao usar filtros**

_Agile_

Quando um usuário tenta exibir um storyboard Scrum usando qualquer filtro, exceto o filtro “[!UICONTROL Todos os grupos]”, uma tela em branco é exibida. O usuário não pode voltar para o filtro “[!UICONTROL Todas as equipes]”.

+++

+++**Atualização de manutenção em 14 de outubro de 2021**

**Os modelos compartilhados em todo o sistema não estão visíveis**

_Modelos_

Ao criar um projeto e tentar usar um modelo que foi compartilhado em todo o sistema, o usuário não consegue ver o modelo na lista disponível e não pode usar o modelo.

**Erro ao criar projetos a partir de modelos**

_Modelos_

Quando um usuário tenta criar um projeto a partir de um modelo que inclui um formulário personalizado com uma seção visível somente para administradores, ele não pode criar o projeto, e a seguinte mensagem é exibida:

“[!UICONTROL A categoria com valores de chave primária ‘xxxxxxxxxxxxxxxx’ não foi encontrada]”

**Links atualizados para copiar e mover tarefas**

_Tarefas_

Os links para copiar e mover tarefas foram atualizados para “[!UICONTROL Copiar para]” e “[!UICONTROL Mover para]” tanto na página de tarefas quanto em uma lista de tarefas.

**Remover limite para pesquisa de função de trabalho ao substituir taxas de faturamento de um projeto**

Função no trabalho

OBSERVAÇÃO: esta atualização está no ambiente de Pré-visualização e estará em Produção com a versão de Produção 22.1. Para obter mais informações, consulte “Visão geral da versão 22.1”.

Substituir as taxas de faturamento de funções de trabalho em um projeto agora pesquisa todas as funções de trabalho no sistema.

Antes, o [!DNL Workfront] pesquisava funções de trabalho nas primeiras 2000 funções em ordem alfabética.

+++

+++**Atualização de manutenção em 7 de outubro de 2021**

**[!UICONTROL As notificações no aplicativo desaparecem do] centro de notificações**

_Notificações_

Quando um usuário visualiza o centro de notificações, algumas notificações anteriormente visíveis não ficam mais disponíveis. Em alguns casos, a notificação pode desaparecer antes que o usuário a visualize.

**Os anúncios não estão visíveis na página [!UICONTROL Todos os anúncios]**

_Notificações_

Quando um usuário abre a página [!UICONTROL Todos os anúncios] da área [!UICONTROL Notificações], não há anúncios visíveis nas seguintes áreas:

* [!UICONTROL Caixa de entrada]
* [!UICONTROL Favoritos]
* [!UICONTROL Rascunhos]
* [!UICONTROL Excluído]

**Erro ao fazer atribuição no [!UICONTROL Balanceador de carga de trabalho]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta fazer uma atribuição do [!UICONTROL Balanceador de carga de trabalho], o trabalho não é atribuído e o usuário vê o seguinte erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

+++


## Atualizações em setembro de 2021

+++**Atualização de manutenção em 30 de setembro de 2021**

**Erro ao navegar rapidamente para ou da [!UICONTROL Página inicial]**

_Página inicial_

Quando um usuário navega rapidamente para ou da [!UICONTROL Página inicial], a página não é carregada e o usuário vê o seguinte erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

Isso também pode ocorrer ao navegar para a [!UICONTROL Página inicial] por meio de um pino.

+++

+++**Atualização de manutenção em 23 de setembro de 2021**

Erro **[!UICONTROL Acesso negado] ao visualizar tíquetes enviados para o[!DNL Workfront]**

_Problemas_

Ao enviar um tíquete para o [!DNL Workfront] e tentar visualizar o tíquete, o usuário verá o seguinte erro:

“[!UICONTROL Acesso negado: ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

**O Resumo de business case mostra valores incorretos**

_Projetos_

Quando um usuário visualiza o painel de resumo [!UICONTROL Business case], os valores exibidos não refletem os valores nas seções [!UICONTROL Business Case] individuais.

**Os cabeçalhos de coluna não estão alinhados com as colunas em listas**

_Configuração_

Quando um usuário estiver na área [!UICONTROL Configuração] e visualizar uma lista, como [!UICONTROL Formulários personalizados] ou [!UICONTROL Níveis de acesso], os cabeçalhos de coluna para essa lista não estarão alinhados com as colunas na lista.

**Os usuários sem as permissões de compartilhamento adequadas podem anexar formulários personalizados a objetos**

_Formulários personalizados_

Quando um formulário personalizado na nova experiência do [!DNL Adobe Workfront] estiver definido para ser visível em todo o sistema, todos os usuários poderão anexar esse formulário personalizado a um objeto. No entanto, eles só devem ser capazes de exibir o formulário personalizado e não podem anexá-lo a um objeto, a menos que ele tenha sido compartilhado especificamente com eles.

+++

+++**Atualização de manutenção em 16 de setembro de 2021**

**Não é possível editar grupos**

_Grupos_

Quando um usuário tenta editar ou excluir um grupo, ele não é editado ou excluído e o usuário vê a seguinte mensagem:

“[!UICONTROL Vamos tentar novamente. Grupo com valores de chave primária ‘(ID do grupo)’ não encontrado]”

O **[!UICONTROL Otimizador de portfólios] não exibe projetos**

_Portfólios_

Quando um usuário tenta visualizar projetos no [!UICONTROL Otimizador de portfólios], a lista de projetos não é exibida e, portanto, o usuário não pode interagir com os projetos.

+++

+++**Atualização de manutenção (hotfix) em 10 de setembro de 2021**

**Data e hora marcadas como UTC ao editar em linha**

_Listas_

Quando um usuário edita uma data ou hora em linha (em uma lista de objetos), a data e a hora são marcadas como UTC. A data e a hora não estão definidas em UTC no [!DNL Workfront]. Esse problema afeta apenas a exibição, não os dados reais.

**A cor do texto não é exibida corretamente quando a formatação condicional é aplicada**

_Relatórios_

Quando um usuário exibe um relatório com formatação condicional que altera a cor do texto, ela é exibida sem alterações.

+++

+++**Atualização de manutenção em 9 de setembro de 2021**

**Os detalhes dos problemas não são exibidos**

_Página inicial_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] seleciona um problema na [!UICONTROL Lista de trabalho], a visualização no painel direito exibe determinados campos sem valores inseridos. No entanto, se você navegar até o problema e visualizar [!UICONTROL Detalhes do problema], esses campos terão valores inseridos.

**Os usuários precisam de permissões do Contribute para visualizar a seção [!UICONTROL Aprovações] na nova experiência do Workfront**

_Aprovações_

Os usuários precisam de permissões do [!UICONTROL Contribute] em um objeto para visualizar a seção [!UICONTROL Aprovações] na nova experiência do [!DNL Workfront]. Eles devem precisar apenas de permissões de [!UICONTROL Visualização] para visualizar a guia [!UICONTROL Aprovações] quando houver um processo de aprovação no objeto.

**[!UICONTROL Erro] ao usar filtros**

_Listas_

Quando um usuário tenta usar um dos seguintes filtros:

* [!UICONTROL Todos os Projetos]
* [!UICONTROL Projetos em que estou trabalhando]
* [!UICONTROL Minhas tarefas atuais]

a lista fica em branco e o usuário vê o seguinte erro:

“[!UICONTROL Vamos tentar novamente.]”

A seção **[!UICONTROL Tarefas] fica em branco ao editar em linha**

_Modelos_

Quando um usuário tenta editar tarefas em linha em um modelo usando uma visualização que inclui o campo “[!UICONTROL Atribuir a: Nome]” e a atribuição contém um usuário, a seção [!UICONTROL Tarefas] fica em branco e o usuário não consegue editar as tarefas do modelo.

**Não é possível exportar o [!UICONTROL Otimizador de portfólios]**

_Portfólios_

Quando um usuário tenta exportar o [!UICONTROL Otimizador de portfólios] e clica em qualquer uma das opções de exportação, o [!UICONTROL Otimizador de portfólios] não é exportado.

**As notificações não estão sendo enviadas para respostas**

_Notificações_

Quando um usuário responde a uma atualização no [!DNL Workfront], outros usuários na thread de comentários não recebem notificações.

**As alterações nos dados personalizados causam atraso**

_Campos personalizados_

Quando um usuário modifica dados personalizados que acionam alterações em outros dados exibidos, as alterações são carregadas lentamente.

**O ícone de agrupamento “[!UICONTROL Recolher ou expandir tudo]” não é exibido**

_Relatórios_

O ícone “[!UICONTROL Recolher ou expandir tudo]” não é exibido no cabeçalho de uma lista ou relatório quando os agrupamentos são aplicados à lista ou ao relatório.

As opções **[!UICONTROL Verificar] e [!UICONTROL Cancelar] não ficam visíveis ao alterar alocações de tarefas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta alterar a alocação de uma tarefa e o período dessa tarefa se estende até ou além da borda da página visível, os botões [!UICONTROL Verificar] e [!UICONTROL Cancelar] não ficam visíveis e o usuário não consegue salvar ou cancelar as alterações de alocação.

**A adição de um campo personalizado à [!UICONTROL Página inicial] faz com que dados de campo não apareçam**

_[!UICONTROL Página inicial]_

Quando um campo personalizado é adicionado à [!UICONTROL Página inicial], outros campos começam a desaparecer e são exibidos incorretamente.

**Não é possível visualizar itens vinculados quando conectado como outro usuário**

_Integrações_

Se um administrador tentou exibir itens vinculados de um provedor externo enquanto estava conectado como outro usuário, ele não pôde abrir as pastas vinculadas e não pôde exibir os itens.

+++

+++**Atualização de manutenção em 2 de setembro de 2021**

**Não é possível fixar o painel personalizado**

_Painéis_

Quando um usuário tenta fixar um painel personalizado, o painel não é fixado e o usuário vê o seguinte erro:

“[!UICONTROL Algo deu errado ao fixar. Entre em contato com [!DNL Workfront] para que possamos resolver isso.]”

O resumo de impressão do **[!DNL Workfront Proof]está em branco**

[!DNL Workfront Proof]

Quando um usuário abre o resumo de impressão para imprimir uma prova, o cabeçalho é exibido, mas o resumo em si está em branco.

+++


## Atualizações em agosto de 2021

+++**Atualização de manutenção em 26 de agosto de 2021**

**No [!DNL Safari] há um plano de fundo cinza escuro no texto dos cabeçalhos da coluna**

_Listas_

No navegador do [!DNL Safari], há um plano de fundo cinza escuro nos cabeçalhos da coluna, destacando o texto. Isso não é um problema com outros navegadores compatíveis.

**Erro inesperado ao definir predecessores**

_Tarefas_

Quando um usuário tenta definir uma tarefa como predecessora usando a edição em linha, a predecessora não é definida e o usuário vê a seguinte mensagem:

“[!UICONTROL Ocorreu um erro inesperado]”

+++

+++**Atualização de manutenção em 19 de agosto de 2021**

**Filtros salvos não aparecem após selecionar um filtro que não exibe problemas**

_Listas_

Filtros salvos estão ausentes em uma lista de problemas depois de selecionar um filtro que não exibe resultados.

**Os detalhes dos problemas não são exibidos**

Resumo da _[!UICONTROL Página inicial]_

Quando um usuário no [!DNL Adobe Workfront Classic] seleciona um problema da [!UICONTROL Lista de trabalho], a visualização no painel direito exibe determinados campos sem valores inseridos. No entanto, se você navegar até o problema e visualizar [!UICONTROL Detalhes do problema], esses campos terão valores inseridos.

+++

+++**Atualização de manutenção em 12 de agosto de 2021**

**Não é possível personalizar a exibição ágil no projeto**

_Agile_

Quando um usuário tenta personalizar uma visualização ágil existente em um projeto, a janela é fechada e o usuário não consegue editá-la.

**O nome não é alterado nas novas versões do documento**

_Documentos_

Quando um usuário carrega uma nova versão de um documento, o nome do documento não é atualizado para corresponder ao nome da versão mais recente.

**O ícone predecessor não fica verde quando o predecessor é concluído.**

_Tarefas_

Quando uma tarefa tem uma tarefa predecessora e essa tarefa é concluída, o ícone predecessor na tarefa dependente não fica verde.

Quando um formulário personalizado na nova experiência do [!DNL Adobe Workfront] estiver definido para ser visível em todo o sistema, todos os usuários poderão anexar esse formulário personalizado a um objeto. No entanto, eles só devem ser capazes de exibir o formulário personalizado e não podem anexá-lo a um objeto, a menos que ele tenha sido compartilhado especificamente com eles.

+++

+++**Atualização de manutenção (hotfix) em 6 de agosto de 2021**

**Não é possível selecionar calendários nas [!DNL Outloo]Configurações do calendário**

_Página inicial_

Quando um usuário na nova experiência do [!DNL Workfront] está visualizando o calendário do [!DNL Outlook] na página inicial e abre as configurações, as caixas de seleção para selecionar calendários não aparecem. Se o usuário clicar onde a caixa de seleção estaria, o calendário responderá como se a caixa de seleção estivesse lá.

**Não é possível reautorizar ou verificar a conexão com o [!UICONTROL Webdam]**

_[!DNL Workfront Fusion]_

Usuários do [!DNL Adobe Workfront Fusion] com cenários conectados ao [!UICONTROL Webdam] deve estar cientes de que as conexões do [!UICONTROL Webdam] exigem reautenticação manual a cada 14 dias. No momento, a API [!UICONTROL Webdam] não permite a reautorização automática.

+++

+++**Atualização de manutenção em 5 de agosto de 2021**

**Não é possível interagir com o documento no [!UICONTROL painel Resumo] ou no menu [!UICONTROL Mais]**

_Documentos_

Quando um usuário na nova experiência do [!DNL Workfront] está visualizando um documento e tenta fazer uma seleção no [!UICONTROL Painel Resumo] ou no menu [!UICONTROL Mais], o documento é desmarcado, fazendo com que o [!UICONTROL Painel Resumo] ou o menu [!UICONTROL Mais] fique em branco.

O botão **[!UICONTROL Nova solicitação] não aparece**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] acessa a página [!UICONTROL Solicitações], o botão [!UICONTROL Nova solicitação] não é exibido e não é possível enviar uma solicitação.

**Os usuários sem as permissões de compartilhamento adequadas podem anexar formulários personalizados a objetos**

_Formulários personalizados_

Quando um formulário personalizado na nova experiência do [!DNL Adobe Workfront] estiver definido para ser visível em todo o sistema, todos os usuários poderão anexar esse formulário personalizado a um objeto. No entanto, eles só devem ser capazes de exibir o formulário personalizado e não podem anexá-lo a um objeto, a menos que ele tenha sido compartilhado especificamente com eles.

**Não é possível alterar as configurações de prova ao criar uma nova prova**

_[!DNL Workfront Proof]_

Quando um usuário cria uma nova prova e tenta alterar as configurações, a configuração é revertida para uma configuração anterior.

O **[!UICONTROL Storyboard] não carrega corretamente**

_Agile_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] navega para um [!UICONTROL Storyboard], pode levar até 10 segundos para carregar o quadro. O atraso no carregamento é devido ao sistema carregar todas as placas quando ele deve carregar apenas 50 placas de cada vez.

+++


## Atualizações em julho de 2021

+++**Atualização de manutenção (hotfix) em 29 de julho de 2021**

**Não é possível carregar nova prova ou nova versão de prova**

_[!DNL Workfront Proof]_

Quando um usuário tenta fazer upload de uma nova prova ou de uma nova versão de uma prova no [!DNL Workfront], a nova página de prova ou nova versão fica em branco e o usuário não pode fazer upload da prova ou da versão.

+++

+++**Atualização de manutenção em 29 de julho de 2021**

As páginas **[!UICONTROL Atividade de prova] e [!UICONTROL Configurações do visualizador de prova] estão sempre disponíveis**

_[!DNL Workfront Proof]_

As páginas de configuração [!UICONTROL Atividade de prova] e [!UICONTROL Visualizador de prova] agora estão sempre visíveis, mesmo se o usuário não tiver acesso para atualizar essas páginas.

Anteriormente, quando um usuário com um Perfil de permissão de prova personalizado navegava para um documento, as páginas de configuração [!UICONTROL Atividade de prova] e [!UICONTROL Visualizador de prova] à esquerda nem sempre estavam visíveis.

**Mensagem de erro ao usar a opção [!UICONTROL Porcentagem] para [!UICONTROL Horas alocadas]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário seleciona a opção [!UICONTROL Porcentagem] para [!UICONTROL Horas alocadas] e há trabalhos listados na seção [!UICONTROL Trabalho não atribuído], o seguinte erro é exibido:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar seu trabalho, tente atualizar esta página do navegador.]”

+++

+++**Atualização de manutenção em 22 de julho de 2021**

**Novos nomes de versão de prova sendo cortados**

_[!DNL Workfront Proof]_

Quando um usuário no [!DNL Adobe Workfront Classic] carrega uma nova versão de uma prova que contém um ponto no nome do arquivo, o nome do arquivo é cortado no final.

+++

+++**Atualização de manutenção (hotfix) em 19 de julho de 2021**

**Erro ao tentar navegar para projetos, folhas de horas, tarefas ou programas**

Na nova experiência do [!DNL Adobe Workfront], quando um usuário tenta navegar para projetos, folhas de horas, tarefas ou programas, ele vê a mensagem de erro “[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

+++

+++**Atualização de manutenção em 15 de julho de 2021**

**A prioridade padrão em novas solicitações está incorreta**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] cria uma solicitação, a solicitação não respeita a prioridade padrão definida em [!UICONTROL Preferências do projeto] e não é possível ajustar a prioridade antes de enviar a solicitação.

**[!UICONTROL Acessar o link de] prova não direciona para o comentário**

_Notificações de email_

Quando um usuário recebe uma notificação por email para um comentário de prova e clica em [!UICONTROL Ir para prova], ele é direcionado ao comentário errado na prova ou não é direcionado a nenhum comentário.

**Valores de campo Rich Text não transferidos após converter um problema em uma tarefa**

_Formulários personalizados_

Quando um usuário converte um problema em uma tarefa e o problema tem um formulário personalizado anexado com um valor inserido em um campo de texto com formatação Rich Text, o valor no campo de texto não é transferido após a conversão.

**Os valores de campo personalizado são alterados após a seleção**

_[!DNL Workfront Proof]_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] estiver criando uma nova prova e inserir um valor em alguns campos personalizados em uma prova, o valor de alguns campos anteriores será revertido para os valores padrão em vez do valor inserido pelo usuário.

**[!UICONTROL Atribuir à] digitação antecipada não funciona**

_[!UICONTROL Página inicial]_

Quando um usuário no [!DNL Adobe Workfront Classic] cria um projeto, tarefa ou solicitação na área [!UICONTROL Página inicial], o campo de digitação antecipada [!UICONTROL Atribuir a] não preenche nomes de usuários.

**Arredondamento de horas incorretos**

_Folhas de horas_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] acessa [!UICONTROL Folhas de horas] > [!UICONTROL Todas as folhas de horas], ele vê que os números totais de horas de algumas folhas de horas são arredondados para uma casa decimal em vez de em incrementos de 0,25, mas o total de horas é exibido corretamente na folha de horas individual. Por exemplo, na área Todas as folhas de horas, uma folha de horas mostra 44,8 horas totais, mas ao abri-la, mostra 44,75 horas totais.

**Não é possível delegar aprovações**

_[!UICONTROL Página inicial]_

Quando um usuário no [!DNL Adobe Workfront Classic] clica em [!UICONTROL Delegar minhas aprovações] na área [!UICONTROL Página inicial] e começa a digitar o nome do usuário ao qual está tentando delegar, nenhum resultado é exibido na lista de [!UICONTROL digitação antecipada] e não é possível selecionar um usuário.

A visualização **[!UICONTROL Gráfico de Gantt] não está disponível para relatórios de Tarefa**

_Relatórios_

OBSERVAÇÃO: isso também afeta os relatórios do projeto.

Quando um usuário na nova experiência do [!DNL Adobe Workfront] abre um relatório de Tarefa, a opção para selecionar uma visualização de [!UICONTROL Gráfico de Gantt] não aparece na barra de ferramentas do relatório. Se a visualização de [!UICONTROL Gráfico de Gantt] for selecionada para exibição por padrão no relatório, será exibido um formato de lista.

**Clicar em [!UICONTROL Veja Mais] no relatório não carrega nada**

_Painéis_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] está visualizando um relatório em um painel e clica no botão [!UICONTROL Veja Mais], nada acontece e não é possível exibir todos os itens no relatório.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 1 de julho de 2021**

**A cópia de módulos não funciona**

_[!DNL Adobe Workfront Fusion]_

Quando um usuário seleciona vários módulos e tenta copiá-los e colá-los, os módulos não são colados.

+++

+++**Atualização de manutenção em 1 de julho de 2021**

**O conjunto de cores para cartões não é respeitado**

_Kanban_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] define cores específicas do cartão nas configurações do grupo, essas cores não são refletidas nos cartões Kanban.

**Não é possível colar texto no campo de mensagem personalizado**

_[!DNL Workfront Proof]_

Quando um usuário cria uma nova prova no [!UICONTROL Visualizador de provas da Web] e tenta colar o texto no campo [!UICONTROL Mensagem] na seção [!UICONTROL Notificação por email], não é possível colar o texto. Parece que isso só ocorre quando o texto tem formatação de parágrafo e há uma quebra de parágrafo.

**As solicitações são enviadas com campos obrigatórios em branco**

_Solicitações_

Quando um usuário faz uma solicitação e a envia, as informações nos campos obrigatórios não são enviadas com a solicitação.

O botão **[!UICONTROL Nova solicitação] não aparece**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] acessa a página [!UICONTROL Solicitações], o botão [!UICONTROL Nova solicitação] não é exibido e não é possível enviar uma solicitação.

**Erro ao expandir um formulário personalizado**

_Projetos_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] tenta expandir um formulário personalizado anexado a um projeto, não é possível abrir o formulário personalizado e é exibida a mensagem de erro “[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.]“Atualizar a página não resolve o problema.

A marca do **[!DNL Adobe Workfront]agora aparece nos emails do centro de anúncios**

Emails

Como a marca do [!DNL Adobe Workfront] é distribuída pelo aplicativo, as seguintes atualizações foram feitas aos emails do centro de anúncios:

* O leão [!DNL Adobe Workfront] foi adicionado à área de conteúdo principal.
* O logotipo do [!DNL Adobe Workfront] foi adicionado ao rodapé.

No futuro, essa marca será mostrada em outros tipos de emails do Workfront.

+++


## Atualizações em junho de 2021

+++**Atualização de manutenção em 24 de junho de 2021**

**Não é possível editar uma equipe**

_Agile_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] clica em [!UICONTROL Editar] para abrir a Página de equipe do [!DNL Edit] de uma Equipe Ágil, a página é carregada inicialmente, em seguida, as configurações desaparecem e ela fica em branco.

**Dados removidos da solicitação enviada**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] preenche uma solicitação, os valores inseridos em alguns campos personalizados não aparecem, às vezes até mesmo em campos obrigatórios.

**As colunas não estão sendo exibidas**

_Kanban_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] adiciona uma coluna [!UICONTROL Campos adicionais] personalizada a um Quadro Kanban, todos os cabeçalhos de coluna param de ser exibidos no quadro.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 23 de junho de 2021**

**Remoção de links corrompidos nos emails de notificação**

_[!DNL Adobe Workfront Fusion]_

Removemos o link para as configurações de notificação de emails de notificação do [!DNL Adobe Workfront Fusion].
Para obter informações sobre como alterar configurações de notificação, consulte organizações e equipes do [!DNL Adobe Workfront Fusion].

+++

+++**Atualização de manutenção em 17 de junho de 2021**

A visualização de **[!UICONTROL Gráfico de Gantt] não está disponível para o Relatório de tarefa**

_Relatórios_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] abre um relatório de Tarefa, a opção para selecionar uma visualização de [!UICONTROL Gráfico de Gantt] não aparece na barra de ferramentas do relatório. Se a visualização de [!UICONTROL Gráfico de Gantt] for selecionada para exibição por padrão no relatório, será exibido um formato de lista.

**O erro de limite de caracteres não ocorre nos envios de solicitação**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] tenta enviar uma solicitação e ela excede o limite de caracteres de um campo, não é possível enviar a solicitação e nenhuma mensagem de erro é exibida. No [!DNL Adobe Workfront Classic], o usuário vê o aviso “[!UICONTROL [acima do número] de caracteres” e quando tentar enviar a solicitação, verá a mensagem de erro “Verifique o seguinte: insira no máximo 2000 caracteres (você inseriu [número] de caracteres).]”

+++

+++**Atualização de manutenção em 10 de junho de 2021**

**Tarefas de modelo reordenadas não são movidas**

_Modelos_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] arrasta uma tarefa de modelo para um novo local em uma lista, o número de atualizações da tarefa de modelo não é reordenado.

**Tarefas secundárias não são selecionadas com tarefas principais**

_Modelos_

Quando um usuário seleciona uma tarefa principal em um projeto criado de um modelo, as tarefas secundárias não são selecionadas automaticamente.

**Marcos de edição em linha em uma lista de tarefas exibem todos os marcos**

_Projetos_

Quando um projeto tem um caminho de marcos adicionado a ele e um usuário na nova experiência do [!DNL Adobe Workfront] edita em linha a coluna [!UICONTROL Marco: Nome] nessa lista de tarefas, todos os caminhos de marcos são exibidos no menu suspenso, em vez de apenas os caminhos de marcos anexados a esse projeto.

+++

+++**Atualização de manutenção em 3 de junho de 2021**

**O prompt faz a página tremer**

_Relatórios_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] executa um relatório com um prompt, as colunas no relatório movem-se rapidamente da esquerda para a direita.

**Algumas frases na página [!UICONTROL Nova prova] não são traduzidas corretamente**

_[!DNL Workfront Proof]_

Quando um usuário navega até a página [!UICONTROL Criação de nova prova] no [!DNL Workfront Proof] e o conteúdo está sendo traduzido para um idioma diferente do inglês, algumas frases ainda são exibidas em inglês.

**Rótulos desativados e excluídos adicionados aos usuários [!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Os rótulos do usuário [!UICONTROL Desativado] e [!UICONTROL Excluído] foram adicionados às seguintes áreas no [!DNL Workfront] Proof:

* Página [!UICONTROL Detalhes da prova]
* [!UICONTROL Visualizações de revisão]
* [!UICONTROL Visualizador de revisão]
* [!UICONTROL Fluxos de trabalho de revisão]
* Página [!UICONTROL Imprimir comentários]
* Página [!UICONTROL Usuário]

+++


## Atualizações em maio de 2021

+++**Atualização de manutenção em 27 de maio de 2021**

O calendário **[!UICONTROL Data de confirmação] é exibido para atualizações**

_Tarefas_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] estiver informando uma atualização em uma tarefa, o calendário [!UICONTROL Data de confirmação] é exibido sem que o usuário selecione o campo [!UICONTROL Data de confirmação].

No menu **[!UICONTROL Mais], não aparecem filtros, visualizações e agrupamentos**

_Listas_

Quando um usuário na nova experiência do [!DNL Adobe Workfront] visualiza os filtros, as exibições ou os agrupamentos de uma lista, o ícone do menu [!UICONTROL Mais] não aparece, o que impede o compartilhamento ou, se tiverem acesso, a remoção de filtros, exibições ou agrupamentos.

**Copiar e colar o [!UICONTROL Número de referência] de um projeto adiciona “[!UICONTROL Esse]”**

_Projetos_

Quando um usuário na nova experiência do [!DNL Workfront] navega para um projeto, copia o [!UICONTROL Número de referência] na área [!UICONTROL Visão geral] e o cola, a palavra “[!UICONTROL Esse]” é adicionada ao final do número.

Emails de **[!UICONTROL Resumo diário] são enviados mesmo quando desativados**

_Notificações de email_

Alguns usuários estão recebendo notificações por email de [!UICONTROL Resumo diário] quando elas não estão ativadas nas configurações do usuário.

**Erro O objeto não existe mais**

_Objetos_

Quando um usuário na nova experiência do [!DNL Workfront] tenta abrir determinados objetos, é exibida a mensagem de erro “[!UICONTROL O (objeto) não existe mais: você pode ter digitado incorretamente o endereço da Web. Verifique novamente e tente inserir o endereço novamente.]” O link do objeto ainda aparece em listas, recentes, favoritos, resultados de pesquisa etc., mas não é possível acessá-lo e ele não aparece na Lixeira com objetos excluídos.



+++

+++**Atualização de manutenção em 20 de maio de 2021**

**Opções de prova ausentes**

_Provas_

Quando um usuário carrega outra versão de uma prova no [!DNL Workfront], os links [!UICONTROL Abrir prova] e [!UICONTROL Fluxo de trabalho de prova] não são exibidos, fazendo parecer que é um documento em vez de uma prova. Quando esses links estiverem ausentes, o rótulo [!UICONTROL Pendente] também é exibido e outros usuários não podem gerar a prova enquanto ela estiver nesse status [!UICONTROL Pendente].

**Usuários que não recebem entregas programadas de relatórios**

_Relatórios_

Quando alguns relatórios são agendados para entrega, os usuários às vezes não os recebem.

**Não é possível remover o acesso ao modelo de layout**

_Painéis_

Quando um usuário abre opções de [!UICONTROL Compartilhamento] para um painel remover o acesso de um modelo de layout, o ícone [!UICONTROL Excluir] não é exibido ao lado do Modelo de layout e não é possível remover o acesso.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 17 de maio de 2021**

**O Painel da organização agora exibe corretamente o número de cenários ativos**

_[!DNL Workfront Fusion]_

O painel [!UICONTROL Organização] anteriormente mostrava um campo em branco em vez do número de cenários que estão sendo utilizados.

**A navegação do armazenamento de dados agora mostra rótulos de coluna**

_[!DNL Workfront Fusion]_

As estruturas de dados que utilizavam rótulos de coluna anteriormente exibiam o nome da coluna na visualização [!UICONTROL navegação do armazenamento de dados].  Agora, o rótulo da coluna é exibido.  Se nenhum rótulo for identificado para a coluna, o nome da coluna será exibido.

**O erro de inicialização de cenário não afeta mais os dados do webhook**

_[!DNL Workfront Fusion]_

Anteriormente, um cenário iniciado por um webhook (incluindo aqueles que estão usando eventos em tempo real para acionar) que encontrasse um erro durante a inicialização do cenário resultaria potencialmente na perda de acesso a esses dados do webhook.  Agora, se ocorrer um erro durante a inicialização do cenário (como não verificar uma conexão), os dados do webhook serão mantidos na fila do webhook e a execução será repetida automaticamente.  Após três tentativas malsucedidas, o cenário é desativado e as informações ainda permanecerão na fila.

**Os registros em filas de webhook agora são processados em lotes menores**

_[!DNL Workfront Fusion]_

Anteriormente, se um usuário ativava um cenário inativo que tinha uma fila de webhook associada de muitos registros, o [!DNL Workfront Fusion] tentaria processar toda a fila em uma única execução (embora com vários ciclos).  Dependendo da quantidade de registros processados, às vezes a execução única pode exceder a quantidade máxima de tempo de execução (40 minutos).  Agora, quando você ativa um cenário inativo que tem uma fila de webhook associada de registros, o Workfront Fusion processará até o número máximo de registros identificados em uma única execução (geralmente 2 registros por execução).

**Agora, os armazenamentos de dados exibem corretamente os valores de “0”**

_[!DNL Workfront Fusion]_

Anteriormente, os valores do armazenamento de dados de 0 eram exibidos como vazios. &lt;...>

+++

+++**Atualização de manutenção em 13 de maio de 2021**

**O calendário suspenso é exibido atrás do cabeçalho [!UICONTROL Trabalho não atribuído]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário navega até o [!UICONTROL Balanceador de carga de trabalho] no [!DNL Workfront Classic], a parte superior do seletor de datas está oculta atrás do cabeçalho [!UICONTROL Trabalho não atribuído], o que impede que o usuário acesse meses diferentes.

**Não é possível colar texto no campo de mensagem personalizado**

_[!DNL Workfront Proof]_

Observação: esse problema parece afetar apenas o navegador da Web do [!DNL Google Chrome] no momento.

Quando um usuário cria uma nova prova no [!DNL Workfront Proof] e tenta colar texto de um email no campo [!UICONTROL Mensagem] na seção [!UICONTROL Notificação por email], não é possível colar o texto.

**Campos não permitidos são exibidos no construtor**

_Formulários personalizados_

Quando um usuário está criando um Formulário personalizado e tenta criar um campo calculado usando um campo dinâmico, como [!UICONTROL Número de riscos em aberto], a caixa de cálculo é destacada em vermelho e não permite salvar as alterações. Campos dinâmicos não devem ser exibidos no seletor para campos calculados.

**A Pré-visualização de tarefas na [!UICONTROL Lista de trabalho] não carrega**

_Página inicial_

Quando um usuário na nova experiência do [!DNL Workfront] é atribuído a um modelo de layout que inclui campos personalizados na [!UICONTROL Página inicial], a página não responde e não carrega tarefas da [!UICONTROL Lista de trabalho] se os usuários as selecionarem.

**Objetos na [!UICONTROL Lista de trabalho] não carregam na [!UICONTROL Página inicial]**

_[!UICONTROL Página inicial]_

Quando um usuário clica em um objeto na [!UICONTROL Lista de trabalho da página inicial], o cabeçalho do objeto é exibido no painel direito, mas os detalhes do objeto não são exibidos. O usuário acaba vendo a mensagem “[!UICONTROL Páginas sem resposta.]”

**Problemas de campo de rich text no[!DNL Microsoft Outlook]**

_Integrações do Workfront_

Quando um usuário está atualizando um campo de rich text com a integração do [!DNL Workfront for Outlook], não é possível:

* Apagar
* Copiar texto
* Colar texto
* Enviar uma solicitação quando todos os campos forem preenchidos

+++

+++**Atualização de manutenção em 6 de maio de 2021**

O campo **[!UICONTROL Moeda] não funciona conforme esperado**

_Listas_

Quando um usuário tenta editar em linha o campo Moeda, não é possível salvar as alterações devido aos seguintes problemas:

* Listas de tarefas e ocorrências não permitem a entrada de símbolos de moeda
* As listas não permitem a entrada de abreviações de moeda ao usar um idioma diferente de inglês
* Listas de subtarefas e problemas permitem somente a abreviação da moeda USD, independentemente da moeda definida para o projeto

**Nome não atualizado para corresponder ao novo nome de prova**

_Documentos_

Quando um usuário cria uma nova versão de uma prova e atualiza o nome da prova, o objeto do documento no [!DNL Workfront] retém o nome original em vez de corresponder ao novo nome de prova.

Os botões **[!UICONTROL Business Case] não funcionam quando formulários personalizados são anexados**

_Projetos_

Quando um projeto na nova experiência do [!DNL Workfront] é criado a partir de um modelo de projeto e há um formulário personalizado anexado, os usuários não podem enviar, rejeitar ou aprovar um business case.

**Provas arquivadas são exibidas em listas e relatórios**

_Provas_

Quando um usuário visualiza sua lista de trabalho na [!UICONTROL Página inicial] ou em [!UICONTROL Meu trabalho], as provas que já foram arquivadas são exibidas na lista. Provas arquivadas também aparecem em relatórios e painéis.

**O projeto criado a partir do modelo tem configurações de acesso incorretas**

_Projetos_

Quando um usuário cria um projeto a partir de um modelo, as configurações de acesso do modelo não são transferidas para o novo projeto criado.

**Objetos na [!UICONTROL Lista de trabalho] não carregam na [!UICONTROL Página inicial]**

_[!UICONTROL Página inicial]_

Quando um usuário clica em um objeto na [!UICONTROL Lista de trabalho da página inicial], o cabeçalho do objeto é exibido no painel direito, mas os detalhes do objeto não são exibidos. O usuário acaba vendo a mensagem “[!UICONTROL Páginas sem resposta.]”

+++


## Atualizações em abril de 2021

+++**Atualização de manutenção em 29 de abril de 2021**

A integração do **[!DNL SharePoint] é autenticada usando credenciais de uma integração separada**

_Integrações do Workfront_

Quando um usuário tiver mais de uma integração do [!DNL SharePoint], uma autenticação do [!DNL SharePoint] tenta autenticar usando as credenciais de outra integração do [!DNL SharePoint].

**Não é possível carregar ou exportar arquivos de produtos do [!DNL Adobe]**

_Integrações do Workfront_

Quando um usuário tenta fazer upload ou exportar arquivos usando a integração do [!DNL Workfront for Adobe Creative Cloud], é exibida a mensagem de erro “[!UICONTROL Não é possível ler a propriedade ‘estágios’ de indefinido]” e não é possível carregar ou exportar os arquivos.

**Os arquivos não estão visíveis no [!DNL Internet Explorer]**

_Documentos_

Quando um usuário com um navegador do [!DNL Internet Explorer] navega até a área [!UICONTROL Documentos] de um objeto, a tela [!UICONTROL Documentos] está em branco e não carrega os arquivos. Para alguns usuários, a tela carrega alguns arquivos, mas o número de arquivos exibidos não corresponde ao número exibido ao lado da seção [!UICONTROL Documentos].

+++

+++**Atualização de manutenção em 22 de abril de 2021**

**Tarefas adicionadas na ordem errada**

_Modelos_

Quando um usuário adiciona uma tarefa a um modelo, a tarefa não recebe o número da tarefa que espera e a tarefa é adicionada no lugar errado.

**Agora, as provas são combinadas em um único email**

_Provas_

O [!DNL Workfront] agora envia um email para provas combinadas, em vez de enviar um email para cada arquivo incluído.
+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 15 de abril de 2021**

Erro **“[!UICONTROL Cenário rejeitado]” ao executar um cenário**

_[!DNL Workfront Fusion]_

Quando um usuário tenta executar um cenário, ele não é executado e o usuário recebe a mensagem “[!UICONTROL Cenário rejeitado.]”

+++

+++**Atualização de manutenção em 15 de abril de 2021**

O **[!UICONTROL Balanceador de carga de trabalho] exibe horas planejadas incorretas**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário visualiza as horas planejadas de uma tarefa no [!UICONTROL Balanceador de carga de trabalho], o valor das horas planejadas não corresponde às horas planejadas atribuídas à tarefa.

**A barra de navegação superior não está visível no [!DNL Workfront Proof]**

_[!DNL Workfront Proof]_

Quando um usuário navega para qualquer página [!DNL Workfront Proof] diferente da página Painel, a barra de navegação superior desaparece. O usuário não pode acessar a funcionalidade na barra de navegação, como as configurações da conta ou o perfil.

**Aprimoramento de formulários personalizados**

_Formulários personalizados_

Para obter uma melhor experiência ao preencher um formulário personalizado, melhoramos a forma como os rótulos de campos personalizados longos são exibidos. Quando há espaço horizontal suficiente para exibi-los na totalidade, esses rótulos não ficam mais truncados.

+++

+++**Atualização de manutenção em 8 de abril de 2021**

**Não é possível criar provas a integração do [!DNL Adobe Creative Cloud]**

_Integrações do Workfront_

Quando um usuário tenta criar uma prova diretamente do [!DNL Adobe Creative Cloud], a prova não é gerada.

+++

+++**Atualização de manutenção em 1 de abril de 2021**

**Problemas ao visualizar o painel de resumo no [!DNL Chrome]**

_[!UICONTROL Resumo]_

Quando um usuário abre o painel [!UICONTROL Resumo] ao usar o navegador do [!DNL Chrome], a interface do usuário do painel de resumo não se comporta conforme esperado. O usuário não consegue rolar a tela, os ícones podem desaparecer e o conteúdo pode se sobrepor a outro conteúdo.

A área **[!UICONTROL Equipes] em [!UICONTROL Configuração] não exibe todas as equipes**

_[!UICONTROL Configuração]_

Quando um administrador acessa a área [!UICONTROL Equipes] da [!UICONTROL Configuração], ele visualiza somente as equipes que criou. As equipes criadas por outros administradores não estão visíveis.

**Não é possível adicionar atualizações ao projeto no status [!UICONTROL Aprovação pendente]**

_Projetos_

Se um usuário tentar adicionar uma atualização a um projeto no status [!UICONTROL Aprovação pendente] e não for o usuário atribuído para aprovar o projeto, a atualização não é adicionada e o seguinte aviso é exibido:

Um projeto com status “[!DNL Pending Approval]”não pode ser editado. Você pode modificar o projeto alterando o status.

+++


## Atualizações em março de 2021

+++**Atualização de manutenção em 26 de março de 2021**

**Os botões em um business case são exibidos incorretamente**

_Projetos_

Quando um usuário estiver visualizando um business case e a janela estiver no modo de tela cheia, os botões [!UICONTROL Salvar] e [!UICONTROL Cancelar] são exibidos perto do meio da tela, sobrepondo os elementos do business case.

**Não é possível alterar a classificação de um relatório**

_Relatórios_

Quando um usuário tenta alterar a classificação de um relatório na nova experiência do [!DNL Workfront], a classificação não muda da classificação selecionada durante a criação do relatório.

**Compartilhamento desativado em novas provas**

_[!DNL Workfront Proof]_

Quando um usuário tiver a opção [!UICONTROL Compartilhamento público] habilitada nas configurações de prova padrão, a prova é criada com o compartilhamento desabilitado. Outros usuários não podem ver o botão [!UICONTROL Compartilhar] ou compartilhar a prova.

Erro **“[!UICONTROL Falha ao gerar prova]” ao criar a prova**

_[!DNL Workfront Proof]_

Quando um usuário tenta criar uma prova, ela não é criada e o usuário vê a seguinte mensagem de erro:

“[!UICONTROL Falha ao gerar a prova -- erro interno]”

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 25 de março de 2021**

**Remoção do campo de referência ou coleção redundante do painel de mapeamento**

_[!DNL Workfront Fusion]2.0_

Quando um usuário usa um termo da API do [!DNL Workfront] para selecionar uma coleção ou um campo de referência que será incluído na saída de um módulo do [!DNL Workfront], a saída desse módulo mostra esse campo com dois pontos (como [!UICONTROL proprietário:nome]) e também nos atributos (o nome é um campo sob o proprietário). O campo rotulado com dois pontos não contém dados e fornece dados incorretos se mapeados para um módulo posteriormente no cenário.

+++

+++**[!DNL Workfront Fusion]Atualização de manutenção em 18 de março de 2021**

**As configurações do modelo de projeto agora se aplicam aos projetos criados por meio do [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront Fusion]2.0_

Ao criar um projeto a partir de um modelo usando o [!DNL Workfront Fusion] 2.0, as configurações do modelo são aplicadas ao novo projeto. Esse comportamento é o mesmo ao criar um projeto a partir de um modelo no aplicativo [!DNL Workfront].

+++

+++**Atualização de manutenção em 18 de março de 2021**

**As configurações do modelo de projeto agora se aplicam aos projetos criados por meio da API**

_[!DNL Workfront]API_

Ao criar um projeto a partir de um modelo usando a API do [!DNL Workfront], as configurações do modelo são aplicadas ao novo projeto. Esse comportamento é o mesmo ao criar um projeto a partir de um modelo no aplicativo [!DNL Workfront].

+++

+++**Atualização de manutenção (hotfix) em 15 de março de 2021**

**O componente compartilhado não está funcionando como esperado**

_[!DNL Workfront Proof]_

Se as contas independentes do [!DNL Workfront Proof] são movidas para um componente compartilhado, a seguinte funcionalidade pode ocorrer quando um usuário adiciona uma nova versão de uma prova ou documento:

* O usuário não pode excluir o usuário [!UICONTROL Studio Proof].
* A mensagem padrão não é exibida na nova versão.

**Compartilhamento de link público não ativado na nova versão de uma prova**

_Documentos_

Quando um usuário ativa o compartilhamento de link público em uma prova e, em seguida, carrega uma nova versão da prova, o compartilhamento de link público não é ativado automaticamente na nova versão da prova.

Os botões **[!UICONTROL Aprovar], [!UICONTROL Alterações], [!UICONTROL Rejeitar] não aparecem na prova**

_[!DNL Workfront Proof]_

Quando um usuário visualiza uma prova no Visualizador de prova, os botões [!UICONTROL Aprovar], [!UICONTROL Alterações] e [!UICONTROL Rejeitar] não aparecem na parte superior da tela.

**Não é possível alterar a classificação de um relatório**

_Relatórios_

Quando um usuário tenta alterar a classificação de um relatório na nova experiência do [!DNL Workfront], a classificação não muda da classificação selecionada durante a criação do relatório.

**A mensagem personalizada na prova não é transferida para a nova versão**

_[!DNL Workfront Proof]_

Quando um usuário anexa uma mensagem personalizada a uma prova e, em seguida, carrega uma nova versão dessa prova, a mensagem personalizada não é exibida na nova prova.

**A lista de usuários não é exibida**

_Listas_

Quando um usuário tenta visualizar uma lista de usuários, e a exibição inclui a coluna “[!UICONTROL Ícones de status]”, a lista não é exibida.

A opção **“[!UICONTROL Notificar recipients sobre esta prova]” fica desabilitada independentemente das configurações do fluxo de trabalho**

_[!DNL Workfront Proof]_

Quando um usuário cria uma nova prova e não ativa manualmente a opção “[!UICONTROL Notificar recipients sobre esta prova]”, o recipient pretendido não é notificado. Isso é verdade mesmo se a opção estiver habilitada nas configurações do fluxo de trabalho.

**Não é possível alterar o intervalo de tempo**

_[!UICONTROL Analítica aprimorada]_

Quando um usuário visualiza a opção [!UICONTROL Analítica aprimorada] e clica no calendário para ajustar o intervalo de datas, as datas não serão alteradas.

**Não é possível baixar o documento compartilhado publicamente**

_Documentos_

Quando um usuário clica em um link compartilhado para baixar um documento, ele não é baixado e o usuário vê um erro do navegador informando que a página não existe.

+++

+++**Atualização de manutenção em 11 de março de 2021**

**A seção de formulário personalizado não exporta para não administradores**

_Formulários personalizados_

Se um formulário personalizado anexado a um objeto tiver uma quebra de seção que exija algo além do acesso “[!UICONTROL Visualização]” necessário para visualizar o conteúdo da seção, o conteúdo da seção não pode ser exportado por ninguém além de um Administrador.

**O documento baixado tem nome incorreto**

_[!DNL Workfront Proof]_

Quando um usuário baixa um documento do [!UICONTROL Visualizador de prova], o do documento tem o nome de uma versão anterior do documento, não a versão que foi baixada.

+++

+++**Atualização de manutenção em 4 de março de 2021**

**Erro ao acessar modelo de layout**

_Modelos de layout_

Quando um usuário que se inscreveu na nova experiência do [!DNL Workfront] muda para a experiência do [!DNL Classic] e tenta acessar um modelo de layout do [!DNL Classic], é exibido o erro “[!UICONTROL Essa página não existe.]”

**Não é possível editar filtros no [!UICONTROL Balanceador de carga de trabalho]**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário tenta editar um filtro no [!UICONTROL Balanceador de carga de trabalho], o construtor de filtros não abre.

O link **“[!UICONTROL Ver todas as notificações]” na notificação por email redireciona para a página incorreta**

_Notificações de email_

Quando um usuário clica no link “[!UICONTROL Ver todas as notificações]” em uma notificação por email, ele é redirecionado para uma página com a seguinte mensagem:

“[!UICONTROL O usuário não existe mais. Talvez tenha digitado o endereço incorreto. Verifique e digite o endereço novamente.]”

**O usuário não é direcionado ao comentário de prova em que está marcado**

_Notificações de email_

Quando um usuário estiver marcado em um comentário de prova e clicar no link [!UICONTROL Ir para prova] em uma notificação por email, ele é direcionado à prova, mas não ao comentário específico. Se o usuário estiver no [!DNL Workfront Classic], será direcionado para a página [!UICONTROL Detalhes do documento] e não para o comentário na prova.

**Usuários adicionados ao estágio do [!DNL Workfront] recebem notificações por email**

_[!DNL Workfront Proof]_

Quando um usuário que não está no fluxo de trabalho abre uma prova do [!DNL Workfront], o sistema cria automaticamente um estágio, adiciona esse usuário à prova e envia uma notificação [!UICONTROL Nova prova] por email.

**O painel de resumo do documento escurece, tornando as ações indisponíveis**

_Documentos_

Quando um usuário está em uma página de documento e passa o mouse sobre o painel de resumo do documento, o painel fica escuro e pode mostrar outros botões. O usuário não consegue clicar nas ações no painel de resumo.

**Atualizar alterações de desempenho do fluxo**

_Atualizar fluxo_

Reduzimos o número de atualizações de usuários exibidas na guia [!UICONTROL Atualizações] de 50 para 25 por vez para melhorar o desempenho.

+++

+++**Atualização de manutenção (hotfix) em 1 de março de 2021**

**Novos emails de prova não estão sendo enviados**

_[!DNL Workfront Proof]_

OBSERVAÇÃO: esse problema foi corrigido na nova experiência do [!DNL Workfront] em 26 de fevereiro de 2021.
Problema corrigido na experiência do [!DNL Classic] em 1 de março de 2021.

Quando um usuário cria uma nova prova e ativa a opção [!UICONTROL Notificar recipients sobre esta prova], nenhum email é enviado para notificar o recipient.

+++


## Atualizações em fevereiro de 2021

+++**Atualização de manutenção em 25 de fevereiro de 2021**

A ferramenta **[!UICONTROL Cronograma] não será carregada em nenhuma área**

_Gerenciamento de recursos_

Quando um usuário com um apóstrofe em seu nome de usuário tenta acessar a ferramenta [!UICONTROL Cronograma] no [!DNL Workfront Classic], a página fica em branco e a ferramenta não é carregada.

**O nome não é alterado em novas versões de prova**

_Documentos_

Quando um usuário na nova experiência do [!DNL Workfront] faz upload de uma nova versão de um documento com um nome diferente, o nome não é atualizado para corresponder ao nome da versão mais recente.

Erro de **[!UICONTROL Compartilhamento de documentos] ao excluir projetos**

_Projetos_

Quando um usuário administrador do sistema tem acesso a um projeto que foi copiado e tenta excluí-lo ou excluir um documento do projeto, ele não pode excluir o objeto e vê o erro “[!UICONTROL Compartilhamento de documentos com valores de chave primária não encontrado.]”

**O relatório do usuário não está aplicando todos os filtros**

_Relatórios_

Quando um usuário na nova experiência do [!DNL Workfront] cria um relatório de Usuário com uma regra de filtro que inclui o campo [!UICONTROL ID principal], nenhuma outra regra de filtro no relatório é aplicada.

**Campos calculados não são recalculados após edições**

_Formulários personalizados_

Quando um usuário na nova experiência do [!DNL Workfront] edita e salva um Formulário personalizado que contém campos calculados, esses campos não são atualizados.

**Documentos são excluídos quando o formulário personalizado é excluído**

_Formulários personalizados_

Quando um usuário na nova experiência do [!DNL Workfront] exclui um formulário personalizado anexado a documentos, esses documentos também são excluídos.

+++

+++**Atualização de manutenção em 18 de fevereiro de 2021**

**Remoção desnecessária da caixa de seleção da área [!UICONTROL Solicitações]**

_Solicitações_

Removemos a caixa de seleção à esquerda dos nomes das solicitações na lista Enviado da área [!UICONTROL Solicitações]. Essa caixa de seleção não estava conectada a nenhuma funcionalidade, portanto, a removemos para evitar que a experiência ficasse confusa.

**Não é possível acessar documentos por meio de links**

_Documentos_

Quando um usuário na nova experiência do [!DNL Workfront] clica em alguns links de documento, não é possível acessar o documento e é exibida a mensagem de erro “[!UICONTROL O documento não existe mais: você pode ter digitado incorretamente o endereço da Web. Verifique novamente e tente inserir o endereço novamente.]” Esse mesmo erro ocorre com o link [!UICONTROL Exibir detalhes] nas notificações por email de prova.

+++

+++**Atualização de manutenção do Workfront Fusion em 16 de fevereiro de 2021**

O **[!DNL Workfront Fusion] 2.0 mostra fusos horários imprecisos**

_Cenários_

Esta atualização corrigiu um problema em que o [!DNL Fusion] 2.0 exibia fusos horários do usuário de maneira imprecisa. Agora, os usuários podem ver o fuso horário exibido em campos de entrada para datas.

+++

+++**Atualização de manutenção em 11 de fevereiro de 2021**

**As provas não estão sendo carregadas na pasta selecionada**

_[!DNL Workfront Proof]_

Quando um usuário abre uma pasta e adiciona uma nova prova, a prova é carregada na área [!UICONTROL Documentos] do objeto e não dentro da pasta.

**Muitas páginas fixadas fazem com que a Navegação superior desapareça**

_Navegação_

Quando um usuário tem mais de 60 páginas fixas, a Navegação superior para de ser exibida, impedindo que o usuário acesse a [!UICONTROL Pesquisa], o [!UICONTROL Menu principal], as [!UICONTROL Notificações] e muito mais.

**O usuário não consegue digitar texto em campo Rich Text**

_Listas_

Quando um usuário tenta editar um campo Rich Text em linha, ele só consegue digitar um único caractere.

+++

+++**Atualização de manutenção em 4 de fevereiro de 2021**

**Relatórios exportados exibem a marca do [!DNL Workfront Classic]**

_Relatórios_

Quando um usuário na nova experiência do Workfront exporta um relatório, o logotipo exibido no relatório exportado corresponde às configurações do [!DNL Workfront Classic] encontradas em [!UICONTROL Configuração] > [!UICONTROL Sistema] > [!UICONTROL Marca].

+++


## Atualizações em janeiro de 2021

+++**Atualização de manutenção em 28 de janeiro de 2021**

**Os comentários não exibem “[!UICONTROL em nome de]”**

_Atualizações_

Quando um administrador do [!DNL Workfront] faz logon como outro usuário e responde a um comentário na área [!UICONTROL Atualizações] de um objeto, o texto “[!UICONTROL em nome de]” não é exibido antes do nome do usuário.

**Não é possível anexar um documento**

_Solicitações_

Quando um usuário na nova experiência do [!DNL Workfront] tenta adicionar um documento a uma nova solicitação de um provedor de documentos externo, a lista [!UICONTROL Documentos] não carrega, o que impede que o usuário selecione o documento e conclua a solicitação.

**A largura da tela se expande à direita, causando problemas de navegação**

_[!UICONTROL Calendário da página inicial]_

Quando um usuário na nova experiência do [!DNL Workfront] abre o [!UICONTROL Calendário da página inicial] e tem itens com vencimento em algumas semanas, a tela se expande para a direita, impedindo-o de visualizar a semana inteira de uma só vez. Se o usuário selecionar um item para abrir o painel [!UICONTROL Detalhes] nesse estado e quiser visualizar os detalhes de outro item, é preciso rolar a tela para a esquerda, o que fecha o painel [!UICONTROL Detalhes].

**O rótulo do processo de aprovação de uso único foi corrigido**

_Projetos_

Ao usar um processo de aprovação de uso único para um projeto na nova experiência do [!DNL Workfront], agora ele é exibido como “[!UICONTROL Processo de aprovação de uso único]” em vez de “&lt;Custom>” na caixa [!UICONTROL Editar projeto]. Isso ainda não está disponível para tarefas e problemas.

**Aparência e comportamento aprimorados para formulários personalizados**

_Projetos_

Melhoramos a aparência do trabalho com formulários personalizados na nova experiência do [!DNL Workfront] para projetos.

**A funcionalidade da API para moeda do projeto agora corresponde à funcionalidade no aplicativo**

_Projetos_

Não é possível alterar a moeda de um projeto quando já há informações financeiras sobre o projeto. Com a atualização de manutenção mais recente, a funcionalidade da API para esse caso agora corresponde à experiência na interface do [!DNL Workfront].

**Não gera automaticamente a semana seguinte**

_Folhas de horas_

Quando um usuário acessa a área [!UICONTROL Folhas de horas], somente a folha de horas da semana atual é exibida. A folha de horas das próximas semanas não é gerada automaticamente.

+++

+++**Atualização de manutenção em 21 de janeiro de 2021**

**A classificação manual por coluna exibe todos os resultados**

_Relatórios_

Quando um usuário na nova experiência do [!DNL Workfront] clica em uma barra no gráfico de um relatório e depois em um cabeçalho de coluna para classificar manualmente os resultados desse agrupamento, todos os resultados do relatório são exibidos, não apenas os resultados do agrupamento selecionado originalmente.

A configuração **“[!UICONTROL Permitir compartilhamento de prova via URL ou código incorporado]” é alterada**

_[!DNL Workfront Proof]_

Quando um usuário cria uma prova e desmarca a configuração [!UICONTROL Permitir compartilhamento de prova via URL ou código incorporado], a configuração é verificada novamente após a geração da prova. Se o usuário deixar a configuração marcada, ela será desmarcada após gerar a prova.

Os usuários do **[!DNL Mac] não conseguem colar em campos de texto no visualizador de prova**

_[!DNL Workfront Proof]_

Quando um usuário tenta colar o texto em determinados campos no visualizador de prova, ele não é exibido no campo.

+++

+++**Atualização de manutenção em 14 de janeiro de 2021**

**Não é possível atualizar as configurações de Notificações por email**

_Configuração_

Quando um usuário tenta atualizar as configurações de notificações por email, não é possível acessar a área [!UICONTROL Notificações por email] e é exibida a mensagem de erro “[!UICONTROL Vamos tentar de novo. Ops! Um erro inesperado aconteceu. Entre em contato com o [!DNL Workfront] para que possamos descobrir o que aconteceu e resolver o problema.]”

O **[!UICONTROL Gráfico de Gantt] faz com que alguns campos fiquem truncados**

_Listas_

Quando um usuário abre o [!UICONTROL Gráfico de Gantt] em algumas áreas da lista, determinados campos, como [!UICONTROL Descrição], deixam o texto truncado. O usuário precisa clicar duas vezes no campo para ver o texto completo.

**Não é possível enviar arquivos de [!UICONTROL Detalhes do documento]**

_Documentos_

Quando um usuário na nova experiência do [!DNL Workfront] tenta enviar um documento da página [!UICONTROL Detalhes do documento], é exibida a mensagem de erro “[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.]”

+++

+++**Atualização de manutenção em 7 de janeiro de 2021**

**A caixa de diálogo Delegar aprovações se fecha**

_Página inicial_

Quando um usuário tenta delegar aprovações na [!UICONTROL Página inicial] e clica em qualquer data, a caixa de diálogo será fechada sem selecionar a data ou permitir que o usuário conclua a delegação do usuário.

**Problema ao mover um documento para uma tarefa**

_Documentos_

Quando um usuário tenta mover um documento ou uma prova na nova experiência do [!DNL Workfront], algumas tarefas fora do projeto não listam o projeto principal conforme esperado.

**PDF baixado com nome incorreto**

_[!DNL Workfront Proof]_

Quando um usuário recebe um link de download por email ([!UICONTROL Prova] > [!UICONTROL Imprimir comentários] > [!UICONTROL PDF]) e exporta o arquivo, o arquivo baixado é intitulado com números aleatórios em vez da ID da prova.

+++
