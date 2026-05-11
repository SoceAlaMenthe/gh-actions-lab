# gh-actions-lab

Dépôt de travaux pratiques — GitHub Actions.

## Workflows

| Fichier | Déclencheur | Description |
|---------|------------|-------------|
| `bonjour.yml` | `push` | Affiche un message de bienvenue, la date et l'acteur GitHub. |
| `pr-check.yml` | `pull_request` vers `main` | Affiche le numéro et l'auteur de la pull request. |
| `scheduled.yml` | `schedule` (cron lun-ven 09:00 UTC) + `workflow_dispatch` | Tâche planifiée avec choix d'environnement (dev/staging/prod). |
| `docs-only.yml` | `push` sur `docs/**` | Se déclenche uniquement quand la documentation est modifiée. |
