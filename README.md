VSCode Configuration
====================

Ce trouve ici l'ensemble des informations pour la réinstallation complète de VSCode avec les modules et paramètres de base.

Module à installer
-----------------

### PHP
 - Intelephense
 - PHP Namespace Resolver
 - PHP DocBlocker
 - phpfmt - PHP Formatter
 - PHP Getters & Setters


### CSS / TWIG
 - Beautify
 - TWIG Pack

### AUTRE
 - Path Intellisense

<br />

Thèmes
-----------------

***Tinacious Design***
- Original
    - [GitHub](https://github.com/tinacious/atom-tinacious-design-syntax)
    - [MarketPlace](https://marketplace.visualstudio.com/items?itemName=tinaciousdesign.theme-tinaciousdesign)
- Personnalisé
    - [GitHub](https://github.com/MaximeGoncalves/TinaciousDeign) (Fichier .TmTheme personnalisé)

Côté VSCode il faut modifier les paramètres utilisateur :

    "workbench.colorCustomizations": {
        "diffEditor.insertedTextBackground": "#00D3641A",
        "diffEditor.removedTextBackground": "#FF339933",
        "tab.activeBackground": "#1D1D26",
        "tab.inactiveBackground": "#1D1D26",
        "activityBar.background": "#1D1D26",
        "editorError.foreground": "#9F5CFF",
        "editorGroup.background": "#0707eb",
        "editorGroupHeader.tabsBackground":"#1D1D26",
        "sideBar.background": "#1D1D26"
    },

Pour les icons télécharger le thème ***Monokai Pro*** ci-dessous :

Téléchagement : [Marketplace](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode)
<br>

    "workbench.iconTheme": "Monokai Pro (Filter Spectrum) Icons",





<br />

Paramètres Utilisateur
-----------------

Intégration du shell Windows :

    "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",

Permettre l'utilisation de PHP7  (Penser à changer la version si différentes)

    "php.validate.executablePath": "C:/wamp64/bin/php/php7.1.9/php.exe",

Pas besoin de l'intelisense de VSCode

    "php.suggest.basic": false,

