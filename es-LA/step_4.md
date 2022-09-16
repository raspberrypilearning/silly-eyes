## Efectos para un objeto

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Puedes hacer que tu objeto **personaje** y tus objetos **ojo tonto** cambien su `Apariencia`{:class="block3looks"} cuando haces clic en ellos.
</div>
<div>

![Un personaje y ojos con efectos gráficos.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Efectos para los ojos tontos

--- task ---

Agrega un bloque `al hacer clic en este objeto`{:class="block3events"} a tu objeto **Eyeball**.

¿Puedes averiguar qué bloque de código pondrías debajo para cambiar el color de ojos de tu objeto cuando haces clic en el objeto **Eyeball**?

--- collapse ---
---
title: Cambia los efectos gráficos al hacer clic en un objeto
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Si quieres que ambos ojos tengan el mismo efecto, tienes que copiar tu script al objeto **Eyeball 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Efectos para personajes

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
title: Haz que un objeto cambie de disfraz cuando hagas clic en él
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

**Depurar:**

Si agregas código al objeto incorrecto, puedes solucionarlo:

[[[scratch3-copy-code]]]

Si lo necesitaras, puedes restablecer los efectos gráficos:

--- collapse ---
---
title: No quiero estos efectos gráficos
---

Para restablecer los efectos gráficos en cualquier momento, haz clic en el bloque `quitar efectos gráficos`{: class = "block3looks"} en el Menú de bloques `Apariencia`{:class="block3looks"}. Hacer clic en la bandera verde también quita los efectos gráficos.

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


