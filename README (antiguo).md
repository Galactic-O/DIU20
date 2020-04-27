# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU2_EscuadrónMapache.  Curso: 2019/20 

Proyecto: Yutaku

Descripción: Aplicación movil de alquiler de viviendas en la que el usuario pdorá realizar búsquedas de piso con filtros de hhabitación y personas, además de mantenerse en contacto y conocer a otras personas con las que vivir.

Logotipo: 

Miembros:
 * :bust_in_silhouette:   [Pablo Vallejo Ruiz]: https://github.com/Galactic-O   ​     :octocat:     

-----

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. 


# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

Observaremos aplicaciones para compartir alojamiento - permiten buscar habitaciones para compartir y poner en alquiler nuestras ubicaciones. Badi es una app móvil gratuita, que se diferencia de otras apps por su sistema de perfiles, que facilita encontrar personas de gustos similares, asegurando una experiencia de convivencia mucho más personalizada.


![Método UX](img/Persona.png) 1.b Persona
-----

![](P1/persona1.png)

Esther Píscore: Se ha escogido este usuario para representar a un demográfico bastante común, una juventud sociable pero con poca experiencia a la hora de usar aplicaciones específicas.



![](P1/persona2.png)

Casimiro Buenavista: Este usuario ha sido escogido con la idea de explorar la accesibilidad que puede o no tener la aplicación - un tema comúnmente ignorado y de extrema importancia a la hora de desarrollar una interfaz.



![Método UX](img/JourneyMap.png) 1.c User Journey Map
----

Se han escogido estas dos experiencias de usuario con el objetivo de explorar dos problemas que muy facilmente podrían surgir durante el uso de la aplicación y que nos permiten reflexionar sobre que mejorar en nuestra aplicación.

![](P1/journey1.png)

![](P1/journey2.png)

![Método UX](img/usabilityReview.png) 1.d Usability Review
----
La revisión de usabilidad a través del [siguiente enlace.](P1/Usability-review.pdf)

· Valoración final: 80

· Comentario: Badi posee una buena base y un buen diseño inicial, pero posee algunos fallos que empeoran la UX Experience. Si estos puntos se tratasen, se podrían hacer relucir aún más los puntos fuertes de Badi y mejorar la experiencia de usuario significantemente.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid
----

Se plantea el siguiente Feedback Capture Grid a modo de conclusión de la última práctica.

![Feedback Capture Grid](P2/feedback.jpg)  

Se puede encontrar el análisis detallado, con el análisis de los problemas de la aplicación y la propuesta de valor alcanzada en [el siguiente enlace.](P2/readme.md)



![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
-----

### User/task matrix

Se ha hecho uso de una matriz de tareas/usuarios para enumerar las distintas tareas que se pueden realizar en la aplicación y que tipo de usuarios serán las que más las realicen.

H = high; M= medium, and L = Low

| Grupos de usuarios/tareas                         | Usuarios sin registrar | Usuarios registrados: compradores | Usuarios registrados: anunciantes |
| ------------------------------------------------- | ---------------------- | --------------------------------- | --------------------------------- |
| **Registrarse en la aplicación**                  | H                      |                                   |                                   |
| **Acceder a la aplicación**                       |                        | H                                 | H                                 |
| **Crear un perfil personal**                      | H                      |                                   |                                   |
| Modificar perfil personal                         |                        | M                                 | M                                 |
| **Abrir menú de navegación**                      | H                      | H                                 | H                                 |
| **Realizar una búsqueda de alojamientos**         | H                      | H                                 | M                                 |
| **Usar filtros de resultados según la vivienda**  | M                      | H                                 | L                                 |
| Usar filtros de resultados según perfil personal  | L                      | H                                 | L                                 |
| **Consultar detalles de anuncios de alojamiento** | H                      | H                                 | L                                 |
| Reportar un anuncio                               | M                      | M                                 | L                                 |
| Realizar una reserva                              |                        | H                                 | L                                 |
| **Publicar un anuncio**                           |                        | L                                 | H                                 |
| Modificar un anuncio publicado                    |                        | **L**                             | **M**                             |
| **Acceder a mensajes personales**                 |                        | H                                 | H                                 |
| Mandar solicitud de mensaje                       |                        | H                                 | H                                 |
| Solicitar chat de ayuda                           | M                      | H                                 | H                                 |
| **Usar chat de ayuda**                            | M                      | H                                 | H                                 |
| Buscar preguntas frecuentes (FAQ)                 | M                      | M                                 | M                                 |
| **Modificar ajustes de la aplicación**            | M                      | H                                 | H                                 |



### Sitemap

Se ha creado un sitemap en el que queda reflejado el flujo que seguirá la página a nivel de navegación.

![](P2/sitemap.png)



![Método UX](img/labelling.png) 2.c Labelling 
----

A continuación se detallan las distintas etiquetas utilizadas en el diseño de la aplicación junto con su descripción e iconografía.

| Etiqueta          | Descripción                                                  | Icono                                   |
| ----------------- | ------------------------------------------------------------ | --------------------------------------- |
| Menú emergente    | Se pulsa para abrir el menú de navegación emergente          | ![Menú emergente](P2/Icons/menu.png)    |
| Página de inicio  | Lleva a la página de inicio de la aplciación, que recoge la mayoría de las opciones de la app, como publicar anuncios o realizar búsquedas, ver notificaciones, o ver ofertas destacadas u otro contenido relevante. | ![Pagina de inicio](P2/Icons/home.png)  |
| Búsqueda          | Lleva a la páquina de Búsqueda en la que se puede realizar búsquedas por escrito, búsquedas recientes o por ubicación | ![Busqueda](P2/Icons/search.png)        |
| Realizar búsqueda | Barra de búsqueda de ofertas en la sección de Búsqueda       |                                         |
| Filtrar           | Lleva al usuario a la página de Filtrar, que permite seleccionar filtros para los resultados de la búsqueda. | ![filtrar](P2/Icons/filtrar.png)        |
| Realizar reserva  | Permite al usuario realizar una reserva en un anuncio específico. | Botón con texto                         |
| Mensajes          | Lleva a la página personal de mensajes, donde el usuario puede ver y contestar a mensajes personales o a través de grupos. | ![Mensajes](P2/Icons/letter.png)        |
| Notificaciones    | Lleva a la página de Notificaciones, donde el usuario puede revisar las notificacione srecibidas previamente. | ![notificaciones](P2/Icons/bell.png)    |
| Perfil            | Representa el perfil del usuario activo en la aplicación y adicionalmente el de otros usuarios. | ![perfil](P2/Icons/man.png)             |
| Ayuda emergente   | Se pulsa para abrir la ventana emergente de ayuda.           | ![ayuda](P2/Icons/pregunta.png)         |
| Chat de ayuda     | Abre el chat de ayuda como ventana emergente.                | ![chat de ayuda](P2/Icons/noticias.png) |
| F.A.Q.            | Representa la sección de F.A.Q. (Preguntas Frecuentes)       | ![](P2/Icons/preguntapersona.png)       |
| Configuración     | Representa la configuración tanto de la aplicación como de los perfiles y anuncios. | ![](P2/Icons/settings.png)              |



![Método UX](img/Wireframes.png) 2.d Wireframes
-----

Se plantean a continuación los wireframes creados para representar el diseño de la aplicación.

| ![PaginaInicio](P2/PaginaInicio.png) | ![](P2/Buscar.png)         | ![](P2/Resultados.png)      |
| ------------------------------------ | -------------------------- | --------------------------- |
| ![](P2/Anuncio.png)                  | ![](P2/Mensajes.png)       | ![](P2/Notificaciones.png)  |
| ![](P2/Perfil.png)                   | ![](P2/Menu-Emergente.png) | ![](P2/Ayuda-Emergente.png) |
| ![](P2/FAQ.png)                      |                            |                             |




## Paso 3. Mi equipo UX-Case Study 


![Método UX](img/moodboard.png) 3.a ¿Como se cuenta un UX-Case Study?
-----

La experiencia MuseApp nos muestra una manera más profesional de plantear un UX Case Study explorando de manera individual cada uno de los métodods UX utilizados. Se puede leer el análisis extendido [aquí.](P3/readme.md) 



![Método UX](img/landing-page.png)  3.b Logotipo
----

Se han diseñado los siguientes logotipo e icono para la aplicación desarrollada.

![](P3/logo.png)

![](P3/icono.png)

Estos serán utilizados para representar a la aplicación tanto dentro del mismo programa como en redes sociales, publicidad, y otros.

### Guía de estilo

También se ha desarrollado una guía de estilo en la que se ha definido la tipografía, iconografía, y paletade colores que usará la aplicación.

![Guía de estilos](P3/guiadeestilo.png)



![Método UX](img/guidelines.png) 3.c Guidelines
----

Se ha decidido seguir los principios de diseño de aplicaciones móviles planteados por Google. Esta decisión se explica con más detalle [en el archivo Readme de la Práctica.](P3/readme.md)



![Método UX](img/mockup.png)  3.d Video
----

Se ha realizado un vídeo en el que se sintetizan las características de nuestro proyecto, y se explica al usuario el proceso de Case Study que hemos realizado para llegar a nuestro producto.

Se puede acceder al video a través del [siguiente enlace.](https://youtu.be/N9TjQsbekaM)




## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Casos asignados
----


>>> Descripción de las asignaciones (3 UX Case Study) y enlace a  sus repositorios.

>>>> En la seccioón P4/readme.md se debe acceder además a sus respectivas hojas de evaluación y conclusiones 


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Seleccione a una de sus personas ficticias. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas


![Método UX](img/Survey.png). 4.c Ranking 
----

>>> Concluya con un ranking de los casos evaluados 

>>> Valoración personal 


## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report
----

>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  








