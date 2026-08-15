ROL: Actúa como un desarrollador frontend senior especializado en sitios web institucionales con alto estándar de diseño editorial y accesibilidad WCAG 2.1 AA.

CONTEXTO: Estoy construyendo el sitio web de "Diálogo y Desarrollo", una organización peruana dedicada al análisis político y ambiental. El sitio debe transmitir seriedad académica con un diseño moderno y limpio. La audiencia principal son profesionales, académicos y ciudadanos interesados en el acontecer político y medioambiental del Perú.

REQUISITOS FUNCIONALES:
1. HEADER: Navbar fijo con logo ("Diálogo y Desarrollo"), menú de navegación (Inicio, Actualidad, Podcasts, Reportajes, Sobre Nosotros, Contacto), y barra de búsqueda visual. En móvil: menú hamburguesa animado.

2. HERO: Sección de bienvenida con imagen de fondo (Unsplash: naturaleza/perú), título "Análisis para el desarrollo sostenible", subtítulo "Artículos, investigaciones y conversaciones sobre política y medio ambiente en el Perú", y botón CTA "Explorar contenido".

3. SECCIÓN "ÚLTIMAS PUBLICACIONES": Grid de 3 columnas en desktop, 1 en móvil. Cada tarjeta: imagen destacada, categoría (badge colorido), título, extracto de 2 líneas, autor, fecha, tiempo de lectura. Mínimo 6 artículos con datos realistas sobre minería, deforestación, reforma política, etc.

4. SECCIÓN "PODCAST": Reproductor visual de episodios. Cada episodio: título, descripción breve, duración, botón "Escuchar" (simulado).

5. SECCIÓN "REPORTAJES MULTIMEDIA": Galería de imágenes en grid. Cada imagen con título y pie de foto al hacer hover.

6. FOOTER: 4 columnas: (a) Logo + misión, (b) Links rápidos, (c) Categorías, (d) Redes sociales + newsletter. Copyright 2026.

REQUISITOS TÉCNICOS:
- Stack: HTML5 semántico + Tailwind CSS (CDN) + JavaScript vanilla
- NO usar React, Vue ni frameworks JS
- Paleta: verde bosque (#1a472a), azul marino (#0f3460), blanco hueso (#faf9f6), gris oscuro (#2d2d2d), terracota (#c75b39)
- Tipografía: 'Playfair Display' (títulos) y 'Inter' (cuerpo) desde Google Fonts
- Responsive: mobile-first, breakpoints sm(640px), md(768px), lg(1024px), xl(1280px)
- Accesibilidad: contraste WCAG AA, ARIA labels, alt text, focus visible
- SEO: meta description, Open Graph tags, lang="es"

RESTRICCIONES:
- No uses librerías externas de JavaScript
- Animaciones con CSS puro
- Código válido HTML5

FORMATO DE SALIDA: Entrega el código en un único archivo index.html con CSS en <style> y JS en <script>.
