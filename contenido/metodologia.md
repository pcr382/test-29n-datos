# Cómo funciona esta app

Es una herramienta independiente e informativa para las elecciones generales del 29 de noviembre de 2026. Sirve para ver a qué partidos te pareces según lo que piensas sobre 40 temas, consultar qué han prometido y votado y entender cómo funciona el voto. No es una web oficial y no recomienda votar a nadie.

## El test

* Son 40 afirmaciones repartidas en 10 bloques. En cada una eliges entre «Totalmente en desacuerdo» y «Totalmente de acuerdo», o «No sé», que no cuenta.
* Están redactadas para que estar de acuerdo no favorezca siempre al mismo lado: 17 acercan a posturas de derecha, más conservadoras o más centralistas; 20, a las contrarias, y 3 no se asocian a ningún eje.
* Cada afirmación tiene un «¿Qué significa?» con la situación actual y sus fuentes. No dice qué partido defiende qué, para no condicionar tu respuesta.
* Al final puedes marcar hasta 3 bloques como importantes: sus afirmaciones cuentan el doble.
* Hacen falta al menos 10 respuestas para ver resultados.

## Cómo se calcula la afinidad

* Cada partido tiene una postura en cada afirmación, en la misma escala de −2 a +2 que tus respuestas.
* En cada afirmación se mide cuánto se parecen tu respuesta y la del partido: 1 si coinciden, 0 si son opuestas (+2 frente a −2) y valores intermedios en el resto. La afinidad es la media de esas coincidencias, en porcentaje.
* Un partido solo se compara contigo si tiene postura en al menos la mitad de las afirmaciones que has respondido, y en un mínimo de 8. Si tiene postura en menos del 70 %, verás el aviso «datos incompletos» y en cuántas afirmaciones se basa su porcentaje.
* El reparto relativo convierte las afinidades de los partidos que puedes votar en porcentajes que suman 100. Usa una función exponencial que destaca las diferencias, así que no es una intención de voto ni una predicción.
* La brújula te sitúa en tres ejes —económico, social y territorial— con la media de tus respuestas en las afirmaciones de cada eje.
* Si los primeros partidos están a menos de 3 puntos, la app avisa de que hay un empate: con una diferencia tan pequeña, el orden no dice mucho.
* En cada partido puedes ver las 3 afirmaciones en las que más coincides (como mucho un punto de diferencia en la escala) y las 3 en las que más te separas (dos puntos o más).
* La afinidad por temas repite el cálculo dentro de cada bloque. Un partido solo aparece en un bloque si se puede comparar en al menos 2 de sus afirmaciones.

## Qué partidos aparecen

* Si eliges tu provincia, primero salen los partidos que puedes votar allí. Debajo salen otros partidos conocidos que no se presentan en tu provincia, con su afinidad pero sin reparto.
* Se consideran conocidos los que se presentan en toda España y los territoriales con grupo propio en el Congreso saliente: ERC, Junts, EH Bildu y PNV. BNG, CC y UPN, con un diputado cada uno, solo aparecen donde se presentan.
* La lista se actualizará con las candidaturas oficiales que publique el BOE.

## De dónde salen las posturas de los partidos

* **Votaciones y decisiones de Gobierno** de la legislatura 2023–2026: confianza alta.
* **Declaraciones** públicas: confianza media.
* **Votaciones de legislaturas anteriores**: confianza baja.
* **Programas electorales**: cuando se publiquen los del 29N, sus compromisos pasarán a ser la referencia; mientras tanto se usan los de 2023 para comparar.

Un partido tiene ±2 si impulsó la iniciativa y ±1 si la votó o la apoyó sin impulsarla. Si se abstuvo o no hay datos, la casilla queda vacía y no cuenta. Frente Amplio hereda las posturas de Sumar; Podemos se codifica aparte.

## Promesas frente a hechos

Cada ficha de partido compara, tema a tema, lo que llevaba en su programa de 2023, lo que hizo en la legislatura y lo que lleva en su programa de 2026, cuando se publique. Solo se compara el sentido, a favor o en contra, y solo con votaciones y decisiones, no con declaraciones. No hay ninguna nota de credibilidad: un partido puede votar contra una ley por otras partes de su contenido, y cada casilla enlaza a su fuente para que puedas juzgarlo.

## Tu relación con la política

Es un cuestionario opcional de 7 preguntas, aparte del test. Calcula cinco índices orientativos, con la fórmula a la vista: descontento con la política, con el Gobierno y con la oposición, y cercanía a no votar y al voto en blanco. No son predicciones y no se comparan con nadie, porque la app no guarda las respuestas de nadie.

## Adivina de quién es

Es un juego con propuestas reales de los partidos. En cada ronda salen 10 frases, como mucho una por partido, y para cada una eliges entre cuatro partidos. Después se revela de quién es y se enlaza su fuente.

* Las propuestas están resumidas con nuestras palabras, sin valoraciones y sin nombrar al partido.
* Cada partido tiene el mismo número de frases, salvo cuando no hemos encontrado propuestas suficientes que lo distingan de los demás.
* Algunas fuentes son resúmenes de propuestas elaborados por otras webs. Cuando se publiquen los programas del 29N, las sustituiremos por el programa.
* No guardamos tus respuestas: el juego funciona solo en tu dispositivo.

## Fuentes

Cada dato enlaza a su fuente y la página «Fuentes» las reúne todas, con un acceso a su copia archivada. Los datos están publicados en un repositorio público, con el historial de todos los cambios.

## Límites

* Una postura de −2 a +2 simplifica posiciones que a veces tienen matices: por eso cada una lleva su explicación y su fuente.
* Algunos partidos tienen menos datos que otros; la app lo indica.
* El test cubre 40 temas, no todos los posibles.
* Puede haber errores. Si ves uno, escríbenos y lo corregiremos: pcr382.apps@gmail.com.

## Independencia y privacidad

* **No es una web oficial.** Es un proyecto personal e independiente: no pertenece al Gobierno, a ninguna administración pública, a la Junta Electoral ni a ningún partido.
* **Tus respuestas no salen de tu móvil.** El test y el cuestionario final se calculan en tu dispositivo, no se envían a ningún servidor ni a ninguna IA y no se guardan.
* **Solo informativo.** El resultado dice a qué partidos te pareces según sus votaciones, declaraciones y programas. No es una recomendación de voto.

