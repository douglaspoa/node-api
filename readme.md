# Node API

Simples api em nodejs

## Installation

Crie um banco no postgres

```bash
* psql postgres
* CREATE DATABASE api;
```

Crie uma tabela users

```bash
CREATE TABLE users (
  ID SERIAL PRIMARY KEY,
  name VARCHAR(30),
  email VARCHAR(30)
);
```

Insira alguns dados na tabela

```bash

INSERT INTO users (name, email)
  VALUES ('Jerry', 'jerry@example.com'), ('George', 'george@example.com');
```


## Iniciar

```bash
node index.js
```
http://localhost:3000/