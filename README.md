# ScreenMatch

Este é um projeto em Java que organiza informações sobre filmes, com funcionalidades para busca, listagem e organização por ano de lançamento. Ele é dividido em várias classes, cada uma com um propósito específico.

## 🔧 Tecnologias Usadas

- **Java**: Linguagem de programação utilizada para desenvolver a lógica do programa.
- **API OMDb**: Usada para buscar informações sobre filmes como título, ano de lançamento, duração, etc.
- **JSON**: Formato utilizado para representar os dados dos filmes de forma estruturada.

## 📌 Funcionalidades

- **PrincipalComBusca**: Esta classe permite que o usuário digite o nome de um filme e consulte uma API (como o [OMDb API](http://www.omdbapi.com/)) para retornar informações detalhadas sobre o filme, como ano de lançamento, duração e outros dados.
- **PrincipalComLista**: Organiza uma lista de filmes por ano de lançamento e exibe essa lista de forma ordenada.
- **Principal**: Exibe o tamanho do array de filmes e o primeiro filme da lista.

## Como Usar

1. **Clone o repositório**
2. Abra o projeto no IntelliJ IDEA ou qualquer IDE de sua preferência.
3. Compile e execute o programa

## Como Funciona

* PrincipalComBusca:
A classe usa uma API externa (OMDb) para buscar dados de filmes.
A API retorna informações como título, ano de lançamento, duração, entre outros, que são armazenadas e exibidas no formato JSON.

* PrincipalComLista:
Recebe um array de objetos Filme e organiza a lista por ano de lançamento, mostrando a lista de filmes ordenada.

* Principal:
Mostra o tamanho do array de filmes e o primeiro filme inserido.

## Dependências

* Este projeto faz uso de uma API externa (*OMDb*) e pode necessitar de uma chave de API. Não se esqueça de configurar a chave da API para o funcionamento da classe PrincipalComBusca.

*________________________________________________________________________________________________*

# ScreenMatch

This is a Java project that organizes movie information, with features for searching, listing, and organizing by release year. It is divided into several classes, each with a specific purpose.

## 🔧 Technologies Used

- **Java**: The programming language used to develop the logic of the program.
- **OMDb API**: Used to fetch movie information such as title, release year, duration, etc.
- **JSON**: The format used to represent movie data in a structured way.

## 📌 Features

- **PrincipalComBusca**: This class allows the user to input a movie name and query an API (such as [OMDb API](http://www.omdbapi.com/)) to return detailed information about the movie, such as release year, duration, and other data.
- **PrincipalComLista**: Organizes a list of movies by release year and displays this list in an ordered way.
- **Principal**: Displays the size of the movie array and the first movie in the list.

## How to Use

1. **Clone the repository**:
2. Open the project in IntelliJ IDEA or any IDE of your choice.
3. Compile and run the program:

## How It Works

* PrincipalComBusca:
  The class uses an external API (OMDb) to fetch movie data.
  The API returns information such as title, release year, duration, etc., which is stored and displayed in JSON format.

* PrincipalComLista:
  Receives an array of Filme objects and organizes the list by release year, displaying the ordered movie list.

* Principal:
  Displays the size of the movie array and the first movie entered.

## Dependencies

* This project uses an external API (OMDb) and may require an API key. Don’t forget to configure the API key for the PrincipalComBusca class to work.