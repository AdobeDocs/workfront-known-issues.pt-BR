---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: b8552cb4de3b5372b5b18d5891b490f22b9d803d
workflow-type: tm+mt
source-wordcount: '3912'
ht-degree: 98%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2023.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em junho de 2023

+++**Atualização de manutenção em 15 de junho de 2023**

Esta atualização inclui apenas correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em 8 de junho de 2023**

Esta atualização inclui apenas correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 8 de junho de 2023**

[!DNL Fusion] implantou uma correção que impede a remoção das conexões de um usuário quando ele é removido ou desativado na [!UICONTROL Adobe Admin Console].

[!DNL Fusion] os administradores de equipe ainda podem remover conexões desnecessárias do [!UICONTROL Conexões] página em [!DNL Fusion].

+++

+++**Atualização de manutenção em 1 de junho de 2023**

**Nenhuma mensagem de erro ao reordenar tarefa com o status [!UICONTROL Aprovação pendente]**

_Tarefas_

Quando um usuário tenta reordenar uma tarefa com o status [!UICONTROL Aprovação pendente] em uma lista de tarefas, a tarefa parece se mover na lista de tarefas. Após a atualização, o usuário vê que o item não foi movido. O item não pode ser movido porque está sob o status [!UICONTROL Aprovação pendente], mas não há uma mensagem informando ao usuário que o item não pode se mover, o que pode causar confusão.

**Nenhuma mensagem de erro ao mover a tarefa predecessora na tarefa dependente**

_Tarefas_

Quando um usuário tenta reordenar uma tarefa com o status [!UICONTROL Aprovação pendente] em uma lista de tarefas, a tarefa parece se mover na lista de tarefas. Após a atualização, o usuário vê que o item não foi movido. O item não pode ser movido porque uma tarefa predecessora não pode ser movida sob uma tarefa para a qual ela é predecessora, mas não há nenhuma mensagem informando o usuário que o item não pode ser movido, o que pode causar confusão.

+++

## Atualizações em maio de 2023

+++**Atualização de manutenção em 25 de maio de 2023**

O quadro do **[!UICONTROL Kanban] fica em branco ao editar cartões**

_Ágil_

Quando um usuário altera um detalhe de um cartão no quadro do [!UICONTROL Kanban], o quadro fica em branco em vez de registrar a alteração. Se o usuário atualiza a página manualmente, o quadro do [!UICONTROL Kanban] reaparece e mostra a alteração correta.

Esse problema foi relatado nas seguintes circunstâncias:

* Edição de um cartão
* Movimentação de um cartão


+++

+++**Atualização de manutenção em 22 de maio de 2023**

**Não é possível ajustar o tamanho do texto descritivo**

_Formulários personalizados_

Quando o designer de formulários personalizados foi lançado na versão beta, a funcionalidade para ajustar o tamanho do texto descritivo não estava disponível. Esse problema foi corrigido e os usuários agora podem ajustar o tamanho do texto descritivo.

+++

+++**Atualização de manutenção em 18 de maio de 2023**

**O relatório não classifica corretamente por campo personalizado**

_Relatórios_
Quando um usuário executa um relatório de tarefa, o relatório parece classificar corretamente durante o carregamento, mas ao término do processo, o relatório não está classificado corretamente.

Isso parece ocorrer se todas as seguintes circunstâncias forem atendidas:

* O relatório é um relatório de tarefa
* O relatório é classificado por um campo personalizado
* O relatório tem um agrupamento aplicado

+++

+++**Atualização de manutenção em 11 de maio de 2023**

**Não é possível alternar a versão da prova ao visualizar a prova**

_Provas_

Quando um usuário visualiza uma prova no [!UICONTROL Visualizador de prova] e alterna para outra versão, a lista suspensa da versão é desativada e o usuário não consegue voltar para a versão original que estava visualizando ou para outra versão da prova.

A pesquisa do **[!DNL Workfront]atinge o tempo limite**

_Pesquisa_

A pesquisa do [!DNL Workfront] atinge o tempo limite. A pesquisa pode retornar alguns resultados ou nenhum.

Esse problema também afeta a funcionalidade do módulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Pesquisar].

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 11 de maio de 2023**

**Erros de tempo limite no[!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

Quando um cenário está em execução, pode ocorrer um erro de tempo limite. As informações do módulo com o erro não chegam ao destino.

A pesquisa do **[!DNL Workfront]atinge o tempo limite**

_Pesquisa_

A pesquisa do [!DNL Workfront] atinge o tempo limite. A pesquisa pode retornar alguns resultados ou nenhum.

Esse problema também afeta a funcionalidade do módulo [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Pesquisar].

+++

+++**Atualização de manutenção em 9 de maio de 2023**

**Filtros salvos disponíveis na coluna de entrada do quadro**

_Quadros_

Agora é possível usar a tarefa existente do Workfront e os filtros de problemas ao configurar a coluna de entrada de um quadro. No entanto, os filtros de coluna de entrada existentes agora são somente leitura no painel de configuração. Os filtros existentes ainda são aplicados à coluna de entrada, mas você deve recriar os filtros se quiser editá-los.

+++

+++**Atualização de manutenção em 4 de maio de 2023**

**Não é possível selecionar um modelo dos [!UICONTROL Modelos favoritos]**

_Modelos_

Quando um usuário tenta selecionar um modelo no menu Ações (três pontos), a lista de modelos desaparece quando o usuário move seu mouse para a lista, impossibilitando a seleção de um modelo. Isso ocorre porque a barra de rolagem está entre o menu e a lista de modelos, e o mouse alterna o foco para a barra de rolagem à medida que se move para a lista de modelos.

+++

## Atualizações em abril de 2023

+++**Atualização de manutenção em 27 de abril de 2023**

**Não é possível alternar entre provas no [!UICONTROL Visualizador de prova]**

_Provas_

Quando um usuário visualiza uma prova no [!UICONTROL Visualizador de prova] e alterna para outra prova, o botão de alternância para de responder. O usuário não consegue voltar para a prova original que estava visualizando ou para outra prova.

**Editar imagens anexadas ao editar um comentário**

_Atualizações_

Agora é possível editar a imagem anexada a um comentário ao editar um comentário. Isso está disponível na seção Atualizações das Metas do Workfront e na seção de problemas ao habilitar a experiência beta de comentários.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção em 25 de abril de 2023**

Os links de ajuda no aplicativo do **[!DNL Fusion]não abrem páginas de ajuda específicas**

_[!DNL Workfront Fusion]_

Quando um usuário visualiza uma prova no [!UICONTROL Visualizador de prova] e alterna para outra prova, o botão de alternância para de responder. O usuário não consegue voltar para a prova original que estava visualizando ou para outra prova.

+++

+++**Atualização de manutenção em 20 de abril de 2023**

**Problemas em campos suspensos personalizados**

_Formulários personalizados_

Campos suspensos personalizados que foram habilitados como campos de seleção múltipla podem exibir os seguintes problemas:

* O botão “+[!UICONTROL Adicionar]” não está presente quando o formulário não está no modo de edição.
* Campos sem valor mostram uma opção “--[!UICONTROL sem rótulo]--”.

**Não é possível usar a ferramenta Polyline ao fazer um comentário em uma prova**

_Provas_

Quando um usuário visualiza uma prova no Visualizador de prova e tenta fazer um comentário usando a ferramenta Polyline, a ferramenta não marca a prova.

**A caixa de opções de texto mostra “textAnnotations”**

_Provas_

Quando um usuário visualiza uma prova, começa a adicionar um comentário e abre a ferramenta de texto, a palavra “textAnnotation” aparece ao lado das opções na ferramenta. A ferramenta de texto ainda funciona conforme o esperado, e “textAnnotation” desaparece após o comentário ser publicado.

**Manter imagens como rascunho ao sair de uma seção Atualização de metas ou de uma seção Atualização de problemas na experiência beta de comentários**

>[!NOTE]
>
>Esse recurso teve uma pré-visualização lançada em 19 de abril de 2023 e foi enviado para produção em 20 de abril de 2023.

_Atualizações_

Agora, ao sair da página Atualizações enquanto estiver no meio da composição de uma mensagem na qual uma imagem foi anexada, a mensagem e a imagem serão preservadas quando você voltar. Antes desta atualização, comentários não enviados eram preservados, mas não as imagens. Isso está disponível na seção Atualizações de metas e na de problemas ao habilitar a experiência beta de comentários.

**Atualizações em tempo real e comentários excluídos na seção Atualizações**

>[!NOTE]
>
>Esse recurso teve uma pré-visualização lançada em 19 de abril de 2023 e foi enviado para produção em 20 de abril de 2023.

_Atualizações_

Agora, quando alguém adiciona um comentário ou resposta ou exclui um comentário da área Atualizações, você pode ver o novo comentário ou uma indicação de que o comentário foi removido em tempo real, sem atraso. Isso está disponível na seção Atualizações de metas e na de problemas ao habilitar a experiência beta de comentários.

**Nível de acesso alterado pelo sistema sem registro da alteração**

_Usuários_

O nível de acesso de um usuário pode ser alterado imprevisivelmente pelo sistema. Quando isso ocorre, não há atualização visível e a alteração não aparece no log de auditoria.

+++

+++**Atualização de manutenção em 17 de abril de 2023**

**Mostrar novos comentários fora da área visível da tela na seção [!UICONTROL Atualizações] de problemas (nova experiência Beta de comentários) e na de [!UICONTROL Metas]**

_Atualizações_

Adicionamos um banner de notificação na seção [!UICONTROL Atualizações] para informar aos usuários quando houver comentários novos em um item que pode estar fora da área visível na tela. Esta atualização está atualmente disponível na seção [!UICONTROL Atualizações] de metas e na de problemas quando a nova experiência beta de comentário tiver sido habilitada para problemas.

+++

+++**Atualização de manutenção em 13 de abril de 2023**

**Os filtros não são aplicados à lista de solicitações**

_Solicitações_

Quando um usuário visualiza uma lista de solicitações com um filtro aplicado, a lista inclui solicitações que o filtro deveria excluir.

**Não é possível selecionar o [!UICONTROL Tipo de hora padrão] ou [!UICONTROL Tipos de hora disponíveis]**

_Usuários_

Quando um administrador edita um usuário e tenta selecionar um [!UICONTROL Tipo de hora padrão] ou [!UICONTROL Tipo de hora disponível], os menus suspensos desses campos são desabilitados e não é possível selecionar os tipos de hora.

+++

+++**Atualização de manutenção em 6 de abril de 2023**

**Os menus suspensos não são abertos quando um usuário é adicionado a uma prova**

_Provas_

Quando um usuário adiciona outro usuário a uma prova no [!UICONTROL Visualizador de prova], os menus suspensos “[!UICONTROL Função de prova]” e “[!UICONTROL Alertas por email]” não podem ser abertos. O usuário não consegue atribuir uma função de prova ou alerta de email. Isso pode ocorrer ao adicionar um usuário por meio de um comentário ou ao compartilhar a prova com o usuário.

+++

## Atualizações em março de 2023

+++**Atualização de manutenção em 30 de março de 2023**

**Não é possível alternar a versão da prova ao visualizar a prova**

_Provas_

Quando um usuário visualiza uma prova no [!UICONTROL Visualizador de prova] e alterna para outra versão, a lista suspensa da versão é desativada e o usuário não consegue voltar para a versão original que estava visualizando ou para outra versão da prova.

**Erro 504 ao exportar relatórios**

_Relatórios_

Quando um usuário tenta exportar um relatório com um número alto de itens, ele vê um erro 504 e não consegue exportar o relatório.

**A atualização feita em nome de um usuário é vinculada diretamente ao usuário**

_Atualizações_

Quando um administrador está conectado como um usuário e faz um comentário, esse comentário é vinculado diretamente ao usuário, e não ao administrador em nome do usuário.

+++

+++**Atualização de manutenção em 23 de março de 2023**

O conteúdo do painel **[!UICONTROL Resumo] é muito largo para o painel**

_Documentos_

Quando um usuário visualiza o painel [!UICONTROL Resumo] de um documento, seus conteúdos são muito largos para serem visualizados no painel. O painel agora tem uma barra de rolagem horizontal, e o usuário deve rolar a barra horizontalmente para ver o conteúdo do painel [!UICONTROL Resumo]. Isso ocorre porque o nome do arquivo do documento não possui quebra de linha. Esse problema é limitado a arquivos em que o nome do arquivo tenha uma extensão de arquivo HTML.

**Nova versão do [!UICONTROL Visualizador de prova para desktop]**

_Prova_

Para corrigir um problema de comentário no [!UICONTROL Visualizador de prova para desktop], implantamos uma nova versão do visualizador.

Os usuários que já tiverem o [!UICONTROL Visualizador de prova para desktop] instalado receberão esta atualização automaticamente.

Os usuários também podem baixar manualmente a versão mais recente. Para obter mais informações, consulte [Instalar o [!UICONTROL Visualizador de prova para desktop]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=pt-BR).

* Versão anterior: 2.1.22
* Nova versão: 2.1.23

+++

+++**Atualização de manutenção em 16 de março de 2023**

**Os itens da lista de verificação não são copiados ao copiar um cartão**

_Quadros_

Ao copiar um cartão ad hoc (os cartões conectados não podem ser copiados), os itens da lista de verificação não são copiados para o novo cartão.

**O campo personalizado está ausente quando o problema é convertido para o projeto**

_Projetos_

Quando um usuário converte um problema em um projeto usando um modelo, um campo personalizado que estava no problema não é exibido no projeto. Esse problema afeta somente usuários não administradores.

**Mensagens personalizadas não aparecem nas notificações por email**

_Provas_

Quando um usuário compartilha uma prova e adiciona uma mensagem personalizada, ela não é exibida no email de notificação do destinatário. O assunto é o nome da prova e a mensagem não aparece no email.

+++

+++**Atualização de manutenção em 9 de março de 2023**

**O nível de acesso não é atribuído ao reativar um usuário**

_Usuários_

Quando um usuário está reativando um usuário desativado e tenta atribuir a ele um nível de acesso na janela [!UICONTROL Reativar usuário], a lista suspensa de nível de acesso não é preenchida conforme o usuário digita e ele não consegue selecionar um nível de acesso. Se o usuário digitar no nível de acesso e salvar, esse nível de acesso não será atribuído ao usuário reativado.

**Salve o rascunho de um comentário na área [!DNL Goals]**

_[!DNL Workfront Goals]_

Agora, quando sair da página [!UICONTROL Atualizações] de uma meta enquanto durante a composição de uma mensagem, a mensagem será preservada para quando você retornar. Antes desta atualização, o comentário não enviado teria sido excluído.

+++

+++**Atualização de manutenção em 2 de março de 2023**

**Não é possível adicionar cartões quando um agrupamento é aplicado**

_Quadros_

Quando um usuário está visualizando um quadro com um agrupamento aplicado e tenta adicionar um cartão, ele só pode digitar o nome do cartão. O restante dos campos do cartão está desativado, incluindo o botão [!UICONTROL Salvar].

Se o usuário altera o agrupamento para [!UICONTROL Nenhum], o problema permanece. O usuário deve alterar o agrupamento para [!UICONTROL Nenhum] e atualizar a página para que a funcionalidade de adicionar um cartão seja restaurada.

**Os cartões conectados não são adicionados às colunas com base no status**

_Quadros_

Mesmo que as políticas de coluna sejam aplicadas para o status, os novos cartões conectados aparecem na coluna mais à esquerda, e não na coluna que corresponde a seu status.


**Vincular a um comentário redireciona para a página [!UICONTROL Detalhes]**

_Atualizações_

Quando um usuário clica em um link para um comentário em um objeto no Workfront, o fluxo de atualização é carregado brevemente e, em seguida, é redirecionado para a área [!UICONTROL Detalhes] do objeto. Isso pode ocorrer se o usuário clicar no link de um email ou colar o link em seu navegador.

Atualmente, isso afeta apenas objetos de Documento.

**O Resumo de impressão não é carregado**

_[!UICONTROL Prova do Workfront]_

Quando um usuário tenta carregar a página Resumo de impressão, ela parece estar sendo carregada, mas o processo nunca é concluído.

+++

## Atualizações em fevereiro de 2023

+++**Atualização de manutenção em 23 de fevereiro de 2023**

**Vincular a um comentário redireciona para a página [!UICONTROL Detalhes]**

_Atualizações_

Quando um usuário clica em um link para um comentário em um objeto no Workfront, o fluxo de atualização é carregado brevemente e, em seguida, é redirecionado para a área [!UICONTROL Detalhes] do objeto. Isso pode ocorrer se o usuário clicar no link de um email ou colar o link em seu navegador.

Atualmente, isso afeta apenas objetos de Documento.

**O usuário não consegue editar suas próprias configurações de notificação**

_Usuários_

Quando um usuário com uma licença [!UICONTROL Trabalhador] tenta editar suas próprias configurações de notificação, as opções de [!UICONTROL Notificações] não ficam visíveis na janela [!UICONTROL Editar] e o usuário não consegue editar as configurações.

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

Adição do campo **[!UICONTROL Story Points] a listas de tarefas e problemas e relatórios**

_Relatórios_

O campo [!UICONTROL Story Points] agora está disponível para adicionar a listas e relatórios para tarefas ou problemas. É um campo de formulário gratuito editável que não está vinculado a horas planejadas ou atribuições de equipe.

+++

+++**Atualização de manutenção em 8 de fevereiro de 2023**

**Botão Filtrar na coluna de entrada**

_Quadros_

A coluna de entrada em um quadro agora inclui um botão **[!UICONTROL Adicionar um filtro]** quando a coluna estiver vazia e nenhum filtro tiver sido criado. O botão abre a área de configuração, onde você pode adicionar filtros para trazer tarefas e problemas para a coluna de entrada.

+++

+++**Atualização de manutenção em 2 de fevereiro de 2023**

O ícone **[!UICONTROL Quadros] aparece no [!UICONTROL Menu principal] por padrão**

_Quadros_

O ícone [!UICONTROL Quadros] agora aparece no [!UICONTROL Menu principal] para usuários que não têm um modelo de layout. Os quadros também são incluídos no Menu principal por padrão em qualquer novo modelo de layout criado. Os modelos de layout existentes não foram alterados.

**Não é possível salvar modelos de email**

_Configuração_

Quando um usuário tenta criar ou editar um modelo de email, o botão [!UICONTROL Salvar] não responde e não é possível salvar o modelo.

+++

## Atualizações em janeiro de 2023

+++**Atualização de manutenção em 30 de janeiro de 2023**

**Atalhos de teclado adicionados para ações comuns da folha de horas**

_Folhas de horas_

Introduzimos os seguintes atalhos de teclado para as seguintes ações executadas com frequência em uma folha de horas:

* Adicionar linha (Cmd+Option++/Ctrl+Option+)
* Excluir linha (Cmd+Option+-/Ctrl+Option+-)
* Fixar ou desafixar um item de trabalho (Option+P/Option+P)
* Abrir comentário (Shift+F2/Shift+F2)
* Salvar comentário (Cmd+Enter/Ctrl+Enter)
* Expandir (Shift+Option+Seta para cima/Shift+Alt+Seta para cima)
* Recolher (Shift+Option+Seta para baixo/Shift+Alt+Seta para baixo)

A área onde essas ações são executadas deve ser realçada para que sejam aplicadas.

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

**Erro ao enviar solicitação do [!DNL Outlook]**

_Integrações_

Quando um usuário tenta enviar uma solicitação com anexos de um email do [!DNL Outlook], um ou mais anexos não são carregados e o usuário vê o seguinte erro:

“[!UICONTROL Ocorreu o seguinte erro: o arquivo com o identificador xxxx não existe.]”

Isso ocorre somente quando uma atribuição é feita para a nova solicitação, seja por meio da fila de solicitações ou manualmente ao criar a solicitação.

**Nova versão do Visualizador de prova para desktop**

_Prova_

Para corrigir um problema de congelamento no Visualizador de prova para desktop, implantamos uma nova versão do visualizador. Os usuários que já tiverem o Visualizador de prova para desktop instalado receberão esta atualização automaticamente.

Os usuários também podem baixar manualmente a versão mais recente. Para obter mais informações, consulte [Instalar o Visualizador de prova para desktop](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=pt-BR).

* Versão anterior: 2.1.19
* Nova versão: 2.1.20

**O usuário não pode editar sua própria configuração de usuário**

_Usuários_

Quando um usuário que possui uma licença de Trabalho, Revisão ou Solicitação tenta editar suas próprias configurações de usuário, a janela pop-up é aberta em branco e o usuário não consegue fazer edições. Para sair da janela pop-up, o usuário precisa atualizar a página.

+++

+++**Atualização de manutenção em 19 de janeiro de 2023**

**Agora, os filtros da coluna de entrada podem ser compartilhados**

_Quadros_

Quando o recurso da coluna de entrada foi lançado para Quadros, os filtros de configuração da coluna de entrada só podiam ser vistos pela pessoa que os criou. Agora, o criador pode compartilhar os filtros com outros usuários ou equipes.

**A funcionalidade de pino está disponível no menu [!UICONTROL Mais]**

_Navegação_

Os seguintes recursos agora estão disponíveis no menu [!UICONTROL Mais] dos marcadores, no ambiente de produção:

* Renomear pinos
* Reorganização de pinos no menu [!UICONTROL Mais]
* Mover um pino para fora do menu [!UICONTROL Mais] (ao fazer isso, o último pino na barra de navegação superior é movido para o menu [!UICONTROL Mais])

+++

+++**Atualização de manutenção em 18 de janeiro de 2023**

**Expressões com curingas não são válidas em campos personalizados**

_Formulários personalizados_

Quando um usuário usa um curinga, como \$$TODAY ou $$NOW, juntamente com um modificador (como “-30d”) em um campo personalizado, o validador não aceita o curinga como válido. Curingas sem modificadores são vistos como válidos.

O **[!UICONTROL Balanceador de carga de trabalho] mostra horas não associadas a um projeto/tarefa/problema**

_[!UICONTROL Balanceador de carga de trabalho]_

Ao visualizar o [!UICONTROL Balanceador de carga de trabalho], o usuário vê horas registradas para um usuário que não estão associadas a nenhum projeto, tarefa ou problema, e que não estão registradas como horas [!UICONTROL Gerais]. Essas horas podem ser exibidas somente na visualização de 4 ou 6 semanas.

+++

+++Atualização de manutenção do **[!DNL Adobe Workfront Fusion] (Hot Fix) em 12 de janeiro de 2023**

**Erros 404 em módulos do [!DNL Workfront]**

_Workfront Fusion_

Quando um cenário é executado, um módulo do [!DNL Workfront] retorna um erro 404.

Esse problema foi relatado os seguintes módulos:

* [!UICONTROL Ler um registro]

+++

+++**Atualização de manutenção (Hot Fix) em 12 de janeiro de 2023**

**Erro “[!UICONTROL Ops!]” ao configurar um campo calculado**

_Formulários personalizados_

Quando um usuário cria ou edita um campo calculado em um formulário personalizado e inclui um campo personalizado na expressão do campo calculado, a expressão é considerada inválida. O botão [!UICONTROL Salvar] está desativado e o usuário não consegue sair do campo personalizado. Além disso, o usuário vê a seguinte mensagem abaixo do campo:

“[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Remover o campo personalizado da expressão permite que o usuário salve e navegue para fora do campo.

**Não é possível definir níveis de acesso**

_Usuários_

Quando um usuário tenta alterar o nível de acesso de outro usuário, os níveis de acesso ficam esmaecidos e não é possível alterá-los. Isso ocorre mesmo quando o usuário que está tentando realizar a alteração é um administrador do sistema.

+++

+++**Atualização de manutenção em 12 de janeiro de 2023**

**Ctrl+F ou Cmd+F não funciona como esperado em campos suspensos**

_Formulários personalizados_

Quando um usuário está preenchendo um formulário personalizado e pesquisa uma lista suspensa usando Ctrl+F ou Cmd+F e, em seguida, tenta passar para a próxima instância dessa pesquisa, a lista suspensa retorna ao topo da lista em vez de pular para a próxima instância da pesquisa. Isso ocorre quando uma lista suspensa é definida para permitir várias seleções.

A tela **[!UICONTROL Editar relatório] está em branco**

_Relatórios_

Quando um usuário está visualizando um relatório e tenta editá-lo, ele é direcionado a uma tela em branco e não consegue editar o relatório.

**As tarefas recuadas não permanecem recuadas**

_Tarefas_

Quando um usuário exibe uma lista de tarefas e recua uma tarefa, a tarefa retorna imediatamente ao seu estado original (recuado).

+++

+++**Atualização de manutenção em 5 de janeiro de 2023**

**A funcionalidade de pino está disponível no menu [!UICONTROL Mais]**

_Navegação_

Os seguintes recursos agora estão disponíveis no menu [!UICONTROL Mais] para pinos, somente no ambiente de visualização:

* Renomear pinos
* Reorganização de pinos no menu [!UICONTROL Mais]
* Mover um pino para fora do menu [!UICONTROL Mais] (ao fazer isso, o último pino na barra de navegação superior é movido para o menu [!UICONTROL Mais])

**Remoção da limitação do Grupo do projeto ao adicionar usuários à equipe do projeto**

_Equipes_

Removemos a limitação que exigia que os usuários que precisam ser adicionados a uma equipe de projeto estivessem no Grupo associado ao projeto. Agora, você pode adicionar qualquer usuário ativo a uma equipe de projeto, independentemente dos grupos aos quais ele pertence.

**Novos ícones de informações para folhas de horas, perfis de folha de horas e preferências de folha de horas**

>[!NOTE]
>
>Essa atualização foi lançada no ambiente de Visualização em 3 de novembro de 2022 e agora está disponível na Produção

_Workfront_

Adicionamos vários ícones de informações às seguintes configurações:

* Caixa de seleção “Pode editar horas” ao criar ou editar uma folha de horas ou um perfil de folha de horas para indicar que, quando ativado, os aprovadores também podem enviar, reabrir ou editar a folha de horas, a menos que o administrador restrinja essas ações na área Preferências da folha de horas da Configuração.
* “Restringir a edição da folha de horas a proprietários e administradores” na área Folha de horas e preferências de hora da configuração para indicar que, quando desativado, os usuários a seguir também podem editar as folhas de horas: usuários com acesso administrativo a folhas de horas, aprovadores de folha de horas com permissão para editar hora e gerentes de proprietários de folha de horas.

Observe que a funcionalidade dessas configurações não foi alterada e somente os ícones de informações foram adicionados para esclarecer o escopo das configurações.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [[!DNL Workfront] Arquivo de atualizações de manutenção - 2022](2022-updates.md)
* [[!DNL Workfront] Arquivo de atualizações de manutenção - 2021](2021-updates.md)
