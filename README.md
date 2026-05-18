📡 Simulador de Alineación de Radioenlaces | MigTel Labs 🛜

¡Bienvenido al Simulador de Alineación de Radioenlaces de MigTel! Este es un juego de capacitación técnica interactivo y educativo diseñado especialmente para el personal técnico y de soporte de MigTel.

El objetivo principal es reforzar los conceptos de instalación, orientación y calibración de enlaces inalámbricos de alta frecuencia utilizando una interfaz sumamente fiel a la suite airOS® 8 de Ubiquiti Networks.

📸 Captura del Proyecto

¡Limpio, moderno y claro! Diseñado con la paleta de colores oficial de Ubiquiti airOS 8, simulando el panel de control de un enlace real.

(Puedes colocar una captura de pantalla del juego aquí una vez que lo subas a tu repositorio: ![Captura de pantalla de airOS 8 - MigTel](screenshot.png))

🚀 Características Principales

🎮 10 Niveles Progresivos por Distancia: Cada nivel incrementa la distancia del enlace en saltos de 5 km (desde 5 km hasta 50 km). A mayor distancia, el haz de radiación se vuelve exponencialmente más estrecho, imitando las propiedades físicas de propagación reales.

🎯 Requisitos de Alineación Reales: Para sincronizar y superar un nivel, el operador debe ajustar el Azimut y la Elevación micrométricamente hasta lograr una señal RX estable de entre -38 dBm y -40 dBm durante al menos 3 segundos continuos.

📡 Antena Ubiquiti LiteBeam® 5AC Gen2 Integrada: Renderizada directamente en el visor mediante gráficos vectoriales dinámicos (SVG). Incluye el reflector grid, alimentador de bocina y un LED azul de señal parpadeante para simular actividad de enlace real.

🌤️ Entornos Dinámicos Aleatorios: Fondos adaptativos de alta fidelidad que cambian entre escenarios rurales (Día en el campo con montañas) y urbanos (Noche en la ciudad con siluetas de edificios).

⚡ Telemetría de Alta Resolución (dBm): El display simula fluctuaciones menores de ruido de fondo atmosférico (jitter) y una barra de nivel (vúmetro) de rápida respuesta que cambia de tonalidad según la calidad del espectro (Rojo/Naranja/Verde).

📱 Diseño Ultra Responsivo: Totalmente optimizado para pantallas táctiles de teléfonos inteligentes, tabletas y computadoras de escritorio.

🛠️ Tecnologías Utilizadas

Para garantizar un rendimiento fluido y una compatibilidad total sin necesidad de instalar dependencias pesadas, el juego se desarrolló bajo el estándar de un solo archivo autocontenido (Single-File Web App):

HTML5 para la estructura semántica y maquetación de la interfaz.

Tailwind CSS para un diseño moderno, claro e inspirado fielmente en el dashboard de airOS 8.

SVG Nativo para el renderizado preciso y ligero de la antena LiteBeam 5AC.

Vanilla JavaScript para toda la física del radioenlace, simulación de atenuación geométrica por distancia y cálculo de dBm.

🕹️ Cómo Jugar

Ajuste Grueso: Utiliza las barras de desplazamiento (sliders) de Azimut (Horizontal) y Elevación (Vertical) para mover la cámara rápidamente y encontrar visualmente la antena en el horizonte.

Sintonía Fina (Micrométrica): Cuando estés cerca del objetivo, utiliza los botones de flechas (◄ / ► y ▼ / ▲) para realizar microajustes de 0.5° en 0.5°.

Estabilidad de Enlace: Una vez que el medidor digital marque entre -38.0 y -40.0 dBm, se activará el temporizador de sincronización. No muevas la antena durante 3 segundos para fijar la frecuencia y completar el salto de nivel.

https://diegoporro.github.io/MigTelAntenaGame/

⚙️ Cómo Desplegar en GitHub Pages

Dado que el juego funciona en un solo archivo, publicarlo en internet de manera gratuita para que toda la empresa juegue es facilísimo:

Asegúrate de que el archivo del juego se llame index.html y esté en la raíz de tu repositorio.

En GitHub, ve a la pestaña Settings (Configuración) de tu repositorio.

En el panel izquierdo, haz clic en Pages.

En Build and deployment -> Branch, selecciona la rama main (o master) y la carpeta / (root). Haz clic en Save.

¡Listo! Tu juego estará en vivo en pocos segundos en la dirección:
https://diegoporro.github.io/MigTelAntenaGame/

🏢 Créditos

Desarrollado con pasión para el equipo de ingeniería y operaciones de MigTel.

Soporte y Consultas: soporte@migtel.net.ve ; tecnologia@migtel.net.ve

Tecnología de Simulación: MigTel Labs 2026

Nota: Este software es una herramienta didáctica de simulación lúdica independiente. airOS® y Ubiquiti® son marcas registradas de Ubiquiti Networks, Inc.
