# SR SERVICES — prototype mobile

Interface web progressive (PWA) en français, conçue pour téléphone, tablette et ordinateur.

## État actuel
- Interface responsive et navigation de démonstration.
- Aperçu Administrateur / Employé / Client.
- Actions simulées pour pointage, rapports et messages.
- Manifeste PWA et cache hors ligne de base.

## Important
Cette version **n'est pas encore connectée à Supabase**. Les exemples sont fictifs; aucun compte, pointage, message, rapport, photo, adresse ou donnée financière n'est réellement enregistré. N'utilisez pas cette démo pour des données de clients.

## Déploiement
Activez GitHub Pages dans **Settings → Pages**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`. Après le déploiement, ouvrez l'adresse GitHub Pages en HTTPS sur votre téléphone puis utilisez le menu du navigateur **Ajouter à l'écran d'accueil**.

## Prochaines étapes
1. Vérifier et sécuriser le schéma Supabase existant.
2. Mettre en place l'authentification et les rôles avec politiques RLS.
3. Ajouter stockage privé pour les photos avant/après.
4. Connecter clients, planning, pointage, rapports et messagerie.
5. Ajouter Google Maps et QuickBooks Online après configuration sécurisée.

Ne placez jamais de clé Supabase `service_role`, mot de passe ou jeton secret dans le dépôt. Le dépôt est actuellement public; passez-le en privé si vous ne souhaitez pas publier le code.