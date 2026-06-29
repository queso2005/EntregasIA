# RESUMEN 2 DE NOTEBOOKLM
## Documento 2: Sistemas Expertos Basados en Reglas
(Basado en 1-sistemasExpertosBasadosEnReglas.pdf)
* Introducción y Arquitectura de los SBR
Los Sistemas Basados en Reglas (SBR) son herramientas eficientes para resolver situaciones complejas regidas por reglas deterministas, como el control de tráfico o transacciones bancarias. Su arquitectura se divide en dos elementos primordiales: los Hechos, que son datos dinámicos y temporales conocidos en una situación particular (almacenados en la memoria de trabajo), y las Reglas, que representan relaciones generales y estáticas de naturaleza permanente (almacenadas en la base de conocimiento).
La Regla: Componentes y Estructura
Una regla es una afirmación lógica compuesta por una premisa o antecedente (si...) y una conclusión o consecuente (entonces...). Las premisas pueden contener múltiples afirmaciones conectadas por operadores lógicos como "Y", "O" y "NO". Debido a que las reglas complejas son difíciles de tratar computacionalmente, se utiliza la sustitución de reglas, reemplazando una regla compuesta por un conjunto de reglas equivalentes más sencillas.
El Motor de Inferencia y sus Pasos
Es el "cerebro" del sistema que gestiona la base de hechos aplicando el conocimiento de las reglas para derivar conclusiones. Sus pasos básicos son:
1.	Reconocimiento de patrones: Comparar los hechos de la memoria de trabajo con las reglas.
2.	Resolución de conflictos: Elegir qué regla aplicar de entre las satisfechas.
3.	Ejecución: Aplicar la regla y actualizar la memoria de trabajo con nuevos hechos.
Para obtener conclusiones, el motor emplea reglas de inferencia fundamentales:
•	Modus Ponens: Inferencia hacia adelante; si el antecedente es cierto, la conclusión se asume cierta.
•	Modus Tollens: Inferencia hacia atrás; si la conclusión es falsa, se deduce que el antecedente es falso. Estas reglas son complementarias y aumentan el conocimiento total del sistema.
•	Mecanismo de Resolución: Permite obtener conclusiones compuestas combinando y simplificando expresiones lógicas equivalentes de varias reglas.
Estrategias de Razonamiento
Existen enfoques distintos según la dirección de la búsqueda:
•	Encadenamiento hacia adelante: Parte de los hechos conocidos y aplica reglas sucesivamente para derivar nuevos hechos hasta que no se pueda concluir más información.
•	Encadenamiento hacia atrás (orientado a objetivos): El algoritmo parte de un nodo objetivo seleccionado por el usuario y navega por las reglas buscando los hechos necesarios para validarlo, preguntando al usuario si la información falta.
•	Compilación de reglas: Permite escribir los objetivos como "ecuaciones objetivo" en función de los datos de entrada para obtener deducciones inmediatas.
Control de Coherencia y Aplicaciones
Es vital asegurar que el conocimiento no sea inconsistente. Un conjunto de reglas es coherente si existe al menos una combinación de valores que no produzca contradicciones. El sistema debe identificar valores no factibles (que siempre llevan a inconsistencias) para guiar al usuario hacia opciones válidas.
El documento ilustra estos conceptos con un sistema de control de tráfico ferroviario, donde reglas de interbloqueo evitan colisiones basándose en el estado de las vías (libre/ocupada) y señales (verde/rojo). Finalmente, se destaca que, aunque los SBR son deterministas, pueden extenderse con lógica probabilística para manejar la incertidumbre, común en campos como el diagnóstico médico. El Subsistema de Explicación complementa el sistema justificando ante el usuario cómo se llegó a cada conclusión mediante la lista de hechos y reglas activadas.

