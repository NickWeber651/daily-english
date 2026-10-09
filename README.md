# Daily English

Zehn Minuten Englisch am Tag: Grammatik üben und selbst schreiben.
Gebaut für **Business English M3W** (HTW Berlin, Modul 7512, Niveau B2.2).

**Benutzen:** Die Android-App unter [Releases](../../releases) installieren —
oder `index.html` herunterladen und im Browser öffnen. Die Datei läuft
eigenständig, ohne Server.

## Was drin ist

| | |
|---|---|
| Grammatikthemen | 26 |
| Fehlersätze | 78 |
| Übersetzungen | 78 |
| Schreibaufgaben | 26 lang, 26 kurz |
| Wendungen | 156 |

Nur M3W-Stoff: Zeiten aktiv und passiv, Conditionals 1–3 und mixed,
Relativsätze, Adjektiv/Adverb, Verbindungswörter und die Kursthemen
Trends, Meetings, Meinung und Präsentation.

Essay und Lesetexte sind bewusst nicht in der App — die laufen im Chat mit Claude.

## Wie es funktioniert

Kein Tagesplan, keine Serie. Du drückst **Start**, die App sucht das Thema aus:
erst was du noch nie hattest, danach immer das, was am schlechtesten sitzt.

**Start — 10 Minuten** führt durch vier Schritte: Regel lesen, in drei Sätzen
den Fehler antippen, drei Sätze übersetzen, am Ende selbst einen Text schreiben.

Am Ende legt ein Knopf deinen Text samt fertiger Anweisung in die Zwischenablage.
In Claude einfügen, und du bekommst die Korrektur, deine wichtigsten Fehler und
eine Regel für das nächste Mal.

## Wo der Fortschritt liegt

Im `localStorage` des Browsers, Schlüssel `dailyEnglish.v2`. Nichts wird
hochgeladen, nichts verlässt das Gerät.

**Das heißt auch: Browserdaten löschen löscht den Fortschritt.**
Unter *Themen → Fortschritt sichern oder zurückholen* gibt es deshalb eine
Sicherung als Datei oder als Text.

Die Android-App unter [Releases](../../releases) hat ihren eigenen Speicher,
den das Löschen von Browserdaten nicht anfasst.

## Technisch

Eine einzige HTML-Datei. Kein Build, keine Abhängigkeiten, keine Netzwerkzugriffe.
Läuft nach dem ersten Laden offline. Hell und dunkel, für Handy gebaut.

Die Android-App ist dieselbe Datei in einer WebView-Hülle (Capacitor).
Sie ist selbst signiert — Android warnt deshalb bei der Installation.
