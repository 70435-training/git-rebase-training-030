Training: Git-Rebase-030 (fortgeschritten)
======================================

Dies ein weiteres Training zu Git-Rebase.
Es dient dazu, dass Du erweiterte Erfahrungen im Umgang mit
Git-Rebase sammelst.

Bitte führe dieses Training erst durch, wenn die "Git-Rebase (grundlegend)" durchgeführt hast!

Zeitaufwand: Max 30 Minuten

Das Training ist intern und extern verfügbar.
Die externe URL ist: [github:git-rebase-training-030](https://github.com/70435-training/git-rebase-training-030).

Voraussetzungen
---------------

Seitens der "Infrastruktur" gibt es diese Voraussetzungen:

* Git-Kommandozeilen-Tools sind installiert [(Hilfe)](cheat-sheet/0810.md)
* Gitg ist installiert [(Hilfe)](cheat-sheet/0900.md)
* Fork von diesem Repo ist angelegt, Arbeit erfolgt nur an
  diesem Fork
* Du hast einen lokalen Clone vom Fork [(Hilfe)](cheat-sheet/0900.md)
* Dein Arbeitsverzeichnis ist im lokalen Clone

Seitens der Kenntnisse:

* Erfahrung mit der Kommandozeile
* Erfahrung mit Git (clone, branch, pull/push, commit, ...)
* [Training: Git-Rebase (grundlegend)](https://github.com/70435-training/git-rebase-training-basic) ist durchgeführt

Ausgangsituation
----------------

![Ausgangssituation](images/start.png)

- Es gibt einen Master-Branch
- ... und auch den Branch "experiment"
- "experiment" wurde irgendwann in der Vergangenheit erzeugt,
  er zweigt in der Vergangenheit vom Master-Branch ab
- Die Ausgangssituation kannst Du visualisieren mit `gitg origin/master origin/experiment`

Zielbild
--------

![Zielsituation](images/final.png)

- Es gibt einen Master-Branch
- ... und auch den Branch "experiment"
- Der Abzweigezeitpunkt von "expriment" ist verschoben
  auf einen definierten Punkt im aktuellen Master-Branch

Ablauf
------

### Vorbereitungen

- Stelle sicher, dass alle Änderungen am zentralen Repo bei Dir lokal verfügbar sind [(Hilfe)](cheat-sheet/1010.md)
- Visualisiere die Situation [(Hilfe)](cheat-sheet/1020.md)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen!
- Kontrolliere, ob "experiment" und "origin/experiment" übereinstimmen!

### Durchführung

- Branch "experiment" auschecken [(Hilfe)](cheat-sheet/1110.md)
- Branch "experiment" aktualisieren [(Hilfe)](cheat-sheet/1120.md)
- Neuen Abzweigepunkt identifizieren:
    - Abzweigung soll nach der letzten Änderung vom 27. Mai 2020 erfolgen,
      also bei "Links auf Einzelseiten"
    - Wir brauchen die Commit-ID von der Änderung!
    - [Hilfe](cheat-sheet/1125.md)
- Rebase durchführen [(Hilfe)](cheat-sheet/1131.md)
- Sichten [(Hilfe)](cheat-sheet/1140.md)
- Ergebnis "veröffentlichen" [(Hilfe)](cheat-sheet/1150.md)

Nachkontrolle
-------------

- Visualisiere die Situation [(Hilfe)](cheat-sheet/1210.md)
- Kontrolliere, ob "master" und "origin/master" übereinstimmen!
- Kontrolliere, ob "experiment" und "origin/experiment" übereinstimmen!
- Vergleiche Dein Bild strukturell mit [images/final.png](images/final.png)

Abschluß
--------

Nach Abschluß des Trainings bitte die URL zu dem bearbeiteten
Fork per Email schicken an "dp-training@daemons-point.com"!
