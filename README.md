Petit tools pour pouvoir manipuler rapidement des données dialogflow.


1 - Lire le fichier excel
  1- Extraire les intents
  2- Extraire les training phrases
  3- Extraire les simples responses
  4- Extraire les suggestions
  5- Extraire les training phrases

2 - Ecrire un fichier json
  1- Mettre les différentes informations, extraites dans la tache 1
  2- Rajouter des informations comme la data (AAAA:MM:DDThh:mm:ss)
  3- rajouter un numéro unique (ID)
  4- rajouter un numéro de version en plus de l'ID

3 - Faire un requête sur dialogflow
  1- Créer un intent
    a- Le nom
    b- Le(s) context(s) en entré
    c- Le(s) context(s) en sortie
  2- Changer l'état de l'intent
    1- Activé
    2- Désactiver
    3- Modifier le priorité
  3- Ajouter une entité
    1- Activer l'option "Required"
    2- Désactiver l'option "Required"
    3- Rajouter un prompt
    4- Activer l'option "List"
    5- Désactiver l'option 'List'
  4- Récupérer les training phrases
  5- Ajouter un training phrase qui se trouve dans le fichier excel

4- Mettre à jour le Datastore
  1- Créer un kind dans une table
  2- Rechercher un kind
  3- Mettre à jour un kind
  4- Supprimer un kind

5- Réaliser des requête HTTP sur le proxy-front
  1- Avoir un id utilisateur, pour être connecté en tant que
    a- Manager
    b- Collaborateur
    c- Default
  2- Récupérer les contexts
    a- Savoir les context en input
    b- Savoir les context en output
  2- Pouvoir enchainer un scénario

6- Définir une architecture
  1- sur les fichiers
    a- root- > name-intent(dossier) -> date(AAAA:MM:DDThh:mm:ss)(fichier).json
  2- Scénario
    a- root -> tests -> scénario -> scenario-name_version_date(AAAA:MM:DDThh:mm:ss)(fichier).json
  3- Command-line ??
