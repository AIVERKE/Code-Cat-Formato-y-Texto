# **Estructura de la Clase – Sesión 1: Texto, Listas, Tablas y Símbolos en HTML**
---
## **1. Formato básico de texto**

Estas etiquetas se usan para dar estilo o resaltar partes de un texto.

| Etiqueta   | Significado / Uso                                                                          | Ejemplo                                                    |
| ---------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------- |
| `<b>`      | Pone el texto en **negrita** (solo estilo, no semántica).                                  | `<b>Importante</b>` → **Importante**                       |
| `<strong>` | Texto con **énfasis fuerte**, semánticamente importante. Similar a `<b>` pero con sentido. | `<strong>Atención</strong>` → **Atención**                 |
| `<i>`      | Texto en _cursiva_ (solo estilo, no semántica).                                            | `<i>Palabra en otro idioma</i>` → _Palabra en otro idioma_ |
| `<em>`     | Texto con _énfasis semántico_, recomendado para resaltar palabras.                         | `<em>Muy importante</em>` → _Muy importante_               |
| `<u>`      | Subraya el texto.                                                                          | `<u>Subrayado</u>` → Subrayado                             |
| `<small>`  | Texto en tamaño más pequeño.                                                               | `<small>Nota al pie</small>` → Nota al pie                 |
| `<mark>`   | Resalta el texto como si fuera un marcador.                                                | `<mark>Resaltado</mark>` → Resaltado                       |
| `<del>`    | Texto tachado (para indicar eliminación).                                                  | `<del>No usar</del>` → ~~No usar~~                         |
| `<ins>`    | Texto subrayado para indicar inserción/cambio.                                             | `<ins>Añadido</ins>` → Añadido                             |

---

## **2. Etiquetas semánticas de texto**

Aportan **significado adicional** al texto (más que apariencia).

|Etiqueta|Significado / Uso|Ejemplo|
|---|---|---|
|`<abbr>`|Abreviatura con su significado.|`<abbr title="HyperText Markup Language">HTML</abbr>` → HTML (al pasar el cursor aparece el significado).|
|`<address>`|Información de contacto (dirección, email, etc.).|`<address>Autor: Diego, correo: diego@mail.com</address>`|
|`<cite>`|Para citar títulos de obras (libros, películas, etc.).|`<cite>Don Quijote</cite>`|
|`<code>`|Fragmento de código de programación.|`<code>console.log("Hola")</code>`|
|`<q>`|Cita corta, genera comillas automáticas.|`<q>La práctica hace al maestro</q>` → “La práctica hace al maestro”|
|`<dfn>`|Define un término por primera vez.|`<dfn>API</dfn> es una interfaz de programación de aplicaciones.`|
|`<var>`|Representa una **variable** en fórmulas o código.|`La variable <var>x</var> representa el tiempo.`|

---

## **3. Listas ordenadas y desordenadas**

Para organizar información de forma jerárquica.

|Etiqueta|Significado / Uso|Ejemplo|
|---|---|---|
|`<ul>`|Lista **desordenada** (con viñetas).|`<ul><li>Pan</li><li>Leche</li></ul>`|
|`<ol>`|Lista **ordenada** (con números).|`<ol><li>Primero</li><li>Segundo</li></ol>`|
|`<li>`|Elemento dentro de una lista (`ul` u `ol`).|`<li>Elemento</li>`|
|`<dl>`|Lista de **definición** (término + definición).|`<dl><dt>HTML</dt><dd>Lenguaje de marcado</dd></dl>`|
|`<dd>`|La **definición** de un término en la lista de definición.|`HTML → Lenguaje de marcado`|

---

## **4. Tablas y sus componentes**

Para mostrar datos en forma de tabla organizada.

|Etiqueta|Significado / Uso|Ejemplo|
|---|---|---|
|`<table>`|Define una tabla.|`<table>...</table>`|
|`<caption>`|Título o leyenda de la tabla.|`<caption>Tabla de alumnos</caption>`|
|`<tr>`|Fila de la tabla.|`<tr>...</tr>`|
|`<th>`|Celda de encabezado (negrita y centrada).|`<th>Nombre</th>`|
|`<td>`|Celda normal (dato).|`<td>Diego</td>`|
|`<thead>`|Encabezado de la tabla (grupo de filas).|`<thead><tr><th>Nombre</th></tr></thead>`|
|`<tbody>`|Cuerpo principal de la tabla.|`<tbody><tr><td>Ana</td></tr></tbody>`|
|`<tfoot>`|Pie de tabla (resúmenes o totales).|`<tfoot><tr><td>Total</td></tr></tfoot>`|
|`<colgroup>`|Agrupa columnas para aplicar estilos.|`<colgroup><col span="2" style="background:yellow"></colgroup>`|

---

## **5. Entidades, símbolos y emojis**

Se usan para mostrar caracteres especiales o emojis que no están en el teclado.

|Tipo|Ejemplo|Resultado|
|---|---|---|
|Menor que|`&lt;`|`<`|
|Mayor que|`&gt;`|`>`|
|Ampersand|`&amp;`|`&`|
|Corazón|`&#9829;`|♥|
|Emoji|`&#128512;`|😀|

---

# **Estructura sugerida de la clase**

1. **Introducción (5 min)** → ¿Qué veremos hoy? Mostrar un ejemplo visual.
    
2. **Formato de texto (10 min)** → Explicación + práctica con frases.
    
3. **Semántica de texto (10 min)** → Explicación + mini-juego de etiquetas.
    
4. **Listas (5 min)** → Crear lista de favoritos (ordenada/desordenada).
    
5. **Tablas (10 min)** → Construir tabla de emojis favoritos.
    
6. **Entidades y emojis (5 min)** → Frases con símbolos y emojis.
    
7. **Cierre (5 min)** → Reto final: documento mini con todo lo aprendido.
    

---

