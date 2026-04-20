# Module d'authentification — US-1

## Objectif

Mettre en place l'authentification SSO pour les agents support (OAuth2 / SAML).

## Critères d'acceptation

- [ ] Connexion via identifiants entreprise
- [ ] Sessions expirent après 8h d'inactivité
- [ ] Accès journalisés (qui, quand, depuis où)
- [ ] Message d'erreur clair si non autorisé
- [ ] Logout invalide la session côté serveur

## Architecture prévue

```
Agent → Front (React) → API Gateway → Provider SSO (Azure AD)
                                    ↓
                              Session Store (Redis)
```

## Endpoints prévus

| Méthode | Endpoint | Rôle |
|---|---|---|
| POST | `/auth/login` | Initie le flow SSO |
| GET | `/auth/callback` | Callback provider |
| POST | `/auth/logout` | Détruit la session |
| GET | `/auth/me` | Infos utilisateur courant |

## Statut

Placeholder initial — structure du module mise en place pour démarrer le développement sur la branche `feature/US-1-authentification`.
