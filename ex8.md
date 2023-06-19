# Exercício 8

## Como podemos subir essa imagem gerada para o hub da Docker?

Através dos comandos:

```
docker login
docker tag imageTag nomeUsuarioHub/nomeImagem:tag
docker push nomeUsuarioHub/nomeImagem:tag
```

