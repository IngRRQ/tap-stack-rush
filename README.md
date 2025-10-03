# Tap Stack Rush — Starter Kit (HTML5)
Fecha: 2025-10-03

Este paquete contiene:
- `index.html` → juego jugable listo para web (móvil/desktop).
- `PRIVACY-POLICY.html` → política de privacidad básica.
- `TERMS.html` → términos de uso básicos.
- `ads-example-snippets.txt` → lugar y guías para pegar anuncios/donaciones.
- `manifest.webmanifest` → opcional para PWA.
- `robots.txt` → estándar.

## 1) Publicar GRATIS en GitHub Pages
1. Crea un repo nuevo en GitHub (p. ej. `tap-stack-rush`).
2. Sube **todos los archivos** de este paquete (drag & drop en la raíz).
3. Ve a **Settings → Pages**.
4. En **Source** elige *Deploy from a branch*.
5. Selecciona `main` y la carpeta `/root` → Save.
6. Espera a que se despliegue. Tu juego quedará online con URL: `https://<tu-usuario>.github.io/tap-stack-rush/`.

## 2) Publicar GRATIS en itch.io (browser / HTML5)
1. Crea/abre tu cuenta en itch.io.
2. **Create new project** → *Kind of project*: **HTML**.
3. Sube `index.html` (y el resto de archivos).
4. Marca **This file will be played in the browser**.
5. Rellena **Title, Short description, Cover** (usa una captura de pantalla del juego).
6. En **Pricing** selecciona **No payments** o **Pay what you want** (donaciones).
7. **Save & Publish**.

## 3) Monetizar sin inversión
A) **Donaciones**: En itch.io activa *Pay what you want*. También puedes pegar tu botón Ko‑fi/BuyMeACoffee dentro del juego (ver `ads-example-snippets.txt`).

B) **Anuncios** (portales HTML5): Regístrate en un portal como CrazyGames o GameMonetize. Ellos te darán un **snippet/SDK**. Pégalo en `index.html` dentro del div `#ad-container` y/o lanza un *ad break* entre **Game Over** y **Reiniciar**.

C) **Licenciamiento**: Algunos portales compran/exclusivan juegos sencillos. Envía tu build y ficha técnica.


## 4) Dónde pegar los anuncios (o donaciones)
- Bloque banner: dentro del contenedor `<div id="ad-container">` en `index.html`.

- Interstitial entre partidas: justo cuando se muestra el panel **Game Over** antes de re‑iniciar.


## 5) Marketing exprés (gratis)
- TikTok/Shorts: clips de 5–8 s con el momento del *Perfect x3!*

- Reddit: r/IndieDev, r/GameDev, r/WebGames.

- Game Jams de itch.io para ganar visibilidad.


## 6) Ajustes rápidos del juego
- Velocidad/dificultad: busca `speed =` en `index.html`.

- Quitar/poner sonido por defecto: variable `soundOn`.

- Reiniciar récord: limpiar `localStorage` → key `tsr_best`.


¡Éxitos y buenas métricas!