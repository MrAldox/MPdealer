# INVERLUMA &bull; Automotive Dealership & Inventory Management Portal

[![Live Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-brightgreen?logo=github)](https://mraldox.github.io/MPdealer/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Portal web comercial e interactivo para concesionario de vehículos (**Dealer Automotriz**), equipado con catálogo público responsivo con filtros en tiempo real, integración directa con WhatsApp para cotizaciones y panel de administración para control de stock e inventario vehicular.

---

## 🔗 Demo en Vivo

Puedes probar la aplicación directamente en tu navegador sin instalar nada:
👉 **[Ver Demo en GitHub Pages](https://mraldox.github.io/MPdealer/)**

---

## 📌 Tabla de Contenidos

- [Características Principales](#-características-principales)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Funcionalidades de la Aplicación](#-funcionalidades-de-la-aplicación)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Puesta en Marcha Local](#-puesta-en-marcha-local)
- [Licencia](#-licencia)

---

## 🌟 Características Principales

### 1. Portal Público de Clientes (`index.html`)
* **Hero Section:** Presentación de alto impacto visual con diseño moderno y modo oscuro (*Dark Mode*).
* **Filtros Dinámicos en Tiempo Real:** Búsqueda reactiva por marca, modelo, rango de precio, año, kilometraje y tipo de combustible.
* **Ficha Técnica Detallada:** Galería de imágenes, especificaciones de motor, transmisión, tracción y estado.
* **Conversión y Leads:** Enlaces directos a WhatsApp preconfigurados con el modelo específico consultado para agilizar la cotización con el equipo de ventas.

### 2. Panel Administrativo (`admin.html`)
* **Control de Inventario:** Altas, bajas y modificaciones de vehículos en el catálogo.
* **Carga de Imágenes:** Subida y previsualización de fotografías de los vehículos.
* **Estados de Disponibilidad:** Gestión de estados (Disponible, Reservado, Vendido).
* **Métricas y Estadísticas:** Resumen numérico en el sidebar con cantidad de unidades por estado.

---

## 📁 Estructura del Proyecto

```text
MPdealer/
├── index.html       # Portal público para clientes con catálogo y filtros
├── admin.html       # Panel de administración e inventario
├── .gitignore       # Reglas de exclusión para Git
├── LICENSE          # Licencia de código abierto MIT
└── README.md        # Documentación profesional del proyecto
```

---

## 💻 Tecnologías Utilizadas

* **HTML5 Semántico:** Estructura optimizada para accesibilidad y SEO.
* **CSS3 Moderno:** Variables CSS (*Custom Properties*), diseño responsivo con *Flexbox* y *CSS Grid*, efectos de desenfoque (*Glassmorphism*) y tipografías personalizadas (Google Fonts: *Barlow Condensed* e *Inter*).
* **JavaScript ES6+:** Filtrado reactivo de colecciones de objetos, persistencia local con *LocalStorage* y manipulación dinámica del DOM.

---

## 🚀 Puesta en Marcha Local

No requiere de servidores complejos ni instalación de dependencias externas.

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/MrAldox/MPdealer.git
   cd MPdealer
   ```

2. **Abrir en tu navegador:**
   * Haz doble clic en `index.html` para abrir el catálogo de clientes.
   * Abre `admin.html` para ver el panel de administración.
   * O corre un servidor estático rápido con Python:
     ```bash
     python -m http.server 8000
     ```
     y navega a `http://localhost:8000`.

---

## 📄 Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).
Desarrollado por [Eduardo Martinez](https://github.com/MrAldox).
