# Portfolio MATV

Site portfolio de MATV, recréé dans [Revel](https://github.com/matv-studio/Revel) d'après
https://matv.framer.website : à ouvrir dans Revel (« Ouvrir un site » sur ce dossier), où tout se modifie
depuis l'interface.

| Fichier ou dossier | Rôle |
|---|---|
| `site.revel.json` | Le site : accueil, gabarit des projets, composants (bouton, chiffre, service, outils, parcours, classement, carte de projet…), couleurs claires et sombres, styles |
| `content/` | Projets (anglais, et français dans `content/fr/`) |
| `.pages.yml` | Champs de la collection des projets (compatible Pages CMS) |
| `media/` | Images, vidéos des projets, polices |

Générer le site sans l'interface : `revel build . --out _site`.
