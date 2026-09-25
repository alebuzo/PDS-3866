# Caso de Prueba: Actualizar el subtotal al cambiar el método de envío

## ID

CT-010

## Objetivo

Verificar que cada método de mensajería aplique su precio correspondiente y que el subtotal de la transacción se actualice al cambiar de opción.

## Precondiciones

- Usuario registrado y autenticado.
- Existe al menos un producto de cuidado de la piel disponible.
- Las cuatro opciones de mensajería están habilitadas y tienen precios diferentes.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.
- La prueba se detiene después de revisar el subtotal, sin confirmar ni enviar el pedido.

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
- Métodos de envío: Las cuatro opciones de mensajería disponibles.
- Tipo de pago: Depósito bancario.
- Dirección de facturación: Misma dirección de envío.
- Propina: Sin propina.

## Pasos

1. Acceder a la tienda e ingresar a la página del producto indicado.
2. Hacer clic en "Añadir al carrito".
3. Abrir el carrito y hacer clic en "Finalizar pedido".
4. Completar los campos de contacto y el formulario de entrega con los datos indicados.
5. Seleccionar la primera opción de mensajería y registrar el subtotal mostrado.
6. Seleccionar la segunda opción de mensajería y registrar el subtotal mostrado.
7. Seleccionar la tercera opción de mensajería y registrar el subtotal mostrado.
8. Seleccionar la cuarta opción de mensajería y registrar el subtotal mostrado.
9. Seleccionar "Depósito bancario" como tipo de pago.
10. Seleccionar "Misma dirección de envío" como dirección de facturación.
11. Revisar el subtotal sin confirmar ni enviar el pedido.

## Resultado Esperado

- Las cuatro opciones de mensajería se muestran con sus precios correspondientes.
- El precio del envío cambia al seleccionar una opción diferente.
- El subtotal de la transacción se recalcula después de cada cambio.
- El subtotal refleja el precio del producto más el costo del método de envío seleccionado.
- La opción de mensajería seleccionada permanece visible en el resumen de compra.
- No aparecen errores visibles.

## Resultado Obtenido

- Los precios se actualizaron correctamente al cambiar de opción de mensajería.
- El subtotal se recalculó correctamente después de cada cambio.
- La opción de mensajería seleccionada permanece visible en el resumen de compra.
- No aparecieron errores visibles.

## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones

