---
name: Prestigio Alabastro
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#725b38'
  on-secondary: '#ffffff'
  secondary-container: '#fedeb2'
  on-secondary-container: '#78603e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#201a17'
  on-tertiary-container: '#8b827e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#fedeb2'
  secondary-fixed-dim: '#e0c298'
  on-secondary-fixed: '#281800'
  on-secondary-fixed-variant: '#584323'
  tertiary-fixed: '#ece0db'
  tertiary-fixed-dim: '#cfc4bf'
  on-tertiary-fixed: '#201a17'
  on-tertiary-fixed-variant: '#4c4542'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  display-xl:
    fontFamily: EB Garamond
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '300'
    lineHeight: 32px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  nav-link:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.2em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
spacing:
  unit: 8px
  margin-edge: 64px
  gutter: 32px
  section-gap: 160px
  container-max: 1440px
---

## Marca y Estilo
Este sistema de diseño personifica la exclusividad y la autoridad intelectual de una firma legal boutique de alto nivel. La narrativa visual se aleja de los clichés jurídicos tradicionales para adoptar una estética **Editorial Minimalista Avant-Garde**, inspirada en publicaciones de alta costura y arquitectura contemporánea.

El objetivo es evocar una respuesta emocional de serenidad, confianza absoluta y sofisticación sin esfuerzo. Se prioriza el espacio negativo como un lujo en sí mismo, permitiendo que cada palabra y elemento visual respire con intención académica. La interfaz debe sentirse cinemática, como una galería privada donde la precisión legal se encuentra con el arte visual.

## Colores
La paleta se define como "Minimalismo Cálido", diseñada para transmitir prestigio sin la frialdad del blanco puro.

- **Fondo Principal (Alabastro):** `#F9F8F6`. Una base cremosa que reduce la fatiga visual y proyecta calidez institucional.
- **Contraste Primario (Obsidiana):** `#0F0F0F`. Utilizado para tipografía principal y elementos estructurales definidos.
- **Contraste Secundario (Espresso):** `#1A1512`. Para capas de profundidad y variaciones sutiles en el texto.
- **Acento (Cobre Champagne):** `#C5A880`. Un tono metálico mate para llamadas a la acción, líneas decorativas y estados de selección, evocando materiales nobles y discretos.

## Tipografía
El sistema emplea un contraste tipográfico de alta tensión entre la tradición literaria y la precisión moderna.

- **EB Garamond (Serif):** Se utiliza para titulares y declaraciones de marca. Debe presentarse con un interletrado ligeramente ajustado en tamaños grandes para enfatizar su elegancia editorial.
- **Inter (Sans-Serif):** Se utiliza para el cuerpo de texto y navegación. Para elementos de interfaz y menús, se debe aplicar un `letter-spacing` generoso (tracking largo) para evocar una sensación de exclusividad y orden.

La jerarquía visual prioriza la legibilidad y el ritmo pausado, evitando bloques densos de texto en favor de una composición aireada.

## Diseño y Espaciado
El sistema de retícula es asimétrico y artístico, rompiendo la rigidez corporativa para alinearse con una estética de revista de lujo.

- **Estructura:** Se basa en una cuadrícula de 12 columnas con márgenes laterales amplios de `64px` en escritorio, permitiendo que el contenido flote centralmente.
- **Asimetría:** Se fomenta el uso de desplazamientos (offsets). Por ejemplo, un titular puede ocupar las primeras 8 columnas, mientras que el cuerpo de texto comienza en la columna 5, creando un flujo visual dinámico.
- **Ritmo Vertical:** Se utilizan saltos de sección extremadamente generosos (`160px`) para separar áreas temáticas, obligando al usuario a desplazarse con calma y apreciar cada mensaje individualmente.

## Elevación y Profundidad
Este sistema rechaza las sombras pesadas y los efectos tridimensionales literales. La profundidad se comunica mediante el **solapamiento de capas tonales** y el uso de bordes extremadamente finos.

- **Capas:** Se utilizan superficies `Alabastro` sobre fondos un tono más oscuros o viceversa para separar secciones.
- **Líneas de Cabello (Hairlines):** El uso de bordes de `1px` con opacidad reducida (`rgba(15, 15, 15, 0.1)`) es la herramienta principal para delimitar espacios sin interrumpir el flujo visual.
- **Opacidad:** Los elementos flotantes (como menús persistentes) deben utilizar un desenfoque de fondo sutil (backdrop-blur) con una transparencia del 90% para mantener la conexión con la narrativa visual inferior.

## Formas
La geometría del sistema es estrictamente ortogonal. El uso de bordes con `0px` de redondeo (sharp corners) refuerza la seriedad, la precisión legal y la arquitectura de vanguardia. Las imágenes deben presentarse con cortes limpios, y los contenedores no deben suavizar sus ángulos bajo ninguna circunstancia, manteniendo una estética arquitectónica y técnica.

## Componentes

### Botones (Acciones de Prestigio)
Los botones principales son rectangulares, con fondo `Obsidiana` y texto en `Inter` con tracking expandido en color `Alabastro`. El estado hover debe ser sutil: una transición suave hacia el color `Cobre Champagne` o un cambio sutil en la opacidad.

### Campos de Entrada (Inputs)
Deben ser minimalistas: solo una línea inferior de `1px` en color `Obsidiana` (60% opacidad). La etiqueta (label) se sitúa encima en `Inter` (Label-sm). No se permiten bordes completos ni sombras internas.

### Tarjetas (Cards)
Las tarjetas no tienen sombras. Se definen por un cambio sutil de color de fondo o por un borde perimetral de `1px` extremadamente tenue. El contenido dentro de la tarjeta debe tener un acolchado (padding) generoso de al menos `40px`.

### Listas de Servicios
Presentadas con numeración romana o viñetas de línea fina en `Cobre Champagne`. Cada ítem debe tener un espacio vertical significativo para denotar la importancia de cada especialidad legal.

### Imágenes
Se deben tratar con una ligera desaturación o filtros cálidos para integrarse con el color Alabastro. El uso de fotografías en blanco y negro con alto contraste es altamente recomendado para mantener el tono cinemático.