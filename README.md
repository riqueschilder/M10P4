## Ponderada 4
### Gateway

O Gateway possui um sistema de logs que registra informações como data de acesso, tipo de requisição, status da requisição e a rota acessada. Esses logs são armazenados na pasta `/logs`, nos arquivos `access.log` e `error.log`. O `access.log` armazena logs de requisições bem-sucedidas, enquanto o `error.log` armazena logs de erros e tentativas de acesso a rotas inexistentes.

### Sistema 3

A aplicação utilizada em sala de aula armazena logs na mesma pasta `/logs`, nos arquivos `app.log` e `app.log-{data}.txt`, registrando acessos às rotas da aplicação.

# Como rodar?

Na pasta raiz, rode o comando:

```bash
docker compose up
```

Após executar o comando docker compose up, acesse os arquivos access.log, app.log e error.log no VSCode. Navegue pelas rotas ("/""/usuários""/produtos") da aplicação para observar os logs sendo gerados:

# Video

https://github.com/riqueschilder/M10P3/assets/99187952/53f0bdc3-cc76-4176-996e-bbeb9b1a22ef

