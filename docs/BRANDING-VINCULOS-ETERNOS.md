# Vínculos Eternos: kit de marca

Este archivo resume el branding y la información del negocio. Si abres un chat nuevo, pega este texto o adjunta este archivo junto con las imágenes que necesites.

## El negocio

- **Nombre:** Vínculos Eternos
- **Lema:** Fotografía encapsulada
- **Qué hace:** imanes personalizados con fotos, corazones de metal y calendarios, hechos a mano en Costa Rica.
- **Instagram:** @vinculos_eternos_cr
- **WhatsApp de pedidos:** 7182-1161 (+506 7182 1161)
- **Pago:** SINPE Móvil o transferencia. Se adelanta el 50 % para encargar (sin adelanto no se inicia); el resto al recibirlo o antes de enviarlo por Correos o Uber.
- **Envíos:** sin costo adicional en San Pedro y Barrio Dent. A otros lugares por Correos de Costa Rica o Uber, cobrando el envío.
- **Fotos:** claras y cuadradas (o que se puedan recortar en cuadrado), por WhatsApp al 7182-1161, de preferencia en HD o como archivo.
- **Tiempo de entrega:** alrededor de 1 semana
- **Dominio web:** todavía no hay

## Concepto

> Vivimos en una época donde acumulamos miles de fotografías, pero dedicamos cada vez menos tiempo a recordar.
> Vínculos Eternos existe para devolver presencia a los momentos que realmente importan.
> No vendemos imanes.
> Ayudamos a las personas a detenerse un momento y recordar lo que realmente importa.

## Catálogo con precios (carrito de la web)

| Producto | Opciones y precio |
|---|---|
| Fotos imantadas | Precio por imán según cantidad: 1 a 4 ₡1 700 · 5 a 9 ₡1 500 · 10 a 19 ₡1 300 · 20 o más ₡1 200 (la web calcula cualquier cantidad) |
| Empaque para regalo (producto aparte, fotos pendientes) | ₡1 000 |
| Dinofabeto | ₡22 500: 27 letras con dinosaurios y líneas de trazo (caligrafía, formar palabras) |
| Matesaurios | Números 0-9 ₡13 000 · 0-9 + 5 signos ₡18 000 · números dobles + signos ₡27 500 (este último si ya hacen operaciones de 2 dígitos o más) |
| Siluetas de metal | Corazón ₡10 000 · Gato ₡5 000. Se cuelgan como cuadro y llevan fotos imantadas encima |
| Lámpara de litofanía | Pequeña ₡25 000 · Mediana ₡30 000 · Grande ₡37 000. Forma personalizable |
| Calendario anual con música | ₡3 500 c/u; música opcional, ₡500 por canción. 100 % personalizable |
| Calendario mensual con música | ₡800 c/u (mínimo 4); música opcional, ₡500 por canción. 100 % personalizable |

**Cómo funciona la música:** cada canción va en un chip NFC pegado al calendario. Al acercar el celular, se abre la canción en Spotify o YouTube.

| Bodas y eventos | Se cotizan aparte con cada persona |

## Ideas e inspiración (sección aparte, sin repetir precios)

Mascotas (las que están y las que ya no) · Familia (abuelos, hijos, papás; lámpara para recordar a alguien) · Parejas (aniversario, San Valentín; sets corazón + 5 fotos, corazón + 10 fotos, 12 calendarios mensuales con fotos de la pareja) · Bebés y etapas (baby shower, primer año mes a mes, graduaciones) · Celebraciones (boda, cumpleaños, sesión de Navidad con fotógrafo).

## Tono de la marca

- Conceptos: "La chispa que nos une" (Kipi es la chispa que une el imán a la superficie y mantiene vivos los recuerdos) y "Recuerdos que brillan" (el destello de memoria que queremos mantener cerca).
- No repetir mucho "hecho a mano", "uno por uno" ni "Costa Rica": no es el mensaje principal.

## Colores

| Nombre | HEX | Uso |
|---|---|---|
| Rosa Vínculo | `#825050` | Titulares, bandas de color |
| Aura | `#F5D6D3` | Fondos suaves, texto claro sobre oscuro |
| Destello | `#F9F0E8` | Fondo principal (crema) |
| Recuerdo | `#3F1E1E` | Texto, fondos oscuros (vino) |
| Conexión | `#913F3F` | Botones y acentos |

Tinte de apoyo de la paleta: `#A46F6E` (rosa claro, para subtítulos).

## Tipografías

- **Títulos:** Poppins ExtraBold (Google Fonts), normalmente en mayúsculas.
- **Subtítulos:** ZT Otez Regular / Italic (archivos en `tipografia/`).
- **Texto:** Poppins Regular.

## Logo

Cuatro versiones en cada color (Aura, Destello, Recuerdo, Rosa Vínculo), todas PNG sin fondo, en `logos/`:

- `horizontal`: logo largo sin lema (el que va en el encabezado de la web)
- `horizontal-con-lema`: logo largo con "Fotografía encapsulada"
- `apilado`: en dos líneas, sin lema
- `apilado-con-lema`: en dos líneas, con lema

Usar el logo claro (Destello o Aura) sobre fondos oscuros y el oscuro (Recuerdo o Rosa Vínculo) sobre fondos claros.

## Kipi, el personaje

Estrella con boina. Ocho versiones PNG sin fondo en `kippi/`:

- **Boina roja (cuerpo rosa):** feliz, feliz con botas, con cámara, con cámara y botas
- **Boina rosa (cuerpo crema):** feliz, feliz con botas, con cámara, con cámara y botas

**Regla de contraste:** Kipi nunca va sobre un fondo de su mismo color.
- Fondos claros (Destello): Kipi de boina roja.
- Fondos oscuros (Recuerdo, Rosa Vínculo): Kipi de boina rosa.
- Evitar Kipi de boina roja sobre Aura (rosa sobre rosa).

Ver `referencias/manual-kippi-sobre-fondos.png`.

## Página web

- Código: repositorio GitHub `marcoaef7-pixel/cisco`, rama `claude/clever-galileo-4gxier`, archivo `index.html`.
- Páginas: Inicio, Catálogo (con detalle de cada producto y los 3 pasos para pedir), Ideas, Bodas y eventos (cómo funciona en 3 pasos y agenda), Sobre nosotros (historia, Kipi y reseñas) y Preguntas frecuentes con Contáctanos. Todo en `index.html` (#catalogo, #ideas, #eventos, #nosotros, #preguntas, #contacto).

## Pendiente

- Fotos para el catálogo (hoy solo hay de mascota, Dinofabeto y bodas)
- Foto de bodas en alta resolución
- Precios de eventos, metales, calendarios, Dinofabeto e imanes para marcas
- Cómo funciona la música de los calendarios

## Nuestra historia (aprobada)

> Hola, soy Mary, la creadora de Vínculos Eternos. Este sueño empezó en 2025, cuando me di cuenta de que tenía miles de fotos en el celular y casi nunca las veía. Las mejores, las de mi familia, mi abuela, mi gatito, estaban perdidas entre capturas de pantalla y memes.
>
> Así que hice mi primer imán. Lo pegué en la refri y cada vez que pasaba por ahí, me detenía un segundo a recordar. Ahí entendí que no estaba haciendo un imán: estaba devolviéndole presencia a un momento.
>
> El nombre salió de esa idea. Las personas que amamos, los momentos que nos marcaron, merecen quedarse cerca para siempre. Eso es un vínculo eterno.
>
> Hoy cada pieza la hago a mano una por una con mucho amor, pensando en la historia que hay detrás de cada foto.

## Reseñas reales

- **Karo** (WhatsApp): "Ya me llegaron los imanes, qué hermosos están de verdad, muchas gracias. Los subiré a Insta para que te sigan más personas. Muy bonito el emprendimiento."
- **María Paula** (WhatsApp): "Mil gracias, quedaron hermosos 😍😍"
- **Tami** (WhatsApp): "Hola, ya me llegó, muchísimas gracias, están hermosos."
- **Kattya** (WhatsApp): "Tengo un problema con el pedido... quedó hermoso y quiero más fotos. Muchísimas gracias, están hermosas. Voy a alistar otro pedido ❤️"
- **Dani** (Instagram, invitada de una boda, con foto del imán en su refri): "Y así se ven en casa. Excelente trabajo, como invitadas lo amamos."
- **Katia** (Instagram): "Hermoso trabajo, súper recomendados."

## Vista previa de la página

https://claude.ai/artifact/LG9r1mR81pFZPicJmGoCU7

## Reuniones para eventos

Lunes a viernes de 6:00 a 8:00 p. m. Hoy la web pide la cita por WhatsApp. Cuando exista la página de citas de Google Calendar, se pega su enlace en `BOOKING_URL` dentro de `index.html`.

## Bodas: cómo funciona

1. Antes de la boda: los novios escogen cuántos imanes y cuántas horas (para ellos, los invitados o ambos).
2. El día de la boda: fotos a los invitados o a los novios; cada quien escoge en la que salió más guapo.
3. Minutos después: el imán en la mano, ese mismo día. Lo más importante: que los novios se lleven el suyo.

## Estado de la web (noviembre 2026)

- Páginas: Inicio, Bodas y eventos, Catálogo, Ideas, Sobre nosotros y Preguntas frecuentes con Contáctanos.
- Funciones:
  - carrito a WhatsApp con adelanto del 50 %, fecha, dirección, forma de lámpara y canciones;
  - precio de imanes por cantidad;
  - ventana de detalle de cada producto;
  - agenda de reuniones de lunes a viernes, de 6 a 8 p. m.;
  - refri virtual en Ideas;
  - juego "¿Cómo sería en tu evento?" en Bodas y eventos: tomar la foto, escoger la favorita, imprimirla, encapsularla y entregarla (reemplaza la línea de tiempo, noviembre 2026);
  - fotos reales de clientes (noviembre 2026): mascotas, invitados de la boda de Kari & Vini, Día de la Mujer, Dinofabeto, Matesaurios, siluetas de metal (gato, corazón, corazón con 6 y con 10 fotos) y calendarios anuales y mensuales. Guardadas en assets/img/productos (fotos completas) y assets/img/imanes (solo la cara del imán).
  - reseñas con estilo de WhatsApp e Instagram.
- Detalles de Kipi:
  - saludo según la hora;
  - chispas al agregar algo al pedido;
  - celebración al enviar el pedido;
  - secreto de 3 toques en la portada.
  - portada "De miles, una": mosaico de fotos que se enfocan con el dedo, contador "4 382 fotos en tu celular" y la foto "esta sí" (noviembre 2026).
- Archivos: guía visual en `DESIGN.md`, ficha del negocio en `PRODUCT.md`, skill Impeccable en `.claude/skills/impeccable`.
- Pendiente del negocio:
  - fotos de productos e ideas;
  - video de bodas;
  - foto de Dani;
  - enlace de citas de Google Calendar (se pega en `BOOKING_URL` dentro de `index.html`);
  - imanes por hora en bodas;
  - hosting y dominio.

### Publicación en GitHub Pages (pendiente, 10 de noviembre de 2026)

- Mari creó la organización de GitHub `vinculoseternos` e invitó a Marco (`marcoaef7-pixel`) como Owner.
- Pasos que faltan:
  1. Marco acepta la invitación.
  2. Instalar la app de Claude en la organización desde https://claude.ai/connect-github.
  3. Crear el repositorio público `vinculoseternos.github.io` dentro de la organización.
  4. Pedirle a Claude: "agrega el repo vinculoseternos/vinculoseternos.github.io" para que suba la página.
  5. Activar Settings → Pages → Deploy from a branch.
- La página quedará en `vinculoseternos.github.io`. La rama con todo el trabajo es `claude/clever-galileo-4gxier` y ya tiene `.nojekyll`.

### Fotos pendientes

- Bebé y baby shower (ideas "Baby shower", "Su primer año" e imán "Bebé" de la refri virtual).
- Cumpleaños o sesión de fotógrafo (idea "Fotos del fotógrafo").
- Más graduaciones.
- Pareja y Día de la Mujer para la refri virtual (por ahora son cuadros de color).
- Empaque para regalo (producto con "Fotos próximamente").

### Reglas de fotos acordadas

- Las fotos de imanes se muestran completas, con la mano o la refri a la vista; no se recortan a la cara del imán. Excepción: los imanes de boda de la refri hecha con IA.
- La refri virtual de Ideas usa fotos originales sin imán, porque ahí la persona convierte su foto en imán.
- Fotos guardadas sin usar todavía: `assets/img/productos/` (abuelita-2, viaje-2, pareja-2, pareja-4, pareja-5, pareja-6, boda-invitados-2, boda-invitados-3, graduacion-1).
