# isma

Herramientas clínicas para traumatología infantil.

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

- **Médico tratante:** por defecto se imprimen los datos del Dr. Ismael Cañete Campos (objeto `DOCTOR_BASE` en `plantillas.html`). Con el botón "Otro médico" se ingresan nombre, RUT y especialidad; se guardan solo en ese navegador y se recuerda la elección.
- **Lugar de atención:** UC CHRISTUS, Hospital Sótero del Río u "Otro lugar", donde se escribe el nombre de la institución y opcionalmente se sube un logo. La elección también se recuerda en el navegador.
- Firma: a mano sobre la línea, después de imprimir.
- Elementos de la plantilla: arreglo `ELEMENTS` en `plantillas.html`.
