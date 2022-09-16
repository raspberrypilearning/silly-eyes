## Effets de sprite

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Tu peux faire en sorte que tes sprites **personnage** et **yeux idiots** changent leur `Apparence`{:class="block3looks"} lorsque tu cliques dessus.
</div>
<div>

![Un personnage et des yeux avec des effets graphiques.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Effets d'oeil idiot

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

Click on your **character** sprite in the Sprite list, then click on the **Code** tab.

Add the same script as you used to change the eye colour. Which graphic effects do you want to change for your **character**?

**Choose:** Choose an effect in the drop-down menu within the `change color effect by`{:class="block3looks"} block. Experiment with the numbers and effects until you have a change that you like.

[[[scratch3-graphic-effects]]]

--- /task ---

### An accessory

Now, add an **accessory**, such as a hat, that changes when you click on it — use the `next costume`{:class="block3looks"} block.

--- task ---

**Choose:** Add an accessory change or costume change of your choice.

![Sprites with accessories.](images/accessory-sprite.png)

--- collapse ---
---
title : Faire un changement de costume de sprite lorsque tu cliques dessus
---

**Gobo with costume accessories**: [See inside](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Some sprites already have a choice of costumes.

You can add code to make a sprite's costume change to the `next costume`{:class="block3looks"} when you click on the sprite:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

If your sprite does not have a choice of costumes, or you want to add more, you can add any costume to a sprite.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Test:** Work on your sprites until they interact in the way that you want.

**Tip:** Try one change at a time and test what it does so that you can easily spot each change and undo anything that you do not like.

--- /task ---

--- task ---

**Déboguer:**

Si tu ajoutes du code au mauvais sprite, tu peux corriger cela :

[[[scratch3-copy-code]]]

Si besoin, tu peux réinitialiser les effets graphiques :

--- collapse ---
---
title: Je ne veux pas de ces effets graphiques
---

Pour réinitialiser les effets graphiques à tout moment, clique sur le `annuler les effets graphiques `{:class="block3looks"} dans les blocs `Apparences`{:class="block3looks"} . Cliquer sur le drapeau vert efface également les effets graphiques.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Test:** Test your project again, but this time, make it full-screen so that you can see how it will appear to someone looking at it.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
By making your project full-screen, you are seeing what you have made from the perspective of a user who is playing with your project. **User interaction** is important in digital making. 
</p>


