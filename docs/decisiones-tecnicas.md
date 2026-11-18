# Decisiones técnicas

## Automatizar la preparación del presupuesto

Una de las tareas que más trabajo les daba a los vendedores era armar cada presupuesto en distintas herramientas. Integré su preparación en el sistema para reutilizar los datos del cliente, los productos y los servicios, y generar el documento desde esa misma operación.

## Separar las pantallas de las reglas comerciales

Usé JavaFX para la aplicación de escritorio y Spring Boot para los servicios. Las pantallas se ocupan de la interacción con el usuario; el backend procesa las operaciones y guarda la información.

## Vincular el PDF con su presupuesto

Agrupé la creación del presupuesto y la generación del PDF en el mismo flujo. Así, el documento conserva su relación con la operación y puede recuperarse durante el seguimiento comercial.

## Evolucionar sobre el trabajo diario

El sistema ya automatiza tareas de vendedores y administrativos. Las mejoras parten de ese uso: reducir pasos manuales, resolver nuevas necesidades y extender la gestión a otras áreas de Newblock.
