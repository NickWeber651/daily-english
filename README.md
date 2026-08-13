# Daily English

Zehn Minuten Englisch am Tag: Grammatik, selbst schreiben, laut reden.
Gebaut für **Business English M3W** (HTW Berlin, Modul 7512, Niveau B2.2).

**Benutzen:** Die Android-App unter [Releases](../../releases) installieren —
oder `index.html` herunterladen und im Browser öffnen. Die Datei läuft
eigenständig, ohne Server.

## Was drin ist

| | |
|---|---|
| Grammatikthemen | 47 |
| Fehlersätze | 141 |
| Übersetzungen | 141 |
| Schreibaufgaben | 47 lang, 47 kurz |
| Sprechthemen | 28 |
| Wendungen | 282 fürs Schreiben, 19 fürs Sprechen |

Alle zwölf englischen Zeitformen, Conditionals 1–3 und mixed, Passiv,
Relativsätze, indirekte Rede — plus die typischen Fehler, die Deutsche
im Englischen machen.

## Wie es funktioniert

Kein Tagesplan, keine Serie. Du drückst **Start**, die App sucht das Thema aus:
erst was du noch nie hattest, danach immer das, was am schlechtesten sitzt.

**Start — 10 Minuten** führt durch vier Schritte: Regel lesen, in drei Sätzen
den Fehler antippen, drei Sätze übersetzen, am Ende selbst einen Text schreiben.

**Sprechen** gibt dir ein Thema, 30 Sekunden zum Überlegen und zwei Minuten
zum Reden — so lang wie in der mündlichen Prüfung.

Beide enden mit einem Knopf, der deinen Text bzw. das Thema samt fertiger
Anweisung in die Zwischenablage legt. In Claude einfügen, und du bekommst
Korrektur oder einen Prüfer, der dir Rückfragen stellt.

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
