# Rutina Completa · Sary

Rutina diaria completa: mañana, tarde y noche con bloques de tiempo

## Estructura

```
rutina-completa/
├── index.html       ← App principal
├── manifest.json    ← Configuración PWA
├── sw.js            ← Service Worker (offline)
├── .nojekyll        ← Para GitHub Pages
├── README.md
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Subir a GitHub y usar como app

1. Crear repo en GitHub → nombre: **rutina-completa** → Public
2. Subir todos los archivos (incluyendo carpeta `icons/` y `.nojekyll`)
3. Settings → Pages → Branch: main → / root → Save
4. URL: `https://TU_USUARIO.github.io/rutina-completa`
5. Chrome Android → entrar a la URL → ⋮ → Instalar app
