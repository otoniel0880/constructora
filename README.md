# Página Web - Ing. Ramón Morla

Sitio web profesional para el Ingeniero Civil Ramón Morla.

## 📁 Archivos del Proyecto

```
index.html/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── otoniel.png         # Foto de perfil
├── imagenes/           # Carpeta para imágenes de proyectos
├── roblox_the_crew/    # Juego de Roblox (proyecto adicional)
└── README.md           # Este archivo
```

## 🌐 Contenido de la Página

### Secciones:
1. **Header** - Nombre, título y foto de perfil
2. **Servicios** - Diseño estructural, supervisión y consultoría
3. **Trayectoria** - Experiencia profesional
4. **Proyectos** - Galería de trabajos realizados
5. **Contacto** - Información de contacto
6. **Footer** - Derechos reservados

## 🎨 Características

- ✅ Diseño responsive (se adapta a móviles)
- ✅ Colores profesionales
- ✅ Efectos hover en tarjetas
- ✅ Galería de proyectos con imágenes
- ✅ Foto de perfil circular
- ✅ Gradientes modernos

## 🚀 Cómo Abrir la Página

### Opción 1: Doble Click
- Busca el archivo `index.html`
- Haz doble click

### Opción 2: Desde el Navegador
1. Abre Chrome, Edge o Firefox
2. Presiona `Ctrl + O`
3. Busca: `C:\Users\Desarrollo\Desktop\index.html\index.html`
4. Abre el archivo

### Opción 3: Desde VS Code
1. Presiona `F5`
2. O click derecho en `index.html` → Open with Live Server

### Opción 4: Copiar Ruta
Pega esto en tu navegador:
```
file:///C:/Users/Desarrollo/Desktop/index.html/index.html
```

## 🛠️ Tecnologías Usadas

- **HTML5** - Estructura de la página
- **CSS3** - Estilos y diseño
- **Imágenes** - PNG para perfil, URLs para proyectos

## 📝 Personalización

### Cambiar Información de Contacto
Edita en `index.html` líneas 108-120:
```html
<h3>📧 Escríbeme</h3>
<p>tu-email@ejemplo.com</p>
```

### Cambiar Colores
Edita en `styles.css`:
```css
/* Color principal */
background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%);

/* Color de acento */
background-color: #e67e22;
```

### Agregar Más Proyectos
Copia este bloque en `index.html` dentro de `.project-grid`:
```html
<div class="project-card">
    <img src="tu-imagen.jpg" alt="Descripción">
    <div class="project-info">
        <h3>Nombre del Proyecto</h3>
        <p>Descripción breve</p>
    </div>
</div>
```

## 📸 Cambiar Foto de Perfil

1. Guarda tu nueva foto como `otoniel.png`
2. Colócala en la misma carpeta que `index.html`
3. Recarga la página

## 🐛 Solución de Problemas

**La página no abre:**
- Verifica que `index.html` y `styles.css` estén en la misma carpeta
- Usa la ruta completa: `C:\Users\Desarrollo\Desktop\index.html\index.html`

**No se ven los estilos:**
- Verifica que `styles.css` exista
- Revisa que el link en el HTML sea correcto: `<link rel="stylesheet" href="styles.css">`

**La imagen no carga:**
- Verifica que `otoniel.png` esté en la misma carpeta
- Revisa el nombre del archivo (mayúsculas/minúsculas)

## 📱 Responsive

La página se adapta automáticamente a:
- 📱 Móviles (menos de 768px)
- 💻 Tablets y laptops
- 🖥️ Pantallas grandes

## 📄 Licencia

© 2025 Ing. Ramón Morla. Todos los derechos reservados.

---

**Creado por:** Otoniel  
**Fecha:** Noviembre 2025  
**Versión:** 1.0
