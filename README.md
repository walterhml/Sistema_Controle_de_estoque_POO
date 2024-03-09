# Sistema_Controle_de_estoque_POO,
# Documentação Técnica

## Classe Produto

A classe `Produto` representa um produto genérico em um estoque. Ela possui três atributos:

- `nome`: uma string que representa o nome do produto.
- `quantidadeDisponivel`: um número que representa a quantidade disponível do produto.
- `precoUnitario`: um número que representa o preço unitário do produto.

A classe `Produto` também possui o seguinte método:

- `calcularValorTotal()`: este método calcula e retorna o valor total do produto, multiplicando a quantidade disponível pelo preço unitário.

## Classe ProdutoPerecivel

A classe `ProdutoPerecivel` é uma subclasse de `Produto` que representa um produto perecível. Ela possui um atributo adicional:

- `dataValidade`: um objeto Date que representa a data de validade do produto.

A classe `ProdutoPerecivel` também possui o seguinte método:

- `verificarValidade()`: este método verifica se o produto perecível está dentro da data de validade, retornando true se estiver válido e false caso contrário.

## Classe Estoque

A classe `Estoque` representa o estoque de produtos. Ela possui um atributo:

- `produtos`: um array que representa a lista de produtos no estoque.

A classe `Estoque` também possui os seguintes métodos:

- `adicionarProduto(produto)`: este método adiciona um produto à lista de produtos no estoque.
- `removerProduto(nome)`: este método remove um produto da lista pelo nome.
- `verificarEstoqueDisponivel(nome)`: este método verifica e exibe a quantidade disponível de um produto pelo nome.
- `calcularValorTotalEstoque()`: este método calcula e exibe o valor total do estoque, somando o valor total de cada produto.

## Exemplo de Uso

O exemplo de uso mostra como criar um estoque, adicionar produtos e produtos perecíveis ao estoque, e usar os métodos da classe `Estoque` para manipular o estoque.
