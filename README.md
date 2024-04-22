-- MARCELO WORMA --

Escopo: Venda de Produtos

- ENTIDADES
* PRODUTO
* CLIENTE
* ESTOQUE
* PEDIDO
* FORNECEDOR

Narrativas:
- PRODUTO
* Os produtos serão vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);
* Cada produto possui um fornecedor;
* Um ou mais produtos podem compor um pedido.

- CLIENTE
* O cluente pode se cadastrar bi sute com seu CPF ou CNPJ;
* O endereço do cliente irá determinar o valor do frete;
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

- PEDIDO
* Os pedidos são criados por clientes e possuem informações de compra, endereço e status de entrega;
* Um produto ou mais compoem o pedido;
* O pedido pode ser cancelado.

Refinando:
* Cliente PJ ou PF - Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
* Pagamento - Pode ter cadastrado mais de uma forma de pagamento;
* Entrega - Possui status e código de rastreio.
