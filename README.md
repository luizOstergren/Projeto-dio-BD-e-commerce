# Projeto dio BD e-commerce
 relação de um banco de dados de um e-commerce


O projeto consiste em definir um banco relacional de um e-commerce.

Tem como objeto principal a tabela de produtos e todos os outros fatores estão ligados a ela.
A tabela "Produtos" contem: categoria do produto, desrição e valor, alem do ID dos produtos

O estoque ta relacionado a quantidade de produtos e o lugar onde o estoque se encontra. É importante saber esta informação pois podemos encontrar um lugar mais proximp, diminuindo o valor do frete.

É de extrema importancia saber tambem qual o fornecedor de cada produto, definindo na tabela com Razão Social e CNPJ.

Além dos fornecedores, existem terceiros que vendem determinados produtos, assim, ampliando a rede de fornecimento de produtos.

O cliente apenas poderá ser PJ ou PF. Este cliente pode fazer mais de um pedido e o mesmo pode conter mais de um produto.

Os produtos podem ter mais de uma forma de pagamento. Após feito o pagamento, sera feita a entrega do produto, o qual irá informar o status e o código de rastreamento do produto.