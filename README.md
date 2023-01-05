
# Integração Contínua: testes automatizados e pipeline no Github Actions


Como criar uma rotina de integração contínua.

Foi tratado as vantagens de ter uma rotina de CI, e as vantagens de utilizar o Github Actions.

Entendendo o que é uma pipeline.

Como realizar testes em uma aplicação de forma automática.

Configuração das rotinas para serem executadas em cada commit realidado.


Aplicação feita em GO, para ser utilizado no curso do CI/CD com o Github Actions

[Curso Alura](https://www.alura.com.br/curso-online-integracao-continua-testes-automatizados-pipeline-github-actions)




<br>

## Tecnologias Utilizadas

- GO language
- Docker
- Github Actions
- PostgSQL

<p float="left">
    <img src="https://seeklogo.com/images/G/go-programming-language-logo-E73DD2532B-seeklogo.com.png" width="100" height="50" alt="go language">
    <img src="https://seeklogo.com/images/D/docker-logo-CF97D0124B-seeklogo.com.png" width="100" height="60" alt="Docker logo">
    <img src="https://seeklogo.com/images/G/github-actions-logo-031704BDC6-seeklogo.com.png" width="80" height="60" alt="github actions logo">
    <img src="https://seeklogo.com/images/P/postgresql-logo-6DBC096ED4-seeklogo.com.png" width="150" height="50" alt="postgresql">
 </p>




<br>

## Executar a aplicação localmente

```bash

# Subir o banco de dados postgreSQL com docker
$ docker-compose up -d

# Para subir a aplicação
$ go run main.go

```

Para certificar que a aplicação subiu basta acessar a porta 8080 da sua máquina, e no final da url adicione uma barra e o seu nome para receber uma mensagem.


&nbsp;&nbsp;&nbsp;&nbsp;[http://localhost:8080/italo](http://localhost:8080/italo)


Como retorno, veremos:


```json
{"API diz": "E ai italo, Tudo beleza?")
```
