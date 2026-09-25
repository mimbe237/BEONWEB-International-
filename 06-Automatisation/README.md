# Lot 6 — CRM, automatisation et sécurité

## Schéma CRM minimal

Compte : identifiant, pays, secteur, langue, responsable.  
Contact : coordonnées professionnelles nécessaires, fonction, préférence de contact.  
Opportunité : étape, besoin, montant estimé, devise, date cible, prochaine action.  
Projet : contrat, périmètre, jalons, livrables, recette, support.

## Automatisations à tester avant activation

- Nouveau prospect qualifié → affectation d'un responsable et tâche de suivi.
- Proposition acceptée → vérification du contrat et de l'acompte avant création du projet.
- Jalon approchant → rappel au responsable ; jamais une promesse automatique au client sans contrôle.
- Recette validée → préparation de la facture finale selon procédure comptable.

## Mesures de sécurité

Authentification multifacteur, comptes nominatifs, accès par rôle, sauvegardes et tests de restauration, journal des actions sensibles, retrait rapide des accès, interdiction de placer mots de passe et données clients dans les dépôts GitHub. Documenter la base juridique des traitements et la durée de conservation des données.
