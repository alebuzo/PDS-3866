# Caso de Prueba: Validar un campo obligatorio vacío

## ID

CT-003

## Objetivo

Verificar que el formulario impida guardar los cambios cuando el campo Nombre, requerido, está vacío.

## Precondiciones

- Usuario registrado y autenticado.
- Acceso a la página de datos personales.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Nombre: Vacío
- Apellido: Vargas
- Empresa: Servicios Vargas
- Dirección1: Calle 2, casa 15
- Dirección2: Oficina 3
- Ciudad: Cartago
- País/Región: Costa Rica
- Provincia: Cartago
- Código Postal: 30101
- Teléfono: 86667890
- Fijar dirección por defecto: No

## Pasos

1. Acceder a la página de datos personales.
2. Hacer clic en el botón "Editar" para ingresar o actualizar los datos indicados en el formulario.
3. Dejar vacío el campo "Nombre".
4. Completar los demás campos con los datos indicados.
5. Hacer clic en el botón para guardar los cambios.

## Resultado Esperado

- El formulario muestra un mensaje indicando que el campo "Nombre" es obligatorio.
- Los cambios no se guardan.
- El usuario permanece en la página de datos personales.
- No aparecen errores técnicos visibles.

## Resultado Obtenido

- El formulario no mostró un mensaje de error indicando que el campo "Nombre" es obligatorio.
- Los demás cambios se guardaron correctamente, a pesar de que el campo "Nombre" estaba vacío.
- Aparecen todos los datos excepto el campo "Nombre", que queda vacío.
- No aparecen errores técnicos visibles.

## Estado de la prueba

:red_circle: Fallida

## Observaciones

- Solo aparece "Provincia de Cartago" en el menú desplegable de provincias, por lo que se debe seleccionar esa opción para que el formulario acepte la información.
- El formulario permite guardar los cambios incluso cuando el campo obligatorio "Nombre" está vacío, lo que indica un comportamiento inesperado del formulario. Existe posibilidad de que los campos no sean obligatorios o que el formulario no esté validando correctamente los campos requeridos.

