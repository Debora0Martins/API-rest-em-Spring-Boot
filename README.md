NewPJ 
Descrição

Aplicativo Spring Boot para gerenciamento de produtos.
Permite criar, listar e consultar produtos usando H2 Database em memória. Ideal para aprendizado de Spring Data JPA e APIs REST.

Funcionalidades
	•	Listar todos os produtos (GET /produtos)
	•	Criar um produto (POST /produtos)
	•	Acesso ao H2 Console (http://localhost:8080/h2-console)

Tecnologias
	•	Java 17
	•	Spring Boot
	•	Spring Data JPA
	•	H2 Database (em memória)
	•	Maven

Configurações de Perfil
	•	application.properties → Configurações padrão
	•	application-dev.properties → Ambiente de desenvolvimento
	•	application-prod.properties → Ambiente de produção

 Como Executar
	1.	Clone o repositório:
 git clone https://github.com/SeuUsuario/NewPJ.git

 Entre na pasta do projeto:
 cd NewPJ

 Execute a aplicação no terminal:
 mvn spring-boot:run

 Acesse a API:

	•	Produtos: http://localhost:8080/produtos
	•	H2 Console: http://localhost:8080/h2-console
	•	JDBC URL: jdbc:h2:mem:meubanco
	•	User Name: sa
	•	Password: (vazio)

Estrutura do Projeto

src
 └── main
     ├── java
     │   └── com.example.newpj
     │       ├── controller
     │       ├── model
     │       └── repository
     └── resources
         ├── application.properties
         ├── application-dev.properties
         └── application-prod.properties

         
