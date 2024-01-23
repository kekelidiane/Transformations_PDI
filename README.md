# Transformations_PDI
## Installation de Pentaho Data Integration
- Telecharger le fichier zip d'installation en ligne
- Decompresser le fichier
- Excecuter le fichier Spoon.bat (sur Windows)
- Admirer l'interface de PDI

## Creation des transformations
- Cliquez sur l'onglet fichier
- Sélectionnez Nouveau > Transformation
- Enregistrez le fichier de transformation dans le dossier spécifié
- Dans la partie gauche, cliquez sur "Palette de creation"
- Recherchez les tranformations à l'aide des mots clés
- Une fois trouvée, faites glisser la transformation dans la grande surface à droite

## Creation des connexions
- Ouvvrez ou créez une transformation
- Demarrez votre serveur MySQL
- Cliquez sur l'onglet fichier
- Sélectionnez Nouveau > Connexion BDD
- Spécifiez le nom de la connexion dans la premiere barre de saisie
- Choisissez MySQL dans la partie "Connection type"
- Remplissez les parametres:
      . Host name: localhost (comme d'habitude)
      . Database name: "nom de la base de donnée que vous avez préalablement créée"
      . Username: root (sauf si vous l'avez modifié)
      . Password: "" (sauf si vous l'avez modifié)
- Cliquez sur tester et vous recevrez un message de confirmation
- Cliquez sur Ok

## Exécution des tranformations
- Cliquez sur le bouton "Run" ou "Exécuter" en forme d'un triangle renversé
- Cliquez sur Démarrer
- Vous verrez des messages tout bleu si cela a marché et avec des rouges au cas contraire


## Autres
Les fichiers utilisés dans les transformations sont dans le dossier ETL join au dépôt. Le sujet de l'activité aussi.
