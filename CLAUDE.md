# luizz28-goat.github.io (Projekt-Hub)

Statische `index.html`, automatisch unter `https://luizz28-goat.github.io/`
gehostet (GitHub Pages, weil der Repo-Name exakt `<username>.github.io`
lautet — nicht zu verwechseln mit der GitHub-Verwaltungsseite des Repos).

## Architektur

- Ein clientseitig gerendertes `projects`-Array in `index.html` ist die
  einzige Datenquelle für die Kacheln. Neues Projekt hinzufügen: Eintrag
  `{ name, desc, icon, url }` im Array ergänzen.
- Kein Build-Schritt, keine Frameworks.

## Workflow in diesem Repo

Bisher immer direkt auf `main` committen und pushen (kein PR-Workflow, keine
CI) — Repo ist klein/risikoarm genug dafür.

## Zusammenspiel mit claude.ai-Projects (Chat/Cowork)

Dieses Repo ist im claude.ai-Project "Kleine Anwendungen" als Kontext verknüpft.
Das Project liest dadurch automatisch den aktuellen Repo-Stand (Commits, Dateien,
auch diese Datei) — es gibt aber keinen Weg zurück: was im Project-Chat besprochen
wird, landet nicht automatisch hier.

Deshalb: tatsächliche Arbeitsanweisungen ("bau X", "ändere Y") nur hier im
Code-Bereich geben, nicht parallel im Project-Chat, damit nicht zwei Stellen
unabhängig voneinander am selben Code arbeiten. Wurde im Project-Chat trotzdem
etwas entschieden, das den Code betreffen soll, wird es zuerst hier (in dieser
Datei oder direkt in der nächsten Anweisung) festgehalten, bevor daran
gearbeitet wird.
