# CURRICULO DO POVO - Projeto Social

Este repositório contém o código fonte para o projeto **"CURRICULO DO POVO"**, uma plataforma online gratuita que visa auxiliar pessoas em situação de vulnerabilidade social na construção de currículos profissionais.

## Objetivo do Projeto

O objetivo do projeto é democratizar o acesso à ferramenta de currículo, oferecendo um sistema intuitivo e fácil de usar, que auxilia na criação de currículos profissionalmente adequados e que aumentam as chances de empregabilidade.

## Tecnologias Utilizadas

O projeto é desenvolvido utilizando as seguintes tecnologias:

- **Next.js**: Framework React para desenvolvimento web de alta performance.
- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **PostgreSQL**: Sistema de gerenciamento de banco de dados relacional.
- **Docker Compose**: Ferramenta para orquestração de containers Docker.
- **Jest**: Framework de testes para JavaScript.

## Estrutura do Repositório

├── infra │ └── compose.yaml └── src ├── components │ ├── ... ├── pages │ ├── index.js │ ├── ... ├── styles │ └── global.css ├── utils │ └── ... └── services ├── database.js └── ...


## Instalação e Execução

1. Instale as dependências:

    ```bash
    npm install
    ```

2. Inicialize os serviços Docker:

    ```bash
    npm run services:up
    ```

3. Execute o servidor de desenvolvimento:

    ```bash
    npm run dev
    ```

## Testes

Para executar os testes unitários:

```bash
npm run test
```

## Para executar os testes em modo "watch":

```bash
npm run test:watch
```

## Contribuições

Contribuições são bem-vindas! Se você gostaria de contribuir com o projeto, por favor, siga as seguintes etapas:

1. Fork o repositório.
2. Crie uma branch para sua nova feature ou correção de bug.
3. Faça suas alterações e commit.
4. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT.

## Contato

Para qualquer dúvida, sugestão ou feedback, entre em contato com:

- **Matheus Milanez Marques Lopes** - matheusmarques@outlook.com

## Agradecimentos

Agradecemos a todos que contribuíram para o desenvolvimento deste projeto!
