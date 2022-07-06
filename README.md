settings.json

{
    "liveSassCompile.settings.formats":[
       {
           "format": "expanded",
           "extensionName": ".css",
           "savePath": "/css"
       },
       {
           "extensionName": ".min.css",
           "format": "compressed",
           "savePath": "/css"
       }
   ],
   "liveSassCompile.settings.excludeList": [
      "**/node_modules/**",
      ".vscode/**"
   ],
   "liveSassCompile.settings.generateMap": true,
   "liveSassCompile.settings.autoprefix": [
       "> 1%",
       "last 2 versions"
   ]
}
