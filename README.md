
# LIVRAISON TOUSALON - Déploiement Automatique

## 🧰 Structure du projet

```
livraison-tousalon/
├── frontend/        # Application React avec Tailwind
├── backend/         # API Node.js avec Express
└── .github/
    └── workflows/   # CI/CD GitHub Actions
```

## 🚀 Déploiement Automatique sur Netlify

Chaque `git push` sur la branche `main` déclenchera :

- Compilation de `frontend/`
- Déploiement vers Netlify automatiquement

## 🔐 Secrets GitHub à configurer :

1. `NETLIFY_AUTH_TOKEN`
2. `NETLIFY_SITE_ID`

Ajoutez-les dans GitHub > Settings > Secrets > Actions

---

👉 Déposez ce dossier sur GitHub pour déclencher la CI automatiquement.
