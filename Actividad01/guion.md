# GUION DE VIDEO
# Sistemas Expertos
* Conocimiento · Base de conocimiento · Motor de inferencia · Línea de tiempo · Tipos de sistemas expertos
* Duración estimada: 10 a 15 min 
## ESCENA 1.  Introducción y presentación personal  
Cuerpo entero, vestimenta formal. Fondo neutro y buena iluminación frontal.
Buenos días/tardes. Mi nombre es [Nombre del estudiante] y en este video voy a presentar el tema de Sistemas Expertos, dentro de la materia de Ingeniería del Conocimiento. A lo largo de la presentación voy a explicar qué es el conocimiento, qué es una base de conocimiento, qué es un motor de inferencia, cuáles son las principales inferencias lógicas, qué es una regla, qué es un hecho, y finalmente, qué es un sistema experto. También revisaremos brevemente la línea de tiempo de los sistemas expertos y sus principales tipos. Comencemos.
## ESCENA 2.  ¿Qué es el conocimiento?   (0:45 – 1:40)
Cambiar a pantalla compartida. Mostrar diapositiva 3 (Concepto fundamental).
Para entender qué es un sistema experto, primero necesitamos entender qué es el conocimiento. Desde el punto de vista de la inteligencia artificial, el conocimiento es la combinación de esquemas o estructuras de datos y procedimientos interpretativos que dan lugar a un comportamiento inteligente. Está formado por hechos, conceptos, procedimientos, ideas, reglas y asociaciones que nos permiten modelar el mundo real.
Existen tres tipos de conocimiento. El conocimiento declarativo, que son los hechos o atributos de un objeto, persona o concepto, y sus relaciones. El conocimiento procedural, que es el conjunto de reglas que un experto utiliza para resolver problemas. Y el metaconocimiento, que es el conocimiento sobre el propio conocimiento, es decir, sobre las capacidades de razonamiento del sistema.
## ESCENA 3.  Base de conocimiento: hechos y reglas  
Mostrar diapositiva 5 (Base de conocimiento), luego diapositiva 6 (Hecho) y diapositiva 7 (Regla).
Una base de conocimiento es el componente del sistema experto donde se almacena el conocimiento del dominio: los hechos y las reglas que un experto humano utiliza para resolver un problema concreto. Dentro de la base de conocimiento, las reglas de producción son el método más usado para representar el conocimiento, y cada elemento se comprende por sí mismo, sin necesidad de conocer el contexto completo.
Ahora bien, ¿qué es un hecho? Un hecho es la información conocida en una situación particular. Es dinámico, puede cambiar de una aplicación a otra, su naturaleza no es permanente, y se almacena en la memoria de trabajo del sistema. Por ejemplo, en un cajero automático, hechos serían: NIP igual a incorrecto, o tarjeta igual a verificada.
Y ¿qué es una regla? Una regla es una afirmación lógica que relaciona dos o más objetos. Tiene dos partes: la premisa, que va después de la palabra SI, y la conclusión, que va después de la palabra ENTONCES. Por ejemplo: si el puesto es menor a 20 o la nota es mayor a 7, entonces se admite y se notifica al estudiante. Cuando la premisa o la conclusión tienen una sola afirmación, hablamos de una regla simple; cuando tienen dos o más afirmaciones conectadas con operadores como Y, O o NO, hablamos de una regla compuesta.
## ESCENA 4.  Motor de inferencia  
Mostrar diapositiva 9 (Motor de inferencia).
El motor de inferencia es el componente del sistema experto que utiliza los hechos y las reglas de la base de conocimiento para obtener conclusiones, aplicando la lógica clásica. Su funcionamiento se puede resumir en tres pasos básicos.
Primero, el reconocimiento de patrones: se comparan las premisas de las reglas con los hechos que están en la memoria de trabajo, y las reglas que pueden aplicarse se guardan en una lista llamada Agenda. Segundo, la resolución de conflictos: el motor elige una regla entre todas las que se cumplen, y ejecuta su conclusión. Tercero, la ejecución: al ejecutarse la regla elegida, se generan nuevos hechos que se incorporan a la memoria de trabajo. Este ciclo se repite hasta que ya no se pueden obtener más conclusiones.
## ESCENA 5.  Inferencia lógica: Modus Ponens y Modus Tollens  
Mostrar diapositiva 10 (Inferencia lógica), luego 12 (Modus Ponens) y 13 (Modus Tollens).
La inferencia lógica es el proceso mediante el cual se obtiene una conclusión válida a partir de hechos conocidos y reglas, aplicando un razonamiento lógico formal. El motor de inferencia puede llegar a dos tipos de conclusiones: simples, cuando provienen de una sola regla, y compuestas, cuando provienen de la combinación de dos o más reglas.
Las dos principales reglas de inferencia lógica son Modus Ponens y Modus Tollens. Modus Ponens es la más utilizada: si tenemos la regla 'si A es cierto, entonces B es cierto', y sabemos que A es cierto, entonces concluimos que B es cierto. Se mueve hacia adelante, de la premisa hacia la conclusión.
Modus Tollens funciona al revés: si tenemos la misma regla, pero sabemos que B es falso, entonces concluimos que A es falso. Se mueve hacia atrás, de la conclusión hacia la premisa. Es importante entender que estas dos reglas no son alternativas, sino complementarias: usarlas juntas permite obtener más conclusiones que usar solo una de ellas.
## ESCENA 6.  Encadenamiento y resolución (estrategias de inferencia)
Mostrar diapositiva 14 (Mecanismo de resolución) y diapositiva 15-16 (Encadenamiento).
Cuando una conclusión depende de dos o más reglas combinadas, se utiliza el mecanismo de resolución, que sigue tres etapas: primero se sustituye cada regla por una expresión lógica equivalente; después esas expresiones se combinan en una sola; y finalmente esa expresión combinada, junto con la evidencia disponible, produce la conclusión.
Otra estrategia muy usada es el encadenamiento de reglas. Cuando la premisa de una regla coincide con la conclusión de otra, los hechos se van encadenando para producir nuevos hechos, hasta que ya no pueden obtenerse más conclusiones. Si el encadenamiento parte de los hechos conocidos hacia las conclusiones, se llama encadenamiento hacia adelante; si parte de un objetivo y busca los hechos necesarios para confirmarlo, se llama encadenamiento orientado a un objetivo, o hacia atrás.
## ESCENA 7.  Línea de tiempo de los sistemas expertos  
Mostrar diapositiva 17 (Línea de tiempo).
Los sistemas expertos tienen una historia de varias décadas. En 1965 nace DENDRAL, considerado el primer sistema experto, desarrollado para inferir estructuras químicas complejas. Entre 1972 y 1976 se desarrolla MYCIN, en la Universidad de Stanford, capaz de diagnosticar infecciones bacterianas y recomendar tratamientos.
En 1980 aparece XCON, el primer sistema experto comercial exitoso, usado por Digital Equipment Corporation para configurar computadoras. Durante los años ochenta hubo un auge comercial de los sistemas expertos, pero a finales de esa década se vivió un segundo invierno de la inteligencia artificial, debido a limitaciones de escalabilidad y altos costos. Desde los años noventa hasta hoy, los sistemas basados en reglas se han combinado con probabilidad, lógica difusa y redes neuronales, dando lugar a enfoques híbridos más robustos.
## ESCENA 8.  Tipos de sistemas expertos   
Mostrar diapositiva 18 (Tipos de sistemas expertos).
Existen distintos tipos de sistemas expertos, según el método de razonamiento que utilizan. Los basados en reglas usan estructuras SI-ENTONCES sobre hechos para deducir conclusiones; es el enfoque clásico que hemos explicado durante todo el video. Los basados en casos resuelven nuevos problemas adaptando soluciones de casos previos similares. Los basados en redes neuronales aprenden patrones a partir de datos, sin reglas explícitas.
También existen los basados en lógica difusa, que manejan la incertidumbre usando grados de verdad en lugar de solo verdadero o falso; los sistemas híbridos, o neuro-difusos, que combinan redes neuronales con lógica difusa; y los basados en probabilidad, que generalizan los sistemas basados en reglas incorporando medidas de incertidumbre.
## ESCENA 9.  ¿Qué es un sistema experto? (síntesis) 
Mostrar diapositiva 19 (Sistema experto).
Con todo lo anterior, ya podemos responder a la pregunta central: ¿qué es un sistema experto? Un sistema experto es un sistema informático que emula la capacidad de decisión de un experto humano en un dominio específico, mediante una base de conocimiento, formada por hechos y reglas, y un motor de inferencia que aplica la lógica para deducir conclusiones.
Además de estos dos componentes principales, un sistema experto completo incluye un subsistema de explicación, que justifica el porqué de cada conclusión, y un control de coherencia, que evita que existan reglas o hechos contradictorios dentro del sistema.
## ESCENA 10.  Ventajas y limitaciones
Mostrar diapositiva 20 (Sistema experto).
Ventajas y limitaciones, capturan y conservan el conocimiento experto, razonamiento transparente: cada conclusión tiene una explicación basada en reglas, consistencia: aplican siempre las mismas reglas y útiles en dominios bien estructurados y deterministas.
Limitaciones, adquisición del conocimiento lenta y costosa, dificultad para manejar conocimiento inconsistente, incompleto o impreciso, el sistema es tan bueno como el experto consultado y escalan mal ante dominios muy amplios o cambiantes.
## ESCENA 11.  Cierre y despedida  
[CÁMARA / INDICACIÓN] Volver a cámara, cuerpo entero, misma vestimenta formal del inicio.
En resumen, hemos visto que el conocimiento se traduce en hechos y reglas dentro de una base de conocimiento; que el motor de inferencia aplica Modus Ponens, Modus Tollens, resolución y encadenamiento para razonar sobre ese conocimiento; y que, desde DENDRAL hasta los sistemas híbridos actuales, los sistemas expertos han evolucionado para incorporar cada vez más incertidumbre y aprendizaje.
Con esto concluyo mi presentación sobre Sistemas Expertos. Muchas gracias por su atención.


# VIDEO SUBIDO A YOUTUBE - ENLACE
* https://youtu.be/YZBm4GsdXzI
