## Para executar o projeto

1 - Remonei o arquivo .example.env para .env.dev

2 - Atualize as variaveis ambientes no docker-compose.yml e .env.dev

3 - Constura as imagens e execute os containers como o seguinte comando:

```
$ docker-compose up -d --build
```

Abra o navegador e digite http://localhost:8000
