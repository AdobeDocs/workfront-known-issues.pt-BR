---
title: 'Usuários: o emblema de aprovação pendente é exibido em novos usuários'
description: Novos usuários do Workfront podem ser exibidos na lista de usuários com um emblema de aprovação pendente. O emblema persiste por mais de alguns minutos e continua presente quando a página é atualizada.
hidefromtoc: true
feature: People Teams and Groups
exl-id: 27db1155-f6aa-465d-a42b-1147cf5431e1
source-git-commit: 39a085b629d6d2afc5a198e47ca639d2bb431b0d
workflow-type: ht
source-wordcount: '245'
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
