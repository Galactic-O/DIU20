# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU2_EscuadrónMapache.  Curso: 2019/20 

Proyecto: Yutaku

Descripción: Aplicación movil de alquiler de viviendas en la que el usuario pdorá realizar búsquedas de piso con filtros de hhabitación y personas, además de mantenerse en contacto y conocer a otras personas con las que vivir.

Logotipo: <img src="P3/icono.png" alt="Logotipo" style="zoom:2%;" />

Miembros:
 * :bust_in_silhouette:   [Pablo Vallejo Ruiz](https://github.com/Galactic-O)        :octocat:     

-----

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil, haciendo uso de herramientas y entregables descritos en [el siguiente CheckList.](https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434




# Proceso de Diseño 

# Paso 1. UX Desk Research & Analisis 


User Research: Para obtener información sobre nuestro cliente objetivo y sus necesidades realizaremos un User Research, consistente en los siguiente Métodos.



## ![Método UX](img/Competitive.png)1.a Competitive Analysis


Observaremos aplicaciones para compartir alojamiento - permiten buscar habitaciones para compartir y poner en alquiler nuestras ubicaciones. Badi es una app móvil gratuita, que se diferencia de otras apps por su sistema de perfiles, que facilita encontrar personas de gustos similares, asegurando una experiencia de convivencia mucho más personalizada.



## ![Método UX](img/Persona.png) 1.b User Personas


Hemos creado 2 user personas para ayudarnos a identificar las metas y frustraciones de nuestro usuario objetivo. Hemos creado los dos siguientes user personas:

El primer usuario, Esther:

![](P1/persona1.png)

Se ha escogido este usuario para representar a un demográfico bastante común, una juventud sociable pero con poca experiencia a la hora de usar aplicaciones específicas.

Y el segundo usuario, Casimiro:

![](P1/persona2.png)

Este usuario ha sido escogido con la idea de explorar la accesibilidad que puede o no tener la aplicación - un tema comúnmente ignorado y de extrema importancia a la hora de desarrollar una interfaz.




## ![Método UX](img/JourneyMap.png) 1.c User Journey Map


Se han escogido estas dos experiencias de usuario con el objetivo de explorar dos problemas que muy facilmente podrían surgir durante el uso de la aplicación y que nos permiten reflexionar sobre que mejorar en nuestra aplicación.

![](P1/journey1.png)

![](P1/journey2.png)




## ![Método UX](img/usabilityReview.png) 1.d Usability Review


A partir de lo observado en las experiencias de usuario que hemos planteado, y después de que nuestro equipo realizase un análisis práctico de la página ejemplo, se ha redactado la siguiente Usability Review. La revisión de usabilidad, junto con el informe de usabilidad extendido, se pueden ver a través del [siguiente enlace.](P1/Usability-review.pdf)

· Valoración final: 80

· Comentario: Badi posee una buena base y un buen diseño inicial, pero también algunos fallos que empeoran la UX Experience. Si estos fallos se tratasen, se podrían hacer relucir aún más los puntos fuertes de Badi y mejorar la experiencia de usuario significantemente.





# Paso 2. UX Design  


## ![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid


Se ha redactado el siguiente Feedback Capture Grid con el objetivo de recopilar toda la información obtenida hasta ahora, para facilitarnos su uso y su análisis.

![Feedback Capture Grid](P2/feedback.jpg)  

Se puede encontrar el análisis detallado, con el análisis de los problemas de la aplicación y la propuesta de valor alcanzada en [el siguiente enlace.](P2/readme.md)

Una vez terminado el User Research y tras haber recabado toda la información de las necesidades y frustaciones de los usuarios, pasamos al diseño de nuestra aplicación.



![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
------

-------

### Feature Prioritisation (User/task matrix):

Se ha hecho uso de una matriz de tareas/usuarios para enumerar las distintas tareas que se pueden realizar en la aplicación y que tipo de usuarios serán las que más las realicen. Esto nos ayudará a saber en que tareas centrar nuestra atención a la hora de diseñar la app.

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



### Sitemap:

Se ha creado un sitemap en el que queda reflejado el flujo que seguirá la página a nivel de navegación. En él quedan representadas las tareas que hemos considerado más relevantes para el uso de la aplicación.

![](P2/sitemap.png)




## ![Método UX](img/labelling.png) 2.c Labelling 


A continuación detallamos las distintas etiquetas utilizadas en el diseño de la aplicación junto con su descripción e iconografía.

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



## ![Método UX](img/Wireframes.png) 2.d Wireframes


Se han creado los primeros prototipos de la aplicación, en forma de wireframes para representar su diseño.

| ![PaginaInicio](P2/PaginaInicio.png) | ![](P2/Buscar.png)         | ![](P2/Resultados.png)      |
| ------------------------------------ | -------------------------- | --------------------------- |
| ![](P2/Anuncio.png)                  | ![](P2/Mensajes.png)       | ![](P2/Notificaciones.png)  |
| ![](P2/Perfil.png)                   | ![](P2/Menu-Emergente.png) | ![](P2/Ayuda-Emergente.png) |
| ![](P2/FAQ.png)                      |                            |                             |





# Paso 3. Mi equipo UX-Case Study 



Para mejorar nuestro UX Case Study, y de acuerdo a la práctica, se ha reestrcuturado el formato del archivo readme.md para dotarlo de una estructura más ordenada.



## ![Método UX](img/moodboard.png) 3.a ¿Como se cuenta un UX-Case Study? Análisis del UX Case Study MuseMap Street Art App


La experiencia MuseApp nos muestra una manera más profesional de plantear un UX Case Study explorando de manera individual cada uno de los métodods UX utilizados. Se puede leer el análisis extendido [aquí.](P3/readme.md) 



## ![Método UX](img/landing-page.png)  3.b Logotipos

Se han diseñado los siguientes logotipo e icono para la aplicación desarrollada.

![](P3/logo.png)

![](P3/icono.png)

Estos serán utilizados para representar a la aplicación tanto dentro del mismo programa como en redes sociales, publicidad, y otros.


### Guía de estilo:

También se ha desarrollado una guía de estilo en la que se ha definido la tipografía, iconografía, y paleta de colores que usará la aplicación.

![Guía de estilos](P3/guiadeestilo.png)




## ![Método UX](img/guidelines.png) 3.c Guidelines

A la hora de realizar el diseño final de la aplicación, se ha optado por seguir los principios de diseño de aplicaciones móviles planteados por Google. Esta decisión se explica con más detalle [en el siguiente enlace.](P3/readme.md)




## ![Método UX](img/mockup.png)  3.d Video

Se ha creado un vídeo en el que se sintetizan las características de nuestro proyecto, y se explica al usuario el proceso de Case Study que hemos realizado para llegar a nuestro producto.

Se puede acceder al video a través del [siguiente enlace.](https://youtu.be/N9TjQsbekaM)



-----



# Paso 4. Evaluación 

## ![Método UX](img/ABtesting.png) 4.a Casos asignados

### Caso 1: DIU1.Cohete - Pazifika

Se analiza el UX Case Study presentado por el equipo DIU1.Cohete, que se puede encontrar en [el siguiente enlace de GitHub](https://github.com/migue99angel/DIU20).

El equipo Cohete nos presenta **Pazifika**, una aplicación para dispositivos móviles que permite buscar compañeros con los que organizar viajes de manera sencilla y ágil, ofreciendo opciones de filtrado para viajes y una interfaz clara y limpia.

Puedes leer el análisis del proyecto, y  las hoja de evaluación en formato PDF y Excel, [en el siguiente enlace](P4/readme.md). Puedes encontrar. 

### Caso 2: DIU2.GMI - Global Home

Se analiza el UX Case Study presentado por el equipo DIU2.GMI, que se puede encontrar en [el siguiente enlace de GitHub](https://github.com/GonzaloMartinezIanez/DIU2-GMI).

El equipo GMI nos presenta **Global Home**, una aplicación para dispositivos móviles que permita a usuarios de distintas partes del mundo buscar un anfitrión donde alojarse o ofrecer su casa a otro usuario, todo esto destinado a personas que buscan alojamiento por trabajo o estudios.

Puedes leer el análisis del proyecto, y  las hoja de evaluación en formato PDF y Excel, [en el siguiente enlace](P4/readme.md).

### Caso 3: DIU3.UltraMerino

Inicialmente se nos pidió realizar una Review del UX Case Study planteado por el equipo [DIU3.Bolargo](https://github.com/iscoct/DIU20). Sin embargo, este caso no se encuentra completo, faltándole el Paso 3 de Mejora de UX Case Study. Por tanto hemos decidido analizar otro caso del mismo grupo (DIU3), optando por el caso del equipo DIU3.UltraMerino, el cual podemos encontrar [en el siguiente enlace de GitHub](https://github.com/merino25/DIU20).

El equipo UltraMerino nos presenta **OCIUS,** una aplicación para dispositivos móviles destinada a la creación y asistencia a eventos de ocio en las casas de sus propios usuarios, fomentando el compartir experiencias únicas y conocer gente nueva.

Puedes leer el análisis del proyecto, y  las hoja de evaluación en formato PDF y Excel, [en el siguiente enlace](P4/readme.md). 



## ![Método UX](img/usability-testing.png) 4.b User Testing


Se ha seleccionado a Casimiro Buenavista, uno de los User Personas descritos en el Paso 1 de nuestro proyecto, para plantear situaciones con los diseños ofrecidos por los equipos y ver posibles problemas o puntos de interés. Puede ver los casos planteados [en el README de la práctica](P4/readme.md).



## ![Método UX](img/Survey.png). 4.c Ranking 



A partir de la puntuación obtenida en las reviews de los casos asignados, hemos creado el siguiente ranking:

|          1º PUESTO           |        2º PUESTO        |       3 PUESTO       |
| :--------------------------: | :---------------------: | :------------------: |
| DIU3.UltraMerino (66 puntos) | DIU1.Cohete (52 puntos) | DIU2.GMI (46 puntos) |

Se puede leer la conclusión y valoración personal de estas valoraciones [en el README de la práctica](P4/readme.md).



# Paso 5. Evaluación de Accesibilidad  


## ![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report


>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 



## Conclusión final / Valoración de las prácticas


>>> (90-150 palabras) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  