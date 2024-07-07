```
            //
           _    _            _                      _ 
          / \  | | __ _  ___| |__  _ __ __ _       / |
         / _ \ | |/ _` |/ _ \ '_ \| '__/ _` |      | |
        / ___ \| | (_| |  __/ |_) | | | (_| |      | |
       /_/   \_\_|\__, |\___|_.__/|_|  \__,_|      |_|
                  |___/                               
```
# Idea
Si bien hay muchos buenos apuntes por ahí. La idea es que en este repo haya un apunte _vivo_ uno que se pueda
ir curando y modificando junto con las guías de nuevos cuatrimestres.
Un apunte con sección _ejercicios de parciales_ que vaya creciendo cuatrimestre a cuatrimestre,
*curados y escritos por el alumnado de álgebra 1*.


¡Esto está para que *cualquier individuo con ganas de contribuir pueda hacerlo*!


# Algebra 1
Algunos ejercicio de álgebra 1 en LaTeX
Están bien los ejercicios?... eso no lo sé, _it's part of the fun_

# Estructura del repo
- [Videos introductorios al repo](https://www.youtube.com/watch?v=8s2Z8MvKbRM&list=PLTgIZ7PjigTILwmmcQqfCDazzR8bo8N6d&pp=gAQBiAQB): 
- En las carpetas de `i-guia`:
    - Hay más carpetas con los códigos de ejercicios, ejercicios-extra y teoría. El archivo que se compila `i-sol.tex` también. 
    que quede lo más organizado posible.

-   En la carpeta `macro`:
    - Ahí está el preambulo `preamble-general.tex` y algunos comandos redefinios para que sea más amena
    la lectura del código en `definiciones.tex`.
    - Recientemente puse el índice, y el encabezado y pie de página.


# Contribuir
Si querés contribuir *no hace falta codear*, podés marcar algún error que pueda haber en un ejercicio por ejemplo. Ahí
podés comentarnos por el Telegram o mail así lo solucionamos y aumentamos la calidad del trabajo.
La gente que contribuya tendrá su nombre (lugar a determinar) en el `.pdf` como corresponde!

*Para contribuir al código directamente debés:*|
- Tener instalado Git
- Tener instalado LaTeX
- Tener cuenta de GitHub
- Pedir en Telegram que te agreguen al repo con permiso para hacer modificaciones



# Compilar
Para compilar los archivos de LaTeX una vez que fueron modificados:
- Con la terminal, entrar a la carpeta de la guía
- Ejecutar para compilar la guía 5:
``` pdflatex 5-sol.tex ```

### Desde la terminal:
Ej, guía 5:
```bash
cd 5-guia/
pdflatex 5-sol.tex
```

Podés usar el código como quieras siguiendo según [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/)

¡Una estrellita al repo es siempre bienvenida!
(^_^)/


_"Un Apunte para gobernarlos a todos, un Apunte para encontrarlos, Un Apunte para atraerlos a todos y promocionar inclusive en las tinieblas"_
