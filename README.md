# Coleccionismo
Diseño, análisis y desarrollo de un sitio para coleccionismo

La idea es realizar un desarrollo COMPLETO desde 0.
He visto muchos muy buenos desarrollos, pero la mayoria comienzan con el desarrollo.
La idea es comenzar antes, desde el momento de la idea, pasando por el analisis, planificacion, acuerdo con el cliente para recien ahi
comenzar con el plan de desarrollo para que al ultimo un programador comience con sitio. De paso practicar el trabajo en equipo remoto.

Veamos como sale...

# PLAN INICIAL:
 + Definir Objetivos
 + Análisis de requisitos
 + Casos de uso
 + Diseño de clases
 + Propuesta de tecnologia
 + Acuerdo de tecnologia y hosting
 + Refinacion de la Estimación
 + Programación
 + Feedback
 + Conclusiones
 + Publicación

# 1 Objetivos:
 # Generales
Desarrollar un sistema online multiusuario de  baja escala.
El diseño deberá ser modular y con la fexibilidad suficiente para permitir añadir
funcionalidades en el futuro sin demasiados costos en codificación.
Usar la documentación como un nexo entre el analista y el cliente y luego entre el analista y los programadores.

# Específcos
Diseñar el sistema de manera que se puedan añadir nuevas funcionalidades al mismo, teniendo en cuenta el constante avance de la tecnología.
Trabajar con API de terceros (para el login y para el almacenamiento de fotos)
Generar una API de salida que permitan, a sistemas externos, tener acceso a datos que provea nuestro sistema.
Ayudar a otros integrantes de la comunidad a documentar y planificar un proyecto.
Aprender a trabajar con equipos remotos.

# 2 Análisis de requisitos
Esta especicación tiene como objetivo analizar y documentar las necesidades funcionales
que deberán ser soportadas por el sistema a desarrollar. Para ello, se identificarán los requisitos
que ha de satisfacer el nuevo sistema, mediante técnicas de educción de requisitos, el estudio
de los problemas de las unidades afectadas y sus necesidades actuales. Además de identificar
los requisitos se deberán establecer prioridades, lo cual proporciona un punto de referencia para
validar el sistema final que compruebe que se ajusta a las necesidades del usuario.

# 2.1.1. Identificación de los usuarios participantes
Los objetivos de esta tarea son identificar a los responsables de cada una de las unidades
implicadas y a los principales usuarios implicados. En la organización se identificaron los
siguientes usuarios:

Coleccionista: Formado por los usuarios capaces de realizar operaciones sobre los datos del
sistema.
Administradores: Formado por aquellos usuarios que poseen la responsabilidad de gestionar
los datos del sistema, agregando nuevos datos o actualizando los ya existentes.

En todos los casos, los distintos grupos de usuarios están definidos por el dueño del sistema.
Es de destacar la necesidad de una participación activa de los usuarios del futuro sistema
en las actividades de desarrollo del mismo, con objeto de conseguir la máxima adecuación del
sistema a sus necesidades y facilitar el conocimiento paulatino de dicho sistema, permitiendo
una rápida implantación.

# 2.1.2. Catálogo de requisitos del sistema
El objetivo de la especificación es definir en forma clara, precisa, completa y verificable
todas las funcionalidades y restricciones del sistema que se desea construir. Será el canal de
comunicación entre las partes implicadas. Esta documentación estará sujeta a revisiones, hasta
alcanzar su aprobación. Una vez aprobado servirá de base al equipo para el desarrollo del nuevo
sistema.
Esta especificación se ha realizado de acuerdo al estándar IEEE Recommended Practice
for Software Requirements Specications (IEEE/ANSI 830-1998).

# 2.1.2.1. Objetivos y alcance del sistema
Desarrollar un sistema online multiusuario para la gestion de una colección. 
Diseñar vistas cuyas principales funcionalidades puedan ser ejecutadas de manera intuitiva tanto en la web como en el celular.
Implementar la tecnología de Google para el login o alguna similar.
Implementar la tecnología de Goglge fotos para la carga de las imagenes.
Generar archivos de salida que permitan, a sistemas externos, tener acceso a productos para la venta o intercambio.

# 2.1.2.2. Defniciones, acrónimos y abreviaturas
API:  Application Programming Interface (cuya traducción es Interfaz de Programación de Aplicaciones). El concepto hace referencia a los procesos, las funciones y los métodos que brinda una determinada biblioteca de programación a modo de capa de abstracción para que sea empleada por otro programa informático.


# 2.1.2.3. Descripción general
Esta sección presenta una descripción general del sistema con el fin de conocer las funciones
que debe soportar, los datos asociados, las restricciones impuestas y cualquier otro factor que
pueda influir en la construcción del mismo.

Desarrollar un sistema online multiusuario para la gestion de una colección. 
Los coleccionista podran registrarse y acceder al sitio donde podran dar de alta su colección, podran elegir si la misma sera publica (cualquier usuario puede verla) o privada (solo podra verla su dueño).
Para el login usaremos una API externa provista por google.
Podran cargar sus productos, detalles de los mismos y fotos.
Las fotos deben estar alojadas en un servidor externo y acceder por medio de una API que asi lo permita.
Se debe poder poner en venta o para canje los productos.
La aplicacion debe tener un buscador para productos que se encuentren en venta o canje, ademas los mismos deben poder ser accedidos por cualquier sistema externo usando la API que brindaremos.

# 2.1.2.4. Requisitos funcionales
(pendiente)

# 2.2. Suposiciones y dependencias

Suposiciones: Se asume que los requisitos en este documento son estables una vez que sean aprobados por el administrador del Sistema. Cualquier petición de cambios en la especificación debe ser aprobada por todas las partes que intervienen y será gestionada por el equipo de desarrollo.
Dependencias: No posee dependencias.

# 2.3. Requisitos de usuario y tecnológicos
Requisitos de usuario: Los usuarios serán las personas que trabajan en el centro de
operaciones de EDET. Existirá un grupo de administradores que se encargarán de diferentes
tareas en cuanto a la gestión de datos del sistema. Las interfaces deben ser intuitivas, fáciles de
usar y amigables de modo que con breves instrucciones los usuarios sean capaces de usarla.
Además se deberá tener en cuenta el diseño de las interfaces del sistema actualmente en
funcionamiento con la idea de que el nuevo sistema adopte ciertos procedimientos y estándares
ya establecidos.
Requisitos tecnológicos: La aplicación se ejecutará sobre un esquema cliente/servidor, con
los procesos e interfaz de usuario ejecutándose en los clientes y éstos solicitando requerimientos
al servidor que cumple su proceso. El usuario podrá ejecutar el sistema en cualquier sistema
operativo en donde se pueda ejecutar un navegador WEB que soporte HTML5, Websocket y
pueda interpretar código javascript estándar. Para poder acceder al sistema el usuario debe
tener una conexión a la red en donde se encuentre el servidor.

# 2.4. Requisitos de interfaces externas
Interfaces de usuario: Interfaces hardware: Ratón, teclado estándar y monitor a color con una resolución mínima
de 1024 x 768 pixeles.
Interfaces software: Los datos del sistema serán obtenidos a partir de una API que estará implementada en el servidor. La API validará tanto el pedido como el envío de información entre los usuarios y los módulos del sistema.

# 2.5. Requisitos de rendimiento

El tiempo de respuesta de la aplicación a cada función solicitada por el usuario no debe ser superior a los 10 segundos. El tiempo de respuesta a los listados dependerá de la cantidad de datos solicitados.

# 2.6. Requisitos de desarrollo
El ciclo de vida será el de prototipado evolutivo utilizando una metodología V-Script, debiendo orientarse hacia el desarrollo de un sistema flexible que permita incorporar de manera sencilla cambios y nuevas funcionalidades.

# 2.7. Restricciones de diseño
Seguridad: La seguridad de los datos estará implementada en el servidor. La conexión del servidor estará cifrada, y para la autenticación se usará el mecanismo de tokens
