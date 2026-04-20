# Organisation Scrum

## Rôles

| Rôle | Responsabilité |
|---|---|
| **Product Owner** | Porte la vision, priorise le backlog, valide les US livrées. Rôle tenu collectivement par le groupe. |
| **Scrum Master** | Anime les rituels, lève les blocages, protège l'équipe. Rôle tournant à chaque sprint. |
| **Dev Team** | Développe les US. Tous les membres du groupe. |

## Sprint

- **Durée : 2 semaines** (bon compromis feedback rapide / incrément utile, cf. cours)
- **Objectif de vélocité cible** : 15 à 20 points par sprint
- **Backlog projet** : ~52 points → environ **3 sprints**

## Rituels

| Rituel | Durée | Objectif |
|---|---|---|
| Sprint Planning | 1h en début de sprint | Choisir les US à embarquer |
| Daily | 10 min chaque jour | Qui fait quoi, quels blocages |
| Sprint Review | 30 min en fin de sprint | Démo au PO / client |
| Rétrospective | 30 min en fin de sprint | Ce qui a bien / mal marché |

## Definition of Done (DoD)

Une user story est **Done** quand :
- [ ] Code écrit et fonctionnel
- [ ] Tests passés (unitaires + fonctionnels)
- [ ] Critères d'acceptation cochés
- [ ] Pull Request review et approuvée par ≥ 1 membre
- [ ] PR mergée sur `main`
- [ ] Documentation mise à jour si besoin
- [ ] Démontrable en sprint review

## Règles d'équipe

- **1 issue = 1 branche** → `feature/US-X-nom-court`
- **Pas de push direct sur `main`** → tout passe par PR
- **PR liée à l'issue** (mention `Closes #X` dans la description)
- **≥ 1 reviewer** avant merge
- **Commits en anglais**, format impératif (`add login form`, `fix status filter`)
- **Déplacement sur le Project Board** en temps réel (Backlog → In Progress → In Review → Done)

## Cycle de vie d'une user story

```
Backlog → Ready → In Progress → In Review → Done
```

- **Backlog** : US créée, pas encore prête
- **Ready** : US raffinée, critères clairs, estimée
- **In Progress** : branche créée, dev en cours
- **In Review** : PR ouverte, attend validation
- **Done** : PR mergée, DoD respectée
