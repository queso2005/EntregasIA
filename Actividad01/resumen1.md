# RESUMEN 1 DE NOTEBOOKLM
## Documento 1: Ingeniería de Conocimiento
(Basado en 0-Ingenieria-del-conocimiento.pdf)
* Definición y Fundamentos del Conocimiento
La Ingeniería de Conocimiento (IC) se define como una rama de la Inteligencia Artificial (IA) dedicada a la adquisición, representación y procesamiento del conocimiento para construir sistemas de software donde el razonamiento es el eje central, conocidos como Sistemas Expertos (SE). En este ámbito, el conocimiento no se limita a datos, sino que es una amalgama de estructuras de datos y procedimientos interpretativos que modelan el mundo real para conferir un comportamiento inteligente. Este se clasifica en tres tipos: declarativo (hechos o atributos de objetos), procedural (reglas usadas por expertos para solucionar problemas) y metaconocimiento (conocimiento sobre las capacidades de razonamiento del propio sistema).
Roles en el Desarrollo
El proceso involucra tres figuras esenciales:
1.	Ingeniero de Conocimiento (ICO): Especialista informático encargado de extraer, organizar e implementar el conocimiento en una base de datos. Debe poseer habilidades de comunicación y nociones de psicología para interpretar adecuadamente al experto humano.
2.	Experto Humano: Persona de prestigio que aporta su experiencia y saber para que sea automatizado.
3.	Usuario: El destinatario final, cuyo nivel de conocimiento debe ser considerado desde el inicio del diseño.
Procesos y Etapas de Desarrollo
La IC está constituida por tres procesos macro: Adquisición del conocimiento (extracción de fuentes), Representación del conocimiento (codificación de reglas) y la Base de conocimiento (almacenamiento final, usualmente mediante reglas de producción). El ciclo de vida de la adquisición se divide en cinco etapas críticas:
•	Identificación: Reconocimiento del problema, subproblemas y recursos.
•	Entendimiento: Determinación de conceptos clave y relaciones para elegir el medio de representación más apto.
•	Formalización: Organización del conocimiento en estructuras lógicas, fase de gran dificultad por la interacción con el experto.
•	Implementación: Programación del conocimiento en la computadora y creación de un prototipo.
•	Pruebas: Validación de la base de conocimiento mediante ejemplos y revisión de reglas para asegurar su exactitud.
Esquemas de Representación (KR)
Para que el conocimiento sea inteligible, se utilizan diversos esquemas:
•	Reglas de Lógica Simbólica: Incluye la lógica proposicional (booleana) y la de predicados, esta última capaz de valorar enunciados lógicos complejos mediante variables, funciones y cuantificadores.
•	Redes Semánticas: Grafos de nodos (elementos) y enlaces (relaciones como "ES-UN" o "ES-SUBCONJUNTO").
•	Frames (Marcos): Estructuras de datos para objetos divididos en slots (ranuras) y facets (atributos), organizados jerárquicamente con mecanismos de herencia.
•	Árboles de Decisión: Representaciones de espacios de búsqueda donde los nodos son metas y las ramas decisiones o resultados.
Técnicas de Extracción del Conocimiento
Se clasifican según su nivel de automatización:
•	Métodos Manuales: Destacan las entrevistas (estructuradas, semiestructuradas o no estructuradas), el análisis de protocolos para rastrear "la trayectoria de los pensamientos" del experto, y el análisis de casos específicos.
•	Métodos Semiautomatizados: Herramientas que apoyan al ICO o al experto, como el Análisis de Rejilla basado en la Teoría de Construcción Personal de Kelly.
•	Métodos Automatizados: Buscan minimizar la intervención humana mediante reglas de inducción (como el algoritmo ID3 para generar árboles de decisión) o programas heurísticos de aprendizaje automatizado.

