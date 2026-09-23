# MyFirstGitRepo

Dies ist mein erstes Git Projekt

1. hello.txt
2. Was bedeutet Staging in Git?
3. Wie heisst der aktive Branch direkt nach dem Initialisieren des Repositories?
4. Womit kann man sich alle bisherigen Commits anzeigen lassen?
5. Welcher Befehl zeigt den aktuellen Status des Repositories an (z. B. ob Dateien gestaged oder committed sind)?
6. Wozu dient die Datei .gitignore?


# Git Grundlagen

## Staging

- Dateien vor dem Commit zur „Veröffentlichung" vorbereiten

- Mit `git add <datei>` in den Staging-Bereich verschieben

- Nur gestaged Dateien werden im nächsten Commit erfasst

## Branch nach init

- `master` (oder `main` in neueren Versionen)

- Standard-Branch nach `git init`

## Commits anzeigen

- `git log` – komplette Commit-Historie

- `git log --oneline` – kompakte Ansicht

## Repository-Status

- `git status` – zeigt gestaged, modified, untracked Dateien

- Hilft zu sehen, was vor dem Commit noch zu tun ist

## .gitignore

- Text-Datei mit Dateien/Ordnern, die Git ignorieren soll

- Ideal für: Abhängigkeiten, Konfigdateien, Logs, Secrets

- Z.B.: `node_modules/`, `*.log`, `.env`

- Wird selbst committed, .gitignore'd Dateien nicht
 

