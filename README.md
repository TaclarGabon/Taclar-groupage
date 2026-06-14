[README.md](https://github.com/user-attachments/files/28921528/README.md)
# TACLAR Groupage V12.5.1

Version de finition après validation de V12.5.0.

## Composition officielle

- Portal : V12.4.0
- Chauffeur : V12.4.0
- Admin : V12.5.1
- Dispatch : V12.5.1

## Fichiers à remplacer

- admin.html
- dispatch.html
- README.md

## Fichiers à conserver

- index.html
- portal.html

## Corrections V12.5.1

### Admin
- ID Session corrigé au format TAC-AAAAMMJJ-001, 002, 003.
- Dates affichées au format français JJ/MM/AAAA.
- Colonne Durée ajoutée au registre Excel.
- Export Excel amélioré en fichier .xls avec mise en forme TACLAR.
- Boutons du tableau mieux recadrés.

### Dispatch
- Bouton Sessions masquées avec compteur : Sessions masquées (0), (1), (2)...
- Titre de la section masquée avec compteur.
- ID Session aligné avec le format officiel.

## À tester

1. Créer deux sessions dans la même journée.
2. Vérifier que les ID deviennent TAC-AAAAMMJJ-001 puis TAC-AAAAMMJJ-002.
3. Vérifier les dates au format JJ/MM/AAAA.
4. Masquer deux sessions dans Dispatch et vérifier le compteur.
5. Sauvegarder les sessions dans Admin puis télécharger le registre Excel.
