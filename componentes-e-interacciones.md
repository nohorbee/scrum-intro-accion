# Componentes e interacciones

Scrum es un framework poco prescriptivo. Lo único que define es un conjunto de componentes e interacciones entre los mismos.
Si bien al acostumbrarnos a Scrum, dejamos de pensar en los conceptos teóricos detrás de cada uno de ellos, vale la pena recopilarlos al menos una vez (y recomiendo, recordarlos de vez en cuando).

Los 3 **componentes** principales (o categorías) son:
- Equipo y roles
- Eventos
- Activos (artifacts)

Las **interacciones** entre los mismos hacen referencia a la dinámica misma de Scrum. Por ejemplo: Le Product Owner (un rol del equipo) interactúa con el Product Backlog (un activo) para ordenarlo, depurarlo y brindar transparencia a todos los interesados.

## Equipo y roles

### Características

Un equipo Scrum es un grupo de personas trabajando colaborativamente para construir un producto. Hay algunas características (teóricamente obligatorias) a las que el equipo debe responder:

- Auto-organizado: El equipo elige la mejor manera de realizar el trabajo. Desde la selección de tareas a realizar hasta las herramientas, procesos, metodologías, etcétera. Suele resonar, ante preguntas tales como "¿cómo hacemos esto?", la respuesta "Preguntale al equipo". Para lograrlo, debe contar con la confianza y **autonomía** para tomar estas decisiones (ej: ¿Cómo estimar tareas? ¿Cuáles son las buenas prácticas técnicas? ¿Qué herramientas para gestión de proyecto? ¿Cómo se distribuye el trabajo?).

- Multifuncional: A diferencia con otros tipos de organizaciones, en donde distintos roles se agrupan en distintos equipos, en Scrum, el equipo debe contar con todos los roles necesarios para realizar el trabajo. Es por eso que es común encontrar en estos equipos, gente de diferentes disciplinas (investigadoris, diseñadoris, programadoris, analistas, QA, DevOps, ..., N).

### Roles

Los roles de un equipo Scrum son solo 3:
- Product Owner: Es le responsable de maximizar el valor del trabajo que se está realizando. Para lograrlo, debe mantener el backlog de producto siempre **ordenado (por prioridad), claro(refinando los requerimientos) y transparente(para otras áreas de la organización)**.
- Development Team: Es el responsable de construir el producto (los incrementos de producto de cada Sprint). Adem;as de autónomo y auto-organizado, se espera que el equipo se considere responsable como tal (y que no haya responsabilidades individuales). Se recomienda que los equipos de desarrollo sean de 3 a 9 personas (menos, se traduce a un gasto innecesario de gestión; más, lo vuelve inmanejable). [Esta regla se le atribuye, muchas veces, al CEO y Co-fundador de Amazon, Jeff Bezos](https://buffer.com/resources/small-teams-why-startups-often-win-against-google-and-facebook-the-science-behind-why-smaller-teams-get-more-done), y si bien puede parecer una prescripción algo rígida, en mi experiencia hasta ahora, la encuentro bastante acertada.
- Scrum Master: Debe asegurar que el equipo entiende y utiliza correctamente Scrum. Actúa como guía para la organización en cuanto a la teoría, práctica y reglas de la herramienta. Se lo considera un lider facilitador (lo cual es bastante frecuente en Scrum y herramientas ágiles en general).


## Eventos

Los eventos Scrum (a veces mencionados como "ceremonias", vaya une a saber por qué) están definidos y orquestados para proveer **transparencia**, facilitar la **inspección** y asegurar la **adaptabilidad**, los 3 principios básicos del [control empírico de procesos](./definiciones-scrum.md) (del cual Scrum forma parte). Suelen describirse en función a su intención, enfoque, reglas y asistentes. Son:
- Sprint
- Sprint planning
- Daily meeting
- Sprint reviews
- Sprint retrospective

##### Acerca de las duraciones y el concepto de Timebox
Todos los eventos de scrum tienen duraciones fijas respondiendo al concepto de Timebox. Este concepto, en breve, dice que no se puede estirar un evento por ningún motivo, razón, o circunstancia. Lo que no se llega a hacer en el tiempo establecido, se hace en una ocurrencia posterior el mismo evento. El concepto de timebox se aplica constantemente para evitar caer en la [ley de Parkinson](https://en.wikipedia.org/wiki/Parkinson%27s_law) que dice que "El trabajo se expande tanto como  haya tiempo disponible para hacerlo". Cuando el tiempo es acotado, los equipos sienten un sentido de *urgencia* que los ayuda a mantener el foco en lo que se está desarrollando. Esta *urgencia* tiene que mantenerse como un concepto positivo, para lo cual es importante trabajar en la motivación, los espacios seguros, y el compromiso de todes les involucrades.

### Sprint
Es el pulso de Scrum. Es un ciclo de tiempo fijo y definido (por el equipo) en el cual se desarrolla todo el trabajo. No hay trabajo en Scrum que esté fuera del Sprint. Un Sprint finaliza en el mismo momento que comienza el siguiente.

#### Reglas

- Duración: Fija y definida por el equipo. Se recomienda que sea menor a 1 mes (la norma en la actualidad es de 2 semanas).
- Cerrada: No se acepta trabajo nuevo durante un Sprint. Esto no debería representar un problema ya que, al ser cortas, ese trabajo se podría realizar en el siguiente Sprint.
- Cancelación: Le Product Owner puede **cancelar** un Sprint si detecta que las tareas comprometidas ya no son relevantes, el objetivo cambia, la empresa realiza algún cambio de estrategia, etcétera). En lo persona, nunca tuve la experiencia de ver un Sprint cancelado.
- Negociación: Si el equipo subestimó tareas (comprometió de más), se debe renegociar el alcance tan pronto como sea posible. En este sentido, la transparencia es importante para tener un control claro de expectativas. Muchas veces la solución es lograr una versión más rudimentaria de una funcionalidad que de todas formas pueda llegar a producción.


### Sprint planning
Ocurre al comienzo del Sprint (es el primer evento). Es una reunión en la cual el equipo selecciona del Product Backlog aquellos requerimientos (Stories) que se van a estar desarrollando durante el Sprint. Al nuevo conjunto se denomina Sprint backlog.

#### Reglas
- Participantes: El Scrum team completo (le Product Owner tiene mayor protagonismo en la primera parte de la reunión).
- Duración: 2 horas por cada semana que dure el Sprint (ej: en un Sprint de 2 semanas, la Sprint planning debería durar menos de 4h).
- Se debe poner foco en las prioridades más altas.

#### Enfoque
1. Determinar el "qué": Se evalúa el Product Backlog y se selecciona qué requerimientos se van a estar trabajando. En esta parte de la reunión, le Product Owner tiene mayor protagonismo.

  **Entradas**:
  - Incremento de producto (del Sprint anterior)
  - Product backlog
  - Capacidad: Condiciones específicas de un Sprint tales como, integrantes del equipo, feriados, días de vacaciones, etcétera.
  - Performance pasada: Se lleva una métrica de la cantidad de trabajo que puede realizar el equipo en un Sprint promedio, y cómo es esa evolución. El objetivo es tener una referencia para saber cuánto trabajo tomar ([ver más](./team-capacity.md)).

  **Salidas**:
  - Sprint Backlog: Lista de requerimientos comprometidos.
  - Objetivo del Sprint: Un enunciado que describe el propósito del Sprint (en mi experiencia, no vi muchos equipos que lo desarrollen).

2. Determinar el "cómo": El equipo de desarrollo empieza a trabajar en diseños más detallados. Le Product Owner se queda en el lugar por consultas ocasionales. Durante esta etapa:
  - Se dividen los requerimientos en tareas más granulares (1 o 2 días de duración). Esto también resultará en una ventaja para la transparencia e inspección (ver [Burndown Chart](./info-grafica.md))
  - Durante esta división, suelen descubrirse nuevas tareas, o incluso re-estimarse las ya conocidas. Esto puede llevar al punto de notar (de forma afortunadamente temprana) que se sobre-comprometió trabajo. Es un excelente momento para charlarlo con le Product Owner y refinar el Sprint Backlog.

### Daily meeting
Una vez al día, se inspecciona el Sprint plan y se decide si es necesario adaptarlo. Aquí nuevamente aparecen los conceptos principales del control empírico de procesos.

#### Reglas

- Participantes: Development team y Scrum Master (Le Scrum Master debe garantizar que suceda, que sólo participe el equipo de desarrollo, y que se honré el *timebox*. Una vez que el equipo puede hacer esto por si solo, le Scrum Master podría no asistir).
- Duración: 15 minutos (de mucha concentración). Esto solo es posible si el equipo va preparado, con información de calidad (precisa, confiable, oportuna) y si no son demasiadas personas (volviendo al tema del tamaño de un equipo de desarrollo dentro de Scrum).

#### Enfoque
- La reunión se realiza todos los días, a la misma hora, en el mismo lugar. Esto ayuda a la organización y la concentración. Muchos
- Cada integrante explica 3 áreas:
  - ¿Qué hizo ayer para ayudar a alcanzar el objetivo del Sprint?
  - ¿Que va a hacer hoy para ayudar a alcanzar el objetivo del Sprint?
  - ¿Encontró algún impedimento par alcanzar el objetivo del Sprint?

  Respecto de estos temas, a muchos equipos no experimentados en Scrum, se les pide que hagan un ejercicio previo a la reunión, con el objetivo de tener estas 3 áreas cubiertas.
  La idea de los impedimentos es poder enunciarlos (incluso determinar si hay demoras). Se pide, en general, que las ideas para superar estos impedimentos sean debatidas **inmediatamente** después de la Daily Meeting entre las personas relevantes. De esta forma, se apunta a que el tema no quede en la nada, pero también a poder cumplir con los tiempos pautados para la reunión.

  **Entradas**:
  - Sprint goal
  - Sprint backlog

  **Salidas/Beneficios**:
  - Mejora en la comunicación.
  - Se pueden eliminar otras reuniones (reportes individuales, micromanagement, etcétera).
  - Identificación temprana de problemas e impedimentos (control de expectativas).
  - Rápida toma de decisiones (por el equipo).
  - Conocimiento compartido

### Sprint review
Al finalizar el Sprint, el equipo chequea cuál fue el incremento del producto y adapta planes futuros en base a ello. Muchas veces se hace referencia a esta reunión como la "Sprint Demo". Si bien es frecuente (y hasta recomendado) hacer demostraciones durante la Sprint review, esta reunión incluye otros puntos que van por fuera de dicha demostración.

#### Reglas
- Participantes: Scrum Team + otres interesades (clientes, usuaries, otras áreas de la empresa).
- Duración: 1 hora por cada semana que dure el Sprint (ej: en un Sprint de 2 semanas, la Sprint review debería durar menos de 2h)

#### Enfoque
1. Demostración del incremento de producto, preguntas y respuestas
2. Los participantes discuten oportunidades de negocio, el uso de los clientes, proyecciones, etcétera.
3. Se realizan las modificaciones necesarias al Product Backlog.

  **Entradas**
  - Incremento del producto durante el Sprint

  **Salidas**
  - Product Backlog adaptado a la nueva realidad

### Sprint retrospective
Al finalizar el sprint, y luego de haber revisado el resultado del mismo, el equipo revisa el proceso en si mismo y decide si es necesario realizar algún tipo de adaptación. El objetivo es el de inspeccionar y adaptar el sistema de trabajo.

#### Reglas
- Participantes: Scrum team.
- Duración: 3/4 de hora por cada semana que dure el Sprint (ej: en un Sprint de 2 semanas, la Sprint retrospective debería durar menos de 1.5h).

#### Enfoque
1. Se inspecciona el último sprint haciendo foco en la gente, las relaciones, el proceso y las herramientas. Es una práctica común (aunque no sea mencionada en Scrum) hacer hablar a todo el equipo en una ronda en donde comenten 1 o 2 ítems que les hayan gustado y 1 o 2 que les gustaría cambiar. Con esto recolectado, se seleccionan algunos temas (habitualmente por votación).
2. Detección de posibles mejoras
3. Armado del plan de mejora (se seleccionan las mejoras candidatas y se establecen responsabilidades y tiempos).


## Activos (artifacts)
Activos (de una traducción mejorable de *artifacts*) hace referencia a elementos tangibles sobre los cuales el equipo se encuentra trabajando. Son en si, elementos inspeccionables sobre los cuales podemos tomar acciones (adaptaciones).

### Product Backlog
Es una lista única y ordenada que contiene todos los requerimientos que se le piden al producto. El Product Backlog es responsabilidad de une únique Product Owner (ver rol), aunque es refinado colaborativamente (por el equipo). También es una lista que está en constante evolución en base al *feedback* de les usuaries, ideas de cualquier involucrade con el proyecto/producto, análisis de la competencia, entre otros factores.

El Product Backlog es un activo que brinda una gran transparencia al proceso Scrum. En cualquier momento, cualquier interesado debería poder consultarlo y entender cuáles son las siguientes funcionalidades a atacar.

Para construir un Product Backlog, se comienza tomando nota de las necesidades. En una primera instancia, el backlog podría no estar ordenado. Se recomienda, en caso de comenzar con un backlog abultado, dar una prioridad general y comenzar a refinar aquellos requerimientos que se quieren atacar más temprano. Uno de los "secretos" de Scrum es el de no realizar trabajo (no prioritario) demasiado pronto, ya que con el avance del tiempo y el cambio de contexto, el resultado de ese trabajo podría no ser válido, o incluso innecesario. Antes de comenzar un Sprint, se necesita que el tamaño del backlog refinado sea mayor (o igual) a la capacidad del equipo (lo que irá al Sprint backlog), pero no mucho más. Muchos equipos prefieren tener refinados y ordenados los casos para trabajar en los próximos 1 o 2 Sprints. En lo personal, recomiendo esta práctica por varios motivos<sup>1</sup>.

#### ¿Qué significa refinar un requerimiento?

En pocas palabras, un requerimiento refinado es un requerimiento lo suficientemente definido como para que el equipo de desarrollo pueda convertirlo en funcionalidad. Esto requiere un buen nivel de detalle (que preferimos dejar por escrito hasta cierto punto y tener disponibilidad de le Product Owner para ampliar más información, como indica uno de los valores de Agile). **En teoría**, para que un requerimiento se considere lo suficiéntemente refinado, debería poder completarse dentro de un Sprint. De no ser así, se supone que el requerimiento es divisible. **En la práctica**, suele ser muy complejo encontrar un buen balance entre requerimientos que puedan completarse en un Sprint y a la vez, la funcionalidad resultante del mismo, aporte valor (sea material de producción). La búsqueda de ese balance podría implicar un esfuerzo mayor que el que debamos dedicarle. **Sugiero que prime el criterio y la decisión del equipo respecto de este tipo de cuestiones**. Existen muchos beneficios (técnicos) de poder llevar funcionalidad a producción en cada Sprint. Un ejemplo, es evitar el *añejamiento* del código lejos de los *branches* principales. Muchos equipos, por ejemplo, deciden enviar funcionalidades inmaduras a producción en modo "invisible" para evitar este inconveniente.
El moment"o en donde un requerimiento está lo suficientemente refinado se lo denomina "Listo para Sprint Planning" (RFSP por sus siglas en inglés).

Si bien tener un backlog ordenado y refinado es responsabilidad de le Product Owner, se considera necesario un esfuerzo colectivo de varias personas del equipo de desarrollo. Teniendo en cuenta que en Scrum no hay espacio entre un Sprint y el siguiente, todo este trabajo se realiza dentro del Sprint, por lo que el esfuerzo debe ser considerado al calcular la capacidad del equipo. Se recomienda que la tarea del requerimiento no supere el 10% de la capacidad del equipo.

<sup>1</sup> En un mundo ideal, tenemos la capacidad de entender las prioridades de los casos antes de refinarlos. En la práctica, muchas veces nos damos cuenta de que algo es más importante de lo que supusimos al analizarlo más en profundidad. Más aún, existe la posibilidad de que algunos requerimientos prioritarios no estén "listos para el desarrollo". Si ese fuera el caso, y hasta que se refinen lo suficiente, podríamos decidir saltearlos. Si no tengo más requerimientos refinados, no tengo suficiente material para un Sprint.

### Sprint backlog
El Sprint backlog es una representación del "qué" y el "cómo" de un Sprint.
Durante la Sprint planning (evento) el Equipo de desarrollo y le Product Owner definen qué se va a hacer durante el Sprint. Más aún, el Equipo de desarrollo también define cómo se va a hacer y que esfuerzo requiere cada actividad.

El Sprint backlog puede cambiar durante un Sprint. Pero hay que considerar las siguientes restricciones:
- El equipo de desarrollo (y solo este equipo) actualiza el Sprint backlog regularmente.
- Se permite actualizar las estimaciones iniciales.
- Se permite agregar o remover nuevas subtareas.
- **No** se permite agregar nuevos ítems al backlog, con excepción de que el equipo haya sobreestimado y al final del Sprnit no tengan tareas para continuar. En ese caso, se debería tomar el siguiente ítem del Product Backlog que se encuentre en estado "listo para Sprint planning" (un motivo adicional para tener algunos requerimientos refinados por adelantado).

El Sprint backlog provee una gran transparencia del día a día del Sprint, exponiendo una descomposición bastante granular de los esfuerzos que debería realizar el equipo para alcanzar el objetivo del Sprint.

Una buena práctica es dar seguimiento de estas actividades mediante un Scrum Baord y algunas gráficas llamadas *burndown charts*. [Ver más](info-grafica.md)

### Product increment

El *Product increment* es una nueva versión **usable** del producto. Si bien no es obligatorio que se lleve cada versión a producción, en teoría, el incremento de producto debería ser candidato a ir a producción. Muchos equipos no tienen automatizados los procesos de *deploy* por lo que realizar esta actividad demanda un esfuerzo y un riesgo tales que se decide acumular varias funcionalidades antes de ir a producción. Las empresas que invirtieron en prácticas [CI/CD](https://en.wikipedia.org/wiki/CI/CD) suelen contar con el concepto de "tren de release" que significa que a intervalos regulares, se hará un despliegue. Toda funcionalidad que se encuentre en el estado correspondiente (correctamente *testeada* y *mergeada* al *branch* correspondiente), será llevada a producción en el siguiente tren. Si todo marcha bien, nuestros Sprints estarían aliendos con las partidas de estos trenes.

#### Definition of done
El equipo en conjunto tiene una visión compartida de lo que se espera de un incremento. Es importante (al momento de relizar la Sprint review) verificar si lo que se está entregando, satisface esta definición. Tener esta definición clara, también aporta transparencia e incentiva la toma de ciertas decisiones que tienen que ver con la adaptabilidad. Por ejemplo, se podría llegar a la conclusión de que algo no está lo suficientemente "listo" y priorizar refinar la funcionalidad por encima de comenzar con nuevos requerimientos.

La suma de todos los incrementos de Sprint pasadas más el actual, es el estado vivo del producto. Este es un concepto no menor, y se encuentra relacionado con uno de los 12 principios de [Agile](./agile.md): El software funcionando es la medida principal de
progreso.
