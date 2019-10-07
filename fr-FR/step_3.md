## Fantômes aléatoires

Ton fantôme est vraiment facile à attraper en ce moment, parce qu'il ne bouge pas!

--- task ---

Peux-tu ajouter du code à ton fantôme pour que, au lieu de rester dans la même position, le fantôme apparaisse à des positions aléatoires sur la scène?

--- hints ---


--- hint ---

Chaque fois avant que ton fantôme apparaît, il faut `aller à`{:class="block3motion"} une position aléatoire sur la scène.

--- /hint --- --- hint ---

Il y a deux ensembles de blocs de code que tu peux utiliser ici. Choisis le jeu que tu préfères.

![sprite-fantôme](images/ghost-sprite.png)

Soit ajoute cet ensemble de blocs à ton sprite fantôme:

```blocks3
aller à (position aléatoire v)
```

Ou ajoute celui-ci à ton sprite:

```blocks3
aller à x: (14) y: (50)

(nombre aléatoire entre (1) et (10))

(nombre aléatoire entre (1) et (10))
```

--- /hint---

--- hint ---

Ton code pourrait ressembler à ceci:

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
quand le drapeau vert pressé
répéter indéfiniment
cacher
attendre (1) secondes
aller à (position aléatoire v)
montrer
attendre (1) secondes
fin
```

Ou pourrait ressembler à ceci:

![sprite-fantôme](images/ghost-sprite.png)

```blocks3
quand le drapeau vert pressé
répéter indéfiniment 
cacher
attendre (1) secondes
aller à x: (nombre aléatoire entre (-150) et (150)) y: (nombre aléatoire entre (-150) et (150))
montrer
attendre (1) secondes
end
```

--- /hint --- --- /hints ---

--- /task ---