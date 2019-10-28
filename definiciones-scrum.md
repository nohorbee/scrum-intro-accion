# Scrum

## Definición

> Un **framework** con el cual la gente puede resolver problemas **adaptativos complejos** al tiempo que entregan productos con el **mayor valor** posible

(extraido y traducido de [Scrum Alliance](https://www.scrumalliance.org/about-scrum/definition)).

De esta definición (que parece no decir nada) es importante los términos que se detallan a continuación:

### Framework

Mucha gente hace referencia a Scrum como una metodología o un proceso. La definición utiliza la palabra *framework* con una intención: dar a conocer que es un marco de trabajo y que, como tal, no hace nada por sí solo. Hay que completarlo. El marco de trabajo define unas pocas reglas (se dice que es poco prescriptivo) lo que lo hace muy fácil de entender.

#### ¿Completarlo con qué?

Las reglas que se definen en Scrum tienen que ver con sus componentes (equipo, eventos y activos<sup>1</sup>) y las interacciones entre ellos ([ver más](./componentes-e-interacciones.md)). Pero, a priori, Scrum no determina ninguna herramienta, práctica, metodología o proceso a aplicar. Algunos ejemplos:
- Scrum determina que los equipos tienen una velocidad y que *lo que entra en una Sprint* debe adecuarse a esa velocidad. Pero no especifica cómo realizar las estimaciones de cada *story* (si bien hay prácticas recomendadas, no son parte del framework).
- Scrum determina que se debe realizar una reunión de retrospección al final de una *Sprint*. Pero no determina la dinámica de la misma (salvo por la duración máxima).

------

1: Activos viene de la palabra *artifact*. Es muy compleja de traducir y creo que "activos" no le hace justicia, pero es la que más parece acercarse. Si estás leyendo esto y se te ocurre una mejor, se acepta la sujerencia [aquí](https://github.com/nohorbee/scrum-intro-accion/issues/new)

### Problemas adaptativos complejos e impredecibles

Se hace referencia a este tipo de problemas cuando el contexto se vuelve tan cambiante que es difícil prever un plan de ejecución que satisfaga el éxito del proyecto.

En modelos más antiguos, como [*waterfall*](https://es.wikipedia.org/wiki/Desarrollo_en_cascada), se dedicaba un tiempo considerable a analizar requerimientos, diseñar soluciones, para luego implementarlas y presentarlas al cliente. Cada etapa podía durar meses (incluso años) y mientras tanto el cliente no recibía **valor**. Más aún, el cliente no podía validar la solución hasta que estuviera completa, lo que generaba sorpresas al final de los proyectos que muchas veces terminaban no implementándose (y con renegociaciones de contratos y otras dificultades). El problema principal era la poca visibilidad y participación por parte del cliente, y la falta de atención al cambio de contexto inicial. Es como si se sacara una foto de un problema, se tardara meses en análizarla y sin volver a mirar el problema se comenzara a desarrollar la solución. En el tiempo de análisis, el problema probablemente haya mutado o incluso desaparecido.

Scrum entiende que los problemas con los que debemos lidiar se desarrollan en contextos cambiantes y propone que, en lugar de poner foco en procesos de control de cambios, que apuntan a restringirlos, se entienda al cambio como motor del framework en si. De aquí que se proponen iteraciones cortas (Sprints), validación frecuente (Sprint Reviews) y re-priorización constante (Backlog).

---
Se hace referencia a Waterfall como un modelo dentro del paradigma de **Control definido de proceso**. Un paradigma apropiado para problemas **simples, predecibles y estáticos.**
En contraposición, Scrum se ubica en el paradigma de **Control empírico de proceso**. Un paradigma más apropiado para (los antes mencionados) problemas **adaptativos, complejos e impredecibles.**

---

#### Acerca del control empírico de proceso

Es un paradigma que se basa en los siguientes pilares: Transparencia, Inspección y Adaptación. Estos pilares permiten analizar la realidad y reaccionar a ella (de ahí lo de empírico). Scrum los aplica de la siguiente manera:
- Transparencia: Todos los componetnes de Scrum son visibles por los roles intevinientes (atención: esto puede incluir al cliente).
- Inspección: El equipio revisa constantemente los activos (backlog y producto) para determinar si hay variaciones respecto de los supuestos (ej: creíamos que una funcionalidad era prioritaria, pero tras charlar con el cliente, nos enteramos de que no).
- Adaptación: Si lo que se está haciendo no aporta el **mayor valor posible**, hay que dejar de hacerlo y cambiar el plan. Para el ejemplo anterior, lo más apropiado sería cambiar las prioridades del backlog.

### Mayor valor posible

Esta es probablemente la parte más importante detrás del framework. Lo que persigue esta (y otras herramientas del ecosistema [agile](./agile.md)) es maximizar el valor que se entrega al cliente. Si en algún momento nos encontramos trabajando en algo que no está alineado con esta definición, es un signo inmediato de que hay que detenernos y buscar otra alternativa.

Scrum está organizado en iteraciones cortas que transforman una porción de un backlog (lista de requerimientos) en incrementos del producto (funcionalidades). Se maneja un concepto muy importante al que se hace referencia con las siglas *MVP* que significan **Mínimo producto factible/viable** (del inglés Minimum Viable Product). Un MVP es aquel grupo de funcionalidades (y ninguna otra) que le aportan valor al cliente. Un MVP debería ser puesto en producción tan pronto como sea alcanzado. Toda iteración futura, irá mejorando ese punto inicial (y los incrementos de todas las anteriores). Si todas las iteraciones apuntan a hacer lo que es más prioritario para el cliente (mayor ROI, mayor prioridad, etc), el framework estará garantizando que siempre se entrega el mayor valor posible (aunque el foco del proyecto sea cambiante).

## Corolario

Se dice que Scrum es muy fácil de entender (por lo poco prescriptivo) pero muy difícil de dominar (por la cantidad de herramientas que hay que implementar).
Si bien es una frase bastante potente, tras haber utilizado Scrum con muchos equipos, mi sensación no es de dificultad sino de desafío. Y la forma de ir superándolo está más relacionada con la experiencia que con la capacidad o inteligencia.

Personalmente me gusta pensar a Scrum como una herramienta que no soluciona ningún problema, pero los expone todos para que podamos tomar las decisiones correspondientes (muchas de ellas, referidas a las herramientas y procesos a implmentar).
