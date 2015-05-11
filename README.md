# gwap-d7-profile
Un profil de base pour toute nouvelle installation de Drupal 7 (inclut automatiquement les modules installés à chaque fois). Ce profil est utilisé sur tous les sites sous Drupal créés par Grisel Websites and Photography.

# Utilisation
1. Installer Drush 
2. Créer un fichier gwap-d7-profile.make dans /var/www/ et y ajouter les lignes suivantes:
core = 7.x

api = 2

projects[drupal][version] = "7.37"
projects[gwap][type] = "profile"
