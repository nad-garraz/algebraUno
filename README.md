```
     //
    _    _            _                      _
   / \  | | __ _  ___| |__  _ __ __ _       / |
  / _ \ | |/ _` |/ _ \ '_ \| '__/ _` |      | |
 / ___ \| | (_| |  __/ |_) | | | (_| |      | |
/_/   \_\_|\__, |\___|_.__/|_|  \__,_|      |_|
           |___/
```

## Las guías resueltas:

En cada directorio `i-guia` vas a encontrar el archivo `i-sol.pdf` que no es otra cosa que la última actualización de la guía `i-ésima`. _Sin necesidad de compilar nada_.
Los archivos son largos como para andar scrolleando todo el tiempo, *usá* los `links`, que para algo los puse. Así que en el índice, pie de página y referencias podés hacer doble click para saltar
y algún que otro _easter egg_.

_¡Una estrellita 🌟 al repo es siempre bienvenida!_
`(^_^)/`


# Idea
Si bien hay muchos buenos apuntes por ahí. La idea es que en este repo haya un apunte _dinámico_, uno que se pueda
ir curando y modificando junto con las guías de nuevos cuatrimestres. Vas a tener que laburar!
Un apunte con sección _ejercicios de parciales_ que vaya creciendo y mejorando cuatrimestre a cuatrimestre,
_curados y escritos por el alumnado de álgebra 1_.

¡Esto está para que _cualquier individuo con ganas de contribuir pueda hacerlo_!

## Estructura del repo

- [Videos introductorios al repo y un poquito a LaTeX](https://www.youtube.com/watch?v=8s2Z8MvKbRM&list=PLTgIZ7PjigTILwmmcQqfCDazzR8bo8N6d&pp=gAQBiAQB):
- En los directorios `i-guia`:

  - `i-sol.pdf`: PDF con los ejercicios correspondientes a los temas de la guía _i-ésima_. El que seguramente estás buscando, a menos que quieras contribuir.
  - `i-sol.tex`: Archivo que se debe compilar para obtener el archivo `i-sol.pdf` que uno quiera ver. En este se inyecta todo el código que está en los directorios, `teoria-i`, `ejercicios-i`, `ejercicios-i-extra`
  - directorio `teoria-i`: Contiene a `teoria-i.tex`
  - directorio `ejercicios-i`: Contiene los ejercicios de la _i-ésima_ guía. Se nombran `ej-j-i.tex` con `j`, el número del ejercicio e `i` el de la guía.
  - directorio `ejercicios-i-extra`: Contiene los ejercicios extras, de clase y/o parciales de los temas de la _i-ésima_ guía. Se nombran `ej-extra-j-i.tex` con `j`, el número del ejercicio e `i` el de la guía.

- En la carpeta `macros`:
  - Ahí están los archivos necesarios para compilar los ejercicios.
    - `preamble-general.tex`: El preambulo con los paquetes necesarios para los comandos usados. -`indice.tex`: El índice, código para generar los links dentro del pdf y saltar directo a los ejercicios mejorando la navegación de los pdf.
    - `definiciones.tex`: Las definiciones, macros para que los comandos de LaTeX sean un poco más agradables y se pueda leer el código en leguaje _más natural_.
    - `encabezado-pie.tex`: Encabezado y pie de página, para darle un poco de 🌠bling-bling 🌠 al apunte y mejor navegación
    - `estructura-ejercicio.tex`: Donde se inyectan los ejercicios dándoloe la estructura que tiene cada PDF.

## Contribuir

Si querés contribuir _no hace falta codear ni saber LaTeX_, podés marcar algún error que pueda haber en un ejercicio por ejemplo. Ahí podés comentarnos por el [grupo de Telegram](https://t.me/+1znt2GV1i8cwMTNh) o mail así lo solucionamos y aumentamos la calidad del trabajo.
Si sabés un poco de LaTeX, ya vas a estar bien, porque hay muchísimos ejercicios con los comandos para que copies y pegues.

_Para contribuir al código directamente tenés que:_

- Tener instalado Git
- Tener instalado LaTeX
- Tener cuenta de GitHub
- Metete en el [grupo de Telegram](https://t.me/+1znt2GV1i8cwMTNh) si necesitás ayuda con alguno de esos pasos. La idea es que te capacites para poder _vos también mantener el repo vivo y actualizado_.

## Compilar

Para compilar los archivos de LaTeX una vez que fueron modificados:

- Con la terminal, entrar a la carpeta de la guía que quieras compilar, por ejemplo la guía 5.

```bash
$ cd algebraUno/5-guia/
$ pdflatex 5-sol.tex
```

Eso debería actualizar el archivo `5-sol.pdf` con los cambios que hubieras realizado.
Luego tenés que hacer una pull request para actualizar el repositorio con tu aporte!

- Metete en el [grupo de Telegram](https://t.me/+1znt2GV1i8cwMTNh) si necesitás ayuda con alguno de esos pasos.
La idea es que te capacites para poder _vos también mantener el repo vivo y actualizado_, porque yo ya hice mi parte y me da paja mantener esto sin ayuda.

Podés usar el código como quieras siguiendo esta licencia: [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

_"Un Apunte para gobernarlos a todos, un Apunte para encontrarlos, Un Apunte para atraerlos a todos y hasta en la tinieblas promocionar"_

_¡Una estrellita 🌟 al repo es siempre bienvenida!_
`(^_^)/`
