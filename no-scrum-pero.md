# Cosas que no son Scrum
#### pero que son frecuentemente asociadas al mismo

Hay algunos conceptos que son tan resonantes en la práctica de Scrum que mucha gente los considera parte. En rigor, no lo son, pero este repositorio no es tan riguroso.

## Información gráfica

Entre todos los reportes y herramientas gráficas que pueden ayudarnos a entender el estado de nuestro proyecto y, sobretodo, brindar transparencia e *inspeccionabilidad* al asunto, hay 2 particularmente utilizadas:
- Scrumboard (tablero Scrum): Nos da una instantánea de cómo se ve nuestro Sprint respecto del estado de cada una de las tareas y subtareas.
- Burndown chart: Nos permite ver la evolución de nuestro Sprint en términos de cómo se fueron desarrollando las tareas. Este gráfico además, nos permite predecir posibles desvíos del plan del sprint.

[Ver más](./info-grafica.md)


## Planning poker

Es una técnica de estimación basada en la búsqueda de concenso. Por el uso de cartas (no obligatorio) se considera que esta técnica está *gamificada*. La dinámica indica que, una vez discutida una tarea, todes les miembres del equipo de desarrollo eligen un puntaje (representado por una carta) y la develan a los demás en forma simultánea para evitar sesgos. Cuando no haya coincidencia, los integrantes del equipo (comenzando por los extremos) deben debatir el motivo por el cual seleccionaron un puntaje. Esto *fuerza* el intercambio y las aclaraciones pertinentes garantizando que todes hayan escuchado un punto de vista diferente.

Los números seleccionados no están necesariamente asociados a una unidad temporal. De hecho, se recomienda que representen una medida de complejidad en lugar de esfuerzo. Al seguir esta recomendación, es difícil encontrar un punto absoluto de diferencia: 1 día es un patrón universal, pero 1 punto puede tener tantos significados como personas. El éxito de la técnica depende de que todes les miembres del equipo de desarrollo logren un criterio común. Para eso, suelen hacerse ejecicios de estimación sobre algunos requerimientos que serán considerados "patrones". Cuando haya dudas, el debate puede llevarse hacia el lado de "¿qué tan complejo te parece este requerimiento comparado con este otro?"

La mayoría de los mazos evitan secuencias de números consecutivos y optan por progresiones incrementales como Fibonacci, potencias de 2, entre otras. El objetivo es lograr una granularidad tal que auente la probabilidad de coincidencia cuando la haya. Por ejemplo: si utilizo Fibonacci (removiendo los números idénticos y el 0): [1, 2, 3, 5, 8, 13, 21,...], una tarea simple podría llevar a discusiones que no aportan valor (¿es un 1 o un 2?). Pero las demás, empiezan a tener una separación que, en caso de no haber coincidencia, indicarían que hay motivos reales para que no la haya.


## Herramientas

Existe un gran número de herramientas para gestionar proyectos Scrum, o incluso para llevar adelante algunas de sus prácticas. Comenzaré con una lista breve que, en caso de curarse colectivamente, deberá llevar su propia sección. Se aceptan issues y pull requests.

- [Jira](https://www.atlassian.com/software/jira): Probablemente la herramienta de gestión de proyectos ágiles más utilizada (al menos, eso dice Atlassian, la empresa responsable). Si bien en un primer momento Jira no había sido específicamente para proyectos Agile, sus sucesivas versiones fueron inclinándose cada vez más hacia este lugar dando tratamiento preferencial a las features útiles para tal fin. Jira nos da la posibilidad de gestionar el Backlog de Producto y de Sprint. Sobre este último, también nos brinda un Scrum board virtual, y diferentes reportes (burndown incluido). Jira es extensible mediante plug-ins, por lo que, si el equipo decidiera utilizar alguna herramienta que no está incluida en el mismo, es muy probable que exista un plug-in que se adapte a la necesidad.

- [Trello](https://trello.com): Trello nació como una herramienta para el manejo de listas de tareas (poder tener nuestros "TODO lists" en la nube, pudiendo compartirlas con otras personas). Incrementalmente (como Agile dicta) fueron agregando funcionalidades que permiten el uso de estas listas para la gestión de los backlog y la inspección de los mismos. Si bien no es tan potente como Jira (es más de propósito general), muchos equipos eligen utilizarlo y aplican sus propias convenciones y extensiones. Un dato intereante es que hace unos años fue adquirido por Atlassian (sí, los mismos que hacen Jira) y las comunicaciones por aquel momento indicaban que habría un intento de fusionar ambas herramientas o de dar prioridad a Trello hasta deprecar Jira. ATOW, ambas son independientes y en crecimiento.

- [Scrumpoker online](https://scrumpoker.online/): No todos los equipos tienen mazos físicos. No todos los equipos se encuentran en una misma sala al momento de estimar. Tiene sentido que el mazo evolucione a aplicaciones que permitan la misma funcionalidad. Scrumpoker online es gratuita, permite armar salas de estimación, seleccionar el tipo de mazo (la progresión), y por supuesto, solo revela los votos una vez que todos lo hayan hecho.

- [DailyBot](https://www.dailybot.co/): Algunos equipos decidieron cambiar una de las reglas principales de las daily meetings (misma hora, mismo lugar). Entre los varios motivos, suele primar el rechazo a las reuniones (que comparto parcialmente). Un problema que se plantea es que al momento de la daily meeting, cualquier miembre del equipo puede estar ocupade haciendo algo más, o simplemente en una ráfaga de concentración que no es recomendable abandonar. Poder hacer daily meetings asincrónicas suena tentador pero necesita algunas reglas para que no pierdan fuerza. Una de ellas es la de poder centralizar la información y asegurarse que todes la reciban en tiempo y forma. Esto es lo que intenta DailyBot que, en principio, se integra con Slack y Hangouts. **Recomendación**: Estas prácticas son complicadas y no deberían pensarse en equipos que estén comenzando a trabajar juntos (o que estén comenzando con Scrum). También requiere que le Scrum Master pueda completar los vacíos generados por el cambio de esta regla.


## User Stories
Una user story es, sobre-simplificando, una manera (informal) de escribir los requerimientos. Si bien no es obligatoria, es bastante popular y cubre muchos aspectos de lo que defiende Agile y lo que implementa Scrum.

Una user story tiene el siguiente formato:

```
Como <role>, yo quiero/puedo <capacidad>, para <motivo>
```

muchas veces mencionado también

```
Como <role>, quiero <qué>, para <por qué>
```

Estos templates incentivan a quién las escribe (le Product Owner) a enfocarse primero en le usuarie (que finalmente es quién determina el valor de una funcionalidad), luego en el requerimiento en sí, y finalmente (y estoy es muy importante y suele ser dejado de lado) la motivación.

Las User stories pueden (deben?) ser refinadas en cuanto a su descripción, agregando notas, adjuntos y sobretodo, un criterio de aceptación.

### Criterio de aceptación
El criterio de aceptación son notas que describen lo que debe estar incluido en una funcionalidad para darla por completa.

### Epics
Un atributo deseable de las User Stories es su independencia. Esto tiene mucha relación con Scrum ya que se considera cada User Story como una pieza completable dentro de un Sprint y como tal, aportando valor por si misma (candidata a producción). Si esto es así, una historia no debería depender de ninguna otra. Pero, como sabemos, este es un atributo costoso. En caso de querer respetarlo, perdemos la capacidad de gestionar iniciativas que puedan demorar más que lo que lleva una Sprint. Una Epic es un proyecto de esas características que se descompone en varias user stories. Se sigue pidiendo independencia para las stories, pero se entiende que son parte de un proyecto mayor.
