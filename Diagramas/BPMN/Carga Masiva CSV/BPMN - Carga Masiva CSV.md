# BPMN 2 - Carga Masiva CSV

## Objetivo

Permitir la carga masiva de calificaciones tributarias mediante archivos CSV.

## Flujo

1. El usuario inicia sesión mediante SSO.
2. Selecciona un archivo CSV.
3. Previsualiza los datos.
4. El sistema valida el formato y estructura.
5. Si existen errores, el usuario decide si corregir el archivo.
6. Si el archivo es válido, se procesan los registros.
7. Se validan las reglas tributarias.
8. Si existen errores de validación, el usuario decide si corregir la información.
9. Si las reglas son correctas, se guardan las calificaciones.
10. Se registra auditoría.
11. El sistema confirma la carga exitosa.

## Beneficios

- Reduce el ingreso manual.
- Permite validar información antes de almacenarla.
- Mantiene trazabilidad mediante auditoría.
- Facilita la carga masiva de datos tributarios.