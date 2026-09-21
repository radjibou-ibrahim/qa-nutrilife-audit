# 01 — Test Scope

## 1. Objectif

L'objectif de cet audit QA est d'effectuer une vérification ciblée de NutriLife afin d'identifier d'éventuels problèmes fonctionnels, comportements inattendus ou points pouvant affecter l'expérience utilisateur.

L'audit est réalisé dans le cadre d'une première session de **QA Testing**.

## 2. Périmètre de test

L'audit couvre les quatre domaines suivants :

### 2.1 Registration & Onboarding

Vérification du parcours initial de l'utilisateur :

- Registration
- Login
- Configuration initiale du profil
- Navigation entre les étapes
- Validation des informations saisies

### 2.2 Meal Planning

Vérification du parcours de création d'un premier plan alimentaire :

- Création du plan
- Sélection des préférences
- Génération du plan
- Navigation
- Modification des informations lorsque disponible

### 2.3 Grocery List

Vérification de la liste de courses :

- Génération de la liste
- Cohérence avec le plan alimentaire
- Navigation
- Consultation et utilisation de la liste

### 2.4 Exploratory Testing

Une session d'**Exploratory Testing** sera réalisée afin d'identifier des comportements qui pourraient ne pas être couverts par les vérifications précédentes.

Une attention particulière sera portée à :

- Navigation
- Boutons et liens
- Champs de formulaire
- Cas limites simples
- Comportements inattendus
- Messages d'erreur

## 3. Types de tests

Les principaux types de tests utilisés sont :

- Functional Testing
- Exploratory Testing
- Positive Testing
- Negative Testing
- Basic Boundary Testing

## 4. Hors périmètre

Les éléments suivants ne sont pas inclus dans cet audit :

- API Testing
- Performance Testing
- Security Testing
- Automation Testing
- Tests approfondis de compatibilité multi-navigateurs
- Tests de charge
- Tests d'accessibilité approfondis

## 5. Livrables

À l'issue de l'audit, les résultats seront synthétisés dans :

- Test Execution
- Bug Reports, si des anomalies sont confirmées
- QA Summary

## 6. Limites de l'audit

Cet audit constitue une **QA review ciblée** et ne représente pas une validation exhaustive de l'ensemble de l'application.

Les résultats et conclusions sont limités aux fonctionnalités et comportements effectivement testés pendant la session.
