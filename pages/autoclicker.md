---
layout: main
permalink: /autoclicker
---

{% include intro.md %}

## Enunciado

<video style="float: right; margin: 10px" controls autoplay>
  <source src="./assets/movies/autoclicker.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

Queremos que crees una app móvil web progresiva basada en los famosos juegos de puntos incrementales como __Cookie Clicker__. Si no lo conoces no pasa nada, a continuación te detallamos el funcionamiento de la misma.

La aplicación debe tener una primera vista **“home”** en la que el usuario introducirá su nombre para registrarse y empezar el juego. Esta primera vista deberá ser la ruta por defecto y cualquier acceso a una ruta que no exista debería redirigir a dicha vista.

La vista **“home”** contendrá al menos **un campo de texto** para introducir el nombre del jugador **y un botón** para iniciar el juego. El botón validará que se ha introducido un nombre de usuario válido antes de iniciar el juego.

Una vez se ha creado el usuario, se transiciona a la vista de juego **“game”** siendo ésta una nueva ruta dentro de la app.

La vista **“game”** mostrará el **nombre del jugador, los puntos que tiene, un botón para generar más puntos y otro para salir**.

Cada vez que se haga `click` en el botón de la vista, se ganará un punto. Este proceso se podrá repetir indefinidamente

Cuando se alcance un número determinado de puntos, al jugador se le mostrará un nuevo botón para comprar “autoclickers”.

Comprar “autoclickers” costará un número determinado de puntos que será incremental en función del número de “autoclickers” comprados. Se puede usar la siguiente fórmula para el coste de los "autoclickers":

> `autoClickerCost = autoClickerBaseCost + autoClickerBaseCost * numAutoClickers`

Por cada “autoclicker” comprado, el jugador ganará un punto cada 100 milisegundos. Si el jugador no tiene suficientes puntos para comprar un “autoclicker” el botón se le mostrará deshabilitado.

El botón de salir permitirá volver al vista “home” y se dejarán de ganar puntos de manera automática para el jugador.

Si en la vista “home” se vuelve a introducir un nombre de jugador que ya existía, se continuará la partida dónde el jugador la dejara.

Si por cualquier motivo se cerrase la applicación, al volver a acceder se continuará con el mismo estado en el que estaba cuando se cerró, es decir, **se deberán persistir los datos de todos los jugadores**.

La aplicación **deberá funcionar offline**, es decir, si en nuestro dispositivo activamos el modo avión y volvemos a la app tras haberla abierto al menos una vez, se podrá acceder a la misma sin problemas.

La aplicación deberá estar desplegada y disponible públicamente.

> **¡RECUERDA!** Los ejemplos visuales mostrados son únicamente orientativos y no deben sesgar tu creatividad.

## Requisitos

- La aplicación deberá contener funcionalmente, como mínimo, las instrucciones detalladas en el enunciado.
- **El código debe ser público** y estar alojado en algún repositorio de git, por ejemplo, [Github](https://github.com/), [GitLab](https://gitlab.com/) o [Bitbucket](https://bitbucket.org).
- Se deberán realizar **tests unitarios** de las vistas y de los componentes de la aplicación.
- Se podrá utilizar cualquier infraestructura de alojamiento pública como, por ejemplo, [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/) o [Github Pages](https://pages.github.com/).
- Se debe subir un **fichero README.md** al repositorio **con las instrucciones** para hacer funcionar la aplicación en local. Puedes añadir cualquier otro dato que consideres necesario.

{% include extra.md %}

{% include output.md %}

{% include goodluck.html %}
