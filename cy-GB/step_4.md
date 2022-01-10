## Effeithiau corlun

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Galli di wneud i dy gorluniau **cymeriad** a **llygad gwirion** newid eu `Edrychiad`{:class="block3looks"} wrth i ti glicio arnyn nhw.
</div>
<div>

![Cymeriad a llygaid ag effeithiau graffigol.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Effeithiau llygad gwirion

--- task ---

Ychwanega floc `pan gaiff y corlun hwn ei glicio`{:class="block3events"} at dy gorlun **Eyeball**.

Wyt ti'n gallu gweithio allan pa floc cod byddet ti'n ei roi oddi tano i newid lliw llygad dy gorlun pan fyddi di'n clicio ar y corlun **Eyeball**?

--- collapse ---
---
title: Newid effeithiau graffeg pan gaiff y corlun ei glicio
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Os wyt ti am i'r ddwy belen llygad gael yr un effaith, bydd angen i ti gopïo dy sgript i'r gorlun **Eyeball 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Effeithiau cymeriad

Os wyt ti eisiau, galli di hefyd wneud i dy **gymeriad** newid lliw a defnyddio effeithiau graffeg eraill pan fyddi di'n clicio arno.

--- task ---

Clicia ar dy **gymeriad** yn y rhestr Corluniau, yna clicia ar y tab **Cod**.

Ychwanega yr un sgript wnes di ei defnyddio i newid lliw'r llygad. Pa effeithiau graffeg wyt ti am eu newid ar gyfer dy **gymeriad**?

**Dewis:** Dewisa effaith yn y gwymplen yn y bloc `newid effaith lliw gan`{:class="block3looks"}. Arbrofa gyda'r rhifau nes bod gen ti newid rwyt ti'n ei hoffi.

[[[scratch3-graphic-effects]]]

--- /task ---

Nawr, ychwanega **ategolyn**, fel het, sy'n newid pan fyddi di'n clicio arno - defnyddia'r bloc `gwisg nesaf`{:class="block3looks"}.

--- task ---

**Dewis:** Ychwanega newid ategolyn neu newid gwisg o dy ddewis.


![Corluniau gydag ategolion.](images/accessory-sprite.png)

--- collapse ---
---
title: Gwneud i gorlun newid ei wisg pan gaiff ei glicio
---

**Gobo gyda ategolion gwisg**: [Gweld tu mewn](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Mae gan rai corluniau ddewis o wisgoedd eisoes.

Galli di ychwanegu cod i wneud i wisg corlun newid i'r `wisg nesaf`{:class="block3looks"} pan wyt ti'n clicio ar y corlun:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Os nad oes gan dy gorlun ddewis o wisgoedd, neu os wyt ti am ychwanegu mwy, galli di ychwanegu unrhyw wisg at gorlun.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Prawf:** Gweithia ar dy gorluniau nes eu bod yn rhyngweithio yn y ffordd rwyt ti eisiau. Ceisia wneud un newid ar y tro a phrofi yr hyn y mae'n ei wneud fel y galli di adnabod pob newid yn hawdd a dad-wneud unrhyw beth dwyt ti ddim yn ei hoffi.

--- /task ---

--- task ---

**Difa chwilod:**

Os wyt ti'n ychwanegu cod at y corlun anghywir, galli di drwsio hynny:

[[[scratch3-copy-code]]]

Os oes angen, galli di ailosod yr effeithiau graffeg:

--- collapse ---
---
title: Dydw i ddim eisiau yr effeithiau graffig yma
---

I ailosod yr effeithiau graffig ar unrhyw adeg, clicia ar y bloc `clirio effeithiau graffeg`{:class="block3looks"} yn y ddewislen blociau `Edrychiad`{:class="block3looks"}. Mae clicio ar y faner werdd hefyd yn clirio effeithiau graffeg.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- save ---

