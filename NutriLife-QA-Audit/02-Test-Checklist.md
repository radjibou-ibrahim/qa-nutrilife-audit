# 02 — Test Checklist

## Objectif

Cette checklist définit les vérifications à effectuer pendant le **QA Audit** de NutriLife.

L'objectif est de couvrir rapidement les principaux parcours utilisateurs et d'identifier les éventuels bugs ou comportements inattendus.

---

## 1. Registration & Onboarding

| ID | Vérification | Résultat |
|---|---|---|
| TC-001 | Créer un compte avec des informations valides | Not Run |
| TC-002 | Vérifier la validation des champs obligatoires | Not Run |
| TC-003 | Vérifier le comportement avec une adresse email invalide | Not Run |
| TC-004 | Vérifier le parcours d'Onboarding avec des informations valides | Not Run |
| TC-005 | Vérifier la navigation entre les différentes étapes de l'Onboarding | Not Run |

---

## 2. Meal Planning

| ID | Vérification | Résultat |
|---|---|---|
| TC-006 | Créer le premier plan alimentaire | Not Run |
| TC-007 | Vérifier la prise en compte des préférences alimentaires | Not Run |
| TC-008 | Vérifier la génération du plan alimentaire | Not Run |
| TC-009 | Vérifier la navigation après la génération du plan | Not Run |
| TC-010 | Vérifier la modification d'une information du plan lorsque disponible | Not Run |

---

## 3. Grocery List

| ID | Vérification | Résultat |
|---|---|---|
| TC-011 | Générer la Grocery List à partir du plan alimentaire | Not Run |
| TC-012 | Vérifier la cohérence entre le plan et la Grocery List | Not Run |
| TC-013 | Vérifier l'affichage des éléments de la Grocery List | Not Run |
| TC-014 | Vérifier la navigation et l'utilisation de la Grocery List | Not Run |

---

## 4. Exploratory Testing

| ID | Vérification | Résultat |
|---|---|---|
| TC-015 | Vérifier les principaux boutons et liens | Not Run |
| TC-016 | Tester quelques champs avec des valeurs inhabituelles ou limites | Not Run |
| TC-017 | Vérifier les comportements après une action répétée ou inattendue | Not Run |
| TC-018 | Vérifier les messages d'erreur et comportements inattendus | Not Run |

---

## Résultats possibles

Chaque vérification sera classée selon l'un des statuts suivants :

- **PASS** — comportement conforme au résultat attendu
- **FAIL** — comportement incorrect ou anomalie confirmée
- **BLOCKED** — test impossible à effectuer
- **N/A** — fonctionnalité non disponible ou non applicable

## Règle de documentation

Lorsqu'un **FAIL** est identifié, l'anomalie sera vérifiée une seconde fois avant d'être considérée comme un bug confirmé.

Les bugs confirmés seront documentés séparément dans :

`04-Bug-Reports.md`

Chaque bug comprendra, lorsque pertinent :

- Bug ID
- Titre
- Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Evidence
