---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do  [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
source-git-commit: 932556d1c72aa33e9169034f41f6250d249a228b
workflow-type: tm+mt
source-wordcount: '2314'
ht-degree: 19%

---

# Atualizações de manutenção do [!DNL Workfront]

>[!NOTE]
>
>Para obter informações sobre interrupções de manutenção para todos os produtos Adobe, incluindo o Workfront, consulte a [página Status da Adobe](https://status.adobe.com/).

Esta página descreve os problemas corrigidos nas atualizações semanais do Workfront.

Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado por você for corrigido.

Para obter atualizações de manutenção anteriores a 2025, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

As seguintes atualizações de manutenção foram efetuadas em 2025.

## Atualizações em outubro de 2025

+++**Semana de atualizações de manutenção de 28 de setembro a 4 de outubro de 2025**

### Atualizações de manutenção semana de 28 de setembro a 4 de outubro de 2025

#### Programas

**Não é possível salvar ao editar um programa**

Quando um usuário está editando um programa e tenta salvar as alterações, as alterações não são salvas.

+++

## Atualizações em setembro de 2025

+++**Semana de atualizações de manutenção de 21 a 27 de setembro de 2025**

### Atualizações de manutenção semana de 21 a 27 de setembro de 2025

#### Usuários

**Não é possível editar as configurações de notificações de outro usuário**

Quando um usuário tenta editar as configurações de notificação de outro usuário, ele não pode editar as configurações e vê a seguinte mensagem:

&quot;Você não tem acesso suficiente para editar dados financeiros.&quot;

+++

+++**Semana de atualizações de manutenção de 14 a 20 de setembro de 2025**

### Atualizações de manutenção na semana de 14 a 20 de setembro de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Semana de atualizações de manutenção de 7 a 13 de setembro de 2025**

### Atualizações de manutenção na semana de 7 a 13 de setembro de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++


+++**Semana de atualizações de manutenção de 31 de agosto a 6 de setembro de 2025**

### Semana de atualização de manutenção de 31 de agosto a 6 de setembro de 2025

#### API

**Novas medidas de proteção para evitar sobrecarga de Assinaturas de Eventos**

Inscrições em eventos foi projetado para fornecer entrega confiável de eventos para todos os usuários. Para garantir isso, foram implementadas salvaguardas para evitar a produção excessiva de eventos por parte de um único usuário, o que poderia causar possíveis problemas de qualidade de serviço para todos os usuários. Como resultado, um usuário que está produzindo muitos eventos em uma taxa alta em um curto período de tempo pode enfrentar sandboxing e atrasos de entrega de eventos.

#### Documentos

**Os usuários adicionados como aprovadores após a conclusão da aprovação não são notificados**

Quando um usuário aprova um documento e, em seguida, mais usuários são adicionados como aprovadores, os aprovadores recém-adicionados não recebem notificações no aplicativo ou por email da solicitação de aprovação.

+++

## Atualizações em agosto de 2025

+++**Semana de atualizações de manutenção de 24 a 30 de agosto de 2025**

### Semana de atualização de manutenção de 24-30 de agosto de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Semana de atualizações de manutenção de 17 a 23 de agosto de 2025**

### Semana de atualização de manutenção de 17 a 23 de agosto de 2025

#### Projetos

**Erro ao adicionar um projeto a um programa**

Quando um usuário tenta adicionar um projeto existente a um programa, o projeto não é adicionado e o usuário vê a seguinte mensagem de erro:

&quot;Erro ao carregar o conteúdo secundário...&quot;

**Os projetos exportados contêm Horas Efetivas imprecisas**

Quando um usuário exporta um projeto para o Excel, a coluna Horas efetivas não exibe os dados corretos.

+++

+++**Semana de atualizações de manutenção de 10 a 16 de agosto de 2025**

### Semana de atualização de manutenção de 10 a 16 de agosto de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Semana de Atualizações de Manutenção de 3 a 9 de agosto de 2025**

### Semana de atualização de manutenção de 3 a 9 de agosto de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Semana de atualizações de manutenção de 27 de julho a 2 de agosto de 2025**

### Atualizações de manutenção semana de 27 de julho a 2 de agosto de 2025

#### Projetos

**O aviso agora é exibido quando a linha do tempo não foi recalculada**

Os usuários agora verão um ícone de aviso quando a linha do tempo do projeto não for recalculada. Ao passar o mouse sobre esse ícone, o usuário vê a seguinte mensagem:

&quot;A linha do tempo do projeto está incorreta. Os gerentes de projeto podem precisar recalcular manualmente a linha do tempo.&quot;

Ocasionalmente, as linhas do tempo podem não ser recalculadas porque um projeto é extremamente complexo. Por exemplo, um projeto que tenha várias dependências, um grande número de tarefas, vários predecessores entre projetos ou vários recuos de tarefas podem ser afetados.

Anteriormente, não havia nenhuma indicação de que uma linha do tempo não tivesse sido recalculada.

#### Tarefas

**A área Aprovações desaparece da navegação à esquerda**

Quando um usuário está visualizando uma tarefa, a área Aprovações pode desaparecer da navegação à esquerda. Remover e adicionar a área Aprovações ao Modelo de layout resolve o problema, mas o problema pode ocorrer novamente.

+++

## Atualizações em julho de 2025

+++**Semana de atualizações de manutenção de 20 a 26 de julho de 2025**

### Atualizações de manutenção semana de 20 a 26 de julho de 2025

#### Provas

**Não é possível marcar usuários em comentários de prova**

Quando um usuário tenta marcar outro usuário em um comentário de prova e começa a digitar o nome dele, ele não aparece na lista e não pode ser selecionado para ser marcado.

+++

+++**Semana de atualizações de manutenção de 13 a 19 de julho de 2025**

### Atualizações de manutenção semana de 13 a 192 de julho

### Integrações

**Problemas com o Workfront para integração com o Slack**

Os seguintes problemas foram relatados em relação à integração do Workfront para Slack:

* Os usuários não são notificados no Slack quando são feitas atualizações no Workfront.
* Os usuários não conseguem fazer logon no Workfront a partir do Slack.
* Outros comandos no Workfront para integração com o Slack não estão funcionando como esperado.

+++

+++**Semana de atualizações de manutenção de 6 a 12 de julho de 2025**

### Atualizações de manutenção na semana de 6 a 12 de julho

### Projetos

**Não é possível mover o projeto para o programa especificado**

Quando um usuário tenta mover um projeto para um programa, o projeto não é movido. Isso pode ocorrer mesmo que o usuário tenha recebido uma mensagem informando que o projeto foi movido com êxito.

+++

## Atualizações em junho de 2025

+++**Semana de atualizações de manutenção de 22 a 27 de junho de 2025**

### Atualização de manutenção da semana de 22 a 27 de junho de 2025

#### Provas

**Não é possível abrir a prova do link direto**

Quando um usuário tenta abrir uma prova de um link direto, a prova não abre. Isso pode ocorrer mesmo se o usuário estiver em um workflow para a prova ou se for um administrador do Workfront.

#### Relatórios

**O detalhamento de gráfico inclui resultados imprecisos**

Quando um usuário está visualizando um relatório de gráfico e tenta detalhar um agrupamento específico, os detalhes incluem resultados que não estão no agrupamento selecionado.

Esse problema foi relatado em relatórios agrupados por data.

+++

+++**Semana de atualizações de manutenção de 15 a 21 de junho de 2025**

### Atualização de manutenção semanal de 15 a 21 de junho de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Semana de atualizações de manutenção de 8 a 14 de junho de 2025**

### Atualização de manutenção semana de 8 a 14 de junho de 2025

#### Planejador de recursos

**O botão Exportar está desabilitado**

Quando um usuário tenta exportar do Planejador de recursos, o botão é desativado (esmaecido) e o usuário não consegue exportar.

#### Planilhas de horas

**Planilha de horas não gerada corretamente**

Quando um usuário tenta gerar folhas de horas e a geração é definida como &quot;A cada duas semanas&quot;, somente uma semana é gerada.

+++

+++**Semana de atualizações de manutenção de 1 a 7 de junho de 2025**

### Atualização de manutenção semana de 1 a 7 de junho de 2025

### Pesquisar

**A Pesquisa Avançada não retorna os resultados esperados**

Quando um usuário usa a Pesquisa avançada, os resultados esperados não são retornados. Isso pode ocorrer mesmo quando não há filtros aplicados à Pesquisa avançada.

+++

## Atualizações em maio de 2025

+++**Atualizações de manutenção na semana de 25 a 31 de maio de 2025**

### Atualização de manutenção da semana de 25 a 31 de maio de 2025

As atualizações desta semana incluem apenas correções de erros menores ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 22 de maio de 2025**

### Atualização de manutenção em sexta-feira, 22 de maio de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 15 de maio de 2025**

### Atualização de manutenção em sexta-feira, 15 de maio de 2025

#### Relatórios

**Erro ao visualizar um relatório com uma exibição de marco**

Quando um usuário tenta visualizar um relatório com uma exibição de marco disponível para ativação do, o relatório não é carregado e exibe um erro.

+++

+++**Atualização de manutenção em sexta-feira, 8 de maio de 2025**

### Atualização de manutenção em sexta-feira, 8 de maio de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 1 de maio de 2025**

### Atualização de manutenção em sexta-feira, 1 de maio de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

## Atualizações em abril de 2025

+++**Atualização de manutenção em sexta-feira, 24 de abril de 2025**

### Atualização de manutenção em sexta-feira, 24 de abril de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 17 de abril de 2025**

### Atualização de manutenção em sexta-feira, 17 de abril de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 10 de abril de 2025**

### **Atualização de manutenção em sexta-feira, 10 de abril de 2025**

#### Painéis

**O painel personalizado não abre**

Quando um usuário visualiza um objeto e tenta abrir um painel personalizado anexado ao objeto, o painel não abre.

#### Relatórios

**Usuários em fusos horários diferentes obtêm resultados de relatório diferentes**

Os usuários em fusos horários diferentes que usam o seletor de datas para obter um relatório para uma determinada data obtêm resultados diferentes para esse relatório.

+++

+++**Atualização de manutenção em sexta-feira, 3 de abril de 2025**

### Atualização de manutenção em sexta-feira, 3 de abril de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

## Atualizações em março de 2025

+++**Atualização de manutenção em sexta-feira, 27 de março de 2025**

### Atualização de manutenção em sexta-feira, 27 de março de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 20 de março de 2025**

### Atualização de manutenção em sexta-feira, 20 de março de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em sexta-feira, 13 de março de 2025**

### Atualização de manutenção em sexta-feira, 13 de março de 2025

#### Relatórios

**A contagem de itens no gráfico é imprecisa**

Em um relatório de painel, clicar em um resultado de gráfico com mais de 15 itens e selecionar para exibir apenas 15 funciona conforme esperado. No entanto, se você abrir o mesmo relatório fora do painel e clicar no mesmo resultado do gráfico, isso indicará que todos os itens estão sendo exibidos, mas apenas 15 realmente aparecem.

+++

+++**Atualização de manutenção em sexta-feira, 6 de março de 2025**

### Atualização de manutenção em sexta-feira, 6 de março de 2025

Esta atualização contém apenas correções de erros pequenos ou menos importantes. O Suporte da Workfront enviará uma notificação quando um problema enviado for corrigido.

+++

## Atualizações em fevereiro de 2025

+++**Atualização de manutenção em sexta-feira, 27 de fevereiro de 2025**

### Atualização de manutenção em sexta-feira, 27 de fevereiro de 2025

#### Grupos

**Não é possível compartilhar o nível de acesso de administrador**

Ao tentar compartilhar o nível de acesso de administrador com um grupo, a caixa para marcar cada grupo não responde e o grupo não obtém o nível de acesso esperado.

+++

+++**Atualização de manutenção em sexta-feira, 20 de fevereiro de 2025**

### Atualização de manutenção em sexta-feira, 20 de fevereiro de 2025

#### Notificações

**Atrasos de emails e notificações no aplicativo**

Quando ocorre um evento que deve acionar notificações por email ou no aplicativo, as notificações não são enviadas no momento do evento e, em vez disso, levam mais de algumas horas para serem enviadas.

#### Tarefas

**Hora registrada restante no projeto anterior depois de movida**

Depois que as tarefas são movidas para um novo projeto, o total de horas do projeto original inclui horas para as tarefas movidas. As tarefas ainda retêm corretamente as horas reportadas no novo projeto.

#### Planilhas de horas

**Total de horas incorreto**

O cálculo do total de horas da folha de horas ocasionalmente mostra uma soma incorreta.

+++

+++**Atualização de manutenção em sexta-feira, 13 de fevereiro de 2025**

### Atualização de manutenção em sexta-feira, 13 de fevereiro de 2025

#### Formulários personalizados

**Dados personalizados não mostrados no painel Resumo**

Quando um cliente está visualizando o painel Resumo de uma tarefa, os dados personalizados que devem aparecer no painel Resumo não estão presentes. Isso pode ocorrer mesmo que o modelo de layout das tarefas inclua os campos personalizados.

#### Relatórios

**Problemas de exibição de prompt**

Ao acessar um relatório solicitado com um grande número de solicitações, a caixa de diálogo de solicitação não permite a rolagem para acessar todas as solicitações ou o botão Executar relatório.

+++

+++**Atualização de manutenção em sexta-feira, 6 de fevereiro de 2025**

### Atualização de manutenção em sexta-feira, 6 de fevereiro de 2025

#### Listas

**Não é possível editar a lista de tarefas após carregar a prova**

Ao fazer upload de uma prova em um projeto, a lista de tarefas desse projeto não pode ser editada em linha até que a página seja atualizada ou a prova termine o upload.

+++

## Atualizações em janeiro de 2025

+++**Atualização de manutenção em sexta-feira, 30 de janeiro de 2025**

### Atualização de manutenção em sexta-feira, 30 de janeiro de 2025

#### Início

**Aprovações que não aparecem no widget Página inicial**

As aprovações enviadas por um usuário não aparecem em seu próprio widget Minhas aprovações, mesmo quando filtradas para exibi-las especificamente.

#### Relatórios

**Os filtros de relatório de horas incluem datas incorretas**

Ao filtrar um relatório de horas para mostrar apenas uma data específica, uma data adjacente diferente é incluída no relatório. Esse problema parece estar relacionado às configurações de fuso horário.

+++

+++**Atualização de manutenção em sexta-feira, 23 de janeiro de 2025**

### Atualização de manutenção em sexta-feira, 23 de janeiro de 2025

#### Relatórios

**Campos de moeda personalizados causam erro de relatório**

Quando uma exibição de relatório contém dois ou mais campos de moeda personalizados, o relatório retorna um erro.

#### Usuários

**A marca &quot;Não Registrado&quot; persiste após o logon**

Apesar de fazer logon com sucesso pelo menos uma vez, a tag &quot;não registrada&quot; não desaparece como esperado para novos usuários.

+++

+++**Atualização de manutenção em sexta-feira, 16 de janeiro de 2025**

### Atualização de manutenção em sexta-feira, 16 de janeiro de 2025

#### Documentos

**Erro &quot;Alterações não salvas&quot; ao adicionar um formulário a um documento**

Ao adicionar um formulário a um documento, um erro &quot;Alterações não salvas&quot; é exibido e impede a interação com o aplicativo.

#### Provas

**O nome da prova não aparece na guia do navegador**

Quando um usuário visualiza uma prova, o nome da prova não fica visível na guia do navegador. Em vez disso, a guia do navegador exibe &quot;Workfront&quot;.

#### Solicitações e problemas

**Erro com atribuições de usuário avançadas**

Quando um usuário tenta fazer uma Atribuição avançada de usuário em uma solicitação ou problema, o usuário não é atribuído e o usuário vê o seguinte erro:

“Ocorreu um erro e estamos trabalhando para resolver o problema. Para continuar com seu trabalho, tente atualizar esta página do navegador.“

Atualizar a página do navegador é ineficaz.

#### Solicitações

**Não é possível criar solicitações em ambientes de Visualização**

Ao tentar criar uma nova solicitação em um ambiente de Pré-visualização da sandbox, um erro informando que a fila de solicitações não está mais disponível é exibido e a solicitação não pode ser criada.

+++

## Atualizações de manutenção anteriores

Informações sobre atualizações de manutenção anteriores estão disponíveis aqui:

* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2024](2024-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2023](2023-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2022](2022-updates.md)
* [Arquivo de atualizações de manutenção do [!DNL Workfront] - 2021](2021-updates.md)
