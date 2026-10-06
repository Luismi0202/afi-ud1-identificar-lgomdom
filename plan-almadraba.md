# PLAN ALMADRABA

### 1. Las fuentes de evidencia

De lo que cuenta el relato, yo creo que las cosas más destacables son:

-Dell de empresa
-Disco externo de 2 TB
-El iphone que es un móvil de empresa
-El ordenador de sobremesa que tiene una sesión al nombre de otra compañera abierta
-El pendrive que le pidió Marta a Javier (está en el cajón de Javier)
-La cámara del techo del pasillo (quizá podría tener una grabación interesante y se podría pedir)
-El servidor de ficheros y el NAS
### 2. La prioridad

Miraría primero el servidor de ficheros y el NAS ya que no solo me parece el objeto más importante que tienen en esta empresa, si no que también me parece raro como todas las pistas llevan a él, quiero decir, Javier ha visto a Marta estando hasta "las tantas" siendo algo "raro en ella" y encima le pidió un pendrive para vete tú a saber qué diciéndole a Javier que su pendrive estaba roto, quizá pudo haber usado este pendrive para conectarlo al server de ficheros y llevarse el render. 

Además también es curioso que haya un ordenador de sobremesa con una cuenta de correos abierta de otra compañera ¿quizá es la cuenta de marta? es algo que según el texto se ha visto de reojo y creo que se debería de comprobar a ver si se ha cerrado sesión o no porque justo Marta se está retirando por hoy con mucha prisa. 

Luego miraría también su dell de empresa y si fuese posible porque con la torpeza se lo fuese a dejar, su disco duro externo, aunque de estas dos mejor hablamos en el siguiente punto porque aquí habría que saber si la empresa tiene firmado un papel que nos autorice poder meternos en estos equipos.

El iphone que es un móvil de empresa también es algo que tendríamos que dejar ahí pero es algo que también nos podría dar una pista lo que pasa es que también se requeriría de un permiso a no ser que esté firmado.

La cámara del techo del pasillo también me parece interesante porque quizá podemos ver a Marta entrando a hacer algo en el servidor de ficheros pero como está no urge tanta prisa porque no es algo que se pueda ir pues podemos dejarla para el final.

### 3. Las medidas inmediatas

-Dell de empresa-> Realmente dudo que aquí haya nada importante pero es mejor no apagarlo por si podemos encontrar un log de que Marta haya accedido al servidor de ficheros de alguna forma remota.

-Disco externo de 2 TB-> Si está presente en el acto realmente tampoco importa demasiado podemos dejarlo ahí al final es no volátil aunque hay alguna información que cambia al apagar el equipo así que por si acaso lo dejo conectado a su respectivo equipo sin tocar nada.

-El iphone/móvil de empresa-> Siendo realista, en esta situación Marta seguramente se lo haya llevado pero en caso de que esté en la empresa, pues se deja ahí sin tocar y ya lo reviso

-El ordenador de sobremesa que tiene una sesión al nombre de otra compañera abierta-> **DEJARLO ENCENDIDO SÍ O SÍ Y FOTOGRAFIAR, HAY OTRA SESIÓN DE LA CUÁL SEGÚN EL TEXTO NO ME HE PARADO A MIRAR MUCHO ASÍ QUE MEJOR MIRO A VER SI ES MARTA O SI ESTÁ CERRADA YA, PORQUE AL FINAL AL SERVIDOR DE FICHEROS SE ACCEDE DESDE CORREOS**

-El pendrive que le pidió Marta a Javier (está en el cajón de Javier)-> Pedirselo a Javier de una forma amable y así tendremos una de las pistas que más me huelen a chamusquina en este caso ¿porque querría Marta un pendrive? Huele rarete.

-La cámara del techo del pasillo (quizá podría tener una grabación interesante y se podría pedir)-> Pedírle a quién sea que lleve las grabaciones de la cámara si me da permisos para poder revisarlas porque creo que aquí se podría ver una pista de lo que Marta pudo hacer si es que se ve que entrase en la sala del servidor.

-El servidor de ficheros y el NAS-> **DEJARLO ENCENDIDO MIENTRAS VALORO JUNTO CON BAHÍA SISTEMAS SI CONVIENE AISLARLO DE LA RED, AQUÍ SEGURAMENTE ENCUENTRE LA CHICHA DEL ASUNTO, O ESO ME DICE MI OLFATO DE FORENSE (llevo solo 1 día de clases en esto pero yo confío en él venga va)**

### 4. Los límites

Como ya dije antes, no podría tocar nada que sea de Marta aunque sean equipos de la empresa a no ser que ellos tengan firmados algún tipo de consentimiento para que yo pueda mirar porque si no realmente sería ilegal a no ser que el jurado me diera el visto bueno y aún así, aunque pueda mirar, estoy un poco restringido a no poder mirar Whatssapps o cosas privadas. Así que el iphone y el dell se quedan un poco en el limbo ahora mismo.

El disco duro externo realmente también sería algo privado y a no ser que un jurado me dé el visto bueno no podría revisarlo porque al final eso es algo privado de Marta, incluso se podría preguntar permisos para poder verle su móvil personal a ver si tiene algo pero eso ya sería escalarlo demasiado creo que con lo que tengo se podría llegar a algo.

La cámara del techo del pasillo tampoco es algo que pueda hacer inmediatamente pero al final eso es tan fácil como preguntar si se puede mirar a quién sea que lo lleve.

El servidor de ficheros también sería buena idea llamar a Bahía sistemas antes de trastear nada porque al final ellos son los técnicos informáticos y no está de más dar un aviso de que tengo que tocar logs para poder ver si han habido movimientos extraños.

### 5. De dónde sale cada decisión

A tener en cuenta es que para este paso he seguido mi propia lista de comprobación como pedía el ejercicio así que citaré en cada apartado el punto de mi lista junto a los puntos en los que se basa de las otras normativas que he visto en este ejercicio para así poder relacionar todo lo que he aprendido en esta actividad en un mismo sitio.

#### 1) Servidor de ficheros y NAS
- Lo prioricé por encima del resto porque las pistas del relato parecen converger en ese punto: las horas extra de Marta, la petición del pendrive y la posible copia del render apuntan a un acceso o una extracción de información desde ese sistema.
- La lista de actuación indica que se debe valorar el valor de los datos y el tiempo necesario para obtenerlos, no solo la volatilidad. Esto encaja con el punto 3.1 de la lista y con la lógica de RFC 3227 §2.1 y NIST SP 800-86 §3.1.2.
- También encaja con los puntos 1.6 y 1.8, que hablan de identificar fuentes relevantes y buscar información en sistemas o datos relacionados con la incidencia (NIST SP 800-86 §3.1.1; ENFSI §9.2; RFC 3227 §§2.1, 3.2).

####  2) Dell y ordenador de sobremesa
- Decidí dejar encendido el Dell y el ordenador de sobremesa, y fotografiar este último antes de tocarlo, porque podrían contener información volátil que desaparece al apagarlos: sesiones abiertas, accesos activos o conexiones recientes.
- Esto se relaciona con la valoración de datos volátiles y con la obligación de describir y fotografiar el estado del equipo antes de cualquier manipulación, según los puntos 2.3 y 2.1 (ENFSI §§9.1, 8.2, 9.2; RFC 3227 §§2.1, 2.2).
- No obstante, antes de revisar la sesión o abrir correos, comprobaría si está dentro del alcance autorizado. Aquí entran los puntos 1.1 y 2.6 (RFC 3227 §§2.4, 2.3).

####  3) Disco externo de 2 TB
- Lo considero una fuente posible, pero no la pondría por delante del servidor y el NAS. En principio, no parece tan urgente ni tan directamente conectada con la posible copia del render.
- La decisión de priorizar por valor y tiempo de adquisición está conectada con el punto 3.1 (RFC 3227 §2.1; NIST SP 800-86 §3.1.2).
- Mientras no quede claro que puedo revisarlo, mantendría la mínima interacción posible, tal y como indica el punto 2.5 (RFC 3227 §§2, 2.2, 5).

####  4) iPhone de empresa
- No revisaría el iPhone si aparece sin confirmar antes el alcance y la autorización.
- Puede contener información útil, pero también datos personales o privados que no están dentro del objetivo inicial del caso.
- Por eso, primero comprobaría si está permitido acceder a él y qué tipo de datos serían relevantes. Esto se apoya en los puntos 1.1 y 2.6 (RFC 3227 §§2.4, 2.3, 3.2).
- Si estuviera encendido, también aplicaría la valoración de datos volátiles antes de decidir si se apaga o se conserva, como indica el punto 2.3 (ENFSI §9.1; RFC 3227 §§2.1, 2.2).

####  5) Pendrive solicitado por Marta
- Pediría el pendrive a Javier y lo conservaría sin manipularlo, porque Marta se lo pidió y eso encaja con la posible copia o traslado de información.
- No demuestra por sí solo un delito, pero sí es un indicio importante que debe recogerse y documentarse.
- Este tipo de pista entra dentro de preguntar a personas implicadas y hacer un inventario de fuentes potenciales, según los puntos 1.3 y 1.6 (RFC 3227 §§3.2, 4.1; NIST SP 800-86 §3.1.1; ENFSI §9.2).
- Si se recoge, lo dejaría bajo cadena de custodia con constancia de quién lo entrega y en qué condición, siguiendo el punto 3.5 (RFC 3227 §§3.1, 3.2, 4.1; ENFSI §9.2).

####  6) Cámara del pasillo
- La cámara también la tendría en cuenta porque podría demostrar quién entró en la sala del servidor y cuándo.
- La lista recoge la búsqueda de cámaras y otras fuentes externas en el punto 1.6, y la consulta de fuentes ajenas a la habitación en el punto 1.8 (NIST SP 800-86 §3.1.1; RFC 3227 §§2.1, 3.2).
- Antes de pedir o analizar las grabaciones, confirmaría que el acceso está autorizado, según el punto 2.6 (RFC 3227 §§2.3, 2.4, 3.2).

####  7) Coordinación con Bahía Sistemas
- Avisaría a Bahía Sistemas antes de intervenir en el servidor o el NAS, porque son los responsables técnicos y pueden ayudar a identificar los registros relevantes sin provocar cambios innecesarios.
- Esto se relaciona con confirmar quién autoriza la intervención y reducir al mínimo la alteración del sistema, según los puntos 1.1 y 2.5 (RFC 3227 §§2.4, 2, 2.2, 5).

####  8) Límite de autorización
- No daría por hecho que puedo revisar cualquier equipo o dato. Antes de ampliar la investigación, confirmaría qué está permitido y qué datos quedan fuera del alcance.
- Esto es especialmente importante en los equipos usados por Marta y en cualquier dato personal o privado que pueda contener. Eso encaja con los puntos 1.1 y 2.6 (RFC 3227 §§2.4, 2.3, 3.2).

####  9) Aislamiento del servidor y del NAS
- Sobre aislarlos, no lo decidiría automáticamente. Aunque dejaría los equipos encendidos mientras valoro la situación, antes de desconectarlos de la red revisaría si alguien podría seguir modificando datos desde fuera.
- La lista recomienda valorar el riesgo y documentar la decisión, según el punto 2.4 (RFC 3227 §2.2; ENFSI §8.2).
- Por eso, en vez de decir “aislar sí o sí”, lo dejaría como una decisión pendiente de esa valoración.