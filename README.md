Task Management System
Um sistema simples de gerenciamento de tarefas desenvolvido em Java, com autenticação via JWT. O objetivo do projeto é demonstrar habilidades práticas em backend Java, APIs REST e segurança com Spring Boot.

Sobre o projeto
O Task Management System permite que usuários se cadastrem, façam login e gerenciem suas tarefas de forma simples e eficiente. Cada usuário pode criar, listar, editar e deletar suas próprias tarefas, tudo com proteção por autenticação JWT.

Ideal para quem quer um exemplo prático de como criar uma API REST segura com Java e Spring Boot!

Funcionalidades
Cadastro e login de usuários

Autenticação com JWT

Criação de tarefas

Listagem de tarefas do usuário logado

Edição e exclusão de tarefas

Estrutura RESTful padrão

Tecnologias Utilizadas
Java 17+

Spring Boot

Spring Security

JWT (JSON Web Token)

Maven

JPA/Hibernate

Estrutura do Projeto
src/
└── main/
└── java/
└── com/
├── Cp1Java/
│ └── task_management_system/
│ └── TaskManagementSystemApplication.java
└── example/
├── config/
├── controller/
├── dto/
├── filter/
├── model/
├── repository/
└── security/

controller/: Endpoints REST

model/: Entidades do sistema (User, Task)

repository/: Integração com o banco de dados

security/ e filter/: Autenticação e segurança com JWT

dto/: Objetos de transferência de dados

Como rodar o projeto localmente
Clone o repositório
git clone https://github.com/seuusuario/CP1Java.git
cd CP1Java

Compile o projeto
./mvnw clean install

Inicie a aplicação
./mvnw spring-boot:run

Acesse a API localmente em http://localhost:8080

Obs.: Não esqueça de configurar o banco de dados no application.properties conforme seu ambiente.

Autor
Vinicius Becker
Projeto desenvolvido para fins acadêmicos.
