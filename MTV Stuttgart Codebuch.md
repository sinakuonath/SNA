CODEBUCH,

edgelist,Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from,"definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort"
to ,"definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. "
club,definiert den vorherigen Verein der Spielerin
country,"definiert das Heimatland der Spielerin (0 = Deutschland, 1 = Niederlande, 2 = Belgien, 3 = Polen, 4 = USA, 5 = Spanien, 6 = Finnland)"
,
nodelist,Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id,"eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.  "
name,vollständiger Name oder Bezeichnung des Knotens. 
type,"relevant bei two-mode Netzwerken, um die Unterscheidung zwischen z.B. Spielerin und Organisation zu berechnen (0 = Person, 1 = Organisation wie Verein oder Land)"
birth,"definiert das Geburtsjahr der Spielerin (0 = 1990-1995, 1 = 1996-2000, 3 = 2001 - 2005)"
age,"definiert das Alter der Spielerin (0 = unter 20, 1 = 20-23, 2 = 24-26, 3 = 27-30)"
position,"definiert die Spielposition der Spielerin (0 = Mittelblock, 1 = Zuspiel, 2=Außenangriff, 3 = Diagonal, 4 = Libera)"
country,"definiert das Heimatland der Spielerin (0 = Deutschland, 1 = Niederlande, 2 = Belgien, 3 = Polen, 4 = USA, 5 = Spanien, 6 = Finnland)"
,
NA,"definiert fehlende Werte, bei der Datenerhebung das Feld einfach weglassen."
