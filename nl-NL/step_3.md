## Maak maffe ogen

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In deze stap maak je de maffe ogen! Elk oog moet een afzonderlijke sprite zijn, zodat het afzonderlijk kan bewegen.

Als je hulp nodig hebt, bekijk dan de tips in de taak **Fouten oplossen** onder aan deze stap.
</div>
<div>

![Een personage met maffe ogen.](images/character-with-eyes.png){:width="300px"}  

</div>
</div>

--- task ---

Gebruik de **Teken** optie om een nieuwe **sprite** te maken.

![De 'Teken' optie in het 'Kies een sprite' menu.](images/paint-a-sprite.png)

De Teken-editor wordt geopend, waarmee je jouw **Oogbol** sprite kunt maken.

--- /task ---

Het is echt belangrijk dat:
- De zwarte pupil en de gekleurde iris aan de rechterkant staan van het **Oogbol** uiterlijk
- Het **Oogbol** uiterlijk is gecentreerd

--- task ---

**Kies:** Teken een oogbol **of** start vanuit een ronde sprite.

--- collapse ---
---
title: Teken een oogbol in de Teken-editor
---

Selecteer het **Cirkel**-gereedschap.

Om een perfecte cirkel te tekenen, houd je de <kbd>Shift</kbd> op het toetsenbord ingedrukt terwijl je tekent met het **Cirkel**-gereedschap. Als je een tablet gebruikt, probeer dan zo dicht mogelijk bij een perfecte cirkel te komen.

In dit voorbeeld stellen we de **Omtrek** op zwart en de **Vulling**-kleur van de oogbol op wit:

![Een witte oogbol met een zwarte omtrek.](images/eyeball-outline.png)

Gebruik de **Vulling**- en **Omtrek** kleurkiezers om kleuren te kiezen. Om zwart te maken, schuif je zowel **Verzadiging** als **Helderheid** naar `0`. Om wit te maken, schuif je de **Verzadiging** naar `0` en de **Helderheid** naar `100`.

![](images/black-colour.png) ![](images/white-colour.png)

Zorg ervoor dat de oogbol gecentreerd is - verplaats hem zodat het blauwe kruis in het uiterlijk uitgelijnd is met het grijze dradenkruis in de Teken-editor.

Teken een kleinere perfecte cirkel en plaats deze aan de rechterkant van de oogbol:

![Een oogbol met een rode iris en zwarte pupil aan de rechterkant.](images/eyeball-with-iris.png)

Je kunt ook cirkels binnen cirkels tekenen of kleur gebruiken om verschillende effecten te krijgen.

--- /collapse ---


--- collapse ---
---
title: Verander een rond uiterlijk in een oogbol
---

Er zijn uiterlijken in Scratch die je kunt bewerken om maffe ogen voor je personage te maken.

Gebruik de Teken-editor om een uiterlijk te wijzigen. Je kunt cirkels toevoegen, een andere **Vulling**-kleur kiezen of delen van het uiterlijk verwijderen om er een maf oog van te maken.

**Tip:** Je moet het **Oogbol**-uiterlijk in de Teken-editor centreren zodat het soepel draait terwijl het ronddraait. Gebruik het dradenkruis om het uiterlijk te centreren. De zwarte pupil en gekleurde iris moeten aan de rechterkant van het uiterlijk worden geplaatst, zodat de **Oogbol** de muisaanwijzer volgt.

![Bestaande Scratch-uiterlijken als oogbollen.](images/costume-eyes.gif)

![De Teken-editor die een bewerkt button1-uiterlijk toont.](images/button-eye.png)

--- /collapse ---

--- /task ---

--- task ---

Noem je sprite `Oogbol` in het Sprite-paneel.

![De naam van de sprite is ingesteld op 'Oogbal' in het Sprite-paneel.](images/eyeball-name.png)

--- /task ---

--- task ---

Sleep de **Oogbol**-sprite om deze op het werkgebied te plaatsen en wijzig de grootte zodat deze bij jouw personage past.

--- /task ---

Laat de oogbol nu naar de `muisaanwijzer`{:class="block3motion"} kijken.

--- task ---

Voeg een script toe om `maak de draaistijl`{:class="block3motion"} in te stellen op `helemaal rond`{:class="block3motion"} om de oogbol `naar de muisaanwijzer`{:class="block3motion"} te laten wijzen `voor altijd herhaald`{:class="block3control"}.

--- collapse ---
---
title: Laat een sprite naar de muisaanwijzer wijzen
---

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

--- /collapse ---

--- /task ---


Als je personage maar één oog heeft, ben je klaar.

--- task ---

Klik anders met de rechtermuisknop (of tik op een tablet en houd vast) op de **Oogbol**-sprite in de Sprite-lijst en kies **dupliceren** om meer maffe ogen te creëren.

[[[scratch3-duplicate-sprite]]]

--- /task ---

--- task ---

**Test:** Klik op de groene vlag en test jouw project. Volgen de maffe ogen je muisaanwijzer terwijl je de muis beweegt?

**Tip:** Je hoeft de muisaanwijzer niet op het speelveld te houden. De ogen zullen jouw muisaanwijzer volgen terwijl je doorgaat met coderen in Scratch.

--- /task ---

--- task ---

**Fouten oplossen:** Mogelijk vind je enkele fouten in jouw project die je moet oplossen. Hier zijn enkele veelvoorkomende fouten:

--- collapse ---
---
title: De ogen bewegen niet
---

Zorg ervoor dat je de code hebt toegevoegd aan de **Oogbol**-sprites en **geklikt op de groene vlag**. Je code wordt pas uitgevoerd als je op de groene vlag klikt.

--- /collapse ---

--- collapse ---
---
title: De ogen wijzen weg van de muis
---

Controleer in de **Oogbol** uiterlijken of de pupil zich aan de rechterkant bevindt (voorbij het blauwe kruis in het midden van het uiterlijk).

De **Oogbol** sprites hebben de `helemal rond`{:class="block3motion"} `draaistijl`{:class="block3motion"}, zodat ze in elke richting kunnen draaien.

Wanneer de **Oogbollen** roteren naar `wijzen in de richting van`{:class="block3motion"} de `muisaanwijzer`{:class="block3motion"}, dan zullen de pupillen zich het dichtst bij de muisaanwijzer bevinden.

![De pupil aan de rechterkant van een oogboluiterlijk plaatsen.](images/eye-right.gif)

![Een oogboluiterlijk met de pupil aan de rechterkant.](images/eye-costume.png)

--- /collapse ---

--- collapse ---
---
title: De ogen springen over het speelveld
---

Controleer of de **Oogbol** uiterlijken gecentreerd zijn. Om een uiterlijk te centreren, sleep je het uiterlijk zo dat het blauwe kruis in het uiterlijk op één lijn ligt met het grijze dradenkruis in de Teken-editor.

![Een oogboluiterlijk centreren in de Teken-editor.](images/eye-centered.gif)

![Een oogboluiterlijk gecentreerd in de Teken-editor.](images/eye-costume.png)

--- /collapse ---

--- collapse ---
---
title: Het personage staat voor de ogen
---

Wanneer je een sprite sleept om deze in het speelveld te plaatsen, beweegt deze voor de andere sprites.

Om ervoor te zorgen dat je sprite van je **personage** `achteraan`{:class="block3looks"} blijft, gebruik je:

```blocks3
when green flag clicked
forever
go to [back v] layer // achter alle andere sprites
```

--- /collapse ---

--- collapse ---
---
title: Het personage en de ogen volgen de muisaanwijzer
---

Heb je de ogen toegevoegd als uiterlijken voor je **personage** in plaats van als uiterlijken voor afzonderlijke sprites? Je kunt dat oplossen.

Een manier om dit op te lossen is door het **personage** te dupliceren en vervolgens de kopie `Oogbol` te noemen. Verwijder vervolgens de **Oogbol**-uiterlijken van de **personage** sprite en verwijder de **personage** uiterlijken van de **Oogbol** sprite. Vervolgens kun je de **Oogbol** dupliceren en de kopie `Oogbol 2`noemen.

De code voor `richt naar`{:class="block3motion"} de `muisaanwijzer`{:class="block3motion"} moet op de **Oogbol** sprites staan en niet de **personage** sprite.

--- /collapse ---

--- collapse ---
---
title: Het personage volgt de muisaanwijzer (en de ogen niet)
---

Je moet het `richt naar`{:class="block3motion"} code toevoegen aan de individuele **Oogbol** sprites, niet je **personage** sprite!

Om de code te kopiëren, kun je de code van het Code-gebied van je **personage** naar de **Oogbol** sprites in de Sprite-lijst slepen.

Je moet ook het script van de **personage** sprite verwijderen. Sleep hiervoor het script naar het Blokkenmenu.

--- /collapse ---

Mogelijk vind je een fout die hier niet wordt vermeld. Kun je achterhalen hoe deze te repareren is?

We horen graag over je fouten en hoe je ze hebt opgelost. Gebruik de **Feedback verzenden** knop onderaan deze pagina en vertel ons of je een andere fout in je project hebt gevonden.


--- /task ---

--- save ---
