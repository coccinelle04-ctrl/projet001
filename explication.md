LES DOSSIERS
node_modules: contient toutes les bibliothèques installées par npm install (React, Vite, etc.). On ne le modifie jamais à la main, et on ne l’envoie pas sur GitHub.
public: fichiers statiques servis tels quels (favicon, images fixes). Ils sont accessibles directement par leur chemin, sans passer par le code.
src: le dossier où on écris le code. C’est l'espace de travail principal.
src/assets/ : les ressources utilisées dans tes composants (images, logos, icônes) que tu importes avec import.
Dans le dossier src
main.jsx : le point d’entrée de l’application. Il récupère la div avec l’id root dans index.html et y affiche le composant App. On y touche rarement.
App.jsx : le composant principal de ton application. C’est là que tu commences à coder ton interface.
App.css : les styles propres au composant App.
index.css : les styles globaux (appliqués à toute la page : police, marges, couleurs de base).
assets/hero.png, react.svg, vite.svg : des images d’exemple fournies avec le modèle de départ. Tu peux les supprimer quand tu nettoies le projet.
index.html : l’unique page HTML du projet (React est une application “single page”). Elle contient une div id="root" où React injecte tout le contenu, et charge main.jsx.
package.json : la carte d’identité du projet. Il liste le nom, les dépendances (React, Vite...) et les scripts (npm run dev, npm run build).
package-lock.json : verrouille les versions exactes des dépendances installées, pour que tout le monde ait les mêmes. Généré automatiquement.
vite.config.js : le fichier de configuration de Vite (plugins, port du serveur, etc.).
.gitignore : liste les fichiers que Git doit ignorer (par exemple node_modules).
.oxlintrc.json : la configuration de Oxlint, le linter que tu as choisi.
README.md : le fichier de documentation du projet (description, instructions d’installation).