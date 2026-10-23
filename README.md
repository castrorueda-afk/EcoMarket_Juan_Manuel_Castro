🌿 EcoMarket
📖 Descripción del proyecto

Sitio web de un e-commerce de productos sustentables, desarrollado con HTML5 y CSS3 puro (sin frameworks ni JavaScript). Presenta un catálogo de 20 productos ecológicos para el cuidado personal, el hogar y el estilo de vida, junto con la historia, los valores y las opiniones de clientes de la marca.

Proyecto académico. Los filtros del catálogo son visuales y los testimonios son ficticios.

<img width="1858" height="1009" alt="image" src="https://github.com/user-attachments/assets/cdfc01b9-deb2-4f13-bac8-1a71b6aa12ac" />


El sitio es responsive. A continuación se muestran las vistas principales en escritorio y en móvil.

🖥️ Vista de escritorio
Inicio	Catálogo
<img width="680" height="555" alt="image" src="https://github.com/user-attachments/assets/59a53301-a6b1-4df8-b971-8abf91915de6" />

Inicio en escritorio	Catálogo en escritorio
Detalle de producto	Sobre Nosotros
Detalle en escritorio	Sobre Nosotros en escritorio
Contacto
Contacto en escritorio
📱 Vista móvil
Inicio	Catálogo	Detalle
Inicio en móvil	Catálogo en móvil	Detalle en móvil
Sobre Nosotros	Contacto
Sobre Nosotros en móvil	Contacto en móvil
✨ Características
Catálogo de 20 productos repartido en 2 páginas con paginación.
Barra lateral de filtros por categoría (Cuidado Personal, Hogar y Limpieza, Estilo de Vida).
Página de detalle de producto enlazada desde cada tarjeta.
Página Sobre Nosotros con historia, misión, valores, impacto ambiental y reseñas de clientes.
Formulario de contacto para solicitar productos.
Diseño responsive con CSS Grid y Flexbox.
Accesibilidad básica: enlace "Saltar al contenido", aria-label, aria-current y textos alt descriptivos en todas las imágenes.
Precios en pesos colombianos (COP).
🗂️ Estructura del proyecto
EcoMarket/
├── index.html
├── css/
│   ├── main.css          # Estilos base y variables
│   ├── components.css    # Tarjetas, botones, reseñas, paginación
│   ├── layout.css        # Estructura de páginas y cuadrículas
│   └── animations.css    # Transiciones y animaciones
├── img/
│   └── products/         # Imágenes de los 20 productos
├── docs/
│   └── screenshots/      # Capturas para el README (escritorio y móvil)
└── views/
    ├── productos.html        # Catálogo, página 1
    ├── productos-p2.html     # Catálogo, página 2
    ├── detalle-producto.html # Detalle de cada producto
    ├── sobre-nosotros.html   # Historia, valores, impacto y reseñas
    └── contacto.html         # Formulario de contacto
🚀 Instrucciones de visualización

No requiere instalación ni dependencias.

Opción 1: abrir directamente

Descarga o clona el repositorio.
Abre index.html en tu navegador.

Opción 2: con un servidor local (recomendado)

Con la extensión Live Server de VS Code, haz clic derecho en index.html y elige Open with Live Server. También puedes usar Python:

bash
python -m http.server 8000

y abrir http://localhost:8000.

bash
git clone https://github.com/castrorueda-afk/EcoMarket_Juan_Manuel_Castro.git
cd EcoMarket_Juan_Manuel_Castro
🛍️ Productos
Categoría	Productos
Cuidado personal	Cepillo de bambú, shampoo sólido, acondicionador sólido, desodorante natural, jabón de avena, discos desmaquillantes, esponja de luffa
Hogar	Detox de cocina, detergente en hojas, servilletas de tela, bolsas de silicona, envoltorios de cera de abeja, velas de cera de soja
Estilo de vida	Bolsa tote bag, bolsas de malla, botella térmica, cubiertos de bambú, popotes de acero, vaso plegable, cuaderno reciclado
🖼️ Convención de imágenes

Las imágenes viven en img/products/ y siguen estas reglas para evitar errores de carga, sobre todo en servidores Linux y GitHub Pages, donde se distinguen mayúsculas y minúsculas:

Nombres en minúsculas, separados por guiones.
Sin espacios, tildes ni caracteres especiales.
Extensión real del archivo (.jpg, .png o .webp).

Ejemplo: cepillo-de-bambu.jpg.

🛠️ Tecnologías
HTML5 semántico
CSS3 (Grid, Flexbox, variables CSS, media queries)
🔮 Posibles mejoras
Hacer funcionales los filtros del catálogo.
Carrito de compras y proceso de pago.
Buscador de productos.
Reseñas reales de clientes.
Optimizar las imágenes (por ejemplo, convertir todas a .webp).
👤 Autor

Juan Manuel Castro GitHub: @castrorueda-afk

📄 Licencia

Proyecto con fines educativos. Define aquí la licencia que prefieras (por ejemplo, MIT) si decides publicarlo.
