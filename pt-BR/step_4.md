## Efeitos do ator

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Você pode fazer seus atores de **personagem ** e ** olho bobo ** mudarem seus `Looks` {:class=" block3looks "} quando você clica neles.
</div>
<div>

! [Um personagem e olhos com efeitos gráficos.] (Images / character-graphic-effects.png) {: width = "300px"}    

</div>
</div>

### Efeitos tolos nos olhos

--- task ---

Adicione um bloco `quando este ator clicou em` {:class="block3events"} ao seu ator **Bola do olho**.

Você pode descobrir qual bloco de código você colocaria embaixo para mudar a cor dos olhos do seu ator ao clicar no ator **Bola do olho**?

--- collapse ---
---
title: Alterar os efeitos gráficos quando o ator é clicado
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Se você quiser que ambos os globos oculares tenham o mesmo efeito, você precisará copiar seu script para o ator **Bola do olho 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Efeitos de personagem

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
title: Faça um ator mudar de roupa quando clicado
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

Se você adicionar o código ao ator errado, você pode consertar isso:

[[[scratch3-copy-code]]]

Se necessário, você pode redefinir os efeitos gráficos:

--- collapse ---
---
title: Não quero esses efeitos gráficos
---

Para redefinir os efeitos gráficos a qualquer momento, clique em `limpar efeitos gráficos`{:class="block3looks"} no `Looks`{:class="block3looks"}. Clicar na bandeira verde também limpa todos os efeitos gráficos.

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


