# Portfolio — Gonzalo Trillo Hidalgo

Portfolio personal de un solo archivo, sin dependencias ni build. Solo HTML y CSS.

## Estructura

```
portfolio/
├── index.html      → la página completa (HTML + CSS + JS en un archivo)
├── assets/         → coloca aquí tu foto y tu CV en PDF si los añades
└── README.md
```

## Antes de publicar

Abre `index.html` y reemplaza estos marcadores (busca `TU-USUARIO`, aparece 6 veces):

- `https://github.com/TU-USUARIO` → tu usuario real de GitHub
- `https://www.linkedin.com/in/TU-USUARIO` → tu perfil real de LinkedIn

El email y los datos de Soltel ya están puestos. Revisa los bullets de
experiencia y ajústalos a lo que haces de verdad.

## Cómo publicarlo gratis

### Opción A — GitHub Pages
1. Crea un repositorio nuevo y sube el contenido de esta carpeta.
2. *Settings → Pages → Branch: `main` / root* y guarda.
3. En 1-2 min tendrás una URL `https://tu-usuario.github.io/portfolio`.

### Opción B — Cloudflare Pages o Vercel
1. Conecta el repositorio.
2. Framework preset: *None* · Build command: *(vacío)* · Output: `/`.
3. Deploy. Puedes asignar un dominio propio cuando quieras.

## Añadir tu foto o el CV (opcional)

1. Mete los archivos en `assets/` (p. ej. `foto.jpg`, `cv.pdf`).
2. Enlázalos desde `index.html` con rutas tipo `assets/cv.pdf`.

---
Hecho a mano · 2026
