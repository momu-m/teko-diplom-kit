# Beispiel-Gutachten zum Übungsbericht (echte KI-Antwort, kommentiert)

Dieses Gutachten hat eine einzige KI im Modus Solo mit der Kopiervorlage `teko-gesamt-audit.md` geschrieben, zum
Übungsbericht in diesem Ordner. Es ist inhaltlich unverändert übernommen. Davor steht, was daran gut ist und was nicht, damit du
lernst, ein Gutachten selbst zu prüfen.

## Was gut ist

- Alle zwölf eingebauten Fehler sind gefunden, jeder mit einem Zitat, das wirklich im Bericht steht.
- Die Rechnung ist gezeigt (36 / 200 = 18 %), nicht nur behauptet.
- Die Abstract-Länge ist gezählt (53 Wörter), nicht geschätzt.
- Es gibt eine Verworfen-Liste mit Grund. Die KI hat ihre eigenen Befunde also angegriffen.

## Was du an diesem Gutachten bemängeln müsstest

1. **Es ist an einer Stelle grüner als seine eigenen Befunde.** Punkt 18 (Quellen nach APA 7) steht auf «erfüllt»,
   obwohl das Gutachten selbst KI und Lexikon im Literaturverzeichnis bemängelt. Richtig wäre «offen».
2. **«Abnahme: Nein» ist ein Urteil über den Bericht.** Gemeint ist ein Urteil über das Gutachten selbst (sind alle
   Befunde belegt, passt der Stand der 20 Punkte zu den Befunden?).
3. **A11 verlangt Quellen auch für eigene Festlegungen** (Schaltpunkte 80 % und 30 %). Eigene Festlegungen brauchen eine
   Begründung, keine Quelle. Eine Quelle braucht die fremde Zahl (±1 mm aus dem Datenblatt).
4. **Die Empfehlung zu A8 ist zu weich.** Eine nachträglich gesenkte Grenze begründet man nicht im Nachhinein. Man nennt
   das Ergebnis gegen die ursprüngliche Grenze (90 % von 95 % verfehlt) und diskutiert es offen.
5. **Die Punkte-Schätzung ist eine grobe Orientierung**, keine Note. Sie kann deutlich daneben liegen.

Solche Fehler macht jede KI. Darum prüfst du jeden Befund am Original, und darum ist eine zweite KI (Modus Duo) besser
als eine.

---

## Das Gutachten der KI (inhaltlich unverändert, nur die Überschriften-Ebenen angepasst)

### Gesamt-Gutachten
Stand: 01.10.2026.
Auftrag: Gesamt-Audit (Modus Solo).
Geprüfte Version: Fassung 0.9.
Hinweis: Prüfung erfolgt «nur lesend».
Massstab: Höhere Fachschule (Systemtechnik), 20-Punkte-Raster.
Warnung: Das ist eine Schätzung [Schlussfolgerung], keine Notenprognose. Das Gutachten gibt keine Gewähr für die Note.

#### 0 In fünf Sätzen
1. Stand: 2 von 20 Punkten sind erfüllt, 4 sind teilweise erfüllt, 14 sind offen. Das Urteil der Abnahme lautet: Nein, mit Einwänden.
2. Die grösste Schwäche ist die fehlende wissenschaftliche Methodik. Es fehlen Quellen für technische Werte, und Testgrenzen wurden nachträglich ohne saubere Begründung geändert.
3. Danach folgen gravierende Widersprüche zwischen dem Text, der Tabelle und dem Fazit.
4. Das grösste technische Risiko ist die unbelegte Behauptung, das System «funktioniert», obwohl die Testmethodik nicht dokumentiert ist.
5. Zwei Befunde wurden im Vorfeld verworfen, da es sich nur um einen Auszug handelt.

#### 1 Wer hat geprüft
| Prüfer | Aufgabe | Ergebnis |
|---|---|---|
| Formprüfer | Abstract, Gliederung, Ziele, Form | Kritisch (Abstract lückenhaft, Ziele nicht messbar) |
| Quellenprüfer | Belege, Literaturverzeichnis | Kritisch (Zahlen unbelegt, KI als Literatur) |
| Sprachprüfer | Floskeln, Werbesprache, Klarheit | Kritisch (Werbewörter und Behauptungen gefunden) |
| Experte | Varianten, Methodik, Fazit | Kritisch (Grenzen angepasst, krasse Widersprüche) |
| Rechner | Alle Zahlen nachrechnen | Fehlerhaft (Prozentrechnung falsch) |
| Gegenprüfer | Eigene Befunde angreifen | Erfolgreich (2 Befunde verworfen) |

#### 2 Was kostet welche Schwäche
| Nr. | Schwäche | Rasterkriterium (Max.) | Abzug (Schätzung) | Gefunden von | Wann beheben |
|---|---|---|---|---|---|
| 1 | Fazit widerspricht den Ergebnissen | Diskussion (20) | -10 | Experte | sofort |
| 2 | Keine Kriterien beim Variantenentscheid | Variantenentscheide (10) | -8 | Experte | sofort |
| 3 | Testgrenzen nachträglich angepasst | Ergebnisse (10) | -5 | Experte | sofort |
| 4 | Ziele nicht messbar und falsche Stufen | Zielsetzung (10) | -5 | Formprüfer | sofort |
| 5 | Fehlende Quellen für Messwerte | Quellen / Hilfsmittel (10) | -5 | Quellenprüfer | sofort |
| 6 | Falsche Prozentrechnung | Einleitung (25) | -3 | Rechner | sofort |
| 7 | KI im Literaturverzeichnis | Quellen / Hilfsmittel (10) | -3 | Quellenprüfer | sofort |
| 8 | Werbewörter und unbelegte Aussagen | Bericht / Design (10) | -3 | Sprachprüfer | sofort |
| 9 | Legende unter der Tabelle | Bericht / Design (10) | -1 | Formprüfer | sofort |

#### 3 Liste A «sofort selbst»
Geordnet nach Rasterpunkten je Stunde Aufwand (schnelle, teure Fehler zuerst):
A1 Kapitel 5: Behauptung streichen, dass alle Ziele erreicht wurden, da Z4 nicht umgesetzt ist (Zitat: «Alle Ziele wurden erreicht.»).
A2 Kapitel 4: Tabelle anpassen, da Z2 im Text nur als teilweise erfüllt gilt (Zitate: «teilweise erfüllt» gegen «erfüllt»).
A3 Kapitel 1.3: Prozentwert von 15 % auf 18 % korrigieren (Zitat: «also eine Abweichung von 15 %.»).
A4 Literaturverzeichnis: Eintrag zu ChatGPT löschen und in eine separate KI-Deklaration verschieben (Zitat: «ChatGPT. (2026).»).
A5 Kapitel 1.2: Tabellenlegende über die Tabelle verschieben (Zitat: «Tabelle 1: Ziele der Arbeit»).
A6 Abstract und Kapitel 5: Werbewörter und leere Behauptungen streichen (Zitate: «nahtlos», «robust», «zukunftssicher», «funktioniert»).
A7 Kapitel 1.2: Kategorie entfernen und Ziele rein auf "Muss" oder "Kann" verteilen (Zitat: «Soll»).
A8 Kapitel 4: Belastbare technische Begründung für das Herabsetzen der Testgrenze aufschreiben (Zitat: «Nach den Tests wurde die Grenze auf 90 % gesenkt»).
A9 Literaturverzeichnis: Wikipedia durch Primärquelle wie das Hersteller-Datenblatt ersetzen (Zitat: «Wikipedia. (2025).»).
A10 Kapitel 1.2: Jedes Ziel zwingend mit Zahl und Termin ausstatten (Zitate: «Das System soll zuverlässig sein.», «Warnung per SMS», «Anzeige des Füllstands»).
A11 Hauptteil: Quellenangaben für alle technischen Daten nachtragen (Zitate: «40 m³», «dreimal», «80 %», «30 %», «95 %», «±1 mm»).
A12 Kapitel 2: Variantenentscheid als Bewertungsmatrix mit Kriterien, Gewichtung und Begründung je Zelle neu schreiben (Zitat: «weil er sich am besten eignet.»).

#### 4 Liste B «nach den letzten Ergebnissen»
B1 Abstract: Kennzahlen zum fertigen Ergebnis, genaue Grenzen und den nächsten Schritt am Ende ergänzen.
B2 Kapitel 4: Die Prüfung wiederholbar machen. Aufbau, Ablauf und das genaue Messprotokoll beschreiben (Zitat: «Die Steuerung wurde an drei Tagen getestet.»).
B3 Kapitel 5: Eine harte Kennzahl zur Qualität der Steuerung aus den Messergebnissen herleiten und ins Fazit aufnehmen.

#### 5 Verworfen mit Grund
| Befund | Von wem | Warum verworfen |
|---|---|---|
| Fehlende Verzeichnisse (Inhalt, Bilder etc.) | Formprüfer | Verworfen. Das Dokument ist ein Auszug. Solche Verzeichnisse liegen vermutlich auf den nicht gelieferten Seiten. |
| Wortzahl pro Seite zu hoch | Formprüfer | Verworfen. Eine Schätzung der Seitendichte ist auf Basis eines unvollständigen Auszugs nicht seriös. |

#### 6 Widersprüche und Lösung
A gegen B: Text in Kapitel 4 bewertet Z2 als «teilweise erfüllt». Die Tabelle in Kapitel 4 nennt Z2 «erfüllt». Das Fazit in Kapitel 5 sagt «Alle Ziele wurden erreicht.», obwohl Z4 gemäss Tabelle «nicht umgesetzt» wurde.
Entscheid: Tabelle und Fazit müssen strikt dem Fliesstext folgen.
Grund: Die Tabelle darf nie grüner (positiver) sein als der Begleittext. Das Fazit darf keine Tatsachen aus den Ergebnistabellen verdrehen.

#### 7 Stand der 20 Punkte
Erfüllt:
- 18 Quellen nach APA 7 (Format teilweise eingehalten, aber inhaltliche Fehler).
- 19 Zeit in Stunden Soll gegen Ist.

Teilweise erfüllt:
- 2 Abstract (Frage und Weg sind da, Ergebnis und Kernzahlen fehlen).
- 5 Messbare Ziele (Kategorien da, aber Termine und Zahlen fehlen).
- 7 Tabelle gleich Text (Vorhanden, aber massiv widersprüchlich).
- 8 Entscheid mit Kriterien (Variante erwähnt, aber Kriterien fehlen).

Offen:
- 1 Roter Faden.
- 3 Gleicher Aufbau.
- 4 Bild trägt, Text deutet.
- 6 Rückverfolgbarkeit (keine IDs im Text erwähnt).
- 9 Ganze Kette geprüft.
- 10 Wiederholbare Prüfung mit Protokoll.
- 11 Fehler mit Ursachenkette.
- 12 Kennzahlen hergeleitet.
- 13 Schwächen vorweg beantwortet.
- 14 Bild je Arbeitsschritt.
- 15 Lesbarkeit gedruckt.
- 16 Anhang als Nachweiskette.
- 17 System als Ganzes.
- 20 Schlusswort konkret und selbstkritisch.

Gezählte Richtwerte:
- Abstract-Länge: 53 Wörter.
- [Unbestätigt] Wort- und Bilddichte pro Seite (im Auszug nicht ermittelbar).

#### 8 Zahlen-Prüfung
| Grösse | Nachrechnung | Urteil |
|---|---|---|
| Zeit-Abweichung (Kapitel 1.3) | (236 - 200) / 200 = 36 / 200 = 0.18 | Falsch. Im Text stehen 15 %, das Rechenergebnis ist 18 %. |
| Korrekte Schaltungen (Kapitel 4) | 18 / 20 = 0.90 | Korrekt. Ergibt exakt 90 %. |

#### 8b Weitere Ergebnisse
- Verweise lückenlos? Nein. Es gibt keine Verweise auf die «Tabelle 1» im Fliesstext.
- Quelle fehlt im Verzeichnis? Ja. Für die Zahlen (40 m³, 80 %, 30 %, 95 %, ±1 mm) fehlen jegliche Herkunftsnachweise.
- Zu lange Sätze? Nein. Der längste Satz zählt 16 Wörter und liest sich flüssig.

#### 8c Abnahme
Urteil: Nein.
Eingearbeitete Einwände: Der Variantenentscheid ist wertlos, da jegliche Kriterien fehlen. Die nachträgliche Anpassung der Testgrenze («auf 90 % gesenkt») verzerrt die Ergebnisse und bricht die Methodik. Die Widersprüche zwischen den Ergebnissen und dem Fazit beschönigen die Arbeit massiv. Künstliche Intelligenz darf niemals als Quellenbeleg im Literaturverzeichnis stehen.

#### 9 Liste C «Entscheid des Studenten oder Betreuers»
C1 Fachlichen Entscheid fällen: Darf die Zielgrenze nachträglich von 95 % auf 90 % gesenkt werden? Wenn ja, muss der Betreuer das absegnen, und es erfordert eine harte technische Begründung im Text.
C2 Vorgaben prüfen: Zwingt die Themenstellung zur Zielkategorie «Soll»? Falls nein, muss Z3 zwingend in «Muss» oder «Kann» umgewandelt werden.

#### Punkte-Schätzung je Rasterbereich
| Bereich | Schätzung (max.) | Begründung |
|---|---|---|
| Hauptteil | 10 (30) | Variantenentscheid hat keine Kriterien. Das Vorgehen ist kaum beschrieben. |
| Einleitung | 12 (25) | Zeitabweichung falsch berechnet. Alle Ziele sind unmessbar. |
| Abstract | 10 (20) | Viel zu kurz. Es fehlen harte Kernzahlen und Grenzen. |
| Diskussion | 5 (20) | Das Fazit widerspricht den Resultaten. Jede kritische Reflexion fehlt. |
| Empfehlung und Ausblick | 5 (15) | Äusserst oberflächlich («weitere Verbesserungen werden beschrieben»). |
| Quellen und Hilfsmittel | 3 (10) | Technische Daten sind unbelegt. KI steht im Quellenverzeichnis. |
| Bericht und Design | 6 (10) | Werbewörter im Text. Legende steht fälschlicherweise unter der Tabelle. |
| Anhang | [Unbestätigt] (10) | Liegt im Auszug nicht vor. |
| Präsentation | Nicht aus dem Bericht prüfbar (20) | - |
| Arbeitsweise | Nicht aus dem Bericht prüfbar (10) | - |
| Onlinepublikation | Nicht aus dem Bericht prüfbar (10) | - |

Summe Schätzung: 51 von 140 prüfbaren Punkten.
