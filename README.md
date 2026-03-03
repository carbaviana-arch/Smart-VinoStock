# 🍷 Smart VinoStock
> Gestión de inventario de bodega elegante, rápida y diseñada para dispositivos móviles.

**Smart VinoStock** es una Web App ligera creada para el control de stock de vinos en tiempo real. Olvídate de las hojas de papel y los Excels complicados; gestiona tu bodega con una interfaz premium directamente desde tu smartphone.

---

## ✨ Características Principales

* **📱 Mobile First:** Diseñada específicamente para usarse con una mano mientras recorres la bodega.
* **💎 Interfaz Premium:** Estética *Glassmorphism* con modo oscuro y tipografía elegante.
* **🔍 Buscador Inteligente:** Filtra instantáneamente por nombre de vino, uva o Denominación de Origen.
* **🚨 Alertas de Stock:** Indicadores visuales automáticos cuando una referencia baja de 5 unidades.
* **⚡ GitHub Pages:** Alojamiento gratuito y siempre disponible.

---

## 🛠️ Estructura del Proyecto

El proyecto se compone de tres archivos fundamentales:

1.  `index.html`: El esqueleto y la lógica de la aplicación.
2.  `style.css`: El diseño visual, animaciones y efectos de cristal.
3.  `vinos.json`: La base de datos de tu bodega (fácil de editar).

---

## 🚀 Cómo actualizar el inventario

Para añadir nuevos vinos o cambiar los precios, solo tienes que editar el archivo `vinos.json` con este formato:

```json
{
  "id": 10,
  "nombre": "Nombre del Vino",
  "do": "D.O. Ejemplo",
  "uva": "Tipo de Uva",
  "stock": 12,
  "precio": 25.50
}
📲 Instalación como App (PWA)
Para que Smart VinoStock se comporte como una aplicación nativa en tu móvil:

Abre la URL de tu GitHub Pages en Safari (iOS) o Chrome (Android).

Pulsa el botón Compartir o los tres puntos de opciones.

Selecciona "Añadir a pantalla de inicio".

¡Listo! Ya tienes el icono en tu escritorio sin necesidad de descargar nada de la App Store.

🛠️ Tecnologías utilizadas
HTML5 & JavaScript (ES6+)

Tailwind CSS (Estructura)

CSS3 Custom Properties (Diseño Premium)

FontAwesome (Iconografía)

Google Fonts (Inter & Playfair Display)

Desarrollado con ❤️ para mejorar la eficiencia en el servicio de vinos.

