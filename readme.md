# 🕹️ Neon Web Arcade - SFC Edition

Un emulador web ultra ligero y soberano para revivir la era dorada de los 16-bits directamente desde el navegador. Optimizado para juegos de pelea (SFC/SNES) con soporte nativo para pantallas táctiles en dispositivos móviles y joysticks/teclado en PC.

Este proyecto está diseñado para desplegarse rápidamente a través de **GitHub Pages** y puede ser integrado fácilmente en cualquier blog o plataforma externa.

## 🚀 Características Principales

*   **Zero-Install:** Ejecución 100% en el navegador del cliente sin necesidad de instalar plugins.
*   **Núcleo Optimizado:** Utiliza el core `snes` de EmulatorJS, garantizando máxima compatibilidad y un consumo mínimo de recursos, eliminando la necesidad de archivos BIOS.
*   **Cross-Platform:** 
    *   📱 **Móvil:** Interfaz táctil inmersiva generada automáticamente (D-Pad virtual y botones de acción).
    *   💻 **PC/Desktop:** Soporte plug-and-play para gamepads USB/Bluetooth y mapeo de teclado completo.
*   **Iframe-Ready:** Estilos CSS (`margin: 0; overflow: hidden;`) configurados para un encuadre perfecto al incrustarlo en otras webs.

## 🎮 Controles por Defecto (PC)

Si no se conecta un Joystick, los controles de teclado predeterminados son:

| Acción | Tecla (PC) |
| :--- | :--- |
| **Movimiento (D-Pad)** | `Flechas de Dirección` |
| **Botones de Golpe/Patada** | `Z`, `X`, `C`, `A`, `S`, `D` |
| **Start** | `Enter` |
| **Select** | `Shift Derecho` |

*Nota: Presionando un botón en el menú del emulador en pantalla, el usuario puede remapear sus propios controles de forma local.*

## 🛠️ Instalación y Despliegue (GitHub Pages)

1. Haz un fork o clona este repositorio.
2. Asegúrate de tener en la raíz los siguientes archivos:
   * `index.html` (El reproductor web).
   * `sf2.zip` (La ROM de tu juego en formato ZIP).
3. Ve a la configuración de tu repositorio en GitHub: **Settings > Pages**.
4. En **Build and deployment**, selecciona la rama `main` y guarda.
5. GitHub generará un enlace en vivo (ej. `https://tu-usuario.github.io/tu-repo/`).

## 🌐 Integración Externa (Blogger / Sitios Web)

Para incrustar este emulador en tu blog o en cualquier otro proyecto web, utiliza la siguiente etiqueta HTML:

```html
<iframe src="[https://tu-usuario.github.io/tu-repo/](https://tu-usuario.github.io/tu-repo/)" width="100%" height="600px" frameborder="0" allowfullscreen></iframe>