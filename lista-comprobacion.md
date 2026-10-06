# Lista de comprobación

## 1. Al llegar

1. **Confirmar qué se puede intervenir y con quién coordinarse.** Aclaro el alcance de la actuación y quién autoriza o dirige cada paso antes de recoger datos.  
   *RFC 3227 §2.4*

2. **Evitar que se manipulen los dispositivos.** Aparto a sospechosos y testigos de los equipos y controlo quién puede acercarse.  
   *ENFSI §8.2*

3. **Preguntar qué ha ocurrido y qué podría ser relevante.** Pregunto a quien avisa, a los usuarios y a los testigos qué equipos se usaban, qué vieron y qué cambios se hicieron. No doy por hecho que la primera respuesta sea la única pista.  
   *RFC 3227 §§3.2, 4.1; NIST SP 800-86 §3.1.1*

4. **Anotar quién está presente y qué observa.** Registro sus nombres, funciones y cualquier actuación o comentario relevante durante la intervención.  
   *RFC 3227 §3.2*

5. **Registrar la escena antes de mover nada.** Hago fotos y un croquis sencillo con la ubicación de los equipos, su estado y los elementos conectados. Recorro el lugar de forma ordenada, prestando atención a las zonas relacionadas con lo que se investiga.  
   *ENFSI §8.2*

6. **Hacer un primer inventario de posibles fuentes.** Busco ordenadores, servidores, portátiles, móviles, cámaras, soportes de almacenamiento y otros dispositivos que puedan contener datos relevantes.  
   *NIST SP 800-86 §3.1.1; ENFSI §9.2*

7. **Seguir las conexiones.** Miro qué está conectado por cable, red inalámbrica, radiofrecuencia o infrarrojos: periféricos, unidades externas, equipos cercanos y dispositivos que puedan comunicarse entre sí.  
   *ENFSI §8.2; RFC 3227 §2.1*

8. **Preguntar si hay fuentes que no están en la habitación.** Compruebo si existen servidores, almacenamiento en red, registros remotos o sistemas de monitorización relacionados con los equipos encontrados.  
   *NIST SP 800-86 §3.1.1; RFC 3227 §§2.1, 3.2*

## 2. Antes de tocar nada

1. **Describir el estado de cada dispositivo.** Anoto si está encendido o apagado, qué aparece en la pantalla, qué cables tiene y dónde está. Si hace falta, fotografío la pantalla antes de interactuar con ella.  
   *ENFSI §§8.2, 9.2*

2. **Anotar la hora que muestra y compararla con la hora real.** Dejo claro si uso hora local o UTC y registro cualquier diferencia que observe.  
   *RFC 3227 §§2, 3.2*

3. **Averiguar si hay datos que solo existen mientras el equipo está encendido.** Antes de apagarlo, considero si puede haber información en memoria, sesiones abiertas, cifrado activo o riesgo de borrado o reinicio remoto.  
   *ENFSI §9.1; RFC 3227 §§2.1, 2.2*

4. **Decidir con cuidado si se aísla de la red.** No desconecto automáticamente: valoro si alguien podría modificar datos desde fuera y si cortar la conexión podría activar un borrado u otro cambio. Documento la decisión.  
   *RFC 3227 §2.2; ENFSI §8.2*

5. **Reducir al mínimo los cambios que puedo causar.** No pruebo funciones ni ejecuto programas sin necesidad; si hay que recoger datos de un sistema activo, uso herramientas preparadas y medios adecuados.  
   *RFC 3227 §§2, 2.2, 5*

6. **Revisar el alcance y la privacidad antes de ampliar la búsqueda.** Si aparece una fuente nueva o datos que no esperaba, compruebo que su recogida esté justificada y autorizada.  
   *RFC 3227 §§2.3, 2.4, 3.2*

7. **Completar la lista de sistemas y datos que se van a recoger.** Para cada fuente, explico qué relación puede tener con el caso y qué evidencia espero obtener. Si tengo dudas, las dejo anotadas para decidirlas con el equipo.  
   *RFC 3227 §3.2; NIST SP 800-86 §3.1.1*

## 3. Al decidir qué se adquiere y en qué orden

1. **Priorizar con más de un criterio.** Tengo en cuenta la volatilidad, el valor de los datos para la investigación y el tiempo o esfuerzo que llevará obtenerlos.  
   *RFC 3227 §2.1; NIST SP 800-86 §3.1.2*

2. **Si procede recoger datos en vivo, empezar por los que pueden desaparecer antes.** Por ejemplo, memoria, procesos, conexiones y estado de red; después, otros datos temporales y el almacenamiento persistente. Ajusto el orden al dispositivo y a lo que ya sé de él.  
   *RFC 3227 §§2.1, 3.2; ENFSI §9.1*

3. **No olvidarme de las fuentes menos visibles o menos volátiles.** Incluyo sistemas de archivos temporales, discos, registros remotos, datos de monitorización, configuración física y topología de red, además de soportes de archivo.  
   *RFC 3227 §2.1; NIST SP 800-86 §§3.1.1, 3.1.2*

4. **Seguir un procedimiento ordenado y explicar cualquier cambio de plan.** En un mismo sistema voy paso a paso; si hay varios equipos y personal suficiente, se puede trabajar en paralelo sin perder el control de cada recogida.  
   *RFC 3227 §§2, 3.1, 3.2*

5. **Dejar documentado qué se recogió y qué pasó con ello.** Registro método, hora, persona responsable, identificador del elemento y cada cambio de custodia. Cuando corresponda, verifico las copias con sumas de comprobación y conservo los originales protegidos.  
   *RFC 3227 §§3.1, 3.2, 4.1; ENFSI §9.2*