## Sprajteffekter

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Du kan få din **karaktärs**sprajt och **"roliga ögon"**-sprajter att ändra sitt `utseende`{:class="block3looks"} när du klickar på dem.
</div>
<div>

![En karaktär och ögon med bildeffekter.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Roliga ögoneffekter

--- task ---

Lägg till ett `"när denna sprajt klickas på"`{:class="block3events"}-block till din **ögonglob**-sprajt.

Kan du komma på vilket kodblock du behöver lägga till för att ändra din sprajts ögonfärg när du klickar på **ögonglob**sprajten?

--- collapse ---
---
title: Ändra bildeffekter när sprajten klickas
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Om du vill att båda ögongloberna ska ha samma effekt måste du kopiera din kod till **ögonglob 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Karaktärseffekter

--- task ---

Klicka på din **karaktärs**sprajt i sprajtlistan och klicka sedan på **kod**fliken.

Lägg till samma kod som du använde för att ändra ögonfärgen. Vilka bildeffekter vill du ändra för din **karaktär**?

**Välj:** Välj en effekt i rullgardinsmenyn inom `"ändra färgeffekten med"`{:class="block3looks"}-blocket. Experimentera med talen och effekterna tills du har en som du gillar.

[[[scratch3-graphic-effects]]]

--- /task ---

### Ett tillbehör

Lägg nu till ett **-tillbehör**, till exempel en hatt, som ändras när du klickar på den — använd `"nästa klädsel"`{:class="block3looks"}-blocket.

--- task ---

**Välj:** Lägg till ett tillbehörsbyte eller klädselbyte som du väljer.

![Sprajter med tillbehör.](images/accessory-sprite.png)

--- collapse ---
---
title: Få en sprajt att byta klädsel när den klickas på
---
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Vissa sprajter har redan ett urval av klädslar.

Du kan lägga till kod för att ändra en sprajts klädsel till `nästa klädsel`{:class="block3looks"} när du klickar på sprajten:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Om din sprajt inte har flera val av klädslar, eller om du vill lägga till något, kan du lägga till valfri klädsel till din sprajt.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Test:** Arbeta med dina sprajter tills de interagerar på det sätt du vill.

**Tips:** Prova en förändring i taget och testa vad den gör så att du enkelt kan upptäcka varje förändring och ångra det du inte gillar.

--- /task ---

--- task ---

**Debug (Felsökning):**

Om du lägger till kod till fel sprajt kan du fixa det:

[[[scratch3-copy-code]]]

Om du behöver kan du återställa de bildeffekterna:

--- collapse ---
---
title: Jag vill inte ha de här bildeffekterna
---

För att återställa bildeffekterna när som helst, klicka på `"rensa bildeffekter"`-blocket{:class="block3looks"} i `Utseende`{:class="block3looks"}blockmenyn. Att klicka på den gröna flaggan rensar också bildeffekter.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Test:** Testa ditt projekt igen, men den här gången gör du det i helskärm så att du kan se hur det kommer att se ut för någon annan som kollar på ditt projekt.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Genom att kolla på ditt projekt i helskärm ser du vad du har gjort utifrån en användares perspektiv som leker med ditt projekt. **Användarinteraktion** är viktigt vid digital tillverkning. 
</p>


