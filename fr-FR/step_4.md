## Effets de sprite

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Tu peux faire en sorte que tes sprites **personnage** et **yeux rigolos** changent leur « Apparence »{:class="block3looks"} lorsque tu cliques dessus.
</div>
<div>

![Un personnage et des yeux avec des effets graphiques.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Effets œil rigolo

--- task ---

Ajoute un bloc `quand ce sprite est cliqué ` {:class="block3events"} à ton sprite **globe oculaire**.

Peux-tu déterminer quel bloc de code tu placeras en dessous pour changer la couleur des yeux de ton sprite lorsque tu cliques sur le sprite **globe oculaire** ?

--- collapse ---
---
title: Changer les effets graphiques lorsque l'on clique sur le sprite
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Si tu veux que les deux globes oculaires aient le même effet, tu devras copier ton script dans le sprite **globe oculaire 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Effets de personnage

--- task ---

Clique sur ton sprite **personnage** dans la liste Sprite, puis clique sur l'onglet **Code**.

Ajoute le même script que tu as utilisé pour changer la couleur des yeux. Quels effets graphiques veux-tu changer pour ton **personnage** ?

**Choisir :** Choisis un effet dans le menu déroulant du bloc `mettre l'effet couleur`{:class="block3looks"}. Expérimente les nombres et les effets jusqu'à ce que tu obtiennes un changement qui te plaise.

[[[scratch3-graphic-effects]]]

--- /task ---

### Accessoire

Maintenant, ajoute un **accessoire**, comme un chapeau, qui change lorsque tu cliques dessus, utilises le `costume suivant`{:class="block3looks"}.

--- task ---

**Choisir :** Ajoute un changement d'accessoire ou de costume de ton choix.

![Sprites avec accessoires.](images/accessory-sprite.png)

--- collapse ---
---
title: Faire un changement de costume de sprite lorsque tu cliques dessus
---

**Gobo avec accessoires de costume** : [Voir à l'intérieur](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Certains sprites ont déjà un choix de costumes.

Tu peux ajouter du code pour changer le costume d'un sprite en `costume suivant`{:class="block3looks"} lorsque tu cliques sur le sprite :

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Si ton sprite n'a pas le choix de costumes, ou si tu souhaites en ajouter d'autres, tu peux ajouter n'importe quel costume à un sprite.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Test :** Travaille sur tes sprites jusqu'à ce qu'ils interagissent comme tu le souhaites.

**Astuce :** essaie une modification à la fois et teste ce qu'elle fait afin de pouvoir facilement repérer chaque modification et annuler tout ce que tu n'aimes pas.

--- /task ---

--- task ---

**Déboguer :**

Si tu ajoutes du code au mauvais sprite, tu peux corriger cela :

[[[scratch3-copy-code]]]

Si besoin, tu peux réinitialiser les effets graphiques :

--- collapse ---
---
title: Je ne veux pas ces effets graphiques
---

Pour réinitialiser les effets graphiques à tout moment, clique sur le `annuler les effets graphiques `{:class="block3looks"} dans les blocs `Apparences`{:class="block3looks"} . Cliquer sur le drapeau vert efface également les effets graphiques.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Test :** Teste à nouveau ton projet, mais cette fois-ci, mets-le en plein écran afin que tu puisses voir comment il apparaîtra à quelqu'un qui le regarde.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
En créant ton projet en plein écran, tu vois ce que tu as fait du point de vue d'un utilisateur qui joue avec ton projet. **L'interaction avec l'utilisateur** est importante dans la création numérique. 
</p>


