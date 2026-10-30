# Page personnelle de Tinhinane Amina Azzouz

Site académique statique en anglais, préparé pour GitHub Pages et actualisé le 30 octobre 2026. L’archive comprend les quatre pages, le portrait repris de la page Google Sites, le CV PDF, sa source LaTeX et les références bibliographiques.

## Voir le site

Ouvrir `index.html` dans un navigateur après avoir extrait l’archive. Les liens entre les pages et le téléchargement du CV fonctionnent localement. Aucun compte, serveur, installation ou service tiers n’est nécessaire pour consulter ces fichiers.

## Publier sur GitHub Pages

Le compte personnel identifié est `Tinaamina`. Si c’est bien le compte choisi, le dépôt d’une page personnelle doit s’appeler `Tinaamina.github.io` et l’adresse sera `https://tinaamina.github.io/` après le premier déploiement réussi. Cette adresse est une destination proposée, pas une publication déjà effectuée.

1. Se connecter au compte GitHub qui doit posséder le site.
2. Créer un dépôt public nommé `Tinaamina.github.io` si le compte choisi est `Tinaamina`. Pour un autre compte, remplacer le nom par `IDENTIFIANT.github.io`. Si un dépôt de ce nom existe déjà, vérifier son contenu avant toute modification.
3. Déposer **le contenu extrait de l’archive** à la racine du dépôt, afin que `index.html` soit directement à la racine. Ne pas déposer uniquement le fichier ZIP.
4. Dans **Settings → Pages → Build and deployment**, choisir **Deploy from a branch**, puis **main** et **/(root)**. Enregistrer.
5. Attendre la réussite de la publication et ouvrir l’adresse indiquée par GitHub. Vérifier l’accueil, les trois autres pages et le lien du CV.

Les mêmes fichiers fonctionnent dans un dépôt de projet ordinaire, à une adresse de la forme `https://IDENTIFIANT.github.io/NOM-DU-DEPOT/`, grâce aux liens relatifs.

Référence officielle : <https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site>.

## Modifier le contenu

| Fichier | Contenu |
| --- | --- |
| `index.html` | Présentation, actualités, contact |
| `research.html` | Articles, prépublication, thèse, recherche et exposés |
| `teaching.html` | Cours actuel et enseignements précédents |
| `cv.html` | Parcours et téléchargement du CV |
| `assets/site.css` | Présentation du site |
| `assets/portrait.jpg` | Portrait repris du Google Site |
| `files/CV_Tinhinane_Amina_Azzouz.pdf` | CV proposé au téléchargement |
| `source/CV_Tinhinane_Amina_Azzouz.tex` | Source modifiable du CV |
| `files/publications.bib` | Bibliographie au format BibTeX |
| `SOURCES.md` | Sources et décisions de mise à jour |

Le nom exact de la feuille de style est aussi indiqué dans la balise `link` au début de chaque fichier HTML. Le site ne nécessite aucune étape de compilation. Une modification validée sur la branche publiée est prise en compte par GitHub Pages.

## Recompiler le CV

Avec une distribution LaTeX disposant des paquets déclarés dans le fichier source :

```sh
cd source
pdflatex CV_Tinhinane_Amina_Azzouz.tex
pdflatex CV_Tinhinane_Amina_Azzouz.tex
```

Copier ensuite le nouveau PDF dans `files/`, en conservant son nom. Les commandes du site et du CV sont indépendantes : publier le site ne nécessite pas LaTeX.

## Mise à jour éditoriale

La page Google Sites et l’ancien CV restent disponibles à leurs adresses d’origine. Le lien web dans le CV renvoie encore à la page existante tant que la nouvelle adresse GitHub n’a pas été publiée. Une fois le site en ligne, remplacer ce lien dans la source du CV, recompiler et déposer le PDF actualisé.

Les projets en cours conservent un statut de travaux en préparation. Les informations professionnelles reprises ici proviennent de pages publiques et du CV public d’origine. Le mois de début du postdoctorat YMSC diffère entre deux sources ; la période est donc indiquée comme **2021–2023**.
