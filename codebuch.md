Sandhu Feedback: 
-> Familie aussuchen und Wohnort und dann anhand dessen wo sind die hergekommen, was haben sie gemacht und wo sind sie hingekommen?
-> Für Jede Familie ein NW erstellen
-> Familiennetzwerke, exemplarisch zeigen wie das Regime vorgegangen ist
-> geographisches NW 
-> 1. Grad an Verwandtschaft (Eltern, Geschwister)
-> Beruf, Wohnort, enteignet, wo sind sie hindeportiert worden, Eheleute getrennt?
-> NW einer Deportation

https://github.com/hdm-crpr/226305/tree/master/data/wohlleben

https://www.wikiwand.com/de/Liste_der_Stolpersteine_in_Stuttgart


- für Pretest: Eine Familie aussuchen 

NW am Ende:
- Jeder eine Familie 
- 5 Familien aus Stuttgart
- NW aufteilen nach verschiedenen Zeitepisoden
- Für jede Famile eigenes R und Edge und Nodelist 


Codebuch 

Fragestellung: Deportationen im Raum Stuttgart aanhand von Stolpersteinen (Wer wurde aus welcher Straße (von wo) wann wohin gebracht?)

Edge-Attributes
= steht für Deportation, ist gerichtet

relation
- 1: Familie
- 2: Arbeit
- 3: Wohnort
- 4: Verfolgung
- 5: Freundschaft
- 6: Liebensbeziehung
- 7: Wittwe/r 
- 8: Geschieden

time (beschreibt Startzeitpunkt der Beziehung)
- Jahreszahl wird direkt in Edgelist geschrieben


duration (Dauer einer Beziehung)
- 1: 0-1 Jahr
- 2: 2-5 Jahre
- 3: 6-10 Jahre
- 4: 11-15 Jahre
- 5: 16-20 Jahre
- 6: über 20 Jahre
- 7: von Geburt bis Tod


Vertex-Attribute

type (da es ein Two-mode Netzwerk ist):
- 1: Person
- 2: Ort

sex
- 1: männlich
- 2: weiblich

family function (in der Familie)
- 1: Vater
- 2: Mutter
- 3: Sohn
- 4: Tochter
- 5: Oma
- 6: Opa
- 7: Onkel
- 8: Tante
- 9: Cousin/Cousine
- 10: Kind aus anderer Ehe
- 11: Ehepartner aus anderer Ehe
- 12: Angeheiratet
- 13: Enkel
- 14: Schwester
- 15: Bruder
- 16: Schwager /Schwägerin

Alter 
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

organisation
- 1: Arbeitsplatz
- 2: KZ
- 3: Wohnort
- 4: Widerstand
- 5: Gefängnis
- 6: Gericht
- 7: Internierungslager

nationality 
- 1: Deutschland
- 2: Ost-Europa (Polen, Tschechien, Slovenien, Ungarn, Bulgarien etc.)
- 3: Süd-Europa (Spanien, Italien, Frankreich etc.)
- 4: Russland
- 5: Großbritanien
- 6: Türkei
- 7: Australien

education (Höchster Bildungsabschluss)
- 1: Studium
- 2: Abitur
- 3: Realschule
- 4: Hauptschule
- 5: Ausbildung/Lehre
- 6: Keine Ausbildung

Origin (Geburtsort)
- 1: Polen
- 2: Stuttgart
- 3: Michelbach
- 4: Russland
- 5: Linz am Rhein
- 6: Lübeck
- 7: Sydney
- 8: Crailsheim

death (Todesort)
- 1: lebt noch
- 2: Tarnow
- 3: Auschwitz
- 4: 1. WK
- 5: Treblinka
- 6: Stuttgart
- 7: Bikernieki
- 8: Ausschwitz

profession (Beruf)
- 1: Kaufmann/Kauffrau
- 2: Tabakschneider
- 3: Amtsangestellte/r
- 4: SchneiderIn
- 5: VerkäuferIn
- 6: Händler, Buchhalter
- 7: Prüfer

year birth 
-> In Nodelist wird Jahreszahl individuell eingetragen

year death
-> In Nodelist wird Jahreszahl individuell eingetragen
