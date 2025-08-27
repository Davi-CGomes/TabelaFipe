# 🚗 Tabela Fipe - API

Este projeto é uma aplicação **Java Spring Boot** que fornece acesso e manipulação de informações da **Tabela Fipe**, permitindo consultar preços de veículos de forma prática e organizada.

## 📌 Tecnologias Utilizadas
- Java 17+  
- Spring Boot  
- Maven  
- REST API

## 🔨 Objetivos do projeto

- O objetivo do projeto é ter um fluxo similar ao que é feito no site, porém com algumas melhorias.
- Foi criado um projeto Spring com linha de comando, utilizando a classe Scanner para fazer interações com o usuário via terminal.
- É solicitado que o usuário digite o tipo de veículo desejado (carro, caminhão ou moto).
- Feito isso, é listado todas as marcas daquele tipo de veículo, solicitando que o usuário escolha uma marca pelo código.
- Após essa escolha, é listado todos os modelos de veículos daquela marca.
- É solicitado que o usuário digite um trecho do modelo que ele quer visualizar, por exemplo **PALIO**.
- É listado apenas os modelos que tiverem a palavra **PALIO** no nome.
- Usuário escolherá um modelo específico pelo código e, diferente do site, já listaremos as avaliações para **TODOS** os anos disponíveis daquele modelo.


