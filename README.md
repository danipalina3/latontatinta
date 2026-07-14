# La Tonta Tinta — Daniela Palina

Sitio web de las obras literarias y los servicios editoriales de **Daniela Palina** (La Tonta Tinta).
Es un sitio **estático** (HTML + CSS + JS), listo para desplegarse en **Vercel** sin configuración.

Tipografías (Google Fonts): **Caveat** (handwriting, para el logo y detalles), **Fredoka** (títulos) y **Nunito** (texto).

## Secciones

- **Inicio** (`index.html`) — despliega como principal la novela *Ya que nos agarramos confianza*.
- **Daniela Palina** (`daniela-palina.html`) — sobre la autora.
- **Libros** (`libros.html`) — lista de libros, con una página por cada uno:
  - `libro-ya-que-nos-agarramos-confianza.html` (2026)
  - `libro-que-fregados-has-estado-haciendo.html` (2021)
- **Servicios** (`servicios.html`)
- **Tienda** (`tienda.html`)
- **Contacto** (`contacto.html`)

## Desplegar en Vercel

1. Sube este repositorio a GitHub (rama de trabajo: `claude/daniela-palina-website-aj9mnr`).
2. En [vercel.com](https://vercel.com) → **Add New… → Project** → importa el repositorio.
3. En *Framework Preset* selecciona **Other** (sitio estático). No hay build; el `Root Directory` es la raíz.
4. **Deploy**. Listo.

El archivo `vercel.json` activa URLs limpias (`/libros` en lugar de `/libros.html`).

## ⚠️ Imágenes por agregar

Coloca estos archivos en `assets/img/`. Mientras no existan, el sitio muestra una portada/placeholder de respaldo automáticamente (no se rompe el diseño).

| Archivo | Dónde se usa |
|---|---|
| `yqnac-1.jpg` | Portada de *Ya que nos agarramos confianza* (Inicio, Libros, página del libro, Tienda) |
| `qfheh1.jpg` | Portada de *¿Qué fregados has estado haciendo?* (Libros, página del libro, Tienda) |
| `daniela-palina.jpg` | Foto de la autora (página Daniela Palina) |
| `personaje1-pato.jpg` | Personaje Pato (página de la novela) |
| `personaje2-juliana.jpg` | Personaje Juliana (página de la novela) |
| `personaje3-beca.jpg` | Personaje Beca (página de la novela) |
| `ebook2.png` | Portada «Dibuja y Colorea» (Tienda) |
| `ebook1.png` | Portada «Girls Trip: Kpop Demon Hunters» (Tienda) |

## Datos de contacto usados en el sitio

- Correo: danipalina3@gmail.com
- WhatsApp: 722 512 7898 (`https://wa.me/527225127898`)
- Instagram: https://www.instagram.com/latontatinta_mx/
- TikTok: https://www.tiktok.com/@la.tonta.tinta
