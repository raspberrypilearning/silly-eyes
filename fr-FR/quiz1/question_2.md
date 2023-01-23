--- question ---
---
legend: Question 2 sur 3
---

Pour rendre la fusée interactive, le sprite **fusée** a ce script :

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

Quel costume de **fusée** devons-nous utiliser pour que le haut de la fusée pointe vers le pointeur de la souris ?

--- choices ---

- ( ) ![Une fusée pointée vers la gauche.](images/rocket_left.png)

  --- feedback ---

Si la fusée pointe vers le côté gauche, la fusée sera tournée dans la direction opposée (loin du) pointeur de la souris lorsqu'elle tourne.

  --- /feedback ---

- ( ) ![Une fusée tournée vers le bas.](images/rocket_down.png)

  --- feedback ---

Si la fusée est orientée vers le bas, elle sera orientée dans une direction différente de celle du pointeur de la souris lorsqu'elle tournera.

  --- /feedback ---

- (x) ![Une fusée pointée vers la droite.](images/rocket_right.png)

  --- feedback ---

Si la fusée pointe vers le côté droit, la fusée est dans la position par défaut pour pointer correctement vers le pointeur de votre souris si le style de rotation est défini sur `360°`{:class="block3motion"}.

  --- /feedback ---

- ( ) ![Une fusée tournée vers le haut.](images/rocket_up.png)

  --- feedback ---

Si la fusée est orientée vers le haut, elle sera orientée dans une direction différente de celle du pointeur de la souris lorsqu'elle tournera.

  --- /feedback ---

--- /choices ---

--- /question ---
