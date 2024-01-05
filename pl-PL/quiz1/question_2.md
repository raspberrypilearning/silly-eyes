--- question ---
---
legend: Pytanie 2 z 3
---

Aby uczynić rakietę interaktywną, duszek **rakieta** ma następujący skrypt:

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

Którego kostiumu **rakieta** powinniśmy użyć, aby czubek rakiety był skierowany w stronę wskaźnika myszy?

--- choices ---

- ( ) ![Rakieta skierowana w lewą stronę.](images/rocket_left.png)

  --- feedback ---

Jeśli rakieta jest skierowana w lewą stronę, to będzie ona zawsze skierowana w kierunku przeciwnym do (z dala od) wskaźnika myszy, gdy się obraca.

  --- /feedback ---

- ( ) ![Rakieta skierowana w dół.](images/rocket_down.png)

  --- feedback ---

Jeśli rakieta jest skierowana w dół, podczas obrotu będzie skierowana w innym kierunku niż wskaźnik myszy.

  --- /feedback ---

- (x) ![Rakieta skierowana w prawą stronę.](images/rocket_right.png)

  --- feedback ---

Jeśli rakieta jest skierowana w prawą stronę, to jest ona w domyślnej pozycji do prawidłowego wskazywania wskaźnika myszy, jeśli styl obrotu jest ustawiony na `dookoła`{:class="block3motion"}.

  --- /feedback ---

- ( ) ![Rakieta skierowana w górę.](images/rocket_up.png)

  --- feedback ---

Jeśli rakieta jest skierowana do góry, podczas obrotu będzie skierowana w innym kierunku niż wskaźnik myszy.

  --- /feedback ---

--- /choices ---

--- /question ---
