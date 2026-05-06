# Top Laces - Tarea Evaluativa 7

Top Laces es un proyecto de desarrollo web frontend que simula una tienda online de *sneakers* de lujo y exclusivas. Este proyecto forma parte de la **Tarea Evaluativa del tema 7**, destacándose por su enfoque en una interfaz de usuario premium (UI/UX), animaciones fluidas y un sistema de carrito de compras completamente funcional implementado en Vanilla JavaScript.

## 🚀 Características Principales

*   **Diseño Premium (UI/UX):** Estética moderna utilizando *glassmorphism* (efectos de cristal desenfocado), sombras suaves, y paletas de colores cuidadosamente seleccionadas para transmitir lujo y exclusividad.
*   **Animaciones y Micro-interacciones:**
    *   Botones magnéticos que siguen sutilmente el cursor.
    *   Efectos de aparición gradual (*fade-up*) controlados mediante `IntersectionObserver`.
    *   Contadores numéricos animados en la sección de experiencia.
*   **Sistema de Carrito Dinámico:**
    *   Funcionalidad para añadir y eliminar productos.
    *   Cálculo automático y en tiempo real del precio total.
    *   Contador dinámico de productos en la barra de navegación.
    *   Persistencia de datos utilizando `localStorage` para no perder la selección al navegar.
*   **Filtros de Colección:** Filtrado dinámico de las zapatillas por categoría (Nike/Jordan, Adidas/Yeezy, Off-White).
*   **Flujo de Checkout (Simulación Interactiva):**
    *   Página independiente de pago (`checkout.html`).
    *   Formulario de datos de envío.
    *   Resumen del pedido dinámico sincronizado con el carrito.
    *   Una experiencia de "broma" final al intentar procesar el pago, con animaciones y efectos personalizados (glitch y red-pulse).

## 🛠️ Tecnologías Utilizadas

*   **HTML5:** Estructuración semántica del contenido.
*   **CSS3:** Estilos personalizados modulares (`reset.css`, `global.css`, `components.css`, `animations.css`).
*   **Tailwind CSS (vía CDN):** Framework de utilidades para un desarrollo ágil y responsive. Configuración personalizada inyectada directamente en el `<head>`.
*   **Vanilla JavaScript:** Toda la lógica de DOM, filtrado, cálculos del carrito y almacenamiento local está escrita en JS puro sin frameworks externos.

## 📁 Estructura del Proyecto

```text
TopLaces-Evaluativa7-/
│
├── index.html              # Página principal (Hero, Colección, Carrito lateral)
├── checkout.html           # Página del flujo de pago y resumen del pedido
├── README.md               # Documentación del proyecto
├── nombres.txt             # Lista en bruto de los nombres de los modelos
│
└── assets/                 # Recursos estáticos
    ├── img/                # Imágenes de los productos y la tienda (e.g. Rey_pez.webp)
    └── styles/             # Hojas de estilo CSS modulares
        ├── reset.css
        ├── global.css
        ├── components.css
        └── animations.css
```

## 💻 Instalación y Uso

Dado que es un proyecto puramente estático (Frontend), no requiere instalación de dependencias ni un entorno backend.

1.  Clona o descarga el repositorio en tu máquina local.
2.  Abre el archivo `index.html` en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).
3.  ¡Explora la tienda, añade pares al carrito y procede al pago para descubrir la sorpresa final!

## ✍️ Autores
Fundadores de la empresa (Katya, Johan, Dani, David, Adri F)
