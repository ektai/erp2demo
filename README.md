## Tiers Lieux

Site de démonstration pour les tiers lieux.

Pour réinitialiser la démo, lancez la commande:

```
bench --site {site} demo-tierslieux --{option} {valeur}
```

#### Options

- `reinstall`: Réinstaller le site avant d'installer les données.  
  Aucune valeur associée.
- `days`: Nombre de jours à simuler.  
  Nombre entier.
- `resume`: Lancer une simulation sans réinstaller les données de base.  
  Aucune valeur associée.
- `admin-password`: Mot de passe administrator
- `mariadb-root-username`: Nom d'utilisateur _root_ de la base de données
- `mariadb-root-password`: Mot de passe _root_ de la base de données

#### Clés d'environnement
Vous pouvez ajouter les clés suivantes dans `site_config.json` ou `common_site_config.json` pour activer les fonctionnalités associées.

- `stripe-public-key`: Clé publique Stripe (Compte de test)
- `stripe-secret-key`: Clé privée Stripe (Compte de test)
- `gocardless-token`: Jeton GoCardless (Compte de test)

#### License

GNU GPLv3