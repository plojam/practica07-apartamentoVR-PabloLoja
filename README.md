# Practica04---Mi-Agenda-Telefonica

## 4.	Generar informe de los resultados en el formato de prácticas. Debe incluir:

### a)	El desarrollo de cada uno de los requerimientos antes descritos. 
### b)	La evidencia del correcto diseño de la escena 
### c)	La evidencia del correcto funcionamiento de la aplicación 
### d)	El informe debe incluir conclusiones apropiadas. 
### e)	En el informe se debe incluir la información de GitHub (usuario y URL del repositorio de la práctica) 
### f)	En el informe se debe incluir la firma digital de los estudiantes

El apartamento resultado es el siguiente:

![1](/ImagenesReadme/1.jpg?raw=true "Apartamento")

Para esto se usaron los siguientes objetos.

![2](/ImagenesReadme/2.jpg?raw=true "Objetos")

Se crearon varios materiales que se usaron en objetos dentro del departamento, los objetos creados a lo largo de la práctica son:

![3](/ImagenesReadme/3.jpg?raw=true "Materiales")

Se creo un tablero de ajedrez, para esto se agregó un objeto 3D (cubo), luego se cambiarn los tamaños del mismo para darle la forma correcta, para finalizar, se le asigno el material de tablero de ajedrez, el resultado de este proceso es el siguiente:

![4](/ImagenesReadme/4.jpg?raw=true "Tablero")

Se crearon cuatro cuadros que representan a la familia, para ello se descargo un modelo en “Asset Strore”:

![5](/ImagenesReadme/5.jpg?raw=true "Tienda")

Luego, usando texturas modificadas provenientes de este modelo, se agregaron los cuadros requeridos, el resultado es el siguiente:

![6](/ImagenesReadme/6.jpg?raw=true "Familia")

Se creo un globo terráqueo usando un modelo cargado en el proyecto “GlobeHolder”, agregándole una esfera como un hijo de este modelo, luego se agrego el material del planeta para mejorarlo visualmente, esto quedo de la siguiente manera:

![7](/ImagenesReadme/7.jpg?raw=true "GloboT")

Para este globo terráqueo se agregaron dos animaciones, una que representa el movimiento horizontal de la esfera y otro que mantiene estático al globo.

![8](/ImagenesReadme/8.jpg?raw=true "MovimientoG")

Se enlazaron estas animaciones y se creo un trigger para que en la ejecución el globo pueda para o volver a rotar, luego se agrega el script TriggerAnimation que permite esta característica.

![9](/ImagenesReadme/9.jpg?raw=true "MovimientoG2")

También, se agrego un reloj el cual se animará de la misma forma que el globo terráqueo.

![10](/ImagenesReadme/10.jpg?raw=true "Reloj")

Para las animaciones se escalo el tiempo, en el caso del horero, tardara 24 minutos en completar una vuelta completa, por lo que su animación durara 1400 segundos reales en completarse.

![11](/ImagenesReadme/11.jpg?raw=true "Horero")

Para el minutero, se animo la manecilla de una vuelta completa, completando una hora tan solo un minuto, por lo que la animación durara 60 segundos:
 
![12](/ImagenesReadme/12.jpg?raw=true "Minutero")

Y para el segundero, la manecilla dará la vuelta completa en un segundo, además en esta manecilla se le agrego una animación extra que realiza el giro inverso a las manecillas del reloj.

![13](/ImagenesReadme/13.jpg?raw=true "Segundero")

Estas dos animaciones están juntas con un trigger el cual permitirá al usuario cambiar la rotación del segundero en ejecución.

![14](/ImagenesReadme/14.jpg?raw=true "TriggerSegundero")

También, se creo un shader que permita que un objeto cambie de color con el tiempo, en este caso, se agrego un sofá que su color cambia en tonalidades de verde.

![15](/ImagenesReadme/15.jpg?raw=true "Sofa")

A este shader se le cambio la propiedad albedo, lo cual permite dar color dinámicamente a un objeto, luego se creo un material que contiene este shader para terminar asignándole este material al objeto 3D dentro del apartamento.

![16](/ImagenesReadme/16.jpg?raw=true "CambiaColor")

Para poder poner una cámara que tenga movimiento al momento de su ejecución, se agregó una cámara normal dentro de GvrEditorEmulator.prefab, esto es propio de Google VR, por lo que es una configuración predefinida, lo que se debe hacer es colocarlo en la misma posición de la cámara para evitar cualquier tipo de error.

![17](/ImagenesReadme/17.jpg?raw=true "Camara")

Para dar claridad al proyecto, se colocaron luces dentro y fuera del apartamento, se agrego un Directional light para simular luz del sol, colocándole un angulo apuntando al apartamento. También se agregaron Point light para simular focos dentro del apartamento.

![18](/ImagenesReadme/18.jpg?raw=true "Luces")

Para la configuración de estas luces, se pone en modo Baked y con un shadow type llamado “Soft Shadows”, lo que permitirá generar sombras antes antes de ejecutar o exportar el proyecto, lo que le permitirá ser menos pesado.

![19](/ImagenesReadme/19.jpg?raw=true "ConfLuces")

Luego en la pestaña lighting se puede configurar algunos aspectos para mejorar y dar mas realismo a los objetos dentro del proyecto, luego, se presiona el botón Generate Lighting para procesar la luz.

![20](/ImagenesReadme/20.jpg?raw=true "ConfLighting")

Por último, para que la cámara muestre un fondo (en las ventanas), en la pestaña lighting, se agrega un skybox antes generado de un fondo que se quiera usar.

![21](/ImagenesReadme/21.jpg?raw=true "AgregarSkybox")

Para generar este skybox, se genera un material con un shader Skybox/Panoramic en donde se agregara la textura que se quiere poner, luego esto se agrega a la pestaña lighting.

![22](/ImagenesReadme/22.jpg?raw=true "Skybox")

Para el audio, se descargo un audio de ambientación de internet y se lo coloco en las paredes del apartamento.

![23](/ImagenesReadme/23.jpg?raw=true "Audio")

Luego, se generó un script que permite quitar el audio en la ejecución, este script se agrega al audio dentro del proyecto para su funcionamiento.

![24](/ImagenesReadme/24.jpg?raw=true "Audio2")

![25](/ImagenesReadme/25.jpg?raw=true "ConfAudio")

El resultado es el siguiente:

Unity:

![26](/ImagenesReadme/26.jpg?raw=true "Unity")

Android:

![27](/ImagenesReadme/27.jpg?raw=true "Android")
