# Tic-Tac-Toe in Python

## Projektübersicht

Dieses Projekt stellt ein einfaches Tic-Tac-Toe-Spiel dar, das in Python implementiert wurde. Es handelt sich um ein textbasiertes Spiel, das zwei Spielern ermöglicht, abwechselnd ihre Züge zu machen. Das Projekt entstand in meiner Freizeit und war mein erster Versuch, Python zu programmieren.

## Funktionsweise

Das Spiel läuft vollständig in der Konsole. Das Spielfeld besteht aus einem 3x3-Raster, 
das durch Zahlen von 1 bis 9 dargestellt wird. Jeder Spieler gibt abwechselnd die Zahl des Feldes ein, 
auf das er sein Symbol (`X` oder `O`) setzen möchte. Das Spiel überprüft nach jedem Zug, ob ein Spieler gewonnen hat oder ob das Spiel unentschieden endet.

### Wichtige Funktionen

- **Spielfeldanzeige (`field_output`)**: Das aktuelle Spielfeld wird nach jedem Zug angezeigt, um den Spielern den aktuellen Stand des Spiels zu zeigen.
- **Spielerzug (`player_input`)**: Der Spieler wird aufgefordert, eine Zahl zwischen 1 und 9 einzugeben, um sein Symbol auf das Spielfeld zu setzen. Wenn ein Spieler `q` eingibt, wird das Spiel abgebrochen.
- **Spielerwechsel (`change_player`)**: Nach jedem Zug wechselt das Spiel den aktiven Spieler.
- **Gewinnprüfung (`control_win`)**: Das Spiel überprüft, ob ein Spieler eine Gewinnkombination (drei gleiche Symbole in einer Reihe, Spalte oder Diagonale) erreicht hat.
- **Unentschiedenprüfung (`control_if_win`)**: Wenn alle Felder belegt sind und kein Spieler gewonnen hat, endet das Spiel unentschieden.

### Spielablauf

1. Zu Beginn wird das Spielfeld angezeigt, und der erste Spieler (`X`) beginnt das Spiel.
2. Der Spieler gibt die Zahl des Feldes ein, auf das er sein Symbol setzen möchte.
3. Das Spielfeld wird aktualisiert und erneut angezeigt.
4. Das Spiel überprüft, ob ein Spieler gewonnen hat oder ob das Spiel unentschieden endet.
5. Wenn kein Ergebnis feststeht, wechselt das Spiel den aktiven Spieler, und der nächste Zug wird ausgeführt.
6. Das Spiel endet, wenn ein Spieler gewinnt oder das Spiel unentschieden ausgeht.

## Fazit

Dieses Tic-Tac-Toe-Projekt war eine großartige Einführung in die Programmierung mit Python. Es hat mir geholfen, grundlegende Programmierkonzepte wie Schleifen, Bedingungen und Funktionen zu verstehen. Das Spiel bietet eine einfache, aber effektive Möglichkeit, die Mechanismen eines klassischen Spiels in einer neuen Programmiersprache umzusetzen.
