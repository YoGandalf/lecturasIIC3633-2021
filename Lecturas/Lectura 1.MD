# Resumen

El *paper* toca muchos de los temas relacionados a los sistemas recomendadores desde el principio,
dando pros y contras de cada uno de ellos. Ningún tema lo aborda en profundidad, pero sí menciona
los principales desafíos desde un punto de vista filosófico (el qué y el porqué).


# Crítica

Es interesante el punto que dice que antes los sistemas recomendadores eran algo en sí mismos
y no como ayuda de una aplicación, ya que el mundo cada vez valora más la especificidad, y este
proceso ha sido inverso. Creo que, a medida que vayan mejorando los sistemas, se va a volver a
la idea de un recomendador en sí mismo, como pasa con Reddit, que cada vez toma más protagonismo.

Creo que esto tiene que ver con la capacidad, actualemente poco explorada, de los sistemas de
recomendar ítems para situaciones específicas. Esto ya que, dado que no existe aún una lógica
causal (como se ve en este [*paper*](http://scielo.sld.cu/scielo.php?script=sci_arttext&pid=S2307-21132013000100006)),
es necesario entregarle nosotros a la máquina el conocimeinto que ella no puede alcanzar
por sí misma. La comunidad científica siempre pensó en términos causales hasta la invención del
computador. Ahí se ocupó toda la fuerza correlacional de la tecnología. Es momento de unir ambas
cosas, con lo mejor de cada una. Por eso, creo que si somos capaces de entregarle a la máquina un
conocimiento a priori, seremos capaces de recomendar mejor (y muchas otras tareas).

En este sentido, el *implicit ranking* puede mejorar considerablemente su punto débil. De entre
todos los tópicos usados, este es el que veo más fácil de corregir, aunque suela ser considerado
el más difícil. De hecho, plataformas como YouTube ya lo están considerando, al preguntar al usuario
no solo por la calificación del producto, sino por el porqué de la misma, utilizando calificación
semántica y no solo numérica, o como llama el paper luego, *tags*.

Otro punto interesante es el de la ética y la confianza, ya que todo el estudio global existente sobre
sistemas recomendadores se basa en principios no absolutos (aunque sí muy comunes), tales como que el
fin sea maximizar el consumo y placer del usuario. A veces, un sistema recomendador debe no maximizar
el consumo, para no prestar su servicio a un vicio que pueda dañar al cliente. También puede querer no
maximizar el placer, cuidando que las pasiones del usuario se ordenen a su razón y no al revés. Por eso,
es importante recalcar siempre cuáles son los supuestos del estudio, porque es fácil creer que esta es
la verdad del estudio, cuando es solo la verdad del estudio que busca tales supuestos, y no toda ella.