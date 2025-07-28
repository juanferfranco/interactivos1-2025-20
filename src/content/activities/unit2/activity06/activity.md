#### Autoevaluación

**Mirando hacia adentro: autoevaluación de máquinas de estados y concurrencia**

El objetivo aquí es doble. Primero, que recuperes de tu memoria los conceptos de diseño y programación con máquinas de estados sin ayuda externa. Este esfuerzo por recordar (práctica de recuperación) es clave para un aprendizaje duradero. Segundo, que reflexiones sobre tu proceso de diseño y depuración, una habilidad esencial para cualquier ingeniero.

:::caution[📤 Bitácora]

En tu bitácora, sin consultar tu código, diagramas o notas, responde a las siguientes preguntas con tus propias palabras. Concéntrate en el esfuerzo de recordar, no en la perfección de la respuesta.

**Parte 1: recuperación de conocimiento (Retrieval Practice)**

1.  Describe con tus palabras qué es una máquina de estados. ¿Cuáles son sus cuatro componentes fundamentales que has utilizado en esta unidad?
2.  Explica por qué la técnica de máquina de estados es tan útil para gestionar la "concurrencia" (atender un temporizador y botones "al mismo tiempo") en un dispositivo con un solo hilo de ejecución como el micro:bit. ¿Qué problema soluciona en comparación con usar funciones como `sleep()`?
3.  Imagina que tienes que añadir una nueva funcionalidad a la bomba temporizada: si se agita (`shake`) el micro:bit *mientras* la cuenta regresiva está activa, el tiempo se reduce a la mitad. ¿Cómo modificarías tu diagrama de máquina de estados para incluir este nuevo evento y acción?
4.  Explica qué es un "vector de prueba" y por qué es una herramienta crucial para verificar que una máquina de estados funciona como se espera.

**Parte 2: reflexión sobre tu proceso (Metacognición)**

1.  ¿Qué parte del diseño de la bomba temporizada te resultó más desafiante: crear el diagrama de estados (Actividad 04) o traducir ese diagrama a código MicroPython (Actividad 05)? ¿Por qué?
2.  Describe un error o "bug" que encontraste al implementar tu programa. ¿Cómo te ayudó pensar en términos de estados, eventos y transiciones a identificar y solucionar el problema?
3.  El problema de la bomba era complejo. ¿Qué estrategia usaste para abordarlo? ¿Comenzaste con una versión simple y añadiste funcionalidades poco a poco?
4.  Ahora que entiendes el patrón de máquina de estados, ¿En qué otro tipo de proyecto o sistema de entretenimiento digital crees que podrías aplicarlo?
:::
