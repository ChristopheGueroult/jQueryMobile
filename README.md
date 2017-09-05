# jQueryMobile

> Fichier de formation jQuery jMobile, niveau débutant et intermédiaire.


### Installation de Sublime Text et plugins
--------

-   Télécharger Sublime  Text à l'adresse suivante : [https://www.sublimetext.com/3](https://www.sublimetext.com/3)
-   Installer Package Control : [https://packagecontrol.io/installation](https://packagecontrol.io/installation)
-   Depuis Sublime Text, menu Tools > Command Palette, saisir install package et cliquer sur **Package Control:install package** pour installer les plugins (opération à reproduire pour chaque plugin).
-   Installer les Plugins Emmet, BraketHighlighter, Color Highlighter, Color Picker

### Installation de NodeJs
--------

- Télécharger et installer NodeJs (macOS Installer (.pkg) ou Windows Installer (.msi)) : [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
- Vérifier dans le Terminal à l'aide de la commande "node --version"

### Installation de lite-server
--------

- Documentation : [https://www.npmjs.com/package/lite-server](https://www.npmjs.com/package/lite-server)
- Créer un fichier package.json à la racine de votre projet
```json
{
  "scripts": {
    "dev": "lite-server"
  },
  "devDependencies": {
    "lite-server": "^2.3.0"
  }
}
```
- Terminal > lancer la commande : npm install -g lite-server pour installer lite-server en global.
- Terminal > placez vous sur votre projet : cd chemin/nom_du_projet
- Terminal > lancer la commande : npm install lite-server --save-dev (création automatique du dossier node_modules et installation des dépendences)
- Terminal > lancer la commande : npm run dev (ouvre un localhost dans le navigateur)


