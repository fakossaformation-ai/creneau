# Créneau

L'application de prise de rendez-vous du Salon Fatou, salon de coiffure à Villeurbanne, tenu par une seule personne.

Les clients regardent les créneaux libres, créent un compte ou se connectent, réservent un créneau d'une heure dans
les deux semaines à venir en laissant leur nom, leur téléphone et le motif, et retrouvent leurs rendez-vous à chaque
connexion pour les annuler. Fatou, la coiffeuse, se connecte sur la même application : elle voit les rendez-vous de tous
ses clients, avec leurs téléphones.

Les rendez-vous vivent dans une base de données Supabase. L'application est prête : il lui manque la base.

## Relier l'application à votre base

Renseignez dans `reglages.js` l'adresse de votre projet Supabase et sa clé publique. Publiez le dépôt avec GitHub
Pages, ou ouvrez `index.html` dans un navigateur : il n'y a rien à installer.

## Avant de construire la base de données

- `entretien.md` : nos notes de l'entretien avec Fatou, la coiffeuse. Ce qu'elle veut, les règles de ses
  rendez-vous, qui voit quoi, et ce qu'on ne fait pas. C'est à partir d'elles qu'on dessine la base.

## Organisation du code

| Fichier | Rôle |
|---|---|
| `reglages.js` | l'adresse et la clé publique du projet Supabase |
| `logique.js` | les échanges avec la base : comptes, planning, réservation, annulation. Aucun affichage. |
| `client.js` | l'affichage et les interactions de l'application |
| `style.css` | la présentation |
| `index.html` | la structure de l'application |
| `entretien.md` | ce que la base de données doit contenir |
| `correction-schema/schema-de-la-base.md` | le schéma de la base que l'application attend : la réponse, à n'ouvrir qu'une fois sa base dessinée |
