# Caso de Prueba: Buscar productos de cuidado de la piel con un término válido

## ID

CT-006

## Objetivo

Verificar que la barra de búsqueda muestre productos relacionados con el término ingresado.

## Precondiciones

- Usuario con acceso a la tienda.
- Acceso a la página principal de la tienda.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Texto de búsqueda: bloqueador.

## Pasos

1. Acceder a la página principal de la tienda.
2. Hacer clic en el icono de lupa.
3. Ingresar "bloqueador" en la barra de búsqueda.
4. Presionar Enter para ejecutar la búsqueda.

## Resultado Esperado

- Se muestran productos relacionados con bloqueadores para el cuidado de la piel.
- Cada producto mostrado contiene información visible para identificarlo.
- No se muestran productos que no estén relacionados con el término buscado.
- No aparecen errores visibles.

## Resultado Obtenido

- Se mostraron productos relacionados con bloqueadores para el cuidado de la piel.
- Cada producto mostrado contenía información visible para identificarlo.
- Después de la primera página de resultados, se mostraron productos que no estaban relacionados con el término buscado.
- No aparecieron errores visibles.

## Estado de la prueba

:red_circle: Fallida

## Observaciones

- Después de la primera página de resultados, se mostraron productos que no estaban relacionados con el término buscado, lo que indica un comportamiento inesperado del sistema de búsqueda. Esto podría deberse a un problema en la lógica de filtrado o en la relevancia de los resultados mostrados. Puede ser parte de la estrategia de la tienda para mostrar productos relacionados, pero no cumple con el objetivo de mostrar únicamente productos que coincidan con el término ingresado.
