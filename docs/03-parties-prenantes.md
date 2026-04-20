# Parties prenantes

## Qu'est-ce qu'une partie prenante ?

Toute personne ou groupe ayant un intérêt dans le projet : qui décide, qui utilise, ou qui est impacté. Les oublier = blocages plus tard.

## Qui est concerné

| Acteur | Rôle |
|---|---|
| Direction générale | Finance le projet |
| DSI | Valide la technique et la sécurité |
| Équipe Data / IA | Conçoit la solution |
| Managers support | Pilotent les équipes terrain |
| Agents support | Utilisateurs finaux de l'IA |
| Clients finaux | Interagissent avec le chatbot |
| DPO / juridique | Conformité RGPD |
| Prestataire cloud / IA | Héberge la solution |

## Matrice pouvoir / intérêt

|  | **Intérêt faible** | **Intérêt fort** |
|---|---|---|
| **Pouvoir fort** | Satisfaire | Gérer étroitement |
| **Pouvoir faible** | Surveiller | Informer |

## Placement

| Acteur | Pouvoir | Intérêt | Case |
|---|---|---|---|
| Direction générale | Fort | Fort | Gérer étroitement |
| DSI | Fort | Fort | Gérer étroitement |
| Équipe Data / IA | Fort | Fort | Gérer étroitement |
| DPO / juridique | Fort | Moyen | Satisfaire |
| Managers support | Moyen | Fort | Informer |
| Agents support | Faible | Fort | Informer |
| Clients finaux | Faible | Moyen | Informer |
| Prestataire cloud | Moyen | Faible | Surveiller |

## Stratégie de gestion

- **Gérer étroitement** (Direction, DSI, Data/IA) → comité de pilotage mensuel, point technique hebdo, équipe IA intégrée aux daily Scrum.
- **Satisfaire** (DPO) → 3 revues de conformité (avant dev, avant tests, avant prod). Validation bloquante.
- **Informer** (managers, agents, clients) → démos en fin de sprint, ateliers utilisateurs, communication client avant déploiement.
- **Surveiller** (prestataire cloud) → suivi contractuel, SLA, factures.

## Point d'attention

Les **agents support** ont un fort intérêt mais peu de pouvoir → risque de résistance au changement. On les implique dès le sprint 2 via ateliers de co-construction pour transformer ce risque en levier d'adoption.
