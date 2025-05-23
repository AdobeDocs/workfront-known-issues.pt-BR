---
title: 'Usuários: o selo de aprovação pendente é exibido para novos usuários'
description: Novos usuários no Workfront podem ser exibidos na lista de usuários com um selo de aprovação pendente. O selo persiste por mais de alguns minutos e ainda está presente quando a página é atualizada.
hidefromtoc: true
feature: People Teams and Groups
source-git-commit: 9c46f9006fa25481a012619a16d627e16f23c15e
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 1%

---


# Usuários: o selo &quot;Aprovação pendente&quot; é exibido em novos usuários

>[!NOTE]
>
>Esse problema pode estar presente em organizações que migraram para a Adobe Admin Console.

Novos usuários no Workfront podem ser exibidos na lista de usuários com um selo de &quot;Aprovação pendente&quot;. O selo persiste por mais de alguns minutos e ainda está presente quando a página é atualizada.

Esse problema é exacerbado quando os usuários são carregados em lotes grandes, como de uma planilha ou de um Início do Workfront.

O comportamento esperado é que o selo desapareça após alguns minutos e não esteja presente quando a página for atualizada.

## Soluções alternativas

Isso ocorre quando usuários adicionados ao Workfront não são sincronizados com a Adobe Admin Console.

Recomendamos as seguintes soluções alternativas:

### Resolver usuários individuais

Você pode resolver usuários individuais na lista Usuários.

1. Selecione o usuário ou usuários na lista Usuários.
1. Clique no menu de três pontos no cabeçalho da lista.
1. Selecione **Aprovar**.
1. Após alguns minutos, atualize a página.

### Resolver usuários adicionados em um lote grande

Para resolver usuários que foram adicionados em um lote grande, é possível adicionar o lote de usuários diretamente ao Adobe Admin Console.

Para obter instruções, consulte [Gerenciar vários usuários | Upload em massa de CSV](https://helpx.adobe.com/br/enterprise/using/bulk-upload-users.html) na documentação do Adobe.


_Relatado pela primeira vez em sexta-feira, 8 de maio de 2025._
