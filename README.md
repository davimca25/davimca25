# Davi Monteiro

Estou no 3º período de Engenharia de Computação e já coloquei uma API para rodar na AWS, construí um e-commerce com 4 microsserviços orientados a eventos e desenvolvi o sistema de rotas de um projeto real com Google Maps. Busco um estágio em back-end, cloud ou DevOps.

O que já construí:

Catalog Manager: e-commerce com 4 microsserviços (Auth, Order, Batch e Stock), cada um com seu próprio banco. Os serviços conversam de forma assíncrona via RabbitMQ, usando o padrão Saga por coreografia para manter a consistência dos pedidos sem acoplamento. Processamento em lote com Spring Batch (MongoDB como staging, PostgreSQL como destino), autenticação stateless com JWT, infraestrutura inteira subindo com um comando no Docker Compose e pipeline de CI por serviço no GitHub Actions, com testes em JUnit e Mockito.

Tec Events: API de eventos hospedada em AWS EC2, com upload de imagens para o Amazon S3 via AWS SDK v2, credenciais fora do código, banco versionado com Flyway e endpoints com paginação e filtros.

Horizon (projeto de extensão): desenvolvi em Java/Spring Boot o sistema de cálculo de rotas integrado às APIs do Google Maps, transformando regras de negócio complexas em dados geoespaciais, e otimizei os fluxos de requisição da API para aguentar mais acessos simultâneos.
API de autenticação: Spring Security com JWT, controle de acesso por roles (RBAC), Flyway e documentação com Swagger.

Stack: Java 21 · Spring Boot · Spring Security · Spring Batch · RabbitMQ · PostgreSQL · MongoDB · Docker · AWS (EC2, S3) · GitHub Actions · JUnit · Mockito · React · TypeScript · Linux

Aberto a estágio no Rio de Janeiro (presencial ou híbrido) ou remoto.  
Computer Engineering student building production-style Java systems (microservices, AWS, CI/CD). Open to back-end, cloud and DevOps internships. English (C1)

### 💻 Tecnologias e Ferramentas

<div style="display: inline_block"> <!-- Linguagens & Backend --> <img align="center" alt="Java" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg"> <img align="center" alt="Spring" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg"> <img align="center" alt="NodeJS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg"> <img align="center" alt="TypeScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg"> <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
<img align="center" alt="MySQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg"> <img align="center" alt="PostgreSQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg">
<img align="center" alt="Kafka" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg"> <img align="center" alt="RabbitMQ" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rabbitmq/rabbitmq-original.svg"> <img align="center" alt="JUnit" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/junit/junit-original.svg">

<img align="center" alt="Git" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg"> </div>

### 📫 Conecte-se comigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/davi-monteiro-cardoso-913b8b380/)
