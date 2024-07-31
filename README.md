# Voll.med API

A Voll.med API é uma aplicação desenvolvida para gerenciar médicos e suas informações associadas, incluindo autenticação e autorização de usuários. A API é construída com Spring Boot e utiliza JWT (JSON Web Token) para autenticação e segurança. Esta aplicação fornece funcionalidades para cadastro, atualização, listagem e exclusão de médicos, além de uma estrutura sólida para a gestão de usuários.

## Funcionalidades

- **Cadastro de Médicos**: Permite o cadastro de médicos com informações detalhadas, incluindo especialidade e endereço.
- **Atualização de Dados**: Possibilita a atualização das informações de médicos existentes.
- **Listagem de Médicos**: Oferece endpoints para listar médicos ativos e detalhes específicos.
- **Autenticação e Autorização**: Utiliza JWT para autenticação de usuários e controle de acesso.
- **Tratamento de Erros**: Implementa um sistema de tratamento de erros com respostas apropriadas para diferentes exceções.

## Tecnologias Utilizadas

- **Spring Boot**: Framework principal para construção da API.
- **Hibernate**: Para gerenciamento da persistência de dados com JPA.
- **JWT (JSON Web Token)**: Para autenticação e autorização segura.
- **PostgreSQL**: Banco de dados relacional para armazenamento das informações.
- **Lombok**: Para geração automática de getters, setters e construtores.
- **Auth0 JWT Library**: Para criação e verificação de tokens JWT.

## Estrutura do Projeto

- **`med.voll.api.domain`**: Contém as classes de domínio, como `Medico`, `Endereco`, e `Usuario`.
- **`med.voll.api.domain.medico`**: Gerencia todas as operações relacionadas aos médicos, incluindo registros e detalhes.
- **`med.voll.api.domain.usuario`**: Gerencia a autenticação e dados dos usuários.
- **`med.voll.api.infra.security`**: Implementa a segurança da API com JWT e filtros de segurança.
- **`med.voll.api.infra.exception`**: Contém o tratamento de exceções e erros da API.

## Autor

Kaio Vitor - [GitHub](https://github.com/Kaio-0708)
