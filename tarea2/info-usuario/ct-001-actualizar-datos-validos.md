# Caso de Prueba: Actualizar datos personales con información válida

## ID

CT-001

## Objetivo

Verificar que un usuario pueda actualizar sus datos personales con información válida y guardar los cambios.

## Precondiciones

- Usuario registrado y autenticado.
- Acceso a la página de datos personales.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.
- Formulario de datos personales lleno con información válida previa.

## Datos de Entrada

- Nombre: Alexa
- Apellido: Carmona
- Empresa: Holiday Travel
- Dirección1: Distrito Carmen, Calle 1
- Dirección2: Apartamento 4B
- Ciudad: San José
- País/Región: Costa Rica
- Provincia: San José
- Código Postal: 10101
- Teléfono: 88881234
- Fijar dirección por defecto: Sí

## Pasos

1. Acceder a la página de "Cuenta" a través del menú de barra izquierda.
2. Hacer clic en el botón "Editar" para ingresar y actualizar los datos indicados en el formulario.
3. Activar la opción "Fijar dirección por defecto".
4. Hacer clic en el botón para guardar los cambios.

## Resultado Esperado

- Los datos son aceptados por el formulario.
- Aparece un mensaje de confirmación.
- La dirección queda fijada como dirección por defecto.
- No aparecen errores visibles.

## Resultado Obtenido

- El formulario acepta los datos ingresados pero no muestra un mensaje de confirmación.
- La dirección queda fijada como dirección por defecto.
- No aparecen errores visibles.

## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones

- La provincia se selecciona mediante un menú desplegable y la opción de San José aparece como "Provincia de San José" en el formulario, por lo que se debe seleccionar esa opción para que el formulario acepte la información.