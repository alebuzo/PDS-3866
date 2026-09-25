# Smoke Tests para la aplicación de compras de SIBO

## Funcionalidades críticas a probar

1. Modificación de la información del usuario (nombre, dirección física, teléfono y opción de fijar como dirección de envío predeterminada).
2. Buscar productos específicos en la barra de búsqueda.
3. Agregar productos al carrito de compras y llenar el formulario de pago.

## Enlaces a los casos de prueba

### Pruebas de modificación de información del usuario

1. [Actualizar datos personales con información válida](./info-usuario/ct-001-actualizar-datos-validos.md)
2. [Conservar los datos personales después de recargar la página](./info-usuario/ct-002-persistencia-datos.md)
3. [Validar un campo obligatorio vacío](./info-usuario/ct-003-campo-obligatorio-vacio.md)
4. [Cancelar cambios en los datos personales](./info-usuario/ct-004-cancelar-cambios.md)

### Pruebas de barra de búsqueda
1. [Activar y cerrar la barra de búsqueda](./buscar-productos/ct-005-activar-y-cerrar-busqueda.md)
2. [Buscar productos de cuidado de la piel con un término válido](./buscar-productos/ct-006-busqueda-valida.md)
3. [Buscar un producto sin coincidencias](./buscar-productos/ct-007-busqueda-sin-coincidencias.md)
4. [Buscar productos mediante un texto parcial](./buscar-productos/ct-008-busqueda-parcial.md)

### Pruebas de carrito y formulario de compra
1. [Llenar el formulario de compra con tarjeta y dirección de facturación igual a la de envío](./agregar-productos/ct-009-compra-completa-tarjeta.md)
2. [Actualizar el subtotal al cambiar el método de envío](./agregar-productos/ct-010-metodos-envio-subtotal.md)
3. [Seleccionar tipos de pago y una dirección de facturación distinta](./agregar-productos/ct-011-tipos-pago-facturacion.md)
4. [Aplicar porcentajes y propina personalizada](./agregar-productos/ct-012-opciones-propina.md)

## Resumen de resultados de las pruebas

| Resultado | Cantidad |
| --- | ---: |
| Pruebas pasadas | 8 |
| Pruebas no pasadas | 4 |
| Total de pruebas | 12 |

## Política de validación para nuevos despliegues

Estas pruebas de humo se basan en el comportamiento esperado de las funcionalidades actuales de la aplicación. Si se realizan cambios en alguna de ellas, es posible que una prueba falle porque el caso ya no está sincronizado con la versión vigente. Cuando esto ocurra, se deben revisar y actualizar los casos de prueba para reflejar el nuevo comportamiento. Por ejemplo, algunas pruebas fallidas pueden deberse a un desconocimiento de la estrategia de disponibilidad del catálogo de productos, en el que se muestran más opciones que las buscadas por el usuario. Si este comportamiento es intencional, se deben actualizar los casos de prueba para reflejarlo.

Si una prueba falla sin que se hayan realizado cambios en la funcionalidad correspondiente, se debe detener el despliegue y reportar el error al equipo de desarrollo para su corrección.

Las funcionalidades cubiertas son críticas para el funcionamiento de la aplicación. Debido a que estas pruebas son superficiales y se enfocan en casos de uso comunes, se espera que todos los despliegues superen el 100 % de las pruebas.