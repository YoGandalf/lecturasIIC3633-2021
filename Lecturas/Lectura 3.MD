# Resumen

El *paper* tiene dos partes claramente diferenciables. En la primera se ve cómo ocupar los sistemas recomendadores
desde el modo *offline* hasta el *online*. En la segunda partes se discuten las diferentes variables que puede
querer buscar un usuario además de la precisión en el *rating*, en la línea que yo había comentado el *paper* anterior.


# Crítica

Lo que más interesante me pareció fue el tema del modo *offline*, ya que la segunda parte fue mi favorita, pero tenía una
unidad en sí misma que no me permite elegir solo algunos puntos. Es interesante la idea de aproximar algoritmos más que
*ratings* o métricas de algún tipo, sea respecto a usuarios o ítems. Creo que es una buena idea para ocupar en modo *online*
también, e ir intercalando con los demás métodos, ya que es uno muy diferente al resto, y juntos pueden predecir mucho mejor
algunas variables latentes.

A decir verdad, creo que tengo muy poco que criticar este *paper*, ya que es exactamente lo que yo esperaba. Sin embargo,
hay algunas cosas que pensaba que estarían y no están:

La primera es la falta del 'criterio de la voluntad'. Con esto me refiero a que un usuario puede 'tener ganas' de consumir
cierto tipo de productos, pero puede querer lo contrario, debido a un bien mayor. Es el caso del que tiene un vicio, o del
que tiene una urgencia, etc. Es decir, un usuario puede perfectamente querer que le recomienden lo menos preciso, o querer
que le recomienden solo algún tipo de ítems, o directamente que no le recomienden nada. Estos temas se tocan un poco pero
desde otra perspectiva, como el *Coverage*, pero nunca desde este punto de vista de la voluntad, sino siempre desde las
pasiones. Y aunque parezca muy parecido a efectos del algoritmo, que exista una diferencia metafísica creo que se debiera
traducir en una variable hasta ahora latente pero que podríamos interpretar.

Y la segunda consiste en la ponderación de estos criterios. Es decir, cuáles son más importantes de acertar que otros, también
cuándo, cómo, con qué tipo de usuarios, etc. Es decir, una conclusión más exhaustiva de la importancia de cada uno. Es difícil
proponer una solución en este espacio, pero destacaría como importante a *Privacy*, *Trust*, *Scalability* y *Confidence*, y
como menos importante a *Serenpidity* y *Risk*.