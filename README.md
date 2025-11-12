# AISX_0373_A00_IntroGithub
## Primer repositorio del curso 2025-26 de ASIX1.
### Es mi primera toma de contacto con GitHub.
#### Soy Daniel Vega Macias

------------------------------------------------------------------------

## Markdown

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
    * Elemento desordenado 1.2
    * Elemento desordenado 2.2

[link](https://markdown.es/ "Manual oficial markdown")

![alt text](./fali.jpg "Imagen Fali")

| Jugador | dorsal | nombre |
|-------|:----------:|:------------------|
| 77 | Cadiz | Fali |
| 33 | Levante | Etta Eyong |
| 20 | Ponfe | JH |
--------------------------------------------------------------------------------------------------------------

#### GIT

###### Comandos GIT

1. git init → iniciar
2. git add → añadir
3. git commit -m (nombre para el commit) → hacer commit
4. git push origin main → subir commit a GitHub

--------------------------------------------------------------------------------------------------------------
#### GitHub

GitHub es una plataforma basada en la nube que permite alojar repositorios Git y colaborar con otros desarrolladores.

1. Conceptos clave
Repositorio (repo): Lugar donde se guarda el código.
Commit: Registro de un cambio en el código.
Branch (rama): Versión paralela del proyecto.

2. Flujo de trabajo básico
Crear o clonar un repositorio.
Crear una rama para trabajar.
Hacer cambios y confirmarlos (commit).
Subir los cambios (push).
Crear un Pull Request para fusionar en la rama principal.

--------------------------------------------------------------------------------------------------------------

# Introducción a HTML

## ¿Qué es HTML?

HTML (HyperText Markup Language):
Lenguaje estándar para crear páginas web.
Es lo más importante de Internet: sin HTML no se vería nada en el navegador.

Etiquetas básicas de HTML:

1. html ... /html → Documento completo

2. head ... /head → Información de la página (metadatos, título, enlaces a CSS/JS)

3. body ... /body → Contenido visible en la web

4. p → Párrafo

5. h1 ... h6 → Encabezados (del más grande al más pequeño)

**HTML (HyperText Markup Language)** es el lenguaje estándar utilizado para crear páginas web.  
Es la base de todo Internet: sin HTML, los navegadores no podrían mostrar ningún contenido.

## Funciones de HTML

- Define la **estructura** y el **contenido** de una página web.  
  Ejemplos: texto, imágenes, listas, enlaces, párrafos, títulos, etc.
- **No define la apariencia** del sitio (eso se hace con **CSS**).
- Es un lenguaje **lógico, estructurado y fácil de entender**.

## Etiquetas Básicas de HTML

| Etiqueta | Descripción |
|-----------|--------------|
| `<html> ... </html>` | Define el documento completo |
| `<head> ... </head>` | Contiene información de la página (metadatos, título, enlaces a CSS/JS) |
| `<body> ... </body>` | Incluye el contenido visible en la web |
| `<p>` | Define un párrafo |
| `<h1>` ... `<h6>` | Define encabezados (del más grande al más pequeño) |

## Atributos en HTML

Los **atributos** son información adicional que se agrega a los elementos HTML.  
No son visibles en la página, pero modifican su comportamiento o estilo.

**Estructura:**
```html
<elemento atributo="valor">Contenido</elemento>
