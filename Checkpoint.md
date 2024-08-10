# Checkpoint : Gestion de l'Etat dans React

## Ce que vous visez

**Développer une application de liste de tâches**

Description : Créez une application de liste de tâches simple à l'aide de React qui illustre divers aspects de la gestion des états. L'application doit permettre aux utilisateurs d'ajouter, de modifier, de supprimer et de marquer les tâches comme terminées. De plus, implémentez la validation de formulaire pour l'ajout/la modification de tâches et utilisez le stockage du navigateur pour conserver les tâches entre les sessions.

**Livrables :**
Une application React qui répond aux exigences décrites ci-dessous. (consultez les instructions)

* Le code doit être bien structuré, avec des composants séparés pour différentes parties de l'application (par exemple, TaskList, TaskForm, TaskItem).
* Incluez des commentaires dans le code pour expliquer le but de chaque composant et fonction.
* Fournissez un bref fichier **README.md** expliquant comment exécuter l'application localement et toute information ou considération supplémentaire.

## Instructions

* Mettre en place un formulaire pour ajouter de nouvelles tâches. Le formulaire doit inclure des champs de saisie pour le nom et la description de la tâche, et il doit effectuer une validation pour s'assurer que les deux champs sont remplis avant d'ajouter une tâche.
* Affichez la liste des tâches avec des options permettant de modifier, de supprimer et de marquer les tâches comme terminées. Les tâches terminées doivent être visuellement distinguées des tâches actives.
* Autoriser les utilisateurs à modifier les détails des tâches en cliquant sur la tâche. Mettre en place un formulaire pré-rempli avec les détails des tâches qui permet aux utilisateurs de mettre à jour le nom et la description de la tâche.
* Proposez une fonctionnalité permettant de supprimer des tâches de la liste. Incluez une invite de confirmation avant de supprimer une tâche.
* Implémentez le stockage du navigateur (localStorage ou sessionStorage) pour conserver les tâches entre les sessions. Assurez-vous que les tâches sont chargées à partir du stockage lorsque l'application s'initialise et enregistrées dans le stockage chaque fois qu'un changement se produit dans la liste des tâches.
* Stylisez l'application à l'aide de CSS pour la rendre visuellement attrayante et conviviale. Utilisez un style approprié pour mettre en évidence les tâches actives et terminées.
* Facultatif : implémentez des fonctionnalités supplémentaires telles que le filtrage des tâches en fonction de l'état d'achèvement, le tri des tâches par priorité ou par date d'échéance, ou l'ajout de dates d'échéance aux tâches.
