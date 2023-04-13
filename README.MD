# Praticando BackEnd

## Tecnlogias

- `JavaScript`
- `SQLite`
- `KNEX.js`
- `Node.js`
- `Git` `Github`

## Documentação da API

```http
  METHOD /localhost:3333/resource
```

#### Criar um usuario

```http
  POST /localhost:3333/users
```

#### Atualizar um usuario

```http
  PUT /localhost:3333/users/:user_id
```

#### Adicionar uma nota ao usuario

```http
  POST /localhost:3333/notes/:user_id
```

#### Mostrar notas

```http
  GET /localhost:3333/notes
```

#### Mostrar nota via ID da mesma

```http
  GET /localhost:3333/notes/:id
```

#### Deletar nota

```http
  DELETE /localhost:3333/notes/:id
```

#### Motrar tags da nota

```http
  GET /localhost:3333/tags/:user_id
```
