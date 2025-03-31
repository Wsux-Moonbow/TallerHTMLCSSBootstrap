# TallerHTMLCSSBootstrap

Cristian Camilo Cortes Moreno - 202011908

Esta página WEB se ha diseñado usando recursos de Flaticon.com

## Descripción

Esta es la primera página web que he desarrollado como parte del taller del curso de Desarrollo de Software en Equipos en la Universidad de los Andes. El sitio tiene como objetivo presentar información histórica sobre armas de la Segunda Guerra Mundial, combinando texto e imágenes a través de tarjetas (cards) estilizadas y un formulario de suscripción. Su diseño es responsivo y se adaptará a distintos tamaños de pantalla.

## Tecnologías Utilizadas

### HTML
- Estructura básica con `<!DOCTYPE html>`, `<html>`, `<head>` y `<body>`.
- Uso de etiquetas semánticas y de contenido: `<div>`, `<header>`, `<footer>`, `<h1>` a `<h6>`, `<p>`, `<img>`, `<ul>`, `<li>`, `<form>`, `<label>`, `<input>`.
- Atributos importantes como `alt` en las imágenes y `meta` para definir codificación y viewport.

### CSS
- Aplicación de estilos mediante selectores de clase, con propiedades como `background-color`, `margin`, `padding`, `font-size` y `font-family`.
- Uso de `@font-face` para incorporar fuentes personalizadas (por ejemplo, _romanAntique_, _WarisOver_ y _PressStyleLarge_).
- Empleo de la función `clamp()` para obtener tipografías fluidas que se adaptan al tamaño del viewport.

### Bootstrap
- Uso del sistema de rejilla (grid) a través de clases como `container-fluid`, `container`, `row`, `col-md-10` y `offset-md-1` para crear un diseño responsivo.
- Implementación de componentes como tarjetas (cards) y formularios, aprovechando las clases predefinidas de Bootstrap.
- Utilización de clases de espaciado (por ejemplo, `mb-4`, `my-5`) para controlar márgenes y separar elementos visualmente.

## Estructura General de la Página

- **Header:** Contiene el logotipo y el título principal.
- **Contenido Principal:** 
  - Una sección introductoría con un mensaje histórico y reflexivo.
  - Tarjetas (cards) que muestran información relevante y detallada sobre armas, acompañadas de imágenes y listados de datos técnicos/históricos.
- **Formulario de Suscripción:** Se incluye un formulario para que el usuario ingrese su nombre y correo electrónico y se suscriba a las noticias.
- **Footer:** Muestra información del autor y enlaces relevantes (por ejemplo, al repositorio de GitHub).

## Conceptos Básicos Aprendidos

- **HTML Básico:** Estructuración de documentos, uso de etiquetas semánticas y atributos esenciales.
- **CSS Básico:** Aplicación de estilos, manejo de colores, márgenes y padding, y definición de fuentes mediante `@font-face`.
- **Bootstrap:** Creación de diseños responsivos utilizando el sistema de rejilla, implementación de componentes predefinidos como cards y formularios, y uso de clases utilitarias para espaciado.
- **Diseño Responsivo:** Empleo de unidades relativas y funciones modernas como `clamp()` para lograr que la tipografía y el diseño se adapten a diferentes tamaños de pantalla.
- **Buenas Prácticas:** Separación de código en HTML, CSS y uso de recursos externos, lo que mejora la mantenibilidad y escalabilidad del proyecto.

Esta documentación resume los aspectos esenciales de la primera página web desarrollada para este taller, demostrando la integración de HTML, CSS y Bootstrap para crear un sitio web funcional y visualmente atractivo.
