# La Genoveva - Carta Digital

Esta es la carta digital interactiva para **La Genoveva - Chichería con Historia**.
El proyecto es una One-Page orientada principalmente a dispositivos móviles con estética premium, diseñada para presentar los platillos, bebidas y chichas de autor del restaurante, preservando la identidad andina y ofreciendo una experiencia moderna.

## Características Principales

*   **Diseño Premium y Responsivo:** Pensado *mobile-first*, garantizando una navegación fluida y sin scroll horizontal. Cuenta con un efecto inicial inmersivo donde la carta se despliega dividiéndose al medio y haciendo zoom al título principal.
*   **Internacionalización (i18n):** Traducción dinámica a 4 idiomas (Español, Inglés, Alemán y Francés). La lógica mantiene las palabras autóctonas ("Chicha", "Mote", "Humita") intactas y traduce únicamente las descripciones, manteniendo el valor cultural.
*   **Interacciones y Animaciones (Micro-interactions):**
    *   *Hover states* unificados con efecto de *glassmorphism* y difuminado (blur) en botones.
    *   **Animación de Maridaje (Scroll Automático):** Al tocar los indicadores de colores en la comida, el usuario es redirigido a la chicha recomendada. Esta resaltará de inmediato con una tenue animación luminosa (respiración) durante un par de segundos.
*   **Integración de Ilustraciones:** Las montañas y paisajes (cerros) están ensamblados armónicamente entre las secciones para imitar el diseño de la carta impresa original.

## Tecnologías Utilizadas

*   **HTML5** semántico.
*   **Tailwind CSS** (vía CDN) extendido con paletas de colores personalizadas de la marca (tonos tierra, beige, vino).
*   **JavaScript (Vanilla):** Para manejar lógica de estado (abrir/cerrar carta), interacciones de *scroll* y el diccionario de traducción multi-idioma.

## Instalación y Uso

Dado que el proyecto utiliza Vanilla JS y CSS, no requiere dependencias pesadas de servidor ni un proceso de build de Node.js.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/agustinbracamonte/lagenoveva-carta.git
   ```
2. Ejecuta un servidor local simple (por ejemplo, con Live Server de VS Code, o utilizando Python):
   ```bash
   npx live-server
   # O en Python:
   python -m http.server 8000
   ```
3. Abre `http://127.0.0.1:8000` o la IP de Live Server en tu navegador para visualizarlo.

## Créditos y Mantenimiento

*   **Identidad y Desarrollo:** Diseñado en conjunto con los lineamientos de la marca de La Genoveva.
*   **Mantenimiento:** *By Consultora Luz* - [consultoraluz.com](https://consultoraluz.com/)
