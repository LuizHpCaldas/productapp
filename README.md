# Desafio Técnico - Oak Tecnologia

Este é um projeto de exemplo criado como parte de um desafio técnico para a Oak Tecnologia. A aplicação permite o cadastro e a listagem de produtos, com funcionalidades específicas descritas abaixo.

## Funcionalidades

### Cadastro de Produtos

- **Formulário com os seguintes campos:**
  - Nome do produto (campo de texto)
  - Descrição do produto (campo de texto)
  - Valor do produto (campo de valor)
  - Disponível para venda (campo com 2 opções: sim / não)

### Listagem de Produtos

- **Colunas da listagem:**
  - Nome
  - Valor
- **Ordenação:**
  - Ordenado por valor do menor para o maior
- **Ações:**
  - Ao cadastrar um novo produto, a listagem é exibida automaticamente
  - Existe um botão para cadastrar um novo produto a partir da listagem

## Estrutura do Projeto

```plaintext
src/main/java/com/example/productapp
|-- ProductAppApplication.java
|-- controller
|   |-- ProductController.java
|-- model
|   |-- Product.java
|-- repository
|   |-- ProductRepository.java
|-- service
    |-- ProductService.java
|
src/main/resources
|-- application.properties
|-- templates
    |-- product_form.html
    |-- product_list.html
