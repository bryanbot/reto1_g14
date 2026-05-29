# ☕ Bryan De Lama - Dashboard Menu Cards

Este proyecto es la resolución del **Reto 1: Cards de Menú (Grid + Navbar)**. Consiste en una interfaz web moderna para una cafetería de especialidad, maquetada utilizando HTML5 semántico y CSS puro, sin dependencias ni frameworks externos.

---

## 🎯 Objetivos del Reto Cumplidos

- [x] **Estructura Semántica**: Uso de etiquetas `header`, `nav`, `main`, `section` y `article`.
- [x] **Layout Híbrido**: Combinación estratégica de CSS Grid para la distribución espacial y Flexbox para los componentes internos.
- [x] **Diseño Fluido e Imágenes Proporcionales**: Control de deformación de imágenes mediante propiedades modernas de CSS.
- [x] **Responsividad**: Adaptación fluida de 3 columnas en desktop a 1 columna en dispositivos móviles.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructuración semántica y accesible.
- **CSS3 Puro**:
  - **CSS Grid** (`grid-template-columns: repeat(3, 1fr)`) para el contenedor principal de platos.
  - **Flexbox** (`display: flex`) para la barra de navegación y la alineación horizontal de nombres/precios.
  - **Variables CSS** (`:root`) para una gestión limpia de la paleta de colores, espaciados y bordes.
  - **Media Queries** para asegurar la adaptabilidad del diseño.

---

## 📐 Decisiones de Arquitectura y CSS (Layout: Grid vs Flex)

Siguiendo las buenas prácticas de desarrollo frontend, el diseño se dividió bajo la siguiente lógica:

| Componente / Situación | Herramienta CSS | Justificación |
| :--- | :--- | :--- |
| **Grid de Cards (2D)** | `display: grid` | Ideal para manejar filas y columnas simultáneamente de forma simétrica. |
| **Navbar (1D Horizontal)** | `display: flex` | Flujo de elementos en una sola dirección con alineación vertical perfecta. |
| **Fila Nombre + Precio** | `display: flex` | Permite el uso de `justify-content: space-between` para empujar el precio al extremo opuesto. |
| **Control de Imágenes** | `object-fit: cover` | Garantiza que las imágenes mantengan su proporción y llenen el contenedor sin distorsionarse. |

---

## 🚀 Cómo Ejecutar el Proyecto Localmente

1. Clona este repositorio o descarga los archivos `index.html` y `styles.css` en una misma carpeta.
2. Abre el archivo `index.html` en tu navegador web preferido (Chrome, Edge, Firefox, Safari).
3. ¡Listo! Ya puedes previsualizar el resultado.

---

## 🧑‍💻 Autor

- **Tu Nombre** - [@tu_usuario_de_github](https://github.com/tu_usuario)
- Entregado para la comunidad de Discord.
