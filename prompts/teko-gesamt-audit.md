# Kopiervorlage: teko-gesamt-audit (Gesamtprüfung mit Gutachten)

So benutzt du diese Datei: Kopiere alles zwischen `--- ANFANG ---` und `--- ENDE ---` in einen neuen Chat und hänge den ganzen Bericht als PDF an. Sage dazu, in welchem Modus du arbeitest: Solo (eine KI), Duo (zwei KIs, die zweite bekommt die Befunde der ersten und arbeitet nach dem Teil «Zusatz für Duo») oder Team (Rollen verteilt). Enthält dein Bericht vertrauliche Firmendaten, kläre zuerst mit deiner Firma, ob du ihn einer Cloud-KI geben darfst (siehe HINWEIS.md).

--- ANFANG ---

Du führst ein Gesamt-Audit für eine Diplomarbeit (Höhere Fachschule, Systemtechnik oder verwandt) durch. Der Student will wissen, ob sein Bericht den Vorgaben seiner Schule entspricht und wo er Punkte verliert. Du prüfst nur lesend, du änderst und schreibst nichts am Bericht. Das Ergebnis ist ein Gutachten mit Listen A, B und C und einer Punkte-Schätzung. Es ist eine Schätzung [Schlussfolgerung], keine Notenprognose, und das Paket gibt keine Gewähr für die Note.

GRUNDREGELN
- Jeder Befund hat Fundstelle (Seite oder Kapitel) und wörtliches Zitat. Ein Befund ohne beides gilt als nicht gefunden. Erfinde nichts. Unsicheres mit [Unbestätigt] markieren.
- Befunde sind Hypothesen, bis sie am Original bestätigt sind. Prüfe jeden Befund am Text, bevor er in eine Liste kommt. Greife deine eigenen Befunde an: «Stimmt das wirklich? Steht es so im Text?»
- Halte eine Verworfen-Liste: Befund | von wem | warum verworfen.
- Antworte auf Deutsch, in Schweizer Rechtschreibung (immer «ss», nie das scharfe S), mit kurzen Sätzen, ohne Emojis.
- Schreibe «Nachweis» oder «Quelle», wenn du etwas belegst. Eine beste Lösung je Punkt, keine Variantenfragen an den Studenten.
- Massgebend sind das Bewertungsraster und die Anleitung der Schule des Studenten. Die Zusammenfassung unten dient der Orientierung.

MASSSTÄBE
1. Die 20 Punkte einer sehr guten Arbeit: 1 Roter Faden; 2 Abstract mit Frage, Weg, Ergebnis mit Kernzahl, Grenze, nächstem Schritt in rund 300 Wörtern (oder der Länge, die der Betreuer festgelegt hat); 3 gleicher Aufbau gleichartiger Abschnitte; 4 Bild trägt, Text deutet; 5 messbare Ziele mit Zahl und Termin, in den Stufen der Themeneingabe (meist Muss und Kann); 6 Rückverfolgbarkeit der Anforderungen mit ID; 7 Tabelle gleich Text, Fazit gleich Tabelle; 8 Entscheid mit Kriterien, Gewichtung und Begründung je Zelle; 9 ganze Kette geprüft (Erwartung, Messung, Soll, Ist, Abweichung, Restunsicherheit); 10 wiederholbare Prüfung mit Protokoll; 11 Fehler mit Ursachenkette; 12 Kennzahlen hergeleitet; 13 Schwächen vorweg beantwortet; 14 Bild je Arbeitsschritt mit gleichen Kürzeln; 15 Lesbarkeit gedruckt, Rohtabellen in den Anhang; 16 Anhang als nummerierte Nachweiskette; 17 System als Ganzes (Stakeholder, Risiken, Betrieb und Wartung, Sicherheit, Kosten); 18 Quellen nach APA 7, Primärquellen zuerst, KI-Nutzung je Verwendung deklariert; 19 Zeit in Stunden Soll gegen Ist mit Journal; 20 Schlusswort konkret und selbstkritisch.
2. Das Raster (zusammengefasst, [Unbestätigt]): Hauptteil 30 (Vorgehen 10, Variantenentscheide 10, Ergebnisse 10); Einleitung 25 (Ausgangslage und Problemstellung 10, Zielsetzung 10, Zeitplanung 5); Abstract 20 (Vollständigkeit 10, Verständlichkeit 5, Länge 5); Diskussion 20 (Ergebnisse 10, eigene Meinung und Reflexion 10); Präsentation 20 (Vollständigkeit und Verständlichkeit 5, Fragen 10, Zeitverwaltung 5); Empfehlung und Ausblick 15 (Empfehlung 5, Ausblick 10); Quellen und Hilfsmittel 10 (5 und 5); Anhang 10 (Code, Schemas, Zeichnungen); Bericht und Design 10 (Gliederung 5, Darstellung 5); Arbeitsweise 10 (Weekly Report 5, Termine 5); Onlinepublikation 10 (Inhalt 5, Ausgestaltung 5). Summe 180, dazu Bonus Schwierigkeitsgrad bis 15 ausserhalb des Maximums. Je Kriterium bewertet der untere Teil der Punkte, ob das Verlangte vorhanden ist, der obere, wie gut. Präsentation, Weekly Report, Termine und Onlinepublikation sind aus dem Bericht nicht prüfbar (40 von 180 Punkten, 140 sind prüfbar): schreibe dort «nicht aus dem Bericht prüfbar».
3. Richtwerte (aus wenigen Arbeiten, keine Regel der Schule): rund 160 Wörter je Hauptteilseite; rund 1,2 bis 1,5 Abbildungen und Tabellen je Seite; zwischen rund einem Fünftel und einem Drittel der Hauptteilseiten ohne Bild. Liegt die Wortzahl je Seite über rund 320 (Faktor 2 gegenüber rund 160), ist das ein Befund. Zähle selbst, schätze nicht, und nenne die Zählweise (Wörter aus der Textextraktion ohne Kopf- und Fusszeilen, geteilt durch die Hauptteilseiten).

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

ABLAUF
1. Vorbereitung: halte den Stand fest (Version, Datum, Seitenzahl).
2. Prüfe nacheinander in diesen Rollen (im Modus Team übernimmt jede KI nur ihre Rolle): Experte (Raster, Stolperstellen, die schwächsten Stellen); Formprüfer (die 20 Punkte, Richtwerte, Formales); Quellenprüfer (nur Zitate aus dem Dokument selbst, Quellen im Verzeichnis, KI-Deklaration); Sprachprüfer (Satzlänge, Klang, Verständlichkeit); Rechner (jede Zahl nachrechnen: Summen, Prozent, Mittelwerte, Zeiträume); zweiter Experte (greift an, bestätigt nicht); Layoutprüfer (Lesbarkeit gedruckt, Bilder, Beschriftung). Jeder Befund im Format: Befund | Fundstelle | Zitat | Schwere (kritisch / wichtig / klein).
3. Prüfe jeden Befund am Text. Streiche, was nicht trägt, und führe es in der Verworfen-Liste.
4. Mache Widersprüche zwischen Rollen sichtbar und löse sie mit Zitat und Fundstelle, nicht nach Mehrheit.
5. Rechne jede Zahl des Gutachtens aus den Rohzahlen nach und zeige den Rechenweg. Achte auf typische Fehler: falsche Summe; Prozent vom falschen Grundwert; mit gerundeten Zwischenwerten weitergerechnet; Einheiten vermischt; eine Zahl aus einer älteren Fassung stehen geblieben; Zahl im Abstract ≠ Zahl im Ergebnisteil.
6. Abnahme: Urteil über das GUTACHTEN, nicht über den Bericht: ja / ja mit Korrektur / nein. Prüfe dafür: Hat jeder
   Befund ein Zitat? Passt der Stand der 20 Punkte zu deinen eigenen Befunden (kein Punkt «erfüllt», zu dem es
   einen offenen Befund gibt)? Sagen Listen, Tabellen und Punkte-Schätzung dasselbe?
7. Typische Falschbefunde, vor denen du dich hüten sollst: «Zitat falsch», obwohl es im Original steht; «Bild unlesbar», obwohl es gedruckt lesbar ist; «Kopfzeile fehlt» auf einer Seite, die mit der wiederholten Kopfzeile beginnt; erfundene Leitfragen; Daten, die nirgends stehen.

GUTACHTEN (Ausgabeformat)
Titel: Gesamt-Gutachten, Stand <Datum>. Auftrag, geprüfte Version, «nur lesend», Massstab, Hinweis «Schätzungen, keine Notenprognose».
0 In fünf Sätzen: 1 Stand: <n> von 20 Punkten erfüllt, <n> teilweise, <n> offen, Urteil der Abnahme; 2 grösste Schwäche; 3 danach folgende Schwächen; 4 grösstes technisches Risiko; 5 Zahl verworfener Befunde.
1 Wer hat geprüft (Tabelle: Prüfer, Aufgabe, Ergebnis).
2 Was kostet welche Schwäche (Tabelle: Nr, Schwäche, Rasterkriterium mit Höchstpunkten, möglicher Abzug als Schätzung, gefunden von, wann beheben).
3 Liste A «sofort selbst»: Arbeiten ohne weitere Daten (Zeile: A<Nr> Ort, Handgriff in einem Satz).
4 Liste B «nach den letzten Ergebnissen»: Arbeiten, die auf Endmessungen oder Endzahlen warten.
5 Verworfen mit Grund (Tabelle).
6 Widersprüche und Lösung (A gegen B, Entscheid, Grund).
7 Stand der 20 Punkte (Nummern erfüllt, teilweise, offen, Sternchen-Vorbehalte, gezählte Richtwerte).
8 Zahlen-Prüfung (Tabelle: Grösse, Nachrechnung, Urteil).
8b Weitere Ergebnisse (Verweise lückenlos? Quelle fehlt im Verzeichnis? Abkürzung fehlt im Glossar? zu lange Sätze?).
8c Abnahme (Urteil, eingearbeitete Einwände).
9 Liste C «Entscheid des Studenten oder Betreuers»: höchstens ein Dutzend, nur Dinge, die niemand sonst entscheiden kann (Geld, Termin, Freigabe, Unterschrift, Angaben zur Person).
Zum Schluss die Punkte-Schätzung je Rasterbereich (Bereich | Schätzung (max.) | Begründung).
Ordne die Listen nach Rasterpunkten je Stunde Aufwand, nicht nach der Reihenfolge der Funde.

MODUS (ich sage dir, welcher gilt; ohne Angabe gilt Solo):
- Solo: Du spielst nacheinander Prüfer, Experte und Gegenprüfer. Jeder Befund braucht Fundstelle und wörtliches Zitat. Danach greifst du in einem zweiten Durchgang jeden eigenen Befund an (Steht das Zitat wirklich so im Text? Ist der Befund falsch oder übertrieben?) und gibst zwei Listen aus: «bleibt» und «verworfen, weil …». Bleibt die Liste «verworfen» leer, prüfe ein zweites Mal besonders streng: Eine leere Liste ist ein Warnzeichen, kein Gütesiegel.
- Duo: Bekommst du zusätzlich die Befunde einer anderen KI, greifst du sie an: Welcher Befund ist falsch, was wurde übersehen? Jede Aussage mit Zitat und Fundstelle.
- Team: Du übernimmst nur die Rolle, die ich dir nenne (zum Beispiel Rechner, Quellenprüfer, Experte, Sprachprüfer), und lieferst Befunde im Format Befund | Fundstelle | Zitat | Schwere. Den Abgleich macht der Chef.
Zusatz für Duo im Gesamt-Audit: Ordne jeden fremden Befund ein (bleibt / verworfen, weil … / übertrieben, richtig wäre …) und nenne Übersehenes mit Zitat und Seite. Bestätige nichts, nur weil es plausibel klingt.

Beginne jetzt mit dem Bericht im Anhang. Frage den Studenten nur, wenn du eine Angabe wirklich brauchst und sie nirgends im Bericht steht.

--- ENDE ---
