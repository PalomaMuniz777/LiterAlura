README.md - LiterAlura: Um Catálogo de Livros

O LiterAlura é um desafio de programação que visa construir um catálogo de livros utilizando as seguintes tecnologias:

Java: Linguagem de programação principal.
Spring Boot: Framework para desenvolvimento de aplicações web.
PostgreSQL: Sistema de gerenciamento de banco de dados relacional.
API Gutendex: API para consultar dados de livros do Project Gutenberg.
Jackson: Biblioteca Java para manipulação de JSON.
Spring Data JPA: Framework para persistência de dados.
Objetivo
Desenvolver um catálogo de livros que ofereça interação textual (via console) com os usuários, proporcionando no mínimo 5 opções de interação. Os livros serão buscados através da API Gutendex.

Funcionalidades
Busca de livro por título: Consulta a API Gutendex e insere o livro no banco de dados.
Listagem de todos os livros: Exibe todos os livros registrados no banco de dados.
Lista de autores: Exibe todos os autores dos livros registrados.
Listar autores vivos em determinado ano: Exibe autores que estavam vivos em um ano específico.
Listar livros em determinado idioma: Exibe livros em um idioma específico.
Como Executar o Projeto
Clone o repositório:

git clone [repositório-github]

Importe para o IntelliJ IDEA:

Abra o IntelliJ IDEA.
Vá em “File” > “Open” e selecione a pasta do projeto clonado.
Configure o Banco de Dados PostgreSQL:

Baixe e instale o PostgreSQL: Download PostgreSQL.
Crie um novo banco de dados chamado “literatura”.
Configure as credenciais do banco de dados no arquivo application.properties.
Execute a aplicação:

Clique no botão “Run” no IntelliJ IDEA (ou pressione Shift + F10).
Instruções Adicionais
Dependências: Certifique-se de que as dependências do projeto estejam configuradas corretamente no arquivo pom.xml.
Testes: A aplicação inclui testes unitários que podem ser executados para verificar o funcionamento do código.
Documentação: A documentação da API Gutendex pode ser encontrada em Gutendex API.
Próximos Passos
Implementar estatísticas sobre os livros, como a quantidade de livros em cada idioma.
Implementar a busca de autor pelo nome do autor.
Implementar a listagem de autores com outros formatos de consultas.
Contribuições
Contribuições são bem-vindas! Abra um “issue” para reportar bugs ou sugestões de melhorias.
