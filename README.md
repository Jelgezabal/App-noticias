# Muro de Noticias Globales

## Descripción
El **Muro de Noticias Globales** es una aplicación web que muestra las últimas noticias en tiempo real de diversas categorías, obtenidas de la API de **GNews**. 

Las noticias se actualizan automáticamente cada 60 segundos, almacenando hasta **6 noticias** durante **24 horas**. Esto permite que los usuarios puedan ver noticias recientes sin perder información importante.

## Características
✅ Muestra noticias de categorías como:
   - General
   - Internacional
   - Nacional
   - Negocios
   - Tecnología
   - Entretenimiento
   - Deportes
   - Ciencia
   - Salud

✅ **Actualización automática** cada 60 segundos con nuevas noticias.
✅ **Almacenamiento de noticias por 24 horas** en `localStorage`.
✅ **Modo claro y oscuro**, con cambio de tema dinámico.
✅ **Interfaz moderna y responsiva**.

## Instalación y Uso
1. **Descargar el código fuente** o clonar el repositorio:
   ```sh
   git clone https://github.com/jelgezabal/App-noticias.git
   ```
2. **Abrir el archivo `index.html`** en un navegador web.
3. **También puedes verlo en línea aquí**: [Muro de Noticias](https://jelgezabal.github.io/App-noticias/)
4. **¡Listo!** Las noticias se actualizarán automáticamente cada minuto.

## Personalización
Si deseas cambiar la cantidad de noticias almacenadas o el intervalo de actualización:
- **Máximo de noticias almacenadas**: Modifica `slice(0, 6)` en `fetchNews()`.
- **Tiempo de actualización**: Cambia `setInterval(fetchNews, 60000);` para modificar el intervalo en milisegundos.

## Requisitos
Solo necesitas un **navegador web moderno** (Chrome, Firefox, Edge, Safari).

## API Utilizada
- **GNews API**: [https://gnews.io/](https://gnews.io/)

## Contribución
Si deseas mejorar la aplicación, puedes hacer un **fork** del proyecto y enviar un **pull request** con tus cambios.

## Licencia
Este proyecto es de código abierto bajo la licencia MIT.

