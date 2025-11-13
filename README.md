# AISX_0373_A00_IntroGithub
## Primer repositorio del curso 2025-26 de ASIX1.
### Es mi primera toma de contacto con GitHub.
#### Soy Daniel Vega Macias

------------------------------------------------------------------------

## Markdown

Markdown es un lenguaje que se usa para dar formato a texto de manera sencilla.

Esto está __negrita__  
Esto está en **negrita**

Esto está en _cursiva_  
Esto está en *cursiva*

**_TEXTO_**

1. Elemento 1
    * Elemento desordenado 1.1
    * Elemento desordenado 1.2
2. Elemento 2
    * Elemento desordenado 2.1
    * Elemento desordenado 2.2
3. Elemento 3
    * Elemento desordenado 3.1
    * Elemento desordenado 3.2

[link](https://markdown.es/ "Manual oficial markdown")

![alt text](./fali.jpg "Imagen Fali")

| Jugador | dorsal | nombre |
|-------|:----------:|:------------------|
| 77 | Cadiz | Fali |
| 33 | Levante | Etta Eyong |
| 20 | Ponfe | JH |

--------------------------------------------------------------------------------------------------------------

#### GIT

Git es un sistema de control de versiones distribuido. Esto significa que permite registrar los cambios de archivos y proyectos a lo largo del tiempo, de forma que puedas:

1. Volver a versiones anteriores si algo sale mal.
2. Trabajar en equipo sin perder cambios de otros.
3. Mantener un historial completo de todas las modificaciones.
4. Conceptos clave de Git
5. Repositorio (repo): Carpeta donde Git guarda todo el historial de un proyecto.
6. Commit: Guardar un cambio específico en el historial del proyecto.
7. Branch (rama): Línea paralela de desarrollo para trabajar sin afectar la versión principal.
8. Merge: Combinar los cambios de una rama con otra.
9. Push: Subir los cambios locales a un servidor remoto (como GitHub).
10. Pull: Traer los cambios de un repositorio remoto a tu máquina local.

###### Comandos GIT

1. git init → iniciar
2. git add → añadir
3. git commit -m "nombre para el commit" → hacer commit
4. git push origin main → subir commit a GitHub

--------------------------------------------------------------------------------------------------------------

#### GitHub

GitHub es una plataforma en la nube que se utiliza para almacenar y gestionar proyectos que usan Git. Es como un lugar online donde los desarrolladores pueden guardar su código, colaborar y compartir proyectos con otros.

1. **Conceptos clave**
    - **Repositorio (repo):** Lugar donde se guarda el código.
    - **Commit:** Registro de un cambio en el código.
    - **Branch (rama):** Versión paralela del proyecto.

2. **Flujo de trabajo básico**
    - Crear o clonar un repositorio.
    - Crear una rama para trabajar.
    - Hacer cambios y confirmarlos (commit).
    - Subir los cambios (push).
    - Crear un Pull Request para fusionar en la rama principal.

3. **Como crear un repo**
    - Entraremos en la web de GitHub
    - Completa los campos:

        1. Repository name: Nombre del repositorio (por ejemplo, mi-primer-repo).
        2. Description (opcional): Breve descripción del proyecto.
        3. Public/Private:
        4. Public: Cualquiera puede ver el repositorio.
        5. Private: Solo tú y colaboradores invitados pueden verlo.
    - Añadir Readme
    - Presionar el boton de "Create Repository"
    - Abrir la carpeta de Repositorios
    - Ejecutar el siguinete comando en el cmd con la ruta de la carpeta de los repositorios "git clone https://github.com/tu-usuario/mi-primer-repo.git"
    - Ya tendremos el repositorio creado

4. **Como hacer un commit**
    - Primeramente necesitamos hacer cambios en nuestro archivo
    - Entramos en la carpeta de nuestro reporsitorio
    - Ejecutamos los siguinetes comandos en orden
        1. git init
        2. git add
        3. git commit -m "nombre para el commit"
        4. git push origin main → subir commit a GitHub


--------------------------------------------------------------------------------------------------------------

# Introducción a HTML

## ¿Qué es HTML?

**HTML (HyperText Markup Language)** 

Es el lenguaje estándar utilizado para crear páginas web.  
Es la base de todo Internet: sin HTML, los navegadores no podrían mostrar ningún contenido.

### Etiquetas básicas de HTML:

1. `<html> ... </html>` → Documento completo  
2. `<head> ... </head>` → Información de la página (metadatos, título, enlaces a CSS/JS)  
3. `<body> ... </body>` → Contenido visible en la web  
4. `<p>` → Párrafo  
5. `<h1> ... <h6>` → Encabezados (del más grande al más pequeño)

## Funciones de HTML

- Define la **estructura** y el **contenido** de una página web.  
  Ejemplos: texto, imágenes, listas, enlaces, párrafos, títulos, etc.
- **No define la apariencia** del sitio (eso se hace con **CSS**).
- Es un lenguaje **lógico, estructurado y fácil de entender**.

## Formularios en HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASIX-0373-IntroHTML</title>
</head>
<body>
    <!--A continuación he puesto un encabezado -->
    <h1>Introducción HTML</h1>
    
    <p>Lorem</p><strong>Impus dolor</strong>

    <form action="URLdeDestino" method="POST">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required>
        <br>

        <label for="realname">Nombre real:</label>
        <input type="text" name="realname" id="realname">
        <input type="radio" name="carnet" value="carnetsi">
    </form>

    <table border="1">
        <thead>
            <tr>
                <td>ORDEN</td>
                <td>ATLETA</td>
                <td>TIEMPO</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Iker</td>
                <td>03:51:02</td>
            </tr>
            <tr>
                <td rowspan="2">2</td>
                <td colspan="2">Juan</td>
            </tr>
            <tr>
                <td>Dani</td>
                <td>03:51:02</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td>ORDEN</td>
                <td>ATLETA</td>
                <td>TIEMPO</td>
            </tr>
        </tfoot>
    </table>
    <caption>Tabla </caption>

    <form action="URLdeDestino.html" method="GET">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required>
        <br>

        <label for="realname">Nombre real:</label>
        <input type="text" name="realname" id="realname">
        <br>

        <fieldset>
            <legend>Carnet de conducir</legend>
            <label for="carnetsi">SI:</label>
            <input type="radio" name="carnet" value="carnetsi" id="carnetsi">
            <label for="carnetno">NO:</label>
            <input type="radio" name="carnet" value="carnetno" id="carnetno">
        </fieldset>

        <br>

        <fieldset>
            <legend>Gustos musicales</legend>
            <label for="pop">Pop:</label>
            <input type="checkbox" name="musica[]" value="pop" id="pop">
            <label for="heavy">Heavy:</label>
            <input type="checkbox" name="musica[]" value="heavy" id="heavy">
            <label for="pachanga">Pachanga:</label>
            <input type="checkbox" name="musica[]" value="pachanga" id="pachanga">
        </fieldset>

        <br>

        <label for="nacioniladidad">Nacionalidad:</label>
        <select name="Nacionalidad" id="nacioniladidad">
            <option value="españa">España</option>
            <option value="EEUU">EEUU</option>
            <option value="Brasil">Brasil</option>
            <option value="Francia">Francia</option>
        </select>

        <br>

        <label for="observaciones">Observaciones:</label><br>
        <textarea name="observaciones" id="observaciones" cols="25" rows="3" placeholder="Introduce aqui cualquier observacion que tengas"></textarea>

        <br>

        <button type="submit" name="Enviar" value="enviar">Enviar Datos</button>
    </form>
</body>
</html>
```