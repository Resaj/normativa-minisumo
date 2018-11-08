ESTA NORMATIVA SE ENCUENTRA EN CONSTRUCCION. EL TEXTO QUE FIGURA A CONTINUACIÓN ES PROPIEDAD DE [BRICO-LABS](https://github.com/brico-labs) Y HACE REFERENCIA A LAS COMPETICIONES CELEBRADAS EN LA OSHWDEM. SE HA COPIADO EN ESTE REPOSITORIO CON EL OBJETIVO DE UTILIZAR COMO PLATILLA DURANTE EL DESARROLLO Y COMPATIBILIZAR LA NORMATIVA DE OPEN-ROBOSPORT CON LAS COMPETICIONES PROPIAS DE LA OSHWDEM :)


# Normativa de Sumo (Minisumo)
Revisión 3 (2015): vigente desde OSHWDem 2015

# Índice
- .[Objetivo]()

# Objetivo
Dos robots compiten entre sí simulando los enfrentamientos humanos de sumo. No se permite a los robots la utilización de armas ni girar sobre sí mismos, y el único objetivo es empujar al robot oponente para sacarlo del Dohyo. El torneo se lleva a cabo mediante el sistema de eliminación simple al mejor de 3 rondas. (Valoramos la clasificación estilo suizo o una liguilla con cabezas de serie en caso de tener ya la clasificación anterior). El robot que primero consiga dos puntos pasará a la siguiente fase del torneo.
El reglamento se detalla a continuación.

# Sección 1: Definición de los enfrentamintos de Sumo Robot
- Artículo 1.- Definición
Un enfrentamiento se libra entre dos participantes. De acuerdo con las reglas del juego (en adelante “el presente Reglamento”) cada participante compite en un Dohyo (ring de sumo) con un robot construido por el/la participante según lo especificado en la Sección 3. Las rondas comienzan a las órdenes del juez y continúa hasta que un participante gana dos puntos. El juez determina el ganador del enfrentamiento.
# Sección 2: Requisitos del Dohyo
- Artículo 2.- Interior del Dohyo
El interior del Dohyo se define como la superficie de juego rodeada de una línea en el borde, que también forma parte de la superficie de juego. Cualquier lugar fuera de esta área se considera el exterior del Dohyo.
- Artículo 3.- Especificaciones del Dohyo
El Dohyo será de forma circular y de unas dimensiones adecuadas para cada clase de robot.
Las líneas de inicio (shikiri-sen) constan de dos líneas paralelas pintadas en color marrón (o equivalente para la absorción de la luz IR) centradas en el Dohyo, con unas dimensiones y espacio de separación adaptadas a cada clase de robot. La distancia de separación entre las líneas se mide a sus bordes exteriores.
La línea del borde se marca como un anillo circular blanco de un ancho apropiado para cada clase de robot, en el borde exterior de la superficie de juego. El área del Dohyo se extiende hasta el borde exterior de esta línea circular.
<img src="https://raw.githubusercontent.com/brico-labs/Regulamentos/gh-pages/img/minisumo_dohyo.png" width="400" height="400">
*Especificaciones del Dohyo
<table>
  <thead>
    <tr>
      <th style="text-align: left">Clase</th>
      <th style="text-align: center">Altura</th>
      <th style="text-align: center">Diámetro</th>
      <th style="text-align: center">Material</th>
      <th style="text-align: center">Grosor*</th>
      <th style="text-align: center">Longitud*</th>
      <th style="text-align: center">Separación*</th>
      <th style="text-align: center">Ancho borde</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left">Mini</td>
      <td style="text-align: center">19mm</td>
      <td style="text-align: center">77 cm</td>
      <td style="text-align: center">MDF</td>
      <td style="text-align: center">2 cm</td>
      <td style="text-align: center">10 cm</td>
      <td style="text-align: center">10 cm</td>
      <td style="text-align: center">2,5 cm</td>
    </tr>
  </tbody>
</table>
<tr>
      <th style="text-align: left">Clase</th>
      <th style="text-align: center">Altura</th>
      <th style="text-align: center">Diámetro</th>
      <th style="text-align: center">Material</th>
      <th style="text-align: center">Grosor*</th>
      <th style="text-align: center">Longitud*</th>
      <th style="text-align: center">Separación*</th>
      <th style="text-align: center">Ancho borde</th>
    </tr>
* Líneas de inicio (shikiri-sen) Estas medidas puoden variar un 5%

- Artículo 4.- Exterior del Dohyo
Debe haber un espacio, adecuado a cada clase de robot, fuera del borde exterior del Dohyo. Este espacio puede ser de cualquier color, material o forma. Este área, con el Dohyo en el medio, se va a llamar el “área del Dohyo”. Cualquier marca o parte de la plataforma del Dohyo fuera de las dimensiones mínimas también serán considerados en el área del Dohyo.
# Sección 3: Reglamentación para los Robots
- Artículo 5.- Especificaciones
La placa controladora del robot, en caso de haberla, debe estar basada en tecnologías abiertas. También son válidas las plataformas o kits de robótica basados en tecnologías abiertas.
El robot debe caber en un cubo de las dimensiones establecidas para cada clase. Un robot puede expandirse en tamaño una vez se da comienzo al enfrentamiento, pero no puede separarse físicamente en pedazos y debe seguir siendo un sólo robot centralizado. Los robots que no cumplan esta restricción perderán la partida. Los tornillos, tuercas y otras partes del robot con una masa total de menos de 5 gramos que caigan del cuerpo de un robot no causarán la pérdida de la partida.
La masa total de un robot al comienzo de una partida debe estar por debajo de la especificada para cada clase.
<table>
  <thead>
    <tr>
      <th style="text-align: left">Clase</th>
      <th style="text-align: center">Altura</th>
      <th style="text-align: center">Anchura</th>
      <th style="text-align: center">Longitud</th>
      <th style="text-align: center">Masa</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left"><strong>Mini</strong></td>
      <td style="text-align: center">Ilimitada</td>
      <td style="text-align: center">10 cm</td>
      <td style="text-align: center">10 cm</td>
      <td style="text-align: center">500 gr</td>
    </tr>
  </tbody>
</table>
<body>
Clases autónomas: Los robots de la clase Mini (500gr) deben ser autónomos. Se puede utilizar cualquier método de control, siempre y cuando esté integrado enteramente en el robot y no reciba señales o indicaciones externas (de cualquier tipo). El funcionamiento autónomo del robot no debe comenzar antes de 5 segundos después de ser iniciado por el usuario. Los robots que no respeten el intervalo de los 5 segundos pierden el punto de esa ronda.
El robot debe tener un nombre o número con fines de registro y seguimiento. El robot debe mostrar este nombre o número para permitir su identificación a la organización y jueces y a los espectadores.
  
- Artículo 6.- Restricciones
· Dispositivos para crear interferencias (jamming), como LED’s IR con la intención de saturar los sensores IR del oponente.
· Partes que puedan dañar o romper el Dohyo. Usar partes que puedan dañar intencionadamente al robot oponente o a su operador. Los empujones y golpes derivados de estos no están considerados con intención de causar daño.
· Dispositivos que puedan almacenar líquidos, polvo, gas u otras sustancias para lanzar al oponente.
· Dispositivos de pirotecnia.
· Dispositivos que lancen objetos al oponente.
· La utilización de sustancias pegajosas para incrementar la tracción.
· El uso de dispositivos para incrementar el “efecto suelo”, como bombas de vacío o imanes.
· El uso de bordes afilados, incluidos pero no limitados a la pala frontal, que puedan dañar el Dohyo, otros robots o a los participantes. Los bordes que, a criterio de los jueces, se consideren que pueden causar daño deberán ser cubiertos con algún tipo de cinta.
· El uso de cualquier tipo de fuente de energía para el funcionamiento del robot que no sea la proporcionada por pilas o baterías eléctricas.
# Sección 4: Desarrollo de las partidas
- Artículo 7.- Desarrollo de las partidas
Una partida consta de tres rondas, con un tiempo total de tres minutos, a menos que sea extendido por los jueces.
El primer participante que gane dos rondas o reciba dos puntos, dentro del tiempo límite, será el ganador de la partida. Un participante recibe un punto cuando gana una ronda. Si se alcanza el límite de tiempo antes de que un participante pueda obtener dos puntos y uno de los participantes ha recibido un punto, el participante con ese punto se considera el ganador de la partida.
Cuando haya un empate entre dos participantes y se alcance el tiempo límite, podría establecerse una nueva ronda (ronda extendida), durante la cual el participante que consiga el punto se convertirá en el ganador de la partida.
# Sección 5: Comienzo, parada, reanudación y finalización de una ronda
- Artículo 8.- Comienzo
Tras las instrucciones de los jueces, los dos participantes se acercarán al Dohyo y pondrán un robot en su mitad del Dohyo, detrás de la línea de inicio. El robot o cualquier parte de este no puede ser colocado más allá de la línea de inicio hacia su oponente. No se requiere poner el robot directamente detrás de dicha línea de inicio y podrá colocarse en cualquier zona siempre que respeta una línea imaginaria respecto de la línea de inicio. Cuando el juez anuncie el comienzo de la ronda, los participantes activarán sus robots y, después de cinco segundo, los robots empezarán a operar. Durante estos cinco segundos los participantes deberán abandonar el área del Dohyo.
- Artículo 9.- Parada y reanudación
Las rondas se paran y reanudan por indicación de los jueces.
- Artículo 10.- Finalización
Las rondas finalizan por indicación de los jueces. Los participantes podrán recuperar sus robots en el área del Dohyo.
# Sección 6: Tiempo de partida
- Artículo 11.- Tiempo de partida
Una partida debe llevarse a cabo en un total de 3 minutos, que comenzarán y finalizarán por orden de los jueces.
- Artículo 12.- Rolda extra
Si, por decisión de los jueces, se requiera una ronda extra, ésta tendrá una duración máxima de 3 minutos.
- Artículo 13.- Exclusións de tempo
Lo siguiente no está incluido dentro del tiempo de partida:
· El tiempo transcurrido desde que los jueces anuncian el punto de la ronda hasta el comienzo de la siguiente ronda. El tiempo establecido entre rondas es de 30 segundos.
· El tiempo transcurrido desde que los jueces anuncian la parada de la ronda hasta su reanudación.
# Sección 7: Puntuación
- Artículo 14.- Puntuación
Un punto se otorga cuando:
Un participante fuerza al robot contrincante a tocar el área fuera del Dohyo, incluyendo el borde lateral del mismo.
El robot contrincante, por sí mismo, toca el área fuera del Dohyo, incluyendo el borde lateral del mismo. Se mantiene esta norma hasta que se anuncia el final de la ronda.
Cuando se requiera la decisión de los jueces para determinar el ganador de una ronda se tendrán en cuenta las siguientes consideraciones:
méritos técnicos en el movimiento y funcionamiento de un robot.
las penalizaciones durante la ronda.
actitud del participante durante la partida.
La ronda se detendrá y volverá a comenzar en las siguientes condiciones:
los robots están enredados u orbitando entre sí sin ningún progreso aparente durante 5 segundos. Si no está clara la intención de los robots, el juez puede prorrogar dicho plazo hasta un máximo de 30 segundos.
ambos robots se mueven sin intención de luchar, o se paran al mismo tiempo y permanecen detenidos durante 5 segundos sin tocarse. Sin embargo, si un robot detiene su movimiento en primer lugar, transcurridos cinco segundos será declarado como que no tiene intención de luchar. En este caso, el oponente recibirá un punto, incluso si éste último también se detiene. Si los dos robots se mueven y no está claro si se están progresando, el juez puede prorrogar el plazo hasta un máximo de 30 segundos.
si los dos robots tocan el exterior del Dohyo más o menos al mismo tiempo, y no se puede determinar quién tocó en primer lugar, se comenzará una nueva ronda.
# Sección 8: Faltas
- Artículo 15.- Faltas
Los participantes que realicen cualquiera de los hechos descritos en los Artículos 6, 16 o 17, serán amonestados por saltarse este reglamento.
- Artículo 16.- Insultos
Un participante que profiere insultos al oponente o a los jueces, o pone voces en el robot que pronuncie palabras insultantes, o que aparezcan escritas en el cuerpo del robot, o que realice gestos insultantes, se considera una falta por incumplimiento de este reglamento.
-  Artículo 17.- Faltas leves
Se considera una falta leve cuando un participante:
· Entra en el Dohyo durante la ronda, excepto cuando el participante lo hace pararecoger el robot fuera del Dohyo una vez el juez anunció la asignación del punto o para la ronda. Entrar en el Dohyo significa:
·una parte del cuerpo del participante está en el Dohyo.
un participante utiliza algún mecanismo para tocar el Dohyo.
· Realiza las siguientes acciones:
·Exige parar la ronda sin razones aparentes.
·Tarda más de 30 segundos para comenzar la ronda, a menos que el juez incremente el tiempo.
·Poner en funcionamiento el robot dentro de los cinco segundos después de que el juez anuncia el comienzo de la ronda.
·Hacer alusiones a la imparcialidad de la ronda, la partida o el torneo.
# Sección 9: Penalizaciones
- Artículo 18.- Penalizaciones
Los jugadores que incumplan los artículos 6 y 16 del presente reglamento perderán la partida y serán descalificados del torneo. El juez otorga dos puntos al oponente.
- Artículo 19.- Acumulación de faltas
Las faltas leves descritas en el artículo 17 son acumulativas a lo largo de toda la ronda. Dos faltas leves conllevan otorgar un punto al oponente.
# Sección 10: Jueces
- Artículo 20.- Los jueces
En la sala habrá una persona identificada como “juez principal” y será la encargada de comunicar cualquier decisión final con respecto al desarrollo de la competición y la interpretación de las normas.
Otras personas pueden estar identificadas como “juez asistente” y ayudarán al juez principal en las tareas que tengan delegadas.
El participante siempre se debe dirigir al juez principal para cualquier reclamación o aclaración de las normas. Entonces, si el juez principal lo estima oportuno, puede redirigir al participante al juez asistente.
Las decisiones finales simpre las tomará el juez principal.
- Artículo 21.- Declaración de objeciones
Un participante puede presentar objeciones a la organización antes de que termine la ronda, si hay alguna duda en el ejercicio de este reglamento. Si no hay miembros de la organización presentes, la objeción se puede presentar al juez antes de la finalización de la ronda.
# Sección 11: Requirimentos para la identificación de los robots
- Artículo 22.- Identificación de los robots
Los robots deben mostrar algún tipo de identificación (nombre y/o número), en lugar bien visible y fácilmente legible, mientras el robot se encuentre en la competición.
# Sección 12: Miscelánea
- Artículo 23.- Flexibilidad del reglamento
Siempre y cuando se respeten el concepto y fundamentos de las reglas, estas deberán ser lo suficientemente flexibles para abarcar cambios en el número de jugadores y en el contenido de las partidas.

*Esta obra está bajo una licencia de Creative Commons Reconocimiento 4.0 Internacional.

*Reglamento derivado de Unified Sumo Robot Rules.
