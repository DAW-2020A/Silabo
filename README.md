# Sílabo para Desarrollo de Aplicaciones Web (TDSR414) ESFOT-EPN

* **Materia:** TDSR414 Desarrollo de Aplicaciones Web
* **Lugar:** Zoom (Meeting ID: 853 1026 1587)
* **Horario:**  Martes de 17:00 a 20:00, Miércoles de 17:00 a 20:00
* **Profesor:** Edwin Salvador, [edwin.salvador@epn.edu.ec](mailto:edwin.salvador@epn.edu.ec)

## Objetivos del Curso

* **De Conocimientos:** 
  * Explicar el funcionamiento de internet y sus componentes.
  * Diferenciar los conceptos de backend y frontend.
  * Explicar en que consiste un modelo de arquitectura.

* **De Destrezas:** 
  * Configurar servidores web.
  * Analizar datos de rendimiento de servidores.
  * Implementar aplicaciones web del lado del servidor robustas usando el modelo de arquitectura MVC.

* **De Actitudes y Valores:** 
  * Desarrollar habilidad para resolver problemas usando programación.
  * Desarrollar habilidad para trabajar en grupo y bajo presión en un proyecto.
  * Demostrar creatividad e innovación.


## Prerequisitos

* TDSR314 PROGRAMACIÓN ORIENTADA A OBJETOS

## Deberes/Proyectos

Cada semana se deberán subir los avances de los videos según se especifique en la sección **Videos** de cada semana. Se revisará los commits de los avances. Al finalizar cada video deben hacer un commit a su repositorio personal para demostrar el avance. El commit de cada video representa la entrega del deber.

## Calificaciones

| Evaluación              | Valoración |
| ----------------------  | ---------- |
| Deberes videos          | 20%        |
| Prueba parcial          | 20%        |
| Trabajo grupal          | 30%        |
| Examen                  | 30%        |


## CALENDARIO DE CLASES

### Clase 1 - Presentación (2020-11-17)
  * [Encuesta de inicio de curso](https://forms.office.com/Pages/ResponsePage.aspx?id=ak4qaH-nWEmjrJ4mbRiqN173BU_p6khOitbGQ_4-nytUNTA2N0dWNVgzNldRMFRNTUxXQ1RJSU1CMi4u)
  * Verificar instalaciones de XAMPP, PHPStorm.
  * [Videos de LARAVEL API REST](https://loom.com/share/folder/1941937cf66e4961a4770971e0219ecf)
  * [Documento guía de LARAVEL API REST](https://epnecuador-my.sharepoint.com/:b:/g/personal/edwin_salvador_epn_edu_ec/EQxcHr7IQAxLjUWsv01xKZUBWgR6fkgy5p9Q-LpCkYcx3w?e=dEXWLN)
  * [Grabaciones clases](https://epnecuador-my.sharepoint.com/:f:/g/personal/edwin_salvador_epn_edu_ec/EhPswlIurK5CujpRnY2L948BHEe2A0L-NXO4kHyisNax1A?e=ct4IS2)
  * Ideas para implementación de proyecto de curso
  * Formación de grupos
  
  * ### Deber
    * **Configurar ambiente de desarrollo Linux**
      * [Instalar Linux, Apache, MySQL, PHP](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04)  
      * (Opcional para desarrollo local, obligatorio para servidor de producción)[Configuración inicial Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-18-04)
      * [Instalar MySQL en Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/como-instalar-mysql-en-ubuntu-18-04-es)
      * [Instalar phpmyadmin](https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-18-04)
      * [Instalar Composer](https://getcomposer.org/download/)
      * Configurar el ambiente de GitHub con [ZenHub](https://chrome.google.com/webstore/detail/zenhub-for-github/ogcgkffhplmphkaahpmffcafajaocjbd) según lo explicado en clase.
      
  * ### Videos
    * **Crear cuenta en Loom. Los videos deben verlos siempre autenticados en Loom para que Loom me verifique quienes han visto los videos.**
    * [1. Introducción](https://www.loom.com/share/1fbae31dc0ee4de0b2e4fa9486c16e01)
    * [2. Instalación de Laravel](https://www.loom.com/share/82cc140b22354b2299a5342f5b0a5e7a)
 
 
### Clase 2 - Instalación de Laravel (2020-11-18)
  * Conveciones API:
    * https://www.restapitutorial.com/lessons/restfulresourcenaming.html
    * https://restfulapi.net/resource-naming/
    
  * Ejemplo creación proyecto: https://github.com/DAW-ESFOT/blog
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales
  * ### Lecturas
    * [Guía de Git](https://rogerdudler.github.io/git-guide/index.es.html)
    * [Ramas en Git](https://nvie.com/posts/a-successful-git-branching-model/)


  
### Clase 3 - API, REST, Laravel (2020-11-24)
  * [Crear repos de los avances de Laravel](https://classroom.github.com/a/A0tDEgFw)
  * [Unirse a la clase en Quizizz](https://quizizz.com/join?class=T060819)
  * [Ejercicios de JavaScript](https://repl.it/classroom/invite/zVqeLwh). 2 Puntos extra al examen para quienes completen todos los ejercicios correctamente y puedan explicar cualquiera de ellos al azar.
  * ¿Dudas sobre Instalación de Laravel?
  * ¿Qué es una API?
  * ¿Qué es REST?
  * ¿Qué es API RESTful?
  * Decisión de proyectos grupales. [Ideas de proyectos](https://epnecuador-my.sharepoint.com/:x:/g/personal/edwin_salvador_epn_edu_ec/ESLqwAe-vshFtEVwgx_Khc4BNjUD8gjvoxT0XUQECAPGFw?e=FWHsIF)
  * [Crear repositorios grupales]()
  * Diseñar modelos de bases de datos
  
  * ### Videos
    * [3. Estructura de directorios y configuración inicial](https://www.loom.com/share/1c350324b93d408eabba82c5fb852256)
    * [4. Flujo de trabajo Git](https://www.loom.com/share/af099b7741bb434db6dc27cdd1fae312)
    * [5. Modelo y migraciones Article](https://www.loom.com/share/593db733b30f4f0da3bca5238c360140)
    
  
### Clase 4 - API, REST, Laravel (2020-11-25)
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales
  
  
### Clase 5 - Modelos y migraciones (2020-12-01)
  * ¿Dudas sobre modelos y migraciones en Laravel?
  * ¿Qué es un modelo?
  * ¿Qué son las migraciones?
  * ¿Cómo deben manejarse las migraciones?
  * Revisión de modelos de bases de datos
  
  * ### Videos
    * [6. Seeding de la BDD](https://www.loom.com/share/b4aa245b2cf8464f977ba50c4f57db31)
    * [7. Rutas y Postman](https://www.loom.com/share/8f22fc7222b747efb013633c60d21966)
    * [8. Controladores y Cors](https://www.loom.com/share/dec50c9dfdf44dceba7e9c8c13a2c6dd)
  
  * ### Deber
    * Mejorar los modelos de BDD
    * Empezar a trabajar en los mockups (marvelapp.com, ninjamock, etc)
    
  * ### Lecturas
    * [Git Explained](https://dev.to/milu_franz/git-explained-the-basics-igc)
    * [The Differences Between a Junior, Mid-Level, and Senior Developer](https://medium.com/better-programming/the-differences-between-a-junior-mid-level-and-senior-developer-bb2cb2eb000d)


### Clase 6 - Modelos y migraciones (2020-12-02)
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales


### Clase 7 - Seeding de la BDD, Rutas y Controladores (2020-12-08)
  * ¿Dudas sobre seeding de la BDD, rutas y controladores?
  * ¿Para qué sirve el seeding de la BDD?
  * ¿Cómo se deben estrucutras las rutas de la API?
  * ¿Qué son los controladores?
  * Revisión de los backlogs
  * Planificación de Sprints
  
  * ### Videos
    * [9. Autenticación de usuarios con JWT](https://www.loom.com/share/a90ed7d5bd864846b06c09ac1cb646ae)
 
  * ### Deber
    * Completar el Backlog de los proyectos en tablero de ZenHub
    * Comenzar con el desarrollo de los proyectos de acuerdo a los sprints
  
  * ### Lecturas
    * [JSON Web Tokens](https://jwt.io/introduction/)
    * [UI Kits for any day use](https://dev.to/tngeene/ui-kits-for-any-day-use-215e?fbclid=IwAR3qu0UPTxJJ8brHw-b5pPUg8zSKcXP4OcO6WyMkxt-sXa3A6HPHe7EV3z0)
    
  
### Clase 8 - Seeding de la BDD, Rutas y Controladores (2020-12-09)  
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales

  
### Clase 9 - Autenticación de usuarios (2020-12-15)
  * ¿Dudas sobre Autenticación de usuarios con JWT?
  * ¿Qué es la autenticación de usuarios?
  * ¿Qué es JWT?
  * ¿Alternativas para la autenticación?
  * Revisión de avances
  
  * ### Videos
    * [10. Relaciones en la BDD](https://www.loom.com/share/787163385bb24599830c3b33a5bbb456)
    * [11. Relaciones en Eloquent - Uno a muchos](https://www.loom.com/share/999787956b6a47f9aed603d15d308884)
    * [12. Relaciones - usuario actual, seeder con relaciones, Tinker](https://www.loom.com/share/e9e9aa429f20427e9d669c83ef09e33b)
    * [13. Relaciones - Muchos a Muchos](https://www.loom.com/share/e28bb083c22f49fa8bc415dac4a60b36)


### Clase 10 - Autenticación de usuarios (2020-12-16)
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales
  * Material de diseño
    * Diseños
      * [Diseños de páginas (ver en la opción others)](https://delesign.com/free-designs/website)
      * [Diseños de páginas](https://landingfolio.com/)
      * [Diseños para secciones del sitio](https://froala.com/design-blocks)
      * [Diseños de páginas](https://dev.to/tngeene/ui-kits-for-any-day-use-215e?fbclid=IwAR3qu0UPTxJJ8brHw-b5pPUg8zSKcXP4OcO6WyMkxt-sXa3A6HPHe7EV3z0)
    
    * Colores, patrones y gradientes
      * [Patrones de diseño](https://products.ls.graphics/paaatterns)
      * [Patrones para fondos](http://www.heropatterns.com/)
      * [Generador de paleta de colores](https://coolors.co/generate)
      * [Oscurecer y aclarar colores](https://www.0to255.com/8f387f)
      * [Generador de gradientes](https://uigradients.com/#ElectricViolet)
      * [Paletas de colores populares](https://colorhunt.co/)
      * [Generación de temas para páginas web](https://components.ai/theme-ui)

    * Ilustraciones e íconos
      * [Ilustraciones](https://lukaszadam.com/illustrations)
      * [Ilustraciones](https://delesign.com/free-designs/graphics)
      * [Ilustraciones](https://undraw.co/illustrations)
      * [Ilustraciones](https://generator.opendoodles.com/)
      * [Íconos SVG](https://iconsvg.xyz/)
      * [Íconos](https://thenounproject.com/)
      * [Íconos animados](https://lordicon.com/icons)
      * [Micro interacciones](https://webkul.github.io/micron/)

    * Imágenes
      * [Breakpoints para imágenes](https://responsivebreakpoints.com/)
      * [Generador de ondas SVG](https://smooth.ie/blogs/news/svg-wavey-transitions-between-sections)
      * [Generador de ondas SVG](https://www.getwaves.io/)

    * Animaciones
      * [Generador de animaciones CSS](https://animista.ne)
      * [Animaciones CSS](https://freefrontend.com/css-animation-examples/)
      * [Spinners CSS](https://freefrontend.com/css-spinners/)
      * [Animaciones scroll](https://michalsnik.github.io/aos/)
      * [Fondos interactivos](http://kamranahmed.info/brusher/)
    
    * Miscelanea
      * [Páginas 404](https://freefrontend.com/html-css-404-page-templates/)
      * [Generador de políticas de privacidad](https://getterms.io/)
  

### Clase 11 - Relaciones de BDD (2020-12-22)
  * **PRUEBA:** [Crear repositorios]()
  
  * ### Videos
    * [14. Recursos API](https://www.loom.com/share/1813c69d34f44ca680e86e07db38e402)
    * [15. Validación de datos (parte 1)](https://www.loom.com/share/1690c558c6ef44b3bddb09fe3225527e)
    * [16. Validación de datos (parte 2)](https://www.loom.com/share/94963aa6d0d04bb3a807b5ea00b7cde2)
    

### Clase 12 - Relaciones de BDD (2020-12-23)
  * ¿Dudas sobre las relaciones en la BDD?
  * Revisión de avances
  * Trabajo en avances de proyectos grupales
  
  * ### Lecturas
    * [¿Qué pasa cuando ingresamos una URL en el navegador?](https://dev.to/educative/behind-the-screens-what-happens-when-you-type-a-url-in-a-browser-161d?fbclid=IwAR1uFyksIjCJ_pqCj-x6j69lxyLqIRZn1movLA6eTGPj3fQkvsRqPj7yS8w)

    
### Clase 13 - Validación de datos en el servidor (2021-01-05)
  * ¿Dudas sobre la validación de datos en el servidor?
  * Revisión de avances
  
  * [Solucion de la prueba](https://github.com/DAW-ESFOT/prueba1-bimestre1-solucion)
  
  * ### Videos
    * [17. Subir y descargar imágenes](https://www.loom.com/share/f0f39ca5253a4fb1aa8103fa1bc56f46)
    * [18. Autorización - Roles y Permisos](https://www.loom.com/share/b07b9f42a6be47dc938da8ae6cdca1ae)
    
    
### Clase 14 - Validación de datos en el servidor (2021-01-06)   
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales
  
  * ### [Crear repositorios grupales para frontend]()
  
  * ### Lecturas
    * [Galería con estilos de diseño de páginas web](https://designsystemsrepo.com/design-systems/)


    
### Clase 15 - Autorización, Roles y Permisos (2021-01-12)
  * ¿Dudas sobre Autorización, Roles y Permisos?
  * Revisión de avances
    
  * ### Videos
    * [19. Relaciones polimórficas](https://www.loom.com/share/be662c3542954a578ec7dbd98664bc99)
    * [20. Relaciones polimórficas (parte 2)](https://www.loom.com/share/b34c5d1e7e7247c0bb5508214e99c501)    
    * [21. Envío de correos](https://www.loom.com/share/0c27a4e962044eb4b4c067e302d54209)
    * **22. Pruebas unitarias** (PENDIENTE)
    
  * Lecturas
    * [JS Promises](https://dev.to/hem/gif-cheatsheet-for-javascript-promise-api-methods-promise-all-promise-allsettled-promise-race-promise-any-1l2o?fbclid=IwAR0iVPbpx8jCAqojCuIqZYX-x1ua3lNz-ZINgIyQ1PQX2VvMmREZ-SCQ_l8)
    
### Clase 16 - Autorización, Roles y Permisos (2021-01-13)
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales


### Clase 17 - Envío de correos y Pruebas unitarias (2021-01-19)

  * **EXAMEN** [Crear repos]()

  * ### Lecturas
    * [Conceptos básicos de JS (Asignación de variables y mutación primitivos/objetos)](https://dev.to/nas5w/foundational-javascript-concepts-variable-assignment-and-primitive-object-mutability-237d?fbclid=IwAR2Txo23mlz9yRVoWU5ragSsZ-GRFuNChmUeIegoBjCV5iQe_9WDFOpOFdY)
    * [Conceptos JS para entender React](https://codequs.com/p/r1U2DMtHL/10-javascript-es6-concepts-you-need-to-master-react/?fbclid=IwAR2NCXvI3_73VLyoDzOt_zL27q32t9sDd2IFjUKacdNjQ69EXKs1naTRp4M)
    * [Regular vs Arrow functions](https://morioh.com/p/761768c97ae4?fbclid=IwAR0qF6i1C-ILs2MBDqgp7-hlOZwC1OULiBbLm9VB8lUIA16y9xGK5uxFEco)
    * [Maneras de iterar un arreglo en JS](https://dev.to/misterkevin_js/11-ways-to-iterate-an-array-javascript-3mjg?fbclid=IwAR19YbdOMvk3WHlThK2bgx4FbVzGx9gpIwSpe4fWsHfi8mif10RWDjIzuWQ)



### Clase 18 - Envío de correos y Pruebas unitarias (2021-01-20)
  * ### **Presentación de proyecto primer bimestre**
    * Acuerdo de TrialQ: Hasta Recursos API y 1 punto extra al examen si presentan hasta validación de datos funcionando perfecto.
    * Acuerdo de sistema de busses: Hasta JWT y 1 punto extra al examen si presentan hasta Relaciones funcionando perfecto.      
  * Trabajo en avances de videos
  * Trabajo en avances de proyectos grupales


### Clase 19 - Introducción a ReactJS (2021-01-26)
   * [Repaso de JS](https://epnecuador-my.sharepoint.com/:b:/g/personal/edwin_salvador_epn_edu_ec/EaxCKtCJ36ZEoJwmO-wxvzkB6xqOk8Ax5CpFnyXoTkN4MQ?e=3y7kdT)
   * ### Lecturas
    * [Learn React in 2020](https://dev.to/codeartistryio/want-to-learn-react-in-2020-here-s-the-blueprint-to-follow-2jdd)
    * [React Cheatsheet](https://dev.to/codeartistryio/the-react-cheatsheet-for-2020-real-world-examples-4hgg)
    * [React Virtual DOM](https://medium.com/@tonynguyenit18/how-react-virtual-dom-decide-to-update-browser-dom-91f170718733)
    * [¿Qué es el package.json](https://dev.to/easybuoy/understanding-the-package-json-file-3fdg?fbclid=IwAR1C6nHctdEYpKRD9hsklHSQU-Sqk0oFKR-KNMhJ3KTnyuipjHWYtvn3N3Q)
    * [Local, Session storage, Cookies](https://morioh.com/p/73377031920f?fbclid=IwAR2AUfmTED7iRa5dciGvpFyazMSCKQKvbu8SB2t2GM6lFzPtBXAj0Pb1SXs)
    




### Clase 20 - ReactJS (2021-01-27)


### Clase 21 - Introducción a ReactJS (2021-02-02)
  * [Manual de JS](https://developer.mozilla.org/es/docs/Web/JavaScript)
  * [Repaso de JS](https://developer.mozilla.org/es/docs/Web/JavaScript/Una_re-introducci%C3%B3n_a_JavaScript)
  * [Tutorial de JS](https://javascript.info/)
  
  
  * [Documento React](https://epnecuador-my.sharepoint.com/:b:/g/personal/edwin_salvador_epn_edu_ec/EWg8X0IA7DRPpauswCwS8JAB8kSI7mf2oy-s5WOUk6bzcQ?e=h6jSc4)
    * [Ejercicio Lista de tareas con React]()


### Clase 22 - Introducción a NextJS con Ant Design (2021-02-03)
   * [Ejercicio useEffect]()


### Clase 23 - Consumir datos de la API (2021-02-09)
  * Ejercicio antd. [Crear el repo]()
    * Formulario que me permita buscar peliculas por título, tipo (serie, película, episodio) desde api omdb (http://www.omdbapi.com/)
    * Las películas se presentan en cards de esta manera: https://ant.design/components/card/#components-card-demo-meta
      * Se debe mostrar la imagen, título, género, director directamente en el card
      * Cada card tiene 2 botones en su footer
        * 1. Ver detalles, ícono: <EyeOutlined />. Abre un modal con la siguiente info:
            * Muestra todo el resto de atributos de la película utilizando el componente: https://ant.design/components/descriptions/#components-descriptions-demo-border
            * Debe mostrar los comentarios debajo , con el componente: https://ant.design/components/comment/#components-comment-demo-list
        * 2. Añadir comentario, ícono: <CommentOutlined />. 
            * Debe abrir otro modal con el formulario de crear un comentario: https://ant.design/components/comment/#components-comment-demo-editor
            * Esto añade una nueva propiedad en el objeto de la película correspondiente para almacenar estos comentarios como un arreglo.
            * Los comentarios tendrán la siguiente estructura:
            
              ```json
              {
                "text": "Texto del comentario",
                "createdAt": "fecha actual cuando se creó el comentario", // pueden usar new Date() o la librería momentjs (recomendado)
                "user": "Nombre genérico de usuario"
              }
              ```
    
  * ### Lecturas
    * [FakeMyAPI](https://fakemyapi.com/)
    

### Clase 24 - Consumir datos de la API (2021-02-10)
  * Ejercicio use effect, películas.


### Clase 25 - React router y Layouts (2021-02-17)
  * (Ejemplo react touter, layout, personalizacion antd)[https://github.com/DAW-ESFOT/intro-antd/tree/react-router]


### Clase 26 - React boilerplate (proyecto base) (2021-02-23)
  * Hacer un fork del repo: [React boilerplate (proyecto base)](https://github.com/chalosalvador/react-api-boilerplate.git)
    * Correr el `npm i`
    * Crear en archivo `.env.development` con la variable `REACT_APP_API_HOST=http://localhost:8000/api`
    * Correr `npm start`. Asegurarse que esto corra en el `http://localhost:3000`
  * [Documento explicación proyecto base](https://epnecuador-my.sharepoint.com/:w:/g/personal/edwin_salvador_epn_edu_ec/EXH7vIqD6XJFiD0jWZCpJXQB6ylPZbeScDIokzPv7iFC2g?e=wYPTxl)
  * Hacer un fork del repo: [Blog API](https://github.com/chalosalvador/blog)
    * Crear el archivo .env
    * Correr `composer install`
    * Generar la base de datos
    * Correr el seed 
    * Generar el jwt secret 
    * Colocar credenciales del mailgun
    * Correr `php artisan serve`. Asegurarse que esto corra en el `http://localhost:8000`
    
  * ### Ejercicio utilizando el boilerplate
    * Crear un nuevo item en el submenú del usuario que diga "Perfil".
    * Esta opción debe dirigir a la ruta "/perfil"
    * Crear una página que presente la información del perfil del usuario que devuelve el api.
      * Para obtener la información del usuario puede utilizar el hook `useAuth()`, puede usar un console.log para ver la información que se incluye en este hook.
    * Debajo de la información del perfil deben presentar las categorias a las que está suscrito el usuario. 
      * Deberá agregar un nuevo endpoint que permita obtener esta información desde el api. `/user/categories`.
      * Este enpoint debe estar protegido y debe devolver únicamente las categorias del usuario que hace la petición.
      * El controlador debe obtener la información del usuario mediante `$user = Auth::user()`. Y puede devolver las categorias en un JsonResponse utilizando `$user->categories`.
    
  


### Clase 27 - Formularios y validación de datos (2021-02-24)


### Clase 28 - Formularios y validación de datos (2021-03-02)


### Clase 29 - Reutilización de componentes (2021-03-03)


### Clase 30 - Reutilización de componentes (2021-03-09)


### Clase 31 - Seguridad (2021-03-10)


### Clase 32 - Examen (2021-03-16)
  * **EXAMEN** [CREAR REPO]()
  
### EXTRA - Entrega de proyecto (2021-03-17)  
  * **ENTREGA DE PROYECTO FINAL**


## Código de Ética

### Políticas de profesor

* Respetar los términos de uso y/o licencia de cualquier material que se reuse.
* Se tendrá en cuenta la asistencia a clases.
* No se aceptan deberes atrasados.
* Todo el material estará publicado en este repositorio.
* **Para poder rendir el examen deben entregar todos los deberes y trabajos**.

### LA ESCUELA POLITÉCNICA NACIONAL

La tradición y el prestigio de la Politécnica exigen que el comportamiento de sus miembros se encuadre en el respeto mutuo, la honestidad, el apego a la verdad y el compromiso con la institución.

Con tal antecedente, el presente Código de Ética define la norma de conducta de los miembros de la Escuela Politécnica Nacional:

RESPETO HACIA SÍ MISMO Y HACIA LOS DEMÁS
* Fomentar la solidaridad entre los miembros de la comunidad.
* Comportarse de manera recta, que afirme la autoestima y contribuya al prestigio institucional, que sea ejemplo y referente para los demás.
* Respetar a los demás y en particular la honra ajena y rechazar todo tipo de acusaciones o denuncias infundadas.
* Respetar el pensamiento, visión y criterio ajenos.
* Excluir toda forma de violencia y actitudes discriminatorias.
* Apoyar un ambiente pluralista y respetuoso de las diferencias.
* Convertir la puntualidad en norma de conducta.
* Evitar el consumo de bebidas alcohólicas, tabaco, substancias psicotrópicas o estupefacientes.

HONESTIDAD
* Hacer de la honestidad el principio básico de comportamiento en todos los actos.
* Actuar con justicia, probidad y diligencia.
* Actuar de acuerdo a la conciencia, sin que presiones o aspiraciones particulares vulneren los intereses institucionales.
* Velar por el cumplimiento de las garantías, derechos y deberes de los miembros de la Comunidad Politécnica.
* Tomar oportunamente las medidas correctivas necesarias para superar las irregularidades que pudieren ocurrir.

VERDAD
* Hacer una mística de la prosecución de la verdad, tanto en la actividad académica como en lo cotidiano.
* Informar con transparencia y en forma completa.
* Emitir mensajes con autenticidad, que no distorsionen eventos ni realidades.

COMPROMISO CON LA INSTITUCIÓN
* Ser leal a la Politécnica y a los valores institucionales.
* Cumplir las normas constitucionales, legales, estatutarias, reglamentarias y las resoluciones de la autoridad legítimamente designada.
* Reconocer y aceptar las consecuencias de las decisiones.
* Participar activamente en la vida y en la dirección de la institución, de acuerdo a los mecanismos de participación, aportando proactivamente con iniciativas de mejoramiento institucional y mantenerse informado.
* Emplear los recursos institucionales con austeridad, de acuerdo a los fines correspondientes.
* Contribuir al ornato y limpieza de nuestra Casa de Estudios.
