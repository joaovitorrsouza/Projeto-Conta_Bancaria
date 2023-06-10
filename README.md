Comecei definindo os atributos da classe: "Nome" e "Saldo". Em seguida, criei os métodos necessários para exibir o saldo, depositar e sacar valores da conta.

Entretanto, decidi ir além das funcionalidades básicas e adicionar novas características ao projeto. Primeiro, implementei o histórico de depósitos e saques, utilizando uma lista chamada "extrato" para armazenar as transações. Cada vez que uma transação ocorria, eu adicionava uma entrada ao extrato, indicando se era um depósito ou saque, juntamente com o valor.

Em seguida, adicionei uma taxa para os saques, que era calculada como 5% do valor do saque. Verifiquei se o saldo era suficiente para cobrir o valor do saque mais a taxa. Caso contrário, exibia uma mensagem de "Valor Insuficiente". Caso houvesse saldo suficiente, registrava a taxa no extrato e deduzia o valor total do saque do saldo.

Além disso, decidi adicionar um limite de saque para evitar que o usuário fizesse saques excessivos. Defini um limite de 100 unidades monetárias e registrei o valor total de saques em uma variável chamada "saque_total". Se o limite fosse atingido, exibia a mensagem "Limite Atingido".

Por fim, implementei a função de transferência entre contas. Ao chamar o método "transferir", deduzi o valor transferido da conta atual e usei o método "depositar" da conta de destino para adicionar o valor transferido. Registrei a transferência no extrato de ambas as contas.

Depois de finalizar a implementação, criei duas instâncias da classe "ContaBancaria" para testar as funcionalidades. Realizei um depósito na primeira conta, seguido de um saque. Em seguida, transferi uma quantia da segunda conta para a primeira. Por fim, exibi o saldo das duas contas para verificar se as operações foram executadas corretamente.

Fiquei satisfeito com o resultado do projeto, pois consegui criar uma classe funcional que permitia ao usuário realizar diversas operações bancárias e manter um histórico detalhado das transações. Essa experiência me ensinou muito sobre programação orientada a objetos e a importância de planejar e implementar recursos adicionais para melhorar a funcionalidade de um projeto.
