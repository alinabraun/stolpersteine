Codebuch 

ID's
- Edelweißpiraten = EWP
- Deutsche Jungenschaft Berlin = DJ
- Leipziger Meuten = LM
- Kommunistischer Jugendverband = KJ


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
-  2: während des Weltkriegs
-	3: nach dem Weltkrieg

duration: Wie lang dauerte die Unterstützung?
-	1: unter einem Jahr
-	2: über ein Jahr
-	3: über drei Jahre

treason: Gab es einen Verrat einzelner Personen oder Gruppen?
- 0: nein
- 1: ja

Vertex-Attribute

Name
- Edelweißpiraten
- Deutsche Jungenschaft Berlin
- Leipziger Meuten
- Kommunistischer Jugendverband

Geschlecht (bei Organisation keine Angabe)
- 1: männlich
- 2: weiblich

type (da es ein Two-mode Netzwerk ist):
- 1: Person
- 2: Widerstandsgruppe

Alter (Wann Person rekrutiert wurde)
- 1: unter 18
- 2: zwischen 18-21
- 3: 21-25
- 4: 25-30
- 5: über 30

size (nur bei Knoten mit type 2):
- 1: weniger als 50 Mitglieder
- 2: zwischen 50 und 100 Mitglieder
- 3: zwischen 100 und 500
- 4: mehr als 500

function (Funktion der Mitglieder innerhalb einer Gruppe):
- 1= Anführer
- 2= Mitglied
- 3= Verräter

organisation: (Organisationsgrad der Gruppen)
- 1= schwache Organisation (Mitglieder kommen nur zu einer Aktion zusammen, kein regelmäßiger Kontakt)
- 2= mittlere Organisation (Treffen ab und zu mit festen Mitgliedern, aber z.B. kein fester Anführer, nicht stark strukturiert)
- 3= gut organisiert (regelmäßige Treffen mit fester Hierarchie)
