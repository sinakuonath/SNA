#Codebuch MTV Stuttgart
Im Codebuch ist definiert, wie und nach welchen Kriterien erfasst wird.

#Inhalt
  + Eges.csv (Edgelist)
  + Nodes.csv (Nodelist)
  
#Edge-Attribute
**from**
Definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist.

**to**
Definiert den Empfänger in ungerichteten Netzwerken. Enspricht ID in der Nodelist.

#Node-Attribute
**id**
Eindeutige Identifikation jedes einzelnen Knotens, der erfasst wird.

**name**
vollständiger Name oder Bezeichnung des Knotens.

**type**
Relevant bei Two-Mode-Netzwerken, um die Unterscheidung zwischen Spielerin und Vereinen zu berechnen.
0 = Person
1 = Verein

**birth**
Definiert das Geburtsjahr der Spielerin
0 = 1990-1995
1 = 1996-2000
2 = 2001-2005

**age**
Definiert das Alter der Spielerin
0 = unter 20
1 = 20-23
2 = 24-26
3 = 27-30

**position**
Definiert die Spielposition der Spielerin
0 = Mittelblock
1 = Zuspiel
2 = Außenangriff
3 = Diagonal
4 = Libera

**country**
Definiert das Heimatland der Spielerin 
0 = Deutschland
1 = Niederlande
2 = Belgien
3 = Polen
4 = USA
5 = Spanien
6 = Finnland
7 = Bulgarien

**NA**
Definiert fehlende Werte, Feld wird bei der Datenerhebung einfach weggelassen.

