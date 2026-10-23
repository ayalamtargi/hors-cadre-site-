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

## Aperçu de la refonte Archives (branche `refonte-editoriale-artistes`)
L'identité graphique principale est identique à la V1 d'origine. Les trois noms d'exposants et le sous-menu Pop-up restent présents, conformément aux demandes antérieures. **Seule la page Archives** change visuellement : deux doubles pages façon livre/photozine, texte et légendes superposés. La galerie 000 est une maquette utilisant provisoirement la photo existante `dist/assets/live.jpg`. Les photos exactes de la référence fournie dans la conversation doivent être importées et leurs droits vérifiés avant publication. Aucun achat réel ni déploiement.

## Dix nouvelles photographies — Archives

La branche de travail référence 10 fichiers WebP sous `dist/assets/archives/` : `IMG_1697.webp`, `IMG_6795.webp`, `IMG_6908.webp`, `IMG_6935.webp`, `IMG_6941.webp`, `IMG_7123.webp`, `IMG_7200.webp`, `IMG_7241.webp`, `IMG_7248.webp`, `IMG_7286.webp`.

Ces images ont été préparées depuis les 10 photos partagées dans la conversation dans une archive ZIP séparée `hors-cadre-archives-10-photos.zip`. **Les fichiers binaires ne sont pas encore présents sur GitHub** : les importer dans `dist/assets/archives/` pour remplacer automatiquement l'image de secours `dist/assets/live.jpg`. Dans l'interface de Github, ouvrir la branche `refonte-editoriale-artistes`, puis **Add file → Upload files** depuis le dossier `dist/assets/archives` à créer si nécessaire ; le ZIP doit d'abord être décompressé.

Les pages ont été reliées aux fichiers et le traitement éditorial conserve les couleurs et recadrages automatiques des images d'origine. Les photographies sont une sélection de démonstration et non des archives d'une édition tenue de l'événement fictif HORS CADRE. Vérifier crédits photographiques et autorisations des personnes avant diffusion publique.
