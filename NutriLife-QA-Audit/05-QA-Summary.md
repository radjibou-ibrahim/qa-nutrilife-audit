# QA Summary

## Application

**NutriLife** — Application web de planification des repas et de suivi de l'alimentation.

## Type d'audit

QA Audit ciblé — Functional Testing & Exploratory Testing.

## Environnement déclaré

- Browser : Chrome 152.0.7977.75
- Device : Android
- OS : Android 14
- Date de session indiquée dans le rapport initial : 21 septembre 2026

> Ces informations sont celles du rapport initial ; elles n'ont pas été vérifiées indépendamment pendant la revue documentaire du dépôt.

## Résultats rapportés

| Metric | Result |
|---|---:|
| Tests exécutés | 18 |
| PASS | 18 |
| FAIL | 0 |
| BLOCKED | 0 |
| Taux de réussite rapporté | 100 % |
| Bugs fonctionnels confirmés rapportés | 0 |

## Limite de traçabilité

Le dépôt ne contenait pas de véritable fichier d'exécution Excel : `03-Test-Execution.xlsx` ne faisait qu'un octet. Le classeur corrigé a été préparé pour enregistrer les statuts rapportés et signaler que les résultats réels détaillés restent à récupérer.

Le taux de réussite de 100 % est donc **le résultat agrégé rapporté dans cette documentation**, et non un résultat que la revue actuelle a pu reproduire à partir de preuves par test. Pour renforcer la crédibilité du portfolio, ajouter les notes d'exécution et les captures originales, puis confirmer chaque statut individuellement.

## Observations UX rapportées

- Densité importante d'informations sur certaines pages.
- Délai perceptible lors de l'utilisation du Scanner.
- Visibilité du menu généré pouvant être améliorée.
- Feedback et messages d'erreur limités dans certains cas.
- Possibilité d'améliorer la personnalisation de la Grocery List.

Ces éléments sont des observations UX rapportées, pas des bugs fonctionnels confirmés. Les détails, impacts et recommandations sont regroupés dans [06-QA-Observations.md](06-QA-Observations.md).

## Conclusion

Le rapport initial déclare que les 18 vérifications incluses dans le périmètre ont réussi et qu'aucun bug fonctionnel n'a été confirmé. La couverture documentaire est cependant incomplète : les éléments de preuve individuels doivent être ajoutés pour rendre les conclusions pleinement auditables.

Cet audit est limité aux fonctionnalités et scénarios déclarés dans le périmètre ; il ne constitue pas une certification exhaustive de l'application.
