# Brief an einen Prüfer

So benutzt du ihn: Fülle die Felder in spitzen Klammern aus, kopiere den Brief in den Chat der Prüfer-KI und hänge den Bericht an. Für jede Rolle schreibst du einen eigenen Brief. Den Teil «Gegenprüfung» brauchst du nur im Modus Duo oder Team, für die zweite KI.

## Teil 1: Auftrag

```
ROLLE: <zum Beispiel Quellenprüfer, Formprüfer, Rechner, zweiter Experte (greift an, bestätigt nicht)>
AUFGABE: <ein Satz, zum Beispiel «Prüfe alle Zitate und das Literaturverzeichnis»>
FAKTEN: <Version, Datei, Kapitelbereich. Quelle dieser Fakten.>
MASSSTAB: <Raster deiner Schule / die 20 Punkte / die Anleitung, je nach Rolle. Füge die Kriterien in den Brief ein, die KI soll keine erfinden.>
VERBOT: Nichts ändern. Nur die Ausgabe schreiben.
ZITATPFLICHT: Jeder Befund mit Fundstelle (Seite oder Kapitel) und wörtlichem Zitat.
          Ein Befund ohne Zitat und Fundstelle gilt als nicht gefunden.
FORMAT: Befund | Fundstelle | Zitat | Schwere (kritisch / wichtig / klein)
BEKANNTE FALSCHBEFUNDE (nicht wiederholen): <Liste oder «keine»>
HALTUNG: Greife an, bestätige nicht. «Das ist gut so» nur mit Nachweis.
UNSICHERES: mit [Unbestätigt] markieren. Nichts erfinden.
FERTIG, WENN: Die Tabelle ist vollständig, mindestens <n> Stellen sind geprüft,
          und am Ende steht die Zeile «Selbstprüfung: jedes Zitat steht im Text ja/nein».
```

## Teil 2: Gegenprüfung (Modus Duo)

Gib der zweiten KI den Bericht, den Auftrag aus Teil 1 und die Befunde der ersten KI. Dazu diesen Text:

```
Hier sind die Befunde eines anderen Prüfers. Widersprichst du? Welcher Befund ist falsch, und was hat er übersehen? Jede Aussage mit Zitat und Seite.

Gehe so vor:
1. Prüfe jeden Befund einzeln am Text. Steht das Zitat wörtlich so da? Stimmt die Seite?
2. Ordne jeden Befund ein: bleibt / verworfen, weil <Grund mit Zitat> / übertrieben, richtig wäre <...>.
3. Nenne, was der andere Prüfer übersehen hat, mit Zitat und Seite.
4. Nichts bestätigen, nur weil es plausibel klingt. Unsicheres mit [Unbestätigt] markieren.

Ausgabe: zwei Tabellen.
Tabelle 1: Befund (Nr. des anderen Prüfers) | Einordnung | Zitat | Seite
Tabelle 2 (Übersehenes): Befund | Fundstelle | Zitat | Schwere
```

## Teil 3: Nachher bei dir

- Du prüfst jeden Befund aus «bleibt» selbst an der genannten Seite.
- Widersprechen sich zwei Prüfer, zählt das Zitat im Original, nicht die Mehrheit.
- Verworfene Befunde kommen mit Grund in die Verworfen-Liste des Gutachtens.
- Speichere Brief, Antwort und Chat-Verlauf. Du brauchst sie für die Deklaration der KI-Nutzung.
