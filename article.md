[![N|Header](https://raw.githubusercontent.com/CristianMendoza99/Cristian/main/header-articles.jpg)](https://www.linkedin.com/company/iassoftware/)

# Desarrollo de apps multi-plataforma vs nativas

El desarrollo de aplicaciones móviles se ha vuelto un boom con el pasar de los años, para nadie es un secreto que el mayor tráfico de usuarios viene dese los dispositivos móviles, esto dada la facilidad que tienen y su rapidez, y aquí entran muchos actores a jugar un papel muy interesante.

Desde los inicios de la web cuando teniamos todo en un solo lugar, hasta tiempo después cuando logramos una separación de roles como lo es ahora frontend y backend, hemos llegado a un punto en donde del lado del frontend tenemos que pensar en un nicho que cada día toma más fuerza, los usuarios que van a utilizar nuestra aplicación desde su celular, siendo un 58.99% el porcentaje de usuarios totales que utilizarán nuestra app desde dispositivos móviles.

![Alt text](statistic_id277125_share-of-global-mobile-website-traffic-2015-2022.png)

## ¿Qué se está haciendo para atender a estos usuarios?

Cuando este problema se hizo evidente no se contaba con muchas opciones para el desarollo de aplicaciones que pudieran ser usadas desde dispositivos móviles, en su mayoría la única opción era el desarollo de aplicaciones nativas lo cual ya les adelanto que si bien tiene un nivel de performance superior a los demás resulta dificil y costoso conseguir talento que pueda sumarse a estos proyectos, es por esto que surgieron alternativas que buscan lograr soluciones parciales a las necesidades del proyecto, dado que ninguna solución es mejor o peor, todo es adaptable a las etapas del proyecto y a la necesidad persé que tiene el proyecto de acceder a según que recursos del propio dispositivo móvil.

![Alt text](app-development.png)

### PWA's :

El desarrollo web sin duda es una de las más grandes areas de la programación, esto ha permitido que se desarrollen muchas estrategias para atacar este problema. Para el año 2015 empezó a hablarse de un término que fue cogiendo cada vez más fuerza, las PWA's. Por sus siglas son Progressive Web Apps, son aplicaciones que corren a través del navegador y están pensadas para que sean utlizadas principalmente desde dispositivos móviles sin consumir muchos recursos, veamos algunas de las principales ventajas que presentan las PWA's:

- No requiere de una instalación dado que corre en el navegador
- Posicionamiento en web, pueden ser optimizadas de manera más sencilla para los distintos buscadores.
- Según como esté pensada la PWA en algunos casos se pueden manejar supuestos para cuando haya una desconexión de la red, lo que conocemos como Network independence
- Diseño responsivo, el desarrollo de las PWA se logra mediante tecnologías como media queries y viewports lo que permite un manejo más acertado para las distintas pantallas que puede tener el usuario (Desktop, tablet, mobile o cualquier otro)
- Las PWA's modernas cuentan con opciones que permiten desde tu propio navegador generar accesos directos desde tu dispositivo móvil y dan la apariencia de tener una app instalada lo que mejora considerablemente la experiencia de usuario y el acceso a la misma aplicación

Las PWA’s sin duda son una alternativa muy buena para proyectos que requieran este tipo de cross-platform en donde el alcance de sus usuarios sea mucho mayor abarcando tanto la web como dispositivos móviles sin la necesidad de acceder a recursos muy específicos.

![Alt text](pwa.png)

¡Aquí hay algunos ejemplos de empresas que actualmente cuentan con una PWA!

- Starbucks
- BMW
- Pinterest
- Spotify

## Native apps :

En la actualidad contamos una gama muy extendida de dispositivos móviles y estos a su vez cuentan internamente con sistemas operativos, algunos dominan sobre otros en el mercado por sus características particulares, cada uno de estos tiene funcionalidades propias que hace del propio dispositivo algo distintivo ya sea a nivel de hardware en la medida en que lucen distinto o por lo que te permitan hacer y su facilidad de uso.

Si bien, sabemos que existen distintos sistemas operativos para dispositivos móviles, en este caso hablaremos de los que indudablemente dominan el mercado, nos referimos a Android y iOS. Estos dos son los líderes en la actualidad y es por esto que gran parte del desarrollo móvil nativo se enfoca en estos dos SO’s.

Una de las principales cualidades que tiene el desarrollo nativo es un gran performance sobre cualquier otro tipo de desarrollo, esto se debe a que se su compilación se hace en código fuente del SO, lo cual brinda un escalón más alto en rendimiento ya que el desarrollo está pensado nativamente para un dispositivo móvil en específico. Además de esto el rendimiento es muy bueno debido a que se puede acceder a todos los recursos propios del SO, y en según qué casos puedes crear módulos propios para crear funcionalidades muy específicas que demanden la lógica de tu negocio.

El desarrollo de aplicaciones nativas ha ido evolucionado teniendo en cuenta que si bien para el desarrollo en dispositivos iOS se contaba con módulos en Objective-C hoy ha evolucionado a un lenguaje un poco más intuitivo y con una curva de aprendizaje menos pronunciada como lo es Swift, también tenemos el mismo ejemplo para Android, en donde inicialmente fue construido en Java, esto ha cambiando a lo que hoy conocemos como Kotlin, aun así a día de hoy, el desarrollo nativo no desconoce estos lenguajes predecesores, de hecho se requiere conocerlos ya que en muchos casos es necesario codificar en dichos lenguajes para la creación de módulos muy específicos que permitan alcanzar altos niveles de rendimiento acorde a los requerimientos y escalabilidad de los proyectos.

### ¿Por qué hacer desarrollo nativo?

- Personalización avanzada
- Mayor seguridad
- Escalabilidad
- Mejor rendimiento
- Facilidad de liberar en tienda
- Reducción de bugs / Manejo de errores
- Mejora en la UX

La mayoría de las empresas que cuentan con una app llegan a un punto en donde requieren hacer este tipo de migración al desarrollo nativo, es por esto que posiblemene cualquiera de las empresas top mundial que tengas en mente ya cuenten con una app nativa, aun así acá comparto unos ejemplos que te pueden ayudar:

- WhatsApp
- Pokemon GO
- Waze
- Tesla
- Spotify

![Alt text](native-apps.png)

## Hybrid mobile app development:

Una de las principales dificultades que tiene el desarrollo nativo es la dificultad de encontrar talento especializado en estos lenguajes, lo que hace que conseguir un grupo de desarrollo con estas skills resulte en una tarea muchas veces difícil y que acarrea un gran costo dada la baja oferta de desarrolladores. Además de esto, si ya resulta complejo conseguir un equipo de trabajo para el desarrollo de una app en un SO, será igual de difícil hacerlo para los demás dispositivos móviles, es por esto que han ido saliendo iniciativas de proyectos que buscan dar una posible solución.

Las PWA's son bastante útiles, pero como ya hemos visto, llega un punto en donde estas se quedan cortas a nivel de acceso en los recursos propios del dispositivo que limita la aplicación, en este punto ya entendemos que el desarrollo de apps nativas sin duda es el que a nivel de rendimiento y demás factores es la mejor, pero también es el desarrollo más costoso y es importante reconocer cuando un proyecto está o no en etapa de este desarrollo, muchas veces las ideas deben crearse rápidamente y probar si funcionan o no.

Por estas razones, con el tiempo han ido saliendo nuevas iniciativas para proveer a la comunidad herramientas / tecnologías que permitan el cross platform development, desarrollar aplicaciones móviles multiplataforma, independientemente el SO que maneje el dispositivo, la aplicación igual va a compilar. Tenemos opciones como React Native la cual ha sido una de las tecnologías con mayor adopción dado que la premisa base es que todo aquel que use React js en la web, puede migrar a un proyecto en React Native sin mayores dificultades, también tenemos el caso de Flutter que permite un desarrollo multiplataforma con una sintaxis muy amigable y que cada vez toma más fuerza por el rendimiento que ofrece.

![Alt text](hybrid-apps.png)

Las aplicaciones que son construidas con tecnologías multiplataforma son increíbles, ya que nos permiten el acceso a recursos propios del dispositivo como desarrollar simultáneamente en varios dispositivos y ofreciendo un rendimiento bastante aceptable, cada día nacen más y más proyectos creados desde un inicio con tecnologías de este tipo por las ventajas que presenta, muchas veces los proyectos en su fase inicial se crean con estas herramientas pero cuando alcanzan un nivel de maduración suficientemente alto y la demanda de la aplicación requiere mayores niveles de performance se suelen hacer migraciones a tecnologías nativas, aun así en la mayoría de los casos el desarrollo híbrido presenta mayores ventajas para los equipos de desarrollo.

Actualmente muchas empresas estan apostando por este tipo de desarrolo al menos en sus etapas más tempranas, algunas de estas son:

- Microsoft teams
- Discord
- Evernote
- Uber
- JustWatch

Las tecnologías híbridas sin ninguna duda están en un gran crecimiento, muchos proyectos se suman a esta tecnologías, el estado de éstas para el 2021 se tiene condensado según la última encuesta realizada por Statista en donde muestra que como les mencionaba, Flutter y React Native son las tecnologías que más se utilizan en el desarrollo de aplicaciones móviles multiplataforma, aun así se empieza a ver que muchas otras propuestas se suman al ecosistema.

![Alt text](technologies.png)

## Conclusiones

No podemos sugerir una de las tres opciones como la única y mejor sobre las demás, si bien cada una de estas tiene aplicaciones distintas según lo que demande cada proyecto / aplicación, la comunidad cada vez más tiende al desarollo de aplicaciones híbridas esto pensando siempre en que las aplicaciones puedan escalar de la mejor manera, si bien muchas veces desde los inicios de los proyectos se tiene una idea muy clara de lo que se va a requerir, las PWA's son una opción muy buena, en muchos otros casos la opción tiende a ser las aplicaciones híbridas y como mencionamos arriba, si tu proyecto demanda poder de rendimiento, acceder a recursos muy específicos del dispositivo o demás puntos clave puedes pensar en el desarrollo / migración de tu app a algo más nativo y enfocado en los SO's que requieran tus usuarios.

Por útlimo queremos compartir una pequeña tabla en donde se resumen las comparaciones entre estas formas de desarrollo, teniendo en cuenta que la opción que se requiera podrá incurrir en costos más altos o más bajos correspondientemente al proyecto, aquí se relacionan los puntos más importantes de cada una.

|               Parámetros                |         Hybrid         |         Native         |   PWA    |
| :-------------------------------------: | :--------------------: | :--------------------: | :------: |
|           Codigo reutilizable           |          Alto          |          Bajo          |   Alto   |
|       Componentes pre-estilizados       |          Alto          |         Medio          |   Alto   |
|          Third-party-libraries          |          Alto          |          Alto          |   alto   |
|               Popularidad               |          Alta          |         Medio          |   Alta   |
|               Performance               |         Medio          |          Alto          |  Medio   |
| Funcionalidades nativas del dispositivo |          Bajo          |          Alto          |   Bajo   |
|              Distribución               | Tienda del dispositivo | Tienda del dispositivo |   URL    |
|                 Soporte                 |        Limitado        |        Muy alto        | Limitado |
|                 Costos                  |         Medio          |          Alto          |  Medio   |
