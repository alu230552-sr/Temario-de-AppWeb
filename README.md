# Temario-de-AppWeb
# Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.   
## 1. Introducción al desarrollo web 
Historia y evolución del desarrollo web:  
El desarrollo web comenzó en la década de 1990 con la invención de la World Wide Web. Inicialmente, las páginas web eran simples documentos de texto con enlaces (HTML). Con el tiempo, evolucionaron incorporando imágenes, estilos (CSS), interactividad (JavaScript) y bases de datos. Actualmente, existen aplicaciones web complejas y dinámicas, como redes sociales, tiendas online y aplicaciones que funcionan casi como programas de escritorio.

## Tipos de aplicaciones web:  

Estáticas: Son páginas cuyo contenido no cambia; cada usuario ve lo mismo. Se componen principalmente de archivos HTML y CSS.  
Dinámicas: El contenido puede variar según el usuario o acciones realizadas. Usan lenguajes de servidor como PHP, bases de datos, etc.  
SPA (Single Page Application): Aplicación de una sola página que carga una vez y después gestiona la navegación y los cambios de contenido dinámicamente sin recargar toda la página (ejemplo: Gmail).  
PWA (Progressive Web App): Aplicaciones web que utilizan tecnologías avanzadas para comportarse como aplicaciones móviles nativas, permitiendo funcionar offline y ser instalables en dispositivos.  
## 2. Arquitectura de aplicaciones web
Cliente-Servidor:
Modelo donde el "cliente" (generalmente el navegador del usuario) solicita información o servicios al "servidor" (donde reside la aplicación y la base de datos). El servidor responde enviando los datos o la página solicitada.

Arquitectura de tres capas:
Separación de la aplicación en tres partes:

## Presentación: Interfaz que ve el usuario (HTML, CSS, JS).
Lógica: Procesamiento de datos y reglas de negocio (PHP, Node.js, etc.).
Datos: Almacenamiento y manejo de datos (bases de datos como MySQL).
REST y API-first design:

## REST: Estilo de arquitectura para crear APIs que permiten la comunicación entre sistemas usando HTTP. Es sencillo, escalable y usa operaciones como GET, POST, PUT, DELETE.
API-first design: Enfoque donde primero se diseña la API (cómo los sistemas se comunicarán) antes de implementar la aplicación, garantizando que sea reutilizable y fácil de mantener.
## 3. Lenguajes y tecnologías fundamentales
HTML (HyperText Markup Language): Lenguaje estándar para crear la estructura y contenido de las páginas web.  
CSS (Cascading Style Sheets): Lenguaje para definir el aspecto visual y el diseño de las páginas web.  
JavaScript: Lenguaje de programación que permite agregar interactividad y dinamismo a las páginas web.  
PHP: Lenguaje de programación del lado del servidor, muy usado para crear páginas web dinámicas.  
MySQL: Sistema de gestión de bases de datos relacional, usado para almacenar y gestionar información en aplicaciones web.  
## 4. Control de versiones
Git y GitHub:

Git: Sistema de control de versiones que permite registrar todos los cambios realizados en el código, facilitando el trabajo en equipo y el seguimiento de la evolución del proyecto.
GitHub: Plataforma en línea para alojar repositorios Git, colaborar, revisar código y gestionar proyectos.
Flujo de trabajo con ramas:

Branching: Crear una rama (branch) para trabajar en una nueva funcionalidad o corrección sin afectar el código principal.
Merge: Unir los cambios de una rama al código principal, integrando las nuevas funcionalidades o correcciones.
Pull requests: Solicitud para que otros revisen y aprueben los cambios antes de integrarlos al proyecto principal, facilitando la colaboración y revisión de código.
<img width="477" height="281" alt="image" src="https://github.com/user-attachments/assets/081a8ff6-29d1-46a0-bf3a-b6d4e02fce91" />


# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
## 1. Diseño e implementación del frontend
Maquetación/Wireframe/Mockup

Maquetación: Proceso de organizar y estructurar los elementos visuales de una página web (textos, imágenes, botones) usando HTML y CSS.
Wireframe: Esquema básico o boceto de una página web, mostrando la disposición de los elementos sin detalles de diseño.
Mockup: Versión más detallada y visual del wireframe, mostrando colores, tipografías y aspecto final antes de programar.
API (Interfaz de Programación de Aplicaciones)

Conjunto de reglas y definiciones que permiten que dos aplicaciones se comuniquen entre sí, generalmente a través de peticiones HTTP (como REST o GraphQL).
## 2. Diseño e implementación del backend
Servidor

Programa o máquina que recibe peticiones de los clientes y envía las respuestas correspondientes (por ejemplo, un servidor Node.js, Django, o Express).
Manejo de peticiones y respuestas HTTP

Proceso donde el servidor recibe solicitudes (GET, POST, PUT, DELETE) y responde con datos o páginas, usando el protocolo HTTP.
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)

Los servidores suelen conectarse a una base de datos para guardar o recuperar información necesaria para la aplicación.
## 3. Bases de datos
Modelado de datos y relaciones

Diseño de la estructura de datos y cómo se relacionan entre sí (tablas, llaves foráneas, colecciones, etc.).
ORM (Object Relational Mapping)

Herramientas que permiten interactuar con una base de datos usando código orientado a objetos en lugar de SQL directo (ej. Sequelize, SQLAlchemy, Mongoose).
CRUD desde el backend

Operaciones básicas que se pueden realizar sobre una base de datos:
Create (Crear)
Read (Leer)
Update (Actualizar)
Delete (Eliminar)
Estas operaciones suelen estar disponibles a través de rutas o endpoints en el backend.
## 4. Seguridad básica en aplicaciones web
Validación de formularios

Proceso de revisar que los datos introducidos por el usuario cumplen ciertos requisitos antes de ser procesados o guardados.
Autenticación y autorización

Autenticación: Verificar la identidad de un usuario (por ejemplo, mediante usuario y contraseña).
Autorización: Controlar qué acciones puede realizar un usuario según su rol o permisos. 
<img width="409" height="272" alt="image" src="https://github.com/user-attachments/assets/5349bf2b-ee14-4b16-b1b9-93f3c6193f8d" />


# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional  
## 1. Integración de frontend y backend
Interfaz de usuario Frontend
El frontend es la parte de una aplicación web con la que interactúa el usuario directamente. Se desarrolla usando tecnologías como HTML, CSS y JavaScript (y frameworks como React, Angular o Vue). El objetivo es crear interfaces atractivas, responsivas y fáciles de usar, gestionando eventos, validaciones y la experiencia visual general.

Manejo de API
El frontend se comunica con el backend a través de APIs (Application Programming Interfaces). Por lo general, se utilizan APIs REST o GraphQL, que permiten al frontend enviar solicitudes HTTP (GET, POST, PUT, DELETE) para crear, leer, actualizar o eliminar datos en el servidor. El manejo de API implica consumir estos endpoints usando fetch, Axios, o librerías similares, gestionando respuestas y errores.

Proceso de Solicitud y Respuesta de Backend
Cuando el frontend realiza una solicitud (por ejemplo, para obtener datos de usuario), el backend la recibe, procesa la lógica necesaria (consultar una base de datos, aplicar reglas de negocio, etc.) y devuelve una respuesta (generalmente en formato JSON). Este ciclo de solicitud/respuesta es la base de la comunicación entre cliente y servidor.

## 2. Almacenamiento en Servidor
Tipos de servidores
Servidor físico (bare-metal): Hardware dedicado exclusivamente a un cliente.
Servidor virtual (VPS): Un entorno virtualizado dentro de un servidor físico, permite mayor flexibilidad y escalabilidad.
Servidores cloud: Recursos virtualizados en la nube, escalables bajo demanda (Amazon AWS, Google Cloud, Azure).
Servidores y servicios de hosting
Hosting compartido: Recursos compartidos entre varios usuarios, económico pero menos potente.
Hosting dedicado: Un servidor completo para un solo usuario, más caro y potente.
Hosting en la nube: Escalabilidad y pago por uso, ideal para aplicaciones que pueden crecer.
PaaS (Platform as a Service): Servicios que gestionan infraestructura y permiten centrarse en el desarrollo (Heroku, Vercel, Netlify).
Proveedores de Servicios de Almacenamiento
Amazon Web Services (AWS): S3 para almacenamiento de archivos, EC2 para servidores.
Google Cloud Platform (GCP): Cloud Storage, Compute Engine.
Microsoft Azure: Blob Storage, Virtual Machines.
Otros: DigitalOcean, Linode, Hetzner, Firebase (para almacenamiento y backend).
## 3. Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Compresión de imágenes: Reducir el tamaño de imágenes sin perder calidad perceptible (usando formatos como WebP).
Minificación: Eliminar espacios y comentarios de archivos JS/CSS.
Carga diferida (Lazy Loading): Cargar imágenes o scripts sólo cuando el usuario los necesita.
Uso de CDN: Distribuir recursos estáticos en servidores globales para reducir latencia.
Despliegue de aplicaciones web
El despliegue es el proceso de poner la aplicación en un servidor accesible por los usuarios. Puede hacerse manualmente (subiendo archivos por FTP/SFTP) o automáticamente usando herramientas de integración continua/despliegue continuo (CI/CD). Se deben tener en cuenta aspectos como la configuración del entorno, variables de entorno, y seguridad.

CI/CD básico
CI/CD (Integración Continua y Entrega/Despliegue Continuo) automatiza pruebas, construcción y despliegue de aplicaciones. Herramientas comunes: GitHub Actions, GitLab CI, Jenkins. Permite detectar errores antes, acelerar el release y mantener calidad.

Documentación del proyecto
La documentación describe cómo funciona la aplicación, cómo instalarla, configurarla, usarla y contribuir. Incluye el README.md, documentación de la API, diagramas de arquitectura y guías para desarrolladores y usuarios.
<img width="232" height="122" alt="image" src="https://github.com/user-attachments/assets/b0760888-51e9-4f3d-a125-c39570f07cec" />


