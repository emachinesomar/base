# Perfil de Marca & Recursos Visuales: Kosury Beauty (Daniela)

Este documento sirve como manual de identidad, guía de estilo y mapa de recursos para el sitio web de **Kosury Beauty**, el espacio de bienestar, estética y nutrición fundado por **Daniela**.

---

## 🏛️ 1. Identidad y Filosofía de la Marca
* **Misión:** Ofrecer un equilibrio entre el cuidado estético exterior (tratamientos avanzados de piel y uñas) y la nutrición interior (asesoría y coaching nutricional personalizado), promoviendo la "buena vibra" y el bienestar real.
* **Tono:** Cercano, sofisticado, minimalista, profesional y pacífico.

---

## 🎨 2. Paleta de Colores y Estilo Visual
Para mantener coherencia con el feed de Instagram, la web utiliza estrictamente los siguientes códigos de color en su Tailwind CSS:
* **Fondo Principal (Calma):** `#FAF6F0` (Blanco roto / beige arena muy suave).
* **Color de Acento (Elegancia):** `#C5A89B` (Rosa viejo / Nude apagado para botones, categorías y bordes).
* **Toques Premium (Lujo sutil):** `#D4AF37` (Dorado sutil para estrellas de testimonios e iconos destacados).
* **Texto Principal (Elegante y legible):** `#2D2B2A` (Gris casi negro, más suave para la vista que el negro puro).

---

## 🏛️ 3. Estructura de Secciones de la Web
1. **Cabecera y Navegación:** Logo oficial de la marca, enlaces y botón de reservas. Cuenta con efecto de cristal traslúcido (*glassmorphism*) al hacer scroll y menú móvil interactivo de pantalla completa.
2. **Hero (El Gancho):** Titular enfocado en el cuidado integral y la conexión personal.
3. **Banner de Promoción:** Espacio dinámico para ofertas destacadas de conversión rápida (ej. 2+1 en faciales).
4. **Catálogo de Servicios Interactivo:** Menú dinámico mediante pestañas (*Tabs*) animadas en Javascript para cambiar suavemente entre:
   * 🌸 *Manicura & Pedicura*
   * 💆‍♀️ *Masajes Corporales*
   * ✨ *Cuidado Facial & Mirada*
   * 💫 *Coach Nutricional*
5. **Sobre Daniela:** Sección dedicada a humanizar la marca con su video de presentación y pilares de servicio.
6. **Kosury Boutique:** Un corner de moda deportiva integrada en el espacio estético.
7. **Galería de Resultados:** Mosaico de fotos reales de antes y después con bordes redondeados.
8. **Reserva Online / Tarjetas Regalo:** Tarjetas enlazadas directamente a Booksy y consulta de Gift Cards.
9. **Testimonios:** Reseñas destacadas de Google Reviews/Instagram con calificación de estrellas doradas.
10. **Contacto, Ubicación y Horarios:** Mapa en escala de grises integrado, formulario y enlaces directos a WhatsApp e Instagram.

---

## 🖼️ 4. Mapa de los 10 Recursos Visuales
Todos estos archivos están enlazados directamente en el código de [index.html](file:///c:/Users/Omar/Documents/dev/daniela/base/index.html) con un sistema de **fallback automático** (si la imagen local no existe, se cargará una alternativa estética de Unsplash para evitar elementos rotos).

| # | Recurso (Nombre de Archivo) | Ubicación en la Web | Prompt de Generación para la IA / Descripción |
|---|-----------------------------|---------------------|-----------------------------------------------|
| 1 | `daniela-estetica-home-hero-banner.jpg` | Imagen lateral del Hero | Fondo de página web de alta gama para salón de belleza. Vista interior minimalista y luminosa de un centro de estética moderno: paredes blanco roto, sutiles detalles dorados, orquídeas blancas en un mostrador y luz solar natural difusa. Espacio vacío a la izquierda para insertar texto. |
| 2 | `daniela-estetica-pestanas-pelo-a-pelo.jpg` | Tarjeta: Ext. de Pestañas (Facial) | Primer plano macro del ojo de una mujer con extensiones de pestañas pelo a pelo perfectamente aplicadas y cejas definidas de forma natural. Enfoque nítido en la mirada, piel limpia y radiante, iluminación de estudio suave estilo cosmética de lujo. |
| 3 | `daniela-presentacion-esteticista-profesional.mp4` | Video: Lado izquierdo "Sobre Daniela" | Clip de vídeo corto en bucle cinematográfico. Una esteticista profesional sonriente y amable (uniforme limpio color beige o lila pastel) preparando sutilmente su mesa de trabajo con pinceles y cremas. Transmite confianza, cercanía y alta experiencia. |
| 4 | `daniela-coach-nutricional-salud-bienestar.jpg` | Tarjeta: Valoración Nutricional (Nutrición) | Composición plana (flat lay) estética sobre una mesa de madera clara: una agenda abierta con planes de alimentación, un vaso de agua con rodajas de limón, un aguacate fresco cortado por la mitad y una cinta métrica pastel. Estilo de vida saludable y equilibrado. |
| 5 | `daniela-estetica-pedicura-spa-relajante.jpg` | Tarjeta: Pedicura Completa Spa | Fotografía de un tratamiento de pedicura en progreso. Pies sumergidos en un cuenco de cerámica blanca con agua tibia, pétalos de rosa flotando y rodajas de cítricos. Ambiente de spa relajante, toallas mullidas de fondo. |
| 6 | `daniela-boutique-ropa-deportiva-fitness.jpg` | Imagen: Sección "Kosury Boutique" | Expositor moderno de ropa en una esquina del salón de belleza. Conjuntos de ropa deportiva (crop tops y mallas) ordenados por colores neutros y pasteles en percheros de madera y metal dorado. Concepto de "Belleza, Salud y Moda en un solo lugar". |
| 7 | `daniela-cosmetica-textura-crema-serum.mp4` | Video en Hover: Ext. de Pestañas | Macro-vídeo estético en cámara lenta mostrando un gotero de vidrio aplicando una gota de sérum facial denso y transparente sobre una superficie lisa, reflejando destellos de luz. Transmite hidratación profunda y calidad médica. |
| 8 | `daniela-estetica-pack-iconos-servicios.png` | Icono decorativo general | Conjunto de 4 iconos lineales vectoriales minimalistas en color oro rosa con fondo transparente. Diseños limpios que representen: una uña pintada (manicura), un rostro de perfil (facial), unas manos masajeando una espalda (masajes) y una manzana con una silueta (nutrición). |
| 9 | `daniela-estetica-reserva-online-booksy.jpg` | Fondo Tarjeta: Reserva Online | Imagen desenfocada (bokeh) del mostrador del salón de belleza con una tablet o smartphone elegante mostrando un calendario de citas disponible. La atmósfera es tecnológica pero sofisticada y limpia. |
| 10| `daniela-estetica-tarjeta-regalo-personalizada.jpg` | Fondo Tarjeta: Tarjetas Regalo | Una elegante tarjeta de regalo física impresa ("Gift Voucher") metida en un sobre de papel kraft texturizado con un lazo de cuerda fino. La tarjeta tiene letras doradas sutiles que dicen "Tu momento de bienestar". |

---

## 🛠️ 5. Especificaciones Técnicas y Código
* **Tecnología Principal:** HTML5, CSS3, Tailwind CSS (vía CDN), Vanilla JavaScript.
* **Tipografías:** `EB Garamond` (para titulares de estilo clásico y distinguido) e `Inter` (para textos, duraciones y etiquetas sumamente legibles).
* **Adaptación Failsafe (Respaldo):**
  Las etiquetas `<img>` y `<video>` cuentan con el script `onerror="this.onerror=null; this.src='[URL_UNSPLASH]'"` para garantizar que la web cargue imágenes profesionales por defecto si los archivos locales todavía no se han cargado en el hosting o disco duro.
