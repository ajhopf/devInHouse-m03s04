# Exercício 4

## Escreva o comando necessário para subir um container de nome web em segundo plano na porta 8081 com imagem do PHP versão 7.2 passando um diretório do host para dentro do container

```
docker run --name web -d -p 8081:80 -v C:\Users\Andre\php:/app php:7.2 docker-php-ext-install mysqli
```