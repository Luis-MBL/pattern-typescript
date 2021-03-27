# pattern-typescript

Projeto TypeScript padrão com sistema de usuários utilizando:

* PostgreSQL
* Express
* TypeORM
* Celebrate
* JSON Web Tokens
* Nodemailer


# Para começar faça o seguinte:

1. Instale as dependencias com:
yarn 

2. Inicie o docker com:
docker run --name PatternTypescript -e POSTGRES_PASSWORD=PatternTypescript@123 -p 6003:5432 -d postgres

3. Rode as migrations com:
yarn typeorm migration:run

4. Inicie o projeto com:
yarn dev

5. Utilize um software como o Postman para testar os endpoints
