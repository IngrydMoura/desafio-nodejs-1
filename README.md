# Desafio Node.js

### Desafio relacionado a criação de rotas de uma aplicação

- Método *GET*: onde através da url da query faz um filter e nos retorna o resultado relacionado aos `repositories`.
- Metódo *POST*: onde através dos dados contidos no title, url e techs pego do body da requisição, cria um novo objeto `repository` com id único (utiliza-se a lib uuidv4 para a criação).
- Método *PUT*: onde através do id trazido do parâmetro faz a atualização do determinado `repository`.
- Método *DELETE*: onde através do id trazido do parâmetro deleta determinado `repository`.
- Método *POST/like*: onde através do id trazido do parâmetro adiciona +1 no dado de likes ao fazer esta requisição sem criar um novo id, apenas atualizando os dados de likes.

