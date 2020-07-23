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

Geschlecht (bei Organisation keine Angabe)
- 1: männlich
- 2: weiblich

type (da es ein Two-mode Netzwerk ist):
- 1: Haushalt
- 2: KZ

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

function (Funktion der Mitglieder innerhalb einer Gruppe):
- 1= Anführer
- 2= Mitglied
- 3= Verräter

organisation: (Organisationsgrad der Gruppen)
- 1= schwache Organisation (Mitglieder kommen nur zu einer Aktion zusammen, kein regelmäßiger Kontakt)
- 2= mittlere Organisation (Treffen ab und zu mit festen Mitgliedern, aber z.B. kein fester Anführer, nicht stark strukturiert)
- 3= gut organisiert (regelmäßige Treffen mit fester Hierarchie)
