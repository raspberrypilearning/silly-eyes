## Efekty duszka

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Możesz sprawić, aby duszki **postaci** i **głupkowatego oka** zmieniały swój `Wygląd`{:class="block3looks"} po ich kliknięciu.
</div>
<div>

![Postać i oczy z efektami graficznymi.](images/character-graphic-effects.png){:width="300px"}    

</div>
</div>

### Efekty dla głupkowatych oczu

--- task ---

Dodaj blok `kiedy ten duszek kliknięty`{:class="block3events"} do swojego duszka **Oko**.

Czy potrafisz określić, jaki blok kodu należy umieścić pod spodem, aby zmienić kolor oczu duszka po kliknięciu duszka **Oko**?

--- collapse ---
---
title: Zmień efekty graficzne po kliknięciu duszka
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Jeśli chcesz, aby obie gałki oczne miały ten sam efekt, musisz skopiować skrypt do duszka **Oko 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Efekty postaci

--- task ---

Kliknij duszka **postać** na liście duszków, a następnie kliknij zakładkę **Skrypt**.

Dodaj ten sam skrypt, którego użyliśmy do zmiany koloru oczu. Jakie efekty graficzne chcesz zmienić dla swojej **postaci**?

**Wybierz:** Wybierz efekt z menu rozwijanego w bloku `zmień efekt kolor o`{:class="block3looks"}. Eksperymentuj z liczbami i efektami, aż uzyskasz pożądaną zmianę.

[[[scratch3-graphic-effects]]]

--- /task ---

### Akcesoria

Teraz dodaj **akcesoria**, takie jak kapelusz, które zmieniają się po kliknięciu — użyj bloku `następny kostium`{:class="block3looks"}.

--- task ---

**Wybierz:** Dodaj zmianę akcesorium lub zmianę kostiumu na taki, jaki chcesz.

![Duszki z akcesoriami.](images/accessory-sprite.png)

--- collapse ---
---
title: Spraw, aby duszek zmieniał swój kostium po kliknięciu
---
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Niektóre duszki mają już wybór kostiumów.

Możesz dodać kod, aby zmienić kostium duszka na `następny kostium`{:class="block3looks"} po kliknięciu duszka:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Jeśli duszek nie ma możliwości wyboru kostiumów lub chcesz dodać ich więcej, możesz dodać do duszka dowolny kostium.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Test:** Pracuj nad swoimi duszkami, aż będą wchodzić w interakcje w pożądany sposób.

**Wskazówka:** Wypróbuj jedną zmianę i przetestuj jej działanie, aby móc łatwo wykryć każdą zmianę i cofnąć wszystko, co Ci się nie podoba.

--- /task ---

--- task ---

**Debugowanie:**

Jeśli dodasz kod do niewłaściwego duszka, możesz to naprawić:

[[[scratch3-copy-code]]]

W razie potrzeby możesz zresetować efekty graficzne:

--- collapse ---
---
title: Nie chcę tych efektów graficznych
---

Aby w dowolnym momencie zresetować efekty graficzne, kliknij blok `wyczyść efekty graficzne`{:class="block3looks"} w menu bloków `Wygląd`{:class="block3looks"}. Kliknięcie zielonej flagi również usuwa efekty graficzne.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Test:** Przetestuj swój projekt ponownie, ale tym razem uruchom go na pełnym ekranie, aby można było zobaczyć, jak będzie wyglądał dla kogoś, kto będzie chciał go obejrzeć.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Wyświetlając swój projekt na pełnym ekranie, widzisz go z perspektywy użytkownika, który bawi się nim. **Interakcja z użytkownikiem** jest ważna w tworzeniu treści cyfrowych. 
</p>


