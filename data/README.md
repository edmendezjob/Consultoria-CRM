# Datos del proyecto

Esta carpeta está reservada para los datos de apoyo que se incorporen a la consultoría. En esta versión no se incluyen bases de datos de clientes, empleados, ventas ni registros transaccionales.

## Estado actual

- Las cifras que aparecen en `docs/` proceden del documento académico fuente y se tratan como estimaciones o supuestos pendientes de validación.
- No deben interpretarse como un conjunto de datos real ni como resultados auditados de una compañía.
- El documento fuente mezcla unidades de conteo (por ejemplo, empresas clientes y «clientes activos»); no se combinan mientras no se definan.

## Convenciones para futuros archivos

Si se añaden archivos de datos, se recomienda:

1. Utilizar exclusivamente datos sintéticos, agregados o autorizados para publicación.
2. No subir nombres, correos, teléfonos, identificadores, credenciales, información financiera individual ni otros datos confidenciales.
3. Documentar significado de cada campo, unidad, periodo, origen, transformaciones y limitaciones.
4. Separar los datos originales de los datos transformados y de los resultados de análisis.
5. Incluir un aviso de que los datos sintéticos no reflejan necesariamente el comportamiento de una organización real.

No subir archivos sensibles al repositorio para luego confiar en `.gitignore`: una vez publicados, pueden permanecer en el historial de Git aunque se eliminen de la última versión.
