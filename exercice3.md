1 : cat etc/passwd.

2 : chmod 744 myfile

3 : pour ignorer les fichier pdf lors du push

  * créer un fichier gitignore dans le depot Git local
  * editer le fichier gitignore 
  
  * #ignorer les fichiers pdf
    
    *.pdf 

4 : Quelles commandes git utiliser pour fusionner les branches main et test_valide

* git checkout main
* git merge test_valide

5:  Donne la(les) ligne(s) de commande(s) bash pour afficher le texte suivant :

. # Malgré le prix élevé de 100$, il a dit "Bonjour !" au vendeur :
- echo "Bonjour est-ce que ce clavier fonctionne bien ?"
- echo "Evidemment ! On peut tout écrire avec, que ce soit des pipe | ou bien des backslash \\ !"
- echo "Même des tildes ~ ?"
- echo "Evidemment !"

 6 : Il faut utiliser la commande fg suivi du numero du job
 
 fg %1

 7 : matériels réseaux sont sur la couche 2 et la couche 3 du modèle OSI et leurs spécificités.
 
 #### la couche 2 est la couche liaison de données
 
-elle gère les méthodes d’accès au média, gère le contrôle d’erreurs.

  #### materiels couche 2.:

  * les commutateurs (switchs) segmentent le reseau et transmettent les données grace aux adresses MAC pour leur acheminement(des données).
  * les ponts permettent de relier des reseaux physiques differents.
  * les cartes reseaux sont l'interface entre votre ordinateur et le réseau. Elle reçoivent les données émises par l'ordinateur et les transfèrent vers un autre appareil présent sur le réseau, contrôlent l'ensemble de ces données et les flux échangés.

#### la couche 3 est la couche reseau

elle permet le routage et l'interconnexion de reseaux differents
  
 #### materiels couche 3

* les routeurs acheminent les paquets de donnéées entres les reseaux en utilisants les adresses ip et de protocoles de routage.ils créent et gerent des tables de routages pour determiner le meilleur chemin pour les données.

 8 : Quels sont les équivalent PowerShell des commandes bash cd, cp, mkdir, ls.

  * cd   :  set-Location 
  * cp   :  copy-Item
  * mkdir : New-Item
  * ls   : Get-ChildItem

9 : Dans la trame ethernet, qu'est-ce que le payload?

 C'est l'ensemble des données encapsulées entre l'en-tête et la fin de la trame, qui sont à transporter entre les systèmes.
 C'est la charge utile,Il peut contenir des paquets IP, des trames ARP, selon le type de communication en cours.
 il contient l'information que les utilisateurs doivent réellement envoyer et recevoir.
 
 
10 : Pourquoi les classes IP sont remplacées par le CIDR ?

c'est pour une  meilleure utilisationet gestion  des Adresses IP en IPV4.
CIDR permet de diviser les blocs d'adresses en sous-réseaux plus petits,permettant aiisi une plus grande exploitation et moins de gaspillage des adresses des IPV4

   

    

