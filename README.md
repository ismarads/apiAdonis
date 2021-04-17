# Aplicativo de API Adonis

Este é o padrão para a criação de um servidor API em AdonisJs, ele vem pré-configurado com.

1. Bodyparser
2. Autenticação
3. CORS
4. Lucid ORM
5. Migrações e sementes

## Configurar

Use o comando adonis para instalar o blueprint

`` `bash
adonis new yardstick --api-only
`` `

ou clone manualmente o repo e execute `npm install`.


### Migrações

Execute o seguinte comando para executar migrações de inicialização.

`` `js
migração adonis: executar
`` `




# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
