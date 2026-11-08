---
name: Vínculos Eternos
description: Fotografía encapsulada. La chispa que nos une.
colors:
  rosa-vinculo: "#825050"
  conexion: "#913e3e"
  recuerdo: "#3e1e1e"
  aura: "#f5d5d2"
  destello: "#f8efe8"
  papel: "#fdf8f3"
  linea: "#e9d6cf"
  rosa-claro: "#a46f6e"
  rosa-texto: "#8c5857"
  muted: "#7a5c5a"
typography:
  display:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(2.2rem, 5vw, 3.7rem)"
    fontWeight: 800
    lineHeight: 1.08
    letterSpacing: "-0.015em"
  headline:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(1.9rem, 4.4vw, 2.9rem)"
    fontWeight: 800
    lineHeight: 1.08
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 700
    lineHeight: 1.08
  voice:
    fontFamily: "ZT Otez, Georgia, Times New Roman, serif"
    fontSize: "clamp(1.3rem, 2.6vw, 1.75rem)"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 600
    letterSpacing: "0.16em"
  lead:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 400
    lineHeight: 1.7
  small:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 400
  ui:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "0.92rem"
    fontWeight: 600
  caption:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "0.78rem"
    fontWeight: 400
  price:
    fontFamily: "Poppins, Segoe UI, system-ui, sans-serif"
    fontSize: "1.35rem"
    fontWeight: 800
  voice-sm:
    fontFamily: "ZT Otez, Georgia, Times New Roman, serif"
    fontSize: "1.2rem"
    fontWeight: 400
    lineHeight: 1.3
rounded:
  photo: "3px"
  focus: "4px"
  field: "12px"
  card: "20px"
  dialog: "24px"
  panel: "28px"
  pill: "999px"
spacing:
  gutter: "20px"
  section: "clamp(64px, 10vw, 110px)"
  container: "1140px"
components:
  button-primary:
    backgroundColor: "{colors.conexion}"
    textColor: "{colors.destello}"
    rounded: "{rounded.pill}"
    padding: "14px 26px"
  button-soft:
    backgroundColor: "{colors.aura}"
    textColor: "{colors.recuerdo}"
    rounded: "{rounded.pill}"
    padding: "14px 26px"
  button-light:
    backgroundColor: "{colors.destello}"
    textColor: "{colors.recuerdo}"
    rounded: "{rounded.pill}"
    padding: "14px 26px"
  card:
    backgroundColor: "{colors.papel}"
    rounded: "{rounded.card}"
  option-chip:
    backgroundColor: "{colors.destello}"
    textColor: "{colors.recuerdo}"
    rounded: "{rounded.field}"
    padding: "8px 14px"
  option-chip-selected:
    backgroundColor: "{colors.aura}"
    textColor: "{colors.recuerdo}"
  input:
    backgroundColor: "{colors.papel}"
    textColor: "{colors.recuerdo}"
    rounded: "{rounded.field}"
    padding: "11px 14px"
---

# Design System: Vínculos Eternos

## Overview

**Creative North Star: "La chispa que nos une"**

Vínculos Eternos se ve como un recuerdo que todavía brilla. La página es cálida, cercana y un poco juguetona. Kipi (Sparky de cariño), la estrellita con boina, es la chispa que une el imán a la refri y a las personas con sus momentos. El sistema mezcla dos voces: titulares en mayúsculas pesadas, que dicen las cosas claras, y una cursiva con carácter (ZT Otez), que dice lo que se siente.

La superficie es papel crema con bandas de color vino y rosa que marcan los momentos importantes. Las fotos reales van en marcos tipo polaroid, ligeramente ladeados, como pegadas a mano. El movimiento es juguetón pero con propósito. Kipi y pequeñas chispas aparecen cuando alguien hace algo que importa, como agregar un recuerdo al pedido o pedir una cita. Nunca como adorno de fondo.

**Key Characteristics:**
- Crema de fondo, bandas Recuerdo y Rosa Vínculo para lo emocional.
- Titulares Poppins ExtraBold en mayúsculas y cursiva ZT Otez como contrapunto.
- Fotos reales en marcos polaroid ladeados; Kipi como personaje, no como icono.
- Formas suaves y redondeadas: botones píldora, tarjetas de 20px.
- Chispas y gestos de Kipi como respuesta a acciones con significado.

## Colors

Paleta cálida de rosas empolvados y vinos sobre crema, sin grises fríos.

### Primary
- **Rosa Vínculo** (#825050): titulares, bandas de color (bodas, Kipi, eventos) y el precio en las tarjetas.
- **Conexión** (#913e3e): botones principales, acentos, enlaces y el punto culminante de la línea de tiempo.

### Secondary
- **Aura** (#f5d5d2): botones suaves, opción seleccionada, texto claro sobre fondos oscuros y avisos tranquilizadores.

### Neutral
- **Recuerdo** (#3e1e1e): texto principal, portada y cierre oscuros.
- **Destello** (#f8efe8): fondo de la página.
- **Papel** (#fdf8f3): tarjetas, campos y marcos polaroid.
- **Línea** (#e9d6cf): bordes y divisores.
- **Rosa Claro** (#a46f6e): bordes punteados, puntos de la línea de tiempo y detalles; nunca para texto pequeño.
- **Rosa Texto** (#8c5857): etiquetas pequeñas, subtítulos en cursiva y notas (5:1 sobre Destello).
- **Muted** (#7a5c5a): texto secundario y descripciones.

### Named Rules
**The Beret Rule.** Kipi nunca va sobre un fondo de su mismo color. Boina roja (cuerpo rosa) sobre Destello o Papel; boina rosa (cuerpo crema) sobre Recuerdo o Rosa Vínculo; nunca Kipi rosa sobre Aura.

**The Readable Tint Rule.** El texto de menos de 18px usa Rosa Texto, no Rosa Claro.

## Typography

**Display Font:** Poppins (with Segoe UI, system-ui)
**Body Font:** Poppins (with Segoe UI, system-ui)
**Voice Font:** ZT Otez Regular e Italic, autoalojada en woff2 (with Georgia)

**Character:** Poppins ExtraBold en mayúsculas dice las cosas con firmeza. ZT Otez en cursiva las dice con el corazón: subtítulos, citas y frases como "Minutos después".

### Hierarchy
- **Display** (800, clamp(2.2rem, 5vw, 3.7rem), 1.08, mayúsculas): solo el titular de la portada.
- **Headline** (800, clamp(1.9rem, 4.4vw, 2.9rem), 1.08, mayúsculas, Rosa Vínculo): títulos de sección.
- **Title** (700, 1.15rem): nombres de productos, pasos e ideas.
- **Voice** (ZT Otez italic, clamp(1.3rem, 2.6vw, 1.75rem), 1.3): subtítulos bajo los títulos, citas y reseñas.
- **Body** (400, 1rem, 1.7): texto corrido, con un máximo de 58–60ch.
- **Label** (600, 0.75rem, 0.16–0.22em, mayúsculas): categorías de tarjetas y la etiqueta del lema.
- **Lead** (400, 1.05rem): párrafo de introducción bajo los títulos.
- **UI** (600, 0.92rem): botones, pestañas y menú.
- **Small** (0.85rem): notas, ayudas, enlaces secundarios y texto de chips.
- **Caption** (0.78rem): detalles mínimos como "c/u" o la etiqueta de las fotos sin foto.
- **Price** (800, 1.35rem): precios en tarjetas y ventanas.

### Named Rules
**The Two Voices Rule.** Cada sección importante tiene una línea en Poppins que informa y una en ZT Otez que emociona. Nunca dos cursivas seguidas.

## Layout

Contenedor de 1140px con 20px de margen lateral. Las secciones respiran con clamp(64px, 10vw, 110px) arriba y abajo. Las rejillas de tarjetas van en 3 columnas, 2 por debajo de 960px y 1 por debajo de 600px. Las bandas a dos columnas (foto y texto) pasan a una columna por debajo de 780px. En celular, las fotos de la portada van arriba del titular. El sitio es una sola página con rutas por enlace (#inicio, #eventos, #catalogo, #ideas, #nosotros, #preguntas). Cada ruta muestra solo su contenido, y el cierre con logo va solo en Inicio.

## Elevation & Depth

La profundidad es cálida y suave. Se usan sombras largas y difusas, teñidas de Recuerdo, en elementos que se levantan: fotos polaroid, botones al pasar el mouse y ventanas. Las tarjetas en reposo son planas, con borde Línea.

### Shadow Vocabulary
- **Lift** (`box-shadow: 0 14px 30px -14px rgba(62, 30, 30, .45)`): botones y tarjetas al pasar el mouse.
- **Polaroid** (`box-shadow: 0 18px 36px -12px rgba(0, 0, 0, .5)`): fotos en marco papel sobre bandas oscuras.
- **Dialog** (`box-shadow: 0 30px 60px -20px rgba(0, 0, 0, .5)`): ventana de detalle y carrito.

### Named Rules
**The Flat-At-Rest Rule.** Las tarjetas no llevan sombra en reposo; la sombra aparece como respuesta (hover, ventana abierta).

## Shapes

Todo es suave y redondeado. Los botones, chips de días y el carrito flotante son píldoras (999px). Las tarjetas son de 20px, los paneles grandes (pedido, agenda) de 28px y los campos y opciones de 12px. La excepción a propósito son las fotos: marcos polaroid casi rectos (3px), con 8px de borde Papel y 30px abajo, rotados entre -7° y 8°.

## Components

### Buttons
- **Shape:** píldora (999px), 14px 26px, Poppins 600 a .95rem.
- **Primary:** Conexión con texto Destello. Es la acción principal: agregar, enviar, agendar.
- **Soft / Light:** Aura o Destello con texto Recuerdo. Se usan sobre bandas oscuras o para acciones secundarias. El botón de cita va a todo el ancho en Destello.
- **Line:** borde del color del texto, fondo transparente.
- **Hover / Focus:** sube 2px con sombra Lift; foco con contorno Conexión de 2px.

### Cards / Containers
- **Corner Style:** 20px.
- **Background:** Papel (en Ideas, Destello).
- **Border:** 1px Línea; en foco o resaltado, Conexión con halo.
- **Internal Padding:** 22px.

### Option chips
- **Style:** Destello con borde Línea de 1.5px, 12px de radio, nombre y precio en dos líneas.
- **State:** la opción seleccionada pasa a Aura con borde Rosa Vínculo.

### Inputs / Fields
- **Style:** fondo Papel, borde Línea, 12px de radio.
- **Error:** borde Conexión con halo suave y mensaje debajo en Conexión.

### Navigation
- **Style:** encabezado fijo en Destello translúcido con desenfoque. Los enlaces son Poppins 500 y la página activa va subrayada en Conexión. En celular, la fila se desliza de lado.

### Polaroid (signature)
Foto real con marco Papel y base ancha, ladeada y con sombra Polaroid. Es la forma en que la marca muestra lo que hace.

### Kipi (signature)
El personaje. Acompaña bandas y estados vacíos, y reacciona a las acciones importantes con un pequeño gesto y chispas. Siempre respeta The Beret Rule.

## Do's and Don'ts

### Do:
- **Do** usar fotos reales de clientes en marcos polaroid; los espacios sin foto dicen "próximamente" con Kipi.
- **Do** acompañar cada título con una línea en ZT Otez.
- **Do** reservar las chispas y los gestos de Kipi para acciones con significado (agregar al pedido, pedir cita, enviar).
- **Do** respetar `prefers-reduced-motion`: sin chispas ni rebotes, solo el cambio de estado.

### Don't:
- **Don't** usar grises fríos ni negro puro; el oscuro es Recuerdo (#3e1e1e).
- **Don't** poner Kipi de boina roja sobre Aura.
- **Don't** usar Rosa Claro para texto pequeño.
- **Don't** repetir "hecho a mano", "uno por uno" o "Costa Rica" como mensaje principal.
- **Don't** inventar fotos de producto ni reseñas.
