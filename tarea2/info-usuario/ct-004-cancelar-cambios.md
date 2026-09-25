# Caso de Prueba: Cancelar cambios en los datos personales

## ID

CT-004

## Objetivo

Verificar que el usuario pueda cancelar modificaciones sin alterar sus datos personales guardados.

## Precondiciones

- Usuario registrado y autenticado.
- El usuario tiene datos personales guardados.
- Acceso a la página de datos personales.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Nombre: Laura
- Apellido: Solís
- Empresa: Datos Originales
- Dirección1: Avenida 3, casa 8
- Dirección2: Local 2
- Ciudad: Alajuela
- País/Región: Costa Rica
- Provincia: Alajuela
- Código Postal: 20101
- Teléfono: 85552468
- Fijar dirección por defecto: No

## Pasos

1. Acceder a la página de "Cuenta" a través del menú de barra izquierda.
2. Hacer clic en el botón "Editar" para ingresar o actualizar los datos indicados en el formulario.
3. Cambiar la opción "Fijar dirección por defecto" a No.
4. Hacer clic en el botón "Cancelar" o salir del formulario sin guardar.
5. Volver a consultar la página de datos personales.

## Resultado Esperado

- El formulario descarta las modificaciones realizadas.
- Los datos personales guardados originalmente permanecen sin cambios.
- No aparece un mensaje de confirmación de guardado.

## Resultado Obtenido

- El formulario descarta las modificaciones realizadas.
- Los datos personales guardados originalmente permanecen sin cambios.
- No hay mensaje de confirmación de guardado.
- No aparecen errores visibles.
- La página redirige correctamente a la sección de datos personales.

## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones


