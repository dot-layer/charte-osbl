# Charte des règlements .Layer

Ce dépôt a comme objectif de définir et publier la charte des règlement de l'organisme sans but lucratif .Layer.

## Compiler le livre

Pour compiler le livre, il faut avoir le logiciel [R](http://cran.utstat.utoronto.ca/) d'installé. De plus, il faut avoir le package `bookdown` d'installé en local. Pour valider si le package est déjà installé, vous pouvez effectuer la commande suivante dans le terminal:

```
R -e "'bookdown' %in% rownames(installed.packages())"
```

Dans le cas où `bookdown` n'est pas installé (output = `FALSE`), vous pouvez l'installer en effectuant la commande suivante dans le terminal:

```
R -e "install.packages('bookdown', repos = 'http://cran.utstat.utoronto.ca')"
```

Une fois ces étapes réalisées, vous pouvez compiler le livre en effectuant la commande suivante dans le terminal:

```
./compile_book.sh
```
