# Comicteca

PWA lectora de cómics — CBZ, CBR, PDF. Funciona offline.

## Archivos

```
index.html   → app principal
manifest.json → config PWA
sw.js         → service worker (offline)
icon-192.png  → ícono
icon-512.png  → ícono
```

## Deploy en GitHub Pages

1. Crea repositorio en github.com (público)
2. Sube todos estos archivos
3. Ve a Settings → Pages → Branch: main → Save
4. Tu URL será: `https://TU_USUARIO.github.io/NOMBRE_REPO`
5. Abre esa URL en Safari del iPhone
6. Compartir → **Agregar a pantalla de inicio**
7. Abre la app una vez con internet — ya queda offline para siempre

## Formatos soportados

- CBZ (recomendado)
- PDF
- ZIP con imágenes
- CBR (solo si internamente es ZIP)
