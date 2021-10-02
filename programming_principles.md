# Curso de programación

Aprenderás a programar a un nivel básico con independencia del lenguaje de
programación. Estos lenguajes no son más que unas simples herramientas con las
que podemos decirle al ordenador (computadora) que realice ciertas tareas.

*¿Qué tipo de tareas puede realizar un computador?*<br>
Generalmente hablando, "cualquier" tarea repetitiva y aburrida, puede ser
transformada en un algoritmo que una computadora puede realizar.

Al final de este documento hay una sección de [recursos](#Recursos) para tener
acceso a otras guías, problemas de programación, ideas para proyectos
personales... etc.

**Nota:** Los recursos puestos en la sección mencionada pueden estar en
castellano o en inglés, siendo en inglés la más predominante por lo que es más
que recomendable que sepas inglés a un buen nivel en los tres campos: lectura,
escucha y escritura o habla.
<br>
<br>

Soy un gran partidiario de la experiencia y de que cada individuo tiene la
capacidad para realizar cualquier cosa, ya sea aprender a programar, ser médico,
matemático, linguista, artista y demás ramas del conocimiento humano. Por lo
que no tengas miedo de enfrentarte a un problema por tus faltas de
conocimiento, simplemente lánzate, el simple hecho de hacerlo te acerca un
paso más a tu objetivo.

<p align="center"><i><b>Ante la adversidad es como evolucionamos</b></i></p>

---------------------------------------------------------------

## Índice

1. [Programación básica](#1-Programación-básica)
    - Entorno de desarrollo integrado (IDE)
    - Variables
    - Control del flujo
      - Condicionales
      - Bucles
    - Funciones
    - Estructuras de datos básicas
    - Analisis de la eficiencia de un algoritmo
    - Diseño de algoritmos
      - Iterativos
      - Recursivos
      - Divide y vencerás
      - Vuelta atrás
2. [Programación avanzada](#2-Programación-avanzada)
    - Estructuras de datos avanzadas
    - Paradigmas de programación
3. [Control de versiones](#3-Control-de-versiones)
4. [Open Source y licencias](#4-Open-Source-y-licencias)
5. [Ingeniería del Software](#5-Ingeniería-del-Software)
    - Metodologías de trabajo
    - Patrones de diseño comunes con paradigma OOP
6. [Sistemas de bases de datos](#6-Sistemas-de-bases-de-datos)
    - Relacionales
    - No relacionales
7. [Redes de comunicación](#7-Redes-de-comunicación)
8. [Sistemas Operativos](#8-Sistemas-Operativos)
9. [Usabilidad y diseño de sistemas interactivos](#9-Usabilidad-y-diseño-de-sistemas-interactivos)
10. [Frameworks o librerías famosas (opcional)](#10-Frameworks-o-librerías-famosas)

## 1. Programación básica

Una de las grandes revoluciones del siglo pasado fue la creación del [transitor](https://es.wikipedia.org/wiki/Transistor). Estos dispositivos actúan de una manera
parecida a los [relés](https://es.wikipedia.org/wiki/Rel%C3%A9), y permiten o
prohíben el paso de corriente electrica entre otras cosas.<br>
Estos componentes electrónicos son el corazón de toda la era digital que
tenemos hoy en día, se pueden hacer muy pequeños y se puede organizar de cierta
forma para crear otros componentes más complejos y todo ello haciendo uso de
solamente de dejar pasar o no corriente eléctrica. De tener dos opciones. El
sistema binario.

Generalmente, representamos el sistema binario usando el siguiente conjunto:
$$
C = \{0, 1\}
$$

Dentro de este curso no profundizaremos en el [sistema binario](https://es.wikipedia.org/wiki/Sistema_binario) aunque es importante comprender y entender cómo se usa, las
distintas representaciones que tiene y las distintas operaciones que se
pueden realizar con él.
<br>
<br>

Ahora avanzaremos uno pasos adelante y responderemos a una duda bastante
importante:<br>
*¿Cómo hacen los computadores para entender el código que les vamos a dar?*<br>
La respuesta es bastante sencilla, *no lo entienden*, los computadores solo
entienden binario ya que han sido creados sobre componentes que solo usan
binario, por eso debemos de traducirles el código a lo que se denomina [lenguaje máquina](https://es.wikipedia.org/wiki/Lenguaje_de_m%C3%A1quina).

La traducción es un proceso llamado [compilación](https://es.wikipedia.org/wiki/Compilador)
y casi todos los lenguajes de programación deben pasar por este proceso.
Existe un método equivalente pero con distintas caracteristicas denominado [interpretación](https://es.wikipedia.org/wiki/Int%C3%A9rprete_(inform%C3%A1tica)).
<br>
<br>


### Entorno de desarrollo integrado (IDE)

A priori podemos escribir código en cualquier editor de texto, aunque no es 
eficiente y es un método con el que es fácil cometer errores. Por eso se crean
editores de texto especializados con herramientas como:
- Autocompletar código
- Debugger
- Simplificación del proceso de ejecución
- Analizador sintáctico
- Localizador de referencias
- Control de versiones simplificado
- Coloreado de palabras clave

Y muchas más funcionalidades. Por el momento no te sientas agobiado si no
entiendes la importancia de esos editores especiales, a medida que vayas
avanzando durante el curso podrás identificar todos los elementos de la lista y
su importancia.

Hay una infinidad de IDE pero el que usaremos será [Visual Studio Code](https://code.visualstudio.com/) un editor diseñado por Microsoft al cual se le puede
extender sus funcionalidades por medio de plug-ins.

## Recursos

Ejercicios y retos:
1. https://leetcode.com/ (EN)(Te plantean problemas que has de resolver en el
  lenguaje que más quieras)
2. https://www.aceptaelreto.com/ (ES)(Mismo concepto que leetcode pero sin
  ayuda de cómo resolver el problema y sin comparaciones de código con otros
  usuarios)
3. https://www.hackerrank.com/ (EN)
4. https://www.topcoder.com/ (EN)
5. https://www.spoj.com/ (EN)(Mismo concepto que el punto 2)
6. https://www.codewars.com/ (EN)(La web tarda en cargar)

Material audiovisual:
1. Canal de youtube: [BettaTech](https://www.youtube.com/channel/UCSf6S_PAhXsqGMTPDiKgdRg) (ES)

Cursos o libros:
1. De parte de Ebook foundation: [Free Programming Book](https://github.com/EbookFoundation/free-programming-books)
2. Cursos gratis de google: [Digital Garage](https://learndigital.withgoogle.com/digitalgarage/courses?category=data_tech)
3. Cursos gratis del MIT: [MIT OpenCourseWare](https://ocw.mit.edu/courses/find-by-topic/#cat=engineering&subcat=computerscience)
3. Libros gratis que resumen ciertas tecnologías: [Succinctly Free Books](https://www.syncfusion.com/succinctly-free-ebooks)

Misceláneo:
- Canales de youtube
  1. [LiveOverflow](https://www.youtube.com/c/LiveOverflow) (seguridad informática)
  2. [David Bombal](https://www.youtube.com/c/DavidBombal) (seguridad informática)
  3. [Blackthornprod](https://www.youtube.com/c/Blackthornprod/videos) (Videojuegos)
  4. [Brackeys](https://www.youtube.com/c/Brackeys) (Videojuegos)
  5. [Ben Eater](https://www.youtube.com/c/BenEater) (Hardware)
  6. [DevEd](https://www.youtube.com/c/DevEd/videos) (Páginas web)
  7. [CrashCourses](https://www.youtube.com/user/crashcourse) (Cursos enteros sobre cualquier cosa)
  8. [Dot CSV](https://www.youtube.com/c/DotCSV) (Inteligencia Artifial)
