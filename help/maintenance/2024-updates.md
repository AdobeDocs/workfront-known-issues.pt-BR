---
title: Atualizações de manutenção do Workfront em 2024
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
feature: Get Started with Workfront
source-git-commit: 1a3bb95b27fb660011ac4b0380eb599f77319c2f
workflow-type: tm+mt
source-wordcount: '7353'
ht-degree: 80%

---

# Atualizações de manutenção do [!DNL Workfront]

>[!NOTE]
>
>Para obter informações sobre interrupções de manutenção para todos os produtos Adobe, incluindo o Workfront, consulte a [página Status da Adobe](https://status.adobe.com/).

Esta página descreve os problemas corrigidos nas atualizações semanais do Workfront.

Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2024, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

As seguintes atualizações de manutenção foram efetuadas em 2024.

## Atualizações em dezembro de 2024

+++**Atualização de manutenção em sexta-feira, 19 de dezembro de 2024**

### Atualização de manutenção em 19 de dezembro de 2024

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 12 de dezembro de 2024**

### Atualização de manutenção em 12 de dezembro de 2024

#### Painéis

**A coluna desaparece quando usada para classificação em um relatório de painel**

Ao classificar um relatório colocado em um painel por uma coluna, ela desaparece e o conteúdo não é classificado.

#### Relatórios

**A coluna do grupo sob a opção de gráfico causa um erro**

Ao ativar a opção &quot;Group column under chart&quot; em um relatório com um gráfico, a seguinte mensagem de erro é exibida: &quot;Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.“

**Ícones de Edição e Exclusão em Massa ausentes nos relatórios**

Ao tentar editar ou excluir vários itens de relatório em massa, os ícones Editar e Excluir ocasionalmente não são exibidos.

**Erros nos relatórios do Projeto (Dados Financeiros)**

Um erro aparece intermitentemente nos relatórios do Projeto (Dados financeiros), tanto na página de detalhes quanto na página de matriz.

Como parte da correção desse problema, os projetos neste tipo de relatório não são mais recalculados automaticamente antes do carregamento dos dados. Os usuários devem recalcular manualmente as finanças de projetos individuais para atualizar os dados em um relatório de dados financeiros.

+++

+++**Atualização de manutenção em sexta-feira, 5 de dezembro de 2024**

### Atualização de manutenção em 5 de dezembro de 2024

#### Formulários personalizados

**Não é possível adicionar os campos de tarefa &quot;estimateByHours&quot; ou &quot;hoursPerPoint&quot;**

Quando um usuário tenta adicionar os campos &quot;estimateByHours&quot; ou &quot;hoursPerPoint&quot; a um formulário personalizado no construtor de formulários, uma mensagem de erro é exibida: &quot;Esta expressão personalizada é inválida. Tente novamente&quot;.

**A lógica de exibição não funciona em formulários personalizados**

Quando um usuário insere informações em um formulário personalizado com lógica de exibição, os campos que devem aparecer com base na lógica de exibição não aparecem.

#### Início

**Os contribuidores exibiram o botão &quot;Trabalhar nisto&quot; não funcional**

Os usuários do Colaborador têm acesso a um botão &quot;Trabalhar nisso&quot; não funcional no widget Meu trabalho na Página inicial.

#### Relatórios

**Trimestres personalizados não aparecem nos prompts do relatório**

Quando um usuário está executando um relatório com um prompt baseado em data, trimestres personalizados não aparecem na lista de seleções do prompt.

+++

## Atualizações em novembro de 2024

+++**Atualização de manutenção em sexta-feira, 28 de novembro de 2024**

### Atualização de manutenção em 28 de novembro de 2024

#### Projetos

**Não é possível compartilhar projetos devido ao erro &quot;acesso para excluir&quot;**

Ao tentar compartilhar um projeto, o usuário recebe um erro: &quot;Você não tem acesso suficiente para excluir este projeto&quot;. Isso ocorre mesmo que o usuário não tente excluir o projeto, assim como o usuário que é o Proprietário do projeto e tem acesso ao Compartilhamento e Gerenciamento.

#### Relatórios

O campo **Nome da Categoria não está vinculado ao formulário personalizado**

Ao visualizar uma lista em um relatório contendo um campo Nome da categoria, o conteúdo da coluna Nome da categoria não pode ser clicado para abrir o formulário personalizado correspondente.

**Cores personalizadas do grupo em relatórios que não funcionam**

Ao atribuir uma cor personalizada a um grupo no Report Builder, a seleção de cores não aparece ao executar o relatório.

**Longos tempos de carregamento para relatórios**

Os relatórios demoram muito para serem carregados. Isso afeta a exibição de relatórios, bem como a edição e criação de relatórios no construtor de relatórios.

**Campo de hora ausente para campos de data/hora calculados em prompts de relatório**

Quando um relatório é executado, um campo Data/Hora personalizado é usado como um prompt e o campo de seleção de hora não aparece na interface do prompt.

**Não é possível exibir relatórios/painéis compartilhados**

Quando um usuário tenta acessar um relatório ou painel que foi compartilhado com ele, o relatório ou painel não pode ser acessado.

#### Planilhas de horas

**Os usuários do colaborador têm o botão &quot;Enviar para aprovação&quot;**

Embora não seja possível inserir horas em folhas de horas, os usuários com nível de acesso de Colaborador têm um botão &quot;Enviar para aprovação&quot; que podem clicar.

+++

+++**Atualização de manutenção em sexta-feira, 21 de novembro de 2024**

### Atualização de manutenção em 21 de novembro de 2024

#### Painéis

**Não é possível interagir com as barras de relatório do gráfico de barras nos painéis**

Ao tentar clicar ou passar o mouse sobre uma barra em um relatório de gráfico de barras em um painel, o menu de detalhes não abre ou nenhuma dica de ferramenta é exibida, respectivamente.

#### Projetos

**Falha ao carregar os projetos**

Ao navegar para um projeto, a página ocasionalmente falha ao carregar qualquer conteúdo.

#### Relatórios

**A edição em massa nas listas de gráficos não responde**

Quando um usuário visualiza um gráfico em um relatório e seleciona vários itens na lista para edição em massa, o cursor desaparece e as caixas de texto para a edição em massa ficam sem resposta.

**Botões Editar e Excluir sem resposta nos relatórios de folha de horas**

Ao tentar clicar nos ícones Editar ou Excluir em um relatório de folha de horas, não há resposta.

**Falha ao carregar relatórios contendo campos de digitação antecipada**

Ao abrir um relatório que contém campos de digitação antecipada personalizados, o relatório ocasionalmente não é carregado e exibe uma mensagem de erro.

+++

+++**Atualização de manutenção em sexta-feira, 14 de novembro de 2024**

### Atualização de manutenção em 14 de novembro de 2024

#### Início

**Erros de itens por- fazer para os itens por- fazer novos e concluídos**

Ao tentar criar uma nova tarefa ou concluir uma tarefa existente no widget Página inicial da tarefa, os usuários encontram um erro e não podem criar ou concluir a tarefa.

#### Usuários

**Caixa de seleção &quot;Enviar emails de convite para essas pessoas&quot; ausente**

Ao importar novos usuários para o Workfront, a caixa de seleção &quot;Enviar emails de convite para essas pessoas&quot; não aparece na janela de diálogo.

+++

+++**Atualização de manutenção em sexta-feira, 7 de novembro de 2024**

### Atualização de manutenção em 7 de novembro de 2024

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

## Atualizações em outubro de 2024

+++**Atualização de manutenção em sexta-feira, 31 de outubro de 2024**

### Atualização de manutenção em 31 de outubro de 2024

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 24 de outubro de 2024**

### Atualização de manutenção em 24 de outubro de 2024

#### Atribuições

**O ícone de folga não aparece ao atribuir tarefas**

Quando um usuário atribui uma tarefa e começa a digitar o nome do designado que tem folga programada durante a tarefa, os ícones de usuário na área Atribuições sugeridas não exibem o ícone de folga (avião). Se o usuário continuar digitando para que o nome seja exibido na área de usuários e equipes, o ícone não será exibido.

#### Formulários personalizados

**Não é possível atualizar dados personalizados em projetos concluídos**

Quando um usuário tenta atualizar dados personalizados em um projeto concluído, não é possível atualizar os dados e é exibida a seguinte mensagem:

&quot;Não é possível concluir a operação de um projeto com o status Concluído.&quot;

#### Projetos

**Não é possível adicionar problemas ao projeto concluído**

Quando um usuário tenta adicionar um problema a um projeto com o status Concluído, ele não consegue adicionar o problema. Isso pode ocorrer mesmo se a opção &quot;Adicionar e editar problemas&quot; estiver ativada

**O gráfico de Gantt não é preciso**

Quando um usuário visualiza o Gráfico de Gantt e alterna as visualizações, o Gráfico de Gantt não mostra dados precisos ou não mostra dados.

+++

+++**Atualização de manutenção em sexta-feira, 17 de outubro de 2024**

### Atualização de manutenção em 17 de outubro de 2024

#### Provas

**Provas mostram data imprecisa**

As datas listadas na lista de documentos estão mostrando a data em que a primeira versão do documento foi criada, em vez da data em que a versão mais recente foi criada.

#### Planilhas de horas

Quando um usuário tenta registrar as horas em uma folha de horas com status Enviado ou Fechado, não é possível registrar as horas.

Esse é o comportamento esperado e não deve ser considerado um problema.

Anteriormente, os usuários podiam registrar horas em folhas de horas enviadas ou fechadas por meio da API do Workfront ou do Workfront Fusion.

+++

+++**Atualização de manutenção em sexta-feira, 10 de outubro de 2024**

### Atualização de manutenção em 10 de outubro de 2024

#### Quadros

**Erro ao mover cartões ou atribuir usuários**

Ao mover cartões ou atribuir usuários, ocasionalmente a ação não prossegue e, em vez disso, produz o erro &quot;Resposta não bem-sucedida: Código de status recebido 502&quot; após um atraso.

**Erro ao carregar um quadro**

Não é possível carregar um quadro, e a seguinte mensagem aparece.

&quot;Erro ao carregar o quadro&quot;

&quot;Algo deu errado ao carregar este quadro. Atualize a página e tente novamente ou entre em contato com o suporte com a ID de erro abaixo se o problema persistir.&quot;

#### Início

**&quot;Marcar como Concluído&quot; fecha o painel de resumo do widget Meus Problemas**

Ao tentar usar o botão &quot;Marcar como concluído&quot; no painel de resumo de um problema aberto pelo widget Meus problemas, o painel de resumo é fechado inesperadamente.

**As configurações do widget Modelo de layout não adicionam a coluna**

Ao selecionar um campo para adicionar a um widget por meio das configurações do widget Modelo de layout, um campo pode ser selecionado, mas a coluna correspondente não aparece no widget.

#### Tarefas

**Problemas com o recálculo da linha de tempo**

Os seguintes problemas foram relatados em relação ao recálculo da linha do tempo:

* Ao atualizar a duração de uma tarefa na linha do tempo, o sistema demora bastante para recalcular.
* Quando o recálculo é concluído, as datas podem ser (ou permanecer) desabilitadas, como se a linha do tempo ainda estivesse sendo recalculada.

**Despesas de tarefa não exibidas**

Depois de adicionar uma despesa a uma tarefa, a despesa não aparece nas informações da tarefa apesar da confirmação da API de que foi inserida.

+++

+++**Atualização de manutenção em sexta-feira, 3 de outubro de 2024**

### Atualização de manutenção em 3 de outubro de 2024

#### Quadros

**Cartões conectados arquivados não sincronizados**

Para solucionar problemas de desempenho, os cartões conectados que são arquivados não são mais sincronizados. As alterações feitas na tarefa ou problema do Workfront não são refletidas nos cartões arquivados. Se você restaurar um cartão, ele será sincronizado novamente.

#### Formulários personalizados

**Exibir erro de conversões de tipo em formulários personalizados**

Campos de rich text fazem com que apareça o seguinte erro em formulários personalizados:

“Erro: não são permitidas conversões de Tipo de exibição entre texto e rich text.”

Isso pode ocorrer nas seguintes circunstâncias:

* A pessoa começa a editar os formulários, mas clica em Aplicar sem fazer alterações.
* A pessoa está criando um formulário personalizado.

Em ambos os casos, campos de rich text estão causando os problemas.

#### Notificações

**Os usuários do colaborador não recebem notificações por email**

Os usuários com licença de colaborador não estão recebendo emails de notificação. Isso pode afetar os emails de notificação instantânea e os emails de resumo diário.

#### Provas

**Assinaturas eletrônicas não podem ser adicionadas ao usar SSO para Prova**

Ao usar o SSO para fazer logon no Proof, os usuários não podem definir uma prova para exigir assinaturas eletrônicas.

+++

## Atualizações em setembro de 2024

+++**Atualização de manutenção em sexta-feira, 26 de setembro de 2024**

### Atualização de manutenção em sexta-feira, 26 de setembro de 2024

#### Ágil

**A opção Adicionar à iteração é listada duas vezes ao atribuir a equipe de scrum**

Ao atribuir uma tarefa ou problema a uma equipe ágil de scrum, a opção “Adicionar à iteração” aparece duas vezes no menu Mais. Isso não afeta a capacidade de atribuir a equipe e não aparece para equipes ágeis sem scrum.

#### Formulários personalizados

**Lista de campos do Editor de Cálculo limitada a 200 itens**

No Editor de cálculo para campos calculados em formulários personalizados, a lista de campos de um objeto agora está limitada a 200 itens para melhorar o desempenho do sistema. Se você souber o nome do campo, poderá pesquisá-lo usando a opção de digitação antecipada em vez de rolar pela lista.

#### Relatórios

**As entregas de relatórios estão atrasadas ou ausentes**

Os relatórios com entregas programadas não são entregues conforme o esperado. As entregas podem atrasar ou até mesmo não ser realizadas.

+++

+++**Atualização de manutenção em sexta-feira, 19 de setembro de 2024**

### Atualização de manutenção em sexta-feira, 19 de setembro de 2024

#### Painéis

**Selecionar o botão Exportar em um relatório rola para a parte superior da página**

Ao clicar no botão Exportar em um relatório de um painel, a janela rola para a parte superior da página, exigindo a rolagem para baixo para chegar ao menu de opções de exportação aberto.

+++

+++**Atualização de manutenção em sexta-feira, 12 de setembro de 2024**

### Atualização de manutenção em sexta-feira, 12 de setembro de 2024

#### Integrações

**Erro ao criar uma solicitação do Outlook**

Quando uma pessoa tenta criar uma solicitação do Workfront para integração com o Outlook e adiciona um anexo, Ela vê a mensagem: “Algo deu errado. Tente novamente mais tarde.”

A solicitação é criada e há uma pasta para anexos de email na solicitação, mas a pasta fica vazia e o anexo não é adicionado à solicitação.

+++

+++**Atualização de manutenção em sexta-feira, 5 de setembro de 2024**

### Atualização de manutenção em 5 de setembro de 2024

#### Grupos

**Os subgrupos não são exibidos corretamente**

Quando uma pessoa visualiza a lista “Grupos” na área “Configuração”, ela vê que os subgrupos não estão listados corretamente no grupo principal. O subgrupo é salvo corretamente no grupo principal, mas a lista pode causar confusão.

Se a pessoa abrir o subgrupo, verá na navegação estrutural que o subgrupo foi salvo corretamente no grupo principal.

#### Usuários

**Não é possível reativar um usuário**

Quando alguém tenta reativar um usuário usando a opção “Reativar usuário” no menu “Mais”, é possível selecionar um nível de acesso para o usuário, mas a alteração não é salva. Em vez disso, o seguinte erro é exibido:

“O homeGroupID não pode ser nulo”

+++

## Atualizações em agosto de 2024

+++**Atualização de manutenção em sexta-feira, 29 de agosto de 2024**

### Atualização de manutenção em sexta-feira, 29 de agosto de 2024

#### Formulários personalizados

**Os formulários retornam ao padrão, os formulários do projeto**

Quando alguém cria um formulário personalizado e seleciona um tipo de objeto para ele, o tipo de objeto é ignorado e o formulário é criado como um formulário de projeto personalizado.

#### Documentos

**Clicar no nome de um documento abre uma página em branco**

Ao tentar ver detalhes do documento clicando no nome dele em uma lista de documentos, ela desaparece e os detalhes não são exibidos.

#### Início

**O widget de aprovações pendentes mostra documentos excluídos**

Quando uma pessoa visualiza o dispositivo Aprovações pendentes da Página inicial, documentos que foram excluídos são exibidos. Se a pessoa clicar em um desses documentos, será direcionada a uma página em branco.

#### Usuários

**O campo “Localidade do email” do perfil do usuário foi desabilitado**

Para organizações no IMS, as preferências de idioma são armazenadas no perfil de cada usuário da Adobe Experience Cloud. O campo “Local do email” no perfil do usuário do Workfront foi desabilitado (somente para organizações do IMS), e uma dica de ferramenta nesse campo fornece instruções para acessar as configurações de idioma no perfil da Adobe.

Isso aborda o problema de quando um administrador tenta alterar a configuração da localidade do email para um usuário, mas ela é revertida para inglês.

+++

+++**Atualização de manutenção em sexta-feira, 22 de agosto de 2024**

### Atualização de manutenção em sexta-feira, 22 de agosto de 2024

#### Relatórios

**Não é possível clicar em um relatório da área Campos personalizados da Configuração**

Quando uma pessoa está visualizando a área Formulários personalizados > Campos, da configuração, e a exibição inclui o campo Relatórios nativo, os links para os relatórios não funcionam. A pessoa deveria ser capaz de clicar no nome de um relatório e ser direcionado a ele, mas isso não funciona.

+++

+++**Atualização de manutenção em sexta-feira, 15 de agosto de 2024**

### Atualização de manutenção em sexta-feira, 15 de agosto de 2024

#### Quadros

**Problemas relacionados a cartões duplicados**

Os seguintes problemas foram relatados em relação a cartões duplicados em Quadros:

* Um cartão é exibido duas vezes. Isso pode ser resolvido atualizando a página.
* Se você excluir um dos cartões duplicados, todas as instâncias desse cartão duplicado serão excluídas.

#### Notificações

**Erro ao definir as preferências de notificação**

O seguinte erro ocorre ao tentar exibir as preferências de notificação:

“[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Esse problema foi relatado nas seguintes áreas:

* Configurações de notificação em um perfil de usuário
* Área de notificações de eventos em Configuração

#### Projetos

**O símbolo de moeda está incorreto ao exportar**

Ao exportar um problema, o símbolo de moeda da exportação não corresponde à moeda definida no projeto ou no problema.

#### Provas

**Marcações de prova imprecisas**

As marcações de prova estão desalinhadas nas impressões de PDF recebidas por email do recurso Impressão de prova.


+++

+++**Atualização de manutenção em sexta-feira, 8 de agosto de 2024**

### Atualização de manutenção em 8 de agosto de 2024

#### Quadros

**O cartão não inclui subtarefas**

Quando uma pessoa visualiza um cartão de uma tarefa que é uma tarefa principal, suas subtarefas não são exibidas no cartão. Em vez disso, o cartão mostra que há 0 subtarefas.

### Relatórios

**As entregas de relatórios estão atrasadas ou ausentes**

Os relatórios com entregas programadas não são entregues conforme o esperado. As entregas podem atrasar ou até mesmo não ser realizadas.

#### Configuração

**A opção “Fazer logon como” abre uma tela em branco**

Quando um(a) admin faz logon como outro usuário, uma tela em branco aparece em vez da conta desse usuário.

+++

+++**Atualização de manutenção em sexta-feira, 1 de agosto de 2024**

### Atualização de manutenção em 1º de agosto de 2024

#### Documentos

**Não é possível criar uma exibição para a lista Documentos**

Quando uma pessoa tenta criar uma nova exibição em uma lista Documentos, a tela fica em branco e não é possível criar a exibição.

As exibições já existentes funcionam conforme esperado.

#### Integrações

**Problemas com a integração com o Dropbox**

Os seguintes problemas foram relatados em relação à integração com o Dropbox:

* Ao tentar procurar um arquivo no seletor de arquivos do Dropbox, uma mensagem de erro de autorização é exibida e o seletor de arquivos não recupera o arquivo do Dropbox.
* Ao tentar abrir uma pasta vinculada, a pessoa vê um erro informando que os arquivos ou a pasta não existem mais no Dropbox.

Esses erros ocorrem devido a problemas com o Dropbox, não com o Workfront.

+++

## Atualizações em julho de 2024

+++**Atualização de manutenção em sexta-feira, 25 de julho de 2024**

### Atualização de manutenção em sexta-feira, 25 de julho de 2024

#### Formulários personalizados

**A lista suspensa se fecha ao selecionar vários valores**

Ao tentar selecionar vários valores em um campo de formulário personalizado, a lista suspensa se fecha após selecionar o primeiro valor.

Isso ocorre quando o campo é associado à lógica de exibição no formulário personalizado.

#### Notificações

**As miniaturas não ficam visíveis nas notificações por email**

Quando uma pessoa visualiza uma notificação por email relacionada a uma aprovação de documento, a miniatura do documento não fica visível no email.

Esse problema foi relatado no Gmail.

+++

+++**Atualização de manutenção em sexta-feira, 18 de julho de 2024**

### Atualização de manutenção em sexta-feira, 18 de julho de 2024

#### Ágil

**O storyboard fica em branco ao adicionar uma subtarefa**

Quando uma pessoa tenta adicionar uma subtarefa a um storyboard enquanto um filtro está selecionado, a tela fica em branco e não é possível adicionar a subtarefa.

#### Início

**Não é possível abrir itens a partir do [!UICONTROL calendário da página inicial] ou da [!UICONTROL lista de trabalho]**

Quando uma pessoa tenta abrir um item de trabalho ou uma prova do [!UICONTROL Calendário da página inicial] ou da [!UICONTROL Lista de trabalho da página inicial], o item não abre.

**A página inicial de admins aparece ao se conectar como outro usuário**

Quando um(a) admin faz logon como outro usuário e visualiza a página inicial desse usuário, a página inicial de admins é exibida.

#### Provas

**Fechar uma prova leva à página “Documentos do produto”**

Quando uma pessoa que está visualizando uma prova a fecha, ela é direcionada para a página Documentos do projeto, em vez de a página na qual a prova foi aberta.

#### Workfront

**A terminologia personalizada não é aplicada**

A terminologia personalizada definida no modelo de layout não aparece em algumas áreas do Workfront. Em vez disso, a terminologia padrão não personalizada é exibida.

Esse problema foi relatado nas seguintes áreas:

* Guias Menu
* Cabeçalhos de página
* Descrições onde os projetos são listados


+++

+++**Atualização de manutenção em sexta-feira, 11 de julho de 2024**

### Atualização de manutenção em 11 de julho de 2024

#### Problemas

**Erro ao fazer uma atribuição avançada a um problema**

Quando uma pessoa tenta fazer uma atribuição avançada a um problema no Workfront, o problema não é atribuído e a seguinte mensagem de erro é exibida:

“[!UICONTROL APIModel INTERNAL não oferece suporte à duração de campo (OpTask)]”

#### Relatórios

**Erro ao definir configurações de matriz no relatório de Horas**

Ao tentar definir as configurações de matriz em um relatório de Horas, a pessoa não consegue definir as configurações e o seguinte erro é exibido:

* “[!UICONTROL Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”


+++

+++**Atualização de manutenção em sexta-feira, 4 de julho de 2024**

### Atualização de manutenção em 4 de julho de 2024

#### Início

**O menu de três pontos não funciona**

Quando uma pessoa clica no menu de três pontos Mais na Lista de trabalho da Página inicial herdada, nenhuma ação é acionada.

#### Relatórios

**“Nenhum dado para exibir” quando o nome do agrupamento tem uma barra ou uma barra invertida**

Quando alguém visualiza um gráfico em um relatório, clica em um agrupamento no gráfico e esse agrupamento tem / ou \ no nome, os detalhes que abrem não exibem os itens no agrupamento e a pessoa vê uma mensagem “Nenhum dado para exibir”.

#### Tarefas

**A função de trabalho não desaparece da lista quando alguém é atribuído à tarefa**

Quando uma função de trabalho é atribuída a uma tarefa e essa tarefa é atribuída a um usuário que tem a função de trabalho, a função de trabalho não desaparece da lista de atribuições.


+++

## Atualizações em junho de 2024

+++**Atualização de manutenção em sexta-feira, 27 de junho de 2024**

### Atualização de manutenção em sexta-feira, 27 de junho de 2024

#### Quadros

**Somente o proprietário do quadro pode atualizar os filtros de configuração**

Por motivos de segurança, somente o proprietário de um quadro pode alterar os filtros do quadro no painel Configurar.

#### Relatórios

**O relatório não é carregado quando a moeda padrão é USD**

Quando alguém tenta visualizar um relatório que tem a moeda padrão como USD, o relatório não carrega.

#### Atualizações

**O link copiado não é colado corretamente**

Se alguém copiar um link de uma atualização ao clicar com o botão direito do mouse e selecionar “[!UICONTROL Copiar endereço do link]” e, logo após, colar o link em uma atualização, o link não será colado corretamente. Somente a primeira parte do link é um link e o restante do URL é ignorado.

Copiar o link usando um método diferente de “[!UICONTROL Copiar endereço do link]” permite que o link seja colado da maneira correta.

+++

+++**Atualização de manutenção em sexta-feira, 20 de junho de 2024**

### Atualização de manutenção em sexta-feira, 20 de junho de 2024

#### Navegação

**O botão Voltar não retorna à página anterior**

Quando se clica no botão Voltar do navegador no Workfront, uma das situações a seguir pode ocorrer.

* O nome da guia do navegador é alterado, mas a página não é alterada. Clicar no botão Voltar novamente pode resolver o problema.
* A pessoa é direcionada para sua página de destino no navegador.

#### Provas

**Não é possível fechar o visualizador de provas**

Quando alguém visualiza uma prova no visualizador de provas e tenta fechá-la clicando em X no canto superior direito, a prova não é fechada.

+++

+++**Atualização de manutenção em sexta-feira, 13 de junho de 2024**

### **Atualização de manutenção em sexta-feira, 13 de junho de 2024**

#### Grupos

**Não é possível adicionar subgrupo**

Quando alguém tenta adicionar um subgrupo já existente a um grupo, o botão Salvar não funciona e o subgrupo não é adicionado.

+++

+++ **Atualização de manutenção em 6 de junho de 2024**

### Atualização de manutenção em 6 de junho de 2024

#### Formulários personalizados

**Limitação em campos nativos no designer de formulários**

Agora há suporte para vários campos nativos em formulários personalizados criados no designer de formulários. Anteriormente, o limite era de um campo nativo por formulário.

+++

## Atualizações em maio de 2024

+++ **Atualização de manutenção em 30 de maio de 2024**

### Atualização de manutenção em 30 de maio de 2024

#### Formulários personalizados

Erro ao editar campos de texto descritivo

Quando uma pessoa tenta editar o texto descritivo em um formulário personalizado, o texto não é salvo e o seguinte erro é exibido:

“Valor de chave duplicada viola restrição exclusiva”

Esse problema foi relatado no construtor de formulários legado.

#### Atualizações

**Copiar e colar uma menção não notifica a pessoa mencionada**

Quando alguém copia um comentário que inclui uma menção no formato @ e o cola na área de atualizações de outro objeto, o usuário mencionado não é notificado sobre o comentário colado.

+++

+++ **Atualização de manutenção em 23 de maio de 2024**

### Atualização de manutenção em 23 de maio de 2024

#### Relatórios

Quando alguém visualiza um relatório e clica no botão Voltar do navegador, uma das situações a seguir pode ocorrer:

* A pessoa permanece na página Relatório.
* A pessoa é direcionada para a página de destino do navegador.
* A pessoa é direcionada para a página de logon.

Esse problema foi relatado com o navegador Chrome.

#### Atualizações

**Pessoas marcadas não conseguem ver quem as marcou**

Quando alguém recebe uma marcação em uma atualização, a pessoa não consegue ver quem a marcou. Isso ocorre quando a configuração “As pessoas em outras empresas devem ver somente os usuários de...” está definida como “A empresa deles”.

**A ação de marcar alguém com @ no painel Resumo não funciona**

Ao tentar marcar alguém usando @ na área de atualizações de um painel Resumo, clicar no nome da pessoa na lista suspensa não gera efeito. Tentar marcar a pessoa uma segunda vez funciona conforme o esperado.

+++

+++**Atualização de manutenção em 16 de maio de 2024**

### Atualização de manutenção em 16 de maio de 2024

#### Configuração

**Status de problemas padrão ausentes em alguns tipos de problemas na configuração**

Quando uma pessoa visualiza os status de problemas na Configuração, ela verá que os status padrão para problemas (Novo, Em andamento e Concluído) estão ausentes em alguns tipos de problemas. Os status padrão não têm a opção para alterar o tipo de problema, portanto, a pessoa não pode reconfigurar os status para serem exibidos para os tipos de problema afetados.

#### Usuários

**Não é possível excluir usuários**

Quando uma pessoa tenta excluir usuários, eles não são excluídos. Esse problema foi relatado em organizações que migraram para o Adobe Admin Console.

+++

+++**Atualização de manutenção em 9 de maio de 2024**

### Atualização de manutenção em 9 de maio de 2024

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++**Atualização de manutenção em 2 de maio de 2024**

### Atualização de manutenção em 2 de maio de 2024

#### Registro de hora

**Não é possível editar horas em tarefas ou problemas**

Quando um usuário tenta editar horas em uma tarefa ou problema, as alterações não são salvas.

+++

## Atualizações em abril de 2024

+++**Atualização de manutenção em 25 de abril de 2024**

### Atualização de manutenção em 25 de abril de 2024

#### Atualizações

**As listas numeradas não ficam numeradas corretamente**

Quando uma pessoa envia um comentário que inclui uma lista numerada, essa lista mostra uma numeração incorreta na atualização.

Esse problema foi relatado na nova experiência de comentários.

**O texto não é preservado ao sair e voltar para o comentário**

Quando um usuário está escrevendo um comentário que inclui uma @mention e, em seguida, sai e volta para o comentário antes de enviá-lo, qualquer texto inserido após a @mention não aparece no rascunho do comentário.

Esse problema foi relatado na nova experiência de comentários.

+++

+++**Atualização de manutenção em 18 de abril de 2024**

### Atualização de manutenção em 18 de abril de 2024

#### Ágil

**Os cartões do Kanban não exibem campos personalizados**

Quando uma pessoa visualiza um quadro do Kanban que foi configurado para incluir campos personalizados, esses campos personalizados podem não ser exibidos.

#### Calendários

**Erro ao atualizar o calendário**

Quando um usuário visualiza um calendário e atualiza a página, um erro “Ops” é exibido. Os dados no calendário são exibidos conforme esperado, mas podem ser ocultados pela mensagem de erro.

#### Formulários personalizados

**Campos de pesquisa externa não retornam resultados**

Quando um campo de pesquisa externa faz referência a um campo de seleção múltipla que tem apenas um valor selecionado, o campo não retorna o valor.

Por exemplo, se um campo de pesquisa externa fizer referência a um campo de seleção múltipla com os valores “vermelho” e “azul” selecionados, o campo funcionará conforme esperado. Se o campo tiver apenas “vermelho” selecionado, o campo de pesquisa externa não retornará nenhum valor.

#### Projetos

**Não é possível converter um problema em um projeto se uma prova da Web estiver anexada**

Quando um problema tem uma prova da Web anexada (uma prova de URL usando um link de um provedor de documentos externo, como o SharePoint) e uma pessoa tenta converter esse problema em um projeto, a conversão falha e o projeto não é criado. O seguinte erro é exibido:

“Houve um problema ao copiar o arquivo (GUID do arquivo). Remova o arquivo ou entre em contato com o suporte e tente novamente.”

+++

+++**Atualização de manutenção em 11 de abril de 2024**

### Atualização de manutenção em 11 de abril de 2024

#### Pesquisar

**Não é possível editar a partir da pesquisa**

Quando uma pessoa está usando a Pesquisa avançada e tenta editar ou editar os resultados da pesquisa em massa, o ícone Editar não responde.

#### Atualizações

**A visualização da imagem nas atualizações está desfocada**

Quando um usuário está visualizando atualizações e clica na lupa em uma imagem para visualizá-la, a visualização aberta fica extremamente desfocada.

Se o usuário baixar a imagem, ela aparecerá na resolução esperada.

**A mensagem “[!UICONTROL Não foi possível postar o seu comentário]” aparece ao responder**

Quando um usuário tenta responder a uma mensagem na nova experiência de comentário, a resposta não é salva e o usuário vê a seguinte mensagem:

“[!UICONTROL Não é possível postar seu comentário agora. Aguarde um momento e tente novamente.]”

+++

+++**Atualização de manutenção em 4 de abril de 2024**

### Atualização de manutenção em 4 de abril de 2024

#### Pesquisar

**Não é possível editar a partir da pesquisa**

Quando uma pessoa está usando a Pesquisa avançada e tenta editar ou editar os resultados da pesquisa em massa, o ícone Editar não responde.

#### Atualizações

**A visualização da imagem nas atualizações está desfocada**

Quando um usuário está visualizando atualizações e clica na lupa em uma imagem para visualizá-la, a visualização aberta fica extremamente desfocada.

Se o usuário baixar a imagem, ela aparecerá na resolução esperada.

**A mensagem “[!UICONTROL Não foi possível postar o seu comentário]” aparece ao responder**

Quando um usuário tenta responder a uma mensagem na nova experiência de comentário, a resposta não é salva e o usuário vê a seguinte mensagem:

“[!UICONTROL Não é possível postar seu comentário agora. Aguarde um momento e tente novamente.]”

+++

+++**Atualização de manutenção em 4 de abril de 2024**

### Atualização de manutenção em 4 de abril de 2024

#### Integrações

**Documentos não anexados ao criar uma solicitação do[!DNL Outlook]**

Quando você cria uma solicitação do [!DNL Outlook], os documentos anexados ao email não são anexados à solicitação.

Esse problema foi relatado para os seguintes tipos de anexo:

XLS
PDF

#### Registro de hora

**Usuários não conseguem registrar horas para o dia atual**

Quando uma pessoa tenta registrar horas na área Atualizações, o dia atual fica esmaecido e ela não consegue registrar horas para o dia atual.

#### Atualizações

<!--no article-->

**Erro ao exibir comentários**

Quando uma pessoa tenta exibir comentários na nova experiência de comentários, ela não consegue vê-los e, em vez disso, o seguinte erro é exibido:

“Algo deu errado. Tente novamente mais tarde.”

A experiência de comentários herdada funciona conforme esperado.

+++

## Atualizações em março de 2024

+++**Atualização de manutenção em 28 de março de 2024**

### Atualização de manutenção em 28 de março de 2024

#### Integrações

**Documentos não anexados ao criar uma solicitação do[!DNL Outlook]**

Quando você cria uma solicitação do [!DNL Outlook], os documentos anexados ao email não são anexados à solicitação.

Esse problema foi relatado para os seguintes tipos de anexo:

XLS
PDF

#### Provas

**As provas permanecem no dispositivo Minhas aprovações**

Uma prova que deveria desaparecer do dispositivo Minhas aprovações permanece. Isso pode ocorrer quando várias pessoas tomam decisões sobre uma prova ao mesmo tempo ou uma pessoa toma uma decisão e a altera rapidamente.

#### Gerenciamento de recursos

**Discrepância em horas orçadas**

As horas orçadas exibidas em uma das seguintes áreas podem não corresponder àquelas exibidas em outra dessas áreas:

* Business Case
* Relatórios
* Ferramenta de orçamento de recursos

#### Tarefas

**A dica de ferramenta da tarefa predecessora não exibe o nome da tarefa**

Quando alguém está visualizando uma lista de tarefas e passa o mouse sobre um ícone predecessor para obter mais informações, a dica de ferramenta exibida não exibe o nome da tarefa predecessora.

#### Atualizações

**Comentários de documentos não aparecem em atualizações do objeto principal**

Quando uma pessoa faz um comentário em um documento, esse comentário não é exibido imediatamente na área Atualizações do objeto principal do documento.

Esse problema foi relatado na nova experiência de comentários. Os comentários aparecem na experiência de comentários herdada, conforme o esperado.

**Marcar um usuário não funciona**

Quando uma pessoa é marcada com tags em um comentário, esse comentário não fica visível para a pessoa marcada. Além disso, a pessoa também não é notificada sobre o comentário, seja por email ou por meio de uma notificação no aplicativo.

Esse problema foi relatado na experiência de comentários herdada.

+++

+++**Atualização de manutenção do Workfront Fusion em 28 de março de 2024**

### Atualização de manutenção do Workfront Fusion em 28 de março de 2024

**RuntimeError com resposta 200 do módulo Workfront**

Um módulo do Workfront pode retornar uma resposta `RuntimeError [200]`. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.

Isso pode ocorrer se a resposta for extremamente longa. Os dados são retornados ao Fusion, mas não podem ser processados por ele.

+++

+++**Atualização de manutenção em 21 de março de 2024**

### Atualização de manutenção em 21 de março de 2024

#### Atualizações

**Espaços grandes entre as linhas**

Quando uma pessoa digita uma atualização com várias linhas usando a tecla Return ou Enter, ou cola várias linhas em uma atualização, ela é exibida conforme esperado. No entanto, se alguém visualizar essas atualizações em um relatório, haverá grandes espaços entre as linhas.

Esse problema foi relatado na nova experiência de comentários.

**Marcar um usuário com @ não funciona**

Quando uma pessoa marca outra com @ em um comentário, ela não é adicionada à área de usuários marcados com tags e não recebe uma notificação sobre o comentário.

Essa correção se aplica somente à nova experiência de comentários.

+++

+++**Atualização de manutenção em 14 de março de 2024**

### Atualização de manutenção em 14 de março de 2024

#### Provas

**Provas criadas de documentos vinculados não têm o modelo de prova aplicado**

Quando uma pessoa cria uma prova de um documento vinculado, o modelo de prova não é aplicado corretamente e podem faltar informações da prova, como o fluxo de trabalho.

Isso também se aplica às provas criadas por meio da API e do Workfront Fusion.

#### Usuários

**Níveis de acesso mais baixos não disponíveis ao criar um usuário**

Quando um usuário cria outro usuário, somente o nível de acesso do primeiro usuário é disponibilizado para o usuário recém-criado. Todos os níveis de acesso com permissões inferiores às do usuário criador devem estar disponíveis para o novo usuário.

+++

+++**Atualização de manutenção em 7 de março de 2024**

### Atualização de manutenção em 7 de março de 2024

#### Quadros

**Erro 400 ao adicionar uma tarefa a um quadro**

Quando uma pessoa está visualizando um projeto e tenta adicionar uma tarefa a um quadro, a tarefa não é adicionada e o seguinte erro é exibido:

Erro: “400: undefined /boards-service/graphql”

#### Início

**Erro ao editar uma tarefa em linha no dispositivo Minha tarefa**

Quando uma pessoa tenta editar uma tarefa em linha no dispositivo Minhas tarefas, o seguinte erro é exibido:

“Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.“


#### Balanceador de carga de trabalho

**As horas planejadas não são atualizadas no Balanceador de carga de trabalho**

Quando as horas planejadas em um projeto são atualizadas, não há nenhuma alteração no Balanceador de carga de trabalho. Isso pode ocorrer mesmo que a alteração seja refletida com precisão no projeto.

+++

+++**Atualização de manutenção do Workfront Fusion em 7 de março de 2024

**Prova do Workfront > Módulo Monitorar prova atinge o tempo limite**

Os cenários que usam o módulo Workfront Proof > Monitorar prova podem ser desativados ao atingir o tempo limite do módulo Monitorar prova.

+++

## Atualizações em fevereiro de 2024

+++**Atualização de manutenção em 29 de fevereiro de 2024**

### Atualização de manutenção em 29 de fevereiro de 2024

#### Atualizações

**Atualizações: a tela fica em branco ao responder a alguém de outra empresa**

Quando você tenta responder a um comentário de alguém em outra empresa, a tela fica em branco.

Isso ocorre porque a pessoa não tem permissão para ver usuários de outras empresas.

+++

+++**Atualização de manutenção em 22 de fevereiro de 2024**

### Atualização de manutenção em 22 de fevereiro de 2024

#### Início

**[!UICONTROL Página inicial]: [!UICONTROL espaço de trabalho] e marcadores não carregam**

Quando uma pessoa faz logon, o seguinte pode ocorrer:

* O novo [!UICONTROL Espaço de trabalho inicial] não carrega e o erro “[!UICONTROL Não foi possível carregar as informações do espaço de trabalho” é exibido. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”
* Os marcadores não são carregados e o erro “[!UICONTROL Seus marcadores estão indisponíveis devido a um erro do sistema. Tente atualizar o navegador para corrigir o problema.]” é exibido.

#### Usuários

**A administração de grupo não consegue definir ou alterar o nível de acesso de usuários**

<!--no article-->

Quando um administrador de grupo tenta alterar o nível de acesso de alguém, uma das situações a seguir pode ocorrer:

* O campo de nível de acesso é desabilitado.
* A administração de grupo não pode escolher um nível de acesso mais baixo.

#### Balanceador de carga de trabalho

**Rótulo para horas não trabalhadas**

O Balanceador de carga de trabalho e o calendário de folga pessoal agora mostram “[!UICONTROL Horas não trabalhadas]” no período em que a pessoa está de folga. Anteriormente, a exibição mostrava “[!UICONTROL Horas de trabalho]” para o período não trabalhado.

+++

+++**Atualização de manutenção em 15 de fevereiro de 2024**

### Atualização de manutenção em 15 de fevereiro de 2024

#### Problemas

**Os campos de hora salvam o tempo incorretamente quando há problemas de edição em massa**

Quando uma pessoa edita problemas em massa, define uma data e hora para um campo de data e salva, o horário salvo nesse campo no problema fica diferente do definido. Em vez disso, o horário parece ser convertido em UTC quando ele é salvo.

#### Tarefas

**O usuário não está atribuído a uma ou mais tarefas**

Um usuário pode ser automaticamente desassociado de uma tarefa à qual está atribuído. Isso pode ocorrer em uma ou mais tarefas. O cancelamento da atribuição não é exibido na área Atualizações de sistema das tarefas, embora seja exibido na seção Feeds de atualização do menu de configuração.

#### Atualizações

**A opção de imagem fica disponível ao editar um comentário mesmo quando desativada**

Depois que a administração do [!DNL Workfront] desabilita a opção para adicionar imagens a comentários, essa opção deixa de estar disponível ao criar um comentário. No entanto, se uma pessoa editar um comentário já existente, a opção aparecerá como disponível.

+++

+++**Atualização de manutenção em 8 de fevereiro de 2024**

### Atualização de manutenção em 8 de fevereiro de 2024

#### Quadros

**Não é possível mover um cartão em uma coluna usando as opções de [!UICONTROL Mover]**

Quando um usuário tenta mover um cartão em uma coluna usando as opções “[!UICONTROL Topo da coluna]” ou “[!UICONTROL Fundo da coluna]” no menu de três pontos, o cartão não se move.

**Os cartões persistem ao alterar a iteração**

Quando uma pessoa visualiza uma iteração em um quadro e, em seguida, altera para outra iteração, os cartões exibidos na nova iteração permanecem sendo os mesmos cartões da anterior.

#### Relatórios

**A coluna “Nenhum valor” não exibe resultados**

Quando um relatório de gráfico tem uma coluna “[!DNL No value]”, a coluna não mostra nenhum dado, mesmo quando eles deveriam estar presentes.

#### Gerenciamento de recursos

**Cálculos financeiros incorretos devido a problemas na função de trabalho**

As horas e os cálculos financeiros podem estar incorretos, mostrando um custo de 0 mesmo que as horas estejam registradas em uma função de trabalho que tenha uma taxa de custo.

Isso ocorre porque as Funções de trabalho estão criando automaticamente taxas duplicadas sem datas de início ou término. Como não têm datas de início ou término, elas são tratadas como um valor 0 quando os cálculos financeiros são executados.

+++

+++**Atualização de manutenção em 1 de fevereiro de 2024**

### Atualização de manutenção em 1 de fevereiro de 2024

#### Logon

**Os usuários de SSO não são redirecionados para o local original ao fazer logon**

Quando uma pessoa está em uma página no [!DNL Workfront] e faz logon com SSO, após sua conclusão, ela é redirecionada para a [!UICONTROL Página inicial] em vez da página em que estava antes de fazer o logon.

#### Modelos

**Erro ao copiar modelos**

Quando alguém tenta copiar um modelo novo ou já existente, ele não é copiado e o seguinte erro é exibido:

“[!UICONTROL ID não pode ser nulo]”

+++

## Atualizações em janeiro de 2024

+++**Atualização de manutenção (hot fix) em 30 de janeiro de 2024**

### Atualização de manutenção (Hot Fix) em 30 de janeiro de 2024

#### Relatórios

**O campo API externa não mostra todos os valores disponíveis nas listas e nos relatórios**

Anteriormente, usuários podiam ver o valor selecionado (e editá-lo) de um campo de pesquisa externo nas listas e nos relatórios, mas não visualizavam a lista suspensa com as opções provenientes da API.

Agora, quando um campo personalizado de pesquisa externa é usado em uma lista ou relatório, a lista suspensa com todas as opções da API externa fica disponível.

+++

+++**Atualização de manutenção em 25 de janeiro de 2024**

### Atualização de manutenção em 25 de janeiro de 2024

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

+++**Atualização de manutenção em 18 de janeiro de 2024**

### Atualização de manutenção em 18 de janeiro de 2024

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

#### Formulários personalizados

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

“Ops! Algo deu errado. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.”

Isso ocorre quando o usuário não tem permissão de Visualização para um formulário personalizado anexado ao modelo.

#### Atualizações

**Os comentários não são transferidos entre a experiência antiga e a nova**

Um comentário feito na experiência de comentários herdada pode não estar visível na nova experiência de comentários. O inverso também pode ocorrer.

+++

+++**Atualização de manutenção em 11 de janeiro de 2024**

### Atualização de manutenção em 11 de janeiro de 2024

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
