# Caso de Prueba: Buscar productos mediante un texto parcial

## ID

CT-008

## Objetivo

Verificar que la barra de búsqueda encuentre productos relacionados cuando el usuario ingresa una parte del nombre del producto.

## Precondiciones

- Usuario con acceso a la tienda.
- Acceso a la página principal de la tienda.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Texto de búsqueda: seru.

## Pasos

1. Acceder a la página principal de la tienda.
2. Hacer clic en el icono de lupa.
3. Ingresar "seru" en la barra de búsqueda.
4. Presionar Enter para ejecutar la búsqueda.

## Resultado Esperado

- Se muestran productos relacionados con serums para el cuidado de la piel.
- Los resultados pueden incluir productos cuyo nombre contenga el término ingresado.
- No aparecen errores visibles.

## Resultado Obtenido

- Se mostraron productos relacionados con serums para el cuidado de la piel.
- Los resultados incluyeron productos cuyo nombre contenía el término ingresado.
- Aparecieron productos que no estaban relacionados con el término buscado.
- No aparecieron errores visibles.

## Estado de la prueba

:red_circle: Fallida

## Observaciones

A pesar de que se mostraron productos relacionados con serums, también aparecieron productos que no estaban directamente relacionados con el término "seru", lo que indica un problema en la precisión del sistema de búsqueda. Puede ser estrategia del negocio para mostrar productos relacionados, pero no cumple con el objetivo de mostrar únicamente productos que coincidan con el término ingresado.