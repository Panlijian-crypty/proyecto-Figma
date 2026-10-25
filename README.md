# GLOBALTICKET — Segunda entrega

Maquetación de dos pantallas del prototipo de GlobalTicket con HTML5 y CSS3 puro, sin frameworks, librerías ni JavaScript.

## Integrantes y pantallas

| Integrante | Pantalla | Archivo |
| --- | --- | --- |
| Pan Lijian Wong | Crear cuenta | [crear-cuenta.html](crear-cuenta.html) |
| Ariana Belén Recinos Santos | Iniciar sesión | [iniciar-sesion.html](iniciar-sesion.html) |

Las dos pantallas forman parte de la misma entrega y comparten la hoja de estilos y los recursos gráficos.

## Archivos

- `crear-cuenta.html`: pantalla de registro con nombre completo, correo electrónico, contraseña y confirmación de contraseña; es el punto de entrada del proyecto.
- `iniciar-sesion.html`: pantalla de acceso con correo electrónico y contraseña.
- `css/style.css`: única hoja de estilos, compartida por ambas pantallas.
- `img/`: íconos e imágenes locales.
- `GLOBALTICKET.fig`: copia exportada del diseño de Figma de la primera entrega.

Los nombres de los HTML corresponden a las dos pantallas elegidas del flujo. Ambas se enlazan entre sí mediante rutas relativas.

## Cómo visualizarlo

Descarga el repositorio desde **Code → Download ZIP** y extrae la carpeta completa. Ábrela en Visual Studio Code y abre `crear-cuenta.html` o `iniciar-sesion.html` en el navegador. También puedes usar la extensión Live Server.

Desde **Crear cuenta**, pulsa **Inicia sesión** para ver la pantalla de Ariana. Desde **Iniciar sesión**, pulsa **Regístrate** para volver a la pantalla de Lijian. Conserva las carpetas `css/` e `img/` junto a los HTML. No se necesitan instalaciones ni comandos para visualizar las páginas.

## Layout y responsive

Se utiliza **Grid** para la estructura general y las columnas del encabezado, y **Flexbox** para los formularios, botones y pie de página. La hoja de estilos contiene tres media queries:

| Vista | Ancho |
| --- | --- |
| Celular | Hasta 767 px |
| Tablet | De 768 a 1023 px |
| Escritorio | Desde 1024 px |

Son pantallas de maquetación: los botones de los formularios y el buscador no procesan datos. Los textos informativos del pie de página no abren otras pantallas.

## Figma de la primera entrega

[Ver el prototipo GLOBALTICKET](https://www.figma.com/design/3TBiqYwUL7tHbOsB83UG1l).
