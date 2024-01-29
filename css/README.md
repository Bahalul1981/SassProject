1. Go to settings then settings
2. Write live scass the go to
3. Live Sass Compile › Settings: Formats
4. Go to "Edit in settings.json" then remove all fromthere
   and pest all them below:

{
"workbench.colorTheme": "Visual Studio Dark",
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"explorer.compactFolders": false,
"liveSassCompile.settings.autoprefix": [],
"liveSassCompile.settings.forceBaseDirectory": "",
"liveSassCompile.settings.formats": [
{
//"format": "expanded", // for one line in all css style to get quick result
"format": "compressed",
"extensionName": ".min.css",
"savePath": null,
"savePathReplacementPairs": null
}
],
"liveSassCompile.settings.watchOnLaunch": true,
"liveSassCompile.settings.generateMap": false
}

5. One more chage in : Live Sass Compile › Settings: Generate Map
6. This line should be 'false': "liveSassCompile.settings.generateMap": false,
