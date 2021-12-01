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

Se quiser, você também pode fazer seu **caractere** mudar de cor e outros efeitos gráficos quando você clicar nele.

--- task ---

Clique em seu **caractere** na lista de Atores e, em seguida, clique na guia **Código**.

Adicione o mesmo script que você usou para alterar a cor dos olhos. Quais efeitos gráficos você deseja alterar para o seu **caractere**?

**Escolha:** Escolha um efeito no menu suspenso dentro de `altere o efeito de cor por`{:class="block3looks"}. Experimente com os números até que você tenha uma mudança que você goste.

[[[scratch3-graphic-effects]]]

--- /task ---

Agora, adicione um **acessório**, como um chapéu, que muda quando você clica nele - use os `próximos blocos de trajes`{:class="block3looks"}.

--- task ---

**Escolha:** Adicione uma mudança de acessório ou roupa de sua escolha.


![Atores com acessórios.](images/accessory-sprite.png)

--- collapse ---
---
title: Faça um ator mudar de roupa quando clicado
---

**Gobo com acessórios de traje**: [Veja interior](https://scratch.mit.edu/projects/496334057/editor){:target="_ blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Alguns atores já têm uma escolha de fantasias.

Você pode adicionar um código para fazer a mudança da fantasia de um ator para a `próxima fantasia`{:class="block3looks"} ao clicar no ator:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Se o seu ator não tiver uma fantasia escolhida, ou se você quiser adicionar mais, você pode adicionar qualquer fantasia a um ator.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Teste:** Trabalhe em seus atores até que eles interajam da maneira que você deseja. Experimente uma mudança de cada vez e teste o que ela faz para que você possa identificar facilmente cada mudança e desfazer qualquer coisa que não goste.

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

--- save ---

