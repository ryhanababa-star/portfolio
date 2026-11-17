# Portfolio – Ryhanatou BABA

Site statique, sans étape de build, déployé sur Vercel : https://ryhanatou-baba.vercel.app

- `index.html` contient les deux langues : bloc `.lang-fr` et bloc `.lang-en` (ids suffixés `-en`). Le bouton FR/EN bascule sans recharger ; `/en` redirige vers `/#en`.
- Toute modification de contenu se fait **dans les deux blocs**.
- Projets : blocs JSON `projets-data` (FR) et `projets-data-en` (EN), même ordre ; images à la racine.
- Formulaire de contact : Web3Forms. Remplacer `VOTRE_CLE_WEB3FORMS` par la clé reçue par e-mail.
