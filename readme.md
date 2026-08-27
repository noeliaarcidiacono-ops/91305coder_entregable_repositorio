# Noeh | Portfolio UX-UI

Portfolio personal de diseño UX-UI desarrollado con HTML, CSS y Bootstrap.

## 🔗 Sitio publicado
https://noeliaarcidiacono-ops.github.io/91305coder_entregable_repositorio/

## 🛠️ Tecnologías
- HTML5
- CSS3 (Grid, Flexbox, Media Queries)
- Bootstrap 5 (Navbar, Carousel)

## 📄 Páginas
- Inicio
- Sobre mí
- Proyectos
- Herramientas
- Contacto

## 🎨 Arquitectura de estilos
Los estilos están organizados en partials SCSS dentro de la carpeta `scss/`:
- `utilities/`: variables y mixins reutilizables
- `base/`: estilos globales y tipografía
- `layout/`: header, nav y footer
- `components/`: cards, botones, formulario, carousel, hero

Para compilar los estilos:
\`\`\`
npm install
npx sass --watch scss/main.scss styles/main.css
\`\`\