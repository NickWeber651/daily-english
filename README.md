# Daily English

Fünfzehn Minuten Englisch am Tag: Grammatik üben, Sätze bauen, Begriffe definieren, selbst schreiben.
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
| Begriffe zum Definieren | 60 |
| Wortbildungs-Sätze | 56 |
| Fokussätze aus dem Writing-Drill | 24 |

Nur M3W-Stoff: Zeiten aktiv und passiv, Conditionals 1–3 und mixed,
Relativsätze, Adjektiv/Adverb, Verbindungswörter und die Kursthemen
Trends, Meetings, Meinung und Präsentation. Dazu der Wortschatz der Kursliste
(Management Styles, Raising Finance, Customer Service, Meetings) in den
Aufgabenarten der Klausur: Begriff definieren, Begriff zur Definition finden,
Wortbildung.

Essay und Lesetexte sind bewusst nicht in der App — die laufen im Chat mit Claude.

## Wie es funktioniert

Kein Tagesplan, keine Serie. Du drückst **Start**, die App sucht das Thema aus:
erst was du noch nie hattest, danach immer das, was am schlechtesten sitzt.

**Start — 15 Minuten** führt durch sechs Schritte: Regel lesen, in drei Sätzen
den Fehler antippen, drei Sätze übersetzen, drei Fokussätze bauen, drei
Wortschatz-Aufgaben lösen, am Ende selbst einen Text schreiben.

**Fokussätze** kommen aus dem Writing-Drill im Chat: je ein deutscher Satz pro
aktuellem Fokusmuster (gerade Pronomen, Subjekt nach Vorbau, Verbform), frei
übersetzen, dann mit der Musterlösung vergleichen. Gezählt wird nur, ob das
Muster saß. Eigene Sätze aus dem Drill kommen zuerst, Verpasstes kommt wieder.
Nach jedem Drill werden `FOCUS.active` und die Sätze in `index.html` angepasst.

**Klausur-Mix — 5 Minuten** geht ohne Grammatikthema: zwei Begriffe definieren,
zwei Begriffe zur Definition finden, zweimal Wortbildung, zwei Sätze übersetzen
(Conditionals, Relativsätze und Passiv durcheinander). Was daneben ging, kommt
in der nächsten Runde zuerst wieder. Unter *Themen* lässt sich jede Aufgabenart
auch einzeln starten.

Die Eingabefelder schalten Rechtschreibhilfe und Autokorrektur ab, soweit der
Browser das zulässt — die Klausur wird auf Papier geschrieben.

Am Ende legt ein Knopf deinen Text und deine Definitionen samt fertiger Anweisung in die Zwischenablage.
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
