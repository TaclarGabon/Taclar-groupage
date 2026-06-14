[README.md](https://github.com/user-attachments/files/28922332/README.md)
# TACLAR Groupage V12.5.2.4 — Version finale Admin

## Versions par module
- Chauffeur : V12.5.2.3
- Admin : V12.5.2.4
- Dispatch : V12.5.1
- Portal : V12.4.0

## Fichiers à remplacer
- `admin.html`
- `README.md`

## Fichiers à conserver
- `index.html`
- `dispatch.html`
- `portal.html`

## Corrections incluses

### Admin
- Écran Admin élargi pour améliorer la lecture du tableau.
- Colonne Action mieux recadrée.
- Nouveau bouton : `Sauvegarder tout Excel`.
- Possibilité de sauvegarder toutes les sessions en attente en une seule action.
- Les sessions sauvegardées passent en statut vert.
- Suppression toujours bloquée tant que la session n’est pas sauvegardée.

### Excel
- Ordre des onglets corrigé :
  1. `Sessions`
  2. `Résumé`
- Onglet Sessions en premier pour ouvrir directement sur le registre détaillé.
- Onglet Résumé en second pour consulter les totaux par jour.
- Commission TACLAR conservée à 25%.
- Dates conservées au format francophone : JJ/MM/AAAA.
- ID Session conservé au format : TAC-AAAAMMJJ-001, 002, 003...

## À tester
1. Admin : vérifier que le tableau est plus lisible.
2. Admin : cliquer sur `Sauvegarder tout Excel`.
3. Vérifier que toutes les lignes en attente deviennent sauvegardées.
4. Télécharger le registre Excel.
5. Vérifier que l’onglet `Sessions` apparaît avant `Résumé`.
6. Vérifier que la suppression reste possible uniquement après sauvegarde Excel.
