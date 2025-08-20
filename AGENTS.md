# AGENTS.md

## Objectif

Ce fichier décrit les règles, procédures et conventions à suivre par tous les agents intelligents (ex : Cursor, Amp, Factory, Roo Code) et les nouveaux membres humains du projet.

---

## Installation & Lancement

- Installer les dépendances avec :  
  `pnpm install`
- Lancer le projet en local :  
  `pnpm dev`
- Créer/mettre à jour le fichier `.env` à partir de `.env.example`

---

## Tests & Quality Gate

- Tous les tests sont dans le dossier `/tests`
- Lancer la batterie de tests :  
  `pnpm test`
- Vérifier le lint avant tout commit/pr :  
  `pnpm lint`
- Utiliser Prettier pour le formatage automatique :  
  `pnpm format`
- Toute pull request doit passer les CI/CD automatiques et les tests avant le merge

---

## Nommage, Structure & Branches

- Branch naming :  
  `feature/[description]`, `fix/[description]`, `chore/[description]`
- Les commits doivent être clairs et respecter la convention du projet
- Respecter la structure du code détaillée dans `/docs/ARCHITECTURE.md` si disponible

---

## Sécurité & Sensibilité

- Jamais d’information secrète (API key, mot de passe…) dans le code source
- Variables sensibles à définir dans le fichier `.env` (jamais versionné)
- Chemins sensibles à protéger via `.gitignore`
- Vérification automatique des dépendances critiques à chaque merge

---

## CI/CD

- Les workflows automatisés sont définis dans `.github/workflows/ci.yml`
- Sur chaque PR et merge dans `main`, les étapes suivantes sont déclenchées :
  - Test complet
  - Vérification lint/style
  - Build
  - Déploiement sur staging (si pipeline activé)

---

## Documentation

- Toute contribution doit être documentée dans `/docs/CONTRIBUTION.md` si besoin

---

## Guide rapide agents (Cursor, Amp, etc.)

- Lire AGENTS.md en priorité avant d’exécuter/tests/refactoring
- Appliquer strictement les commandes et les noms définis
- Remonter toute question ou anomalie en issue GitHub

---
