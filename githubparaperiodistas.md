# Github para Periodistas

Meta de hoy: Aprenderás a usar Github para crear tu sitio web, para administrar desde tu computador tus proyectos de sitios web usando Github Desktop y a publicarlos en la web. También aprenderás el "lingo" de Github, necesario para usarlo. 

## 1. Creáte una cuenta en Github

Como ya dijimos [Github](https://www.github.com/) es el equivalente a un Dropbox para proyectos de código, datos y web. Permite mantener una versión de tu proyecto en tu computador (local) y otra en Github (en sus servidores: "la nube") para sincronizar cambios y mantener un registro de todos los cambios del proyecto. Así si te equivocas **puedes volver atrás**. Github está construido sobre [Git,](http://git-scm.com/) un sistema de control de versiones usado por programadores. Pero como es un poco complicado al principio, iremos por el camino fácil. 

Ok. Partamos.

1. Anda a [Github](https://www.github.com/) y crea tu nombre de usuario y pasword. Usa un nombre fácil de recordar, en minúsculas y sin espacios. Algo como juanperez. Nada de JuAn32pEreZ1. Prohibido.  

![Github homepage][1]

[1]: images/githubparaperiodistas/github-homepage.png

## 2. Creáte una cuenta en Github

Una vez registrado verás una pantalla igual o similar a la que se ve acá abajo. Busca el botón **"New repository"** y púlsalo para crear tu primer **repositorio**. Como dijimos, Github usa su propio *lingo* para nombrar las cosas. **Repositorio es igual a proyecto o a carpeta** (dentro de la cual tendrás los archivos y más carpetas de tu proyecto). Más adelante veremos como acceder y guardar otros proyectos, **clonándolos** (copiándolos) o haciendo un **fork** (algo así como tomar un pedazo de carne con un tenedor y llevarlo a nuestra plato). ¿Ya pulsaste en "New repository"?

![Github homepage][2]

[2]: images/githubparaperiodistas/github-homepage-1.png

## 3. Nombra tu repositorio

1. Nombra tu repositorio en minúsculas, sin espacios ni símbolos extraños. 
1. Incluye una descripción breve.
1. Define si el repositorio será público o privado.
1. Haz check en la caja de "Initialize this repository with a README"
1. Ahora podrás pulsar el botón “Create repository”.

![][3]

[3]: images/githubparaperiodistas/3-nombra-tu-repositorio.png

## ¡Voilá! Ya tienes tu primer repositorio. 

Lo vas a copiar a tu computador. Antes, anda a tu computador y lee el siguiente paso. 

![][4]

[4]: images/githubparaperiodistas/-iexcl-voil-aacute---ya-tienes-tu-primer-repositorio-.png

## 4. Crea una carpeta dónde guardarás todos tus repositorios

Realizar proyectos digitales requiere que seas ordenado y definas dónde guardarás este y otros proyectos. En mi caso, tengo una carpeta madre en la cual guardo todos los repositorios de clases y otros proyectos. La llamo para no olvidarme: **repos.** 

1. Crea tu carpeta **repos **así todos sabremos siempre dónde tienes tus repositorios y no lo olvidarás 
1. Cuando copies tu repositorio desde Github a tu computador, guarda el repositorio dentro de** repos.**

![][5]

[5]: images/githubparaperiodistas/4-crea-una-carpeta-d-oacute-nde-guardar-aacute-s-todos-tus-repositorios.png

## 5. Instalar Github Desktop en tu computador

¿Recuerdas cuando aprendiste a usar una aplicación de subida de archivos a servidor vía FTP como [File Zilla](https://filezilla-project.org/) para publicar tu sitio web? 

Bueno [Github Desktop](https://desktop.github.com/) sirve el mismo propósito en Github. Es la herramienta más rápida y fácil de comenzar a trabajar con repositorios para subirlos y bajarlos de los servidores de Github. 

1. Descarga [Github Desktop](https://desktop.github.com/) e instálalo. Muévelo a tu carpeta de Aplicaciones o Applications.
1. Haz click sobre el ícono de Github Desktop (el [octogato](https://octodex.github.com/)) y cuando se abra la aplicación, anda al menú superior izquierdo y pulsa sobre Preferencias o **Preferences**.

*Si tienes dudas, más adelante revisa las *[*guías de ayuda*](https://help.github.com/desktop/)* de la aplicación.*

![][6]

[6]: images/githubparaperiodistas/5-instalar-github-desktop-en-tu-computador.png

## 6. Agrega tu nombre de usuario y contraseña

1. En la ventana de **Preferences** selecciona **Accounts**.
1. Ingresa tu nombre de usuario en login y tu contraseña y haz click en **Sign In**.  
1. Ya estás adentro.

*Si tienes dudas, más adelante revisa las *[*guías de ayuda*](https://help.github.com/desktop/)* de la aplicación.*

![][7]

[7]: images/githubparaperiodistas/6-agrega-tu-nombre-de-usuario-y-contrase-ntilde-a.png

## 7. Clona (copia) tu repositorio a tu computador con Github Desktop

1. En la barra lateral izquierda de Github Desktop debieras ver en la lista de repositorios el repositorio que creaste. 
1. Si no lo ves, como es mi caso, sigue los pasos que se ven en la imagen de abajo y haz click en "Clone micasa"

*Si tienes dudas, más adelante revisa las *[*guías de ayuda*](https://help.github.com/desktop/)* de la aplicación.*

![][8]

[8]: images/githubparaperiodistas/7-clona--copia--tu-repositorio-a-tu-computador-con-github-desktop.png

## 8. Guarda el repositorio clonado en tu carpeta repos

Al **clonar **y guardar el repositorio en tu carpeta madre repos lo que estás haciendo es **bajar a tu computador una copia de tu repositorio** que estaba alojado en Github.com. 

![][9]

[9]: images/githubparaperiodistas/8-guarda-el-repositorio-clonado-en-tu-carpeta-repos.png

## 9. Tu primer repositorio y tu primer "Commit"

Git y Github llevan un registro de todos los cambios que haces en tu repositorio (editaste texto, agregaste una foto, etc). 

El objetivo es que tu puedas conocer e identificar todos los cambios importantes que hagas y tener a mano las distintas versiones. Algo así como llevar un registro de cambios de todos los borradores que escribes hasta que tu reportaje es publicado. 

Peeeero.. para que te sea fácil identificar los cambios debes contarle a Github que los hiciste y publicarlos. Esto se llama "Commit changes" ("cometer cambios" o hacer cambios). En corto "Commit". 

La regla de oro es que hagas commits muy frecuentemente y que expliques brevemente qué cambios hiciste. 

1. Back in the GitHub application, you should see your files in the left column. Make sure they are all checked. If so, enter a message in the text box called “commit summary”, something like “initial commit.” Then, click the commit button.

  Al clonar y guardar el repositorio en tu carpeta madre repos lo que estás haciendo es bajar a tu computador unacopia de tu repositorio alojada en Github.com. 

![][10]

[10]: images/githubparaperiodistas/9-tu-primer-repositorio-y-tu-primer--commit-.png

## 10. Crea un index.html, haz tu segundo "Commit" y súbelo a Github

Reitero: La regla de oro es que hagas commits muy frecuentemente y que expliques brevemente qué cambios hiciste. 

1. Abre tu repositorio en Sublime, escribe un mensaje tipo (el que quieras), guarda el archivo como index.html dentro del repositorio (carpeta).
1. Anda a Github Desktop y revisa la parte superior de Commited o Uncommited Changes. ¿Qué ves? 
1. Haz tu segundo commit. 

![][11]

[11]: images/githubparaperiodistas/10-crea-un-indexhtml--haz-tu-segundo--commit--y-s-uacute-belo-a-github.png

## 11. Resultado



![][12]

[12]: images/githubparaperiodistas/11-resultado.png

## Ejercicio 1: Crear tu primer sitio web personal en Github

1. Ir a [https://pages.github.com/](https://pages.github.com/) 
1. Haz click en [User or organization site](https://pages.github.com/#user-site)
1. Anda a [GitHub](https://github.com/) y [crea un nuevo repositorio](https://github.com/new) que se llame **username.github.io**, donde *username* es tu tu nombre de usuario en Github.

*Si tienes dudas más adelante revisa las *[*guías de ayuda*](https://help.github.com/desktop/)* de la aplicación.*

![][13]

[13]: images/githubparaperiodistas/ejercicio-1--crear-tu-primer-sitio-web-personal-en-github.png

## Clónalo a tu computador



![][14]

[14]: images/githubparaperiodistas/cl-oacute-nalo-a-tu-computador.png

## Debiera verse así

![][15]

[15]: images/githubparaperiodistas/debiera-verse-as-iacute-.png

## Ejercicio 2: Crea una página web y súbela a tu repositorio tunombredeusuario.github.io haciendo "Commit"

Incluye:

* Index.html
* Carpeta de archivos de imágenes y dentro, las imágenes.
* Carpeta de archivos de css y dentro, el o los archivos .css

****Ojo: ****Puedes usar una página web que ya hayas hecho.*

1. Copia los archivos (Index.html y las carpetas de imágenes y de css) y pégalos dentro de la carpeta o repositorio **tunombredeusuario.github.io **en tu computador.
1. Recuerda: la carpeta o repositorio **tunombredeusuario.github.com **está dentro de la carpeta madre **repos.**
1. Ahora abre en Github Desktop la carpeta o repositorio **tunombredeusuario.github.com **y haz un **commit** detallando los cambios.

## Resultado: Esta es la página del curso Craft 2 Español

[https://craft2es.github.io/](https://craft2es.github.io/) 

![][16]

[16]: images/githubparaperiodistas/resultado--esta-es-la-p-aacute-gina-del-curso-craft-2-espa-ntilde-ol.png

## Ejercicio 3

1. Haz click en [https://github.com/craft2es/githubparaperiodistas](https://github.com/craft2es/githubparaperiodistas)
1. Pulsa el botón verde **Clone or download** y luego el botón **Open in Desktop**
1. Guarda el repositorio en tu carpeta **repos**
1. Abre Github Desktop y verás que ahora en tu computador tienen una versión local del repositorio **githubparaperiodistas**.
1. Ahora anda a [https://github.com/craft2es/githubparaperiodistas](https://github.com/craft2es/githubparaperiodistas) y abre un Issue:
1. En título pon **Mi primer issue**. 
1. En el cuerpo del Issue incluye la dirección de tu cuenta de usuario en Github (**github.com/sunombredeusuario**), la dirección de tu sitio web en Github (**sunombredeusuario.github.io**) y escribe qué cosas del taller no te quedaron claras.
1. Pulsa el botón verde **Submit an issue**

## Lista de medios recomendados en Github

[https://github.com/showcases/open-journalism](https://github.com/showcases/open-journalism) 

**Desafío: **Haz **fork** de los repositorios que te gustan y ve qué pasa.