# Caso de Prueba: Aplicar porcentajes y propina personalizada

## ID

CT-012

## Objetivo

Verificar que el usuario pueda seleccionar los tres porcentajes de propina disponibles o ingresar una propina personalizada, y que el monto de la transacción se actualice correctamente.

## Precondiciones

- Usuario registrado y autenticado.
- Existe al menos un producto de cuidado de la piel disponible.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.
- La prueba se detiene después de revisar el resumen, sin confirmar ni enviar el pedido.

## Datos de Entrada

- Producto: Serum Estelar Vitamina C al 7%.
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
- Método de envío: Opción de mensajería con precio disponible.
- Tipo de pago: SINPE Móvil.
- Dirección de facturación: Misma dirección de envío.
- Propinas: Los tres porcentajes disponibles y propina personalizada de 2500 colones.

## Pasos

1. Acceder a la tienda e ingresar a la página del producto indicado.
2. Hacer clic en "Añadir al carrito".
3. Abrir el carrito y hacer clic en "Finalizar pedido".
4. Completar los campos de contacto y el formulario de entrega con los datos indicados.
5. Seleccionar un método de envío.
6. Seleccionar "SINPE Móvil" como tipo de pago.
7. Seleccionar "Misma dirección de envío" como dirección de facturación.
8. Seleccionar el primer porcentaje (5 %) de propina y registrar el monto mostrado.
9. Seleccionar el segundo porcentaje (10 %) de propina y registrar el monto mostrado.
10. Seleccionar el tercer porcentaje (15 %) de propina y registrar el monto mostrado.
11. Seleccionar "Propina personalizada" e ingresar 2500 colones.
12. Revisar el resumen de la compra sin confirmar ni enviar el pedido.

## Resultado Esperado

- Los tres porcentajes de propina están disponibles para seleccionar.
- Solo una opción de propina permanece seleccionada a la vez.
- El monto de la propina cambia según el porcentaje seleccionado.
- La opción de propina personalizada permite ingresar un monto válido.
- El monto total de la transacción se actualiza al cambiar la propina.
- El resumen muestra el monto de propina seleccionado.
- No aparecen errores visibles.

## Resultado Obtenido

- Los tres porcentajes de propina están disponibles para seleccionar.
- Solo una opción de propina permanece seleccionada a la vez.
- El monto de la propina cambió según el porcentaje seleccionado.
- La opción de propina personalizada permite ingresar un monto válido.
- El monto total de la transacción se actualiza al cambiar la propina.
- El resumen muestra el monto de propina seleccionado.
- No aparecen errores visibles.

## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones

