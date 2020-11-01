# Utilisation dans une page

Utilisation simple :

```markdown
![Dessin manquant](dessins/Chacha/17-1.jpg)
```

Ajout d'un titre sous l'image et faire basculer en "mode &lt;figure> HTML" :

```markdown
![Dessin manquant](dessins/Mathieu/1.jpg "La traversée du Torrent Glacé")
```

# Effets

Pour appliquer un effet à une image, ajouter l'une des extensions suivantes :

- `.esquisse` : pour indiquer que le dessin n'est qu'une esquisse avec un crayon très sec et qu'il faut renforcer le trait

Exemple d'utilisation :

```markdown
![Dessin manquant](dessins/Mathieu/3.esquisse.jpg)
```

# Voir aussi

Toutes les images markdown sont interprétées en HTML par le hook [render-image](../../layouts/_default/_markup/render-image.html).
