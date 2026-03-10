# 🎮 GTA VI - Fan Website

<p align="center">
  <a href="https://astro.build"><img src="https://img.shields.io/badge/Astro-5.14.1-FF5D01?logo=astro&logoColor=white" alt="Astro"></a>
  <a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind_CSS-4.1.13-06B6D4?logo=tailwind-css&logoColor=white" alt="Tailwind CSS"></a>
  <a href="https://greensock.com/gsap/"><img src="https://img.shields.io/badge/GSAP-3.13.0-88CE02?logo=greensock&logoColor=white" alt="GSAP"></a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-Educational-blue" alt="License"></a>
</p>

<a id="top"></a>

## 🌐 Navegación Rápida / Quick Navigation

- 🇪🇸 [Ir a versión en Español](#es)
- 🇺🇸 [Go to English version](#en)

---

<a id="es"></a>

![gta-vi-website-1](https://github.com/user-attachments/assets/418f8662-5102-4859-942b-a95588ee879b)

> **Proyecto educativo sin fines comerciales**

Un sitio web tributo no oficial de Grand Theft Auto VI, desarrollado con fines educativos para demostrar capacidades de desarrollo web moderno, animaciones avanzadas y diseño responsive.

## ⚠️ Aviso Legal

**Este es un proyecto educativo y de demostración creado exclusivamente con fines de aprendizaje y práctica de desarrollo web.** 

- ❌ **NO es un sitio oficial** de Rockstar Games o Take-Two Interactive
- ❌ **NO tiene afiliación** con Rockstar Games, Take-Two Interactive o cualquier entidad relacionada
- ❌ **NO está destinado a fines comerciales** de ningún tipo
- ✅ Todos los derechos de Grand Theft Auto VI pertenecen a Rockstar Games y Take-Two Interactive
- ✅ Este proyecto es únicamente una demostración técnica de habilidades de desarrollo frontend

Si representas a Rockstar Games o Take-Two Interactive y deseas que este proyecto sea eliminado, por favor contacta y será retirado inmediatamente.

![gta-vi-website-2](https://github.com/user-attachments/assets/e98d0f2c-5260-4812-9ea0-354fdaf0a9e6)

## 🚀 Características

### Diseño y UI/UX
- 🎨 Diseño moderno inspirado en la estética de GTA VI
- 📱 **Responsive Design** - Optimizado para todas las resoluciones desktop (1024px - 4K)
- 🎭 Menú desplegable con animaciones suaves y transiciones elegantes
- 🖼️ Sistema de visualización de personajes y lugares con imágenes dinámicas
- ⚡ Animaciones con GSAP (GreenSock Animation Platform)
- 🎬 Sección de tráilers con previews interactivos
- 📥 Sección de descargas con cards animadas
  
![gta-vi-website-3](https://github.com/user-attachments/assets/a335599e-8111-4709-8729-621d0a0c843a)

### Tecnologías Utilizadas
- **[Astro](https://astro.build)** - Framework web moderno para sitios estáticos
- **[Tailwind CSS](https://tailwindcss.com)** - Framework CSS utility-first
- **[GSAP](https://greensock.com/gsap/)** - Biblioteca de animaciones profesional
- **JavaScript Vanilla** - Para interacciones y lógica del menú

### Características Técnicas
- ⚡ Arquitectura estática optimizada para rendimiento
- 🎯 SEO-friendly
- 🔄 Transiciones suaves con fade in/out controlados
- 📦 Componentes modulares y reutilizables
- 🎨 Sistema de diseño consistente con variables CSS
- 🖱️ Efectos hover avanzados con transformaciones CSS

![gta-vi-website-4](https://github.com/user-attachments/assets/d968855b-232b-4ec3-b817-d535278efbef)

## 📋 Estructura del Proyecto

```
gta-vi-website/
├── src/
│   ├── assets/          # Imágenes, SVGs y recursos visuales
│   ├── layouts/         # Layouts base de Astro
│   └── pages/           # Páginas del sitio
│       └── index.astro  # Página principal
├── public/              # Archivos estáticos
├── astro.config.mjs     # Configuración de Astro
├── package.json         # Dependencias del proyecto
└── README.md           # Este archivo
```

## 🛠️ Instalación y Uso

### Requisitos Previos
- Node.js 18.0 o superior
- npm o yarn

### Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/Fr4n0m/gta-vi-website.git
cd gta-vi-website
```

2. Instala las dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
```

4. Abre tu navegador en `http://localhost:4321`

### Comandos Disponibles

| Comando | Descripción |
|---------|-------------|
| `npm run dev` | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run lint` | Ejecuta validaciones de Astro (`astro check`) |
| `npm run build` | Construye el sitio para producción en `./dist/` |
| `npm run preview` | Vista previa del build de producción |
| `npm run astro` | Ejecuta comandos CLI de Astro |

## 🎨 Características del Diseño

### Hero Section
- Logo animado con efecto de máscara SVG
- Botón de reproducción con animación de escala
- Footer con logo recortado y texto descriptivo
- Animaciones de scroll con GSAP ScrollTrigger

### Menú Navegación
- Menú hamburguesa con animación a cruz
- Panel dividido con imagen de fondo (izquierda) y navegación (derecha)
- **Animaciones secuenciales:**
  1. Panel derecho entra desde la derecha (700ms)
  2. Panel izquierdo aparece con fade in (600ms + 400ms delay)
  3. Logo aparece con fade in (1000ms + 600ms delay adicional)
- Sistema de pestañas: Personajes, Lugares, Tráilers, Descargas
- Efecto hover en personajes/lugares muestra imágenes con transiciones suaves

### Sección Personajes y Lugares
- 8 personajes principales con imágenes individuales
- 6 ubicaciones icónicas del juego
- Textos grandes y bold con tipografía condensada
- Hover states que muestran imágenes a pantalla completa
- Transiciones de opacidad de 1000ms para efectos cinematográficos

### Sección Tráilers
- Cards con previews de video
- Badges "Nuevo" para contenido reciente
- Overlays de play con blur y transparencias
- Duraciones visibles en cada preview
- Hover states con cambio de fondo

### Sección Descargas
- Cards visuales para Vídeos, Capturas y Arte
- Iconos de flecha circular con cambio de color en hover
- Efectos de zoom sutil (99% scale) en las imágenes
- Bordes amarillos que aparecen suavemente en hover (700ms)
- Aumento de brillo en imágenes (brightness-125)
- Botón "Ver todas las descargas" con icono de flecha

### Footer del Menú
- Selector de idioma
- Selector de modo de movimiento
- Iconos SVG personalizados

## 🎯 Responsive Design

El sitio está optimizado para todas las resoluciones de escritorio:

- **1024px - 1279px (lg)**: Tablets landscape y monitores pequeños
- **1280px - 1535px (xl)**: Laptops y monitores estándar
- **1536px+ (2xl)**: Monitores grandes y 4K

Todos los elementos escalan proporcionalmente:
- Textos: 6xl → 7xl → 8xl
- Espaciados: aumentan gradualmente
- Imágenes y contenedores: mantienen proporciones
- Cards de descargas: 200px → 240px → 280px

## 🎨 Paleta de Colores

```css
/* Gradientes principales */
--gradient-left: linear-gradient(135deg, #286074 0%, #523c47 100%)
--gradient-right: linear-gradient(223.17deg, #1b1828 0%, #111117 100%)

/* Colores de acento */
--yellow-accent: #fef3c7
--purple-dark: #36364e
--pink-accent: #cc96bc
```

## 📝 Créditos

### Desarrollo
- Diseño UI/UX: Inspirado en el material oficial de Rockstar Games

### Recursos
- **Imágenes y Assets**: Extraídos de material promocional oficial de GTA VI
- **Tipografías**: Fuentes personalizadas similares a la estética GTA
- **Iconos**: SVG personalizados y optimizados

### Tecnologías
- Astro v5.14.1
- Tailwind CSS v4.1.13
- GSAP v3.13.0

## 🤝 Contribuciones

¿Te gustaría mejorar este proyecto? Los PRs son bienvenidos y ayudan a hacerlo más útil para la comunidad.

- 🛠️ Puedes proponer mejoras de rendimiento, accesibilidad, UI o estructura
- 🧪 Si puedes, añade pruebas o validaciones junto con tus cambios
- 💬 Si tienes dudas, abre primero un issue y lo revisamos

Pasos recomendados:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está creado únicamente con **fines educativos y de demostración**.

**Todos los derechos de propiedad intelectual de Grand Theft Auto VI, su contenido, imágenes, logos y material relacionado pertenecen exclusivamente a:**
- **Rockstar Games**
- **Take-Two Interactive Software, Inc.**

Este proyecto no reclama ningún derecho sobre el contenido de GTA VI y puede ser eliminado bajo petición de los titulares de los derechos.

---

**Recuerda**: Este es un proyecto educativo sin ánimo de lucro creado para practicar y demostrar habilidades de desarrollo web. No está afiliado ni respaldado por Rockstar Games o Take-Two Interactive.

⭐ Si este proyecto te sirvió como inspiración o aprendizaje, considera darle una estrella en GitHub.

🔗 Portfolio: **[Fr4n0m | codebyfran.es](https://codebyfran.es)**

⬆️ [Volver arriba](#top)

---

# 🎮 GTA VI - Fan Website (English)

<a id="en"></a>

![gta-vi-website-1](https://github.com/user-attachments/assets/418f8662-5102-4859-942b-a95588ee879b)

> **Educational project with no commercial purpose**

An unofficial Grand Theft Auto VI tribute website, built for educational purposes to showcase modern web development skills, advanced animations, and responsive design.

## ⚠️ Legal Notice

**This is an educational and showcase project created exclusively for learning and web development practice purposes.**

- ❌ It is **NOT an official website** of Rockstar Games or Take-Two Interactive
- ❌ It has **NO affiliation** with Rockstar Games, Take-Two Interactive, or any related entity
- ❌ It is **NOT intended for any commercial purpose**
- ✅ All Grand Theft Auto VI rights belong to Rockstar Games and Take-Two Interactive
- ✅ This project is only a technical demonstration of frontend development skills

If you represent Rockstar Games or Take-Two Interactive and want this project to be removed, please contact me and it will be taken down immediately.

![gta-vi-website-2](https://github.com/user-attachments/assets/e98d0f2c-5260-4812-9ea0-354fdaf0a9e6)

## 🚀 Features

### Design and UI/UX
- 🎨 Modern design inspired by GTA VI aesthetics
- 📱 **Responsive Design** - Optimized for all desktop resolutions (1024px - 4K)
- 🎭 Dropdown menu with smooth animations and elegant transitions
- 🖼️ Character and location showcase system with dynamic images
- ⚡ GSAP animations (GreenSock Animation Platform)
- 🎬 Trailer section with interactive previews
- 📥 Downloads section with animated cards

![gta-vi-website-3](https://github.com/user-attachments/assets/a335599e-8111-4709-8729-621d0a0c843a)

### Technologies Used
- **[Astro](https://astro.build)** - Modern web framework for static sites
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first CSS framework
- **[GSAP](https://greensock.com/gsap/)** - Professional animation library
- **Vanilla JavaScript** - For interactions and menu logic

### Technical Features
- ⚡ Static architecture optimized for performance
- 🎯 SEO-friendly
- 🔄 Smooth transitions with controlled fade in/out
- 📦 Modular and reusable components
- 🎨 Consistent design system with CSS variables
- 🖱️ Advanced hover effects with CSS transforms

![gta-vi-website-4](https://github.com/user-attachments/assets/d968855b-232b-4ec3-b817-d535278efbef)

## 📋 Project Structure

```text
gta-vi-website/
├── src/
│   ├── assets/          # Images, SVGs and visual resources
│   ├── layouts/         # Base Astro layouts
│   └── pages/           # Website pages
│       └── index.astro  # Main page
├── public/              # Static files
├── astro.config.mjs     # Astro configuration
├── package.json         # Project dependencies
└── README.md            # This file
```

## 🛠️ Installation and Usage

### Prerequisites
- Node.js 18.0 or higher
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Fr4n0m/gta-vi-website.git
cd gta-vi-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser at `http://localhost:4321`

### Available Commands

| Command | Description |
|---------|-------------|
| `npm run dev` | Starts the development server at `localhost:4321` |
| `npm run lint` | Runs Astro checks (`astro check`) |
| `npm run build` | Builds the site for production in `./dist/` |
| `npm run preview` | Previews the production build |
| `npm run astro` | Runs Astro CLI commands |

## 🎨 Design Features

### Hero Section
- Animated logo with SVG mask effect
- Play button with scale animation
- Footer with cut logo and descriptive text
- Scroll animations with GSAP ScrollTrigger

### Navigation Menu
- Hamburger menu with cross animation
- Split panel with background image (left) and navigation (right)
- **Sequential animations:**
  1. Right panel slides in from the right (700ms)
  2. Left panel fades in (600ms + 400ms delay)
  3. Logo fades in (1000ms + additional 600ms delay)
- Tab system: Characters, Places, Trailers, Downloads
- Hover effect on characters/places shows images with smooth transitions

### Characters and Places Section
- 8 main characters with individual images
- 6 iconic game locations
- Large bold text with condensed typography
- Hover states displaying fullscreen images
- 1000ms opacity transitions for cinematic effects

### Trailers Section
- Cards with video previews
- "New" badges for recent content
- Play overlays with blur and transparency
- Visible durations on each preview
- Hover states with background changes

### Downloads Section
- Visual cards for Videos, Screenshots, and Artwork
- Circular arrow icons with color change on hover
- Subtle zoom effects (99% scale) on images
- Yellow borders appearing smoothly on hover (700ms)
- Increased image brightness (brightness-125)
- "View all downloads" button with arrow icon

### Menu Footer
- Language selector
- Motion mode selector
- Custom SVG icons

## 🎯 Responsive Design

The website is optimized for all desktop resolutions:

- **1024px - 1279px (lg)**: Landscape tablets and small monitors
- **1280px - 1535px (xl)**: Laptops and standard monitors
- **1536px+ (2xl)**: Large monitors and 4K

All elements scale proportionally:
- Text: 6xl → 7xl → 8xl
- Spacing: increases gradually
- Images and containers: keep proportions
- Download cards: 200px → 240px → 280px

## 🎨 Color Palette

```css
/* Main gradients */
--gradient-left: linear-gradient(135deg, #286074 0%, #523c47 100%)
--gradient-right: linear-gradient(223.17deg, #1b1828 0%, #111117 100%)

/* Accent colors */
--yellow-accent: #fef3c7
--purple-dark: #36364e
--pink-accent: #cc96bc
```

## 📝 Credits

### Development
- UI/UX Design: Inspired by Rockstar Games official material

### Resources
- **Images and Assets**: Taken from official GTA VI promotional material
- **Typography**: Custom fonts similar to GTA aesthetics
- **Icons**: Custom and optimized SVGs

### Technologies
- Astro v5.14.1
- Tailwind CSS v4.1.13
- GSAP v3.13.0

## 🤝 Contributions

Want to improve this project? PRs are welcome and highly appreciated.

- 🛠️ Feel free to propose performance, accessibility, UI, or architecture improvements
- 🧪 If possible, include tests or validation with your changes
- 💬 Open an issue first if you want to discuss a bigger idea

Recommended flow:

1. Fork the project
2. Create a branch for your feature (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is created only for **educational and showcase purposes**.

**All intellectual property rights of Grand Theft Auto VI, including content, images, logos, and related material belong exclusively to:**
- **Rockstar Games**
- **Take-Two Interactive Software, Inc.**

This project does not claim any rights over GTA VI content and can be removed upon request by the rights holders.

---

**Remember**: This is a non-profit educational project created to practice and showcase web development skills. It is not affiliated with or endorsed by Rockstar Games or Take-Two Interactive.

⭐ If this project helped or inspired you, consider giving it a star on GitHub.

🔗 Portfolio: **[Fr4n0m | codebyfran.es](https://codebyfran.es)**

⬆️ [Back to top](#top)
