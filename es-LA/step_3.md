## Crea ojos tontos

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
¡En este paso, crearás los ojos tontos! Cada ojo debe ser un objeto separado para que pueda moverse independientemente.

Si necesitas ayuda, consulta las sugerencias de la tarea **Depurar** al final de este paso.
</div>
<div>

![Un personaje de ojos tontos.](images/character-with-eyes.png){:width="300px"}  

</div>
</div>

--- task ---

Utiliza la opción **Pintar** para crear un nuevo **objeto**.

![La opción 'Pintar' en el menú 'Elegir un objeto'.](images/paint-a-sprite.png)

Se abrirá el Editor de dibujo, lo que te permitirá crear el disfraz de **Globo ocular**.

--- /task ---

Es súper importante que:
- La pupila negra y el iris de color miren hacia el lado derecho del disfraz **Globo ocular**
- El **Globo ocular** esté centrado

--- task ---

**Elige:** Dibuja un globo ocular **o** empieza con un objeto redondo.

--- collapse ---
---
title: Dibuja un globo ocular en el Editor de dibujo
---

Selecciona la herramienta **Círculo**.

Para dibujar un círculo perfecto, mantén presionada la tecla <kbd>Mayúscula</kbd> en el teclado mientras dibujas con la herramienta **Círculo**. Si estás usando una tableta, trata de dibujar un círculo lo más perfecto que puedas.

En este ejemplo, estableceremos el **Contorno** en negro y el **Relleno** del globo ocular en blanco:

![Un globo ocular blanco con un contorno negro.](images/eyeball-outline.png)

Usa los selectores de color de **Relleno** y **Contorno** para elegir colores. Para hacerlo negro, cambia tanto la **Saturación** como el **Brillo** a `0`. Para hacerlo blanco, cambia la **Saturación** a `0` y el **Brillo** a `100`.

![](images/black-colour.png) ![](images/white-colour.png)

Asegúrate de que el globo ocular esté centrado; muévelo de modo que la cruz azul del disfraz se alinee con la cruz gris en el Editor de dibujo.

Dibuja un círculo perfecto más pequeño y colócalo en el lado derecho del globo ocular:

![Un globo ocular con iris rojo y pupila negra en el lado derecho.](images/eyeball-with-iris.png)

También puedes dibujar círculos dentro de círculos o usar colores para obtener diferentes efectos.

--- /collapse ---


--- collapse ---
---
title: Convierte un disfraz redondo en un globo ocular
---

Hay disfraces en Scratch que puedes editar para crear ojos tontos para tu personaje.

Usa el Editor de dibujo para cambiar un disfraz. Puedes agregar círculos, elegir un color de **Relleno** diferente o quitar partes del disfraz para convertirlo en un ojo tonto.

**Sugerencia:** Tienes que centrar el disfraz **Globo ocular** en el Editor de dibujo para que gire suavemente a medida que gira. Usa la mira para centrar el disfraz. La pupila negra y el iris de color deben colocarse en el lado derecho del disfraz para que el **Globo ocular** siga el puntero del ratón.

![Disfraces de Scratch existentes como globos oculares.](images/costume-eyes.gif)

![El Editor de dibujo que muestra un disfraz button1 editado.](images/button-eye.png)

--- /collapse ---

--- /task ---

--- task ---

Nombra tu objeto `Globo ocular` en el Panel de objetos.

![El nombre del objeto establecido como 'Globo ocular' en el Panel de objetos.](images/eyeball-name.png)

--- /task ---

--- task ---

Arrastra el objeto **Globo ocular** para colocarlo en el escenario y cambia su tamaño para que se ajuste a tu personaje.

--- /task ---

Ahora, haz que el globo ocular mire el `puntero del ratón`{:class="block3motion"}.

--- task ---

Agrega un Script `fijar estilo de rotación a`{:class="block3motion"} `en todas las direcciones`{:class="block3motion"} para hacer que el globo ocular pueda `apuntar hacia puntero del ratón`{:class="block3motion"} `por siempre`{:class="block3control"}.

--- collapse ---
---
title: Haz que un objeto apunte hacia el puntero del ratón
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


Si tu personaje tiene un solo ojo, entonces has terminado.

--- task ---

De lo contrario, haz clic con el botón derecho (o en una tableta, mantén presionado) en el objeto **Globo ocular** en la Lista de objetos y elige **duplicar** para crear más ojos tontos.

[[[scratch3-duplicate-sprite]]]

--- /task ---

--- task ---

**Prueba:** Haz clic en la bandera verde y prueba tu proyecto. ¿Los ojos tontos siguen el puntero de tu ratón cuando lo mueves?

**Sugerencia:** No es necesario que mantengas el puntero del ratón en el escenario. Los ojos seguirán el puntero del ratón mientras continúas codificando en Scratch.

--- /task ---

--- task ---

**Depurar:** Es posible que encuentres algunos errores en tu proyecto que necesites corregir. A continuación, se muestran algunos errores comunes:

--- collapse ---
---
title: Los ojos no se mueven
---

Asegúrate de haber agregado el código a los objetos **Globo ocular** y hayas **presionado la bandera verde**. Tu código no se ejecutará hasta que hagas clic en la bandera verde.

--- /collapse ---

--- collapse ---
---
title: Los ojos apuntan lejos del mouse
---

Para cada disfraz **Globo ocular**, comprueba que la pupila esté al lado derecho (más allá de la cruz azul en el medio del disfraz).

Los objetos **Globo ocular** tienen `en todas las direcciones`{:class="block3motion"} como `estilo de rotación`{:class="block3motion"}, por lo que pueden rotar en cualquier dirección.

Cuando los **Globos oculares** giran para `apuntar hacia`{:class="block3motion"} el `puntero del ratón`{:class="block3motion"}, las pupilas estarán más cerca del puntero del ratón.

![Colocando la pupila en el lado derecho de un disfraz de globo ocular.](images/eye-right.gif)

![Un disfraz de globo ocular con la pupila en el lado derecho.](images/eye-costume.png)

--- /collapse ---

--- collapse ---
---
title: Los ojos saltan por el escenario
---

Comprueba que los disfraces de **Globo ocular** estén centrados. Para centrar un disfraz, arrastra el disfraz de modo que la cruz azul en el disfraz se alinee con la cruz gris en el Editor de dibujo.

![Centrando un disfraz de globo ocular en el Editor de dibujo.](images/eye-centered.gif)

![Un disfraz de globo ocular centrado en el Editor de dibujo.](images/eye-costume.png)

--- /collapse ---

--- collapse ---
---
título: El personaje está frente a los ojos
---

Cuando arrastras un objeto para colocarlo en el escenario, se mueve delante de los otros objetos.

Para que el objeto de tu **personaje** se mantenga `atrás`{:class="block3looks"}, usa:

```blocks3
when green flag clicked
forever
go to [back v] layer // detrás de todos los demás objetos
```

--- /collapse ---

--- collapse ---
---
title: El personaje y los ojos siguen el puntero del ratón
---

¿Agregaste ambos ojos como disfraces para tu **personaje** en lugar de como disfraces para objetos separados? Puedes solucionarlo.

Una forma de solucionarlo es duplicar tu objeto **personaje** y luego cambiar el nombre de la copia a `Globo ocular`. Luego, elimina los disfraces **Globo ocular** del objeto **personaje**, y elimina los disfraces **personaje** del objeto **Globo ocular**. Luego, puedes duplicar el objeto **Globo ocular** y nombrar la copia `Globo ocular 2`.

El código para `apuntar hacia`{:class="block3motion"} el `puntero del ratón`{:class="block3motion"} debe estar en los objetos para **Globo ocular** y no en el objeto **personaje**.

--- /collapse ---

--- collapse ---
---
title: El personaje sigue el puntero del ratón (pero los ojos no)
---

Debes agregar el código `apuntar hacia`{:class="block3motion"} a los objetos **Globo ocular**, ¡no a tu objeto de **personaje**!

Para copiar el código, puedes arrastrar el código desde el Área de código para tu **personaje** a los objetos **Globo ocular** en la Lista de objetos.

También deberás eliminar el script del objeto **personaje**. Para hacer esto, arrastra el script al Menú de bloques.

--- /collapse ---

Es posible que encuentres un error que no se incluye aquí. ¿Puedes averiguar cómo solucionarlo?

Nos encanta conocer tus errores y cómo los solucionaste. Usa el botón **Enviar comentarios** en la parte inferior de esta página y cuéntanos si encontraste un error distinto en tu proyecto.


--- /task ---

--- save ---
