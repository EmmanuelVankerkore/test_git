# 0 Paramétrer son git avant la première utilisation

## Contexte:
```
    Contenu du Git --> Null
    Contenu du GitHub --> Null
```

## Commande:
```
    git config --global user.name "<nom d'utilisateur>"
    git config --global user.email "<adresse email>"
```

## Résultat:
```
    Git peut maintenant être utilisé.
```

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

# 5 la branche actuelle

## Contexte:
```
    Contenu du Git --> Nouveau(x) document(s)
    Contenu du GitHub --> Aucun document
```

## Commande:
```
    git branch
```

## Résultat:
```
    Par défaut, la branche actuelle se nomme "master"
```

# 6 Ajout d'une nouvelle branche

## Contexte:
```
    
```

## Commande:
```
    git checkout -b "<nom de la nouvelle branche>"
```

## Résultat:
```
    
```

# 7 Se déplacer vers une branche existante

## Contexte:
```
    
```

## Commande:
```
    git checkout "<nom de la branche existante>"
```

## Résultat:
```
    
```

# 8

## Contexte:
```
    
```

## Commande:
```
    git stash
```

## Résultat:
```
    
```

# 9

## Contexte:
```
    
```

## Commande:
```
    git stash pop
```

## Résultat:
```
    
```

# 10 Renommer le nom d'une branche

## Contexte:
```
    
```

## Commande:
```
    git branch -M <nouveau nom de la branche actuelle>
```

## Résultat:
```
    
```

# 11 Définir la télécommande d'accès direct au GitHub

## Contexte:
```
    
```

## Commande:
```
    git remote add origin <url>
```

## Résultat:
```
    
```