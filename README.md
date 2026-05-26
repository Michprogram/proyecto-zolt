# ZOLT — Energía Natural. Sin compromiso. ⚡🥤

¡Bienvenido al repositorio oficial de **ZOLT**, el prototipo de bebida energética natural e interactiva diseñado para la Quinta Región! Este proyecto nace como una respuesta innovadora, saludable y tecnológica frente al auge desmedido del consumo de estimulantes artificiales en la población juvenil escolar.

## 📌 Contexto del Proyecto

Las bebidas energéticas tradicionales dominan el mercado juvenil mediante agresivas campañas de marketing que asocian sus productos con el rendimiento deportivo, el éxito en los videojuegos (*gaming*) y un estilo de vida dinámico. Sin embargo, la realidad científica detrás de estas latas es alarmante: dosis masivas de cafeína sintética, taurina y azúcares que provocan arritmias, insomnio y el posterior "efecto crash" (bajón severo de energía).

**ZOLT** rompe este paradigma. Es una propuesta de bebida energética alternativa que compite directamente en el mismo terreno de atracción que las marcas tradicionales: tiene gas, un envase metálico de lata con estética urbana/neón y un sabor a maracuyá intensamente ácido. La gran diferencia es que su estímulo proviene 100% de la tierra, entregando energía limpia y real al cuerpo.

---

## 📱 La Solución Tecnológica: Experiencia Phygital (Física + Digital)

Este proyecto no es solo una bebida, es una **intervención sociotécnica**. El flujo de la experiencia del usuario está automatizado a través de dispositivos móviles:

1. **El Producto Físico:** El usuario sostiene una lata prototipo de ZOLT en sus manos.
2. **El Conector (QR):** La lata incluye un código QR integrado en su diseño de etiqueta.
3. **La Experiencia Web (Landing Page):** Al escanear el QR con la cámara del celular, el estudiante es redireccionado de inmediato a una aplicación web interactiva optimizada para móviles (alojada de forma pública en Vercel).
4. **Publicidad Interactiva:** La interfaz web cuenta con animaciones líquidas, un modelo visual inmersivo, datos interactivos de salud y burbujas que simulan el gas del producto, capturando el interés de la generación *Z* a través de la gamificación.

---

## 🛠️ Características Técnicas del Prototipo Web

La plataforma fue desarrollada priorizando la velocidad de carga, la adaptabilidad móvil (*Mobile-First*) y una identidad visual impactante:

* **Arquitectura:** HTML5 semántico, CSS3 avanzado (con variables nativas y animaciones `@keyframes`) y JavaScript Vanilla para el control de eventos.
* **Efectos Visuales Activos:**
  * **Efecto Gas Animado:** Generación dinámica de partículas de burbujas en tiempo real mediante manipulación del DOM con JS.
  * **Scroll Reveal:** Animación síncrona de elementos informativos a medida que el usuario desliza la pantalla con el dedo.
  * **Contadores Dinámicos:** Animación numérica en la sección de estadísticas para destacar los componentes saludables.
* **Diseño UI/UX:** Estética *Dark Mode* con contrastes en verde cian y naranja neón, emulando la energía visual de las marcas comerciales pero canalizada hacia lo natural.

---

## 📂 Estructura del Repositorio

El proyecto mantiene una estructura limpia de archivo único para asegurar un despliegue inmediato y sin fricciones:

```text
├── index.html          # Código fuente principal (Estructura, Estilos CSS y Lógica JS)
└── README.md           # Documentación general del proyecto (Este archivo)
