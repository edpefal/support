# Página de Soporte - GitHub Pages

Esta es una página de soporte moderna y responsiva diseñada para ser desplegada en GitHub Pages.

## Características

- ✅ Diseño moderno y responsivo
- ✅ Sección de preguntas frecuentes (FAQ) interactiva
- ✅ Formulario de contacto funcional
- ✅ Navegación suave entre secciones
- ✅ Animaciones y efectos visuales
- ✅ Optimizado para dispositivos móviles
- ✅ Compatible con GitHub Pages

## Estructura de archivos

```
support/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interactividad
└── README.md           # Este archivo
```

## Cómo desplegar en GitHub Pages

### Opción 1: Repositorio dedicado

1. Crea un nuevo repositorio en GitHub llamado `tu-usuario.github.io`
2. Sube todos los archivos de este directorio al repositorio
3. Ve a Settings > Pages en tu repositorio
4. Selecciona "Deploy from a branch" y elige "main"
5. Tu página estará disponible en `https://tu-usuario.github.io`

### Opción 2: Subdirectorio en repositorio existente

1. Crea una carpeta llamada `docs` en tu repositorio existente
2. Copia todos los archivos a la carpeta `docs`
3. Ve a Settings > Pages en tu repositorio
4. Selecciona "Deploy from a branch" y elige "main" / "docs"
5. Tu página estará disponible en `https://tu-usuario.github.io/tu-repositorio`

## Personalización

### Cambiar el nombre de la app

1. Edita `index.html` y cambia "Mi App" por el nombre de tu aplicación
2. Actualiza el email de contacto en la sección de contacto
3. Modifica los enlaces de redes sociales en el footer

### Agregar más preguntas frecuentes

1. Edita `index.html`
2. Encuentra la sección `.faq-list`
3. Agrega nuevos elementos `.faq-item` siguiendo la estructura existente

### Cambiar colores y estilos

1. Edita `styles.css`
2. Modifica las variables CSS al inicio del archivo
3. Los colores principales están definidos con valores hexadecimales

## Funcionalidades JavaScript

- **FAQ interactiva**: Los elementos se expanden/contraen al hacer clic
- **Navegación suave**: Scroll suave entre secciones
- **Formulario de contacto**: Validación básica y simulación de envío
- **Header dinámico**: Se oculta/muestra según el scroll
- **Animaciones**: Elementos aparecen con animación al hacer scroll
- **Búsqueda en FAQ**: Campo de búsqueda para filtrar preguntas

## Tecnologías utilizadas

- HTML5 semántico
- CSS3 con Flexbox y Grid
- JavaScript vanilla (ES6+)
- Font Awesome para iconos
- Google Fonts (Inter)

## Compatibilidad

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Dispositivos móviles

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente para tus proyectos.

## Soporte

Si tienes preguntas sobre esta página de soporte, puedes:

1. Revisar la documentación de GitHub Pages
2. Consultar la documentación de HTML/CSS/JavaScript
3. Crear un issue en el repositorio si encuentras algún problema
