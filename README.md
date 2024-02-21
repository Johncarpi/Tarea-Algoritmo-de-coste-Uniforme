# Tarea-Algoritmo-de-coste-Uniforme
Tarea Algoritmo de coste Uniforme
![Diagram Coste](https://github.com/Johncarpi/Tarea-Algoritmo-de-coste-Uniforme/assets/150828183/e76b6694-2113-4f80-8112-4ebaa35d7781)

![1708506981672](https://github.com/Johncarpi/Tarea-Algoritmo-de-coste-Uniforme/assets/150828183/8e5326fe-9a96-4d3b-b651-1c8b3084d7a4)


Leyenda: A = Nodo Abierto | C = Nodo Cerrado
1º Iteración:
Partimos desde A coruña y nos dirigimos a ponferrada ya que tiene el menor coste.
C{Ourense,Ponferrada}  A{Benavente,León}

2º Iteración:
Según el algoritmo ahora expandiremos a Benavente.
C{Ourense,Ponferrada,Benavente}  A{León,Valladolid,Palencia}

3º Iteración:
Ahora expandiremos a León.
C{Ourense,Ponferrada,Benavente,León}  A{Valladolid,Palencia,Osorno}

5º Ineración:
Ahora expandiremos a Vallalodid
C{Ourense,Ponferrada,Benavente,León,Vallalodid}  A{Palencia,Osorno,Aranda}

6º Ineración:
Ahora expandiremos a Palencia
C{Ourense,Ponferrada,Benavente,León,Vallalodid,Palencia}  A{Osorno,Aranda,Burgos,Osorno}

7º Ineración:
Como al expandir palencia se descubre que se puede ir a Osorno con un coste menor al que ya habíamos mirado por 
lo que se descarta ese camino.
C{Ourense,Ponferrada,Benavente,León,Vallalodid,Palencia,Osorno}  A{Aranda,Burgos}

8º Ineración:
Ahora expandiremos a Burgos.
C{Ourense,Ponferrada,Benavente,León,Vallalodid,Palencia,Osorno,Burgos}  A{Logroño,Soria,Aranda}

9º Ineración:
Ahora expandiremos a Aranda.
C{Ourense,Ponferrada,Benavente,León,Vallalodid,Palencia,Osorno,Burgos,Aranda}  A{Logroño,Soria,Osma}

10º Ineración:
Ahora exoadiremos a Osma.
C{Ourense,Ponferrada,Benavente,León,Vallalodid,Palencia,Osorno,Burgos,Aranda,Osma}  A{Logroño,Soria,Calatayud}

11º Ineración:
Ahora expandiremos a Soria.
C{Ourense,Ponferrada,Benavente,León,Vallalodid,Palencia,Osorno,Burgos,Aranda,Osma,Soria}  A{Logroño,Calatayud}

12º Ineración:
Al expandir Logroño vemos que volvemos a Soria con un costo mayor, por lo cual descartamos este nodo.

-Caminos:

1- Ourense,Benavente,Valladolid,Aranda,Osma,Calatayud: Total 641 Km

2- Ourense,Benavente,Valladolid,Aranda,Osma,Soria,Calatayud: Total 650 Km

