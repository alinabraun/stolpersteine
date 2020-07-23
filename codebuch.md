FRAGE: Zusammenhänge zwischen Familien oder zwischen den Straßen darstellen?

Sandhu Feedback: 
-> Familie aussuchen und Wohnort und dann anhand dessen wo sind die hergekommen, was haben sie gemacht und wo sind sie hingekommen?
-> Für Jede Familie ein NW erstellen
-> Familiennetzwerke, exemplarisch zeigen wie das Regime vorgegangen ist
-> geographisches NW 
-> 1. Grad an Verwandtschaft (Eltern, Geschwister)
-> Beruf, Wohnort, enteignet, wo sind sie hindeportiert worden, Eheleute getrennt?
-> NW einer Deportation

https://github.com/hdm-crpr/226305/tree/master/data/wohlleben

- für Pretest: Eine Familie aussuchen 

NW am Ende:
- Jeder eine Familie 
- 5 Familien aus Stuttgart
- NW aufteilen nach verschiedenen Zeitepisoden
- Für jede Famile eigenes R und Edge und Nodelist 

Vertex: Name, Alter, Religion, Geschelcht, Wohnort, Nationalität, Beruf, höchster Bildungsgrad, Todesort, Geburtsort, 


Codebuch 

Fragestellung: Deportationen im Raum Stuttgart aanhand von Stolpersteinen (Wer wurde aus welcher Straße (von wo) wann wohin gebracht?)

Edge-Attributes
= steht für Deportation, ist gerichtet

time (Wann wurden die Personen deportiert?)
- 1: 1940
- 2: 1941
- 3: 1942
- 4: 1943
- 5: 1944
- 6: 1945

relation
- 1: Familie
- 2: Arbeit
- 3: Wohnort
- 4: Verfolgung
- 5: Freundschaft

time (Beginn der Beziehung)
- 

duration (Dauer einer Beziehung)
- 1: 0-1 Jahr
- 2: 1-3 Jahre
- 3: 3-5 Jahre
- 4: 5-7 Jahre
- 5: 7-10 Jahre
- 6: über 10 Jahre


Vertex-Attribute

type (da es ein Two-mode Netzwerk ist):
- 1: Person
- 2: Ort

sex
- 1: männlich
- 2: weiblich

Alter (Wann Person deportiert wurde)
- 1: 0 bis 10
- 2: 10 bis 20 
- 3: 20 bis 30
- 4: 30 bis 40
- 5: 40 bis 50
- 6: 50 bis 60
- 7: 60 bis 70

religion 
- 1: Judentum
- 2: Christentum (evangelisch)
- 3: Christentum (katholisch)
- 4: keine Religion
- 5: Islam
- 6: 

region
- 1: Stuttgart Mitte
- 2: Stuttgart Ost
- 3: Stuttgart West
- 4: Stuttgart Süd
- 5: Stuttgart Nord
- 6: Stuttgart Feuerbach
- 7: Stuttgart Vaihingen
- 8: Stuttgart Zuffenhausen
- 9: Stuttgart Stammheim
- 10: Stuttgart Bad Canstatt
- 11: Stuttgart Münster
- 12: Stuttgart Obertürkheim
- 13: Stuttgart Hedelfingen
- 14: Stuttgart Botnang
- 15: Stuttgart Degerloch
- 16: Stuttgart Sillenbuch
- 17: Stuttgart Möhringen
- 18: Stuttgart Mühlhausen
- 19: Stuttgart Plieningen
- 20: Stuttgart Weilimdorf
- 21: Stuttgart Neuwirtshaus 
- 22: Stuttgart Untertürkheim
- 23: Stuttgart Wangen
- 24: Stuttgart Kaltental

organisation
- 1: Arbeitsplatz
- 2: KZ
- 3: Straße
- 4: 
- 5: 
- 6: 
