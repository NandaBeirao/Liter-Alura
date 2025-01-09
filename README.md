# Liter-Alura

## Descrição

Liter-Alura é uma aplicação Java que permite gerenciar livros e autores utilizando JPA (Java Persistence API) com Hibernate e um banco de dados PostgreSQL. A aplicação oferece diversas funcionalidades para buscar e listar livros e autores, bem como obter estatísticas e curiosidades.

[Link para vídeo - demo (13 min)](https://youtu.be/S_Wtcx2KEOc)

## Funcionalidades

1. **Buscar livro por título e/ou autor (e adicionar ao banco próprio)**
2. **Buscar por nome do autor no repositório**
3. **Listar livros registrados**
4. **Listar autores registrados**
5. **Listar autores vivos em um determinado ano**
6. **Listar livros por idioma**
7. **Estatísticas baseadas em API**
8. **Estatísticas baseadas no repositório**
9. **Curiosidades com anos**

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- **Modelos**: Definição das entidades `Autor` e `Livro`.
- **Repositórios**: Interfaces que definem os métodos de acesso ao banco de dados para as entidades `Autor` e `Livro`.
- **Serviços**: Classe `LivroService` que fornece métodos para a busca de livros em uma API externa.
- **Principal**: Classe `Principal` que contém o método `main` e a lógica da aplicação.

## Requisitos

- Java 8 ou superior
- Maven
- PostgreSQL
- Dependências do Maven para JPA, Hibernate e PostgreSQL

## Uso

Ao executar a aplicação, será exibido um menu no console com as seguintes opções:

## Menu de Opções

### Bem-vindo ao Liter-Alura

1. **Buscar livro por título e/ou autor** (e adicionar ao banco próprio)  
2. **Buscar por nome do autor no repositório**  
3. **Listar livros registrados**  
4. **Listar autores registrados**  
5. **Listar autores vivos em um determinado ano**  
6. **Listar livros por idioma**  
7. **Estatísticas (API)**  
8. **Estatísticas (Repositório)**  
9. **Curiosidades com anos**  

0. **Sair**



## Configuração

1. **Clonar o repositório:**

```bash
git clone <url_do_repositorio>
cd liter-alura


