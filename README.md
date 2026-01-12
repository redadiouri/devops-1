# devops-1

Application ViteJS avec Pipeline CI/CD

## Description

Application Hello World construite avec ViteJS et React, incluant une pipeline CI complète avec:
- ESLint pour le linting
- Prettier pour le formatage du code
- Snyk pour les contrôles de sécurité

## Scripts disponibles

- `npm run dev` - Lancer le serveur de développement
- `npm run build` - Builder l'application pour la production
- `npm run lint` - Vérifier le code avec ESLint
- `npm run format` - Formater le code avec Prettier
- `npm run format:check` - Vérifier le formatage sans modifier les fichiers
- `npm run preview` - Prévisualiser le build de production

## Pipeline CI

La pipeline CI exécute automatiquement dans l'ordre:
1. Lint (ESLint)
2. Format Check (Prettier)
3. Security Scan (Snyk)
4. Build (ViteJS)

