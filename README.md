Orquídea Boutique

Tienda web de demostración para una boutique de ropa y accesorios de mujer. Proyecto de portafolio hecho con HTML, CSS y JavaScript puro, sin frameworks. Los productos, precios y textos son de ejemplo.

Demo: https://stevequispia.github.io/mi-primera-tienda-web/

Tecnologías
HTML semántico, CSS con variables (colores, radios, sombras) y JavaScript puro.
Google Fonts: Bodoni Moda y DM Sans.
Ilustraciones de producto en SVG generadas con JavaScript.
localStorage para guardar el carrito.
Pedidos y consultas mediante enlaces de WhatsApp (wa.me).
Funcionalidades
Menú adaptable a móvil y carrito con contador.
Categorías, búsqueda por nombre, filtros combinables, orden por precio y mensaje sin resultados.
Ventana de detalle de producto (<dialog>) con talla, color y cantidad.
Carrito lateral: cantidades de 1 a 10, subtotal, total, quitar y vaciar, persistente al recargar.
Pedido o reserva por WhatsApp con productos, variantes, total, nombre y notas.
Preguntas frecuentes desplegables, contacto, enlace a Google Maps y año automático en el pie.
Respeta prefers-reduced-motion y tiene foco visible para navegar con teclado.
Cómo ejecutarlo

Abre index.html en el navegador. No necesita instalación. Los datos de la tienda (WhatsApp, dirección, horario) y las preguntas frecuentes se editan en las constantes CFG y FAQ al inicio del <script>.

Pruebas realizadas
Revisión de sintaxis del JavaScript con Node.
18 pruebas automáticas de la lógica con un DOM simulado: filtros, búsqueda combinada, orden, agrupación de variantes, límite de cantidad, total, guardado en localStorage, mensaje de WhatsApp (número, productos, tallas, colores, total, notas) y validaciones del pedido.
Limitaciones conocidas
No hay backend, base de datos, usuarios ni pasarela de pago: la compra termina en WhatsApp.
Sin existencias reales: la disponibilidad se confirma por WhatsApp.
No se ha probado en un navegador real: faltan comprobar consola, diseño en móvil, tableta y escritorio, navegación completa con teclado y lectores de pantalla.
El carrito lateral no atrapa el foco del teclado.
Las ilustraciones SVG son provisionales; conviene sustituirlas por fotos propias optimizadas.
Créditos

Tipografías: Bodoni Moda y DM Sans (Google Fonts, licencia OFL).

Descripción para LinkedIn

Orquídea Boutique es una tienda web de demostración que desarrollé con HTML, CSS y JavaScript puro. Incluye catálogo con búsqueda, filtros y ordenamiento, detalle de producto, carrito persistente con localStorage y pedidos por WhatsApp. Es responsive y cuida la accesibilidad básica. Con este proyecto practiqué manejo del DOM, estado de la aplicación, validación de datos y diseño de interfaces. No usa backend ni pagos reales.

Habilidades que demuestra el código

Maquetación semántica y responsive, CSS con variables, manipulación del DOM, filtrado y ordenamiento de datos, gestión de estado, localStorage con manejo de errores, codificación de URLs, accesibilidad básica y SEO básico.
