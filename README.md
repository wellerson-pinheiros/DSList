# 📦 Projeto Java com Spring Boot

Este projeto foi desenvolvido utilizando **Java** e o framework **Spring Boot**, com foco em criar uma aplicação robusta, escalável e de fácil manutenção. A persistência de dados é gerenciada via **JPA**, com suporte a múltiplos bancos de dados: **PostgreSQL** em ambiente de produção e **H2** em ambiente de desenvolvimento.

---

## 🚀 Tecnologias Utilizadas

- **Java 17+**  
  Linguagem principal do projeto, escolhida por sua maturidade, performance e ampla comunidade.

- **Spring Boot**  
  Framework que simplifica a criação de aplicações Java, oferecendo configuração automática, servidor embutido e integração com diversos módulos como Spring Data, Security, Web, etc.

- **JPA (Java Persistence API)**  
  Abstração para persistência de dados que permite trabalhar com entidades Java e realizar operações no banco de forma orientada a objetos. Utilizamos a implementação **Hibernate** para mapear as entidades e gerenciar o ciclo de vida dos dados.

- **PostgreSQL**  
  Banco de dados relacional utilizado em ambiente de produção. Reconhecido por sua estabilidade, segurança e suporte a recursos avançados como JSON, triggers e stored procedures.

- **H2 Database**  
  Banco de dados em memória utilizado em ambiente de desenvolvimento e testes. Permite agilidade na prototipação sem necessidade de instalação ou configuração externa.

---

## ⚙️ Como Rodar o Projeto

### Pré-requisitos

- Java 17 ou superior
- Maven instalado
- IDE (Eclipse, IntelliJ, VS Code, etc.)

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-projeto.git
   
2.  Navegue até a pasta do projeto:

	cd seu-projeto
	
3. Execute o projeto : 

	./mvnw spring-boot:run
	
4. Confira se está rodando seu projeto na tela de erro inicial do Spring: 


	http:localhost:8080
	
	
### Exemplo da página de erro padrão do Spring !
	
![Página de erro padrão do Spring Boot](https://javatutorial.net/wp-content/uploads/2017/11/spring-whitelabel-error-page.jpg)
	
	

	
	
	
   