# TINA
Logiciel de ticketing

## Présentation

**TINA** (Ticket Incident Navigation Assistant) est une solution complète et intuitive pour la gestion des tickets d'incidents. Conçu pour simplifier le suivi et la résolution des problèmes, TINA vous permet de créer, gérer et suivre facilement vos tickets tout au long de leur cycle de vie.

Fonctionnalités clés :

- **Création et gestion des tickets** : Créez des tickets en quelques clics, affichez-les dans un tableau modifiable et gérez-les facilement avec des options de modification ou de suppression.
- **Filtrage avancé** : Utilisez la barre de recherche ou des filtres visuels sous forme de carrés de couleurs pour trier les tickets par état (nouveau, en cours, en attente, résolu).
- **Exportation des tickets** : Exporte facilement la liste complète des tickets avec toutes leurs informations associées pour un partage rapide ou une analyse plus poussée.
- **Statistiques détaillées** : Consultez des statistiques claires et concises sur vos tickets : nombre total, tickets par technicien ou prestataire, temps de résolution moyen, et répartition par catégorie.
- **Exportation des statistiques** : Vous pouvez exporter ces statistiques sous format CSV pour une analyse approfondie et un reporting personnalisé.
- **Gestion des utilisateurs** : Un bouton paramètres permet d'ajouter ou supprimer des auteurs, des techniciens et des prestataires pour un contrôle total sur les accès et les attributions de tickets.

TINA est l'outil idéal pour améliorer l'efficacité et la collaboration au sein de votre équipe en vous offrant une gestion centralisée et flexible de vos incidents.

## Installation
Télécharger le fichier *TINA_Setup.exe* et suivez les étapes d'installation.
Vous n'avez pas besoin d'un code administrateur pour l'installer sauf si vous souhaitez l'installer dans un répertoire nécessitant des droits administrateur.

## Créer un ticket
Pour créer un ticket, cliquez sur le bouton "*Créer un ticket*" situé en haut à gauche de l'application. 
Puis remplissez les champs : 

![image](https://github.com/user-attachments/assets/8173f801-940b-4548-ad7a-79dae77e5093)

Par défaut, lors du premier lancement de l'application :
- Les options "Directeur, Technicien, Utilisateur" sont créées dans le champ "Auteur",
- Les options "Technicien A, Technicien B, Technicien C" sont créées dans le champ "Assigné à",
- Les options "Presta 1, Presta 2, Presta 3" sont créées dans le champ "Saisie Prest.",

Les champs comportant un asterix rouge sont obligatoires.

Pour valider l'ajout du ticket, il vous suffit de cliquez sur "*Ajouter Ticket*".

![image](https://github.com/user-attachments/assets/89d671d9-6278-48e8-b170-edada470fff4)

## Supprimer ou modifier un ticket
Pour supprimer un ticket, cliquez sur le bouton avec la corbeille :

![image](https://github.com/user-attachments/assets/5f91155d-ff84-432a-85f3-39c077be0e28)

Si vous souhaitez modifier le ticket, cliquez sur le bouton avec le stylo.
Le formulaire d'ajout s'ouvrira mais avec les champs déjà complétés par les informations du ticket :

![image](https://github.com/user-attachments/assets/ed9c4365-12d7-410a-b922-04140706f222)

Vous pouvez ainsi modifier le technicien assigné au ticket, saisir une date de résolution avec une solution apportée ainsi que tous les autres champs.

## Statistiques

Pour afficher les statistiques de l'application, cliquez sur le bouon "Statistiques" en bas à droite de l'application.
*Note : Il se peut que lors de la première ouverture, la fenêtre mettre quelques secondes à s'ouvrir.*

![image](https://github.com/user-attachments/assets/0245ac4e-8e6f-41c4-9d62-d572ef607531)

Vous obtiendrez les statistiques suivantes :
- Nombre de ticket par status (nouveau, en cours, en attente, résolus),
- Tickets par technicien,
- Tickets par prestataire (le cas où vous auriez des prestataires externes afin de savoir s'ils sont utiles),
- Tickets par catégories avec la possibilité de l'afficher en graphique via votre navigateur,
- Temps de résolution moyen des tickets (s'il est résolu le jour même, il sera compter 0).

Vous pouvez exporter les statistiques au format CSV.

## Paramètres
Il est possible de supprimer les utilisateurs par défaut et d'en ajouter des nouveaux avec les paramètres d'application (bouton situé à côté des statistiques) :

![image](https://github.com/user-attachments/assets/ea873351-50ee-48c6-8682-914182f485a4)

Pour ajouter un auteur, un technicien ou un prestataire, il vous suffit de saisir le nom de la personne ou de l'entreprise dans le champ dédié et de cliquer sur le bouton "*Ajouter*".

Pour supprimer un auteur, un technicien ou un prestataire, il vous suffit de sélectionner la personne ou l'entreprise dans la liste déroulante correspondante et de cliquer sur "*Supprimer*".

