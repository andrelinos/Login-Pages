
## Configurações do LiveSassCompile

Dentro das configurações do VSCode...

```json
{
  "liveSassCompile.settings.autoprefix": [],

  "liveSassCompile.settings.formats":[ 
    {
        "format": "expanded",
        "extensionName": ".css",
        "savePath": "css"
    },
    {
        "format": "compressed",
        "extensionName": ".min.css",
        "savePath": "css"
    },
  ],
  "liveSassCompile.settings.generateMap": false,

  // Opcional
  "liveSassCompile.settings.excludeList": [

    "**/node_modules/**",
    ".vscode/**",

    //adicione sua pasta aqui!!
    "/sua-pasta/**" 
  ],
}
```