# API REST com CRUD e padrões de projeto Facade, Singleton e Strategy

Este é um projeto de exemplo para demonstrar o uso de padrões de projeto em uma API RESTful de cadastro de clientes, usando o Spring Framework. O objetivo do projeto é ilustrar como os padrões de projeto podem ajudar a simplificar a lógica de negócios e tornar o código mais legível, escalável e fácil de manter.

O projeto consiste em uma API RESTful simples que permite que os usuários realizem as operações básicas de CRUD, com uma base de dados de clientes, sendo necessário apenas a inserção do nome e cep para inserir um novo cliente e obter seu endereço .

## Tecnologias utilizadas

- Java
- Spring Boot
- H2 Database
- Hibernate
- JPA

## Funcionalidades

A API permite realizar as seguintes operações:

- Criar um novo cliente
- Ler os dados de um cliente
- Atualizar os dados de um cliente 
- Excluir um cliente pelo id

## Padrões de projeto

### Facade
Padrão estrutural que fornece uma interface simplificada para um conjunto de subsistemas mais complexos. Ele esconde a complexidade do subsistema e fornece uma interface simples e unificada para os clientes, tornando a utilização do sistema mais fácil e intuitiva.

### Strategy
Padrão comportamental que permite definir um conjunto de algoritmos, encapsular cada um como uma classe separada e torná-los intercambiáveis. O objetivo é permitir que o algoritmo possa variar independentemente dos clientes que o utilizam.


### Singleton
Padrão de criação que garante que uma classe tenha apenas uma instância, e fornece um ponto global de acesso para essa instância. É comumente utilizado para classes que representam recursos compartilhados, como conexões com bancos de dados, ou para implementar gerenciadores de configuração.
 


