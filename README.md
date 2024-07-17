# ForumHub

ForumHub é uma aplicação para gerenciar tópicos de discussão em um fórum, desenvolvida utilizando Java e o framework Spring.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
- **Hibernate**
- **MySQL**

## Funcionalidades

1. **Criação de Tópicos:** Permite criar novos tópicos com título, mensagem e associá-los a cursos específicos.
2. **Listagem de Tópicos:** Exibe uma lista paginada dos tópicos disponíveis no fórum.
3. **Atualização de Tópicos:** Permite atualizar o título e a mensagem de um tópico existente.
4. **Respostas:** Os usuários podem responder aos tópicos existentes.
5. **Gestão de Cursos:** Administração dos cursos associados aos tópicos.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- **`src/main/java`:** Contém o código-fonte Java.
    - **`br.com.alura.forumhub.forumHub.controller`:** Controladores da aplicação.
    - **`br.com.alura.forumhub.forumHub.domain`:** Entidades de domínio, como `Topico`, `Curso`, `Autor`, entre outras.
    - **`br.com.alura.forumhub.forumHub.domain.autor`:** Classes relacionadas aos autores dos tópicos.
    - **`br.com.alura.forumhub.forumHub.domain.curso`:** Classes relacionadas aos cursos associados aos tópicos.
    - **`br.com.alura.forumhub.forumHub.domain.topicos`:** Classes relacionadas aos tópicos do fórum.
    - **`br.com.alura.forumhub.forumHub.repository`:** Repositórios para acesso aos dados.
- **`src/main/resources`:** Recursos da aplicação.
    - **`application.properties`:** Configurações da aplicação, como configurações do banco de dados.
    - **`data.sql`:** Script SQL para inicialização dos dados iniciais.

## Como Executar o Projeto

1. **Pré-requisitos:**
    - Java JDK 11 ou superior instalado.
    - MySQL Server instalado e configurado.

2. **Configuração do Banco de Dados:**
    - Crie um banco de dados no MySQL chamado `forumhub`.
      - Configure as credenciais de acesso no arquivo `application.properties`.

3. **Execução:**
    - Clone o repositório do projeto.
   ```bash
    git clone https://github.com/seu-usuario/forumhub.git
    cd forumhub
   ```
   - Importe o projeto em sua IDE preferida (IntelliJ IDEA, Eclipse, etc.).
   - Execute a classe principal `ForumHubApplication.java`.

4. **Testando a Aplicação:**
    - Acesse `http://localhost:8080` em seu navegador.
    
