# Selah Music Academia — Estado del Sitio Web

**Versión:** 1.0 (octubre 2026)  
**Link:** https://selah-indol.vercel.app

---

## Lo que YA tiene la V1

1. **Navegación fija** — logo + menú que cambia al hacer scroll, hamburguesa en móvil
2. **Hero** — frase principal, botón de WhatsApp, estadísticas (9 años, instrumentos, alumnos)
3. **Marquee animado** — cinta con los instrumentos disponibles
4. **Encontrá tu instrumento** — 16 instrumentos con iconos, 3 modalidades (presencial, virtual, grupal)
5. **Pequeño Gran Músico (PGM)** — descripción del programa, libros, ensambles, coloreables
6. **Extras** — talleres, presentaciones, estimulación temprana, videoclases pregrabadas
7. **Más que una academia** — servicios: grabación, eventos, reparación, curso de audio
8. **Tienda** — catálogo ficticio con 6 productos, precios en colones, botón de WhatsApp para consultar
9. **Nosotros** — historia de Bryan, libros patentados, visión/misión, dirección
10. **Equipo docente** — card de Bryan como fundador + 3 placeholders para profesores
11. **Testimonios** — Familia 3G, niño prodigio, espacio para entrevistas a papás
12. **Precios** — matrícula, clase individual, clase grupal
13. **Contacto** — WhatsApp directo, dirección (frente al Parque de San Antonio, Desamparados), horarios
14. **Redes sociales** — Instagram, TikTok, Facebook con links reales
15. **SEO** — título geo-localizado, Open Graph tags
16. **Responsive** — funciona en celular, tablet y escritorio
17. **Deploy** — sitio en vivo en Vercel

---

## Lo que FALTA para completar la V1

Estos son datos o materiales que Bryan debe facilitar para quitar los placeholders amarillos:

| # | Qué falta | Dónde aparece |
|---|-----------|---------------|
| 1 | Confirmar cantidad exacta de alumnos (¿100+?) | Hero — estadísticas |
| 2 | Confirmar cantidad exacta de instrumentos (¿15+?) | Hero — estadísticas |
| 3 | Link a la pista animada de YouTube (PGM) | Sección PGM |
| 4 | Link o contenido de videoclases pregrabadas | Sección Extras |
| 5 | Foto profesional de Bryan | Sección Profesores |
| 6 | Bio corta de Bryan (2-3 líneas) | Sección Profesores |
| 7 | Nombres y fotos de los otros 3 profesores | Sección Profesores |
| 8 | Videos de los 2 testimonios (Familia 3G y niño prodigio) | Sección Testimonios |
| 9 | Videos de entrevistas a papás | Sección Testimonios |
| 10 | Confirmar precios actuales (matrícula, individual, grupal, PGM, virtual) | Sección Precios |
| 11 | Confirmar precios y marcas de la tienda (guitarra, violín, teclado) | Sección Tienda |
| 12 | Catálogo completo de tienda (más productos) | Sección Tienda |
| 13 | Link de canal de YouTube (o confirmar que no existe aún) | Footer — redes sociales |

---

## Posibles mejoras para V2 y futuras versiones

Basado en la reunión del 22 de octubre:

### V2 — Corto plazo
- **QR en libros físicos** — código QR en los libros impresos que redirige a la página (actualizable sin reimprimir)
- **Preview de libros** — sección donde se puedan hojear los libros del PGM desde la web (Issuu gratis)
- **Marca de agua digital** — "Selah Music by Bryan Martínez" en contenido descargable (iLovePDF/Canva gratis)
- **Canal de YouTube** — embeber videos cuando exista el canal

### V3 — Mediano plazo
- **Cursos especializados:**
  - Adultos mayores
  - Personas con discapacidad (incluye método para sordos)
- **Galería de fotos/videos** — presentaciones, recitales, clases en acción
- **Blog o noticias** — artículos sobre música, tips para padres, novedades de la academia
- **Temporadas y promociones** — banners para Navidad, Día del Niño, Día de la Madre/Padre, septiembre (apartados para diciembre)
- **Sistema de inscripción online** — formulario de matrícula con selección de instrumento y horario

### V4 — Largo plazo
- **App móvil / PWA** — la visión de Bryan de tener una app con los iconos de instrumentos como botones interactivos
- **E-commerce real** — tienda con carrito, pagos en línea, tracking de envíos (Henry hace envíos en San José, correos al resto del país)
- **Red de academias** — secciones para sucursales futuras (Joan y Mónica como subdirectores)
- **Plataforma de videoclases** — acceso por suscripción a clases pregrabadas
- **Agenda y reservas** — los alumnos reservan su horario de clase directamente

---

## Protección de contenido digital (videos, libros, pistas)

Bryan quiere que cierto contenido (videoclases, libros del PGM, pistas) sea accesible para alumnos pero no descargable ni redistribuible. Opciones investigadas:

### Videos de clases

| Opción | Precio | Protección |
|--------|--------|-----------|
| YouTube no listado | Gratis | Mínima — se descarga con extensiones |
| **Vimeo Starter** | ~$12/mes | Buena — desactiva descarga, restringe por dominio |
| **Hotmart** | Gratis (cobra % por venta) | Buena — watermark automático con email del alumno |
| Teachable/Thinkific | $39-49/mes | Buena pero cara para empezar |

### PDFs / Libros

| Opción | Precio | Protección |
|--------|--------|-----------|
| **Issuu** | Gratis (con ads) / $19/mes | Visor flipbook, sin descarga, sin clic derecho |
| FlipHTML5 | Gratis limitado / $15/mes | Similar, se puede embeber en el sitio |

### Recomendación

- **Para vender cursos como producto:** Hotmart (gratis, cobra comisión) — incluye watermark dinámico + protección de video y PDF
- **Solo para alumnos activos:** Vimeo Starter ($12/mes) + Issuu (gratis)
- **Marca de agua estática:** iLovePDF o Canva (gratis) — "Selah Music by Bryan Martínez"
- DRM completo (tipo Netflix) no es viable para una academia pequeña, pero el DRM ligero (login + sin descarga + watermark) disuade al 95% de los casos
