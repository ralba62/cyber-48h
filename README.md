# 48 h après l'attaque

Histoire interactive de cybersécurité pour la technologie en 3e (séquence 6, activité 3 : *Comment se protéger des menaces provenant du réseau Internet ?*).

Le site du collège et des comptes ENT viennent d'être piratés. En binôme, les élèves suivent **Claude**, élève de 3e, pendant 48 h et décident à sa place. Chaque mauvais choix montre ses conséquences, puis on peut **remonter le temps**.

| Chapitre | Notion | Questions du cahier | Code |
|---|---|---|---|
| 1. Le PC de la maison | Téléchargement, mises à jour, pare-feu et antivirus | Q1 a-b-c, Q2 | VIGILE |
| 2. La story de vacances | Traces volontaires et involontaires, objets connectés | Q1 d-e, Q3 | TRACES |
| 3. Le bandeau de cookies | RGPD, consentement | Q4 | CONSENTEMENT |
| 4. Le groupe de classe | Cyberviolence (Claude est témoin), 3018 | Q5 | TEMOIN |
| 5. La consultation en ligne | http / https, vérifier un site | Q6, Q7 | CADENAS |
| Bonus : le mail piège | Hameçonnage | Exercice 6 | HAMECON |

## À quoi servent les codes

Chaque code ne s'affiche **qu'une fois**, à la fin de son chapitre, et doit être noté sur la fiche. À la fin du jeu, le **dossier d'enquête** est verrouillé. Chaque code ouvre une pièce du dossier qui explique une partie de l'attaque : la faille, la collecte d'informations, la liste d'adresses, les comptes détournés, les mots de passe en clair. Le code bonus révèle le coupable, un mail d'hameçonnage. Le rapport final ne s'ouvre qu'une fois les 5 pièces débloquées.

## Fichiers

- `index.html` : l'appli complète en un seul fichier, sans dépendance et utilisable hors connexion.
- `Fiche_observations_48h.docx` : le carnet d'enquête de l'élève, à imprimer en recto-verso. Au recto, les élèves recopient les 12 infos que l'appli affiche dans les cartes « À noter » (définitions et bonnes pratiques) et les clés de chapitre. Au verso, ils préparent la trace écrite à partir de 6 débuts de phrases, puis remplissent une auto-évaluation.
- Le bouton **📒 Mes notes** de l'appli réaffiche les infos déjà rencontrées. Les clés n'y figurent pas.
- `Fiche_observations_48h_CORRIGE.docx` : le corrigé pour le professeur. **Ne pas le publier sur GitHub.**

## Mode professeur

- Cliquer **5 fois** sur le titre « 48 h après l'attaque », ou ajouter `#prof` à la fin de l'adresse.
- On peut alors aller directement à un chapitre, ouvrir le dossier verrouillé, afficher le rapport final (tout déverrouillé) ou remettre le poste à zéro. Les codes y sont aussi affichés.
- La progression est sauvegardée dans le navigateur de chaque poste.

## Mettre en ligne sur GitHub Pages, sans plugin

1. Sur github.com, cliquer sur **New repository**. Donner un nom (par ex. `cyber-48h`) et cocher **Public**.
2. Cliquer sur **uploading an existing file**, puis glisser **uniquement `index.html`** (et ce README si on veut). Valider avec **Commit changes**.
3. Aller dans **Settings → Pages**, puis choisir *Source : Deploy from a branch*, *Branch : main / (root)*, et cliquer sur **Save**.
4. Une à deux minutes plus tard, l'appli est disponible à l'adresse `https://<votre-identifiant>.github.io/cyber-48h/`.
