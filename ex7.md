# Exercício 7

1° - produza um simples Dockerfile para compilar e executar uma aplicação Java através de um arquivo .java (se preferir pode usar outra tecnologia que esteja mais familiarizado….)

[Dockerfile](Dockerfile)

2° - Mostre o comando para buildar esse Dockerfile:

```
docker build -t my-java-app:1.0 .
```

3° - Mostre como um container pode usar a imagem gerada

```
docker run my-java-app:1.0
```