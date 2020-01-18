## [Máster en Ingeniería Web por la Universidad Politécnica de Madrid (miw-upm)](http://miw.etsisi.upm.es)
## Plantilla para la práctica de Ecosistema (IWVG-ecosystem)
> Plantilla con Spring básico (API, test) 

## Ecosistema
* Java
* Maven
* Logs
* JUnit5
* IntelliJ
* GitHub
* Travis-CI
* Sonar Cloud
* Better Code Hub
* Spring
* Heroku
* OpenAPI-Swagger
1. Crear un proyecto

Crear un proyecto Maven llamado: iwvg-ecosystem-nombre-apellido, versión 1.0.0. Para ello se aporta zip de la plantilla. Añadir tipo de Licencia.

    Recordar editar el pom y cambiar el nombre del artefacto (artifactId).
    Recordar cambiar el nombre de la carpeta.
    Importarlo desde IntelliJ.
    Crear un repositorio en GitHub.

2. Preparar la gestión mediante Scrum

    Crear un proyecto de gestión en GitHub y prepararlo para la metodología de Scrum (columnas, etiquetas, hitos...).

3. Sprint 1. Preparación del ecosystema

Se crearán las siguientes 4 historias (Issues) pero se trabajarán en las ramas develop & master.

    one Integración continua con Travis-CI. Incluir Badge en README con link a la cuenta de Travis-CI.
    two Análisis del código con Sonarcloud. Incluir Badge en README con link a la cuenta de Sonar.
    three Análisis del código con Better Code Hub. Incluir Badge en README.
    four Desplegar en Heroku. Incluir Badge en README con link a la página de Swagger-ui.html.

    one, two... representa el orden temporal de desarrollo de los issues.

4. Release

    Realizar la primera liberación del código (v.1.0.0-release)

5. Sprint 2. Preparación del software a desarrollar

Se crearán las siguientes 4 historias (Issues).

    Clases onePoint & fivePointTest.
    Clases twoUser & threeUserTest.
    Clases fourDecimalCollection & eightDecimalCollectionTest.
    Clases sixFraction & sevenFractionTest.

    one, two... representa el orden temporal de desarrollo de los issues. Cuando un issue se termine se debe incorporar a la rama develop. Las clases Point, User, DecimalCollection, Fraction se podrán copiar de las dadas en clase.

6. Release

    Realizar la segunda liberación del código (v.1.1.0-release)

7. Sprint 3. Preparación mejoras del software

Se crearán las siguientes 4 historias (Issues).

    Point: onemejora 1 y fourmejora 2.
    User: twomejora 1 y sevenmejora 2.
    DecimalCollection: threemejora 1 y ninemejora 2.
    Fraction: fivemejora 1, sixmejora 2 y eightmejora 3.

    one, two... representa el orden temporal de desarrollo de los issues. Cuando un issue se termine se debe incorporar a la rama develop.

Las posibles ampliaciones son libres, o podrían ser las siguientes:
   Point

    Aumentar a una tercera coordenada.
    Limitar los límites posibles: 0..100, -10..+10...
    Poder modificar las coordenadas.

   User

    Presentar el nombre en mayúsculas.
    Incluir métodos con otras formas de presentar el nombre completo.
    Permitir nombres compuestos, separados por blancos y controlar las mayúsculas y minúsculas.

   DecimalCollection

    Incluir métodos como menor, multiplicar, tamaño, media...

   Fraction

    Incluir métodos como isPropia, isImpropia. Las fracciones propias son aquellas cuyo numerador es menor que el denominador, y las fracciones impropias el resto.
    Incluir el método isEquivalente. Dos fracciones son equivalentes cuando el producto de extremos es igual al producto de medios.
    Incluir métodos para comparar fracciones: mayor, menor.
    Incluir métodos para sumar, restar, multiplicar o dividir fracciones.

8. Release

    Realizar la tercera liberación del código (v.1.2.0-release)

9. Bug

    Suponer que la mejora 3 de la clase Fraction no es buena y se debe proceder a eliminarla. Realizar la cuarta liberación del código (v.1.2.1-release).
