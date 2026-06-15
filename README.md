[README.md](https://github.com/user-attachments/files/28941475/README.md)
# TACLAR Groupage — V12.6.0

## Objet

Sécurité locale simple avec rôles et codes fixes.

## Codes d'accès

- Direction TACLAR : 0512
- Admin : 1111
- Dispatch : 2222
- Chauffeur : 3333

## Accès

- Direction TACLAR : Chauffeur + Dispatch + Admin
- Admin : Admin uniquement
- Dispatch : Dispatch uniquement
- Chauffeur : Chauffeur uniquement

## Versions par module

- Portal : V12.6.0
- Chauffeur : V12.6.0
- Dispatch : V12.6.0
- Admin : V12.6.0

## Fichiers à remplacer

- portal.html
- index.html
- dispatch.html
- admin.html
- README.md

## Ce qui n'a pas été modifié

La logique métier reste inchangée :

- sièges chauffeur
- clôture avec motifs
- contrôle de caisse
- justification “Autre”
- sessions masquées / réafficher
- export Excel
- commission 25 %
- sauvegarde Excel sécurisée

## Prochaine étape

V12.6.1 : Direction TACLAR pourra modifier les codes depuis l'application.

V13.0.0 : Firebase Authentication et comptes utilisateurs cloud.
