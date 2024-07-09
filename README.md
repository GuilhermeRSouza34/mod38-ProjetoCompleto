# Projeto de Aplicação Completa com JSF, Serviço de Validação e JPA

Este projeto é uma aplicação web completa desenvolvida utilizando JavaServer Faces (JSF) para a camada de apresentação, um controle para recebimento de informações dos usuários, um serviço dedicado à validação das regras de negócio e integração com JPA para persistência de dados no banco de dados PostgreSQL.

## Tecnologias Utilizadas

- **JavaServer Faces (JSF)**: Framework web para Java EE utilizado para construção das páginas web.
- **JPA (Java Persistence API)**: Padrão de mapeamento objeto-relacional para gerenciar o banco de dados.
- **PostgreSQL**: Banco de dados relacional utilizado para armazenar os dados da aplicação.
- **Java EE**: Plataforma utilizada para desenvolvimento e execução da aplicação web.
- **Maven**: Gerenciador de dependências utilizado para configurar e construir o projeto.

## Funcionalidades

- **Páginas JSF**: Desenvolvimento de interfaces de usuário utilizando JavaServer Faces.
- **Controle de Informações**: Recebimento e manipulação de informações provenientes das páginas JSF.
- **Serviço de Validação**: Implementação de um serviço Java para validar as regras de negócio da aplicação.
- **Integração com JPA**: Utilização de mapeamento objeto-relacional através do JPA para persistência de dados no PostgreSQL.

## Estrutura do Projeto

- **src/main/java**: Contém os arquivos Java da aplicação, incluindo classes de controle, serviço e entidades JPA.
- **src/main/webapp**: Diretório para os recursos web da aplicação, como páginas JSF, arquivos CSS e imagens.
- **META-INF/persistence.xml**: Arquivo de configuração do JPA para definir a unidade de persistência e as propriedades de conexão com o banco de dados.

## Configuração e Implantação

1. **Clonagem do Repositório**: Clone o repositório para o seu ambiente de desenvolvimento.

2. **Configuração do Banco de Dados**: Certifique-se de ter um servidor PostgreSQL configurado e crie um banco de dados para a aplicação.

3. **Configuração do persistence.xml**: Edite o arquivo `persistence.xml` localizado em `src/main/resources/META-INF/` para configurar a conexão com o seu banco de dados PostgreSQL.

4. **Execução do Projeto**: Compile e execute o projeto utilizando o Maven.

5. **Implantação no Servidor**: Implante o arquivo WAR gerado (localizado em `target/`) em um servidor compatível com Java EE, como Apache Tomcat ou WildFly.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias, correções de bugs ou novas funcionalidades.
