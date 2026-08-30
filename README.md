# Zumia
Zumia es un proyecto para una **actividad de clas**e. El objetivo era crear un pagina de presentación sencilla de un **producto**. La pagina debia ser **responsive** y adaptarse a todas las pantallas. Para ello debiamos crear un **menu hamburguesa**.

## 🎯 Objetivos
- Crear la pagina de un producto.
- Crear el diseño de marca de Zumia.
- Hacerla adaptable a todas las pantallas.
- Crear un menu hamburguesa (desplegable).
- Mejorar mis habilidades en Git y GitHub.
  
## 🛠️ Tecnologías
### FrontEnd
- HTML
- CSS
- JavaScript

### Herramientas
- Visual Studio Code
- Git
- GitHub

## 📁 Estructura del proyecto

├── img/

├── style.css

├── script.js

├── index.html

├── README.md

>La estructura puede cambiar a medida que evoluciona el proyecto.
## 🚀 Instalación y ejecución
Clonar el repositorio: git clone URL_DEL_REPOSITORIO

Acceder al repositorio: git cd developer-profile

>El proyecto puede ejecutarse o modificarse usando **Visual Studio Code**.

## 🍔 Menú hamburguesa

Un menú hamburguesa permite adaptar la navegación a pantallas pequeñas.

## 1. HTML

```html
<button class="menu-toggle">☰</button>

<ul class="menu">
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Productos</a></li>
    <li><a href="#">Contacto</a></li>
</ul>
```

## 2. CSS

```css
.menu-toggle {
    display: none;
}

@media (max-width: 768px) {
    .menu-toggle {
        display: block;
    }

    .menu {
        display: none;
    }

    .menu.active {
        display: flex;
    }
}
```

## 3. JavaScript

```javascript
const button = document.querySelector(".menu-toggle");
const menu = document.querySelector(".menu");

button.addEventListener("click", () => {
    menu.classList.toggle("active");
});
```

**Funcionamiento:**
`☰ → clic → añadir/quitar .active → mostrar/ocultar menú`

## 📌 Estado del proyecto
**🚧 En desarrollo**

Completado.

## 👤 Autora
**Sara Martínez Fernández**

Desarrolladora web | DAW
