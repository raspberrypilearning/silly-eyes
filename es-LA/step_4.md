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

Agrega un bloque `al hacer clic en este objeto`{:class="block3events"} a tu objeto **Globo ocular**.

¿Puedes averiguar qué bloque de código pondrías debajo para cambiar el color de ojos de tu objeto cuando haces clic en el objeto **Globo ocular**?

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

Si quieres que ambos ojos tengan el mismo efecto, tienes que copiar tu script al objeto **Globo ocular 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Efectos para personajes

Si lo desearas, también puedes hacer que tu objeto **personaje** cambie de color y que tenga otros efectos gráficos cuando hagas clic en él.

--- task ---

Haz clic en tu objeto **personaje** en la Lista de objetos, luego haz clic en la pestaña **Código**.

Agrega el mismo script que usaste para cambiar el color de ojos. ¿Qué efectos gráficos deseas cambiar para tu **personaje**?

**Elige:** Elige un efecto en el Menú desplegable dentro del `cambiar el efecto color en`{:class="block3looks"}. Experimenta con los números hasta que tengas un cambio que te guste.

[[[scratch3-graphic-effects]]]

--- /task ---

Ahora, agrega un **accesorio**, como un sombrero, que cambia cuando haces clic en él; usa el bloque `siguiente disfraz`{:class="block3looks"}.

--- task ---

**Elige:** Agrega un cambio de accesorio o de disfraz de tu elección.


![Objetos con accesorios.](images/accessory-sprite.png)

--- collapse ---
---
title: Haz que un objeto cambie de disfraz cuando hagas clic en él
---

**Gobo con accesorios de disfraz**: [Ver dentro](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Algunos objetos ya tienen una selección de disfraces.

Puedes agregar código para hacer que el disfraz de un objeto cambie al `siguiente disfraz`{:class="block3looks"} cuando haces clic en el objeto:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Si tu objeto no tiene una opción de disfraces, o quieres agregar más, puedes agregar cualquier disfraz a un objeto.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Prueba:** Trabaja en tus objetos hasta que interactúen de la forma que desees. Prueba un cambio a la vez y prueba lo que hace, de tal manera que puedas detectar fácilmente cada cambio y deshacer cualquier cosa que no le guste.

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

Para restablecer los efectos gráficos en cualquier momento, haz clic en el bloque `quitar efectos gráficos`{:class="block3looks"} en el Menú de bloques `Apariencia`{:class="block3looks"}. Hacer clic en la bandera verde también quita los efectos gráficos.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- save ---

