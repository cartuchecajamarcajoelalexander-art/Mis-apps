# 🚀 Portafolio de Proyectos en GitHub

Sitio web estático e interactivo que consume la API pública de GitHub para mostrar, organizar y enlazar en tiempo real todos mis repositorios y aplicaciones públicas.

🔗 **Demo en vivo:** [Ver página web](https://[tu-usuario].github.io/[nombre-del-repositorio]/)

---

## ✨ Características

- **Sincronización automática:** Obtiene los repositorios públicos directamente desde la API REST de GitHub sin necesidad de actualizar el código manualmente.
- **Vista detallada:** Muestra el nombre del proyecto, descripción, lenguaje principal y enlace directo al código fuente (y a su demo si tiene GitHub Pages activo).
- **Diseño responsivo:** Adaptado para visualizarse correctamente tanto en computadoras de escritorio como en dispositivos móviles.
- **Despliegue ligero:** Construido sin dependencias pesadas para una carga rápida.

---

## 🛠️ Tecnologías utilizadas

- **HTML5** – Estructura semántica del sitio.
- **CSS3** – Estilos y diseño responsivo *(modifica si usaste Tailwind, Bootstrap, etc.)*.
- **JavaScript (Vanilla)** – Consumo de la API de GitHub (`fetch`) y renderizado dinámico del DOM.
- **GitHub Pages** – Alojamiento gratuito y despliegue continuo.

---

## 📂 Estructura del proyecto

```text
├── index.html      # Estructura principal, estilos y lógica de conexión con la API
└── README.md       # Documentación del proyecto
