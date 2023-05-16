# game-list-docs
Esta API cadastra,edita,deleta games

## Endpoints
### GET /games 
# Esse endpoint é responsavel por retorna a listagem de todos osgames cadastrados no banco de dados
#### Parametros
Nenhum
#### Respostas
#### OK ! 200 ✅
Caso essa resposta aconteça você irá receber todos os games
Exemplo de respostas
```[
	{
		"id": 23,
		"title": "Call of duty",
		"year": 2021,
		"price": 50
	},
	{
		"id": 65,
		"title": "Minecraft",
		"year": 2012,
		"price": 50
	},
	{
		"id": 2,
		"title": "Clash of clans",
		"year": 2023,
		"price": 10
	}
]

```
#### Falha na autenticação 404 ❌

```
{
	"message": "token invalido"
}
```
### POST /auth 
# Esse endpoint é responsavel por fazer o processo de login
#### Parametros
```
  {
	  "email":"flavio.santos92@live.com",
    "password":"node"
   }
```
#### Respostas
#### OK ! 200 ✅
Caso essa resposta aconteça você irá receber todos os games
Exemplo de respostas
# login feito
