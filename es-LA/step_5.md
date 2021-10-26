## Efectos para escenario

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
También puedes hacer que el proyecto haga algo cuando haces clic en el ** Escenario **.
</div>
<div>

![El Escenario con efectos gráficos.](images/stage-effects.png){:width="300px"} 
{:width="300px"}  

</div>
</div>

--- task ---

Haz clic en el panel Escenario y luego en la pestaña **Código** para agregar código al **Escenario**.

**Elige:** Elige lo que deseas que cambie al hacer clic en el **Escenario**.

--- collapse ---
---
title: Cambia los efectos gráficos al hacer clic en el Escenario
---

```blocks3
when stage clicked
change [color v] effect by [25]
```

--- /collapse ---

--- collapse ---
---
title: Cambia el fondo al hacer clic en el escenario
---

```blocks3
when stage clicked
next backdrop
```

--- /collapse ---

--- /task ---

--- task ---

**Prueba:** Haz clic en el **Escenario** y comprueba que el fondo o los efectos gráficos cambian.

--- /task ---

--- task ---

**Prueba:** Prueba tu proyecto nuevamente, pero esta vez, hazlo en pantalla completa para que puedas ver cómo se verá cuando alguien más lo mire.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Al ver tu proyecto en pantalla completa, estás viendo lo que has hecho desde la perspectiva de un usuario que está jugando con tu proyecto. La ** Interacción del usuario ** es importante en la creación digital. 
</p>

--- save ---
