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
