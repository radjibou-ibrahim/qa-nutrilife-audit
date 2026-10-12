# 02 — Test Checklist

## Objectif

Cette checklist définit les vérifications prévues pendant le QA Audit de NutriLife.

> **Traçabilité à compléter :** le QA Summary du dépôt rapporte 18 tests exécutés, tous PASS. Les statuts ci-dessous reprennent ce résultat agrégé. Le dépôt ne contient toutefois pas encore de résultats détaillés ni de preuves par test permettant d'auditer indépendamment chaque PASS. Voir `03-Test-Execution.xlsx`.

## 1. Registration & Onboarding

| ID | Vérification | Résultat rapporté |
|---|---|---|
| TC-001 | Créer un compte avec des informations valides | PASS* |
| TC-002 | Vérifier la validation des champs obligatoires | PASS* |
| TC-003 | Vérifier le comportement avec une adresse email invalide | PASS* |
| TC-004 | Vérifier le parcours d'Onboarding avec des informations valides | PASS* |
| TC-005 | Vérifier la navigation entre les différentes étapes de l'Onboarding | PASS* |

## 2. Meal Planning

| ID | Vérification | Résultat rapporté |
|---|---|---|
| TC-006 | Créer le premier plan alimentaire | PASS* |
| TC-007 | Vérifier la prise en compte des préférences alimentaires | PASS* |
| TC-008 | Vérifier la génération du plan alimentaire | PASS* |
| TC-009 | Vérifier la navigation après la génération du plan | PASS* |
| TC-010 | Vérifier la modification d'une information du plan lorsque disponible | PASS* |

## 3. Grocery List

| ID | Vérification | Résultat rapporté |
|---|---|---|
| TC-011 | Générer la Grocery List à partir du plan alimentaire | PASS* |
| TC-012 | Vérifier la cohérence entre le plan et la Grocery List | PASS* |
| TC-013 | Vérifier l'affichage des éléments de la Grocery List | PASS* |
| TC-014 | Vérifier la navigation et l'utilisation de la Grocery List | PASS* |

## 4. Exploratory Testing

| ID | Vérification | Résultat rapporté |
|---|---|---|
| TC-015 | Vérifier les principaux boutons et liens | PASS* |
| TC-016 | Tester quelques champs avec des valeurs inhabituelles ou limites | PASS* |
| TC-017 | Vérifier les comportements après une action répétée ou inattendue | PASS* |
| TC-018 | Vérifier les messages d'erreur et comportements inattendus | PASS* |

## Signification des statuts

- **PASS** — vérification exécutée et résultat conforme, avec résultat réel traçable.
- **FAIL** — comportement incorrect reproduit et confirmé.
- **BLOCKED** — test impossible à effectuer.
- **N/A** — fonctionnalité non disponible ou non applicable.
- **PASS*** — PASS rapporté dans le QA Summary, mais résultat réel détaillé et preuve encore absents du dépôt.

## Action requise avant publication du portfolio

Remplacer progressivement chaque `PASS*` par un statut final après récupération/validation des notes d'exécution, des résultats réels et, si possible, des captures d'écran. Ne pas présenter le symbole * comme une anomalie de l'application : il indique une limite documentaire du portfolio.
