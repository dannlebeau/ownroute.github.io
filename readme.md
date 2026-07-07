# José Córdova-Fredes — Portfolio

Sitio web personal construido sobre la plantilla [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) de BootstrapMade.

**Live:** [dannlebeau.github.io/ownroute.github.io](https://dannlebeau.github.io/ownroute.github.io)

---

## Stack

- HTML5 / CSS3 / Vanilla JS
- Bootstrap 5 · AOS · Isotope · GLightbox · Typed.js
- GitHub Pages (deploy automático desde `main`)

## Estructura

```
ownroute.github.io/
├── index.html          → Página principal
├── assets/
│   ├── css/style.css   → Estilos del tema
│   ├── js/main.js      → Lógica del template + custom JS
│   └── img/            → Imágenes y capturas de proyectos
└── forms/              → Handler del formulario de contacto
```

## Personalización rápida

| Qué cambiar | Dónde |
|---|---|
| Foto de perfil | `assets/img/Foto_JCF_.JPG` |
| Capturas de proyectos | `assets/img/` — reemplazar el `<div class="portfolio-placeholder">` por `<img>` |
| URLs de credenciales Acreditta | Buscar `acreditta-badge` en `index.html` y actualizar `href` |
| Año de copyright | Automático via JS |
| Contador de experiencia | Automático desde `new Date(2019, 0, 3)` |

## Ramas

| Rama | Uso |
|---|---|
| `main` | Producción — GitHub Pages |
| `beta` | Desarrollo |

## Licencia

Contenido personal © José Córdova-Fredes.  
Plantilla: BootstrapMade iPortfolio (licencia BootstrapMade).
