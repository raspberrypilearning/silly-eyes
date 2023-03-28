--- question ---
---
legend: Fråga 2 av 3
---

För att göra raketen interaktiv har **raket**sprajten den här koden:

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

Vilken **raket**-klädsel ska vi använda så att toppen av raketen pekar mot muspekaren?

--- choices ---

- ( ) ![En raket som pekar åt vänster.](images/rocket_left.png)

  --- feedback ---

Om raketen pekar åt vänster, kommer raketen att vara vänd i motsatt riktning till (bort från) muspekaren när den roterar.

  --- /feedback ---

- ( ) ![En nedåtvänd raket.](images/rocket_down.png)

  --- feedback ---

Om raketen är vänd nedåt kommer den att vara vänd mot en annan riktning än muspekaren när den roterar.

  --- /feedback ---

- (x) ![En raket pekar åt höger.](images/rocket_right.png)

  --- feedback ---

Om raketen pekar mot höger sida är raketen i standardpositionen för att peka mot din muspekare om rotationsstilen är inställd på `rotera`{:class="block3motion"}.

  --- /feedback ---

- ( ) ![En uppåtvänd raket.](images/rocket_up.png)

  --- feedback ---

Om raketen är vänd uppåt kommer den att vara vänd mot en annan riktning än muspekaren när den roterar.

  --- /feedback ---

--- /choices ---

--- /question ---
