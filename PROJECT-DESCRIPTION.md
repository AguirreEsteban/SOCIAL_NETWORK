
##Otra plataforma social

En este proyecto, se espera que diseñes e implementes una aplicación de plataforma social que se ejecute en los navegadores web. En primer lugar, vamos a empezar con los componentes del proyecto.

## Componentes

### 1. Backend

El componente Backend es responsable de la gestión del estado de la aplicación. Por estado de la aplicación, nos referimos a los usuarios actuales en la aplicación, sus habilidades, acciones realizadas, etc.

### 2. Frontend
El componente Frontend es donde el usuario interactúa con la aplicación, por lo tanto, es la interfaz de usuario (UI). 

### 3. Usuario
El componente de usuario es el principal actuador que hace que las acciones sean tomadas por otros componentes.

## Requerimientos
En esta sección, se describen las características esperadas en el proyecto y sus funcionalidades.

### 1. Usuario
* 1.1 Autenticación
  * 1.1.1 El usuario debe poder registrarse en la aplicación con un correo electrónico y una contraseña.
  * 1.1.2 El usuario debe ser capaz de iniciar sesión en la aplicación con el correo electrónico y la contraseña especificada en el registro.
  * 1.1.3 El usuario podrá restablecer su propia contraseña asociada al correo electrónico.
  * 1.1.4 El usuario deberá validarse a sí mismo visitando el enlace en el correo que recibió después de registrarse.
* 1.2 Perfil
  * 1.2.1 El usuario podrá subir una imagen para su perfil.
  * 1.2.2 El usuario podrá especificar la descripción, la fecha de nacimiento y las aficiones para los detalles de su perfil.
  * 1.2.3 El usuario podrá ver el número de seguidores y seguidos en su página de perfil.
* 1.3 Seguimiento
  * 1.3.1 El usuario podrá seguir a otro usuario.
  * 1.3.2 El usuario podrá dejar de seguir a otro usuario que ya esté siendo seguido por él.
  * 1.3.3 Otros usuarios podrán mostrar la página de perfil del usuario.
* 1.4 Publicar
  * 1.4.1 El usuario deberá tener una página llamada Posts donde podrá ver los posts que pertenecen a los usuarios que ya está siguiendo.
  * 1.4.2 El usuario podrá crear un **publicación de texto** con un título, una imagen y una descripción.
  * 1.4.3 El usuario podrá crear un **publicación de imagen** con sólo una imagen.
  * 1.4.4 El usuario debe poder comentar una entrada de texto y una entrada de imagen.
  * 1.4.5 El usuario deberá poder filtrar los posts con respecto a su usuario.

### 2. Backend

* 2.1 Seguridad
  * 2.1.1 El backend debe rechazar cualquier variante de Cross Site Scripting (XSS).
  * 2.1.2 El backend debe denegar cualquier acceso no autorizado a la aplicación.
  * 2.1.3 El backend debe rechazar cualquier variante de SQL Query Injection si se utiliza una base de datos SQL en la aplicación.
  * 2.1.4 El backend debe almacenar las versiones hash de las contraseñas de los usuarios y en texto plano.
* 2.2 Rendimiento
  * El backend deberá ser capaz de manejar más de 1000 peticiones concurrentes en cualquier momento.

### 3. Frontend
* 3.1 Compatibilidad
  * El frontend deberá ser capaz de funcionar en los navegadores web más utilizados: Firefox, Safari, Opera y Chrome.

## Entornos

El backend debe vivir en un servidor público accesible por su dirección IP. El frontend debe vivir en nuestros navegadores web.

## Herramientas y pila de software

Usted es libre de utilizar cualquier herramienta y pila de software, pero le recomendamos que utilice estas tecnologías:

1. Backend: Node.js 
2. Frontend: Vue.js v3+ para JS Framework, Tailwind CSS para CSS Framework

## Ciclo de desarrollo

En esta sección, explicaremos cómo debes desarrollar el proyecto. En primer lugar, se espera que desarrolles el componente Frontend. En el desarrollo del componente Frontend, debes centrarte en añadir funcionalidad al componente e implementar las pruebas. Deberá simular el comportamiento del componente Backend en el punto en el que el Frontend y el Backend deben comunicarse. Por lo tanto, no tienes que implementar el Frontend y el Backend al mismo tiempo.


Si no utilizas ningún framework css en el componente Frontend, entonces se espera que construyas tú mismo un framework CSS básico que debería incluir bloques de construcción básicos como el sistema de rejilla, la tarjeta, el formulario, etc.