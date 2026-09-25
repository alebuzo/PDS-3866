# Caso de Prueba: Conservar los datos personales después de recargar la página

## ID

CT-002

## Objetivo

Verificar que los datos personales guardados permanezcan disponibles después de recargar la página.

## Precondiciones

- Usuario registrado y autenticado.
- Acceso a la página de datos personales.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Nombre: Mariana
- Apellido: Méndez
- Empresa: Comercio Central
- Dirección1: Calle 5, casa 20
- Dirección2: Barrio Los Ángeles
- Ciudad: Heredia
- País/Región: Costa Rica
- Provincia: Heredia
- Código Postal: 40101
- Teléfono: 87774567
- Fijar dirección por defecto: No

## Pasos

1. Acceder a la página de datos personales.
2. Ingresar los datos indicados en el formulario.
3. Mantener desactivada la opción "Fijar dirección por defecto".
4. Hacer clic en el botón para guardar los cambios.
5. Recargar la página.

## Resultado Esperado

- Los datos guardados se muestran nuevamente después de recargar la página.
- Los valores de los campos permanecen sin cambios.
- La opción "Fijar dirección por defecto" conserva el estado No.
- No aparecen errores visibles.

## Resultado Obtenido

- Los datos guardados se muestran nuevamente después de recargar la página.
- Los valores de los campos permanecen sin cambios.
- La dirección queda fijada como dirección por defecto.
- No aparecen errores visibles.

## Estado de la prueba

:red_circle: Fallida

## Observaciones

- La dirección queda fijada como dirección por defecto a pesar de que la opción "Fijar dirección por defecto" estaba desactivada, lo que indica un comportamiento inesperado del formulario. Lo más probable es que la primera dirección ingresada se fije automáticamente como predeterminada, independientemente de la selección del usuario.

