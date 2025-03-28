# Configuración avanzada de I3wm

Esta es una configuración avanzada para el gestor de ventanas **i3wm**, con un diseño atractivo, animaciones, atajos de teclado personalizados y un entorno altamente funcional. Está orientada a ofrecer una experiencia fluida y agradable para usuarios que deseen aprovechar al máximo su escritorio en Linux.

## Características

- **Paleta de colores oscura** con tonos vivos para una mejor experiencia visual.
- **Animaciones suaves** para las ventanas (compositores como `picom`).
- **Atajos personalizados** para la gestión de ventanas y aplicaciones.
- **Conky** para mostrar información en tiempo real sobre el sistema.
- **Aplicaciones y servicios al inicio**, como `nm-applet`, `volumeicon` y más.
- **Integración con `Rofi`** para lanzar aplicaciones con un diseño atractivo.
- **Configuración avanzada de ventanas** con soporte para divisiones (splits) horizontales y verticales, ventanas apiladas y más.

## Requisitos

Antes de usar esta configuración, asegúrate de tener instalados los siguientes programas y herramientas:

- **i3wm**: El gestor de ventanas.
- **picom**: Para animaciones de ventanas y sombras.
- **gnome-keyring-daemon**: Para gestionar las claves.
- **conky**: Para mostrar información del sistema en el escritorio.
- **rofi**: Para lanzar aplicaciones.
- **feh** o **nitrogen**: Para establecer el fondo de pantalla.

### Instalar dependencias

En una distribución basada en Debian/Ubuntu, puedes instalar las dependencias con los siguientes comandos:

```bash
sudo apt update
sudo apt install i3 picom gnome-keyring rofi feh conky nitrogen
