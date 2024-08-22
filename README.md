# Book Depository

## Execução

1. Copie o arquivo `.env.example` para `.env` e configure as variáveis de ambiente conforme necessário.

    ```bash
    cp .env.example .env
    ```

2. Para executar, basta instalar o [Docker](https://www.docker.com/) e executar o comando abaixo:

    ```bash
    docker compose up -d
    ```

3. **[Opcional]** Execute o comando abaixo para acessar o Prisma Studio:

    ```bash
    docker exec book-depository-api-1 npm run prisma:studio
    ```
