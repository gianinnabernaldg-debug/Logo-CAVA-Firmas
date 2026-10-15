# CAVA Estudio — Logos para firma

Hosting estático del logo para usarlo en firmas de correo (Gmail, Outlook, Apple Mail).

## Archivos

| Archivo | Tamaño | Uso |
|---|---|---|
| `public/logo-cava-150.png` | 150×150 | Firma de correo (recomendado) |
| `public/logo-cava-300.png` | 300×300 | Firma en pantallas retina |
| `public/logo-cava.png` | 917×918 | Original |

## Publicar

1. Crea un repositorio nuevo en GitHub (ej. `cava-logos`) y sube todo el contenido de esta carpeta.
2. En [vercel.com](https://vercel.com) → **Add New → Project** → importa el repo.
3. Framework Preset: **Other**. No cambies nada más → **Deploy**.
4. Tu logo quedará en: `https://TU-PROYECTO.vercel.app/logo-cava-150.png`

## Usar en la firma

**Gmail:** Configuración → Firma → icono de imagen → pestaña **URL web** → pega la URL.

**HTML (Outlook, Apple Mail, generadores de firma):**

```html
<img src="https://TU-PROYECTO.vercel.app/logo-cava-300.png"
     width="80" height="80" alt="CAVA Estudio"
     style="display:block;border:0;">
```

Usar la versión de 300 px mostrada a 80 px se ve nítido en pantallas retina.
