# 🍕 La Pizzería Gourmet - Página Web Profesional

Una página web moderna y responsive para "La Pizzería Gourmet", diseñada con HTML5, CSS3 y JavaScript vanilla. Perfecta para mostrar pizzas artesanales, menús, testimonios y información de contacto.

## ✨ Características

- **🎨 Diseño Moderno**: Interfaz elegante con paleta de colores cálidos (rojo, dorado, blanco, negro)
- **📱 Totalmente Responsive**: Adaptado a móviles, tablets y escritorio
- **🚀 Performance Optimizada**: Sin frameworks pesados, solo CSS y JavaScript vanilla
- **🎭 Animaciones Suaves**: Efectos de scroll, hover y transiciones fluidas
- **🔍 SEO Optimizado**: Meta tags, estructura semántica y accesibilidad
- **📞 Funcionalidades Interactivas**: Formulario de contacto, botón WhatsApp flotante
- **🎯 Navegación Intuitiva**: Menú hamburguesa para móviles y scroll suave

## 🏗️ Estructura del Proyecto

```
📁 La Pizzería Gourmet/
├── 📄 index.html              # Página principal
├── 📁 assets/
│   ├── 📁 css/
│   │   └── 📄 styles.css      # Estilos principales
│   ├── 📁 js/
│   │   └── 📄 main.js         # Funcionalidades JavaScript
│   └── 📁 images/             # Carpeta para imágenes (opcional)
└── 📄 README.md               # Este archivo
```

## 🚀 Cómo Publicar en GitHub Pages

### Paso 1: Crear un Repositorio en GitHub

1. Ve a [GitHub.com](https://github.com) y inicia sesión
2. Haz clic en el botón verde "New" o "Nuevo"
3. Nombra tu repositorio (ej: `pizzeria-gourmet`)
4. Marca como "Public" (necesario para GitHub Pages)
5. Haz clic en "Create repository"

### Paso 2: Subir el Código

#### Opción A: Usando GitHub Desktop (Recomendado para principiantes)

1. Descarga e instala [GitHub Desktop](https://desktop.github.com/)
2. Clona tu repositorio
3. Copia todos los archivos del proyecto a la carpeta del repositorio
4. En GitHub Desktop, verás los cambios
5. Escribe un mensaje de commit (ej: "Initial commit: Página web de La Pizzería Gourmet")
6. Haz clic en "Commit to main"
7. Haz clic en "Push origin"

#### Opción B: Usando Git desde la Terminal

```bash
# Clonar el repositorio
git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git

# Entrar a la carpeta
cd TU-REPOSITORIO

# Copiar todos los archivos del proyecto aquí

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Initial commit: Página web de La Pizzería Gourmet"

# Subir a GitHub
git push origin main
```

### Paso 3: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en "Settings" (Configuración)
3. En el menú izquierdo, haz clic en "Pages"
4. En "Source", selecciona "Deploy from a branch"
5. En "Branch", selecciona "main" y "/(root)"
6. Haz clic en "Save"
7. Espera unos minutos para que se active

### Paso 4: Acceder a tu Sitio Web

Tu sitio estará disponible en:
```
https://TU-USUARIO.github.io/TU-REPOSITORIO
```

## 🎨 Personalización

### Cambiar Colores

Edita `assets/css/styles.css` y modifica las variables de color:

```css
/* Colores principales */
.btn-primary {
    background: linear-gradient(135deg, #TU-COLOR-1, #TU-COLOR-2);
}

.nav-logo {
    color: #TU-COLOR-LOGO;
}
```

### Cambiar Imágenes

1. Reemplaza las URLs de Unsplash en el HTML con tus propias imágenes
2. O coloca tus imágenes en `assets/images/` y actualiza las rutas

### Cambiar Información de Contacto

Edita `index.html` y actualiza:
- Número de WhatsApp
- Dirección
- Teléfono
- Email
- Horarios

### Cambiar Menú

Modifica la sección del menú en `index.html`:
- Nombres de pizzas
- Descripciones
- Precios
- Imágenes

## 🔧 Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Flexbox, Grid, animaciones y media queries
- **JavaScript ES6+**: Funcionalidades interactivas y efectos
- **Google Fonts**: Tipografías elegantes (Playfair Display, Poppins)
- **Font Awesome**: Iconos vectoriales
- **Unsplash**: Imágenes de alta calidad

## 📱 Características Responsive

- **Mobile First**: Diseño optimizado para móviles
- **Breakpoints**: 480px, 768px y 1200px
- **Menú Hamburguesa**: Navegación adaptativa para móviles
- **Grid Adaptativo**: Layouts que se ajustan automáticamente
- **Imágenes Responsive**: Se adaptan a diferentes tamaños de pantalla

## 🎭 Animaciones y Efectos

- **Scroll Animations**: Elementos aparecen al hacer scroll
- **Hover Effects**: Transiciones suaves en botones y tarjetas
- **Parallax**: Efectos de profundidad sutiles
- **Typing Effect**: Animación de escritura en el título principal
- **Particle System**: Partículas flotantes en el hero

## 📊 SEO y Accesibilidad

- **Meta Tags**: Title, description, keywords y Open Graph
- **Estructura Semántica**: Header, nav, main, section, footer
- **Alt Text**: Descripciones para imágenes
- **ARIA Labels**: Etiquetas para lectores de pantalla
- **Contraste**: Colores con buen contraste para legibilidad

## 🚀 Optimizaciones de Performance

- **CSS Minificado**: Estilos optimizados
- **JavaScript Modular**: Código organizado y eficiente
- **Lazy Loading**: Carga diferida de imágenes
- **Debounce**: Optimización de eventos de scroll
- **Intersection Observer**: API moderna para animaciones

## 🐛 Solución de Problemas

### El sitio no se muestra
- Verifica que el repositorio sea público
- Espera 5-10 minutos después de activar GitHub Pages
- Revisa que el archivo se llame exactamente `index.html`

### Las imágenes no cargan
- Verifica que las URLs de Unsplash sean correctas
- Asegúrate de que las rutas a imágenes locales sean correctas

### El menú móvil no funciona
- Verifica que el archivo `main.js` esté correctamente enlazado
- Revisa la consola del navegador para errores JavaScript

### Los estilos no se aplican
- Verifica que la ruta a `styles.css` sea correcta
- Asegúrate de que el archivo CSS esté en `assets/css/`

## 📞 Soporte

Si tienes problemas o preguntas:

1. Revisa la consola del navegador (F12) para errores
2. Verifica que todos los archivos estén en las carpetas correctas
3. Asegúrate de que GitHub Pages esté activado
4. Revisa que el repositorio sea público

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🙏 Agradecimientos

- **Unsplash** por las imágenes de alta calidad
- **Google Fonts** por las tipografías elegantes
- **Font Awesome** por los iconos vectoriales
- **GitHub** por proporcionar GitHub Pages gratuitamente

---

**¡Disfruta creando tu página web de pizzería! 🍕✨**
