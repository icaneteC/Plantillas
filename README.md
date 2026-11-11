# isma

Herramientas clínicas del Dr. Ismael Cañete Campos.

## plantillas.html

Indicación de plantillas ortopédicas con esquema dinámico.

- Datos del paciente (nombre, RUT con validación, edad, diagnóstico).
- Lateralidad: bilateral igual, ambos pies distinto, solo derecho o solo izquierdo.
- Plantillas siempre de largo completo. Elementos con medida en mm: realce posteromedial (cuña), realce posterolateral (tipo Coleman, desde la base del 5° metatarsiano), arco longitudinal medial, barra retrocapital, botón retrocapital, cuña de antepié (medial/lateral) y alza de talón.
- El esquema de la plantilla se actualiza en tiempo real.
- "Generar PDF / Imprimir" abre el diálogo de impresión (tamaño carta). Para PDF, elegir "Guardar como PDF".
- "Limpiar y comenzar de nuevo" borra todo.

No se guarda ni se envía ningún dato del paciente: todo ocurre en el navegador.

### Configuración

- Datos del médico: objeto `DOCTOR` al inicio del script en `plantillas.html`.
- Lugares de atención: arreglo `SEDES` (nombre impreso y logo en `logos/`). La elección se recuerda en el navegador.
- Firma: a mano sobre la línea, después de imprimir.
- Elementos: arreglo `ELEMENTS` en el mismo archivo.
