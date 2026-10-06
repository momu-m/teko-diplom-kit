# Übungsbericht (erfunden)

Mit diesem kurzen, absichtlich fehlerhaften Bericht testest du deine KI, bevor du ihr deine eigene Arbeit gibst.
Er enthält zwölf eingebaute Fehler. Die Lösung steht in `SCHLUESSEL.md` (erst nach dem Test öffnen), ein Beispiel-
Gutachten in `BEISPIEL_GUTACHTEN.md`. Alles hier ist ausgedacht: Firma, Anlage, Zahlen und Quellen.

---

# Diplomarbeit (erfunden): Füllstandregelung für ein Regenwasserbecken

Fassung 0.9, 01.10.2026, 14 Seiten Hauptteil (Auszug)

## Abstract

In dieser Arbeit wurde eine Steuerung für die Pumpe eines Regenwasserbeckens entwickelt. Zuerst wurde die Ausgangslage
analysiert, dann wurden Varianten untersucht und eine Lösung umgesetzt. Die Steuerung wurde getestet und funktioniert.
Es ist wichtig zu beachten, dass die Lösung nahtlos in die bestehende Anlage integriert werden kann. Im Ausblick werden
weitere Verbesserungen beschrieben.

## 1 Einleitung

### 1.1 Ausgangslage

Die Firma betreibt ein Regenwasserbecken mit 40 m³ Inhalt. Die Pumpe wird heute von Hand eingeschaltet. Bei starkem
Regen lief das Becken im letzten Jahr dreimal über.

### 1.2 Ziele

| Nr. | Ziel | Stufe |
|---|---|---|
| Z1 | Das System soll zuverlässig sein. | Muss |
| Z2 | Die Pumpe schaltet bei 80 % Füllstand automatisch ein. | Muss |
| Z3 | Eine Warnung per SMS bei Überlauf-Gefahr. | Soll |
| Z4 | Anzeige des Füllstands auf einem Bildschirm. | Kann |

Tabelle 1: Ziele der Arbeit

### 1.3 Zeitplanung

Geplant waren 200 Stunden. Gebraucht wurden 236 Stunden, also eine Abweichung von 15 %.

## 2 Varianten

Für die Messung des Füllstands wurde ein Ultraschallsensor gewählt, weil er sich am besten eignet. Ein Drucksensor und
ein Schwimmerschalter wären auch möglich gewesen.

## 3 Umsetzung

Der Ultraschallsensor hat eine Genauigkeit von ±1 mm. Die Steuerung liest den Füllstand jede Sekunde und schaltet die
Pumpe bei 80 % ein und bei 30 % aus. Die SMS-Warnung wird bei 95 % gesendet.

## 4 Tests und Ergebnisse

Die Steuerung wurde an drei Tagen getestet. Die Pumpe schaltete in 18 von 20 Fällen korrekt ein. Damit ist Ziel Z2
teilweise erfüllt. Ursprünglich war als Bestanden-Grenze 95 % korrekte Schaltungen festgelegt. Nach den Tests wurde die
Grenze auf 90 % gesenkt, weil das in der Praxis reicht.

| Ziel | Ergebnis |
|---|---|
| Z1 | erfüllt |
| Z2 | erfüllt |
| Z3 | erfüllt |
| Z4 | nicht umgesetzt |

## 5 Fazit

Alle Ziele wurden erreicht. Die Lösung ist robust und zukunftssicher.

## Literaturverzeichnis

ChatGPT. (2026). Antwort auf die Frage nach dem besten Füllstandsensor. OpenAI.

Wikipedia. (2025). Ultraschallsensor.
