# Exercício 3

## Sabendo que um contêiner pode ser encerrado a qualquer momento e que isso excluirá todos seus registros, dados e configurações, como podemos contornar essa situação? exemplifique

Para fazermos a persistência de dados podemos criar volumes, ou seja, "apontar" um local na máquina do host onde deverá ser feita a persistência dos dados.

Fazendo isso, será possível excluir um container, e, ao subir novamente um container que esteja configurado para utilizar este mesmo volume, ele terá acesso aos dados.

Podemos fazer isso utilizando volume nomeado ou bind volume.

Para criarmos um volume nomeado utilizamos o comando:

```
    docker volume create nomeVolume
```

O bind volume é um espelhamento bidirecional de uma pasta do host para uma pasta dentro do container:

```
-v C:\Users\Andre\dados_oracle:var/lib/mysql
```

Com o bind volume utilizamos o comando acima em conjunto com o comando docker run.