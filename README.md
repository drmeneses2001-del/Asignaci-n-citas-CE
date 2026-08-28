# Solicitud de valoración

Aplicación de una sola página para imprimir, en hoja tamaño carta, la nota de
solicitud de valoración: la leyenda **FAVOR DE VALORAR:** con el servicio, el
médico y la firma seleccionados.

El texto se imprime en la **esquina superior derecha** de la hoja, en el mismo
sentido de lectura del ejemplo, para que el resto del formato quede libre.

## Cómo usarla

1. Abrir `index.html` con doble clic (funciona en Chrome, Edge o Firefox; no
   requiere internet ni instalación).
2. Elegir los tres datos en los combos: **Servicio**, **Médico** y **Firma**.
3. Presionar **Imprimir** y confirmar en el cuadro de impresión del navegador.

En la pantalla se ve una vista previa de la hoja completa, con el texto en el
lugar exacto en que quedará impreso. Los controles (títulos y botones) no se
imprimen.

### Ajustar la posición

En **Ajustar la posición en la hoja** se cambia la separación del borde derecho
y del borde superior, en centímetros, para alinear el texto con el formato
preimpreso. Los valores quedan guardados para la siguiente ocasión.

### Recomendación para el cuadro de impresión

- Tamaño de papel: **Carta** (la página ya lo solicita de forma automática).
- Márgenes: **Predeterminados** o **Ninguno** — la hoja trae sus propios
  márgenes de 2.5 cm.
- Desactivar **Encabezados y pies de página** para que no se impriman la fecha
  ni la dirección del archivo.

## Opciones de los combos

| Servicio | Médico | Firma |
| --- | --- | --- |
| Medicina materno fetal | Dr. Mejía Islas | Dr. Serrano Berrones |
| Clínica de menopausia | Dr. Serrano Berrones | Dr. Meneses Campos |
| Laparoscopia ginecológica | Dr. Apolo Trujillo | |
| Obstetricia | Dr. Pérez Zúñiga | |
| Ginecología vespertino | Dr. Camal Ugarde | |
| | Dra. Luz María Bravo | |
| | Dra. Alejandra López | |

## Cómo modificar las listas

Las opciones están en `index.html`, dentro de los elementos `<select>` con los
identificadores `servicio`, `medico` y `firma`. Basta con agregar, quitar o
editar las líneas `<option>` correspondientes y guardar el archivo.
