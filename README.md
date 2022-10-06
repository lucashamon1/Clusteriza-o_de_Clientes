# Clusterização_de_Clientes

Problema de Negócio:
Apartir da base de dados de clientes de um banco queremos criar estratégias para aumentar o lucro da instituição.

O que foi feito:
Separou-se os clientes em grupos, chamados de clusters no contexto de ciência de dados, com base no comportamento desses clientes.
Chegamos a 5 grupos que ficaram divididos assim:
grupo 1 = CLUSTER 0: menor limite de crédito; pagamento menor que o gasto; menos clientes
grupo 2 = CLUSTER 1: gastam muito com compras no cartão; pagamento maior que o gasto; melhores pagadores
grupo 3 = CLUSTER 2: gastam muito com saques; pagamentos bem maior do que o gasto
grupo 4 = CLUSTER 3: menores gastos; maior limite de crédito; mais clientes
grupo 5 = CLUSTER 4: maiores gastos; menor valor em compras; valor considerável de saques; pagamento bem abaixo do valor gasto; piores pagadores

Com base na ánalise desses grupos vemos que podemos ter como estratégia de negócio:
-Estimular os clientes do cluster 3 a gastarem mais
-Outros clusters bons para estimular o consumo são o cluster 1 e o cluster 2
-Clusters 0 e 4 estão entre os piores pagadores (o que os diferencia é que o cluster 0 tem pouco limite e o cluster 4 tem bastante limite) portanto deve-se buscar a realização de ações para diminuir a inadimplencia desses grupos 
