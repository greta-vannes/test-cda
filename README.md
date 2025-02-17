## Règles du jeu

Nous aimerions que vous réalisiez un programme qui affichera un couplet de sa musique préférée *99 shooters sans alcool* dépendant du nombre de shooters en entrée. 
Ce nombre sera compris entre 0 et 99 comme vous pouvez le [voir ici](SONG.md).

Exemples de solutions :

![Image terminal](images/term-99.png)
![Image web](images/web-99.png)

Pour cela vous êtes libre du langage utilisé ainsi que de l'interface qui nous permettra d'interagir avec votre programme.

## Spécifications

**Dans la plupart des cas :**

- [ ] Lorsque je rentre un nombre `n`, j'obtiens le couplet suivant :

```md
`n` shooters sans alcool sur le mur, `n` shooters sans alcool.
Bois en un et au suivant ! `n - 1` shooters sans alcool sur le mur.
```

**Attention cependant :**

- [ ] Lorsqu'il ne reste qu'un shooter, j'enlève le `s` à shooters.
- [ ] Lorsqu'il n'y a plus de shooters, je remplace `0` par `plus de`.
- [ ] Enfin, si je n'ai plus de shooters je dois aller en acheter :

```md
Plus de shooters sans alcool sur le mur, plus de shooters sans alcool. 
Vas au supermarché pour en acheter, 99 shooters sans alcool sur le mur.
```

**Dans tous les cas :**

- [ ] L'affichage doit respecter le saut de ligne
- [ ] Faire attention aux majuscules en début de phrase

[Voir la musique complète](SONG.md)

## Mot de la fin

À la fin de cet exercice, vous devez nous partager votre code pour qu'on le teste via ...<br/>
Il faudra donc que votre code soit de qualité et facile à prendre en main !

À vous de jouer !
