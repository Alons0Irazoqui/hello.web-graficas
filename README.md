# Brief de Proyecto Web — GRÁFICAS Diseño y Publicidad

## 1. Resumen del proyecto

- **Tipo de proyecto:** Landing page para negocio local (imprenta / taller de diseño gráfico y publicidad).
- El desarrollo se realizará sobre una **plantilla base de HTML ya existente**.
- Ya se entregó por separado un **prompt inicial** con instrucciones para adaptar dicha plantilla a este negocio.
- **La estructura de secciones de la página NO se define en este documento.** Debe respetarse la estructura ya definida por la plantilla base. Este brief cubre únicamente: información del negocio, identidad de marca, estilo visual y efectos requeridos.

---

## 2. Información del negocio

Datos extraídos del análisis de las imágenes en la carpeta `imagenes/` (flyers publicitarios del negocio), complementados con los datos proporcionados directamente por el cliente.

| Dato | Detalle |
|---|---|
| **Nombre comercial** | GRÁFICAS — Diseño y Publicidad |
| **Nombre en Facebook** | Graficas Zacatecas |
| **Giro** | Imprenta / taller de diseño gráfico, publicidad e impresión digital |
| **Dirección** | Calzada Luis Moya No. 403-B, Zacatecas, Zacatecas |
| **Teléfono principal** | 492 106 7050 — WhatsApp y llamadas |
| **Horarios de atención** | No se encontraron en las imágenes ni en las redes sociales disponibles. **Confirmar directamente con el cliente.** |
| **Facebook** | https://www.facebook.com/profile.php?id=61566544267645 |
| **Ubicación (Google)** | https://share.google/HVtFJAFY8OwpswOD2 |

> ⚠️ **Nota — discrepancia de teléfono:** en una de las piezas publicitarias (anuncio de "Toldo Enrollable") aparece el número **4921067059**, que difiere en el último dígito del número proporcionado por el cliente (**4921067050**). Confirmar con el cliente cuál es el número correcto antes de publicarlo en el sitio.

### Servicios / productos identificados

A partir de las piezas publicitarias se identificaron las siguientes líneas de negocio (con precios de referencia tal como aparecen en los flyers; deben confirmarse con el cliente antes de publicarse, ya que pueden estar desactualizados):

- **Impresión textil (DTF):** playeras personalizadas ($160 c/u; $180 por pieza en pedidos de mayoreo desde 12 piezas), envíos a todo el país.
- **Sublimación:** tazas ($65), gorras ($65), láminas, llaveros, fotobotones, vasos térmicos.
- **Gran formato:** lona impresa HD ($78 + IVA, entrega el mismo día), vinil impreso HD ($140/m²).
- **Rotulación vehicular y de espacios:** vinil en interiores/exteriores, car wrap, rotulación de vitrinas y oficinas.
- **Corte y grabado láser:** termos ($220), MDF, acrílico — placas, trofeos, llaveros y decoración personalizada.
- **Toldos enrollables** para negocios (instalación, varios colores).
- **Papelería e impresión general:** tarjetas de presentación, volantes, notas de venta, invitaciones, fotografías, boletos, tabloide 13x19 ($20), adherible/sticker 13x19 ($25).
- **Publicidad exterior:** banderas publicitarias tipo pluma (banderines) para negocios.
- **Vasos y cilindros personalizados** (desde $18).

### Fuentes adicionales de información

Si el desarrollador necesita más contexto (fotos reales del local, reseñas, publicaciones recientes, promociones vigentes, horarios, etc.), puede consultarlo directamente en:

- Facebook del negocio: https://www.facebook.com/profile.php?id=61566544267645
- Ubicación en Google: https://share.google/HVtFJAFY8OwpswOD2

---

## 3. Identidad de marca (branding)

### Logo

El logo consiste en el wordmark **"GRÁFICAS"** en tipografía sans-serif bold/geométrica negra, donde la letra **"A"** está construida con fragmentos de color estilo CMYK (cian, magenta, amarillo, negro), evocando marcas de registro de impresión. Debajo, la leyenda **"DISEÑO Y PUBLICIDAD"** en versalitas espaciadas, subrayada por una fila de pequeños cuadros de color alternando cian/magenta/amarillo/negro. Existe también una variante con un ícono geométrico abstracto tipo "destello/salpicadura" a la izquierda del wordmark, construido con la misma paleta.

### Paleta de colores (HEX)

**Colores de marca (extraídos directamente del logo — proceso CMYK):**

| Color | HEX | Uso |
|---|---|---|
| Cian | `#00AEEF` | Acento / detalle de marca |
| Magenta | `#EC008C` | Acento / detalle de marca |
| Amarillo | `#FFD100` | Acento / detalle de marca |
| Negro | `#0A0A0A` | Wordmark, texto principal |

**Paleta sugerida para el sitio (versión refinada, enterprise/premium):**

| Rol | HEX | Nota |
|---|---|---|
| Fondo base | `#FFFFFF` / `#FAFAFA` | Blanco limpio, respiración visual |
| Superficie oscura | `#0A0A0A` / `#141414` | Secciones oscuras, footer, contraste |
| Texto principal | `#111111` | Sobre fondo claro |
| Texto secundario | `#5C5C5C` | Subtítulos, descripciones |
| Acento primario | `#00AEEF` (Cian) | CTAs, links, detalles destacados |
| Acento secundario | `#EC008C` (Magenta) | Hover states, highlights puntuales |
| Acento terciario | `#FFD100` (Amarillo) | Uso mínimo, detalles/badges |

Se recomienda usar los 4 colores del logo como **acentos puntuales** (no como fondos grandes) para mantener el look premium/minimalista solicitado, apoyándose en negro, blanco y grises neutros como base.

### Tipografía sugerida

- **Encabezados:** Montserrat (peso 800–900 / ExtraBold-Black) — coherente con el trazo grueso y geométrico del wordmark del logo.
- **Cuerpo de texto:** Inter (peso 400–500) — limpia, minimalista y de alta legibilidad, típica de identidades "big tech".

---

## 4. Estilo visual obligatorio

El sitio debe transmitir una identidad de marca **premium, enterprise y corporativa**, con un acabado **elegante y minimalista de nivel big tech**. Evitar saturación de color: usar la paleta de marca como acento, no como base.

---

## 5. Efectos y animaciones requeridos

- Efectos visuales y **animaciones de scroll** (reveal/fade-in/parallax al hacer scroll).
- **Pantalla de carga (preloader)** con spinner + logo del negocio.
- Animaciones en el **título del hero**: efecto máquina de escribir, cambio de color en las letras u otros efectos tipográficos.

---

## 6. Instrucciones sobre assets

- El **logo** se encuentra en la carpeta `imagenes/` pero viene **con fondo** (no es transparente): el desarrollador debe **removerle el fondo** antes de usarlo en el sitio.
- Las 20 imágenes disponibles en `imagenes/` son en su mayoría **flyers publicitarios** (con precios, promociones y fotos de stock) usados para redes sociales, **no fotografías reales del local, del equipo o de trabajos terminados limpias para web**. Úsalas como referencia de servicios, precios y branding, pero **no las publiques directamente como imágenes finales del sitio** salvo el logo (una vez procesado). Si el sitio requiere fotografías reales (fachada, productos, equipo trabajando), solicitarlas al cliente o revisar su Facebook.

---

## 7. Nota para el desarrollador

Este brief es un punto de partida. El desarrollador puede **iterar sobre el proyecto usando Claude Code**, dándole instrucciones las veces que sea necesario, hasta lograr el resultado deseado.

---

## 8. Checklist de trabajo

- [ ] Remover el fondo del logo y generar una versión en PNG transparente.
- [ ] Confirmar con el cliente el teléfono correcto (4921067050 vs. 4921067059), horarios de atención y dirección exacta.
- [ ] Revisar Facebook y la ubicación de Google del negocio por si hay información adicional o más reciente.
- [ ] Aplicar la paleta de colores y tipografía de marca definidas en este documento.
- [ ] Adaptar la plantilla base al negocio siguiendo el prompt inicial ya entregado (sin modificar la estructura de secciones).
- [ ] Implementar el preloader (spinner + logo).
- [ ] Implementar las animaciones de scroll.
- [ ] Implementar la animación del título en el hero (máquina de escribir / cambio de color).
- [ ] Gestionar con el cliente fotografías reales del negocio (fachada, productos, equipo), ya que las imágenes actuales son mayormente flyers publicitarios.
- [ ] Validar el diseño responsivo (mobile, tablet, desktop).
- [ ] Iterar con Claude Code las veces que sea necesario hasta lograr el resultado final.
