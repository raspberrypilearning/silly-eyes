--- question ---
---
legend: Domanda 2 di 3
---

Per rendere interattivo il razzo, lo sprite **rocket** ha questo script:

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

Quale costume **rocket** dovremmo usare in modo che la parte superiore del razzo punti verso il puntatore del mouse?

--- choices ---

- ( ) ![Un razzo che punta verso il lato sinistro.](images/rocket_left.png)

  --- feedback ---

Se il razzo punta verso il lato sinistro, il razzo sarà rivolto nella direzione opposta (lontano dal) puntatore del mouse quando ruoterà.

  --- /feedback ---

- ( ) ![Un razzo rivolto verso il basso.](images/rocket_down.png)

  --- feedback ---

Se il razzo è rivolto verso il basso, sarà rivolto in una direzione diversa rispetto al puntatore del mouse quando ruoterà.

  --- /feedback ---

- (x) ![Un razzo che punta verso il lato destro.](images/rocket_right.png)

  --- feedback ---

Se il razzo punta verso destra, il razzo è nella posizione predefinita per puntare correttamente verso il puntatore del mouse se lo stile di rotazione è impostato su `può ruotare`{:class="block3motion"}.

  --- /feedback ---

- ( ) ![Un razzo rivolto verso l'alto.](images/rocket_up.png)

  --- feedback ---

Se il razzo è rivolto verso l'alto, sarà rivolto in una direzione diversa rispetto al puntatore del mouse quando ruoterà.

  --- /feedback ---

--- /choices ---

--- /question ---
