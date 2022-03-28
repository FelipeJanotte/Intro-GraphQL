# GraphQL
- Quais problemas GraphQL resolve?
  - Overfetching
    - Buscando mais do que precisa
  - Underfetching
    - Buscando menos do que precisa

- Dificuldades
  - Cache
  - Erros

## Exemplo de código
```gql
// htpp://localhost:3000/users

query {
  users{
    id
    name
    github

    addresses {
      city
      state
      country
    }
  }
}
```
