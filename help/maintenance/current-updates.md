---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: f60d2cab1983c7486ca611050de5ee53596c9e05
workflow-type: tm+mt
source-wordcount: '1482'
ht-degree: 73%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2023.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em fevereiro de 2023

+++**(Planejado) Atualização de manutenção em 9 de fevereiro de 2023**

Esta atualização inclui apenas correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

+++

+++**Atualização de manutenção em 8 de fevereiro de 2023**

**Botão Filtrar na coluna de entrada**

_Quadros_

A coluna de entrada em um quadro agora inclui um **Adicionar um filtro** quando a coluna estiver vazia e nenhum filtro tiver sido criado. O botão abre a área de configuração, onde você pode adicionar filtros para trazer tarefas e problemas para a coluna de entrada.

+++

+++**Atualização de manutenção em 2 de fevereiro de 2023**

**O ícone Quadros aparece no Menu principal por padrão**

_Quadros_

O ícone Quadros agora aparece no Menu principal para usuários que não têm um modelo de layout. Os quadros também são incluídos no Menu principal por padrão em qualquer novo modelo de layout criado. Os modelos de layout existentes não foram alterados.

**Não é possível salvar modelos de email**

_Configuração_

Quando um usuário tenta criar ou editar um modelo de email, o botão [!UICONTROL Salvar] não responde e não é possível salvar o modelo.

+++

+++**Atualização de manutenção em 30 de janeiro de 2023**

**Atalhos de teclado adicionados para ações comuns da folha de ponto**

_Folhas de horas_

Introduzimos os seguintes atalhos de teclado para as seguintes ações comumente executadas dentro de uma folha de ponto:

* Adicionar linha (Cmd+Option++ / Ctrl+Option+)
* Excluir linha (Cmd+Option+- / Ctrl+Option+-)
* Fixar ou Desfixar um item de trabalho (Opção+P / Opção+P)
* Abrir comentário (Shift+F2 / Shift+F2)
* Salvar comentário (Cmd+Enter / Ctrl+Enter)
* Expandir (Shift+Opção+Seta para cima/ Shift+Alt+Seta para cima)
* Recolher (Shift+Option+Seta para baixo/ Shift+Alt+Seta para baixo)

A área onde essas ações são executadas deve ser realçada para que sejam aplicadas.

**Novos ícones de informações para folhas de horas, perfis de folha de horas e preferências de folha de horas**

_Folhas de horas_

>[!NOTE]
>
>Essa atualização foi lançada somente no ambiente de Visualização em 3 de novembro de 2022 e agora está disponível em Produção.

Adicionamos vários ícones de informações às seguintes configurações:

* &quot;[!UICONTROL Pode editar tempo]&quot;caixa de seleção ao criar ou editar uma folha de ponto ou um perfil de folha de ponto para indicar que, quando ativada, os aprovadores também podem enviar, reabrir ou editar a folha de ponto, a menos que o administrador restrinja essas ações na variável [!UICONTROL Preferências da folha de ponto] área de [!UICONTROL Configuração].
* &quot;[!UICONTROL Restringir edição de folha de ponto a proprietários e administradores]&quot; na [!UICONTROL Folha de Horas e Preferências de Hora] área de [!UICONTROL Configuração] para indicar que, quando desativado, os usuários a seguir também podem editar as folhas de horas: usuários com acesso administrativo a folhas de ponto e horas, aprovadores de folha de ponto com permissão para editar tempo e gerentes de proprietários de folha de ponto.

Observe que a funcionalidade dessas configurações não foi alterada e somente os ícones de informações foram adicionados para esclarecer o escopo das configurações.

+++

+++**Atualização de manutenção em 26 de janeiro de 2023**

**Erro ao enviar solicitação de[!DNL Outlook]**

_Integrações_

Quando um usuário tenta enviar uma solicitação com anexos de um email do [!DNL Outlook], um ou mais anexos não são carregados e o usuário vê o seguinte erro:

“[!UICONTROL Ocorreu o seguinte erro: o arquivo com o identificador xxxx não existe.]”

Isso ocorre somente quando uma atribuição é feita para a nova solicitação, seja por meio da fila de solicitações ou manualmente ao criar a solicitação.

**Nova versão do Visualizador de Verificação de Verificação Linguística para Desktop**

_Prova_

Para corrigir um problema de congelamento no Desktop Proofing Viewer, implantamos uma nova versão do visualizador de prova de desktop. Os usuários que já tiverem o Desktop Proofing Viewer instalado receberão esta atualização automaticamente.

Os usuários também podem baixar manualmente a versão mais recente. Para obter mais informações, consulte [Instale o Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

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

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção (Hot Fix) em 12 de janeiro de 2023**

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
