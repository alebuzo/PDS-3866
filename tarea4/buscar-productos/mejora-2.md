# Mejora 2

## Área

Buscar productos

## Elemento

Filtros de búsqueda

## Descripción del problema

La página muestra resultados para una búsqueda, pero no se observan filtros para acotar la lista. Cuando hay varios productos, encontrar uno que cumpla características concretas puede requerir revisar muchos resultados.

## Objetivo

Facilitar que las personas reduzcan los resultados de búsqueda según características relevantes para encontrar un producto adecuado.

## Descripción de la mejora

Añadir filtros para acotar los resultados por categoría, rango de precio y disponibilidad. Los filtros deben poder combinarse y aplicarse sin perder el término de búsqueda original. Mostrar las selecciones activas para que sea fácil quitarlas o limpiar todos los filtros.

## Elementos nuevos

| Elemento | Comportamiento propuesto |
|---|---|
| **Filtros de resultados** | Permitir filtrar por categoría, rango de precio y disponibilidad. Se pueden evaluar filtros por tipo de piel o necesidad si los datos del catálogo son fiables. |
| **Filtros activos** | Mostrar las opciones seleccionadas y permitir quitar cada una individualmente o limpiarlas todas. |
| **Contador actualizado** | Indicar cuántos productos coinciden después de aplicar los filtros. |
| **Estado sin resultados** | Informar cuando ningún producto coincide con los filtros y ofrecer limpiarlos. |

## Criterios de aceptación

1. El usuario puede filtrar los resultados por categoría, rango de precio y disponibilidad, y combinar esos filtros.
2. Los resultados y su contador se actualizan al aplicar o quitar filtros, sin perder el término de búsqueda.
3. Los filtros activos se identifican claramente y se pueden quitar individualmente o limpiar todos.
4. Si ningún producto coincide, se muestra un mensaje claro y una opción para limpiar los filtros.
5. Los filtros se pueden utilizar con mouse, pantalla táctil y teclado, con foco visible y texto legible en escritorio y móvil.

## Evidencia

![Resultados de búsqueda](image-1.png)

Descripción: La imagen muestra los resultados de búsqueda para el término "aloe", con varias tarjetas de productos y sin filtros visibles para acotar los resultados.