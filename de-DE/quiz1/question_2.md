--- question ---
---
legend: Frage 2 von 3
---

Um die Rakete interaktiv zu machen, hat die Figur **Rakete** dieses Skript:

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

Welches **Raketen** Kostüm sollten wir verwenden, damit die Spitze der Rakete zum Mauszeiger zeigt?

--- choices ---

- ( ) ![Eine Rakete, die nach links zeigt.](images/rocket_left.png)

  --- feedback ---

Wenn die Rakete nach links zeigt, wird sie beim Drehen in die entgegengesetzte Richtung (von dem Mauszeiger weg) zeigen.

  --- /feedback ---

- ( ) ![Eine nach unten gerichtete Rakete.](images/rocket_down.png)

  --- feedback ---

Wenn die Rakete nach unten zeigt, zeigt sie beim Drehen in eine andere Richtung als der Mauszeiger.

  --- /feedback ---

- (x) ![Eine Rakete, die nach rechts zeigt.](images/rocket_right.png)

  --- feedback ---

Wenn die Rakete nach rechts zeigt, befindet sie sich in der Standardposition, um korrekt auf deinen Mauszeiger zu zeigen, sofern der Drehtyp auf `rundherum`{:class="block3motion"} eingestellt ist.

  --- /feedback ---

- ( ) ![Eine Rakete, die nach oben zeigt.](images/rocket_up.png)

  --- feedback ---

Wenn die Rakete nach oben zeigt, zeigt sie beim Drehen in eine andere Richtung als der Mauszeiger.

  --- /feedback ---

--- /choices ---

--- /question ---
