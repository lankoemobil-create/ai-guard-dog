# AI Guard Dog

**Nachvollziehbar prüfen, was eine KI tatsächlich getan hat — und ob sie das durfte.**

> **Experimentelle Testversion. Unabhängige Tests erforderlich. Keine Freigabe für den produktiven Einsatz und kein Sicherheitszertifikat.**
>
> **Zugang:** Die öffentliche Online-Demo wird vorbereitet. Hier steht noch kein freigeschalteter Testlink. Sobald der Betrieb geprüft ist, wird er auf dieser Seite ergänzt.

## Worum geht es?

AI Guard Dog untersucht Aktionen von KI-Anwendungen: Passt die Aktion zur Rolle des Nutzers? Bleiben Daten innerhalb des erlaubten Mandanten? Liegt eine passende Freigabe vor? Und stimmen die Angaben der Anwendung mit separat beobachteten Auswirkungen überein?

Das erste Testlabor nutzt einen fiktiven Support-Assistenten. Der absichtlich fehlerhafte Modus und der korrigierte Modus zeigen, wie Befunde entstehen und wie ein Nachtest aussieht. Ein separater Beobachter prüft unter anderem, ob eine Exportdatei tatsächlich entstanden ist.

## Was du ausprobieren können wirst

- Einen absichtlich eingebauten Berechtigungsfehler finden.
- Eine Aktion erkennen, die trotz gemeldeter Ablehnung ausgeführt wurde.
- Den korrigierten Modus mit denselben Regeln vergleichen.
- Einzelne Befunde nachvollziehen und nachtesten.
- Einen Bericht mit synthetischen Testdaten herunterladen.

Die Online-Demo verwendet festgelegte Abläufe, **kein live aufgerufenes Sprachmodell**. Sie nimmt keine eigenen Dokumente, Zugangsschlüssel oder Zieladressen entgegen. Die Anbindung eigener Anwendungen ist noch nicht Teil dieser öffentlichen Testfreigabe.

## Was bisher belegt ist — und was offen bleibt

Es gibt lokale automatisierte Prüfungen und einen begrenzten Versuch mit einem echten Modell. Das belegt ausgewählte technische Abläufe. Es belegt **keine allgemeine Erkennungsquote**, keinen Schutz gegen unbekannte Angriffe und keinen bestätigten Nutzen im Alltag eines Unternehmens.

Details: [Teststand und Grenzen](BETA-STATUS.md).

## Rückmeldung geben

Über [Issues](https://github.com/lankoemobil-create/ai-guard-dog/issues) kannst du Verständnisprobleme, Fehler und konkrete Einsatzwünsche melden. Bitte beschreibe erwartetes und beobachtetes Verhalten mit einem kleinen synthetischen Beispiel. **Keine Passwörter, Schlüssel, personenbezogenen Daten oder vertraulichen Unternehmensinformationen veröffentlichen.**

Hilfreich ist besonders: Welche KI-Aktion musst du heute prüfen? Wie prüfst du sie bisher? Welcher Arbeitsschritt würde durch dieses Werkzeug kürzer oder zuverlässiger?

## Verfügbarkeit und Rechte

Dieses Repository enthält die öffentliche Projektbeschreibung und Feedbackvorlagen. Der Produktkern bleibt privat; es wird keine Open-Source-Lizenz für das Produkt erteilt. Die Online-Testphase kann pausiert oder beendet werden. Ein dauerhafter kostenloser Zugang oder ein späterer Funktionsumfang wird nicht zugesagt.

Bereits heruntergeladene Berichte und sichtbare Seiteninhalte lassen sich nicht zurückrufen. Sie ermöglichen keinen eigenständigen Betrieb des serverseitigen Prüfkerns.

[Hinweise zu Rechten](RIGHTS.md) · [Beitrag leisten](CONTRIBUTING.md)
