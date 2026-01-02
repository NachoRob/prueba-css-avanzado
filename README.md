# 🎸 Space Odyssey: Guitar Effects & Simulations

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Flexbox](https://img.shields.io/badge/Flexbox-%23563D7C.svg?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

Bienvenido al repositorio de **Space Odyssey**, una landing page de alto rendimiento diseñada para la exploración de efectos y simuladores de guitarra con una estética galáctica y futurista.

## 🌐 Demo en Vivo
**[Ver proyecto en GitHub Pages →](https://nachorob.github.io/Space-Odyssey/)**

---

## 🎯 Objetivo del Proyecto
Este proyecto fue desarrollado como parte del desafío de maquetación avanzada, con un enfoque particular en el control de flujos complejos, diseño responsive y efectos visuales interactivos. Los objetivos principales incluyen:

- **Estructura de Paneles Laterales**: Implementación de un layout dividido mediante Flexbox, separando una navegación lateral persistente de un área de contenido dinámico.
- **Navegación Sticky Adaptable**: Uso de posicionamiento `sticky` en escritorio que se transforma en menú horizontal superior en dispositivos móviles.
- **Optimización de Carga**: Uso de formatos de imagen de última generación (**AVIF**) para garantizar una experiencia de usuario rápida y fluida.
- **Efectos CSS Avanzados**: Transiciones de grayscale a color en imágenes, animaciones sutiles tipo "Star Wars intro" y efectos hover interactivos.
- **Diseño Completamente Responsive**: Media queries implementadas en todas las secciones para adaptarse a tablets y móviles.

## 🚀 Tecnologías y Herramientas

### Frontend
* **HTML5 Semántico**: Estructura clara utilizando etiquetas como `section`, `footer` y divisiones lógicas de contenido.
* **CSS3 Avanzado**: 
    * **Flexbox**: Control total de la cuadrícula de productos, alineación de testimonios y layout principal.
    * **CSS Filters**: Efecto grayscale con transición suave a color en hover.
    * **CSS Transforms**: Escalado y movimiento de elementos en interacciones.
    * **Gradientes y Overlays**: Degradados espaciales y capas semitransparentes para efectos de profundidad.
    * **Animations & Transitions**: Animación fadeInUp para la sección de contacto y transiciones suaves en todos los elementos interactivos.
    * **Media Queries**: Breakpoint en 768px para adaptación completa a dispositivos móviles.
    * **Smooth Scroll**: Navegación interna fluida mediante identificadores de sección (`#ID`).

### Recursos Externos
* **Iconografía**: 
    * **Boxicons** para la interfaz de usuario del menú lateral
    * **Font Awesome** para iconos de redes sociales (Instagram, Facebook, GitHub)
* **Tipografías**: Sistema sans-serif para mantener legibilidad en todos los dispositivos.

## 📱 Estructura de la Landing Page

El diseño se organiza en secciones modulares que se adaptan perfectamente a diferentes tamaños de pantalla:

### 1. **Left Panel / Top Menu**
- **Desktop**: Menú lateral sticky con logo y navegación vertical
- **Mobile**: Se transforma en barra horizontal superior con iconos y texto apilado
- Incluye enlaces a: Effects, Testimonies y Contact Info

### 2. **Effects Gallery**
- Galería de 9 presets de efectos de guitarra organizados en 3 filas
- Imágenes con efecto grayscale que revelan color al hover
- Zoom sutil (scale 1.05) en interacción
- **Responsive**: Se apilan verticalmente en móviles

### 3. **Testimonies Section**
- 3 testimonios con diseño alternado (dark/light)
- Fondos con overlay sobre imagen espacial para mantener coherencia visual
- Citas con icono de comillas estilizado
- **Responsive**: Se apilan verticalmente en móviles con padding reducido

### 4. **Contact Section**
- Diseño inspirado en "intro de Star Wars" con animación fadeInUp
- Información de contacto (email y teléfono) con iconos
- Enlaces a redes sociales: Instagram, Facebook y GitHub
- Fondo espacial con overlay degradado
- **Responsive**: Elementos apilados y tamaños de fuente reducidos

### 5. **Space Footer**
- Footer con imagen de fondo espacial
- Copyright y enlaces a redes sociales
- **Responsive**: Elementos en columna con padding ajustado

## 🎨 Características de Diseño

### Paleta de Colores
- **Fondo principal**: `#0b091a` (azul oscuro espacial)
- **Menú lateral**: Degradado de `#1a1a2e` a `#000000` con toques púrpuras
- **Overlays**: Tonos semitransparentes de azul oscuro y blanco

### Efectos Interactivos
- ✨ **Imágenes**: Grayscale → Color + Zoom al hover
- 🎯 **Links del menú**: Fondo púrpura + desplazamiento a la derecha
- 🌟 **Logo**: Efecto drop-shadow con brillo púrpura
- 📱 **Iconos sociales**: Elevación (translateY) al hover
- 🎬 **Sección contacto**: Aparición suave desde abajo (fadeInUp)

### Responsive Design
```css
@media (max-width: 768px) {
  /* Menú: lateral → horizontal superior */
  /* Galería: 3 columnas → 1 columna */
  /* Testimonios: horizontal → vertical */
  /* Contacto: elementos apilados */
  /* Footer: columna con gap reducido */
}
```

## 🛠️ Instalación y Uso

### Opción 1: Clonar el repositorio
```bash
git clone https://github.com/nachorob/Space-Odyssey.git
cd Space-Odyssey
```

### Opción 2: Descargar ZIP
1. Descarga el archivo ZIP desde GitHub
2. Extrae el contenido en tu carpeta de proyectos

### Visualización
1. Abre el archivo `index.html` en tu navegador
2. O utiliza Live Server en VS Code para desarrollo
3. Prueba el diseño responsive redimensionando la ventana o usando DevTools (F12 → modo dispositivo)

## 📂 Estructura del Proyecto
```
Space-Odyssey/
│
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       ├── logosinfondo.png
│       ├── main-background.avif
│       ├── footer.png
│       └── [presets de efectos]
└── README.md
```

## 🎓 Aprendizajes Clave

Durante el desarrollo de este proyecto se implementaron:

1. **Layout avanzado con Flexbox**: Manejo de paneles sticky y distribución responsive
2. **CSS Filters y Transforms**: Efectos visuales profesionales sin JavaScript
3. **Pseudo-elementos (::before)**: Para overlays y capas de profundidad
4. **Media Queries estratégicas**: Transformación completa del layout para móviles
5. **Animaciones CSS**: Keyframes y transitions para mejorar la experiencia de usuario
6. **Fixed backgrounds**: Parallax sutil con `background-attachment: fixed`
7. **Organización de código**: Estructura clara de HTML semántico y CSS modular

## 🌟 Características Destacadas

- ✅ **100% Responsive**: Funciona perfectamente en desktop, tablet y móvil
- ✅ **Sin JavaScript**: Todas las interacciones con CSS puro
- ✅ **Smooth Scroll nativo**: Navegación fluida entre secciones
- ✅ **Optimización de imágenes**: Formato AVIF para carga rápida
- ✅ **Accesibilidad**: Uso de etiquetas semánticas y aria-labels
- ✅ **Diseño moderno**: Estética espacial/cyberpunk coherente

## 📝 Créditos y Reconocimientos

**Diseñado y desarrollado por**: Ignacio Robles  
**Academia**: Desafío Latam  
**Año**: 2025

---

## 📬 Contacto

Si tienes preguntas o sugerencias sobre este proyecto:

- 📧 Email: ignaciorob86@gmail.com
- 📱 Instagram: [@i_ro_86](https://instagram.com/tu_usuario)
- 💼 GitHub: [@nachorob](https://github.com/nachorob)

---

⭐ Si te gustó este proyecto, considera darle una estrella en GitHub

**[Ver proyecto en vivo →](https://nachorob.github.io/Space-Odyssey/)**