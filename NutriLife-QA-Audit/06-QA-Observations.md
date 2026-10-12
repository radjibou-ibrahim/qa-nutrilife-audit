# 06 — QA Observations

## Objectif

Ce document conserve les observations UX rapportées pendant l'audit. Elles ne sont pas considérées comme des bugs confirmés faute de résultats détaillés et de preuves disponibles dans le dépôt.

## Observations à revalider

| ID | Zone | Observation rapportée | Impact potentiel | Recommandation de suivi | Statut |
|---|---|---|---|---|---|
| OBS-001 | Pages à forte densité | Densité importante d'informations sur certaines pages | Compréhension et lecture potentiellement plus difficiles | Identifier les écrans concernés et vérifier la hiérarchie visuelle avec captures | À revalider |
| OBS-002 | Scanner | Délai perceptible lors de l'utilisation du Scanner | Perception de lenteur ou incertitude sur l'état de l'action | Mesurer le délai avec plusieurs essais et noter les conditions ; ne pas conclure à un bug de performance sans mesures | À revalider |
| OBS-003 | Menu généré | Visibilité du menu généré pouvant être améliorée | L'utilisateur peut avoir du mal à repérer le résultat | Capturer l'écran concerné et formuler une recommandation UI précise | À revalider |
| OBS-004 | Feedback et erreurs | Feedback/messages d'erreur jugés limités dans certains cas | L'utilisateur peut ne pas comprendre le résultat d'une action | Identifier l'action, le message attendu et le message observé | À revalider |
| OBS-005 | Grocery List | Personnalisation de la liste de courses potentiellement améliorable | La liste peut être moins adaptée au besoin de l'utilisateur | Clarifier le comportement actuel et proposer une amélioration distincte d'un bug | À revalider |

## Règle de qualification

- **Bug** : écart reproductible entre le résultat réel et attendu.
- **Observation UX** : point d'utilisabilité ou piste d'amélioration qui n'implique pas nécessairement un dysfonctionnement.
- **Performance** : un délai perçu est une observation ; une conclusion chiffrée exige des mesures reproductibles.

## Action requise

Pour chaque observation, compléter la capture, la page ou le parcours concerné, les étapes pour retrouver le comportement et la recommandation exacte. Modifier le statut seulement après revalidation.
