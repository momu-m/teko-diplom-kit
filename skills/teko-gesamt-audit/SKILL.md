---
name: teko-gesamt-audit
description: Ablauf für eine Gesamtprüfung des ganzen Berichts vor der Abgabe, mit Rollen, jedem Befund am Original geprüft, Verworfen-Liste, Gutachten und Abhakliste A/B/C. Auslöser: "Gesamt-Audit", "ganzen Bericht prüfen", "vor der Abgabe prüfen", "Gutachten schreiben".
---

# teko-gesamt-audit — der ganze Bericht in einem Durchgang

> In einem Durchgang prüfst du den ganzen Bericht gegen Raster, Anleitung und die 20 Punkte, ohne dass falsche Befunde einer KI in deinem Bericht landen. Grundlage: TEKO, Anleitung Technischer Bericht (Stand Jan. 2026); TEKO, Bewertungsraster Diplomarbeit (Stand 2026).

## Wann benutzen

Ein bis zwei Wochen vor der Abgabe, wenn der Bericht vollständig ist, aber noch Zeit bleibt, eine Liste abzuarbeiten. Später nach grossen Änderungen noch einmal.

## Was du brauchst

- Den ganzen Bericht als PDF in der Fassung, die du abgeben würdest.
- Das Raster und die Anleitung deiner Schule.
- Die Skills `teko-experte` und `teko-6er-check` (oder deren Kopiervorlagen).
- Einen Ordner für Briefe und Ausgaben, zum Beispiel `audit/briefe/` und `audit/ausgaben/`.
- Die Vorlagen `vorlagen/BRIEF_AN_PRUEFER.md`, `vorlagen/GUTACHTEN_VORLAGE.md` und `vorlagen/ABHAKLISTE.md`.

Wichtig: Die Prüfer lesen nur. Während des Audits änderst du am Bericht und an den Daten nichts. Prüferantworten sind Hypothesen, bis jemand sie am Original bestätigt hat.

## Ablauf

1. **Vorbereitung.** Raster, Anleitung, deine Entscheide und den 6er-Check lesen. Stand festhalten: Version, Datum und Uhrzeit, Seitenzahl. Ordner anlegen.
2. **Rollen verteilen** (siehe unten) und für jede Rolle einen Brief schreiben.
3. **Prüfen.** Die Prüfer arbeiten nacheinander, wenn parallele Läufe Konflikte erzeugen (parallele Läufe können leer bleiben). Jede Antwort auf Inhalt prüfen: eine leere Antwort einmal wiederholen, dann einen Ersatzprüfer nehmen. Nach jedem Lauf nachsehen, ob ein Prüfer selbst Dateien geschrieben hat. Solche Nebenprodukte archivieren, nicht löschen.
4. **Jeder Befund am Original.** Der Chef prüft jeden Befund am Original (PDF-Seite bei Druckauflösung, die Quelle im Original, Quelltext, Messdatei), bevor er in eine Liste kommt. Ein Befund ohne Fundstelle und wörtliches Zitat gilt als nicht gefunden.
5. **Verworfen-Liste führen:** Befund | von wem | warum verworfen. Auch Befunde aus früheren Durchgängen gehören hinein.
6. **Widersprüche lösen.** Die Antwort von Prüfer A dem Prüfer B vorlegen («Widersprichst du?»). Dann entscheiden, mit Grund. Nicht die Mehrheit zählt, sondern das Zitat im Original.
7. **Zahlen nachrechnen.** Ein Rechner (zweite KI oder du) rechnet jede Zahl des Gutachtens aus den Rohzahlen nach. Abweichungen am Original klären.
8. **Abnahme.** Ein unabhängiger Prüfer liest das fertige Gutachten und urteilt über das Gutachten, nicht über den Bericht:
   ja / ja mit Korrektur / nein. Er prüft, ob jeder Befund belegt ist und ob der Stand der 20 Punkte zu den Befunden
   passt (kein Punkt «erfüllt», zu dem es einen offenen Befund gibt). Im Modus Solo macht das die KI selbst. Einwände schriftlich beantworten oder beheben.
9. **Gutachten schreiben** nach `vorlagen/GUTACHTEN_VORLAGE.md`, mit den Listen A, B und C und der Punkte-Schätzung. Danach beginnt Liste A ohne weitere Rückfrage.

### Rollen

Die Rollen heissen nach ihrer Aufgabe. Du bist nicht an bestimmte KI-Marken gebunden.

| Rolle | Aufgabe |
|---|---|
| Experte | Raster, Stolperstellen, die zwölf Fragemuster (Skill `teko-experte`) |
| Formprüfer | die 20 Punkte, Richtwerte zählen, Formales, Pflichtenliste mit Status (Skill `teko-6er-check`) |
| Quellenprüfer | Quellen im Original prüfen. Es zählen nur Zitate aus dem Dokument selbst. |
| Sprachprüfer | Satzlänge, Klang, Verständlichkeit. Nur Berichtstext, keine Zugangsdaten und keine vertraulichen Daten. |
| Rechner | jede Zahl nachrechnen: Summen, Prozent, Mittelwerte, Zeiträume |
| zweiter Experte | greift die Befunde an und bestätigt nicht. Am Ende die Abnahme. |
| Layoutprüfer | Layout und Bilder im PDF, Lesbarkeit gedruckt |

Weitere Rollen nach Bedarf: ein Konsistenzprüfer (stehen Kernzahlen an allen Stellen gleich?), ein Verweisprüfer (Querverweise, Glossar, Literaturverzeichnis), ein Skriptprüfer (Auswerteskripte und Zielkontrolle nachrechnen, nur lesend), ein Logikprüfer (roter Faden, nur mit Zitatpflicht, sonst verwerfen). Dienste mit unsicherem Datenschutz bekommen keine vertraulichen Daten.

### Prüfliste je Rolle

Eine Rolle ohne eigene Liste übersieht Formfehler. Darum bekommt jede Rolle ihre Liste
(im Modus Solo arbeitet die eine KI alle Listen nacheinander ab):

```
PRÜFLISTE JE ROLLE (jede Rolle arbeitet ihre Liste ganz ab und meldet auch «geprüft, ohne Befund»):
- Formprüfer: Abstract (Wörter zählen, nicht schätzen, Zählweise nennen; enthält Frage, Weg, Ergebnis mit Kernzahl,
  Grenze, nächsten Schritt); Legende einer Tabelle steht über der Tabelle, Legende einer Abbildung unter der Abbildung,
  jede Tabelle und Abbildung ist nummeriert und im Text erwähnt; Gliederung höchstens dreistufig (1.1.1); die Zielstufen
  sind genau die der Themeneingabe (meist zwei: Muss und Kann), eine zusätzliche Stufe im Bericht ist ein Befund; jedes
  Ziel hat Zahl und Termin; Verzeichnisse vorhanden (Inhalt, Abbildungen, Tabellen, Literatur, Hilfsmittel); Liste der
  Hilfsmittel mit KI-Deklaration vorhanden.
- Quellenprüfer: jede fremde Zahl (Herstellerangabe wie eine Genauigkeit, Norm- oder Grenzwert, Literaturwert, Preis)
  hat eine Quelle, jede eigene Messzahl ein Protokoll, jede eigene Festlegung (Sollwert, Schaltpunkt) eine Begründung,
  sonst ist sie ein Befund; Primärquelle vor Sekundärquelle (Datenblatt, Norm, Hersteller statt Lexikon oder
  Blog); eine KI steht nie im Literaturverzeichnis, ihre Nutzung gehört in die KI-Deklaration; Verweis im Text und
  Eintrag im Verzeichnis passen zusammen.
- Sprachprüfer: Floskeln und Werbewörter sind Sprachbefunde, egal wer sie geschrieben hat; ob eine KI schrieb, ist
  nicht die Frage (Beispiele: «es ist wichtig zu beachten», «nahtlos», «robust», «zukunftssicher», «innovativ»,
  «zusammenfassend lässt sich sagen»); Behauptung ohne Nachweis («funktioniert», «eignet sich am besten»); Sätze über
  30 Wörter; Fachwort ohne Erklärung.
- Experte: Variantenentscheid mit Kriterien, Gewichtung und Begründung je Zelle; Kriterien und Grenzen vor der Prüfung
  festgelegt (nachträglich geändert ist ein Befund); Tabelle nie grüner als der Text, Fazit gleich Tabelle; jede
  Kennzahl im Fazit hergeleitet; Prüfung wiederholbar beschrieben (Aufbau, Ablauf, Protokoll).
- Rechner: jede Summe, jeden Prozentwert und jede Abweichung nachrechnen und den Rechenweg zeigen.
```

### Brief-Bausteine

Jeder Brief enthält:

- Auftrag in einem Satz und die Rolle des Prüfers: angreifen, nicht bestätigen.
- Fakten: Version, Datei, Kapitelbereich und die Quelle dieser Fakten.
- **Schreibverbot** für den Prüfer: nichts ändern, höchstens die Ausgabedatei schreiben.
- **Zitatpflicht:** jeder Befund mit Fundstelle und wörtlichem Zitat.
- Format: `Befund | Fundstelle | Zitat | Schwere`
- Bekannte Falschbefunde, die nicht wiederholt werden sollen.
- «Unsicheres mit [Unbestätigt] markieren, nichts erfinden.»
- Ein prüfbares Fertig-Kriterium (zum Beispiel «mindestens zehn Stellen geprüft, am Ende die Zeile ‹Selbstprüfung: jedes Zitat steht im Text ja/nein›»).

## Ergebnis

Das Gutachten folgt `vorlagen/GUTACHTEN_VORLAGE.md`:

| Abschnitt | Inhalt |
|---|---|
| 0 In fünf Sätzen | Stand der 20 Punkte (erfüllt, teilweise, offen), grösste Schwäche, danach folgende Schwächen, grösstes Risiko, Zahl verworfener Befunde |
| 1 Wer hat geprüft | Prüfer, Aufgabe, Ergebnis, Datei |
| 2 Was kostet welche Schwäche | Schwäche, Rasterkriterium mit Höchstpunkten, möglicher Abzug als Schätzung, gefunden von, wann beheben |
| 3 Liste A | sofort selbst erledigen, ohne weitere Daten |
| 4 Liste B | nach den letzten Ergebnissen |
| 5 Verworfen | Befund, von wem, warum verworfen |
| 6 Widersprüche | A gegen B, Entscheid, Grund |
| 7 Stand 6er-Check | Zählung mit Vorbehalten und Richtwerten |
| 8 Zahlen-Prüfung | Grösse, Nachrechnung, Urteil |
| 8b Weitere Ergebnisse | zum Beispiel: Verweise lückenlos, Quelle fehlt im Verzeichnis, Abkürzung fehlt im Glossar, zu lange Sätze |
| 8c Abnahme | ja / ja mit Korrektur / nein, eingearbeitete Einwände |
| 9 Liste C | nur, was du oder dein Betreuer entscheiden muss (Geld, Termin, Freigabe, Unterschrift) |
| Notenspanne | Berichtpunkte von 140, drei Annahmen für die übrigen 40, Note je Annahme mit Rechenweg (Regel im Skill `teko-bericht-regeln`, «So wird aus Punkten die Note») |
| Punkte-Schätzung | je Rasterbereich, mit Hinweis «nicht aus dem Bericht prüfbar» bei Präsentation, Weekly Report, Terminen und Onlinepublikation |

Die Abhakliste folgt `vorlagen/ABHAKLISTE.md`, geordnet nach Rasterpunkten je Stunde, nicht nach der Reihenfolge der Funde. Eine abgehakte Zeile nennt Datum und Stelle der Änderung. Nach jeder Änderung: neu bauen, Zahlen nachrechnen lassen, Abnahme, erst dann abhaken.

## Modus Solo, Duo, Team

### Solo (eine KI)
Die KI spielt die Rollen nacheinander (Experte, Formprüfer, Quellenprüfer, Rechner, Gegenprüfer) und belegt jeden eigenen Befund mit wörtlichem Zitat und Fundstelle (Seite oder Kapitel). Danach greift sie ihre eigenen Befunde in einem zweiten Durchgang an («Stimmt das wirklich? Steht es so im Text?») und schreibt die Verworfen-Liste. Du bist der Chef: Du prüfst jeden Befund am Original. Bleibt die Liste «verworfen» leer, prüfe ein zweites Mal besonders streng: Eine leere Liste ist ein Warnzeichen.

### Duo (zwei KIs)
KI 1 prüft alle Rollen und liefert die Befunde. KI 2 bekommt den Text und die Befunde von KI 1 und greift sie an: «Widersprichst du? Welcher Befund ist falsch?» Der Satz steht im Brief-Teil «Gegenprüfung». KI 2 rechnet auch die Zahlen nach. Du entscheidest am Original.

### Team (mehrere KIs)
Die Rollen werden auf mehrere KIs verteilt. Alle prüfen unabhängig, keine KI sieht vorher die Antwort der anderen. Ein Chef (du oder eine KI) gleicht ab, macht Widersprüche sichtbar, prüft jeden Befund am Original und schreibt das Gutachten. Ein zweiter Experte macht am Ende die Abnahme.

## Regeln, die immer gelten

- Eine beste Lösung je Punkt, keine Variantenfragen an dich. Fragen an dich nur, wenn niemand sonst entscheiden kann.
- Schreibe «Nachweis» oder «Quelle», wenn du etwas belegst.
- Sichere die Prüferantworten dauerhaft, nicht nur in einem temporären Ordner.
- Typische Falschbefunde, auf die du vorbereitet sein solltest: «Zitat falsch», obwohl es im Original steht. «Bild unlesbar», obwohl es gedruckt lesbar ist. «Kopfzeile fehlt» auf einer Seite, die mit einer wiederholten Kopfzeile beginnt. Erfundene Leitfragen. Daten, die nirgends stehen. Jeder Befund wird am Original geprüft.
- Richtwert Wörter je Seite: Liegt die Wortzahl je Seite über rund 320 (Faktor 2 gegenüber rund 160), ist das ein Befund.
- Typische Rechenfehler: falsche Summe; Prozent vom falschen Grundwert; mit gerundeten Zwischenwerten weitergerechnet; Einheiten vermischt; eine Zahl aus einer älteren Fassung stehen geblieben; Zahl im Abstract ≠ Zahl im Ergebnisteil. Ein solcher Fehler macht jede Zahl unsicher, die darauf aufbaut; rechne sie alle nach. Er wiegt schwerer als Layout.
- Neue allgemeine Falschbefunde als Lehre festhalten.
- Das Gutachten ist eine Schätzung; die Notenspanne ist eine Orientierung, keine Note. Unsicheres mit [Unbestätigt] markieren.
- Während des Audits ändert niemand den Bericht.

## So benutzt du es ohne Claude Code

Kopiere den Inhalt von `prompts/teko-gesamt-audit.md` zwischen `--- ANFANG ---` und `--- ENDE ---` in den Chat und hänge den Bericht an. Für Duo und Team schreibst du die Briefe nach `vorlagen/BRIEF_AN_PRUEFER.md`. Das Gutachten schreibst du in `vorlagen/GUTACHTEN_VORLAGE.md`.

## Quellen

- TEKO, Anleitung Technischer Bericht (Stand Jan. 2026).
- TEKO, Bewertungsraster Diplomarbeit (Stand 2026).
