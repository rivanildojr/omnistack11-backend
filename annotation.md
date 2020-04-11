# Rotas / Recursos

## Rotas

  - [x] `http://localhost:3333`

## Recursos

  - [x] `/users`
  - [x] `/api/v1/posts/:id`

# Métodos HTTP

  ### GET 
    - Buscar/listar uma informação do back-end
  ### POST
    - Criar uma informação no back-end  
  ### PUT
    - Alterar uma informação no back-end
  ### DELETE
    - Deletar uma informação no back-end
  
# Tipos de Parâmentros

  ### Query Params
    - Parâmetros nomeados enviados na rota após "?" (Filtros, paginação)
    - (req.query)
  
    - Ex: /users?page=2nome=Diego
  
  ### Query Params
    - Parâmentros utilizados para identificar recursos. Não pode enviar mais do que é esperado.
    - (req.params)

    - Ex: /users/:id - /users/1

  ### Request Body
    - Corpo da requisição, utilizado para criar ou alterar recursos
    - - (req.body)

    - Ex: {"nome": "rivanildo"}