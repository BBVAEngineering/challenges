---
layout: main
permalink: /autoclicker
---

<style type="text/css" media="screen">
h1 {
  text-align: center;
}
</style>

# ¡Demuéstranos lo que sabes!

Como parte de nuestro proceso de selección, nos gustaría ver qué tipo de aplicación eres capaz de desarrollar. Valoraremos muy positivamente cualquier característica adicional, tanto en la aplicación como en el entorno de desarrollo o despliegue, que quieras implementar por tu cuenta.

## Enunciado

<video style="float: right; margin: 10px" controls autoplay>
  <source src="./assets/movies/autoclicker.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

Queremos que crees una app móvil web progresiva basada en los famosos juegos de puntos incrementales como Cookie Clicker. Si no lo conoces no pasa nada, a continuación te detallamos el funcionamiento de la misma.

La aplicación debe tener una primera vista “home” en la que el usuario introducirá su nombre para registrarse y empezar el juego. Esta primera vista deberá ser la ruta por defecto y cualquier acceso a una ruta que no exista debería redirigir a dicha vista.

La vista contendrá al menos un input para introducir el nombre del jugador y un botón para iniciar el juego. El botón validará que se ha introducido un nombre de usuario válido antes de iniciar el juego.

Una vez se ha creado el usuario, se transiciona a la vista de juego “game” siendo ésta una nueva ruta dentro de la app.

La vista de juego mostrará el nombre del jugador, los puntos que tiene, un botón para generar más puntos y otro para salir.

Cada vez que se haga click en el botón de la vista, se ganará un punto. Este proceso se podrá repetir indefinidamente

Cuando se alcance un número determinado de puntos, al jugador se le mostrará un nuevo botón para comprar “autoclickers”.

Comprar “autoclickers” costará un número determinado de puntos que será incremental en función del número de “autoclickers” comprados.

Por cada “autoclicker” comprado, el jugador ganará un punto cada 100 milisegundos. Si el jugador no tiene suficientes puntos para comprar un “autoclicker” el botón se le mostrará deshabilitado.

El botón de salir permitirá volver al vista “home” y se dejarán de ganar puntos de manera automática para el jugador.

Si en la vista “home” se vuelve a introducir un nombre de jugador que ya existía, se continuará la partida dónde el jugador la dejara.

Si se cierra la app y se vuelve a abrir, se continuará con el mismo estado en el que estaba cuando se cerró, es decir, se deberán persistir los datos de todos los jugadores.

La aplicación deberá funcionar offline, es decir, si en nuestro dispositivo activamos el modo avión y volvemos a la app tras haberla abierto al menos una vez, se podrá acceder a la misma sin problemas.

La aplicación deberá estar desplegada y disponible públicamente.

Los ejemplos visuales mostrados son únicamente orientativos y no deben sesgar tu creatividad.

## Requisitos

- La aplicación deberá contener funcionalmente, como mínimo, las instrucciones detalladas en el enunciado.
- El código debe ser público y estar alojado en algún repositorio de git, por ejemplo, [Github](https://github.com/), [GitLab](https://gitlab.com/) o [Bitbucket](https://bitbucket.org).
- Se deberán realizar tests unitarios de las vistas y de los componentes de la aplicación.
- Se podrá utilizar cualquier infraestructura de alojamiento pública como, por ejemplo, [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/) o [Github Pages](https://pages.github.com/).
- Se debe subir un fichero README.md al repositorio con las instrucciones para hacer funcionar la aplicación en local. Puedes añadir cualquier otro dato que consideres necesario.

## Otras consideraciones

Se puede utilizar cualquier herramienta, librería o framework, dentro del ecosistema  de JavaScript.

Si crees que lo anterior no es suficiente y quieres demostrarnos todo lo que sabes, se valorarán muy positivamente otros puntos como:

- La calidad, claridad y limpieza del código.
- El uso de componentes reutilizables.
- La realización de otro tipo de tests.
- Herramientas de análisis estático y formateo de código que mejoren la experiencia del desarrollador.
- Mejoras en el flujo y la metodología de desarrollo, construcción y despliegue.
- Otras características que consideres importantes para una aplicación web progresiva.

## Entregable

Envíanos un enlace al repositorio en el que se encuentre el código de la aplicación y un enlace con la url de la aplicación desplegada.

