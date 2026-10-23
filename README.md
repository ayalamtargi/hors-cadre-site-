# HORS CADRE — prototype 001

Prototype statique en français, sans dépendance ni paiement. Aucune publication effectuée.

## Voir le site
Ouvrir `dist/index.html` dans un navigateur ou servir le dossier `dist` avec un serveur HTTP statique. Les liens utilisent des routes avec `#` : ils fonctionnent sans configuration serveur.

## Modifier
- `dist/data.js` : artistes, biographies, produits, prix, disponibilités et programme.
- `dist/app.js` : pages, textes pratiques, liens de billetterie et galeries.
- `dist/style.css` : identité graphique et adaptation mobile.
- `dist/assets/live.jpg` : photo d’ambiance Unsplash, pas une photo de l’événement.

Les visuels produits sont illustratifs et les archives 000 sont une démonstration. L’édition 001 affiche « Archives à venir ». Les boutons Acheter ouvrent une fenêtre de simulation ; aucun panier ni paiement n’est transmis.

## Choix V1
HTML/CSS/JavaScript natif pour une prévisualisation autonome, au lieu de la pile Next.js envisagée dans le cahier des charges. Aucune infrastructure commerciale. L’architecture peut ensuite être portée vers React/Next.js.

## Vérification
Syntaxe JavaScript vérifiée avec Node. Navigation, onglets et simulation d’achat vérifiés dans le navigateur. CSS responsive prévu à 760 px. Date et lieu restent à confirmer.

## Refonte éditoriale (branche `refonte-editoriale-artistes`)
- Logo de navigation agrandi, typographies Anton/Arimo/DM Mono, mise en page plus éditoriale.
- Menu Pop-up avec accès direct aux pages **ENFAN DE PALESTINE**, **BIDULES EYEWEAR** et **SIMPLELIFE**.
- Trois pages boutiques : produits entièrement fictifs, simulations d'achat uniquement, aucune affiliation ou vente réelle présumée.
- Archives présentées en journal photographique : édition 001 à venir, édition 000 galerie de démonstration.
- Les photographies, véritables produits et textes officiels sont à ajouter après validation des créateurs.

Pour prévisualiser cette version, servir `dist/` à l'aide d'un serveur statique local. Les changements de cette branche ne sont pas automatiquement publiés sur ChatGPT Sites ni sur un hébergement public.
