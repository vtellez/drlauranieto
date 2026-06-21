# Web Dra. Laura Nieto Pascual

Landing de la Dra. Laura Nieto — Ginecología y Menopausia (Córdoba).

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (público), p. ej. `dralauranieto`.
2. **Add file → Upload files** y sube `index.html` (y `CNAME` si vas a usar el dominio propio). Commit.
3. **Settings → Pages → Source:** *Deploy from a branch*, rama `main`, carpeta `/ (root)`. Guarda.
4. En 1–2 min tu web estará en `https://TU-USUARIO.github.io/dralauranieto/`.

## Dominio propio (dralauranieto.es)

- El archivo `CNAME` ya contiene `dralauranieto.es`. Si **todavía no** vas a usar el dominio, **borra el archivo `CNAME`** antes de subir.
- En tu proveedor de dominio, crea 4 registros **A** apuntando a:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- (Opcional) un **CNAME** `www` → `TU-USUARIO.github.io`
- En Settings → Pages, activa **Enforce HTTPS** cuando esté disponible.

## Actualizar la web

Cuando haya cambios, sustituye `index.html` por la nueva versión (Add file → Upload files → Commit).
