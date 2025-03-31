# 🌐 Dominando o Protocolo HTTP e Integrando com a PokeAPI 🐾

Neste projeto, o objetivo foi aprender sobre o **Protocolo HTTP** e aplicar esse conhecimento para integrar com a **PokeAPI**, uma API pública que fornece dados sobre o universo Pokémon.

## 📚 O que é feito neste projeto?

Este projeto tem como foco principal:

1. **Compreender o Protocolo HTTP**:
   - Entender como as requisições HTTP funcionam (GET, POST, etc.).
   - Como usar essas requisições para obter dados de APIs.

2. **Integração com a PokeAPI**:
   - A PokeAPI é uma API pública que fornece dados sobre Pokémon, como nomes, tipos, habilidades e muito mais.
   - O projeto faz requisições para essa API para buscar e exibir dados sobre Pokémon de forma simples.

3. **Desenvolvimento de um servidor simples**:
   - Utilizando o **Express**, criamos um servidor que responde a requisições, permitindo ao usuário buscar informações como:
     - Dados sobre um Pokémon específico (ex.: Pikachu).
     - Listar todos os tipos de Pokémon.
     - Obter as habilidades de um Pokémon.

4. **Trabalhar com JSON**:
   - Ao consumir dados da PokeAPI, os resultados são retornados no formato **JSON**, e o projeto lida com esse formato para apresentar as informações de forma organizada.

## 💻 Funcionalidades do Projeto

- **Consultar dados de um Pokémon específico**: Com base no nome do Pokémon, você pode obter informações como ID, tipos e habilidades.
  
- **Listar os tipos de Pokémon**: Através de uma rota específica, é possível listar todos os tipos de Pokémon disponíveis na PokeAPI.

- **Obter as habilidades de um Pokémon**: É possível consultar as habilidades de um Pokémon específico.

## 🚀 Tecnologias Usadas

- **JavaScript** (Node.js)
- **Axios** (para realizar as requisições HTTP)
- **Express** (para criar o servidor)
- **PokeAPI** (API pública de dados sobre Pokémon)

## 🔧 Como Rodar o Projeto

Para rodar este projeto localmente, basta seguir esses passos simples:

1. Clone o repositório:
    ```bash
    git clone https://github.com/SavioFagundes/dominando-http-pokeapi.git
    ```

2. Instale as dependências:
    ```bash
    cd dominando-http-pokeapi
    npm install
    ```

3. Execute o servidor:
    ```bash
    npm start
    ```

O servidor estará rodando em `http://localhost:3000` e você pode começar a testar as rotas para buscar Pokémon, tipos e habilidades!
