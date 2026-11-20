# D+VINE [LUV] — Traducción al inglés y español

Traducción no oficial y gratuita al **inglés** y **español latinoamericano** de **D+VINE [LUV]** para **Sega Dreamcast**, presentada por **Gyasuke & Wakabayashy Workshop**.

La traducción se distribuye mediante un **parcheador HTML sin conexión para Android y PC**. **No se incluye el juego.** Debes disponer de tus propios archivos japoneses originales de Dreamcast.

**Versión actual:** 0.7.0 V63 — experimental y acumulativa  
**Actualizado:** 20 de noviembre de 2026  
**Idiomas del juego:** inglés y español latinoamericano  
**Interfaz del juego:** inglés en la versión EN y español latinoamericano en la ES, cuando se trate de texto editable  
**Texto integrado en gráficos:** inglés en ambas versiones

## ¿De qué trata el juego?

**D+VINE [LUV]** es un RPG de acción con elementos de novela visual. Sigue a **Hyde**, un joven aventurero que explora unas ruinas misteriosas cerca de **Arvil**. La exploración de mazmorras, los combates contra monstruos, la mejora del equipo y los encuentros con los habitantes de la ciudad permiten descubrir poco a poco los secretos de ese mundo.

## Cambios de V63

- Reflow corregido en **36 registros ingleses y 36 españoles** que contienen pausas y otros controles especiales del guion.
- Corregido el desbordamiento narrativo de Sakura reportado en **SCN366**, donde una palabra se partía entre dos líneas.
- Conservados los comandos originales de pausa, color y control, sin introducir secuencias de paginación cuyo comportamiento no esté verificado.
- Se mantienen las mejoras de V62: eliminación de signos decorativos de apertura y cierre en diálogos y revisión más amplia de la distribución de líneas.
- Se conservan las correcciones anteriores de nombres de personajes, menús, gráficos ingleses y combate.

**Importante:** V63 **no** completa la auditoría global del reflow. Se identificaron más de 800 segmentos con posibles problemas en los dos idiomas. Son **casos de riesgo por investigar, no 800 errores visuales confirmados**.

## Contenido incluido

- Historia, narraciones y diálogos traducidos al inglés y al español latinoamericano.
- Nombres, menús, mensajes del sistema, objetos y descripciones, magia y equipo traducidos, todavía sujetos a revisión editorial.
- **Gráficos traducidos únicamente al inglés**, compartidos por ambas versiones, incluidos los de Configuración y los rótulos de ubicaciones.
- Corrección de la alineación de opciones en los menús, incluido el menú del Gremio de Aventureros con sus cinco opciones separadas.
- Revisión de nombres que aparecen en cajas de contacto de personajes y se almacenan en varios recursos del juego.
- Corrección del **valor de integridad de ITEM.DAT** que impedía causar daño a los enemigos al traducir los textos de los objetos.
- Parcheador HTML independiente con el logo de **Gyasuke & Wakabayashy Workshop**, interfaz bilingüe y selector de idioma del juego por separado.
- **Aplicación sin conexión:** los archivos se procesan en tu dispositivo y no se envían a ningún servidor.

**Distinción entre idiomas:** el idioma de la interfaz del parcheador y el idioma de la traducción del juego son dos opciones diferentes. Los textos editables de la interfaz del juego corresponden a la versión EN o ES elegida. El texto dibujado dentro de recursos gráficos se mantiene en inglés en ambas versiones.

## Instalación

1. **Haz una copia de seguridad** de los archivos japoneses originales y de tus partidas guardadas.
2. Descarga `DVINE_LUV_0.7.0 PARCHEADOR_ANDROID_PC_V63.html` y ábrelo en un navegador actualizado de **Android o PC**. No necesita internet.
3. Selecciona el archivo original y sin modificaciones **`track03.bin`** de tu juego japonés de Dreamcast **v1.002**, procedente del conjunto de pistas `.gdi`.
4. Elige el **idioma de la interfaz del parcheador** (Español o English). Esto **no** cambia el idioma del juego.
5. Elige el **idioma de la traducción**: español latinoamericano o inglés.
6. Pulsa **Verificar y preparar traducción**. Cuando termine la verificación, descarga el nuevo `track03.bin` mediante el enlace que aparecerá en el parcheador.
7. Coloca el archivo traducido en una **copia** de la carpeta del juego, junto con su `.gdi` y las demás pistas originales sin modificar. **No sobrescribas el original limpio.**
8. Abre el `.gdi` de esa copia con **Flycast** u otra configuración compatible con Dreamcast y comprueba el resultado.

**Archivo requerido:** `track03.bin` japonés original de Dreamcast v1.002, con **1.185.760.800 bytes**. El parcheador de PC verifica su SHA-256:

`098bd3f027696c9846d826141c4dfc54c1449798ce0a1cc38efffcb4e65622ae`

**Importante:** empieza **siempre desde el archivo japonés limpio**. Los parches son acumulativos; no apliques V63 sobre V62 ni sobre ningún juego previamente traducido. Un archivo `.chd`, `.cdi`, `.iso` o `.gdi` no reemplaza al `track03.bin` limpio que solicita el parcheador.

### Android y archivos grandes

El archivo de salida ocupa aproximadamente **1,19 GB**. Asegúrate de tener espacio libre suficiente y un navegador capaz de manejar archivos grandes. Mantén abierta la pestaña durante el proceso. En Android, usa el enlace de descarga al finalizar; si el navegador no consigue completar la operación, utiliza el paquete de PC.

## Pruebas y estado del proyecto

**V63 es una versión experimental de pruebas, no un lanzamiento definitivo completamente revisado dentro del juego.**

### Resultados confirmados en el juego

- Se comprobó en **Flycast** que la corrección incorporada en V57 permite volver a causar daño a los enemigos sin perder los objetos traducidos.
- Se confirmó que los gráficos editados de Configuración y del nombre de la posada aparecen correctamente, y que el combate seguía funcionando durante esas pruebas.
- Se confirmó que las **cinco opciones del Gremio de Aventureros** aparecen separadas tras la corrección de alineación de V60.

### Validación de la versión actual

El parcheador V63 reconstruyó las pistas completas en inglés y español desde el disco japonés limpio. Las comprobaciones binarias verificaron registros de guion, estructuras de menú, sumas de los sectores modificados y conservación de las correcciones anteriores. **Estas comprobaciones técnicas no garantizan que todas las cajas de diálogo se vean correctamente durante el juego.**

## Limitaciones conocidas y reportes de errores

- **El reflow todavía está en revisión.** Aproximadamente 808 segmentos de texto temporizado entre EN y ES necesitan investigación adicional; algunos podrían requerir más espacio para páginas o modificaciones específicas del motor.
- Las correcciones nuevas de V63 todavía necesitan **pruebas visuales en Flycast**, especialmente en narraciones, pausas temporizadas y páginas reorganizadas.
- Algunos **valores seleccionados de Configuración** pueden aparecer todavía en japonés en una capa superpuesta, independiente de los gráficos de fondo ya traducidos.
- Las correcciones de nombres de contacto añadidas en V61 y algunas escenas poco frecuentes todavía requieren confirmación dentro del juego.
- Pueden aparecer textos japoneses, desbordamientos, inconsistencias terminológicas u otros fallos. Que el parcheador termine correctamente no significa que toda la partida haya sido probada.

Si encuentras algún problema, envía un reporte con lo siguiente, cuando sea posible:

- La **versión del parche (V63)** y el **idioma del juego (EN/ES)**.
- El emulador y su versión, o la configuración de Dreamcast utilizada.
- El lugar o escena y los pasos necesarios para reproducir el error.
- El diálogo, menú o gráfico afectado, preferiblemente con una captura o un video corto.
- Si ocurre un cierre o bloqueo, los detalles del error y si también sucede con el juego japonés limpio.

Haz una copia de seguridad de tu partida antes de investigar. **No adjuntes copias del juego con derechos de autor a los reportes.**

## Créditos

- **Proyecto, traducción, modificaciones técnicas y presentación del parche:** Gyasuke & Wakabayashy Workshop.

Gracias a todas las personas que ayudan a mejorar las versiones inglesa y española mediante sus pruebas y reportes detallados.

## Aviso legal y distribución

Esta es una **traducción no oficial, gratuita y sin fines comerciales**. No está afiliada, patrocinada ni respaldada por los desarrolladores, distribuidores o titulares de derechos del juego. El juego original, los personajes, las ilustraciones, la música y las marcas pertenecen a sus respectivos propietarios.

**Este parche debe seguir siendo gratuito. No se puede vender ni colocar detrás de un muro de pago. Si alguien te cobra por él, esa venta no está autorizada por el proyecto.**

**No se incluyen imágenes de Dreamcast, BIOS, música ni archivos originales del juego.** El parcheador contiene únicamente datos de modificación. Cada usuario es responsable de obtener y utilizar sus propios archivos de acuerdo con las leyes aplicables.

---

¡Gracias por jugar **D+VINE [LUV]** en inglés o español!
