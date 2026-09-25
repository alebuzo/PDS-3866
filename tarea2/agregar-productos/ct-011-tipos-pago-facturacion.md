# Caso de Prueba: Seleccionar tipos de pago y una dirección de facturación distinta

## ID

CT-011

## Objetivo

Verificar que el usuario pueda seleccionar cada tipo de pago disponible y utilizar una dirección de facturación diferente a la dirección de envío.

## Precondiciones

- Usuario registrado y autenticado.
- Existe al menos un producto de cuidado de la piel disponible.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.
- La prueba se detiene después de revisar el resumen, sin confirmar ni enviar el pedido.

## Datos de Entrada

- Producto: Serum Estelar Vitamina C al 7%
- Cantidad: 1.
- Contacto: 88881234.
- Datos de entrega:
  - Nombre: Alexa.
  - Apellido: Carmona.
  - Empresa: Holiday Travel.
  - Dirección1: Distrito Carmen, Calle 1.
  - Dirección2: Apartamento 4B.
  - Ciudad: San José.
  - País/Región: Costa Rica.
  - Provincia: San José.
  - Código Postal: 10101.
  - Teléfono: 88881234.
- Dirección de facturación:
  - Nombre: Alexa.
  - Apellido: Carmona.
  - Dirección1: Avenida Segunda, Edificio Centro.
  - Dirección2: Oficina 12.
  - Ciudad: San José.
  - País/Región: Costa Rica.
  - Provincia: San José.
  - Código Postal: 10102.
  - Teléfono: 88881234.
- Método de envío: Opción de mensajería por correo con precio disponible.
- Tipos de pago: Depósito bancario, pago con tarjeta y SINPE Móvil.
- Propina: Sin propina.

## Pasos

1. Acceder a la tienda e ingresar a la página del producto indicado.
2. Hacer clic en "Añadir al carrito".
3. Abrir el carrito y hacer clic en "Finalizar pedido".
4. Completar el contacto y el formulario de entrega con los datos indicados.
5. Seleccionar un método de envío por correo.
6. Seleccionar "Usar una dirección distinta" en la sección de dirección de facturación.
7. Completar la dirección de facturación con los datos indicados.
8. Seleccionar "Depósito bancario" y verificar que la opción quede seleccionada.
9. Seleccionar "Pago con tarjeta" y verificar que la selección cambie correctamente.
10. Seleccionar "SINPE Móvil" y verificar que la selección cambie correctamente.
11. Revisar el resumen de la compra sin confirmar ni enviar el pedido.

## Resultado Esperado

- Se puede seleccionar cada uno de los tres tipos de pago.
- Solo un tipo de pago permanece seleccionado a la vez.
- La opción "Usar una dirección distinta" permite ingresar la dirección de facturación.
- La dirección de facturación se muestra separada de la dirección de envío.
- El resumen conserva el producto, el método de envío y la dirección de facturación seleccionados.
- No aparecen errores visibles.

## Resultado Obtenido

- Se pudo seleccionar cada uno de los tres tipos de pago.
- Solo un tipo de pago permaneció seleccionado a la vez.
- La opción "Usar una dirección distinta" permitió ingresar la dirección de facturación.
- La dirección de facturación se mostró separada de la dirección de envío.
- El resumen conservó el producto, el método de envío y la dirección de facturación seleccionados.
- No aparecieron errores visibles.


## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones

- Cuando la dirección de envío se pasó a Heredia, la opción de mensajería se actualizó a la opción de envío particular a Heredia, lo que indica que el sistema ajusta las opciones de envío según la ubicación del usuario.