# Resumen

El *paper* no es ni demasiado intensivo ni extensivo. Empieza dando un par de nociones sobre lo que nos gustaría lograr respecto a las recomendaciones basadas en contenido, y luego pasa a sugerir diferentes métodos para lograrlo, como los *Decision Trees*, *Linear Classifiers* y *Naive Bayes* (muy comunes en Machine Learning). Finalmente termina con una pequeña reflexión.


# Crítica

En realidad me es difícil criticar algo de este *paper*, ya que es un tema relativamente distinto al resto. Lo único que me parece realmente interesante comentar es la última parte: *Limitations and Extensions*. Esto ya que me parece realmente difícil hacer algunas recomendaciones, como el ejemplo que pone el paper de los chistes. No es fácil para un algoritmo descubrir el tono que tiene una frase y el sentido en que se dice. Es más, a menos que se descubra un modo de lograr una lógica causal y no solo correlacional (esto es, la computación clásica), creo que es imposible.

La única solución que se me ocurre es almacenar a mano el llamado "conocimiento de sentido común". Por ejemplo, que una silla sirve para sentarse. El único problema es que es mucho trabajo, y no solo el almacenamiento en sí, sino también su constante actualización. Esto es necesario, ya que las masas van cambiando su forma de hablar, van cambiando los modos de entender las palabras, y van surgiendo palabras y formas de hablar nuevas.

Creo que en base a eso se puede mejorar las recomendaciones muchísimo, pero tampoco es trivial (o yo al menos no lo veo, aunque quizás en el estado del arte sí se conozca) el modo de ocuparlo en las generalizaciones posteriores.