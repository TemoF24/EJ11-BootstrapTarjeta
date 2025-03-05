# README - Tarjeta de Perfil

## Descripción
Este es un ejemplo de una tarjeta de perfil personal utilizando HTML, CSS y Bootstrap 5. La tarjeta muestra una imagen de perfil circular, un nombre de usuario, una breve descripción y botones de contacto que permiten enviar un correo electrónico o acceder a los perfiles de LinkedIn y GitHub del usuario.

## Estructura del código

1. **HTML**
   - El código HTML está estructurado dentro de una `div` con clases de Bootstrap que facilitan la organización y el diseño de la página.
   - La tarjeta contiene una imagen de perfil, un nombre y una breve descripción del usuario.
   - También incluye tres botones de contacto: uno para enviar un correo electrónico, otro para acceder a LinkedIn y otro para GitHub.

2. **CSS**
   - Se añade un estilo personalizado a la tarjeta de perfil para darle un diseño más atractivo.
   - La tarjeta tiene un borde redondeado (`border-radius`) y una sombra (`box-shadow`) para crear un efecto de elevación.
   - La imagen de perfil es circular y se ajusta automáticamente al contenedor con la propiedad `object-fit: cover`.

3. **Bootstrap**
   - Se utiliza el framework Bootstrap 5 desde un CDN para facilitar la creación de un diseño responsive y elegante.
   - Las clases de Bootstrap como `card`, `btn`, `container`, `row`, y `col-md-4` se utilizan para la disposición y estilo de los elementos de la tarjeta.
   
4. **Botones de contacto**
   - Los botones proporcionan enlaces a las plataformas de comunicación del usuario, como:
     - Correo electrónico (utilizando `mailto:`).
     - Perfil de LinkedIn.
     - Repositorio de GitHub.
   - Los botones utilizan las clases de Bootstrap (`btn btn-primary`, `btn btn-info`, `btn btn-dark`) para estilizarse con diferentes colores.

## Estilos y diseño

- **Colores:** Los botones tienen diferentes colores, dependiendo de su propósito:
  - Botón de correo electrónico: color azul (`btn-primary`).
  - Botón de LinkedIn: color azul claro (`btn-info`).
  - Botón de GitHub: color oscuro (`btn-dark`).
  
- **Tipografía:** Se utiliza la tipografía predeterminada de Bootstrap con el formato estándar para los elementos de la tarjeta.

- **Imagen de perfil:** La imagen de perfil está centrada y es circular, con un tamaño de 120px de ancho y alto.

## Archivos necesarios

- **Imagen de perfil:** Se utiliza una imagen de ejemplo (`https://via.placeholder.com/150`). Puedes reemplazarla por la imagen de perfil del usuario.

## Instrucciones de uso

1. Abre el archivo `.html` en tu navegador para ver la tarjeta de perfil en acción.
2. Asegúrate de tener conexión a Internet para cargar los recursos de Bootstrap desde el CDN.
3. Personaliza los enlaces de contacto y la imagen de perfil con la información del usuario.

## Contacto

- Si tienes preguntas o dudas, puedes ponerte en contacto con el usuario a través de mi correo electrónico, LinkedIn o GitHub.

