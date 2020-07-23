Codebuch 

Fragestellung: Deportationen im Raum Stuttgart aanhand von Stolpersteinen (Wer wurde aus welcher Straße (von wo) wann wohin gebracht?)

Edge-Attributes

Gewicht: Häufigkeit der Unterstützung
-	einmalige Unterstützung: 1
-	öftere Unterstützung: 2
-	ständige Unterstützung: 3

relation: Wie hat man unterstützt?
-	1: Aktive Aufforderung
-	2: Mithilfe bei Aktion
-	3: Geldunterstützung

time: Wann fand die Unterstützung statt?
-	1: vor dem Weltkrieg
- 2: während des Weltkriegs
-	3: nach dem Weltkrieg

duration: Wie lang dauerte die Unterstützung?
-	1: unter einem Jahr
-	2: über ein Jahr
-	3: über drei Jahre

treason: Gab es einen Verrat einzelner Personen oder Gruppen?
- 0: nein
- 1: ja

Vertex-Attribute

type (da es ein Two-mode Netzwerk ist):
- 1: Person
- 2: KZ

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

size (Haushaltsgröße)
- 1: Ein-Personen-Haushalt
- 2: Zwei-Personen-Haushalt
- 3: Drei-Personen-Haushalt
- 4: Vier-Personen-Haushalt
- 5: Fünf-Personen-Haushalt
- 6: Sechs-Personen-Haushalt
- 7: Sieben-Personen-Haushalt
- 8: Acht-Personen-Haushalt

death (Im KZ gestorben)
- 1: Ja
- 2: Nein

Group (Zugehörigkeit zu Gruppe, die von nazis deportiert wurde)
- 1: Jude
- 2: Homosexuell
- 3: Behindert
- 4: Widerstandskämpfer
- 5: politischer Gegner
- 6: Sinti Roma

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

household (Zugehörigkeit):
- 1: Familie
- 2: Freundschaft

household name
-> Ersten drei Buchstaben einer Familie, wenn es sich doppelt mit I,II usw arbeiten

organisation
- 1: Arbeitslager
- 2: Vernichtungslager
- 3: Frauenlager
- 4: Durchgangslager
- 5: Zuchthaus
- 6: Erziehungslager
