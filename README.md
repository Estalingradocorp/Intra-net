# 🌐 Intra-net de Estalingrado Corp

Portal retro estilo 90s (Windows 95 / Synthwave / Geocities) de **Estalingrado Corp**. Un ciberespacio corporativo que combina estética Win95 con colores neón 80s, música, minijuegos y una extensa colección de recursos, enlaces y herramientas.

> ⚠️ **Este proyecto migró de un blog de Google (Blogger) del año 2008** a un sitio estático publicado en GitHub Pages.

---

## 📌 Origen del proyecto

Este portal nació como un **blog de Google (Blogger) en 2008** bajo el nombre de Estalingrado Corp. Con el tiempo, todo el contenido, los enlaces, los recursos y el espíritu retro del blog original fueron migrados y reconstruidos desde cero como una página web estática moderna, conservando la estética nostálgica de finales de los 90 / principios de los 2000.

### Lo que se conservó del blog original
- 🎨 El estilo visual retro (colores, botones Win95, marquee neón, GIFs animados)
- 📡 Los enlaces corporativos y la red de sitios de Estalingrado Corp
- 🎬 Los archivos multimedia y videoteca
- 📚 Los recursos educativos y herramientas online
- 👥 Los grupos y páginas de Facebook administrados por la corporación

### Lo que se mejoró en la migración
- ⚡ Carga mucho más rápida (recursos optimizados, carga diferida)
- 📱 Diseño adaptable a móviles
- 🕹️ Minijuegos interactivos (Snake) integrados en la página
- 🎵 Reproductor de música funcional (estilo WinAmp)
- 📝 Bloc de notas y libro de visitas con guardado local

---

## 🚀 Despliegue

El sitio se publica automáticamente en **GitHub Pages** mediante el push a la rama `main`.

**URL:** https://estalingradocorp.github.io/Intra-net/

### Cómo actualizar
```bash
git add .
git commit -m "Descripción del cambio"
git push origin main
```
GitHub Pages regenera el sitio en aproximadamente 1 minuto.

---

## 📁 Estructura

```
index.html           → Portal principal retro (todo el contenido en un solo archivo)
index2.html          → Subpágina "data-wiki" (Centro de Control Digital, estilo moderno)
Buscador retro.html  → Subpágina buscador retro (IDEX, metabuscador)
K27.html             → Subpágina K27 (DarkWeb Terminal Store, estilo terminal)
README.md            → Este documento
```

Las páginas se navegan entre sí mediante enlaces en cada cabecera/menú:

| Desde | Enlaces a |
|-------|-----------|
| **index.html** | index2.html (🎛️ Centro de Control), Buscador retro.html (🔍 Buscar), K27.html (🖥️ K27) |
| **index2.html** | index.html (⬅️ Portal Retro), Buscador retro.html (🔍 Buscador), K27.html (🖥️ K27) |
| **Buscador retro.html** | index.html, index2.html, K27.html (menú Empresa) |
| **K27.html** | Menú separado `[RED_ESTALINGRADO]` con enlaces a los otros 3 portales |

**URLs:**
- Portal retro: `https://estalingradocorp.github.io/Intra-net/`
- data-wiki: `https://estalingradocorp.github.io/Intra-net/index2.html`
- Buscador retro: `https://estalingradocorp.github.io/Intra-net/Buscador%20retro.html`
- K27: `https://estalingradocorp.github.io/Intra-net/K27.html`

---

## 🧩 Secciones principales del portal

| Sección | Descripción |
|---------|-------------|
| **HERO BANNER** | Atardecer synthwave con logo corporativo |
| **BUSCADOR INTERNO** | Búsqueda en vivo con resaltado de coincidencias |
| **MEGA PROMO** | Portal central, red de sitios y redes sociales |
| **LEARN FOR FREE** | 37 recursos educativos gratuitos (HTML, Python, IA, IBM Quantum, etc.) |
| **GAME ROM LAUNCHER** | Lanzador de juegos y proyectos del Software Lab |
| **SNAKE_95** | Minijuego retro interactivo |
| **VIDEOTECA** | Archivos de video corporativos embebidos |
| **RECURSOS ONLINE** | Empleo, salud, educación e inteligencia |
| **DISTRIBUCIONES LINUX** | Sitios de distribuciones de Linux (Ubuntu, Arch, Kali...) y otros sistemas (FreeBSD, ReactOS, Haiku...) |
| **TERMINAL CMD** | Herramientas (Rufus, WinRAR, Safety Scanner) |
| **ACTIVADOR WIN10** | Métodos de activación y claves |
| **INTERNET ARCHIVE** | Biblioteca digital |
| **THE BLACK MARKET** | Sección promocional especial |
| **JUEGOS ONLINE** | Juegos jugables en el navegador |
| **LINKS ESTALINGRADO** | Todos los enlaces corporativos, grupos y páginas |
| **PUBLICIDADES** | Banner animados con enlace al Market (incl. promos de ECOS PRO) |
| **AI ASSISTANT** | Asistente virtual retro (CRT) |
| **WINAMP** | Reproductor de música funcional |
| **NOTEPAD** | Bloc de notas con guardado local |
| **GUESTBOOK** | Libro de visitas local |
| **STATS** | Contador de visitas persistente |
| **DNS ADBLOCK** | Servidor DNS para bloqueo de anuncios |

---

## 🛠️ Recursos educativos incluidos (Learn for Free)

HTML, CSS, JavaScript, React, Vue, Angular, Git, Web3, Python, SQL, Blockchain, Next.js, IA, PHP, API, Go, Rust, Design Patterns, TypeScript, C++, Java, C#, Swift, Django, Flask, Docker, Kubernetes, Linux, Ciberseguridad, DevOps, Cloud (AWS/GCP/Azure) e IBM Quantum Cloud.

---

## 📄 Subpáginas

### `index2.html` — data-wiki (Centro de Control Digital)
Estilo moderno (Inter font, tema claro/azul). Permite cambiar el color de pantalla (blanco, negro, rojo, verde, etc.), funciona como panel de control digital y reproductor de pantallas de color. Incluye selector de idioma y botón de sonido.

### `Buscador retro.html` — IDEX (Buscador Retro)
Metabuscador con estética retro que integra múltiples motores (Bing, Yahoo, DuckDuckGo, Yandex, Brave, Baidu, Startpage, Qwant, Ecosia, Wikipedia, Internet Archive, SearXNG), herramientas de IA (DeepSeek, Qwen, ChatGPT, Géminis, Copilot...), creador de PDF, privacidad y más. Soporta búsqueda por voz y exportación.

### `K27.html` — DarkWeb Terminal Store
Tienda/terminal con estética de "dark web" (fondo negro, texto verde, fuente monoespaciada). Incluye buscador, tienda, terminal root, información del sistema, estado de cifrado AES-256-GCM y modo de pantalla completa. Su menú de navegación entre portales aparece como `[RED_ESTALINGRADO]` bajo el header.

---

## 🎮 Características técnicas

- **Tecnología:** HTML5 + CSS3 + JavaScript vanilla (sin dependencias externas de código)
- **Fuentes:** VT323 y Press Start 2P (carga diferida para no bloquear el render)
- **Persistencia local:** `localStorage` para visitas, notas y libro de visitas
- **Carga optimizada:** imágenes e iframes con `loading="lazy"`, audios con `preload="none"`, BIOS que arranca con `DOMContentLoaded`

---

© 1989-2026 Estalingrado Corp | Optimizado para Netscape Navigator 4.0 e Internet Explorer 5.0