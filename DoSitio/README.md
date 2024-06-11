<div align="center">
  
# **Programação avançada para WEB**
## *Trabalho 1*
</div>

### Christopher Passos Thompson

<br>

# **1. Introdução**
Em nossa disciplina estamos desenvolvendo as API’s de backend utilizando Node.js/Fastify
com bancos de dados não-relacionais (MongoDB). Nosso projeto prático, "Dositio",
atualmente apresenta um CRUD de produto e uma rota de autenticação (`/auth`). Até este
ponto, juntos, implementamos as rotas: `GET /products` e `/products/:id`, `POST /products`,
`PUT /products/:id` e `DELETE /products/ :id`.

<br>

# **2. Implementação**
> - `GET /categories`: Deve retornar a lista de categorias de produtos existentes na
aplicação 
> - `POST /categories`: Deve criar uma nova categoria no banco de dados. Garanta a
validação dos campos (apenas name` e img_url). Deve retornar status 201 sem
conteúdo.
> - `PUT /categories/:id`: Deve atualizar os dados de uma categoria específica
> - `DELETE /categories/:id`: Deve remover a categoria.
> - `GET /categories/:id/products`: Deve retornar todos os produtos de uma categoria
específica
> - `POST /register`: Deve criar um novo usuário. Garanta validação dos campos
