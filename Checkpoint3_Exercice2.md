Partie 1

Q.2.1.1 La commande est sudo adduser mindy, ensuite je créé le mot de passe du compte  
Q.2.1.2 Je préconise de lui donner les droits sudo: sudo usermod -aG sudo mindy


Partie 2

Q.2.2.1 La commande est nano /etc/ssh/ssh_config , dans le fichier je rajoute une ligne # PermitRootLogin no  
Q.2.2.2 Dans ce même fichier, je rajoute la ligne Allowusers mindy  


Partie 3
Q.2.3.1    
![1](https://github.com/mindysthm/Checkpoint3/blob/main/Capture%20d'%C3%A9cran%202025-01-17%20094215.png)

Q.2.3.2  Les types sont ext4 et ext2   
Q.2.3.3   

Partie 4 : Sauvegardes

Q.2.4.1 Le bareos dir supervise et planifie les sauvegardes et restaurations.  
Le bareos sd gère le stockage des données sur les supports de sauvegarde.  
Et le bareos fd est installé sur les ordinateurs clients pour envoyer les fichiers à sauvegarder vers le serveur.



Partie 6 : Analyse de logs
Q.2.6.1  
![4](https://github.com/mindysthm/Checkpoint3/blob/main/Capture%20d'%C3%A9cran%202025-01-17%20110825.png)
