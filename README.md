# All Remodeling and Painting RG LLC — Website

**Empresa:** All Remodeling and Painting RG LLC  
**Propietario:** Fernando Torres  
**Teléfono:** 813-693-7429  
**Email:** allremodeling.business@gmail.com  
**Área:** Tampa Bay, Florida

---

## Estructura de archivos

```
pagina github/
├── index.html          ← Homepage principal
├── about.html          ← Sobre nosotros / Fernando Torres
├── services.html       ← Todos los servicios detallados
├── quote.html          ← Formulario de cotización gratis
├── contact.html        ← Contacto y redes sociales
├── resources.html      ← Tips, guías y preguntas frecuentes
├── assets/
│   ├── css/
│   │   └── style.css   ← CSS global compartido
│   └── images/         ← Aquí van las fotos de Fernando / proyectos
├── .nojekyll           ← Necesario para GitHub Pages
└── README.md           ← Este archivo
```

## Cómo subir a GitHub Pages

1. Crea un repositorio en github.com (ej: `allremodeling-web`)
2. Sube todos estos archivos (drag & drop o git push)
3. Ve a **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. GitHub te dará una URL tipo: `https://TU-USUARIO.github.io/allremodeling-web/`
5. Cuando tengas tu dominio, en Settings → Pages → Custom Domain, escribe tu dominio

## Fotos recomendadas para agregar (carpeta assets/images/)

- `fernando.jpg` — Foto de Fernando (para about.html)
- `hero-bathroom.jpg` — Foto de baño terminado
- `hero-kitchen.jpg` — Foto de cocina terminada  
- `hero-tile.jpg` — Foto de trabajo de tile
- `hero-painting.jpg` — Foto de pintura exterior/interior
- `logo.png` — Logo si existe

Para usar las fotos, reemplaza el background de los `.hero-slide` en index.html:
```css
.hero-slide:nth-child(1) { background-image: url('assets/images/hero-bathroom.jpg'); }
```
