## Sprite-effecten

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Je kunt de `Uiterlijken`{:class="block3looks"} van je **personage** sprite en **maffe ogen** sprites laten veranderen als je erop klikt.
</div>
<div>

![Een personage en ogen met grafische effecten.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Maffe oogeffecten

--- task ---

Voeg een `wanneer op deze sprite wordt geklikt`{:class="block3events"} blok toe aan je **Oogbol** sprite.

Kun je uitzoeken welk codeblok je eronder zou plaatsen om de oogkleur van je sprite te veranderen als je op de **Oogbol** sprite klikt?

--- collapse ---
---
title: Grafische effecten wijzigen wanneer op de sprite wordt geklikt
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Als je wilt dat beide oogbollen hetzelfde effect hebben, moet je je script naar de sprite **Oogbol2** kopiëren.

[[[scratch3-copy-code]]]

--- /task ---

### Personage-effecten

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
title: Verander een sprite-uiterlijk wanneer erop wordt geklikt
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

**Fouten oplossen:**

Als je code aan de verkeerde sprite toevoegt, kun je dat oplossen:

[[[scratch3-copy-code]]]

Indien nodig kunt je de grafische effecten opnieuw instellen:

--- collapse ---
---
title: Ik wil deze grafische effecten niet
---

Om de grafische effecten op elk moment opnieuw in te stellen, klik je op het `zet alle effecten uit`{:class="block3looks"} in het `Uiterlijken`{:class="block3looks"} blokkenmenu. Door op de groene vlag te klikken, worden ook de grafische effecten gewist.

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


