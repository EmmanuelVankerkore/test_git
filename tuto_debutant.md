# 1 Initialisation

## Contexte:
```
    Contenu du Git --> Aucun document
    Contenu du GitHub --> Aucun document
```

## Commande:
```
    git init
```

## Résultat:
```
    Le projet git est initialisé.
```

# 2 Ajouter les modifications

## Contexte:
```
    Contenu du Git --> Nouveau(x) document(s)
    Contenu du GitHub --> Aucun document
```

## Commande:
```
    git add *
```

## Résultat:
```
    Les fichiers sont prêt à être commit.
```

# 3 Commit

## Contexte:
```
    Contenu du Git --> Nouveau(x) document(s)
    Contenu du GitHub --> Aucun document
```

## Commande:
```
    git commit -m <nom du commit>
```

## Résultat:
```
    Le commit a été créé.
```

# 4 l'état

## Contexte:
```
    Contenu du Git --> Nouveau(x) document(s)
    Contenu du GitHub --> Aucun document
```

## Commande:
```
    git status
```

## Résultat:
```
    Si affichage en rouge --> il faut git add.
    Si affichage en vert --> prêt pour le commit.
    Sinon tout est en ordre.
```