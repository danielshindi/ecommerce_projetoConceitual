# Projeto conceitual de banco de dados - E-commerce

- **Produto**
  - Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
  - Cada produto possui um fornecedor
  - Um ou mais produtos podem compor um pedido
    
- **Cliente**
  - O cliente pode se cadastrar no site com seu CPF ou CNPJ
  - o valor do frete será calculado pelo endereço que o cliente especificar
  - Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto
    
- **Pedido**
  - Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
  - Um produto ou mais compoem o pedido
  - O pedido pode ser cancelado
    
- **Fornecedor e estoque**
  - A quantidade em estoque de um produto está especificado na relação entre estoque e produto.
  - Produto possui um ou mais fornecedores.

#### Refinando:

- Cliente PJ e PF - uma conta pode ser PJ ou PF, mas não pode ter as duas informações
- Pagamento - pode ter cadastrado mais de uma forma de pagamento
  - cartão: id e nome
- Entrega - possui status e código de rastreio
