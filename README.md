# Proyecto Final: La Deserción Escolar en la Educación Media Superior
### CRISTIAN EDUARDO MONTESINO FERNANDEZ, NEREYDA MOTA DOMÍNGUEZ Y YAHYR MORALES GARRIDO.
## Fases del Proyecto
1. Introducción [haz click para ir](Introducción.md)
2. Planteamieto del problema [haz click para ir](Planteamiento del problema.md)
3. Conjunto de datos [haz click para ir]()
4. 

## Objetivo
Hacer un análisis y determinar los principales riesgos de deserción escolar en algunas escuelas de Xalapa.
## Conjunto de datos
Los conjuntos de datos de este proyecto contienen información detallada sobre la tasa de abandono escolar por entidad federativa y respuestas de las preguntas que se realizaron en una encuesta en algunas escuelas preparatorias de Xalapa. A continuación, se describe cada uno de los elementos clave de cada uno de los conjuntos de datos:
### Columnas principales del primer conjunto
1. Entidad Federativa: Nombre de cada estado de la república mexicana.
2. Nivel educativo: Incluye preescolar, primaria, secundaria, educación media superior y superior.
3. 2000/2001: ciclo escolar seleccionado para realizar la tasa.
4. 2005/2006: ciclo escolar seleccionado para realizar la tasa.
6. 2010/2011: ciclo escolar seleccionado para realizar la tasa.
7. 2015/2016: ciclo escolar seleccionado para realizar la tasa.
8. 2020/2021: ciclo escolar seleccionado para realizar la tasa.
9. 2021/2022: ciclo escolar seleccionado para realizar la tasa.
10. 2022/2023: ciclo escolar seleccionado para realizar la tasa.
### Columnas principales del segundo conjunto
1. ¿Hay situaciones familiares, económicas que dificultan tu permanencia en la preparatoria?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
2. ¿Crees que te haga falta apoyo psicológico o emocional para continuar y terminar tus estudios?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
3. ¿ Consideras que tienes acceso a los recursos y herramientas necesarias para estudiar?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
4. ¿Sientes que lo que aprendes en la preparatoria es relevante para tus metas personales?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
5. ¿Crees que la carga académica o el ritmo de estudios es demasiado intenso y puede desmotivarte a seguir estudiando?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
6. ¿Sientes que tienes tiempo suficiente para equilibrar tus estudios con otras responsabilidades?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
7. ¿Cuáles serían los cambios que te ayudarían a sentirte mas motivad@ para continuar en la escuela?: Pregunta con el objetivo de tener una respuesta afirmativa o negativa.
### Variables contextuales
1. Socieconomico
2. Rendimiento escolar
3. Psicológico
### Cantidad de registros
1. En el conjunto de datos sobre la tasa de abandono escolar se tuvieron 142 registros de los 32 estados de la república.
2. En el conjunto de datos de la encuesta, se recabaron 215 respuestas de estudiantes de las escuelas preparatorias.
### Propósitos del conjunto de datos
Para el primer conjunto, es comprobar y analizar que el abandoo escolar se encuentra principalmente en la eduacación media superior, mientras que, en el segundo es determinar en que variables o preguntas es más alto el porcentaje de una respuesta negativa o positiva para determinar directamente los factores que más afectan a los estudiantes abandonar este nivel de estudio.
### Proceso incial
Se hizo primero una limpieza de datos con python, para eliminar valores nulos, además de rellenar algunos espacios de acuerdo al promedio, y en algunas variables catégoricas, volverlas número para simplificar.
## Modelamiento de Datos
Seleccionamos dentro de las tres variables principales: Socioeconómico, Rendimiento escolar y Psicológico o Salud Mental; las preguntas más relevantes y creamos los gráficos correspondientes, ya que, es una forma sencilla para que los resultados puedan comprenderse fácilmente.
## Resultados
De acuerdo al análisis, se determinó que efectivamente el abnadono escolar se encuentra principalmente en la educación media superior, además de que las respuestas indican que en las escuelas preparatorias de Xalapa la deserción escolar se debe principalmente al equilibrio de estudiar con otras responsabilidades y la carga académica o el ritmo de estudios que llevan los alumnos, incluso relacionandose a factores de salud mental.
## Conclusiones
### Resumen del Análisis
El análisis realizado confirma que la deserción escolar en la educación media superior es un problema crítico, especialmente en las escuelas preparatorias de Xalapa. Los resultados destacan que las principales causas identificadas están relacionadas con:
Dificultad para equilibrar estudios con otras responsabilidades.
Carga académica intensa y ritmo de estudios desmotivador.
Necesidad de apoyo psicológico o emocional para manejar los desafíos académicos y personales.
Estos factores también reflejan una interacción con el contexto socioeconómico de los estudiantes, lo que refuerza la hipótesis inicial de que los problemas financieros y el acceso limitado a recursos educativos son determinantes clave.
### Aplicaciones Prácticas
Intervenciones Educativas Personalizadas: Los resultados pueden ser utilizados para diseñar programas que ayuden a los estudiantes a equilibrar responsabilidades, como tutorías académicas o programas flexibles de estudio.
Apoyo Psicológico y Emocional: Crear espacios de atención psicológica en las escuelas para atender problemas emocionales que afectan la continuidad de los estudios.
Políticas Educativas Informadas: Los datos obtenidos pueden servir para guiar a las instituciones educativas y al gobierno en la implementación de políticas que reduzcan la carga académica y mejoren la infraestructura escolar.
### Limitaciones Encontradas
Tamaño y Representatividad de la Muestra: Aunque el análisis se centró en 215 estudiantes de algunas escuelas en Xalapa, los resultados no necesariamente reflejan la situación en todo el país.
Disponibilidad de Datos Históricos: La información sobre la tasa de deserción escolar no siempre está actualizada ni incluye detalles sobre factores individuales como salud mental o dinámicas familiares.
### Propuestas para Proyectos Futuros
1. Análisis Regional Ampliado: Recopilar datos de otras regiones del país para comparar patrones de deserción escolar en contextos urbanos y rurales.
2. Integración de Nuevas Variables: Explorar factores como el rol de la calidad docente, infraestructura escolar y programas extracurriculares.
4. Evaluación de Intervenciones: Diseñar y evaluar programas piloto de apoyo psicológico y académico para medir su impacto en la reducción de la deserción escolar.
5. Estudios Cualitativos: Complementar el análisis cuantitativo con entrevistas o grupos focales para profundizar en las experiencias de los estudiantes.
