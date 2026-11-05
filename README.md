# Die Zeitarbeitssoftware – Online-Demo

[Demo in Safari oder einem anderen Browser öffnen](https://muhammet-kose.github.io/HR4ME-demo/)

Dieses Repository enthält ausschließlich die fertigen Dateien der Frontend-Demo.
Der Quellcode wird im privaten Repository HR4ME-multi gepflegt.

- Anmeldung: Büro → Administrator.
- Fiktive Ausgangsdaten; Eingaben und Uploads bleiben im jeweiligen Browser.
- Keine Verbindung zu Staging oder Produktion.
- Der LODAS-Download ist eine Muster-CSV.
- Der veröffentlichte Quellcode-Stand steht in demo-build.json.

GitHub Pages veröffentlicht den main-Branch. Die Seiten funktionieren auch über Direktlinks.

## Überarbeitete Bereiche einzeln öffnen

Diese Linkliste in Safari öffnen; die folgenden Seiten bleiben dann in Safari.

1. [Dashboard](https://muhammet-kose.github.io/HR4ME-demo/)
2. [Arbeitszeitkonto – AZK](https://muhammet-kose.github.io/HR4ME-demo/azk)
3. [AZK und Lohnvorbereitung abschließen](https://muhammet-kose.github.io/HR4ME-demo/azk#azk-closing-title)
4. [PDF hochladen und Stundennachweise](https://muhammet-kose.github.io/HR4ME-demo/monatsabrechnung/gutschriften)
5. [Stunden prüfen](https://muhammet-kose.github.io/HR4ME-demo/monatsabrechnung/pruefung)
6. [Monatsstunden](https://muhammet-kose.github.io/HR4ME-demo/monatsabrechnung/monatswerte)
7. [Rechnungen – Rechnung mit „Prüfen“ öffnen](https://muhammet-kose.github.io/HR4ME-demo/abrechnung)
8. [Rechnung aus Wochenstunden erstellen](https://muhammet-kose.github.io/HR4ME-demo/abrechnung/neu)
9. [Offene Zahlungen](https://muhammet-kose.github.io/HR4ME-demo/abrechnung?view=statuses)
10. [Einsatz anlegen – ab Einsatzbeginn](https://muhammet-kose.github.io/HR4ME-demo/einsaetze/neu)
11. [Einsatzgruppe anlegen](https://muhammet-kose.github.io/HR4ME-demo/einsaetze/teams/neu)
12. [Mitarbeiter – Stammdaten bearbeiten](https://muhammet-kose.github.io/HR4ME-demo/mitarbeitende/employee-1/bearbeiten)
13. [Mitarbeiter – Personalnummern](https://muhammet-kose.github.io/HR4ME-demo/mitarbeitende/employee-1/personalnummern)
14. [Mitarbeiter anlegen](https://muhammet-kose.github.io/HR4ME-demo/mitarbeitende/neu)
15. [Firma anlegen](https://muhammet-kose.github.io/HR4ME-demo/unternehmen/neu)
16. [Konditionen](https://muhammet-kose.github.io/HR4ME-demo/konditionen)
17. [Auftragsmappe anlegen](https://muhammet-kose.github.io/HR4ME-demo/auftragsmappen/neu)
18. [Dokumente](https://muhammet-kose.github.io/HR4ME-demo/dokumente)
19. [Vorlagen und Schreiben](https://muhammet-kose.github.io/HR4ME-demo/dokumentvorlagen)

20. [Manuelle Rechnung erstellen](https://muhammet-kose.github.io/HR4ME-demo/abrechnung/neu?art=manuell)

Manuelle Demo-Rechnungen benötigen keinen abgeschlossenen Monat. Kunde, Einsatz, Monat, Rechnungsgrund und Leistungspositionen werden direkt erfasst; danach kann die Muster-PDF heruntergeladen werden.

„Stundennachweise“ bezeichnet die PDFs mit Einzelzeiten; „Monatsstunden“ die zusammengefassten Stunden eines Monats.

21. [Wochen abrechnen](https://muhammet-kose.github.io/HR4ME-demo/monatsabrechnung/wochen?month=2026-10)

## Wöchentlich abrechnen, monatlich AZK festlegen

Stundennachweis hochladen → Stunden prüfen und übernehmen → Kalenderwoche abschließen → Wochenrechnung erstellen. Die Wochenübersicht zeigt je Kunde und Einsatz, welche Woche noch offen ist und ob ihre Rechnung bereits erstellt wurde.

Der Monatsabschluss bleibt davon getrennt: Tagesstunden des Monats sammeln → Monat abschließen → AZK je Mitarbeiter aufteilen → Muster-LODAS exportieren. Wochen über zwei Monate werden anhand der tatsächlichen Arbeitstage aufgeteilt. Die AZK-Aufteilung ändert die Kundenrechnung nicht.

Die Wochenrechnung und ihr PDF sind Demo-Belege. Es erfolgt kein Versand.

[Vorschüsse öffnen](https://muhammet-kose.github.io/HR4ME-demo/zahlungen/) · [Vorschuss anlegen](https://muhammet-kose.github.io/HR4ME-demo/zahlungen/neu/)

„Vorschuss anlegen“ öffnet eine eigene Seite mit dem Formular. Nach erfolgreichem Speichern erscheint die Bestätigung in der Vorschussliste.
