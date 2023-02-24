 # Sistema de gerenciamento de estoque de produtos
Este projeto consiste em dois arquivos Java, "Program.java" e "Product.java". Ambos fazem parte de um sistema de gerenciamento de estoque de produtos.

O arquivo "Product.java" contém a classe Product que possui três atributos: name (nome do produto), price (preço do produto) e quantity (quantidade em estoque do produto). A classe Product também possui três métodos:

totalValueInStock(): calcula e retorna o valor total do estoque de produtos multiplicando o preço do produto pela quantidade em estoque.

addProducts(int quantity): adiciona a quantidade de produtos especificada ao estoque do produto.

removeProducts(int quantity): remove a quantidade de produtos especificada do estoque do produto.

Já o arquivo "Program.java" contém a classe Program que contém o método main. Esse método é responsável por instanciar um objeto da classe Product e preencher seus atributos com informações fornecidas pelo usuário através de entrada de dados.

Uma vez que o usuário tenha fornecido as informações necessárias, a aplicação é encerrada.

Este projeto é apenas um exemplo simples de como as classes podem ser usadas para gerenciar informações sobre produtos em um sistema de estoque. Ele pode ser estendido e modificado para atender a outras necessidades de gerenciamento de estoque mais complexas.
