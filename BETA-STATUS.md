# Teststand und Grenzen

Stand: 12. Oktober 2026. Experimentell; unabhängige Überprüfung erforderlich.

## Vorhandene technische Nachweise

| Prüfung | Beobachtung | Aussagegrenze |
| --- | --- | --- |
| Lokale Referenz mit 26 Fällen | Korrigiert: 22 bestanden, 4 unklar. Absichtlich fehlerhaft: 17 bestanden, 5 Verstöße, 4 unklar. | Die Fehler wurden in einer selbst entwickelten Referenz gezielt eingebaut. |
| Separater Wirkungsnachweis | Ein Export lässt sich trotz gemeldeter Ablehnung anhand der erzeugten Datei nachweisen. | Nur an die angeschlossenen Beobachtungsquellen gebunden. |
| Verzögerte Aktionen | Lokaler Hintergrundprozess und explizite Abschlussmeldung geprüft; fehlender Abschluss bleibt unklar. | Kein Beweis für beliebige externe Systeme oder unbegrenzt späte Aktionen. |
| Begrenzter Modellversuch | 16 Szenariodurchläufe: 15 bestanden, 1 wegen Modellaufruf-Fehler unklar. | Eigene Szenarien; keine unabhängige Angriffsstudie und keine belastbare Erfolgsquote. |

Die vier unklaren Referenzfälle erzeugen absichtlich Timeout, leere Antwort, Serverfehler oder unvollständige Belege. Sie werden nicht als bestanden gewertet.

## Was als Nächstes wirklich geprüft werden muss

- Eine fremde, autorisierte Testanwendung mit echten Geschäftsregeln.
- Angriffe von Personen, die die Implementierung und bisherigen Fälle nicht geschrieben haben.
- Weitere Modellläufe, Sprachen, Gespräche über mehrere Runden und manipulierte Dokumente.
- Unbekannte Werkzeuge und nachgelagerte Aktionen in anderen Systemen.
- Fehlalarme bei normalen Arbeitsabläufen.
- Einrichtungsaufwand, Verständlichkeit der Befunde und tatsächliche Zeitersparnis.

## Was die Online-Demo nicht leistet

Sie schützt keine produktive Anwendung, überwacht keine echten Mitarbeiter und ersetzt keine serverseitigen Berechtigungsprüfungen. Sie führt keine Modellaufrufe über ein Betreiberkonto aus. Eigene Dokumente und Kundendaten gehören nicht in die öffentliche Demo.

Der Vergleich fehlerhaft/korrigiert demonstriert das Prüfprinzip. Er bedeutet nicht, dass AI Guard Dog fremde Anwendungen automatisch repariert.

## Produktstatus

Technischer Referenznachweis vorhanden. Öffentlicher Hosting-Betrieb noch nicht freigeschaltet. Kundennutzen, unabhängige Bewertung und ein belastbarer Vorteil gegenüber vorhandenen Werkzeugen sind offen.
