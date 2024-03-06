# GITHUB adherent_par_quartier_parmi_20
TEST AVEC FICHIER ADRESSES ADHERENTS POUR LEQUEL IL FAUT AJOUTER LE QUARTIER 

EN ENTREE : 
fichier test_adherent.csv avec COLONNES Adherent,Adresse,Code postal,Commune pour confidentialité des données :-)
numero-de-rue-quartier.csv généré par autre prog python GITHUB rue_par_quartier_parmi_20

PREPARATION DES DONNEES :
- supprimer les caractètes accentués
- supprimer les ponctuations
- remplacer les abréviations par les mots entiers : BD, BLVD en BOULEVARD, puis ST en SAINT, etc
- mettre ne majuscule pour être au même format que le fichier de metropole Toulouse

EN SORTIE : 
fichier resultats.csv avec COLONNES Adherent,adresse,quartier