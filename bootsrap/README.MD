# Configuration SASS avec l'extension VS Code
Live Sass Compiler  
## Configuration de l'extension
ouvrir le fichier settings.json en passant par "Fichier/Préférences/Paramètres", puis cliquer sur l'un des liens mentionnant "Modifier dans settings.json" 

"liveSassCompile.settings.formats": [{
    "format": "expanded",
    "extensionName": ".css",
    "savePath": "~/../css/"
    },
    {
    "format": "compressed",
    "extensionName": ".min.css",
    "savePath": "~/../css/"
    }
],
