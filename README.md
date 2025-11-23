# 📘 GLORIOSA
### Presentación Web Interactiva 16:9  
**Estrategia de Ventas Institucionales y Sector Público**  
**Librería Al Pie de la Letra**

## 🧭 Descripción General
Gloriosa es una presentación institucional completamente interactiva desarrollada en HTML, CSS y JavaScript Vanilla, diseñada como una herramienta corporativa para capacitaciones en ventas institucionales, sector público, y contratación estatal (SECOP II).

El proyecto implementa una arquitectura visual tipo “mini-app” con navegación lateral, contenedor escalable 16:9, modales dinámicos, tarjetas interactivas, timeline automático y componentes reutilizables.

## 🎯 Objetivos del Proyecto
- Presentación de contenidos institucionales mediante una experiencia interactiva.
- Alternativa moderna a PowerPoint, Keynote o Canva.
- Capacitación en estrategias de relacionamiento, venta institucional y uso de SECOP II.
- Base reusable para futuras presentaciones web profesionales.

## 🖼️ Características Principales
- Diseño moderno y responsivo, con tokens en :root.
- Contenedor escalable 16:9.
- Navegación lateral estilo aplicación.
- Slides temáticos:
  1. Portada  
  2. La Librería  
  3. Ponente  
  4. Estrategias de Relacionamiento  
  5. Sector Público y SECOP II  
  6. Riesgos Críticos  
  7. Cierre
- Modales: normativa, riesgos, checklist, línea de tiempo.
- Flip-cards animadas.
- Timeline generado dinámicamente.
- Checklist con barra de progreso.

## 🛠️ Tecnologías Utilizadas
- HTML5  
- CSS3  
- JavaScript Vanilla  
- Font Awesome 6.4.0  
- Google Fonts (Montserrat + Playfair Display)

## 📁 Estructura del Proyecto
```
/gloriosa
│── index.html
│── /css
│     └── styles.css
│── /js
│     └── app.js
│── /assets
│     └── img/
```

## 🧩 Lógica JavaScript Principal
- `app.goToSlide(index)` – Navegación.
- `app.openTab(index)` – Pestañas internas.
- `app.openModal(id)` / `app.forceClose(id)` – Modales.
- `app.toggleCheck(element)` – Checklist.
- Timeline dinámico basado en `timelineData[]`.

## 🚀 Cómo Usarlo
### Opción 1 — Local
1. Descarga `index.html`.
2. Ábrelo en el navegador.

### Opción 2 — GitHub Pages
1. Sube los archivos al repositorio.
2. En Settings → Pages activa la rama `main`.
3. Abre la URL generada.

## 🧩 Reutilización y Personalización
- Tokens centralizados en `:root`.
- Slides modulares y fáciles de ampliar.
- Componentes reutilizables.
- Animaciones y datasets ampliables.

## 👩‍💻 Autores
**Diseño, Arquitectura Web y Desarrollo**  
**Ana María Ochoa Patiño**  
GitHub: https://github.com/AnaMar-8a  
LinkedIn: https://www.linkedin.com/in/8aanamaria/ 

**Librería Al Pie de la Letra**
