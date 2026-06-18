# Proyectos Propios — sitio interno

Sitio estático (HTML + CSS, sin frameworks) con los dossieres de due diligence de las operaciones inmobiliarias propias. Listo para GitHub Pages.

> **CONFIDENCIAL** — Documento interno Xavi + Rus. Prohibida su difusión. No publicar en un repo público sin revisar.

## Estructura

```
PROYECTOS-PROPIOS-WEB/
├── index.html              # Portada / índice de operaciones
├── .nojekyll               # Desactiva el procesado Jekyll de GitHub Pages
├── README.md
└── beniarbeig/
    ├── index.html          # Dossier del Edificio Beniarbeig
    └── assets/             # Fotos del estado actual
```

## Cómo abrirlo en local

Doble clic en `index.html`, o servirlo con un servidor estático:

```bash
cd PROYECTOS-PROPIOS-WEB
python -m http.server 8080
# abrir http://localhost:8080
```

## GitHub Pages

Subir el contenido a la rama configurada como Pages. El `.nojekyll` evita que GitHub ignore carpetas. Al ser material confidencial, usar repo **privado** o Pages restringido.

## Añadir una operación nueva

1. Crear `nueva-operacion/index.html` (copiar la estructura del dossier de Beniarbeig).
2. Añadir su carpeta `assets/` con fotos.
3. Duplicar la tarjeta `<a class="card">` en `index.html` y apuntarla a la nueva ruta.

## Fuente de datos

Dossier de Beniarbeig transcrito de `INFORME-EXTRACTO-BENIARBEIG.md` (consolidación de 5 informes de due diligence). Las cifras, el veredicto y los riesgos se transcriben literalmente del informe fuente.
