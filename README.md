# isla
### Una aplicación de red social construida con Vue.js, Node.js, Express y MongoDB
==============



## Instalación

### Paso 1: Clonar el repo
```
git clone https://github.com/fcyln/island
```

### Paso 2: Prerrequisitos(Frontend)
Esto instalará las dependencias del frontend de este sitio web. Se instalarán varios paquetes como Vue, vue-router, vuex, axios, vue-skeletor, vue-spinner y sass-loader
```
cd frontend
npm install (en el directorio de frontend)
```

### Paso 3: Prerrequisitos (Backend)
Esto instalará las dependencias del backend de este sitio web. Se instalarán varios paquetes como express, express-fileupload, bcrypt, cors, dotenv, helmet, jsonwebtoken, mongoose, morgan, multer, nodemailer, nodemon y xoauth2
```
cd backend
npm install (en el directorio backend)
```

### Paso 4: Ejecutar el proyecto
```
cd frontend
npm run serve

cd backend
npm start
```

### Paso 5: Configurar las variables de entorno
Configurar las variables de entorno y añadir claves para la isla.

```
MONGO_URL=tu cadena de conexión a mongodb

SECRET_KEY= tu clave secreta
EMAIL_SECRET= tu clave secreta de correo electrónico

AUTH_USER= tu cuenta de gmail
AUTH_CLIENT_ID = su id de cliente
AUTH_CLIENT_SECRET = su secreto de cliente
AUTH_REFRESH_TOKEN = su token de actualización
AUTH_ACCESS_TOKEN = su token de acceso

```

## Características

### 1. Usuario
* 1.1 Autenticación
  * 1.1.1 El usuario puede registrarse en la aplicación con un correo electrónico y una contraseña.
  * 1.1.2 El usuario puede iniciar sesión en la aplicación con el correo electrónico y la contraseña especificados al registrarse.
  * 1.1.3 El usuario puede restablecer su propia contraseña asociada al correo electrónico.
  * 1.1.4 El usuario puede validarse visitando el enlace en el correo que recibió después de registrarse.
* 1.2 Perfil
  * 1.2.1 El usuario puede subir una imagen para su perfil.
  * 1.2.2 El usuario puede especificar la descripción, la fecha de nacimiento y las aficiones para los detalles de su perfil.
  * 1.2.3 El usuario puede ver el número de seguidores y seguidos en su página de perfil.
* 1.3 Seguimiento
  * 1.3.1 El usuario puede seguir a otro usuario.
  * 1.3.2 El usuario puede dejar de seguir a otro usuario que ya está siendo seguido por el usuario.
  * 1.3.3 Otros usuarios pueden mostrar la página de perfil del usuario.
* 1.4 Publicar
  * 1.4.1 El usuario tiene una página llamada Timeline donde puede ver las publicaciones que pertenecen a los usuarios que ya sigue.
  * 1.4.2 El usuario puede crear un **publicación de texto** con un título, imagen y descripción.
  * 1.4.3 El usuario puede crear una **publicación de imagen** con sólo una imagen.
  * 1.4.4 El usuario puede comentar un post de texto y un post de imagen.
  * 1.4.5 El usuario puede filtrar los mensajes con respecto a su usuario.
  
### 2. Backend

* 2.1 Seguridad
  * 2.1.1 Backend puede denegar cualquier variante de Cross Site Scripting (XSS).
  * 2.1.2 Backend puede denegar cualquier acceso no autorizado a la aplicación.
  * 2.1.3 El backend puede denegar cualquier variante de SQL Query Injection si se utiliza una base de datos SQL en la aplicación.
  * 2.1.4 El backend puede almacenar las versiones hash de las contraseñas de los usuarios y en texto plano.
* 2.2 Rendimiento
  * El backend puede manejar más de 1000 peticiones concurrentes en cualquier momento.


Traducción realizada con la versión gratuita del traductor www.DeepL.com/Translator