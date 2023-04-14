**Nom :** Yanis Verdier
**Groupe :** B2 - Equipe 08
**Année :** 2023
**IUT Le Havre - Cours GIT**

# Compte-rendu TP3 Introduction GIT

Dans ce TP, on apprend à travailler avec github en équipe.  
À l'issue de la répartition des rôles, j'assume le rôle de Porthos.  

## 1. Inviter des collaborateurs dans un dépôt personnel
Mes collaborateurs m'invitent dans leurs dépôts respectifs.  
Je clone donc leur TP3 dans mon dossier personnel à l'aide de la commande `git clone git@github.com:Amaxi76/tp3.git` et `git clone git@github.com:Celiants/tp3.git`, Amaxi76 et Celiants étant mes collaborateurs.  

Je transfert les fichiers du tp2 dans le tp3 pour que mes collaborateurs procèdent au `git pull`, ce qui fonctionne.

## 2. Développement d'un projet java en équipe
Une fois que la synchronisation de nos dépôts tp3 est assurée, mes collaborateurs procèdent à l'ajout des fichiers .java dans le dépôt que je récupère avec un `git pull`.  
Les fichiers sont bien présents, je m'intéresse donc au code de Portefeuille.java et complète les méthodes incomplètes.  
En collaborant avec mes collaborateurs, nous nous transmettons les fichiers et finalement, le script de test fonctionne correctement.

## 3. Gérer des nouvelles fonctionnalités à l'aide des branches
Nous créons chacun la branche test avec la commande `git checkout -b test`.  
À l'aide du TP, nous comprenons que le fichier text.txt ajouté dans la branche test n'est pas apparant dans la branche main.  
Les deux branches séparent le dépôt, ce qui explique ce résultat.  
Avec la commande `git merge test`, nous fusionnons nos branches.  

Je créé ensuite ma branche personnelle 'UtaaBranch' pour créer ma cryptomonnaie, la UtaaCoin.  
Je fusionne ensuite ma branche avec la branche principale avec les commandes `git checkout main` suivie de `git merge UtaaBranch`.  
J'ai réussi à créer ma monnaie sans impacter la branche principale avant de terminer mon travail.