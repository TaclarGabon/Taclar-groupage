[README.md](https://github.com/user-attachments/files/28922004/README.md)
# TACLAR Groupage V12.5.2.3

## Version corrective après tests V12.5.1

### Versions par module
- Chauffeur : V12.5.2
- Admin : V12.5.2
- Dispatch : V12.5.1
- Portal : V12.4.0

## Fichiers à remplacer
- `index.html`
- `admin.html`
- `README.md`

## Fichiers à conserver
- `dispatch.html` si la version V12.5.1 fonctionne déjà
- `portal.html`

## Corrections incluses

### Chauffeur
- Correction du clavier numérique de vérification caisse.
- Ajout de la saisie possible au clavier physique : chiffres, Backspace, Entrée, Échap.
- Après démarrage de session, la zone de saisie plaque / PIN / axe est masquée.
- Le chauffeur voit seulement la session active, le nom chauffeur et les sièges.

### Admin
- Commission TACLAR passée à 25%.
- ID Session corrigé au format séquentiel : TAC-AAAAMMJJ-001, 002, 003...
- Dates conservées au format francophone : JJ/MM/AAAA.
- Export Excel amélioré avec 2 onglets :
  - Résumé
  - Sessions
- Onglet Résumé : Jour, nombre de sessions, montant total, commission TACLAR.
- Onglet Sessions : registre détaillé des sessions.
- Recadrage amélioré de la colonne Action.

### Dispatch
- Aucune modification nécessaire si V12.5.1 fonctionne.
- Sessions masquées avec compteur déjà présentes.

## À tester
1. Chauffeur : démarrer une session, vérifier que plaque/PIN sont masqués après démarrage.
2. Chauffeur : clôturer une session et tester le clavier numérique.
3. Admin : vérifier que la commission est bien à 25%.
4. Admin : sauvegarder Excel et télécharger le registre.
5. Excel : vérifier les onglets Résumé et Sessions.


---

## Correctif V12.5.2.3

Module modifié :
- Chauffeur : V12.5.2.3

Fichiers à remplacer :
- index.html
- README.md

Fichiers à conserver :
- admin.html
- dispatch.html
- portal.html

Correction :
- Suppression du bloc "Dernières actions" côté chauffeur pour obtenir un écran compact après démarrage : sièges, Tous descendus, Info, Incident, Clôturer session.
