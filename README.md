# Documentación del Código HTML del Portafolio

## Información General
Este código corresponde a una página de portafolio personal, creada en la clase **"HTML y CSS: Clases, Posicionamiento y Flexbox"** de la unidad **Principiante en Programación G8 - ONE**, parte de la certificación **ORACLE ONE G8 - INACAP**.

### Propósito del Proyecto
El objetivo del proyecto es presentar un portafolio personal que permita a la desarrolladora **Ana García** destacar su experiencia como desarrolladora Front-end con especialización en React, HTML y CSS. La página incluye enlaces a redes sociales, una imagen representativa de su trabajo, y un diseño visualmente atractivo y accesible.

---

## Estructura del Código

### Declaración Inicial
```html
<!DOCTYPE html>
<html lang="es-mx">
```
Se utiliza `<!DOCTYPE html>` para indicar que el documento está en HTML5, y el atributo `lang="es-mx"` establece el idioma principal como español (México).

---

### `<head>`
La sección `<head>` contiene configuraciones esenciales:

- **Codificación de Caracteres:**
  ```html
  <meta charset="UTF-8">
  ```
  Soporta caracteres especiales en español.

- **Compatibilidad:**
  ```html
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  ```
  Optimiza la compatibilidad con navegadores modernos.

- **Diseño Responsivo:**
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```
  Ajusta la página a distintos tamaños de pantalla.

- **Título de la Página:**
  ```html
  <title>Portafolio</title>
  ```

- **Estilos CSS Externos:**
  ```html
  <link rel="stylesheet" href="style.css">
  ```
  Enlaza la hoja de estilos `style.css`.

---

### `<body>`
El cuerpo de la página incluye las siguientes secciones principales:

#### `<header>`
Un contenedor reservado para futuros elementos del encabezado.

#### `<main>` 
La sección principal del contenido, organizada de la siguiente manera:

1. **Encabezado Principal (`<h1>`):**
   ```html
   Eleve tu negocio digital a otro nivel 
   <strong class="titulo-destaque">con un Front-end de calidad!</strong>
   ```
   Destaca el mensaje central con estilos visuales.

2. **Descripción (`<p>`):**
   ```html
   ¡Hola! Soy Ana García, desarrolladora Front-end con especialización en React, HTML y CSS. Ayudo a pequeños negocios y diseñadores a llevar a cabo buenas ideas. ¿Hablamos?
   ```

3. **Enlaces a Redes Sociales:**
   ```html
   <a class="presentacion__enlaces__link" href="https://instagram.com/">Instagram</a>
   <a class="presentacion__enlaces__link" href="https://github.com/">GitHub</a>
   ```

4. **Imagen Representativa (`<img>`):**
   ```html
   <img src="Imagem.png" alt="Foto de Ana García desarrolando un proyecto">
   ```

#### `<footer>`
Un contenedor vacío reservado para futuros elementos del pie de página.

---

## Diseño y Estilo

El diseño se gestiona mediante el archivo `style.css`, que incluye:

1. **Colores y Tipografía:**
   - Fondo oscuro (`#000000`) con texto claro (`#F6F6F6`).
   - Fuentes: `'Krona One'` y `'Montserrat'`, importadas desde Google Fonts.

2. **Estilo Responsivo:**
   - Diseño flexible con `flexbox`.
   - Ajustes automáticos para tamaños de pantalla.

3. **Enlaces y Botones:**
   - Estilos interactivos: cambio de color y elevación en hover.
   - Diseño visual moderno con bordes redondeados.

---

## Notas Importantes
1. **Accesibilidad:**
   - Uso del atributo `alt` en las imágenes.
   - Contraste adecuado entre texto y fondo.

2. **Extensibilidad:**
   - Secciones `<header>` y `<footer>` listas para ser ampliadas.

3. **Compatibilidad:**
   - Uso de metaetiquetas para garantizar funcionalidad en navegadores modernos.

---

## Requisitos Técnicos
1. **Archivo CSS Externo:** El archivo `style.css` debe estar ubicado en el mismo directorio que `index.html`.
2. **Imagen Representativa:** `Imagem.png` debe estar en el directorio raíz o se debe ajustar su ruta.

---

## Mejoras Futuras
1. **Contenido Adicional:**
   - Agregar secciones como `<nav>` para navegación o `<section>` para proyectos destacados.

2. **Favicon:**
   - Incluir un favicon en la sección `<head>`.

3. **Soporte Multilingüe:**
   - Preparar la página para varios idiomas.

---

## Enlaces Relacionados
- [Instagram](https://instagram.com/)
- [GitHub](https://github.com/)
