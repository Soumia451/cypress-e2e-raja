# Tests E2E automatisés — Site e-commerce RAJA

Projet réalisé dans le cadre de ma formation Testeur logiciel (OpenClassrooms).

Automatisation des tests end-to-end des parcours clés du site raja.fr avec Cypress.

## Objectifs

- Rédiger les scénarios et cas de test des fonctionnalités principales : achat, demande de devis, création de liste, formulaires, modification de compte, recommandations produits
- Automatiser les flux end-to-end pour fiabiliser les régressions
- Documenter les résultats et suivre les anomalies

## Stack technique

| Outil | Usage |
|-------|-------|
| Cypress | Automatisation des tests E2E |
| JavaScript | Écriture des scripts de test |
| GitHub | Versioning et suivi des modifications |
| Excel / Slack | Documentation et partage des campagnes |

## Structure du projet

    cypress/
    ├── e2e/            # Scénarios de test (parcours achat, devis, formulaires…)
    ├── fixtures/       # Jeux de données de test
    └── support/        # Commandes personnalisées et configuration
    cypress.config.js   # Configuration Cypress

## Lancer les tests

    # Installer les dépendances
    npm install

    # Ouvrir l'interface Cypress (mode interactif)
    npx cypress open

    # Lancer tous les tests en mode headless
    npx cypress run

## Couverture des tests

- Parcours d'achat : ajout au panier, tunnel de commande
- Devis : demande et validation de devis
- Listes : création et modification de listes de produits
- Formulaires : validation des champs, messages d'erreur
- Recommandations : affichage des produits suggérés

## Autrice

Soumia Sadki — QA Analyst & future Product Owner
https://www.linkedin.com/in/soumia-sadki/
