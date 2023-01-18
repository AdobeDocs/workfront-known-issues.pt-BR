---
title: Atualizações de manutenção do Workfront
description: Atualizações de manutenção do [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
source-git-commit: f85f2ffac82c14c3ad3d6b1d6e8155c61586d767
workflow-type: tm+mt
source-wordcount: '770'
ht-degree: 55%

---

# Atualizações de manutenção do [!DNL Workfront]

As seguintes atualizações de manutenção foram efetuadas em 2023.

>[!NOTE]
>
>Essas atualizações também incluem outras correções de erros menores ou menos importantes. O suporte do [!DNL Workfront] enviará uma notificação quando um problema enviado for corrigido.

Para obter atualizações de manutenção anteriores a 2023, consulte [Atualizações de manutenção anteriores](#previous-maintenance-updates)

## Atualizações em janeiro de 2023

+++**Atualização de manutenção em 18 de janeiro de 2023**

**Expressões com curingas não são válidas em campos personalizados**

_Formulários personalizados_

Quando um usuário usa um curinga, como \$$TODAY ou $$NOW, juntamente com um modificador (como &quot;-30d&quot;) em um campo personalizado, o validador não aceita o curinga como válido. Curingas sem modificadores são vistos como válidos.

**[!UICONTROL Balanceador de Carga de Trabalho] mostra horas não associadas a um projeto/tarefa/problema**

_[!UICONTROL Balanceador de carga de trabalho]_

Quando um usuário exibe a variável [!UICONTROL Balanceador de Carga de Trabalho], veem horas registradas para um usuário que não está associado a nenhum projeto, tarefa ou problema, nem são registradas como [!UICONTROL Geral] horas. Essas horas podem ser exibidas somente na visualização de 4 ou 6 semanas.

+++

+++**[!DNL Adobe Workfront Fusion]Atualização de manutenção (hotfix) em 12 de janeiro de 2023**

**erros 404 em módulos do[!DNL Workfront]**

_Workfront Fusion_

Quando um cenário é executado, um módulo do [!DNL Workfront] retorna um erro 404.

Esse problema foi relatado os seguintes módulos:

* [!UICONTROL Ler um registro]

+++

+++**Atualização de manutenção (hotfix) em 12 de janeiro de 2023**

**&quot;[!UICONTROL Boias]&quot; ao configurar um campo calculado**

_Formulários personalizados_

Quando um usuário cria ou edita um campo calculado em um formulário personalizado e inclui um campo personalizado na expressão do campo calculado, a expressão é considerada inválida. O botão [!UICONTROL Salvar] está desativado e o usuário não consegue sair do campo personalizado. Além disso, o usuário vê a seguinte mensagem abaixo do campo:

“[!UICONTROL Ops! Um erro inesperado aconteceu. Entre em contato com o Workfront para que possamos descobrir o que aconteceu e resolver o problema.]”

Remover o campo personalizado da expressão permite que o usuário salve e navegue para fora do campo.

**Não é possível definir níveis de acesso**

_Usuários_

Quando um usuário tenta alterar o nível de acesso de outro usuário, os níveis de acesso ficam esmaecidos e não é possível alterá-los. Isso ocorre mesmo quando o usuário que está tentando a alteração é um administrador do sistema.

+++

+++**Atualização de manutenção em 12 de janeiro de 2023**

**Ctrl+F ou Cmd+F não funciona como esperado em campos suspensos**

_Formulários personalizados_

Quando um usuário está preenchendo um formulário personalizado e pesquisa uma lista suspensa usando Ctrl+F ou Cmd+F e, em seguida, tenta passar para a próxima instância dessa pesquisa, a lista suspensa retorna ao topo da lista em vez de pular para a próxima instância da pesquisa. Isso ocorre quando uma lista suspensa é definida para permitir várias seleções.

**[!UICONTROL Editar relatório] a tela está em branco**

_Relatórios_

Quando um usuário está visualizando um relatório e tenta editá-lo, ele é direcionado a uma tela em branco e não consegue editar o relatório.

**As tarefas recuadas não permanecem recuadas**

_Tarefas_

Quando um usuário exibe uma lista de tarefas e recua uma tarefa, a tarefa retorna imediatamente ao seu estado original (recuado).

+++

+++**Atualização de manutenção em 5 de janeiro de 2023**

**Funcionalidade de pin disponível em [!UICONTROL Mais] menu**

_Navegação_

Os seguintes recursos agora estão disponíveis no [!UICONTROL Mais] para pinos, somente no ambiente de visualização:

* Renomear pinos
* Reorganizando pinos dentro da [!UICONTROL Mais] menu
* Mover um pino para fora do [!UICONTROL Mais] (ao fazer isso, o último pino na barra de navegação superior é movido para o [!UICONTROL Mais] menu)

**Remoção da limitação do Grupo do projeto ao adicionar usuários à equipe do projeto**

_Equipes_

Removemos a limitação que exigia que os usuários que precisam ser adicionados a uma equipe de projeto estivessem no Grupo associado ao projeto. Agora, você pode adicionar qualquer usuário ativo a uma equipe de projeto, independentemente dos grupos aos quais ele pertence.

**Novos ícones de informações para folhas de horas, perfis de folha de horas e preferências de folha de horas**

>[!NOTE]
>
>Essa atualização foi lançada no ambiente de Visualização em 3 de novembro de 2022 e agora está disponível em Produção

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
