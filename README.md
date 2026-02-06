# Generador de Memes

Proyecto de un generador de memes web desarrollado como parte de la asignatura **Lenguajes de Marcas y Sistemas de Gestión de la Información**, correspondiente a la **Unidad Didáctica 03**, del ciclo formativo **C.F.G.S. Desarrollo de Aplicaciones Multiplataforma**.

## Descripción del proyecto

La aplicación consiste en un generador de memes funcional desarrollado mediante **HTML5, CSS3 y JavaScript**, que permite crear memes personalizados de forma interactiva. El proyecto cumple estrictamente con los requisitos funcionales, visuales y estructurales especificados en el enunciado de la práctica.

El generador permite seleccionar imágenes base, añadir textos personalizables en la parte superior e inferior, modificar tamaños y colores dinámicamente, y descargar el resultado final como imagen.

---

## Funcionalidades

### Visualización y configuración

* Panel de configuración del meme con controles intuitivos.
* Selección de imagen base mediante botón de carga de archivos.
* Visualización dinámica del meme en tiempo real conforme se realizan cambios.
* Imágenes aleatorias en la cabecera que cambian con cada recarga de página.

### Configuración de textos

* **Texto superior:**
  * Control deslizante para ajustar el tamaño (visualización dinámica en píxeles).
  * Selector de color con paleta completa.
  * Campo de entrada de texto.

* **Texto inferior:**
  * Control deslizante para ajustar el tamaño (visualización dinámica en píxeles).
  * Selector de color con paleta completa.
  * Campo de entrada de texto.

### Generación y descarga

* Generación del meme mediante Canvas API.
* Botón de descarga que guarda la imagen con el nombre "meme".
* Ventana de diálogo del sistema para elegir ubicación de guardado.

### Efectos visuales

* Efecto de escalado al pasar el ratón sobre el panel del meme generado.
* Efecto de escalado y cambio de color en el botón de descarga.
* Transiciones suaves en todos los elementos interactivos.

---

## Diseño y estilos

### Paleta de colores

* Fondo de página: `#f4f4f4`
* Texto general: `#333`
* Cabecera: `#222`
* Fondo sección configuración: `rgba(255, 255, 255, 0.9)`
* Sombra configuración: `#ffcc00`
* Botón descarga: `#ff6666`
* Botón descarga (hover): `#ff3333`
* Contenedor meme: degradado lineal de `#1f1f1f` a `#3a3a3a` a 145deg
* Texto del meme: blanco con sombra negra
* Pie de página: `#222`

### Tipografías

* Texto general: Arial, Helvetica, sans-serif
* Título cabecera: 'Luckiest Guy', cursive (2.2rem)
* Textos del meme: Impact, Arial Black, sans-serif (mayúsculas, peso 900, separación 2px)
* Pie de página: 'Luckiest Guy', cursive (0.8rem)
* Autor pie de página: 0.7rem con separación entre letras de 1px

### Estructura y espaciado

* Body con altura mínima del 100% del viewport.
* Uso de Flexbox para centrado horizontal y vertical.
* Bordes redondeados en sección de configuración (12px) y contenedor del meme (20px).
* Sombras aplicadas a elementos principales para profundidad visual.
* Transiciones suaves de 0.2-0.3 segundos en efectos visuales.

---

## Estructura del proyecto

```
Relación 03 UD 03 - Meme generator/
│── index.html
│── estilos.css
│── js/
│   └── javascript.js
└── imagenes/
    │── Awesome_Face.svg
    │── meme01.png
    │── meme02.png
    │── meme03.png
    │── meme04.png
    │── meme05.png
    │── meme06.png
    │── meme07.png
    │── meme08.png
    │── meme09.png
    └── meme10.png
```

* El archivo JavaScript se importa al final del cuerpo del documento HTML.
* El favicon utilizado corresponde al archivo `Awesome_Face.svg`.
* La estructura de carpetas debe respetarse estrictamente para el correcto funcionamiento.

---

## Resultados de Aprendizaje

Este proyecto está diseñado para contribuir al desarrollo del siguiente Resultado de Aprendizaje:

**RA 3.** Accede y manipula documentos web utilizando lenguajes de script de cliente.

### Criterios de Evaluación

* **CE3a:** Se han identificado y clasificado los lenguajes de script de cliente relacionados con la web y sus diferentes versiones y estándares.
* **CE3b:** Se ha identificado la sintaxis básica de los lenguajes de script de cliente.
* **CE3c:** Se han utilizado métodos para la selección y acceso de los diferentes elementos de un documento web.
* **CE3d:** Se han creado y modificado elementos de documentos web.
* **CE3e:** Se han eliminado elementos de documentos web.
* **CE3f:** Se han realizado modificaciones sobre los estilos de un documento web.

---

## Pie de página

El pie de página de la aplicación incluye:

* El texto: "Ejercicio 02 UD 03 - Lenguajes de marcas y sistemas de gestión de información".
* El nombre del autor junto con una declaración explícita de no haber utilizado herramientas de inteligencia artificial, tal como se indica en el enunciado de la práctica.

---

## Autor

Nelson Filipe Fardilha Karlsson  
1º Desarrollo de Aplicaciones Multiplataforma  
CPIFP Alan Turing
