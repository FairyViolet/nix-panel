# nix-panel

Panel de publicar y página de comentarios de **Mi Mundo Nix**
(<https://ultravioletfairy.neocities.org>). Se sirve con GitHub Pages.

- `admin/` — panel Sveltia CMS. Edita el repositorio privado
  `FairyViolet/mi-mundo-nix`; al publicar, GitHub Actions sube la web a
  Neocities. Se entra con "Sign In with Token".
- `comentarios.html` — comentarios de las visitas (Cusdis). La web de
  Neocities la muestra en un marco porque allí no se puede hablar con
  otros servidores.

Este repositorio es público pero no contiene entradas ni nada privado: solo
este panel. La fuente está en `panel/` del repositorio principal; se publica
aquí con `git subtree push --prefix panel panel main`.
