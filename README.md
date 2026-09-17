### 2026---TP2---G04
### Maggiolo - Panelli - Pujana

# Aplicaciones WEB
## ¿Qué son?
Una aplicación web (web app) es un software que se ejecuta en un servidor y al que se accede a través de un navegador web. No necesita instalarse en el dispositivo del usuario y funciona desde cualquier equipo con conexión a internet.  

A diferencia de un programa tradicional, la lógica y el procesamiento de datos se realizan principalmente en el servidor, mientras que el navegador actúa como interfaz de usuario. Esto permite que las aplicaciones web sean más accesibles, escalables y fáciles de mantener.

## Funcionamiento
Las aplicaciones web utilizan una arquitectura cliente–servidor:

- **El cliente (navegador):** es la parte visible para el usuario. Carga la interfaz, muestra botones, formularios y contenidos, y envía las acciones del usuario al servidor.
- **El servidor de aplicaciones:** procesa las solicitudes recibidas, ejecuta la lógica de negocio y gestiona los permisos, cálculos o validaciones necesarias.
- **La base de datos:** almacena la información de forma estructurada y segura: usuarios, pedidos, archivos, configuraciones, etc.  

Una vez procesada la solicitud, el servidor devuelve la respuesta al navegador, que la muestra al usuario casi al instante

## Arquitectura
### Arquitectura del lado del cliente
El script del lado del cliente se encarga de la funcionalidad de la interfaz de usuario, como los botones y los cuadros con menús desplegables. Cuando el usuario final hace clic en el enlace de la aplicación web, el navegador web carga el script del lado del cliente y renderiza los elementos gráficos y el texto para la interacción del usuario.
### Arquitectura del lado del servidor
El script del lado del servidor se encarga del procesamiento de datos. El servidor de la aplicación web procesa las solicitudes del cliente y envía una respuesta de vuelta. Las solicitudes suelen ser obtener más datos, editar datos o guardar nuevos datos. 


## Tipos de aplicaciones Web
Según su arquitectura, funcionamiento y propósito, las aplicaciones web se clasifican en:

- **Estáticas:** Se caracterizan por tener un contenido fijo y no interactivo, siendo comunes en blogs, portfolios o landing pages informativas. Son rápidas y de fácil lectura, aunque ofrecen poca interactividad y su contenido no es personalizable.
- **Dinámicas:** Su contenido cambia en respuesta a las interacciones del usuario mediante bases de datos y scripts del lado del servidor. Utilizan tecnologías como AJAX para actualizar datos sin recargar la página. Son muy interactivas y personalizables en tiempo real (por ejemplo, foros o redes sociales), aunque resultan más complejas de desarrollar y mantener.
- **De página única (SPA):** Toda la información se carga en una sola página utilizando frameworks de JavaScript como React, Angular y Vue.js. Las actualizaciones se realizan sin recargar la pantalla, ofreciendo una experiencia rápida y fluida (por ejemplo, Gmail, Google Maps o Trello). Su desarrollo es complejo y pueden presentar desafíos en SEO y accesibilidad.
- **De múltiples páginas (MPA):** Siguen la estructura tradicional donde cada acción del usuario carga una nueva página HTML desde el servidor. Son comunes en plataformas de e-commerce, portales de noticias o sitios educativos. Favorecen un SEO más sencillo, aunque la navegación puede sentirse menos fluida.
- **Progresivas (PWA):** Ofrecen una experiencia similar a las aplicaciones nativas mediante tecnologías como Service Workers y el Manifiesto de Aplicación Web. Permiten trabajar offline y recibir notificaciones push (por ejemplo, Pinterest o Starbucks). Son muy rápidas y adaptables, pero requieren conocimientos avanzados para su implementación y poseen ciertas limitaciones frente a las apps nativas.
- **De e-commerce:** Diseñadas para facilitar la compra-venta de productos y servicios online. Integran catálogos, carritos de compra y pasarelas de pago (por ejemplo, Amazon). Permiten analizar datos y personalizar la oferta, aunque demandan una gestión rigurosa en aspectos legales y logísticos.
- **En tiempo real:** Enfocadas en proporcionar actualizaciones instantáneas de datos mediante tecnologías de comunicación bidireccional. Requieren una infraestructura robusta para manejar conexiones continuas. Se utilizan principalmente en chats (por ejemplo, WhatsApp Web) y videojuegos online.
- **Sociales:** Diseñadas para fomentar la interacción, la creación de perfiles, la mensajería y el networking entre usuarios (por ejemplo, LinkedIn, Facebook o Instagram). Tienen un alto nivel de engagement, aunque exigen una compleja gestión de la privacidad y el control de la sobrecarga de contenido.
## Ventajas
