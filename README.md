# EUR-TEST : Serious Game sur le Virus West Nile

Un serious game interactif pour sensibiliser au virus West Nile et évaluer les risques d'exposition à travers un questionnaire diagnostique.

## Description

Ce projet est un jeu sérieux (serious game) développé pour l'unité EUR (Enseignement Universitaire et Recherche) visant à éduquer les utilisateurs sur le virus West Nile. L'application pose une série de questions pour évaluer le niveau de risque d'exposition au virus et fournit des recommandations médicales appropriées.

## Fonctionnalités

- **Questionnaire interactif** : Questions progressives sur les facteurs de risque et symptômes
- **Système de scoring** : Évaluation automatique du niveau de risque (Faible, Moyen, Élevé)
- **Interface responsive** : Optimisée pour desktop, tablette et mobile
- **Multilingue** : Support français et anglais
- **Easter egg** : Mini-jeu avec moustiques pour engagement ludique
- **Navigation intuitive** : Possibilité de revenir en arrière dans le questionnaire
- **Liens utiles** : Redirections vers Doctolib, site d'information, vidéos pédagogiques et dons

## Technologies utilisées

- **Vue.js 3** : Framework JavaScript pour l'interface utilisateur
- **Tailwind CSS** : Framework CSS pour le styling responsive
- **HTML5** : Structure de base
- **JavaScript ES6+** : Logique applicative

## Compatibilité

- Navigateurs modernes (Chrome, Firefox, Safari, Edge)
- Responsive design pour tous les appareils
- Optimisé pour mobile (touch-friendly)

## Installation et utilisation

### Prérequis

- Un navigateur web moderne
- Connexion internet (pour les liens externes)

### Installation

1. Clonez ce repository :
   ```bash
   git clone [url-du-repo]
   cd EUR_Test_interactif
   ```

2. Ouvrez le fichier `index.html` dans votre navigateur :
   - Double-cliquez sur `index.html`
   - Ou utilisez un serveur local pour éviter les restrictions CORS

### Utilisation

1. **Page d'accueil** : Cliquez sur "COMMENCER" pour débuter le questionnaire
2. **Saisie du nom** : Entrez votre nom pour personnaliser l'expérience
3. **Questionnaire** : Répondez aux questions sur vos facteurs de risque et symptômes
4. **Résultats** : Consultez votre niveau de risque et les recommandations
5. **Actions** : Utilisez les liens pour prendre rendez-vous médical ou en savoir plus

## Easter Egg

Sur la page d'accueil, cliquez sur tous les moustiques pour déclencher un easter egg spécial !

## Logique du questionnaire

Le système de scoring évalue plusieurs facteurs :

- **Âge > 65 ans** : +1 point
- **Système immunitaire affaibli** : +2 points
- **Voyage dans zone à risque** : +3 points
- **Proximité avec eau stagnante** : +2 points
- **Absence de protection domicile** : +1 point
- **Piqûres de moustiques** : +1 point
- **Séjour en zone grise France** : +3 points
- **Symptômes** : Fièvre (+2), maux de tête (+1), douleurs musculaires (+1), fatigue (+1), éruption cutanée (+3), raideur nuque (+3), confusion (+4), durée >5 jours (+2)

**Niveaux de risque :**
- **0-5 points** : Probabilité faible
- **6-13 points** : À surveiller
- **14+ points** : Vigilance recommandée

## Structure du projet

```
EUR_Test_interactif/
├── index.html          # Application principale
├── README.md           # Ce fichier
└── [images]/           # Images utilisées (non incluses dans le repo)
    ├── image_acc.png
    ├── image_fond1.png
    ├── easter_egg.png
    ├── moustique.png
    └── carte.jpg
```

## Déploiement

L'application est entièrement statique et peut être déployée sur :
- GitHub Pages
- Netlify
- Vercel
- Tout serveur web statique

## Licence

Ce projet est développé dans le cadre d'un enseignement universitaire.

## Contribution

Pour contribuer :
1. Fork le projet
2. Créez une branche pour votre fonctionnalité
3. Committez vos changements
4. Poussez vers la branche
5. Ouvrez une Pull Request

## Support

Pour toute question ou problème, contactez l'équipe de développement.

---

**Disclaimer :** Cette application est à but éducatif uniquement et ne remplace pas un avis médical professionnel. En cas de symptômes, consultez immédiatement un médecin.
