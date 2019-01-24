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
Desarrollar un sistema online multiusuario para la gestion de una colección. 
El diseño deberá ser modular y con la fexibilidad suficiente para permitir añadir
funcionalidades en el futuro sin demasiados costos en codificación.

# Específcos
Diseñar el sistema de manera que se puedan añadir nuevas funcionalidades al mismo,
teniendo en cuenta el constante avance de la tecnología.
Diseñar vistas cuyas principales funcionalidades puedan ser ejecutadas de manera intuitiva
tanto en la web como en el celular.

Desarrollar una herramienta que permita cargar datos y fotos de la colección y buscarlos facilmente, permitiendo distintas opciones de visivilidad y asi como opciones de intercambio y/o venta.
Implementar la tecnología de Google para el login o alguna similar.
Implementar la tecnología de Goglge fotos para la carga de las imagenes.
Generar archivos de salida que permitan, a sistemas externos, tener acceso a productos para la venta o intercambio.

Ayudar a otros integrantes de la comunidad a documentar y planificar un proyecto.
Aprender a trabajar con equipos remotos.

 + 

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

El principal objetivo del módulo a desarrollar es permitir a los usuarios la gestión de los
datos obtenidos a partir de otros módulos del sistema SCADA DIGICOM. El sistema deberá
permitir a los usuarios conocer en tiempo real el estado de la red eléctrica de la provincia de
Tucumán; para ello debe gestionar los datos provenientes de un gran número de equipos de
medición distribuidos a lo largo de la provincia.
El usuario deberá conocer el estado actual de cada equipo, permitiéndole tomar decisiones
sobre las acciones a ejecutar para lograr el correcto funcionamiento de la red. Para esto, también
debe ser capaz de ejecutar ordenes sobre los equipos.

# 2.1.2.2. Defniciones, acrónimos y abreviaturas
no se han definido de momento

# 2.1.2.3. Descripción general

Esta sección presenta una descripción general del sistema con el n de conocer las funciones
que debe soportar, los datos asociados, las restricciones impuestas y cualquier otro factor que
pueda inuir en la construcción del mismo.
