---
title: 'Usuários: o emblema de aprovação pendente é exibido em novos usuários'
description: Novos usuários do Workfront podem ser exibidos na lista de usuários com um emblema de aprovação pendente. O emblema persiste por mais de alguns minutos e continua presente quando a página é atualizada.
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: 254442ca-6997-5cfa-963e-f420870aea53
    internal-label: People Teams and Groups
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
source-git-commit: 70ec59e07299bc7d7bb4649c67dff23161a50efa
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 100%
---
# Usuários: o selo de “Aprovação pendente” é exibido em novos usuários

>[!NOTE]
>
>Esse problema pode estar presente em organizações migradas para o Adobe Admin Console.

Novos usuários do Workfront podem ser exibidos na lista de usuários com um emblema de “Aprovação pendente”. O emblema persiste por mais de alguns minutos e continua presente quando a página é atualizada.

Esse problema é agravado quando os usuários são inseridos em lotes grandes, como de uma planilha ou de um Kick-Start do Workfront.

O comportamento esperado é que o emblema desapareça após alguns minutos e não esteja presente quando a página for atualizada.

## Soluções alternativas

Isso ocorre quando usuários adicionados ao Workfront não são sincronizados com o Adobe Admin Console.

Recomendamos as seguintes soluções:

### Resolver usuários individualmente

É possível resolver usuários individuais na lista Usuários.

1. Selecione um ou mais usuários na lista Usuários.
1. Clique no menu de três pontos no cabeçalho da lista.
1. Selecione **Aprovar**.
1. Após alguns minutos, atualize a página.

### Resolver usuários adicionados em um lote grande

Para resolver os usuários que foram adicionados em um lote grande, é possível adicionar o lote de usuários diretamente ao Adobe Admin Console.

Para obter instruções, consulte [Gerenciar vários usuários | Upload em massa de CSV](https://helpx.adobe.com/br/enterprise/using/bulk-upload-users.html) na documentação da Adobe.


_Relatado pela primeira vez em 8 de maio de 2025._
