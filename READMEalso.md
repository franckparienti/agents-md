# AGENTS.md – Standard de collaboration pour agents d’IA

## Présentation

Bienvenue sur ce dépôt !  
Ici, vous découvrez comment le fichier **AGENTS.md** révolutionne la collaboration entre humains et agents IA dans le développement logiciel.

Les agents intelligents (outils d’édition comme Cursor, automatisation avec Amp ou Factory, refactoring avec Roo Code…) prennent une place de plus en plus grande dans nos workflows.  
Pour qu’ils soient efficaces, il leur faut des consignes claires, structurées, réutilisables : c’est exactement ce que fournit **AGENTS.md**.

***

## Avantages

- **Interopérabilité :** Un fichier lu par tous vos agents IA : Cursor, Amp, Factory, Roo Code, etc.
- **Clarté des règles :** Centralisation des guidelines, procédures de test, conventions de nommage, pratiques de sécurité.
- **Onboarding accéléré :** N’importe quel alternant, nouveau développeur ou agent IA adopte immédiatement vos standards.
- **Automatisation sécurisée :** Les workflows CI/CD, les tests et les opérations techniques sont exécutés sans erreur.
- **Évolutivité & robustesse :** Un seul fichier à mettre à jour et à surveiller pour garder le contrôle sur la qualité du projet.

***

## Exemple concret

Un AGENTS.md typique ressemble à cela :

```markdown
# AGENTS.md

## Installation
- `pnpm install` pour installer les dépendances
- `pnpm dev` pour lancer le projet en local

## Tests & CI
- Test : `pnpm test` (tous les tests dans /tests)
- Lint : `pnpm lint`
- Les PR passent toutes les vérifications CI avant merge

## Conventions
- Formatage via Prettier
- Règles spécifiques dans .eslintrc.json
- Branches : nommées selon `feature/description`

## Sécurité
- Aucune clé ou secret dans le code source : utiliser .env.example
```

***

## Ressources

- [Article détaillé sur AGENTS.md et cas d’usage](https://www.businessdigital.fr/articles/agentsmd--le-standard-pour-collaborer-avec-les-agents-dia-en-dveloppement-logiciel)
- [Dépôt OpenAI/agents.md (exemples communautaires)](https://github.com/openai/agents.md)
- [Découvrir l’éditeur Cursor](https://www.cursor.so/)

***

## Comment utiliser ce dépôt

1. Parcourez le fichier AGENTS.md pour comprendre les guidelines d’un projet moderne IA-ready.
2. Inspirez-vous de la structure proposée pour vos propres projets.
3. Proposez vos améliorations, exemples d’utilisation ou questions via issues ou pull requests !

***

**Adoptez AGENTS.md et préparez vos projets au futur de la collaboration homme + IA !**

