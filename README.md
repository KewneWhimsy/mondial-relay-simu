# Simulateur de frais Mondial Relay — Offre Start

Outil interactif pour estimer les frais de livraison Mondial Relay et calculer les prix à appliquer à sa boutique.

**[Ouvrir le simulateur](https://kewnewhimsy.github.io/mondial-relay-simu/)**

## Utilisation

Ouvrir `index.html` dans un navigateur — aucune installation, aucune connexion requise.

### Paramètres disponibles

- **Mode de tarification** : prix calculé automatiquement ou prix fixe par tranche
- **Marge de sécurité** : pourcentage ajouté pour couvrir les imprévus
- **Arrondi** : exact, au 0,50 € ou à l'euro supérieur
- **TVA** : avec ou sans TVA 20% sur les frais de port
- **Mode de livraison** : point relais ou domicile
- **Volume mensuel** : palier de remise selon le nombre de colis envoyés par mois

Le tableau affiche les prix résultants pour chaque tranche de poids.

## Mise à jour des tarifs

Les tarifs Mondial Relay sont intégrés directement dans le fichier `index.html`. En cas de changement tarifaire, mettre à jour les données dans le tableau JavaScript correspondant.

## Technique

Un seul fichier HTML autonome : styles, scripts et polices sont tous intégrés. Aucune dépendance externe, aucun build nécessaire.
