# Snake mit Twist

Das klassische Snake – aber nach jedem Futter ändert sich eine Regel.

## Spielen

`index.html` im Browser öffnen. Es gibt keine Abhängigkeiten und keinen Build-Schritt.

## Steuerung

| Taste | Aktion |
| --- | --- |
| Pfeiltasten oder WASD | Schlange steuern |
| Leertaste | Start / Neustart, im Spiel Pause |
| P | Pause |

Auf Touch-Geräten: tippen zum Starten, wischen zum Steuern.

## Regeln

Nach jedem gefressenen Futter wird zufällig eine neue Regel aktiv:

| Regel | Wirkung |
| --- | --- |
| Turbo | Die Schlange ist deutlich schneller. |
| Zeitlupe | Alles läuft gemächlich. |
| Spiegelsteuerung | Links ist rechts, oben ist unten. |
| Offene Wände | Am Rand kommst du gegenüber wieder heraus. |
| Geisterschwanz | Du kannst durch deinen eigenen Körper gleiten. |
| Doppelt | Das nächste Futter zählt und verlängert doppelt. |
| Mauerbau | Drei neue Hindernisse erscheinen und bleiben. |

Jede Runde beginnt mit der Regel „Normal“. Der Rekord wird lokal im Browser gespeichert.
