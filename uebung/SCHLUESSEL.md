# Schlüssel zum Übungsbericht (erst nach dem Test öffnen)

So wertest du aus: Zähle, wie viele der zwölf Fehler deine KI mit einem echten Zitat gefunden hat. Prüfe jedes Zitat im
Übungsbericht nach. Ein Befund mit erfundenem Zitat zählt nicht, auch wenn der Fehler stimmt.

- **9 bis 12 gefunden, kein erfundenes Zitat:** Deine Einrichtung funktioniert. Jetzt kannst du deinen eigenen Bericht prüfen.
- **6 bis 8 gefunden:** Benutze die Kopiervorlage `teko-gesamt-audit.md` (sie hat eine Prüfliste je Rolle) und schreib
  «Modus Solo, arbeite jede Prüfliste ganz ab». Oder nimm eine zweite KI dazu (Modus Duo).
- **Weniger als 6 oder erfundene Zitate:** Diese KI ist für eine Prüfung nicht geeignet, oder der Bericht kam nicht
  richtig an. Versuche es mit einer anderen KI.

| Nr. | Eingebauter Fehler | Stelle | Welcher Skill ihn finden soll |
|---|---|---|---|
| F1 | Abstract ohne Ergebnis, ohne Zahl, ohne Grenze und viel zu kurz | Abstract | teko-bericht-regeln, teko-6er-check |
| F2 | Floskeln und Werbewörter: «Es ist wichtig zu beachten», «nahtlos», «robust und zukunftssicher» | Abstract, Fazit | teko-sprache |
| F3 | Ziel Z1 nicht messbar (keine Zahl, kein Termin) | Tabelle 1 | teko-6er-check |
| F4 | drei Zielstufen (Muss, Soll, Kann), wo die Themeneingabe meist nur zwei kennt | Tabelle 1 | teko-bericht-regeln |
| F5 | Tabellenlegende unter statt über der Tabelle | Tabelle 1 | teko-bericht-regeln |
| F6 | Rechenfehler: 236 h gegen 200 h sind 18 % mehr, nicht 15 % | Kapitel 1.3 | Rechner, teko-team-lehren |
| F7 | Variantenentscheid ohne Kriterien, Gewichtung und Begründung | Kapitel 2 | teko-experte, teko-6er-check |
| F8 | Zahl ohne Quelle (Genauigkeit ±1 mm) | Kapitel 3 | teko-quellen |
| F9 | Bestanden-Grenze nach dem Test von 95 % auf 90 % gesenkt | Kapitel 4 | teko-experte, teko-team-lehren |
| F10 | Tabelle grüner als der Text (Z2 «erfüllt», im Text «teilweise»; Z1 und Z3 ohne Nachweis «erfüllt») | Kapitel 4 | teko-6er-check, teko-team-lehren |
| F11 | Fazit «Alle Ziele wurden erreicht», obwohl Z4 nicht umgesetzt ist | Kapitel 5 | teko-6er-check |
| F12 | KI als Quelle im Literaturverzeichnis, Lexikon statt Primärquelle, keine KI-Deklaration | Literatur | teko-quellen |

Weitere Schwächen, die eine gute Prüfung zusätzlich nennt: Test nicht wiederholbar beschrieben (kein Ablauf, kein
Protokoll), Ergebnistabelle ohne Legende, «weil er sich am besten eignet» als Scheinbegründung, Tabelle 1 im Text nie
erwähnt.

Zum Vergleich: Bei der Prüfung des Pakets fand eine einzige KI mit `teko-gesamt-audit` im ersten Anlauf 8 von 12; nach
einer Verbesserung der Vorlage fand dieselbe KI 12 von 12. Das Ergebnis steht in `BEISPIEL_GUTACHTEN.md`.
