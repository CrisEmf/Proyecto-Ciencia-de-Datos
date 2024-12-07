# Conjunto de datos
Los conjuntos de datos de este proyecto contienen información detallada sobre la tasa de abandono escolar por entidad federativa y respuestas de las preguntas que se realizaron en una encuesta en algunas escuelas preparatorias de Xalapa. A continuación, se describe cada uno de los elementos clave de cada uno de los conjuntos de datos:
## Columnas principales del primer conjunto
1. Entidad Federativa: Nombre de cada estado de la república mexicana.
2. Nivel educativo: Incluye preescolar, primaria, secundaria, educación media superior y superior.
3. 2000/2001: ciclo escolar seleccionado para realizar la tasa.
4. 2005/2006: ciclo escolar seleccionado para realizar la tasa.
6. 2010/2011: ciclo escolar seleccionado para realizar la tasa.
7. 2015/2016: ciclo escolar seleccionado para realizar la tasa.
8. 2020/2021: ciclo escolar seleccionado para realizar la tasa.
9. 2021/2022: ciclo escolar seleccionado para realizar la tasa.
10. 2022/2023: ciclo escolar seleccionado para realizar la tasa.
## Columnas principales del segundo conjunto
1. ¿Hay situaciones familiares, económicas que dificultan tu permanencia en la preparatoria?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
2. ¿Crees que te haga falta apoyo psicológico o emocional para continuar y terminar tus estudios?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
3. ¿ Consideras que tienes acceso a los recursos y herramientas necesarias para estudiar?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
4. ¿Sientes que lo que aprendes en la preparatoria es relevante para tus metas personales?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
5. ¿Crees que la carga académica o el ritmo de estudios es demasiado intenso y puede desmotivarte a seguir estudiando?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
6. ¿Sientes que tienes tiempo suficiente para equilibrar tus estudios con otras responsabilidades?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
7. ¿Cuáles serían los cambios que te ayudarían a sentirte mas motivad@ para continuar en la escuela?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
## Variables contextuales
1. Socieconomico
2. Rendimiento escolar
3. Psicológico
## Cantidad de registros
1. En el conjunto de datos sobre la tasa de abandono escolar se tuvieron 142 registros de los 32 estados de la república.
2. En el conjunto de datos de la encuesta, se recabaron 215 respuestas de estudiantes de las escuelas preparatorias.
## Propósitos del conjunto de datos
Para el primer conjunto, es comprobar y analizar que el abandoo escolar se encuentra principalmente en la eduacación media superior, mientras que, en el segundo es determinar en que variables o preguntas es más alto el porcentaje de una respuesta negativa o positiva para determinar directamente los factores que más afectan a los estudiantes abandonar este nivel de estudio.
## Proceso incial
Se hizo primero una limpieza de datos con python, para eliminar valores nulos, además de rellenar algunos espacios de acuerdo al promedio, y en algunas variables catégoricas, volverlas número para simplificar.

Conjunto de datos utilizado [haz click aquí](dataset/Educacion_11.csv)

Segundo Conjunto de datos utilizado [haz click aquí](dataset/DESERCIÓNESCOLARENEMS(Respuestas)-Respuestasdeformulario1.csv)

