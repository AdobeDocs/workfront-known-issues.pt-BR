---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 704f5f9f7a460d13c7258df7865d84540e72fc6b
workflow-type: ht
source-wordcount: '7697'
ht-degree: 100%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2023.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em dezembro de 2023

+++**Atualização de manutenção em sexta-feira, 21 de dezembro de 2023**

**Problemas ao visualizar o status de subtarefas**

_Quadros_

Os seguintes problemas foram relatados em relação à exibição do status de subtarefas em um cartão nos Quadros:

* O status é mostrado como “Selecionar status” mesmo quando a tarefa já possui um status. Esse status pode ser visto ao visualizar a tarefa diretamente.
* Se a pessoa tentar selecionar um status, a tela ficará em branco e precisará ser atualizada.

**Não é possível anexar um documento a um cartão**

_Quadros_

Quando um usuário tenta anexar um documento a um cartão conectado, é possível selecionar o documento a ser anexado, mas ele não aparece na área de documento do cartão e não é anexado ao objeto ao qual o cartão está conectado.

Isso foi relatado nos problemas de cartões conectados.

**Não é possível selecionar o modelo na lista de [!UICONTROL Favoritos]**

_Modelos_

Quando um usuário tenta selecionar um modelo da lista de [!UICONTROL Favoritos], a lista desaparece quando a pessoa move o mouse em direção à lista, impossibilitando a seleção de um modelo.

**Algumas atualizações estão ausentes na nova experiência de comentários**

_Atualizações_

Quando uma pessoa visualiza atualizações na nova experiência de comentários, alguns dos comentários que deveriam ser exibidos não são. Se a pessoa mudar para a experiência de comentários herdada, todos os comentários são exibidos.

+++

+++Atualização de manutenção do **[!DNL Adobe Workfront Fusion]em 21 de dezembro de 2023**

O campo Módulo demora muito para ser aberto

_[!DNL Workfront Fusion]_

<!--no article-->

Quando um usuário está configurando um módulo que exige dados da conta conectada (por exemplo, para selecionar um registro), o módulo não pode recuperar os dados e a solicitação de dados atinge o tempo limite.

+++

+++**Atualização de manutenção em sexta-feira, 14 de dezembro de 2023**

**Provas que estão pendentes de aprovação não aparecem nos relatórios**

_Provas_

Quando uma pessoa visualiza um relatório de aprovações de prova pendentes, algumas aprovações pendentes não aparecem no relatório.
+++

+++**Atualização de manutenção em sexta-feira, 7 de dezembro de 2023**

**Aprovação paralisada no dispositivo [!UICONTROL Aguardando minha aprovação]**

_Página inicial_

Quando uma nova versão de um documento é enviada e a versão anterior possui uma aprovação que não está concluída, a versão antiga do documento fica paralisada no dispositivo [!UICONTROL Aguardando minha aprovação] do seu aprovador. A aprovação nem pode ser aprovada, já que há uma nova versão, nem pode ser removida do dispositivo.

**Problemas ao adicionar itens de trabalho na Visualização do quadro de tarefas ou de problemas**

_Tarefas / Problemas_

Quando uma pessoa visualiza a exibição de Quadro da área de tarefas ou problemas em um projeto e tenta adicionar uma tarefa ou problema, pode ocorrer o seguinte:

* A janela pop-up alterna entre dois estilos de janela diferentes
* A pessoa não consegue fechar a janela pop-up

Foi relatado que isso ocorre quando uma pessoa seleciona uma área na navegação à esquerda da janela pop-up antes de inserir qualquer informação.

+++

## Atualizações em novembro de 2023

+++**Atualização de manutenção em sexta-feira, 30 de novembro de 2023**

**As tarefas não aparecem no dispositivo [!UICONTROL Meu trabalho] **

_[!UICONTROL Página inicial]_

Quando um usuário visualiza seus [!UICONTROL Meu trabalho] widget em [!UICONTROL Início], algumas tarefas às quais estão atribuídos não são exibidas no widget. Por exemplo, um usuário ou usuária pode ir para um projeto e ver que tarefas lhe foram atribuídas, mas essas tarefas não aparecem no dispositivo [!UICONTROL Meu trabalho].

**A página de logon redireciona para a página de destino de logout**

_Logon_

Quando uma pessoa tenta fazer logon no [!DNL Workfront], em vez da página de logon, a pessoa é direcionada para a página que apareceria se fizesse logout.

**Erro 500 ao exportar um relatório**

_Relatórios_

Quando alguém tenta exportar um relatório, a exportação falha com o seguinte erro:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

Esse problema foi relatado em relatórios que usam um `valueexpression` para referenciar o texto da nota `lastNote`.

+++

+++**Atualização de manutenção em 16 de novembro de 2023**

**As horas orçadas no relatório de utilização não correspondem às horas orçadas relatadas por meio da API**

_Relatórios_

Quando um usuário faz uma chamada de API para o objeto RPBGHR de um determinado projeto e compara os resultados dessa chamada com o relatório de utilização desse projeto, os resultados não correspondem.

**É exibida a moeda personalizada incorreta na página Nova solicitação**

_Solicitações_

Quando um usuário envia uma solicitação e faz uma seleção que altera a lógica de exibição no formulário de solicitação, a moeda exibida é revertida para a moeda padrão em vez da moeda personalizada definida no projeto que a fila de solicitações representa.

Quando o usuário envia sua solicitação, a moeda é exibida como a moeda personalizada correta para o projeto que a fila de solicitações representa

**Linhas extras em comentários feitos por meio da API ou do[!DNL Workfront Fusion]**

_Atualizações_

Quando uma pessoa envia um comentário por meio de uma API ou do [!DNL Workfront Fusion], o comentário exibido na área Atualizações mostra linhas extras. Às vezes, há tantas linhas que a pessoa precisa rolar para baixo para ver o conteúdo do comentário.

Esse problema foi relatado na nova experiência de comentários.

+++

+++**Atualização de manutenção em 9 de novembro de 2023**

**Objetos ausentes no dispositivo Meu trabalho quando não ele está no topo da página**

_Página inicial_

O dispositivo Meu trabalho exibirá todos os objetos esperados se estiver no topo da nova Página inicial. No entanto, se ele estiver abaixo de qualquer outro dispositivo na página, ele exibirá apenas 10 objetos.

**Não é possível gerar a prova**

_Provas_

Quando um usuário tenta gerar uma prova, ela não é criada e o usuário vê o seguinte erro:

“[!UICONTROL Erro ao gerar a prova]”

Isso ocorre quando é desabilitada a configuração de nível de acesso do usuário[!UICONTROL  Exibir informações de contato].

**Campos são apagados quando um documento é adicionado a uma solicitação**

_Solicitações_

Quando uma pessoa cria uma solicitação, preenche campos em um formulário e, em seguida, adiciona ou remove um documento, alguns campos no formulário têm os dados apagados e é necessário preenchê-los novamente antes de enviar a solicitação.

**Tarefas pessoais aparecem na folha de horas**

_Folhas de horas_

Quando um usuário cria uma tarefa no widget [!UICONTROL To do] da nova experiência da [!UICONTROL Página inicial], essa tarefa aparece na folha de horas do usuário. Isso ocorre mesmo se a tarefa não contiver horas registradas e o projeto pessoal não tiver sido fixado.

+++

+++**Atualização de manutenção (Hot Fix) em 3 de novembro de 2023**

**Tarefas derivadas aparecem fora de ordem quando movidas sob a tarefa principal**

_Modelos_

Quando uma pessoa cria tarefas em um modelo e as move sob uma tarefa principal, os números atribuídos a essas tarefas derivadas não aparecem na ordem esperada. Assim, quando a página é atualizada, as tarefas derivadas são classificadas por números de tarefa inesperados e, portanto, fora de ordem.

+++

+++**Atualização de manutenção em 2 de novembro de 2023**

**Atualizações privadas são exibidas nos campos de valueexpression**

_Relatórios_

Quando um campo de relatório inclui uma valueexpression que faz referência a uma atualização privada, pessoas que não estão incluídas nessa atualização privada podem vê-la no relatório.

**Usuário exibido como superalocado devido a uma capacidade imprecisa**

_Balanceador de carga de trabalho_

Um usuário pode ser exibido como “superalocado” no balanceador de carga de trabalho. Se o usuário passar o mouse sobre a superalocação, verá que sua capacidade está definida como 0.

Ao alterar o intervalo de datas, a alocação está adequada. No entanto, ao atualizar a página, a capacidade poderá se tornar inadequada novamente.

+++

## Atualizações em outubro de 2023

+++**Atualização de manutenção em 26 de outubro de 2023**

**A pesquisa não está funcionando**

_Quadros_

Quando tentam pesquisar quadros, a pesquisa não retorna todos os cartões que satisfazem os critérios da pesquisa.

**Não é possível exibir a prova interativa no visualizador da web**

_Provas_

Quando uma pessoa tenta visualizar uma prova no visualizador de provas da web, a prova não é exibida, e a pessoa vê o seguinte erro:

“[!UICONTROL Parâmetro de consulta Key-Pair-Id ou valor de cookie ausente]”

**Não é possível criar uma nova versão de uma prova**

_Provas_

Quando uma pessoa tenta criar uma nova versão de uma prova, a nova versão não é gerada e a seguinte mensagem de erro é exibida:

“[!UICONTROL Erro ao gerar a prova]”

**O usuário é duplicado ao compartilhar uma solicitação**

_Solicitações_

Ao compartilhar uma solicitação, quando o nível de acesso de um usuário com o qual a solicitação está sendo compartilhada é modificado, o usuário logo acima desse usuário na lista se torna esse usuário.

Por exemplo, se a solicitação estiver sendo compartilhada com o Usuário A e com o Usuário B, e o acesso do Usuário B for modificado, o Usuário A será alterado para Usuário B, passando a haver dois Usuários B na lista. Além disso, somente o acesso do Usuário B superior é modificado.

**Erro “[!UICONTROL Ops]” no cabeçalho da tarefa**

_Tarefas_

Quando um usuário visualiza uma tarefa, o cabeçalho da tarefa não contém informações. Em vez disso, o usuário vê a seguinte mensagem de erro:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

+++

+++**Atualização de manutenção em 19 de outubro de 2023**

Os usuários não são notificados sobre respostas em um thread de comentários

_Notificações_

Quando um usuário responde a um comentário, outros usuários que deveriam receber notificações sobre a resposta não as recebem. Alguns usuários podem receber a notificação, mas outros, não.

**Comentário em branco extra ao fazer um comentário em uma prova**

_Provas_

Ao fazer um comentário em uma prova, um outro comentário em branco é criado.

Esse problema foi relatado em provas de vídeo.

A guia **[!UICONTROL Atividade da prova] não abre**

_Provas_

Quando um usuário está visualizando uma prova e clica na guia [!UICONTROL Atividade da prova], ela leva o usuário de volta à guia [!UICONTROL Detalhes da prova].

As **[!UICONTROL Horas planejadas] são realocadas quando uma tarefa é atribuída a um usuário adicional**

_Tarefas_

Quando uma tarefa que contenha [!UICONTROL Horas planejadas] alocadas a outros designados na tarefa é atribuída a um usuário, as [!UICONTROL Horas planejadas] da tarefa são distribuídas equitativamente para todos os designados na tarefa.

**“[!UICONTROL Excluído]” é exibido como o nome de usuário nas atualizações do sistema quando um problema é convertido em tarefa**

_Atualizações_

Quando um usuário conectado como outro usuário converte um problema em tarefa e o problema é atribuído a uma equipe, as atualizações do sistema exibem “[!UICONTROL Excluído]” como nome do usuário que solicitou que a equipe trabalhasse na tarefa.

+++

+++**Atualização de manutenção em 12 de outubro de 2023**

**Fluxos de trabalho removidos em contas que não os usam**

_Quadros_

Nas contas que nunca criaram um fluxo de trabalho no aplicativo Quadros, a área de fluxos de trabalho foi removida do painel de Quadros. As contas que usam fluxos de trabalho ainda têm acesso a eles.

**Os campos calculados não retêm valores quando um problema é convertido em tarefa**

_Formulários personalizados_

Os campos calculados que fazem referência a si mesmos não retêm seus valores quando um problema é convertido em tarefa.

Ao converter o problema em tarefa, o valor desejado é exibido corretamente na janela de edição. No entanto, após a conclusão da conversão, o campo calculado exibe “N/A”.

**Erro ao alterar filtros na [!UICONTROL Página inicial]**

_Página inicial_

Quando um usuário altera os filtros na [!UICONTROL Página inicial], a área da [!UICONTROL Página inicial] não é carregada, e o usuário vê o seguinte erro:

“[!UICONTROL Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.]”

+++

+++**Atualização de manutenção em 5 de outubro de 2023**

**O quadro é carregado lentamente**

_Quadros_

Quando um usuário carrega um quadro, o quadro é carregado muito lentamente. Isso pode ocorrer mesmo se o quadro tiver um pequeno número de cartões.

Cartões arquivados, mesmo quando não eram exibidos, estavam afetando o tempo de carregamento do quadro.

**Não é possível mover cartões entre colunas**

_Quadros_

Quando um usuário tenta mover um cartão em um quadro, o cartão não se move. Isso ocorre nas seguintes circunstâncias:

* Arrastar e soltar
* Opção Mover no cartão
* Editar o cartão

**Não é possível mover cartões para fora da coluna de entrada**

_Quadros_

O usuário pode arrastar um cartão para fora da coluna de entrada para outra coluna do quadro, mas os cartões subsequentes não podem ser movidos para fora da coluna de entrada.

**A função Agrupar por afeta o desempenho do quadro**

_Quadros_

Quando uma pessoa tenta agrupar os cartões por responsáveis ou tags, o desempenho do quadro fica muito lento.

**Os emails de lembrete automático não estão sendo enviados**

_Notificações_

Os lembretes de email automáticos não estão sendo enviados. Isso começou em 14 de setembro de 2023.

+++

## Atualizações em setembro de 2023

+++**Atualização de manutenção em 28 de setembro de 2023**

**Não é possível excluir o campo personalizado**

_Formulários personalizados_

Quando uma pessoa tenta excluir um campo personalizado, não consegue excluí-lo e vê a mensagem: “[!UICONTROL Erro no banco de dados devido à violação de restrição]”.

**Comentários feitos na nova experiência de comentários não estão visíveis na experiência herdada**

_Atualizações_

Os comentários feitos na nova experiência são exibidos na área Comentários, porém, o mesmo comentário pode não aparecer na experiência herdada. Isso pode fazer com que usuários da experiência herdada percam alguns comentários.

**Faltam elementos na página do objeto**

_Workfront_

Quando uma pessoa navega para uma seção personalizada em um objeto no [!DNL Workfront], a página que é carregada pode não ter alguns elementos. Esses elementos podem incluir:

* O painel de navegação esquerdo
* O nome do objeto ao qual a seção personalizada pertence
* Campos e informações no cabeçalho

+++

+++**Atualização de manutenção em 21 de setembro de 2023**

**Não é possível atribuir um usuário em um quadro no fluxo de trabalho**

_Quadros_

Ao tentar atribuir usuários a uma tarefa de um quadro que faz parte de um fluxo de trabalho e começar a digitar o nome, o usuário não é exibido na lista suspensa de usuários disponíveis. Isso ocorre mesmo quando o usuário está ativo e é membro do quadro e do fluxo de trabalho.

Também é possível observar que os usuários desativados são exibidos no menu suspenso.

**Não é possível excluir um item da lista de verificação**

_Quadros_

Quando uma pessoa tenta excluir um item da lista de verificação de um cartão em um quadro, o botão [!UICONTROL Excluir] não responde e o item não é excluído.

**Os formulários personalizados são carregados lentamente**

_Formulários personalizados_

Quando uma pessoa tenta carregar um formulário personalizado, o formulário é carregado lentamente.

**Não é possível mover um documento para uma pasta diferente**

_Documentos_

Ao mover um documento para uma pasta de objetos, não é possível mover o objeto para uma pasta diferente.

**Erro de XML ao baixar**

_Documentos_

Quando uma pessoa tenta baixar um documento, ele não é baixado e uma página com a seguinte mensagem seguida por um texto XML é exibida.

“[!UICONTROL O arquivo XML não parece ter informações de estilo associadas a ele. Veja a árvore de documentos abaixo.]”

**Não é possível baixar documentos de ambientes de Visualização / Sandbox**

_Documentos_

Quando uma pessoa tenta baixar um documento de um ambiente distinto da produção, ele não é baixado e o seguinte erro é exibido:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

**As provas parecem dessaturadas ou cortadas**

_Provas_

Os seguintes problemas foram relatados ao criar uma prova de um URL.

* A prova parece dessaturada ou desbotada.
* A prova está cortada.

Isso pode dificultar as decisões da prova, pois a prova não é representada com precisão.

**As provas demoram muito para serem geradas**

_Provas_

Quando uma pessoa tenta gerar uma prova, ela demora muito para ser gerada. A geração da prova pode levar vários dias.

+++

+++**Atualização de manutenção em 14 de setembro de 2023**

**Erro “[!UICONTROL Sem fábrica]” ao adicionar um documento**

_Documentos_

Quando uma pessoa tenta adicionar um documento de uma fonte externa, o [!DNL Workfront] não consegue acessar a origem e o seguinte erro é exibido:

“[!UICONTROL Ocorreu o seguinte erro: Nenhuma fábrica encontrada para o tipo de autenticação nulo]”

**Erro “Ops” em relatórios de matriz**

_Relatórios_

Ao tentar visualizar um relatório de matriz, o relatório não carrega e o seguinte erro é exibido:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Isso ocorre ao agrupar um relatório por intervalos de datas.

+++

+++**Atualização de manutenção em 11 de setembro de 2023**

**As tarefas pessoais não são exibidas nas folhas de horas**

_Folhas de horas_

As tarefas pessoais não são mais exibidas por padrão na folha de horas. As tarefas pessoais serão exibidas na folha de horas quando forem fixadas ou possuírem horas registradas. Antes dessa alteração, as tarefas pessoais eram exibidas nas folhas de horas por padrão.

+++

+++**Atualização de manutenção em 7 de setembro de 2023**

**O projeto fica em branco quando carregado a partir da nova experiência da [!UICONTROL Página inicial]**

_Projetos_

Ao clicar em um projeto na nova experiência da [!UICONTROL Página inicial], a página do projeto não carrega.

Isso ocorre quando a pessoa faz logon como outro usuário e, em seguida, sai dessa conta e retorna à sua própria página [!UICONTROL Inicial].

+++

## Atualizações em agosto de 2023

+++**Atualização de manutenção em 31 de agosto de 2023**

**Os filtros não se aplicam aos dispositivos na experiência da nova [!UICONTROL Página inicial]**

_[!UICONTROL Página inicial]_

Ao tentar aplicar um filtro a um dispositivo na experiência da nova [!UICONTROL Página inicial], o dispositivo mostra itens que deveriam ter sido excluídos pelo filtro.

Esse problema foi relatado no ambiente de Sandbox personalizada. Os mesmos dispositivos filtram conforme o esperado nos ambientes Visualização e Produção.

**Problemas ao carregar relatórios de matriz**

_Relatórios_

Ao tentar carregar um relatório de matriz como um gráfico, uma das seguintes situações pode ocorrer:

* Algumas informações no relatório não são carregadas
* O relatório exibe o erro “[!UICONTROL Não foi possível carregar o conteúdo do servidor]”

**O planejador não carrega quando um filtro está aplicado**

_[!UICONTROL Planejador de recursos]_

Não é possível carregar o [!UICONTROL Planejador de recursos] e a seguinte mensagem de erro é exibida:

“[!UICONTROL Erro: algo deu errado ao conectar ao serviço WorkPerDay]”

+++

+++**Atualização de manutenção em 24 de agosto de 2023**

**Não é possível selecionar texto em listas ou marcadores**

_Provas_

Ao visualizar uma prova no visualizador de prova e tentar selecionar o texto que está em uma lista ou em um marcador, a ferramenta de seleção de texto não funciona e o texto não é selecionado.

**Criar uma nova versão de uma prova exclui todas as versões dela**

_Provas_

Ao criar uma prova de um documento, o processo ocorre conforme o esperado. No entanto, ao criar outra versão da prova, tanto a versão antiga quanto a nova são excluídas. Existe uma opção [!UICONTROL Criar prova] no documento original e as versões da prova podem ser encontradas na [!UICONTROL Lixeira] da área [!UICONTROL Prova] no [!DNL Workfront].

+++

+++**Atualização de manutenção em 17 de agosto de 2023**

**Não é possível acessar um projeto com um URL que usa uma [!UICONTROL ID de referência]**

_Projetos_

Ao tentar acessar um projeto usando um URL que inclui um número de [!UICONTROL ID de referência], o usuário é redirecionado para uma página com uma mensagem de erro. Acessar uma tarefa usando um URI com uma [!UICONTROL ID de referência] funciona conforme o esperado.

**A configuração “[!UICONTROL Desabilitar notificações de email de prova]” é exibida incorretamente**

_Provas_

Ao visualizar as configurações de uma prova no [!DNL Workfront], a caixa de seleção “[!UICONTROL Desabilitar notificações de email de prova]” não exibe a configuração atual corretamente. Ao marcar a caixa, o que deveria desabilitar as notificações de email de prova, as notificações são habilitadas. O oposto também é verdadeiro.

**Não é possível ajustar marcações de prova**

_Provas_

Ao fazer um comentário no visualizador de prova, realizar uma marcação e clicar fora dela, não é mais possível ajustar a marcação.

+++

+++**Atualização de manutenção em 10 de agosto de 2023**

**Não é possível excluir o item [!UICONTROL Tarefa] na experiência da nova [!UICONTROL página inicial]**

_Página inicial_

Ao utilizar a experiência da nova [!UICONTROL Página inicial] e tentar excluir um item do dispositivo [!UICONTROL Tarefa], o item não é excluído e o seguinte erro é exibido:

“[!UICONTROL Erro ao remover a tarefa. Tente novamente mais tarde.]”

Isso pode ocorrer quando há horas registradas no item [!UICONTROL Tarefa].

**O projeto fixado não exibe informações em algumas colunas**

_Projetos_

Ao acessar um projeto fixado com um marcador, as listas de objetos (como a lista de tarefas) podem exibir colunas em branco. Por exemplo, a coluna [!UICONTROL Atribuições] pode não exibir atribuições, mesmo que elas tenham sido feitas.

**Módulo de suspensão causa travamento de cenários**

_[!DNL Workfront Fusion]_

O módulo [!UICONTROL Ferramentas] > [!UICONTROL Suspender] pode travar a execução de um cenário. Essas execuções mostram um status de Em execução no [!UICONTROL Histórico do cenário] e não são concluídas.

+++

+++**Atualização de manutenção em 3 de agosto de 2023**

**Dificuldade em localizar itens na coluna de entrada**

_Quadros_

A coluna de entrada em um quadro era anteriormente classificada pela prioridade definida em tarefas e problemas, o que dificultava a localização de itens específicos.

A ordem padrão agora é a seguinte:

Tarefas:

* Ordem principal: nome do projeto
* Ordem secundária: estrutura do detalhamento do trabalho

Problemas

* Ordem principal: nome do projeto
* Ordem secundária: número de referência

**O projeto não soluciona corretamente o problema**

_Projetos / Problemas_

Ao alterar o status de um projeto que é objeto da resolução de um problema, o status do problema é alterado para um que não corresponde à mesma chave do status do projeto.

**Erro “Ops” em relatórios de matriz**

_Relatórios_

Ao tentar visualizar um relatório de matriz, o relatório não carrega e o seguinte erro é exibido:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Esse problema foi relatado por usuários na região da Europa, Oriente Médio e África (EMEA).

+++

## Atualizações em julho de 2023

+++**Atualização de manutenção em 27 de julho de 2023**

**As tags e itens de listas de verificação não funcionam corretamente na visualização do quadro do projeto**

_Quadros_

As tags e itens de listas de verificação foram removidos da visualização do quadro dos projetos, pois não fazem parte das tarefas do Workfront e não podem ser compartilhados entre usuários.

**“[!UICONTROL Habilitar em todo o sistema]” e “[!UICONTROL Exibir em todo o sistema]” apresentam funcionalidades diferentes**

_Filtros_

Ao compartilhar um filtro e habilitar a opção “[!UICONTROL Exibir em todo o sistema]”, o filtro é compartilhado com cada usuário no sistema. No entanto, se um(a) admin visualizar esse filtro na [!UICONTROL Configuração], verá que ele é exibido como “[!UICONTROL falso]” na coluna “[!UICONTROL Visível para todo o sistema]”. Para tornar esse filtro um padrão do sistema, o administrador deve habilitar a opção “[!UICONTROL Habilitar em todo o sistema]” na [!UICONTROL Configuração]. Isso pode causar confusão devido à similaridade dos termos.

+++

+++**Atualização de manutenção em 20 de julho de 2023**

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++**Atualização de manutenção em 13 de julho de 2023**

**A linha do tempo não é recalculada**

_Projetos / Tarefas / Problemas_

Quando ocorre um evento que deveria acionar um cálculo da linha do tempo, ela não é recalculada. Isso afeta os recálculos que ocorrem após alterações, bem como os recálculos programados. Isso pode afetar a precisão do Balanceador de carga de trabalho.

**As aprovações de prova bloqueadas ainda são mostradas na Lista de trabalho**

_Provas_

As aprovações de prova que ultrapassaram seu prazo e foram bloqueadas ainda são mostradas na Lista de trabalho da página inicial do aprovador, em vez de serem removidas da lista quando o prazo acabou.

**O relatório de utilização não é carregado**

_Relatórios_

Quando um cliente tenta visualizar um relatório de utilização, um ícone giratório de carregamento é exibido, mas o relatório não é carregado. O relatório retorna um erro 500, mas nenhuma indicação é exibida sobre a falha do relatório.

**A página Editar usuário fica em branco**

<!--no article-->

_Usuários_

Quando uma pessoa tenta editar um usuário(a), a página Editar usuário fica em branco e ela não consegue editar o usuário(a).

+++

## Atualizações em junho de 2023

+++**Atualização de manutenção em 29 de junho de 2023**

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++**Atualização de manutenção em 22 de junho de 2023**

**Erro “[!UICONTROL Ops]” ao visualizar um relatório de matriz**

_Relatórios_

Quando uma pessoa visualiza um relatório de matriz, ele verá o seguinte erro:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Esse problema foi relatado quando o relatório está classificado por data e a opção “[!UICONTROL Mostrar semanas sem resultados]” está habilitada.

**As datas são exibidas incorretamente nos relatórios de matriz**

_Relatórios_

Quando um gráfico ou relatório de matriz é agrupado por data, as datas próximas aos limites do agrupamento podem aparecer tanto no agrupamento correto, quanto no agrupamento anterior/seguinte ou em ambos.

+++

+++**Atualização de manutenção em 15 de junho de 2023**

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++**Atualização de manutenção em 8 de junho de 2023**

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++Atualização de manutenção do **[!DNL Adobe Workfront Fusion]em 8 de junho de 2023**

O [!DNL Fusion] implantou uma correção que impede a remoção das conexões de um usuário quando ele for removido ou desativado no [!UICONTROL Adobe Admin Console].

Os administradores de equipe do [!DNL Fusion] ainda podem remover conexões desnecessárias da página [!UICONTROL Conexões] no [!DNL Fusion].

+++

+++**Atualização de manutenção em 1° de junho de 2023**

**Nenhuma mensagem de erro ao reordenar uma tarefa com o status [!UICONTROL Aprovação pendente]**

_Tarefas_

Quando uma pessoa tenta reordenar uma tarefa com o status [!UICONTROL Aprovação pendente] em uma lista de tarefas, ela parece se mover na lista. Após a atualização, é possível ver que o item não é movido. O item não pode ser movido porque está sob o status [!UICONTROL Aprovação pendente], mas não há uma mensagem que informe isso ao usuário, o que pode causar confusão.

**Nenhuma mensagem de erro ao mover a tarefa predecessora sob uma tarefa dependente**

_Tarefas_

Quando uma pessoa tenta reordenar uma tarefa com o status [!UICONTROL Aprovação pendente] em uma lista de tarefas, ela parece se mover na lista. Após a atualização, é possível ver que o item não foi movido. O item não pode ser movido porque uma tarefa predecessora não pode ser movida sob uma tarefa na qual ela atua como predecessora, mas não há uma mensagem que informe isso ao usuário, o que pode causar confusão.

+++

## Atualizações em maio de 2023

+++**Atualização de manutenção em 25 de maio de 2023**

O quadro do **[!UICONTROL Kanban] fica em branco ao editar cartões**

_Ágil_

Ao alterar um detalhe de um cartão no quadro do [!UICONTROL Kanban], o quadro fica em branco em vez de registrar a alteração. Se a página for atualizada manualmente, o quadro do [!UICONTROL Kanban] reaparece e mostra a alteração correta.

Esse problema foi relatado ao:

* Editar um cartão
* Mover um cartão


+++

+++**Atualização de manutenção em 22 de maio de 2023**

**Não é possível ajustar o tamanho do texto descritivo**

_Formulários personalizados_

Quando o designer de formulários personalizados foi lançado na versão beta, a funcionalidade para ajustar o tamanho do texto descritivo não estava disponível. Esse problema foi corrigido e agora é possível ajustar o tamanho do texto descritivo.

+++

+++**Atualização de manutenção em 18 de maio de 2023**

**O relatório não classifica corretamente por campo personalizado**

_Relatórios_
Ao executar um relatório de tarefa, o relatório parece classificar corretamente durante o carregamento, mas ao término do processo, o relatório não está classificado corretamente.

Isso parece ocorrer se todas as seguintes circunstâncias forem atendidas:

* O relatório é um relatório de tarefa
* O relatório é classificado por um campo personalizado
* O relatório tem um agrupamento aplicado

+++

+++**Atualização de manutenção em 11 de maio de 2023**

**Não é possível alternar a versão da prova ao visualizar provas**

_Provas_

Ao visualizar uma prova no [!UICONTROL Visualizador de prova] e alternar para outra versão, a lista suspensa de versões é desabilitada e não é possível retornar à versão original que se estava visualizando ou para outra versão da prova.

A pesquisa do **[!DNL Workfront]atinge o tempo limite**

_Pesquisa_

A pesquisa do [!DNL Workfront] atinge o tempo limite. A pesquisa pode retornar alguns resultados ou nenhum.

Esse problema também afeta a funcionalidade do módulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Pesquisar].

+++

+++Atualização de manutenção do **[!DNL Adobe Workfront Fusion]em 11 de maio de 2023**

**Erros de tempo limite no[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Quando um cenário está em execução, pode ocorrer um erro de tempo limite. As informações do módulo com erro não chegam ao destino.

A pesquisa do **[!DNL Workfront]atinge o tempo limite**

_Pesquisa_

A pesquisa do [!DNL Workfront] atinge o tempo limite. A pesquisa pode retornar alguns resultados ou nenhum.

Esse problema também afeta a funcionalidade do módulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Pesquisar].

+++

+++**Atualização de manutenção em 9 de maio de 2023**

**Filtros salvos disponíveis na coluna de entrada do quadro**

_Quadros_

Agora é possível usar a tarefa existente do Workfront e os filtros de problemas ao configurar a coluna de entrada de um quadro. No entanto, os filtros de coluna de entrada existentes agora são somente leitura no painel de configuração. Os filtros existentes ainda são aplicados à coluna de entrada, mas é preciso recriar os filtros para poder editá-los.

+++

+++**Atualização de manutenção em 4 de maio de 2023**

**Não é possível selecionar um modelo dos [!UICONTROL Modelos favoritos]**

_Modelos_

Ao tentar selecionar um modelo no menu Ações (três pontos), a lista de modelos desaparece quando o mouse é movido para a lista, impossibilitando a seleção de um modelo. Isso ocorre porque a barra de rolagem está entre o menu e a lista de modelos, e o mouse alterna o foco para a barra de rolagem à medida que se move para a lista de modelos.

+++

## Atualizações em abril de 2023

+++**Atualização de manutenção em 27 de abril de 2023**

**Não é possível alternar entre provas no [!UICONTROL Visualizador de prova]**

_Provas_

Ao visualizar uma prova no [!UICONTROL Visualizador de prova] e alternar para outra prova, o botão de alternância para de responder. Não é possível retornar à prova original que se estava visualizando ou para outra prova.

**Editar imagens anexadas ao editar um comentário**

_Atualizações_

Agora é possível editar a imagem anexada a um comentário ao editar o comentário. Isso está disponível na seção Atualizações das Metas do Workfront e na seção de problemas ao habilitar a experiência beta de comentários.

+++

+++Atualização de manutenção do **[!DNL Adobe Workfront Fusion]em 25 de abril de 2023**

Os links de ajuda no aplicativo do **[!DNL Fusion]não abrem as respectivas páginas de ajuda**

_[!DNL Workfront Fusion]_

Ao visualizar uma prova no [!UICONTROL Visualizador de prova] e alternar para outra prova, o botão de alternância para de responder. Não é possível retornar à prova original que se estava visualizando ou para outra prova.

+++

+++**Atualização de manutenção em 20 de abril de 2023**

**Problemas em campos suspensos personalizados**

_Formulários personalizados_

Campos suspensos personalizados que foram habilitados como campos de seleção múltipla podem apresentar os seguintes problemas:

* O botão “+[!UICONTROL Adicionar]” não está presente quando o formulário não está no modo de edição.
* Campos sem valor mostram uma opção “--[!UICONTROL sem rótulo]--”.

**Não é possível usar a ferramenta Polyline ao fazer um comentário em uma prova**

_Provas_

Ao visualizar uma prova no Visualizador de prova e tentar fazer um comentário usando a ferramenta Polyline, a ferramenta não marca a prova.

**A caixa de opções de texto mostra “textAnnotations”**

_Provas_

Ao visualizar uma prova, começar a adicionar um comentário e abrir a ferramenta de texto, a palavra “textAnnotation” aparece ao lado das opções na ferramenta. A ferramenta de texto ainda funciona conforme o esperado, e “textAnnotation” desaparece após o comentário ser publicado.

**Manter imagens como rascunho ao sair de uma seção de atualização de metas ou de problemas na experiência beta de comentários**

>[!NOTE]
>
>Uma pré-visualização desse recurso foi lançada em 19 de abril de 2023 e disponibilizada no ambiente de produção em 20 de abril de 2023.

_Atualizações_

Agora, ao sair da página Atualizações durante o processo de composição de uma mensagem com uma imagen anexada, a mensagem e a imagem estarão preservadas quando você voltar. Antes desta atualização, os comentários não enviados eram preservados, mas não as imagens. Isso está disponível na seção Atualizações de metas e problemas ao habilitar a experiência beta de comentários.

**Atualizações em tempo real e comentários excluídos na seção Atualizações**

>[!NOTE]
>
>Uma pré-visualização desse recurso foi lançada em 19 de abril de 2023 e disponibilizada no ambiente de produção em 20 de abril de 2023.

_Atualizações_

Agora, ao adicionar um comentário ou resposta, ou excluir um comentário da área Atualizações, é possível ver o novo comentário ou uma indicação de que o comentário foi removido em tempo real, sem atraso. Isso está disponível na seção Atualizações de metas e problemas ao habilitar a experiência beta de comentários.

**Nível de acesso alterado pelo sistema sem registro da alteração**

_Usuários_

O nível de acesso de um usuário pode ser alterado pelo sistema sem avisos. Quando isso ocorre, não há uma atualização visível e a alteração não aparece no log de auditoria.

+++

+++**Atualização de manutenção em 17 de abril de 2023**

**Mostrar novos comentários fora da área visível da tela na seção [!UICONTROL Atualizações] de problemas (nova experiência Beta de comentários) e na de [!UICONTROL Metas]**

_Atualizações_

Adicionamos um banner de notificação na seção [!UICONTROL Atualizações] para informar quando houver comentários novos em um item que pode estar fora da área visível na tela. Esta atualização está atualmente disponível na seção [!UICONTROL Atualizações] de metas e na de problemas quando a nova experiência beta de comentário tiver sido habilitada para problemas.

+++

+++**Atualização de manutenção em 13 de abril de 2023**

**Os filtros não são aplicados à lista de solicitações**

_Solicitações_

Quando uma pessoa visualiza uma lista de solicitações com um filtro aplicado, a lista inclui solicitações que o filtro deveria excluir.

**Não é possível selecionar o [!UICONTROL Tipo de hora padrão] ou [!UICONTROL Tipos de hora disponíveis]**

_Usuários_

Quando um administrador edita um usuário e tenta selecionar um [!UICONTROL Tipo de hora padrão] ou [!UICONTROL Tipo de hora disponível], os menus suspensos desses campos ficam desabilitados e não é possível selecionar os tipos de hora.

+++

+++**Atualização de manutenção em 6 de abril de 2023**

**Os menus suspensos não são abertos quando um(a) usuário(a) é adicionado a uma prova**

_Provas_

Quando uma pessoa adiciona um usuário a uma prova no [!UICONTROL Visualizador de prova], os menus suspensos “[!UICONTROL Função de prova]” e “[!UICONTROL Alertas por email]” não podem ser abertos. O(a) usuário(a) não consegue atribuir uma função de prova ou alerta de email. Isso pode ocorrer ao adicionar um usuário por meio de um comentário ou ao compartilhar a prova com o usuário.

+++

## Atualizações em março de 2023

+++**Atualização de manutenção em 30 de março de 2023**

**Não é possível alternar a versão da prova ao visualizar provas**

_Provas_

Quando uma pessoa visualiza uma prova no [!UICONTROL Visualizador de prova] e alterna para outra versão, a lista suspensa de versões fica desativada, impedindo de voltar para a versão original que estava visualizando ou para outra versão da prova.

**Erro 504 ao exportar relatórios**

_Relatórios_

Quando uma pessoa tenta exportar um relatório com um número elevado de itens, um erro 504 lhe é exibido e ela não consegue exportá-lo.

**Uma atualização feita em nome de um usuário é vinculada diretamente a ele**

_Atualizações_

Quando um administrador está conectado como um usuário e faz um comentário, esse é vinculado diretamente ao usuário, e não ao administrador em nome do usuário.

+++

+++**Atualização de manutenção em 23 de março de 2023**

O conteúdo do painel **[!UICONTROL Resumo] é muito largo para o painel**

_Documentos_

Quando uma pessoa visualiza o painel [!UICONTROL Resumo] de um documento, seus conteúdos são muito largos para serem visualizados no painel. O painel agora tem uma barra de rolagem horizontal e é necessário rolar essa barra para ver o conteúdo do painel [!UICONTROL Resumo]. Isso ocorre porque o nome do arquivo do documento não possui quebra de linha. Esse problema é limitado a arquivos em que o nome do arquivo tenha uma extensão de arquivo HTML.

**Nova versão do [!UICONTROL Visualizador de prova para desktop]**

_Prova_

Para corrigir um problema de comentário no [!UICONTROL Visualizador de prova para desktop], implantamos uma nova versão do visualizador.

As pessoas que já tiverem o [!UICONTROL Visualizador de prova para desktop] instalado receberão esta atualização automaticamente.

Também é possível baixar manualmente a versão mais recente. Para obter mais informações, consulte [Instalar o [!UICONTROL Visualizador de prova para desktop]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=pt-BR).

* Versão anterior: 2.1.22
* Nova versão: 2.1.23

+++

+++**Atualização de manutenção em 16 de março de 2023**

**Os itens da lista de verificação não são copiados ao copiar um cartão**

_Quadros_

Ao copiar um cartão ad hoc (os cartões conectados não podem ser copiados), os itens da lista de verificação não são copiados para o novo cartão.

**O campo personalizado está ausente quando o problema é convertido para o projeto**

_Projetos_

Quando uma pessoa converte um problema em um projeto usando um modelo, um campo personalizado que estava no problema não é exibido no projeto. Esse problema afeta somente usuários não administradores.

**Mensagens personalizadas não aparecem nas notificações por email**

_Provas_

Ao compartilhar uma prova e adicionar uma mensagem personalizada, a mensagem não é exibida no email de notificação do destinatário. O assunto é o nome da prova e a mensagem não aparece no email.

+++

+++**Atualização de manutenção em 9 de março de 2023**

**O nível de acesso não é atribuído ao reativar um usuário**

_Usuários_

Ao reativar um usuário que estava desativado e tentar atribuir a ele(a) um nível de acesso na janela [!UICONTROL Reativar usuário], a lista suspensa de nível de acesso não é preenchida conforme o usuário digita e não é possível selecionar um nível de acesso. Se você digitar o nível de acesso e salvar, esse nível de acesso não será atribuído ao usuário reativado.

**Salve o rascunho de um comentário na área [!DNL Goals]**

_[!DNL Workfront Goals]_

Agora, ao sair da página [!UICONTROL Atualizações] de uma meta durante o processo de composição de uma mensagem, a mensagem estará preservada quando você retornar. Antes desta atualização, o comentário não enviado era excluído.

+++

+++**Atualização de manutenção em 2 de março de 2023**

**Não é possível adicionar cartões quando um agrupamento é aplicado**

_Quadros_

Ao visualizar um quadro com um agrupamento aplicado e tentar adicionar um cartão, só é possível digitar o nome do cartão. O restante dos campos do cartão está desabilitado, incluindo o botão [!UICONTROL Salvar].

Se o agrupamento for alterado para [!UICONTROL Nenhum], o problema permanece. É necessário alterar o agrupamento para [!UICONTROL Nenhum] e atualizar a página para que a funcionalidade de adicionar um cartão seja restaurada.

**Os cartões conectados não são adicionados às colunas com base no status**

_Quadros_

Mesmo que as políticas de coluna sejam aplicadas para o status, os novos cartões conectados aparecem na coluna mais à esquerda, e não na coluna que corresponde ao status.


**O link de um comentário redireciona para a página [!UICONTROL Detalhes]**

_Atualizações_

Ao clicar em um link de um comentário em um objeto no Workfront, o fluxo de atualização é carregado brevemente e, em seguida, há um redirecionamento para a área [!UICONTROL Detalhes] do objeto. Isso pode ocorrer ao clicar no link de um email ou colar o link no navegador.

Atualmente, isso afeta apenas objetos de Documento.

**O Resumo de impressão não é carregado**

_[!UICONTROL Prova do Workfront]_

Ao tentar carregar a página Resumo de impressão, ela parece estar sendo carregada, mas o processo nunca é concluído.

+++

## Atualizações em fevereiro de 2023

+++**Atualização de manutenção em 23 de fevereiro de 2023**

**O link de um comentário redireciona para a página [!UICONTROL Detalhes]**

_Atualizações_

Ao clicar em um link de um comentário em um objeto no Workfront, o fluxo de atualização é carregado brevemente e, em seguida, há um redirecionamento para a área [!UICONTROL Detalhes] do objeto. Isso pode ocorrer ao clicar no link de um email ou colar o link no navegador.

Atualmente, isso afeta apenas objetos de Documento.

**Não é possível editar configurações pessoais de notificação**

_Usuários_

Quando um usuário com uma licença de [!UICONTROL Trabalhador] tenta editar suas próprias configurações de notificação, as opções de [!UICONTROL Notificações] não são exibidas na janela [!UICONTROL Editar] e não é possível editar as configurações.

+++

+++**Atualização de manutenção em 16 de fevereiro de 2023**

**Várias atribuições de equipe em quadros**

_Quadros_

Agora é possível atribuir várias equipes a uma tarefa ou problema em um quadro, bem como ao próprio quadro.

**Aumento do limite de queda do cartão**

_Quadros_

Os limites de tempo de queda do cartão foram aumentados para 8 semanas (60 dias) em vez de 4 semanas (30 dias).

**A desativação programada não desativa o usuário**

_Usuários_

A desativação programada de um usuário não ocorre ao chegar a data e hora programadas.

+++

+++**Atualização de manutenção em 9 de fevereiro de 2023**

Adição do campo **[!UICONTROL Pontos da história] a listas de tarefas e problemas e relatórios**

_Relatórios_

O campo [!UICONTROL Pontos da história] agora está disponível para adicionar a listas e relatórios para tarefas ou problemas. É um campo de formulário editável e gratuito que não está vinculado a horas planejadas ou atribuições de equipe.

+++

+++**Atualização de manutenção em 8 de fevereiro de 2023**

**Botão Filtrar na coluna de entrada**

_Quadros_

A coluna de entrada em um quadro agora inclui um botão **[!UICONTROL Adicionar um filtro]** quando a coluna estiver vazia e nenhum filtro tiver sido criado. O botão abre a área de configuração, onde é possível adicionar filtros para trazer tarefas e problemas para a coluna de entrada.

+++

+++**Atualização de manutenção em 2 de fevereiro de 2023**

O ícone **[!UICONTROL Quadros] aparece no [!UICONTROL Menu principal] por padrão**

_Quadros_

O ícone [!UICONTROL Quadros] agora aparece no [!UICONTROL Menu principal] para quem não têm um modelo de layout. Os quadros também são incluídos no Menu principal por padrão em qualquer novo modelo de layout criado. Os modelos de layout existentes não foram alterados.

**Não é possível salvar modelos de email**

_Configuração_

Quando uma pessoa tenta criar ou editar um modelo de email, o botão [!UICONTROL Salvar] não responde e não é possível salvá-lo.

+++

## Atualizações em janeiro de 2023

+++**Atualização de manutenção em 30 de janeiro de 2023**

**Atalhos de teclado adicionados para ações comuns da folha de horas**

_Folhas de horas_

Introduzimos os seguintes atalhos de teclado para as seguintes ações executadas com frequência em uma folha de horas:

* Adicionar linha (Cmd+Option++/Ctrl+Option++)
* Excluir linha (Cmd+Option+-/Ctrl+Option+-)
* Fixar ou desafixar um item de trabalho (Option+P/Option+P)
* Abrir comentário (Shift+F2/Shift+F2)
* Salvar comentário (Cmd+Enter/Ctrl+Enter)
* Expandir (Shift+Option+Seta para cima/Shift+Alt+Seta para cima)
* Recolher (Shift+Option+Seta para baixo/Shift+Alt+Seta para baixo)

A área onde essas ações serão executadas precisa estar realçada para que sejam aplicadas.

**Novos ícones de informações para folhas de horas, perfis de folha de horas e preferências de folha de horas**

_Folhas de horas_

>[!NOTE]
>
>Essa atualização foi lançada apenas no ambiente de Visualização em 3 de novembro de 2022 e agora está disponível na Produção.

Adicionamos vários ícones de informações às seguintes configurações:

* Caixa de seleção “[!UICONTROL Pode editar horas]” ao criar ou editar uma folha de horas ou um perfil de folha de horas para indicar que, quando ativado, os aprovadores também podem enviar, reabrir ou editar a folha de horas, a menos que o administrador restrinja essas ações na área [!UICONTROL Preferências da folha de horas] da [!UICONTROL Configuração].
* “[!UICONTROL Restringir a edição da folha de horas a proprietários e administradores]” na área [!UICONTROL Folha de horas e preferências de hora] da [!UICONTROL Configuração] para indicar que, quando desativado, os usuários a seguir também podem editar as folhas de horas: usuários com acesso administrativo a folhas de horas, aprovadores de folha de horas com permissão para editar hora e gerentes de proprietários de folha de horas.

Observe que a funcionalidade dessas configurações não foi alterada e somente os ícones de informações foram adicionados para esclarecer o escopo das configurações.

+++

+++**Atualização de manutenção em 26 de janeiro de 2023**

**Erro ao enviar solicitação a partir do [!DNL Outlook]**

_Integrações_

Quando uma pessoa tenta enviar uma solicitação com anexos a partir de um email do [!DNL Outlook], um ou mais anexos não são enviados e o seguinte erro é exibido:

“[!UICONTROL Ocorreu o seguinte erro: o arquivo com o identificador xxxx não existe.]”

Isso ocorre somente quando uma atribuição é feita para a nova solicitação, seja por meio da fila de solicitações ou manualmente ao criar a solicitação.

**Nova versão do Visualizador de prova para desktop**

_Prova_

Para corrigir um problema de congelamento no Visualizador de prova para desktop, implantamos uma nova versão do visualizador. As pessoas que já tiverem o Visualizador de prova para desktop instalado receberão esta atualização automaticamente.

Os usuários também podem baixar manualmente a versão mais recente. Para obter mais informações, consulte [Instalar o Visualizador de prova para desktop](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=pt-BR).

* Versão anterior: 2.1.19
* Nova versão: 2.1.20

**Não é possível editar configurações pessoais**

_Usuários_

Quando um usuário que possui uma licença de Trabalho, Revisão ou Solicitação tenta editar suas próprias configurações, a janela pop-up é aberta em branco e não permite fazer edições. Para sair da janela pop-up, é necessário atualizar a página.

+++

+++**Atualização de manutenção em 19 de janeiro de 2023**

**Agora, os filtros da coluna de entrada podem ser compartilhados**

_Quadros_

Quando o recurso da coluna de entrada foi lançado para Quadros, os filtros de configuração da coluna de entrada só podiam ser vistos pela pessoa que os criou. Agora, o(a) criador(a) pode compartilhar os filtros com outros usuários ou equipes.

**A funcionalidade Fixar está disponível no menu [!UICONTROL Mais]**

_Navegação_

Os seguintes recursos para marcadores agora estão disponíveis no menu [!UICONTROL Mais] do ambiente de produção:

* Renomear marcadores
* Reorganização de marcadores no menu [!UICONTROL Mais]
* Ao mover um marcador para fora do menu [!UICONTROL Mais], o último marcador na barra de navegação superior é movido para o menu [!UICONTROL Mais]

+++

+++**Atualização de manutenção em 18 de janeiro de 2023**

**Expressões com curingas não são válidas em campos personalizados**

_Formulários personalizados_

Ao utilizar um curinga, como \$$TODAY ou $$NOW, juntamente com um modificador (como “-30d”) em um campo personalizado, o validador não aceita o curinga como válido. Curingas sem modificadores são vistos como válidos.

O **[!UICONTROL Balanceador de carga de trabalho] mostra horas não associadas a um projeto/tarefa/problema**

_[!UICONTROL Balanceador de carga de trabalho]_

Ao consultar o [!UICONTROL Balanceador de carga de trabalho], é possível ver horas registradas para um usuário que não estão associadas a nenhum projeto, tarefa ou problema, e que não estão registradas como horas [!UICONTROL Gerais]. Essas horas são exibidas somente na visualização de 4 ou 6 semanas.

+++

+++Atualização de manutenção do **[!DNL Adobe Workfront Fusion] (hot fix) em 12 de janeiro de 2023**

**Erros 404 em módulos do [!DNL Workfront]**

_Workfront Fusion_

Quando um cenário é executado, um módulo do [!DNL Workfront] retorna um erro 404.

Esse problema foi relatado nos seguintes módulos:

* [!UICONTROL Ler um registro]

+++

+++**Atualização de manutenção (hot fix) em 12 de janeiro de 2023**

**Erro “[!UICONTROL Ops!]” ao configurar um campo calculado**

_Formulários personalizados_

Ao criar ou editar um campo calculado em um formulário personalizado e incluir um campo personalizado na expressão do campo calculado, a expressão é considerada inválida. O botão [!UICONTROL Salvar] é desabilitado e não é possível sair do campo personalizado. Além disso, a seguinte mensagem é exibida abaixo do campo:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Remover o campo personalizado da expressão permite salvar e sair do campo.

**Não é possível definir níveis de acesso**

_Usuários_

Ao tentar alterar o nível de acesso de outro usuário, os níveis de acesso ficam esmaecidos e não é possível alterá-los. Isso ocorre mesmo quando a pessoa que está tentando realizar a alteração é um(a) admin do sistema.

+++

+++**Atualização de manutenção em 12 de janeiro de 2023**

**Os comandos Ctrl+F ou Cmd+F não funcionam como esperado em campos suspensos**

_Formulários personalizados_

Durante o preenchimento de um formulário personalizado, se você realizar uma pesquisa em uma lista suspensa usando Ctrl+F ou Cmd+F e, em seguida, tentar pular para a próxima instância dessa pesquisa, a lista suspensa retornará ao topo da lista. Isso ocorre quando uma lista suspensa é definida para permitir várias seleções.

A tela **[!UICONTROL Editar relatório] está em branco**

_Relatórios_

Ao visualizar um relatório e tentar editá-lo, uma tela em branco é exibida e não é possível editar o relatório.

**As tarefas recuadas não permanecem recuadas**

_Tarefas_

Ao visualizar uma lista de tarefas e recuar uma tarefa, ela retorna imediatamente ao seu estado original (recuado à esquerda).

+++

+++**Atualização de manutenção em 5 de janeiro de 2023**

**A funcionalidade Fixar está disponível no menu [!UICONTROL Mais]**

_Navegação_

Os seguintes recursos para marcadores agora estão disponíveis no menu [!UICONTROL Mais], apenas no ambiente de visualização:

* Renomear marcadores
* Reorganização de marcadores no menu [!UICONTROL Mais]
* Ao mover um marcador para fora do menu [!UICONTROL Mais], o último marcador na barra de navegação superior é movido para o menu [!UICONTROL Mais]

**Remoção da limitação do grupo do projeto ao adicionar usuários à equipe do projeto**

_Equipes_

Removemos a limitação que exigia que os usuários adicionados a uma equipe de projeto estivessem no grupo associado ao projeto. Agora, é possível adicionar qualquer usuário ativo a uma equipe de projeto, independentemente dos grupos aos quais ele(a) pertence.

**Novos ícones de informações, perfis e preferências para a folha de horas**

>[!NOTE]
>
>Essa atualização foi lançada no ambiente de visualização em 3 de novembro de 2022 e agora está disponível na produção

_Workfront_

Adicionamos vários ícones de informações às seguintes configurações:

* A caixa de seleção “Permitir edição de horas” ao criar ou editar uma folha de horas ou um perfil de folha de horas para indicar que (quando habilitada) aprovadores(as) também podem enviar, reabrir ou editar a folha de horas, a menos que um(a) admin restrinja essas ações na área Preferências da configuração da folha de horas.
* A opção “Restringir a edição da folha de horas a proprietários(as) e admins” na folha de horas e nas Preferências de hora da área de configuração para indicar que (quando habilitada) os usuários a seguir também podem editar as folhas de horas: usuários com acesso administrativo a folhas de horas, aprovadores(as) de folha de horas com permissão para editar horas e gerentes de proprietários(as) de folha de horas.

Observe que a funcionalidade dessas configurações não foi alterada e os ícones de informações só foram adicionados para esclarecer o escopo das configurações.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2022](2022-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2021](2021-updates.md)
