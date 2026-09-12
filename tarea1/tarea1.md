# Tarea 1: Definición del sistema a probar

## Datos del Sistema

Nombre: Sibö Body Care Supply Co

Página Web: [https://www.sibobodycare.com/](https://www.sibobodycare.com/)

![Logo](./sib-logo.png)

## Propósito del Sistema

El propósito del sistema es permitir a los usuarios comprar productos de cuidado personal y belleza a través de la página web de Sibö Body Care Supply Co desde la comodidad de sus hogares. Su público objetivo son personas interesadas en productos de cuidado personal y belleza de origen costarricense, que buscan una experiencia de compra conveniente y segura en línea. El flujo de uso principal del sistema es el proceso de compra, que incluye la selección de productos, la adición al carrito de compras, elección de método de pago y la confirmación del pedido.

## Lista de Chequeo

### 1. Accesibilidad Inicial y Carga

- ✅ El sitio carga correctamente (sin errores de carga o fallos visibles).
- ✅ El contenido principal aparece rápidamente (menos de 5 segundos).
- ✅ No hay errores evidentes (mensajes técnicos, 404, pantallas en blanco).
- ✅ El sitio es _responsivo_ (se adapta a pantallas móviles/tablets).

### 2. Navegación General

- ✅ El menú principal es visible y funcional.
- ✅ Los enlaces llevan a las páginas correctas.
- ❌ El botón "Inicio" o logo lleva a la página principal. (_El logo solo aparece en algunas páginas, no en todas, pero al hacer click sí lleva a la página principal_)
- ❌ Hay forma de volver atrás fácilmente o de reiniciar una acción (_No hay botón de "regreso" en ninguna página, pero sí se puede usar el botón de "atrás" del navegador_).

### 3. Flujos Críticos

_(Estos dependerán del tipo de sistema, adaptar según el contexto y/o si aplican)_

- ❌ Registro de usuario (campos obligatorios, validación, éxito). (_El registro funciona correctamente; sí hay validación del correo electrónico, pero no hay confirmación de contraseña y la contraseña puede ser débil_)
- ✅ Inicio de sesión / recuperación de contraseña.
- ✅ Cierre de sesión correcto.
- ✅ Creación o envío de datos (formularios, publicaciones, etc.). (_Formulario de dirección de envío y de compra_)
- ✅ Edición de datos existentes (perfil, configuraciones). (_No hay verificación de los espacios de la dirección residencial de envío, pero sí se puede editar el perfil y la dirección de envío_)
- ✅ Proceso de pago / reserva / acción principal del sistema.

### 4. Formularios y Validaciones

- ❌ Los campos requeridos están claramente marcados. (_Los campos opcionales dan error si se dejan vacíos, a pesar de que se indica claramente que son opcionales_)
- ❌ El sistema valida entradas incorrectas (email inválido, números, etc.). (_En el login sí hay validación del correo @, pero no hay validación del código postal en la dirección de envío_)
- ✅ Mensajes de error son comprensibles y útiles. (_Sí hay mensajes de error; los campos se ponen en rojo_)
- ✅ Se pueden corregir errores sin reiniciar todo el formulario. (_El formulario de compra sí se puede corregir; el de registro y login sí se reinicia_)
- ✅ Los mensajes de éxito aparecen correctamente.

### 5. Contenido y Usabilidad

- ✅ Textos sin errores ortográficos o gramaticales.
- ✅ Botones y enlaces tienen nombres claros y consistentes ("Guardar", "Cancelar", etc.).
- ✅ Las acciones del usuario tienen retroalimentación (mensajes, animaciones tipo _loaders_).
- ✅ No se requieren pasos innecesarios o confusos.
- ✅ El sistema es intuitivo sin necesidad de instrucciones externas.

### 6. Compatibilidad Básica

- ✅ Probar en al menos dos navegadores (Chrome, Firefox, Edge, Safari).
- ✅ Probar en dispositivo móvil vs escritorio (modo responsivo o dispositivo real).
- ✅ Probar en resolución más baja (ej. 1024x768) y más alta.

### 7. Manejo de Errores y Casos Límite

- ⚠️ ¿Qué ocurre si el usuario deja todo un formulario vacío? _Los formularios vacíos sí generan un banner de error excepto el de dirección de envío, que no da ningún mensaje de error y permite guardar una dirección vacía._
- ⚠️ ¿Qué pasa si introduce datos absurdos (nombre de 1000 caracteres, símbolos raros)? _El formulario de dirección de envío no genera ningún mensaje de error pero no guarda la dirección con datos absurdos, sino que se guarda una dirección vacía. El formulario de compra sí genera un mensaje de error si se introducen datos absurdos._
- ⚠️ ¿Qué ocurre si se recarga la página durante una acción? _Algunas partes del formulario de compra se borran, otras se mantienen. En el login, si se recarga la página, el usuario es redirigido a la página de login de nuevo con los campos vacíos._
- ⚠️ ¿Cómo responde el sistema si se pierde la conexión a Internet? _La pantalla se queda congelada hasta que se restablece la conexión, no hay mensaje de error ni de reconexión, excepto que el navegador muestre un mensaje de error de conexión total._

### 8. Seguridad básica visible (sin análisis técnico)

- ✅ Las contraseñas no se ven mientras se escriben (excepto si tienen un recurso para poder verlas, e.g. el "ojito").
- ⚠️ No se puede navegar hacia páginas privadas sin haber iniciado sesión. (No aplica, ya que no hay páginas privadas, pero sí hay un perfil de usuario que no se puede acceder sin iniciar sesión)
- ⚠️ El usuario no puede ver información de otros usuarios. (No aplica, ya que no hay información de otros usuarios)
- ✅ Después de cerrar sesión, no puedes volver con el botón "atrás".

### 9. Feedback y Soporte

- ⚠️ Los mensajes de ayuda, tooltips o instrucciones están presentes (si aplica). (_No aplica, no hay mensajes de ayuda ni tooltips; no se consideran necesarios_)
- ✅ Hay términos y condiciones / políticas de privacidad visibles (si aplica).

## 10. Aspecto General y Estabilidad

- ✅ Diseño consistente entre secciones.
- ⚠️ Imágenes y elementos visuales se cargan correctamente. (_Faltan algunas imágenes en el catálogo de productos, pero no afectan la funcionalidad._)
- ✅ El sitio no se desajusta al hacer zoom (Ctrl + o -).
- ✅ No hay "pantallas muertas" sin contenido o acción clara.

