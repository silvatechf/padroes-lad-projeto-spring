Padrões de Projeto com Spring Framework

Este repositório é um laboratório prático que demonstra a implementação de Padrões de Projeto (Design Patterns) utilizando Java e o ecossistema Spring. O objetivo é mostrar como o Spring Framework, com seus princípios de Injeção de Dependência e Inversão de Controle, facilita e potencializa a aplicação desses padrões.

Padrões Explorados

Singleton:Gerenciado nativamente pelo contêiner IoC do Spring (escopo padrão dos Beans).
Strategy:Implementado com diferentes Beans de serviço que compartilham uma interface comum.
Facade:Utilizado para criar uma camada de serviço (`@Service`) que simplifica a comunicação com múltiplos componentes do backend.
Observer:Pode ser implementado utilizando o `ApplicationEventPublisher` do Spring para um sistema de eventos desacoplado.


Tecnologias

Java 17+
Spring Boot
Spring Data JPA
Maven / Gradle

Como Executar

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/silvatechf/padroes-lad-projeto-spring.git]
    ```
2.  Navegue até o diretório do projeto.
3.  Execute a aplicação usando o Maven ou sua IDE:
    ```bash
    ./mvnw spring-boot:run
    ```
4.  A aplicação estará disponível em `http://localhost:8080`.
