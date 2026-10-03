# Espace Rawaa Llaarousa — site web

```
rawaa/
├── index.html      la page
├── css/styles.css  couleurs, polices, mise en page
├── js/main.js      menu, filtres du lookbook, agrandissement des photos, reel, formulaire
└── images/         les 11 photos (optimisées)
```

## Voir le site
Double-cliquez sur `index.html`. Le reel Facebook et la carte ne s'affichent qu'une fois le site en ligne.

## Informations utilisées (page Facebook)
- Téléphone : 58 303 412 (Fadhila Salhi)
- Adresse : à côté de l'école primaire, municipalité d'Echraya, 1251 Sbeitla
- Messenger : https://m.me/61566683417219

## À vérifier
- **WhatsApp** : le formulaire envoie la demande sur WhatsApp au 58 303 412. Si ce numéro n'a pas WhatsApp, videz `WHATSAPP_NUMBER` en haut de `js/main.js` (`""`) : la demande sera alors copiée et Messenger s'ouvrira.
- **Carte** : elle cherche « Echraya, Sbeitla, Tunisie ». Pour un point exact, remplacez le texte après `q=` dans l'iframe de la carte (section CONTACT de `index.html`), par exemple par des coordonnées GPS `35.2,9.1`.

## Vidéo
Le reel https://www.facebook.com/reel/1013256545084346 est intégré. Pour le changer, remplacez `FACEBOOK_REEL` en haut de `js/main.js` et le lien du bouton « Regarder sur Facebook » dans `index.html`.

## Photos
Le début du nom de chaque photo indique sa catégorie : `mariee-…`, `tradition-…` / `tenue-…` (Tradition), `soiree-…` / `caftan-…` (Soirée).

## Mise en ligne
Glissez le dossier sur https://app.netlify.com/drop (gratuit), ou publiez-le sur GitHub Pages / tout hébergeur.
