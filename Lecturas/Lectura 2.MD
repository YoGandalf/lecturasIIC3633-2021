# Resumen

El *paper* habla de los sistemas anteriores a los de *matrix factorization*, y luego explica por qué
este es tan conveniente. Luego explica algunas variaciones del mismo, que aportan exactitud pero exigen
mayor capacidad de cómputo, como los *bias*, *signal sources*, *temporal dynamics*, etc. Luego, terminan
con el ejemplo de Netflix.


# Crítica

Encontré especialmente interesante el tema de eliminar valores de la matriz en lugar de imputarlos, ganando en
capacidad de cómputo, e incluso ganando también en exactitud si la imputación no se lleva correctamente a cabo.
Creo que el criterio de los vectores (y valores) propios es muy adecuado para saber cuáles datos conviene eliminar.
Lo único que me hace algo de ruido es que debiera haber un algoritmo más explícito para saber cuántos eliminar y
cuántos imputar, y no solo mencionarlo, porque creo que lo mejor es buscar el equilibrio entre la total eliminación
y la total imputación, que en algunos casos puede ser alguno de los dos extremos.

También creo que es muy interesante el tema de los *latent factors*, que, aunque creo que están bien llevados desde
el punto de vista de la computación, creo que se debiera tomar mucho en cuenta desde el punto de vista lógico humano,
para poder lograr entenderlo de un mejor modo, y poder indagar en él.

Es también interesante el tema de los *temporal dynamics*, y creo que debiera haber sido considerado desde el
comienzo del estudio. Sin embargo, creo que aún faltan algunas cosas por tomar en cuenta, y de entre
ellas, la más importante es la capacidad de influencia que tiene el propio sistema de recomendación sobre
los usuarios. Lo digo porque a mí me ha pasado que YouTube me recomienda constantemente un video que en
principio no me llama la atención, pero ante la insistencia decido verlo, sea por confianza en el sistema
de recomendación, sea porque es el primero que aparece en el *feed*, o por cualquier otro motivo.
Entonces YouTube tiende a premiar su sistema, pensando que fue una buena recomendación, siendo que algunas
veces (otras sí) no lo fue.

En el tema del *dot product*, creo que falta una variable. Y es que se toma en cuenta la dirección de ambos
vectores (el coseno), y también la longitud de ambos. Sin embargo no se toma en cuenta la diferencia (o proporción
o cualquier métrica de este tipo) de los vectores. Y creo que es un error, porque un usuario puede estar en la misma
dirección que un ítem, pero no necesariamente por eso estarán cerca. Encuentro incluso más adecuado ocupar una
norma *p* cualquiera, si no se toma en cuenta la distancia entre ellos.
