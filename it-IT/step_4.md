## Effetti sugli sprite

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Puoi fare in modo che lo sprite del tuo **personaggio** e gli sprite dell'**occhio buffo** cambino il loro `Aspetto`{:class="block3looks"} quando fai clic su di essi.
</div>
<div>

![Un personaggio e i suoi occhi con effetti grafici.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Effetti per gli occhi buffi

--- task ---

Aggiungi un blocco `quando si clicca su questo sprite`{:class="block3events"} al tuo sprite **Bulbo oculare**.

Riesci a capire quale blocco di codice inseriresti sotto per cambiare il colore degli occhi del tuo sprite quando fai clic sullo sprite **Bulbo oculare**?

--- collapse ---
---
title: Modifica gli effetti grafici quando si fa clic sullo sprite
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Se vuoi che entrambi i bulbi oculari abbiano lo stesso effetto, dovrai copiare il tuo script nello sprite **Bulbo oculare 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Effetti sui personaggi

--- task ---

Fai clic sul tuo sprite del **personaggio** nell'elenco degli Sprite, poi fai clic sulla scheda **Codice**.

Aggiungi lo stesso script che hai usato per cambiare il colore degli occhi. Quali effetti grafici vuoi cambiare per il tuo **personaggio**?

**Scegli:** Scegli un effetto nel menu a discesa all'interno del blocco `cambia effetto colore`{:class="block3looks"}. Sperimenta i numeri e gli effetti finché non ottieni il cambiamento che ti piace.

[[[scratch3-graphic-effects]]]

--- /task ---

### Un accessorio

Ora aggiungi un **accessorio**, ad esempio un cappello, che cambia quando fai clic su di esso: utilizza il blocco `passa al costume seguente`{:class="block3looks"}.

--- task ---

**Scegli:** Aggiungi un cambio di accessorio o un cambio di costume a tua scelta.

![Sprite con accessori.](images/accessory-sprite.png)

--- collapse ---
---
title: Fai cambiare costume al tuo sprite quando viene cliccato
---
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Alcuni sprite hanno già una scelta di costumi.

Puoi aggiungere il codice per modificare il costume di uno sprite quando fai clic sullo sprite, utilizzando il blocco `passa al costume successivo`{:class="block3looks"}:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Se il tuo sprite non ha una scelta di costumi, o vuoi aggiungerne altri, puoi aggiungere qualsiasi costume allo sprite.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Prova:** Modifica i tuoi sprite finché non interagiscono nel modo che desideri.

**Suggerimento:** Prova una modifica alla volta e verifica cosa fa in modo da poter individuare facilmente ogni modifica e togliere tutto ciò che non ti piace.

--- /task ---

--- task ---

**Debug:**

Se aggiungi codice allo sprite sbagliato, puoi sistemarlo:

[[[scratch3-copy-code]]]

Se vuoi, puoi ripristinare gli effetti grafici:

--- collapse ---
---
title: Non voglio questi effetti grafici
---

Per ripristinare gli effetti grafici in qualsiasi momento, clicca sul blocco `rimuovi effetti grafici`{:class="block3looks"} nel menu dei blocchi `Aspetto`{:class="block3looks"}. Facendo clic sulla bandierina verde si cancellano anche gli effetti grafici.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Prova:** Prova nuovamente il tuo progetto, ma questa volta impostalo a schermo intero in modo da poter vedere come apparirà a qualcuno che lo guarda.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Rendendo il tuo progetto a schermo intero, vedrai ciò che hai realizzato dal punto di vista di un utente che sta giocando con il tuo progetto. **L'interazione con l'utente** (User Interaction) è importante nella creazione digitale. 
</p>


