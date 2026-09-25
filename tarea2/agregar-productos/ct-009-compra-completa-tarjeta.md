# Caso de Prueba: Llenar el formulario de compra con tarjeta y dirección de facturación igual a la de envío

## ID

CT-009

## Objetivo

Verificar que el usuario pueda elegir un producto, añadirlo al carrito y llenar el formulario de compra usando tarjeta de crédito o débito, sin confirmar el pedido.

## Precondiciones

- Usuario registrado y autenticado.
- Existe al menos un producto de cuidado de la piel disponible.
- El producto tiene precio y opciones de envío disponibles.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.
- La prueba se detiene antes de confirmar o enviar el pedido.

## Datos de Entrada

- Producto: Serum Estelar Vitamina C al 7%
- Cantidad: 1.
- Contacto: alexa.carmona@example.com.
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
- Método de envío: Opción de mensajería estándar.
- Tipo de pago: Pago con tarjeta.
- Dirección de facturación: Misma dirección de envío.
- Propina: Sin propina.

## Pasos

1. Acceder a la tienda e ingresar a la página del producto indicado.
2. Hacer clic en "Añadir al carrito".
3. Abrir el carrito y hacer clic en "Finalizar pedido".
4. Ingresar el correo electrónico o número de teléfono en el campo de contacto.
5. Completar el formulario de entrega con los datos indicados.
6. Seleccionar la opción de mensajería estándar.
7. Seleccionar "Pago con tarjeta" como tipo de pago.
8. Seleccionar "Misma dirección de envío" como dirección de facturación.
9. Mantener la propina sin seleccionar.
10. Revisar el resumen de la compra sin confirmar ni enviar el pedido.

## Resultado Esperado

- El producto se añade correctamente al carrito.
- Se muestra el formulario de compra después de hacer clic en "Finalizar pedido".
- El formulario acepta los datos de contacto y entrega.
- Se aplica el precio correspondiente al método de envío seleccionado.
- La dirección de facturación utiliza la misma dirección de envío.
- El tipo de pago seleccionado es pago con tarjeta.
- El resumen muestra el producto, el envío y el monto total de la transacción.
- El formulario queda listo para continuar, sin confirmar ni enviar el pedido.

## Resultado Obtenido

- El producto se añadió correctamente al carrito.
- Se mostró el formulario de compra después de hacer clic en "Finalizar pedido".
- El formulario aceptó los datos de contacto y entrega.
- Se aplicó el precio correspondiente al método de envío seleccionado.
- La dirección de facturación utilizó la misma dirección de envío.
- El tipo de pago seleccionado fue pago con tarjeta.
- El resumen mostró el producto, el envío y el monto total de la transacción.
- El formulario quedó listo para continuar, sin confirmar ni enviar el pedido.

## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones

