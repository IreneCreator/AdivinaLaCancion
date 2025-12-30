🥂 Adivina el Hit 2024 - Nochevieja Musical

¡Bienvenido a la aplicación definitiva para animar tu fiesta de Nochevieja! Esta es una PWA (Progressive Web App) diseñada para jugar a adivinar canciones por categorías, gestionar puntos por equipos y funcionar totalmente sin conexión (Offline) una vez cargada por primera vez.

🚀 Instalación y Uso Offline

Esta aplicación está optimizada para funcionar en cualquier lugar, incluso sin WiFi:

Primera Carga: Abre la URL de la aplicación (GitHub Pages) mientras tengas conexión a internet.

Instalar en el navegador: En Chrome (Android) o Safari (iOS), selecciona la opción "Añadir a la pantalla de inicio". Esto instalará un acceso directo que funciona como una App nativa.

Sin WiFi: Una vez instalada, puedes abrirla en mitad de las uvas sin miedo a la falta de cobertura. Todos los datos se guardan localmente en tu dispositivo.

🎮 Reglas del Juego

El objetivo es sencillo: los equipos deben adivinar la canción que suene según la categoría sorteada.

💰 Sistema de Puntuación (El Bote)

El juego utiliza un sistema de puntos acumulados (Bote):

Inicio: El bote empieza en 5 puntos.

Aumento: Cada vez que se pulsa el botón "+5", el valor del bote sube.

Degradación Proporcional: Si un equipo falla y quieres dar una oportunidad al siguiente por menos puntos, usa el botón "Degradar".

La resta es automática y justa: si el bote es de 5 resta 1, si es de 10 resta 2, si es de 15 resta 3...

Reset: Pulsa el icono de retorno para volver el bote a 5 puntos rápidamente.

⚡ Todo o Nada

¿Un equipo se siente muy seguro? Pueden jugarse el "Todo o Nada".

Al activar esta opción, los puntos en juego para ese equipo se duplican (x2).

¡Cuidado! Si aciertan ganan el doble, pero si fallan, también pierden el doble.

🛡️ Escudo de Rebote

Cada equipo tiene un indicador de "Escudo Disponible". Úsalo para marcar quién tiene derecho a rebote o para gestionar ventajas especiales durante la partida.

🛠️ Estructura del Código

La aplicación es un único archivo index.html que incluye:

React: Para la interfaz interactiva.

Tailwind CSS: Para el diseño moderno y oscuro.

Lucide Icons: Para la iconografía.

Service Worker: El motor que permite el acceso offline.