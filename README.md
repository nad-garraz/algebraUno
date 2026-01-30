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

En cada directorio `i-guia` vas a encontrar el archivo `i-sol.pdf` que no es otra cosa que la última actualización de la guía `i-ésima` y al final tenés ejerecicios sacados de parciales resueltos. _Sin necesidad de compilar nada_.
Los archivos son largos como para andar scrolleando todo el tiempo, *usá* los `links`, que para algo los puse.
Así que en el índice, pie de página y referencias podés hacer doble click para saltar y algún que otro _easter egg_.

- [Guía 1](https://github.com/nad-garraz/algebraUno/blob/main/1-guia/1-sol.pdf)
- [Guía 2](https://github.com/nad-garraz/algebraUno/blob/main/2-guia/2-sol.pdf)
- [Guía 3](https://github.com/nad-garraz/algebraUno/blob/main/3-guia/3-sol.pdf)
- [Guía 4](https://github.com/nad-garraz/algebraUno/blob/main/4-guia/4-sol.pdf)
- [Guía 5](https://github.com/nad-garraz/algebraUno/blob/main/5-guia/5-sol.pdf)
- [Guía 6](https://github.com/nad-garraz/algebraUno/blob/main/6-guia/6-sol.pdf)
- [Guía 7](https://github.com/nad-garraz/algebraUno/blob/main/7-guia/7-sol.pdf)

_¡Una estrellita 🌟 al repo es siempre bienvenida!_
`(^_^)/`
[Ni hablar de uno o más cafecitos ☕️☕️☕️](https://cafecito.app/nad-garraz)


# Idea
Si bien hay muchos buenos apuntes por ahí. La idea es que en este repo haya un apunte _dinámico_, uno que se pueda
ir curando y modificando junto con las guías de nuevos cuatrimestres. Vas a tener que laburar!
Un apunte con sección _ejercicios de parciales_ que vaya creciendo y mejorando cuatrimestre a cuatrimestre,
_curados y escritos por el alumnado de álgebra 1_.

¡Esto está para que _cualquier individuo con ganas de contribuir pueda hacerlo_!

## Estructura del repo

- [Videos introductorios al repo y un poquito a LaTeX (tengo que actualizar esto, igual sirve..._peropaja_)](https://www.youtube.com/watch?v=8s2Z8MvKbRM&list=PLTgIZ7PjigTILwmmcQqfCDazzR8bo8N6d&pp=gAQBiAQB):
- En los directorios `i-guia`:

  - `i-sol.pdf`: PDF con los ejercicios correspondientes a los temas de la guía _i-ésima_. El que seguramente estás buscando, a menos que quieras contribuir.
  - `i-sol.tex`: Archivo que se debe compilar para obtener el archivo `i-sol.pdf` que uno quiera ver. En este se inyecta todo el código que está en los directorios, `teoria-i`, `ejercicios-i`, `ejercicios-i-extra`
  - directorio `teoria-i`: Contiene a `teoria-i.tex`
  - directorio `ejercicios-i`: Contiene los ejercicios de la _i-ésima_ guía. Se nombran `ej-j-i.tex` con `j`, el número del ejercicio e `i` el de la guía.
  - directorio `ejercicios-i-extra`: Contiene los ejercicios de parciales de los temas de la _i-ésima_ guía. Se nombran `ej-extra-j-i.tex` con `j`, el número del ejercicio e `i` el de la guía.

- En la carpeta `macros`:
  - Ahí están los archivos necesarios para compilar los ejercicios.
    - `preamble-general.tex`: El preambulo con los paquetes necesarios para los comandos usados. -`indice.tex`: El índice, código para generar los links dentro del pdf y saltar directo a los ejercicios mejorando la navegación de los pdf.
    - `definiciones.tex`: Las definiciones, macros para que los comandos de LaTeX sean un poco más agradables y se pueda leer el código en leguaje _más natural_.
    - `encabezado-pie.tex`: Encabezado y pie de página, para darle un poco de 🌠bling-bling 🌠 al apunte y mejor navegación
    - `estructura-ejercicio.tex`: Donde se inyectan los ejercicios dándoloe la estructura que tiene cada PDF.
    - `...etc...`

## Contribuir

Para contribuir:

1 - Clonás el repo:
```
git clone https://github.com/nad-garraz/algebraUno 
```

2 - Creas una rama en la cual laburar, con un nombre descriptivo onda _"ej-10-guia-2"_ y la pusheas así
    los demás nos enteramos de la existencia de esa rama
```
git switch -c nombre-nueva-rama
git push origin nombre-nueva-rama
```

3 - Codeas en el archivo del ejercicio que querés hacer, por ejemplo el "ej-10-2.tex". Agregas el archivo para que git lo sepa y
    commiteas los cambios con un comentario descriptivo, "Agrego ej-10-2.tex inciso a y b"
```
git add ej-10-2.tex 
git commit -m "Comentario descriptivo sobre lo que hiciste"
```

4 - Si ya terminaste y querés subir los cambios a github vas a primero hacer un pull, 
    por si alguien cambió algo mientras laburabas en tu rama. Luego vas a hacer un push
```
git pull
git push origin nombre-nueva-rama
```
5 - Los cambios deberían aparecer en github, EN TU RAMA. Para fusionar vas a hacer una PULL REQUEST
    desde la página. Cuando estés ahí vas a tener que esperar el visto bueno para la fusión y luego 
    se mergea y listo. La rama nombre-nueva-rama va desaparecer.

6 - Si en tu repositorio local todavía ves la rama y la querés borrar:
```
git branch
git switch main
git branch -D nombre-nueva-rama
```

Si tenés preguntas sobre el workflow preguntá en el grupo de [Telegram](https://t.me/+1znt2GV1i8cwMTNh)

Si querés contribuir _no hace falta codear ni saber LaTeX_, podés marcar algún error que pueda haber en un ejercicio por ejemplo.
[Y también un feca que si no me duermo `(-o-)zzZ☽ ` ☕️☕️☕️ `(ﾟ◇ﾟ；)ノﾞ`](https://cafecito.app/nad-garraz)

Podés usar el código como quieras siguiendo esta licencia: [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

_"Un Apunte para gobernarlos a todos, un Apunte para encontrarlos, Un Apunte para atraerlos a todos y en la tinieblas atraparlos"_

_¡Una estrellita 🌟 al repo es siempre bienvenida!_
`(^_^)/`
