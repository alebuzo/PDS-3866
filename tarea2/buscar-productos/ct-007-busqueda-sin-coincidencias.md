# Caso de Prueba: Buscar un producto sin coincidencias

## ID

CT-007

## Objetivo

Verificar que la tienda maneje correctamente una búsqueda cuyo texto no corresponde a ningún producto disponible.

## Precondiciones

- Usuario con acceso a la tienda.
- Acceso a la página principal de la tienda.
- Acceso a un navegador actualizado.
- Conexión estable a Internet.

## Datos de Entrada

- Texto de búsqueda: inexistente-987.

## Pasos

1. Acceder a la página principal de la tienda.
2. Hacer clic en el icono de lupa.
3. Ingresar "inexistente-987" en la barra de búsqueda.
4. Presionar Enter para ejecutar la búsqueda.

## Resultado Esperado

- No se muestran productos que no coincidan con el texto buscado.
- Se muestra un mensaje indicando que no hay resultados o productos disponibles.
- La barra de búsqueda permanece disponible para realizar otra búsqueda.
- No aparecen errores técnicos visibles.

## Resultado Obtenido

- Se obtuvo una página que indica "Su búsqueda de "inexistente-987" no tuvo resultados."
- La barra de búsqueda permaneció disponible para realizar otra búsqueda.
- No aparecieron errores técnicos visibles.
- No aparecieron productos que no coincidieran con el texto buscado.

## Estado de la prueba

:white_check_mark: Exitosa

## Observaciones

Un banner extra indica que hay 0 resultados para la búsqueda realizada, lo que confirma que no hay productos disponibles que coincidan con el texto ingresado.