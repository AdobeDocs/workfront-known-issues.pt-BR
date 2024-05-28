---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: c3e3297bd52a4189321102e75cd952ac5162f1fa
workflow-type: tm+mt
source-wordcount: '3781'
ht-degree: 95%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2024.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2024, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em maio de 2024

+++ **(Planejado) Atualização de manutenção em sexta-feira, 30 de maio de 2024**

### (Planejado) Atualização de manutenção em sexta-feira, 30 de maio de 2024

#### Formulários personalizados

Erro ao editar campos de texto descritivo

Quando um usuário tenta editar o texto descritivo em um formulário personalizado, o texto não é salvo e o usuário vê o seguinte erro:

&quot;O valor da chave duplicada viola a restrição exclusiva&quot;

Esse problema foi relatado no construtor de formulários herdado.

#### Atualizações

**Copiar e colar uma menção não notifica o usuário mencionado**

Quando alguém copia um comentário que inclui uma menção no formato @ e o cola na área de atualizações de outro objeto, o usuário mencionado não é notificado sobre o comentário colado.

+++

+++ **Atualização de manutenção em sexta-feira, 23 de maio de 2024**

### Atualização de manutenção em sexta-feira, 23 de maio de 2024

#### Relatórios

Quando um usuário visualiza um relatório e clica no botão Voltar do navegador, uma das situações a seguir pode ocorrer:

* O usuário permanece na página Relatório.
* O usuário é direcionado para a página inicial do navegador.
* O usuário é direcionado para a página de Logon.

Esse problema foi relatado com o navegador Chrome.

#### Atualizações

**O usuário marcado não consegue ver quem os marcou**

Quando um usuário é marcado em uma atualização, ele não consegue ver quem o marcou. Isso ocorre quando a configuração &quot;As pessoas em outras empresas só devem visualizar os usuários de...&quot; está definida como &quot;Sua empresa&quot;.

**Marcar um usuário com @ no painel Resumo é ineficaz**

Ao tentar marcar alguém usando @ na área de atualizações de um painel Resumo, clicar no nome da pessoa na lista suspensa não gera efeito. Tentar marcar a pessoa uma segunda vez funciona conforme o esperado.

+++

+++**Atualização de manutenção em sexta-feira, 16 de maio de 2024**

### Atualização de manutenção em sexta-feira, 16 de maio de 2024

#### Configuração

**Status de problemas padrão ausentes em alguns tipos de problemas na configuração**

Quando uma pessoa visualiza os status de problemas na Configuração, ela verá que os status padrão para problemas (Novo, Em andamento e Concluído) estão ausentes em alguns tipos de problemas. Os status padrão não têm a opção para alterar o tipo de problema, portanto, a pessoa não pode reconfigurar os status para serem exibidos para os tipos de problema afetados.

#### Usuários

**Não é possível excluir usuários**

Quando uma pessoa tenta excluir usuários, eles não são excluídos. Esse problema foi relatado em organizações que migraram para o Adobe Admin Console.

+++

+++**Atualização de manutenção em sexta-feira, 9 de maio de 2024**

### Atualização de manutenção em sexta-feira, 9 de maio de 2024

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 2 de maio de 2024**

### Atualização de manutenção em 2 de maio de 2024

#### Registro de hora

**Não é possível editar horas em tarefas ou problemas**

Quando um usuário tenta editar horas em uma tarefa ou problema, as alterações não são salvas.

+++

## Atualizações em abril de 2024

+++**Atualização de manutenção em sexta-feira, 25 de abril de 2024**

### Atualização de manutenção em sexta-feira, 25 de abril de 2024

#### Atualizações

**As listas numeradas não ficam numeradas corretamente**

Quando uma pessoa envia um comentário que inclui uma lista numerada, essa lista mostra uma numeração incorreta na atualização.

Esse problema foi relatado na nova experiência de comentários.

**O texto não é preservado ao sair e voltar para o comentário**

Quando um usuário está escrevendo um comentário que inclui uma @mention e, em seguida, sai e volta para o comentário antes de enviá-lo, qualquer texto inserido após a @mention não aparece no rascunho do comentário.

Esse problema foi relatado na nova experiência de comentários.

+++

+++**Atualização de manutenção em sexta-feira, 18 de abril de 2024**

### Atualização de manutenção em sexta-feira, 18 de abril de 2024

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

+++**Atualização de manutenção em sexta-feira, 11 de abril de 2024**

### Atualização de manutenção em sexta-feira, 11 de abril de 2024

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

+++**Atualização de manutenção em sexta-feira, 4 de abril de 2024**

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

+++**Atualização de manutenção em sexta-feira, 4 de abril de 2024**

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

+++**Atualização de manutenção em sexta-feira, 28 de março de 2024**

### Atualização de manutenção em sexta-feira, 28 de março de 2024

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

+++**Atualização de manutenção do Workfront Fusion em sexta-feira, 28 de março de 2024**

### Atualização de manutenção do Workfront Fusion em 28 de março de 2024

**RuntimeError com resposta 200 do módulo Workfront**

Um módulo do Workfront pode retornar uma resposta `RuntimeError [200]`. O 200 implica uma resposta bem-sucedida, mas o erro mostra que a solicitação foi malsucedida.

Isso pode ocorrer se a resposta for extremamente longa. Os dados são retornados ao Fusion, mas não podem ser processados por ele.

+++

+++**Atualização de manutenção em sexta-feira, 21 de março de 2024**

### Atualização de manutenção em sexta-feira, 21 de março de 2024

#### Atualizações

**Espaços grandes entre as linhas**

Quando uma pessoa digita uma atualização com várias linhas usando a tecla Return ou Enter, ou cola várias linhas em uma atualização, ela é exibida conforme esperado. No entanto, se alguém visualizar essas atualizações em um relatório, haverá grandes espaços entre as linhas.

Esse problema foi relatado na nova experiência de comentários.

**Marcar um usuário com @ não funciona**

Quando uma pessoa marca outra com @ em um comentário, ela não é adicionada à área de usuários marcados com tags e não recebe uma notificação sobre o comentário.

Essa correção se aplica somente à nova experiência de comentários.

+++

+++**Atualização de manutenção em sexta-feira, 14 de março de 2024**

### Atualização de manutenção em sexta-feira, 14 de março de 2024

#### Provas

**Provas criadas de documentos vinculados não têm o modelo de prova aplicado**

Quando uma pessoa cria uma prova de um documento vinculado, o modelo de prova não é aplicado corretamente e podem faltar informações da prova, como o fluxo de trabalho.

Isso também se aplica às provas criadas por meio da API e do Workfront Fusion.

#### Usuários

**Níveis de acesso mais baixos não disponíveis ao criar um usuário**

Quando um usuário cria outro usuário, somente o nível de acesso do primeiro usuário é disponibilizado para o usuário recém-criado. Todos os níveis de acesso com permissões inferiores às do usuário criador devem estar disponíveis para o novo usuário.

+++

+++**Atualização de manutenção em sexta-feira, 7 de março de 2024**

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

+++**Atualização de manutenção em sexta-feira, 29 de fevereiro de 2024**

### Atualização de manutenção em sexta-feira, 29 de fevereiro de 2024

#### Atualizações

**Atualizações: a tela fica em branco ao responder a alguém de outra empresa**

Quando você tenta responder a um comentário de alguém em outra empresa, a tela fica em branco.

Isso ocorre porque a pessoa não tem permissão para ver usuários de outras empresas.

+++

+++**Atualização de manutenção em sexta-feira, 22 de fevereiro de 2024**

### Atualização de manutenção em sexta-feira, 22 de fevereiro de 2024

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

+++**Atualização de manutenção em sexta-feira, 15 de fevereiro de 2024**

### Atualização de manutenção em sexta-feira, 15 de fevereiro de 2024

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

+++**Atualização de manutenção em sexta-feira, 8 de fevereiro de 2024**

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

+++**Atualização de manutenção em sexta-feira, 1 de fevereiro de 2024**

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

+++**Atualização de manutenção (hot fix) em quarta-feira, 30 de janeiro de 2024**

### Atualização de manutenção (Hot Fix) em 30 de janeiro de 2024

#### Relatórios

**O campo API externa não mostra todos os valores disponíveis nas listas e nos relatórios**

Anteriormente, usuários podiam ver o valor selecionado (e editá-lo) de um campo de pesquisa externo nas listas e nos relatórios, mas não visualizavam a lista suspensa com as opções provenientes da API.

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
