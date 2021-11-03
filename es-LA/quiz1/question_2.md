--- question ---
---
legend: Pregunta 2 de 3
---

Para hacer que el cohete sea interactivo, el **cohete** tiene este script:

```blocks3
when flag clicked
set rotation style [all around v]
forever
point towards (mouse-pointer v)
end
```

¿Qué disfraz del **cohete** deberíamos usar para que la parte superior del cohete apunte hacia el puntero del ratón?

--- choices ---

- ( ) ![Un cohete apuntando hacia el lado izquierdo.](images/rocket_left.png)

  --- feedback ---

Si el cohete apunta hacia el lado izquierdo, el cohete estará orientado en la dirección opuesta (alejándose de) el puntero del ratón cuando gire.

  --- /feedback ---

- ( ) ![Un cohete apuntando hacia abajo.](images/rocket_down.png)

  --- feedback ---

Si el cohete mira hacia abajo, estará en una dirección diferente a la del puntero del ratón cuando gire.

  --- /feedback ---

- (x) ![Un cohete apuntando hacia el lado derecho.](images/rocket_right.png)

  --- feedback ---

Si el cohete apunta hacia el lado derecho, el cohete está en la posición predeterminada para apuntar correctamente hacia el puntero del mouse si se fija el estilo de rotación a `en todas las direcciones`{:class="block3motion"}.

  --- /feedback ---

- ( ) ![Un cohete apuntando hacia arriba.](images/rocket_up.png)

  --- feedback ---

Si el cohete mira hacia arriba, estará en una dirección diferente a la del puntero del ratón cuando gire.

  --- /feedback ---

--- /choices ---

--- /question ---
