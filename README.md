# Page personnelle de Tinhinane Amina Azzouz

Site académique statique en anglais, publié sur GitHub Pages et actualisé le 30 octobre 2026. L’archive comprend les quatre pages, le portrait repris de la page Google Sites, le CV PDF, sa source LaTeX et les références bibliographiques.

## Site en ligne

- **Site :** [https://tinaamina.github.io/](https://tinaamina.github.io/)
- **Dépôt :** [Tinaamina/Tinaamina.github.io](https://github.com/Tinaamina/Tinaamina.github.io)
- **CV :** [Télécharger le PDF](https://tinaamina.github.io/files/CV_Tinhinane_Amina_Azzouz.pdf)

GitHub Pages publie automatiquement la branche **main**, depuis le dossier **/(root)**. HTTPS est activé et imposé.

Pour consulter une copie locale, extraire l’archive et ouvrir `index.html` dans un navigateur. Les liens entre les pages et le téléchargement du CV fonctionnent également localement.

## Mettre le site à jour

1. Ouvrir le [dépôt GitHub](https://github.com/Tinaamina/Tinaamina.github.io) avec le compte `Tinaamina`.
2. Ouvrir le fichier à modifier, puis cliquer sur le crayon **Edit this file**. Modifier le texte en conservant les balises HTML autour de celui-ci.
3. Enregistrer avec **Commit changes** sur la branche **main**. Pour remplacer un PDF ou une image, utiliser **Add file → Upload files** dans le dossier correspondant, en conservant le nom du fichier.
4. Attendre la fin de la publication automatique, puis ouvrir la page concernée sur le site et vérifier les liens modifiés.

Le site ne nécessite aucune compilation ni dépendance externe. La configuration de publication est consultable dans **Settings → Pages** ; les déploiements apparaissent dans **Actions**. [Documentation GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

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

Les quatre pages utilisent la même feuille de style, `assets/site.css`. Les liens entre les fichiers sont relatifs : conserver leurs noms et leur emplacement lors des mises à jour.

## Recompiler le CV

Avec une distribution LaTeX disposant des paquets déclarés dans le fichier source :

```sh
cd source
pdflatex CV_Tinhinane_Amina_Azzouz.tex
pdflatex CV_Tinhinane_Amina_Azzouz.tex
```

Copier ensuite le nouveau PDF dans `files/`, en conservant son nom, puis mettre à jour le PDF et la source LaTeX dans le dépôt. Le lien « Research webpage » du CV renvoie à [https://tinaamina.github.io/](https://tinaamina.github.io/). Publier les pages HTML ne nécessite pas LaTeX.

## Mise à jour éditoriale

La page Google Sites et l’ancien CV restent disponibles à leurs adresses d’origine. Le site GitHub et le CV actualisé utilisent désormais la nouvelle adresse personnelle.

Les projets en cours conservent un statut de travaux en préparation. Les informations professionnelles reprises ici proviennent de pages publiques et du CV public d’origine. Le mois de début du postdoctorat YMSC diffère entre deux sources ; la période est donc indiquée comme **2021–2023**.
