=== Nombre del plugin ===
Contributors: (esto debería ser una lista de usuarios de wordpress.org)
Donate link: https://ejemplo.com/
Tags: comments, spam
Requires at least: 4.6
Tested up to: 4.7
Stable tag: 4.3
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Aquí una descripción corta del plugin. No debería tener más de 150.  No uses marcado aquí.

== Description ==

Esta es la descripción larga. Sin límite, y puedes usar Markdown (así como en las siguientes secciones).

Por compatibilidad previa, si no está disponible esta sección ses usa toda la descripción corta y analiza el Markdown.

Unas cuantas notas sobre las secciones anteriores:

*   "Contributors" es una lista separada por comas de nombres de usuario de wordpress.org
*   "Tags" es una lista separada por comas de la lista de etiquetas aplicable al plugin
*   "Requires at least" es la versión más antigua en la que funcionará el plugin
*   "Tested up to" es la versión más moderna en la que "has probado con éxito el plugin". Podría funcionar en versiones superiores … 
esta es simplemente la más moderna en la que lo has verificado.
*   La tag Stable debería indicar la "tag" en Subversion de la última versión estable, o "trunk," si usas `/trunk/` como
estable.

    Ten en cuenta que el `readme.txt` de la tag stabe es la que se considera que está definida para el plugin, así que
si el archivo `/trunk/readme.txt` dice que la tag estable es la `4.3`, entonces es `/tags/4.3/readme.txt` el que se usará
para mostrar a información del plugin.  En esta situación, lo único a considerar del `readme.txt` del trunk
es lo que apunta a la tag stable.  Por tanto, si desarrollas en trunk, puedes actualizar el `readme.txt` de trunk para reflejar cambios
en tu versión en desarrollo, sin mostrar incorrectamente esa información sobre la verión estable actual, que carece de esos cambios, siempre
que el `readme.txt` de trunk apunte a la tag stable correcta.

    Si no se facilita una tag stable se asume que trunk es la stable, pero deberías especificar "trunk" si es ahí donde
pones tu versión estable, para eliminar cualquier duda.

== Installation ==

Esta sección describe cómo instalar el plugin y hacer que funcione.

P.ej.

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings->Plugin Name screen to configure the plugin
1. (Haz que tus instrucciones se ajusten al flujo de usuario deseado para la activación e instalación de tu plugin. Incluye cuanlquier paso necesario para que se entienda)


== Frequently Asked Questions ==

= Una duda que alguien podría tener =

Una respuesta a esa duda.

= What about foo bar? =

Respuesta al dilema foo bar.

== Screenshots ==

1. Esta descripción de la captura corresponde a screenshot-1.(png|jpg|jpeg|gif). Date cuenta de que la captura se obtiene del directorio
/assets o del directorio que contiene el readme.txt stable (tags o trunk). Las capturas en el directorio /assets tienen preferencia. Por
ejemplo, `/assets/screenshot-1.png` ganaría a `/tags/4.3/screenshot-1.png` (o jpg, jpeg, gif).
2. Esta es la descripción de la segunda captura

== Changelog ==

= 1.0 =
* Un cambio desde la versión anterior.
* Otro cambio.

= 0.5 =
* Lista versiones desde la más reciente hasta la más antigua al fondo.

== Upgrade Notice ==

= 1.0 =
Los avisos de actualizaciones describen el motivo por el que se debería actualizar.  No más de 300 caracteres.

= 0.5 =
Esta versión arregla un fallo de seguridad.  Actualiza inmediatamente.

== Arbitrary section ==

Puedes ofrecer secciones arbitrarias, en el mismo formato que las anteriores.  Esto se puede usar en plugins muy complicados
en los que se debe facilitar mucha información que no se ajuste a las categorías de "description" o
"installation."  Las secciones arbitrarias se mostrarán bajo las secciones por defecto explicas arriba.

== Un breve ejemplo de Markdown ==

Lista ordenada:

1. Una característica
1. Otra característica
1. Algo más del plugin

Lista desordenada:

* algo
* algo más
* otra cosa

Esto es un enlace a [WordPress](htssp://es.wordpress.org/ "Tu software favorito") y uno a [Documentación sobre la sintáxis de Markdown][sintáxis de markdown].
Los títulos son opcionales, naturalmente.

[sintáxis de markdown]: http://daringfireball.net/projects/markdown/syntax
            "Markdown es lo que usa el analizador para procesar la mayoría del archivo readme"

Markdown usa anotaciones estilo email para las citas:
> Asteriscos para *énfasis*. Dobles para **strong**.

`<?php code(); // va en comillas invertidas ?>`

Nota general:
Todos los textos debes facilitarlos en inglés, luego se podrán traducir en translate.wordpress.org de tu plugin
