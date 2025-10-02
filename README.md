# 🎮 GTA VI - Fan Website

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

## 🚀 Características

### Diseño y UI/UX
- 🎨 Diseño moderno inspirado en la estética de GTA VI
- 📱 **Responsive Design** - Optimizado para todas las resoluciones desktop (1024px - 4K)
- 🎭 Menú desplegable con animaciones suaves y transiciones elegantes
- 🖼️ Sistema de visualización de personajes y lugares con imágenes dinámicas
- ⚡ Animaciones con GSAP (GreenSock Animation Platform)
- 🎬 Sección de tráilers con previews interactivos
- 📥 Sección de descargas con cards animadas

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
├── tailwind.config.mjs  # Configuración de Tailwind
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
git clone [url-del-repositorio]
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
- Desarrollo Frontend: [Tu Nombre/Organización]
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

Este es un proyecto educativo. Si deseas contribuir con mejoras técnicas:

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

⭐ Si este proyecto te sirvió como inspiración o aprendizaje, considera darle una estrella en GitHub!
