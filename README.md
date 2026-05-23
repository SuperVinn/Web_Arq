# Web_Arq

## Descripción
Proyecto de maqueta web educativa para la asignatura de Arquitectura de Computadoras. El sitio presenta un diseño oscuro y moderno, con secciones visuales que permiten comparar conceptos clave y mostrar tutoriales de EMU8086 y Arduino.

> Este proyecto fue creado por Sergio, Ervin y Angel. Nosotros lo estamos desarrollando como parte de la presentación de Arquitectura de Computadoras.

## Objetivo
Crear una interfaz visual limpia y profesional que se pueda presentar en clase como una propuesta de diseño para enseñar:
- Arquitectura vs Organización
- Microprocesador vs Microcontrolador
- Tutorial básico de EMU8086
- Tutorial básico de Arduino

## Archivos del proyecto
- `index.html` — Página de inicio / menú principal con botones que abren páginas dedicadas para cada tema.
- `unidad1.html` — Página dedicada a Arquitectura vs Organización y Microprocesador vs Microcontrolador.
- `emu8086.html` — Página dedicada al tutorial de EMU8086 con caja de código.
- `arduino.html` — Página dedicada al tutorial de Arduino con mapa de pines y ejemplo `.ino`.
- `styles.css` — Estilos CSS que definen el tema oscuro, la tipografía, los paneles y la navegación visual.
- `README.md` — Documentación del proyecto.

## Estructura de la página
### Encabezado
- Título del proyecto
- Descripción corta
- Tarjeta destacada con fecha de entrega

### Sección `Fundamentos`
- Comparativa visual entre Arquitectura y Organización
- Comparativa visual entre Microprocesador y Microcontrolador
- Uso de tarjetas y listas para resaltar ideas clave

### Sección `#emu8086`
- Presentación del tutorial de EMU8086
- Tres pasos de aprendizaje
- Caja de código simulado con ejemplo de ensamblador

### Sección `#arduino`
- Presentación del tutorial de Arduino
- Vista de pines: digital, analógico y alimentación
- Ejemplo de código `.ino`

## Cómo usarlo
1. Abrir `index.html` en un navegador web.
2. Seleccionar el tema deseado con los botones laterales o las tarjetas.
3. Cada botón abre una página dedicada: `unidad1.html`, `emu8086.html` o `arduino.html`.
4. Opcional: editar textos y ejemplos para agregar contenido real del curso.

## Mejoras recomendadas
- Sustituir los textos de ejemplo por contenido técnico real del curso.
- Agregar íconos, diagramas o imágenes de circuitos y microprocesadores.
- Incluir navegación y botones de llamada a la acción.
- Añadir interactividad ligera (hover, transiciones y animaciones suaves).
- Usar más etiquetas semánticas si se expande el proyecto.

## Notas
Este proyecto actualmente es una maqueta de diseño y se enfoca en la presentación visual. La estructura está lista para que otra IA o desarrollador agregue contenido didáctico y ejemplos reales del temario.

## Despliegue en Vercel
1. Conecta este repositorio a Vercel desde el panel de Vercel (https://vercel.com) o usando la CLI.
2. Si usas la CLI, instala Vercel y ejecuta:
   - `npm i -g vercel`
   - `vercel login`
   - `vercel`
3. Vercel detectará este proyecto como un sitio estático y usará `vercel.json` para el despliegue.
4. Después de desplegar, cualquier cambio que empujes al repositorio se podrá actualizar automáticamente si activas los despliegues continuos.
